[**10x-devs**](../../../README.md)

***

[10x-devs](../../../modules.md) / [actions/notes](../README.md) / createNote

# Function: createNote()

> **createNote**(`baseName?`): `Promise`\<\{ `content`: `string` \| `null`; `createdAt`: `Date`; `name`: `string`; `noteId`: `number`; `updatedAt`: `Date`; `userId`: `string`; \}\>

Defined in: [src/app/actions/notes.ts:193](https://github.com/jcubic/10xDevs/blob/8643271036ed0399a2b11ac87568ff44ec315445/src/app/actions/notes.ts#L193)

Creates a new note for the authenticated user.
Automatically generates unique note names with counters for duplicates.

## Parameters

### baseName?

`string` = `'New Note'`

Base name for the note

## Returns

`Promise`\<\{ `content`: `string` \| `null`; `createdAt`: `Date`; `name`: `string`; `noteId`: `number`; `updatedAt`: `Date`; `userId`: `string`; \}\>

Created note with generated noteId and final name

## Async

## Throws

'Unauthorized' if no active session

## Throws

'Failed to create note' for database errors

## Example

```tsx
// Create with default name
const note1 = await createNote(); // name: 'New Note'
const note2 = await createNote(); // name: 'New Note 1'

// Create with custom name
const note3 = await createNote('My Project'); // name: 'My Project'
const note4 = await createNote('My Project'); // name: 'My Project 1'
```

## Remarks

- Requires active user session
- Note names are sanitized before storage
- If name exists, appends counter (e.g., "Note 1", "Note 2")
- noteId is per-user incremental (starts at 1 for each user)
- Uses database transaction for atomicity (prevents race conditions)
- Initial content is empty string (not null)
- Counter logic finds highest existing counter and increments
