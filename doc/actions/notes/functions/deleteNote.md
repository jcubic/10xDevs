[**10x-devs**](../../../README.md)

***

[10x-devs](../../../modules.md) / [actions/notes](../README.md) / deleteNote

# Function: deleteNote()

> **deleteNote**(`noteId`): `Promise`\<`void`\>

Defined in: [src/app/actions/notes.ts:368](https://github.com/jcubic/10xDevs/blob/8643271036ed0399a2b11ac87568ff44ec315445/src/app/actions/notes.ts#L368)

Deletes a note for the authenticated user.
Verifies ownership before deletion.

## Parameters

### noteId

`number`

Per-user note ID to delete

## Returns

`Promise`\<`void`\>

## Async

## Throws

'Unauthorized' if no active session

## Throws

'Note not found or access denied' if note doesn't exist or belongs to another user

## Throws

'Failed to delete note' for database errors

## Example

```tsx
await deleteNote(1);
console.log('Note deleted successfully');
```

## Remarks

- Requires active user session
- Uses compound key (noteId + userId) for ownership verification
- Deletion is permanent and cannot be undone
- Throws error if note doesn't exist or user doesn't own it
