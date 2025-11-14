[**10x-devs**](../../../README.md)

***

[10x-devs](../../../modules.md) / [actions/notes](../README.md) / updateNote

# Function: updateNote()

> **updateNote**(`noteId`, `updates`): `Promise`\<\{ `content`: `string` \| `null`; `createdAt`: `Date`; `name`: `string`; `noteId`: `number`; `updatedAt`: `Date`; `userId`: `string`; \}\>

Defined in: [src/app/actions/notes.ts:296](https://github.com/jcubic/10xDevs/blob/8643271036ed0399a2b11ac87568ff44ec315445/src/app/actions/notes.ts#L296)

Updates an existing note's name or content.
Verifies ownership before allowing update.

## Parameters

### noteId

`number`

Per-user note ID to update

### updates

`Partial`\<`Pick`\<[`Note`](../../../prisma/type-aliases/Note.md), `"name"` \| `"content"`\>\>

Fields to update (name and/or content)

## Returns

`Promise`\<\{ `content`: `string` \| `null`; `createdAt`: `Date`; `name`: `string`; `noteId`: `number`; `updatedAt`: `Date`; `userId`: `string`; \}\>

Updated note with new updatedAt timestamp

## Async

## Throws

'Unauthorized' if no active session

## Throws

'Note not found or access denied' if note doesn't exist or belongs to another user

## Throws

'Failed to update note' for database errors

## Example

```tsx
// Update content only
await updateNote(1, { content: '# New Content' });

// Update name only
await updateNote(1, { name: 'Renamed Note' });

// Update both
await updateNote(1, { name: 'New Name', content: '# New Content' });
```

## Remarks

- Requires active user session
- Uses compound key (noteId + userId) for ownership verification
- Automatically updates updatedAt timestamp
- Partial updates allowed (can update name, content, or both)
- Returns full updated note object
