[**10x-devs**](../../../README.md)

***

[10x-devs](../../../modules.md) / [components/Editor](../README.md) / default

# Variable: default

> `const` **default**: `NamedExoticComponent`\<[`EditorProps`](../../../types/editor/interfaces/EditorProps.md) & `RefAttributes`\<[`EditorRef`](../../../types/editor/interfaces/EditorRef.md)\>\>

Defined in: [src/components/Editor.tsx:148](https://github.com/jcubic/10xDevs/blob/8643271036ed0399a2b11ac87568ff44ec315445/src/components/Editor.tsx#L148)

CodeMirror 6-based markdown editor with syntax highlighting and line scrolling.

## Param

Editor configuration

## Param

Current editor content (default: '')

## Param

Callback when content changes

## Param

Placeholder text when editor is empty

## Param

Whether editor is read-only (default: false)

## Param

Line number to scroll to (1-based)

## Param

Additional CSS classes

## Param

Callback when editor API is ready

## Param

Callback for Cmd/Ctrl+S keyboard shortcut

## Param

Ref exposing editor API methods

## Returns

Rendered CodeMirror editor

## Remarks

**Line Scrolling:**
- Set `selectedLine` prop to scroll to a specific line (1-based index)
- Use `editorRef.current.scrollToLine(lineNumber)` for programmatic scrolling
- Scrolling waits for content to load and view to be ready
- Invalid line numbers are logged as warnings (no errors thrown)

**Editor Ref API:**
- `focus()` - Focus the editor
- `blur()` - Blur the editor
- `getValue()` - Get current content as string
- `setValue(value)` - Replace all content
- `scrollToLine(line)` - Scroll to line number (1-based)

**Theme:**
- Automatically switches between light/dark based on Chakra UI color mode
- Uses `basicLight` and `basicDark` themes from `@uiw/codemirror-theme-basic`

**Keyboard Shortcuts:**
- Cmd/Ctrl+S: Triggers `onSave` callback (prevents default browser save)

**Performance:**
- Memoized component to prevent unnecessary re-renders
- Extensions and theme are memoized to avoid recreation
- Uses `requestAnimationFrame` for smooth scrolling

## Example

```tsx
const editorRef = useRef<EditorRef>(null);

// Scroll to line 42
editorRef.current?.scrollToLine(42);

// Get current content
const content = editorRef.current?.getValue();

// Set new content
editorRef.current?.setValue('# New Content');
```
