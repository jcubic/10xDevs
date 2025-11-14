[**10x-devs**](../../README.md)

***

[10x-devs](../../modules.md) / actions/notes

# actions/notes

## Description

Server actions for note CRUD operations.
Provides functions for creating, reading, updating, and deleting user notes.
All operations are scoped to the authenticated user and include authorization checks.

## Dependencies

- @/lib/auth: Server-side authentication for user session
- @/lib/prisma: Database client with Note type
- next/headers: Server-side header access
- fs/promises: File system operations for welcome content

## Remarks

- All functions require active user session
- Note IDs are per-user (noteId is unique within userId scope)
- Uses compound keys (noteId + userId) for ownership verification
- Welcome content is cached in memory for performance
- Note names are sanitized to prevent invalid characters
- Duplicate note names get auto-incremented counters
- Transactions ensure atomicity for create operations

## Example

```tsx
import { getNotes, createNote, updateNote, deleteNote } from '@/app/actions/notes';

// Fetch all notes for current user
const notes = await getNotes();

// Create a new note
const newNote = await createNote('My New Note');

// Update note content
await updateNote(1, { content: 'Updated content' });

// Delete a note
await deleteNote(1);
```

## Functions

- [createNote](functions/createNote.md)
- [deleteNote](functions/deleteNote.md)
- [getNote](functions/getNote.md)
- [getNotes](functions/getNotes.md)
- [updateNote](functions/updateNote.md)
