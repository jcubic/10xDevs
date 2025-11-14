[**10x-devs**](../../../README.md)

***

[10x-devs](../../../modules.md) / components/notes/NotesContext

# components/notes/NotesContext

## Description

React Context for managing global notes state with URL synchronization.
Provides notes tree, selection state, save status, and CRUD operations to all child components.

## Dependencies

- `next/navigation` - usePathname and useRouter for URL-based routing
- `@/hooks/useNodeSelection` - Core state management hook for notes
- `@/types/tree` - NoteTreeNode type definition
- `@/types/notes` - SaveStatus type definition

## Remarks

**Features:**
- Global notes tree state (flat array of notes with selection flags)
- Selected note tracking with URL synchronization
- Save status management (saving, saved, error, unsaved)
- Note CRUD operations (update content, update name, mark dirty)
- Auto-select first note when navigating to root
- Next.js router integration for note navigation

**URL Synchronization:**
- `/note/:id` routes automatically sync to context state
- `selectNote(id)` updates both state and URL
- Browser back/forward buttons work correctly
- Initial note selection from URL on mount

**State Management:**
- Uses `useNodeSelection` hook for core logic
- Context wraps hook state for global access
- Initial state from server-side props (SSR-friendly)
- Automatically syncs when initial props change

**Performance:**
- Memoized callbacks to prevent unnecessary re-renders
- Selective updates (only changed notes re-render)
- useCallback for all functions to stabilize references

## Example

```tsx
import { NotesProvider, useNotesContext } from '@/components/notes/NotesContext';

// Wrap app with provider
export default function NotesLayout({ children, initialNotes }) {
  return (
    <NotesProvider initialNotes={initialNotes}>
      {children}
    </NotesProvider>
  );
}

// Use context in child component
function NoteEditor() {
  const {
    notes,
    selectedNoteId,
    updateNoteContent,
    saveStatus
  } = useNotesContext();

  const selectedNote = notes.find(n => n.id === selectedNoteId);

  return (
    <Editor
      value={selectedNote?.data?.content || ''}
      onChange={(content) => updateNoteContent(selectedNoteId!, content)}
      saveStatus={saveStatus}
    />
  );
}
```

## Functions

- [NotesProvider](functions/NotesProvider.md)
- [useNotesContext](functions/useNotesContext.md)
