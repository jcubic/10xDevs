[**10x-devs**](../../../README.md)

***

[10x-devs](../../../modules.md) / [hooks/useNodeSelection](../README.md) / useNodeSelection

# Function: useNodeSelection()

> **useNodeSelection**(`initialNotes?`, `initialSelectedId?`): `object`

Defined in: [src/hooks/useNodeSelection.ts:88](https://github.com/jcubic/10xDevs/blob/8643271036ed0399a2b11ac87568ff44ec315445/src/hooks/useNodeSelection.ts#L88)

Custom hook for managing note selection and state in the note tree.
Provides state and functions for note selection, content updates, and dirty tracking.

## Parameters

### initialNotes?

[`NoteTreeNode`](../../../types/tree/type-aliases/NoteTreeNode.md)[] = `[]`

Initial array of note tree nodes

### initialSelectedId?

Initially selected note ID

`number` | `null`

## Returns

`object`

Hook state and updater functions

### notes

> **notes**: [`NoteTreeNode`](../../../types/tree/type-aliases/NoteTreeNode.md)[]

### saveStatus

> **saveStatus**: [`SaveStatus`](../../../types/notes/type-aliases/SaveStatus.md)

### selectedNoteId

> **selectedNoteId**: `number` \| `null`

### setNotes

> **setNotes**: `Dispatch`\<`SetStateAction`\<[`NoteTreeNode`](../../../types/tree/type-aliases/NoteTreeNode.md)[]\>\>

### setSaveStatus

> **setSaveStatus**: `Dispatch`\<`SetStateAction`\<[`SaveStatus`](../../../types/notes/type-aliases/SaveStatus.md)\>\>

### updateDirtyFlag()

> **updateDirtyFlag**: (`noteId`, `dirty`) => `void`

#### Parameters

##### noteId

`number`

##### dirty

`boolean`

#### Returns

`void`

### updateNoteContent()

> **updateNoteContent**: (`noteId`, `content`) => `void`

#### Parameters

##### noteId

`number`

##### content

`string`

#### Returns

`void`

### updateNoteName()

> **updateNoteName**: (`noteId`, `name`) => `void`

#### Parameters

##### noteId

`number`

##### name

`string`

#### Returns

`void`

### updateSelection()

> **updateSelection**: (`newSelectedId`) => `void`

#### Parameters

##### newSelectedId

`number` | `null`

#### Returns

`void`

## Example

```tsx
const {
  notes,
  selectedNoteId,
  updateSelection,
  updateNoteContent
} = useNodeSelection(initialNotes, 1);

// Select a different note
updateSelection(2);

// Update note content (marks as dirty)
updateNoteContent(2, '# New Content');
```

## Remarks

- updateSelection ensures only one note is selected at a time
- updateNoteContent automatically sets dirty flag to true
- All updater functions use useCallback for performance
- State updates are immutable (creates new arrays/objects)
- saveStatus is independent of note state (managed separately)
