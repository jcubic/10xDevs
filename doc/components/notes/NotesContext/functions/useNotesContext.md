[**10x-devs**](../../../../README.md)

***

[10x-devs](../../../../modules.md) / [components/notes/NotesContext](../README.md) / useNotesContext

# Function: useNotesContext()

> **useNotesContext**(): `NotesContextValue`

Defined in: [src/components/notes/NotesContext.tsx:140](https://github.com/jcubic/10xDevs/blob/8643271036ed0399a2b11ac87568ff44ec315445/src/components/notes/NotesContext.tsx#L140)

Hook to access NotesContext value in child components.

## Returns

`NotesContextValue`

Notes context value with state and operations

## Hook

## Throws

If used outside of NotesProvider

## Remarks

Must be used within a component wrapped by `<NotesProvider>`.
Throws error if context is undefined (not within provider).

## Example

```tsx
function NotesList() {
  const { notes, selectNote } = useNotesContext();

  return (
    <ul>
      {notes.map(note => (
        <li key={note.id} onClick={() => selectNote(note.id)}>
          {note.name}
        </li>
      ))}
    </ul>
  );
}
```
