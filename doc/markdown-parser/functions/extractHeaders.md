[**10x-devs**](../../README.md)

***

[10x-devs](../../modules.md) / [markdown-parser](../README.md) / extractHeaders

# Function: extractHeaders()

> **extractHeaders**(`content`): [`Header`](../../types/notes/interfaces/Header.md)[]

Defined in: [src/lib/markdown-parser.ts:57](https://github.com/jcubic/10xDevs/blob/8643271036ed0399a2b11ac87568ff44ec315445/src/lib/markdown-parser.ts#L57)

Extracts markdown headers from content using AST parsing.
Correctly handles headers inside code blocks by using a peggy-based parser.

## Parameters

### content

`string`

Markdown content to parse

## Returns

[`Header`](../../types/notes/interfaces/Header.md)[]

Array of header objects with metadata

## Example

```ts
const content = `
# Main Title
## Section 1
### Subsection
`;

const headers = extractHeaders(content);
// [
//   { id: 'header-0-1', text: 'Main Title', content: '# Main Title', line: 1 },
//   { id: 'header-1-2', text: 'Section 1', content: '## Section 1', line: 2 },
//   { id: 'header-2-3', text: 'Subsection', content: '### Subsection', line: 3 }
// ]
```

## Remarks

- Returns empty array if content is empty or null
- Header IDs are formatted as 'header-{index}-{level}'
- Text is trimmed and has leading '#' symbols removed
- Line numbers are 1-based (matching editor line numbers)
- Does not extract headers from code blocks or inline code
