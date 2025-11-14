[**10x-devs**](../../../README.md)

***

[10x-devs](../../../modules.md) / [actions/notes](../README.md) / getNote

# Function: getNote()

> **getNote**(`noteId`): `Promise`\<\{ `content`: `string` \| `null`; `createdAt`: `Date`; `name`: `string`; `noteId`: `number`; `updatedAt`: `Date`; `userId`: `string`; \} \| `null`\>

Defined in: [src/app/actions/notes.ts:433](https://github.com/jcubic/10xDevs/blob/8643271036ed0399a2b11ac87568ff44ec315445/src/app/actions/notes.ts#L433)

Retrieves a single note by ID for the authenticated user.

## Parameters

### noteId

`number`

Per-user note ID to fetch

## Returns

`Promise`\<\{ `content`: `string` \| `null`; `createdAt`: `Date`; `name`: `string`; `noteId`: `number`; `updatedAt`: `Date`; `userId`: `string`; \} \| `null`\>

Note object if found, null if not found

## Async

## Throws

'Unauthorized' if no active session

## Throws

'Failed to fetch note' for database errors

## Example

```tsx
const note = await getNote(1);
if (note) {
  console.log(`Found note: ${note.name}`);
} else {
  console.log('Note not found');
}
```

## Remarks

- Requires active user session
- Uses compound key (noteId + userId) for ownership verification
- Returns null if note doesn't exist (not an error)
- User can only fetch their own notes
