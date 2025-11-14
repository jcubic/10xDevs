[**10x-devs**](../../../README.md)

***

[10x-devs](../../../modules.md) / [actions/notes](../README.md) / getNotes

# Function: getNotes()

> **getNotes**(): `Promise`\<`object`[]\>

Defined in: [src/app/actions/notes.ts:102](https://github.com/jcubic/10xDevs/blob/8643271036ed0399a2b11ac87568ff44ec315445/src/app/actions/notes.ts#L102)

Retrieves all notes for the currently authenticated user.
Returns notes ordered by creation date with welcome content for null content.

## Returns

`Promise`\<`object`[]\>

Array of user's notes, empty array if not authenticated

## Async

## Example

```tsx
const notes = await getNotes();
console.log(`User has ${notes.length} notes`);
```

## Remarks

- Requires active user session
- Returns empty array if user is not authenticated (no error thrown)
- Notes ordered by createdAt ascending (oldest first)
- Null content is replaced with welcome.md content
- Welcome content comes from public/samples/welcome.md
