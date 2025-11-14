[**10x-devs**](../../../../README.md)

***

[10x-devs](../../../../modules.md) / [components/notes/NotesContext](../README.md) / NotesProvider

# Function: NotesProvider()

> **NotesProvider**(`props`): `Element`

Defined in: [src/components/notes/NotesContext.tsx:216](https://github.com/jcubic/10xDevs/blob/8643271036ed0399a2b11ac87568ff44ec315445/src/components/notes/NotesContext.tsx#L216)

Notes context provider with URL synchronization and auto-selection.

## Parameters

### props

`NotesProviderProps`

Provider configuration

## Returns

`Element`

Provider wrapping children

## Component

## Remarks

**Initialization:**
- Accepts `initialNotes` from server-side props (SSR)
- Accepts `initialSelectedNoteId` to pre-select a note
- Syncs initial state when props change (e.g., after navigation)

**URL Synchronization:**
- Watches pathname for `/note/:id` pattern
- Updates selection state when URL changes (e.g., browser back/forward)
- `selectNote()` updates both state and URL via Next.js router

**Auto-selection:**
- If at root (`/`) with notes available and none selected, auto-selects first note
- Automatically navigates to `/note/:id` after auto-selection
- Prevents empty state when notes exist

**State Management:**
- Uses `useNodeSelection` hook for core state logic
- Exposes state and operations via context value
- Memoized callbacks to prevent unnecessary re-renders

**Operations:**
- `updateNoteContent`: Updates content and marks as dirty
- `updateNoteName`: Updates name and marks as dirty
- `markNoteDirty`: Sets dirty flag (true = unsaved changes)
- `selectNote`: Updates selection and navigates to URL
- `getSelectedNote`: Returns currently selected note object
- `getNote`: Returns note by ID

## Example

```tsx
// In layout component
export default async function NotesLayout({ children }) {
  const notes = await getNotes();
  const selectedId = getSelectedNoteIdFromUrl();

  return (
    <NotesProvider
      initialNotes={notes}
      initialSelectedNoteId={selectedId}
    >
      {children}
    </NotesProvider>
  );
}
```
