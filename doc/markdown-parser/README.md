[**10x-devs**](../README.md)

***

[10x-devs](../modules.md) / markdown-parser

# markdown-parser

## Description

Markdown header extraction using peggy-based parser.
Replaces regex-based parsing to correctly handle headers in code blocks.

## Dependencies

- @snapp-notes/markdown-parser: Peggy-based markdown parser for AST generation
- @/types/notes: Type definitions for Header objects

## Remarks

- Uses peggy parser to build AST, avoiding false positives from code blocks
- Extracts line numbers for navigation and scrolling features
- Generates unique IDs for each header based on index and level

## Example

```ts
const markdown = '# Title\n\n## Section\n\n```md\n# Not a header\n```';
const headers = extractHeaders(markdown);
// Returns only the real headers, not the one in code block
```

## Functions

- [extractHeaders](functions/extractHeaders.md)
