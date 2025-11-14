[**10x-devs**](../../README.md)

***

[10x-devs](../../modules.md) / hooks/useNodeSelection

# hooks/useNodeSelection

## Description

Custom React hook for managing note tree selection and state.
Provides centralized state management for note selection, content updates, dirty flags, and save status.

## Dependencies

- @/types/tree: NoteTreeNode type definition
- @/types/notes: SaveStatus type definition

## Remarks

- Used in NotesLayoutWrapper to manage note list and selection state
- Ensures only one note is selected at a time
- Tracks dirty flags for unsaved changes
- Optimized with useCallback to prevent unnecessary re-renders
- Immutable state updates for predictable behavior

## Example

```tsx
function NotesManager() {
  const {
    notes,
    selectedNoteId,
    saveStatus,
    updateSelection,
    updateNoteContent,
    updateDirtyFlag
  } = useNodeSelection(initialNotes, firstNoteId);

  return (
    <div>
      <NotesList notes={notes} onSelect={updateSelection} />
      <NoteEditor
        noteId={selectedNoteId}
        onChange={(content) => updateNoteContent(selectedNoteId, content)}
      />
    </div>
  );
}
```

## Functions

- [useNodeSelection](functions/useNodeSelection.md)
