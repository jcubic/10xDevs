[**10x-devs**](../../../README.md)

***

[10x-devs](../../../modules.md) / [types/editor](../README.md) / EditorProps

# Interface: EditorProps

Defined in: [src/types/editor.ts:1](https://github.com/jcubic/10xDevs/blob/8643271036ed0399a2b11ac87568ff44ec315445/src/types/editor.ts#L1)

## Properties

### basicSetup?

> `optional` **basicSetup**: `object`

Defined in: [src/types/editor.ts:10](https://github.com/jcubic/10xDevs/blob/8643271036ed0399a2b11ac87568ff44ec315445/src/types/editor.ts#L10)

#### allowMultipleSelections?

> `optional` **allowMultipleSelections**: `boolean`

#### autocompletion?

> `optional` **autocompletion**: `boolean`

#### bracketMatching?

> `optional` **bracketMatching**: `boolean`

#### closeBrackets?

> `optional` **closeBrackets**: `boolean`

#### crosshairCursor?

> `optional` **crosshairCursor**: `boolean`

#### dropCursor?

> `optional` **dropCursor**: `boolean`

#### foldGutter?

> `optional` **foldGutter**: `boolean`

#### highlightActiveLine?

> `optional` **highlightActiveLine**: `boolean`

#### highlightActiveLineGutter?

> `optional` **highlightActiveLineGutter**: `boolean`

#### highlightSelectionMatches?

> `optional` **highlightSelectionMatches**: `boolean`

#### indentOnInput?

> `optional` **indentOnInput**: `boolean`

#### lineNumbers?

> `optional` **lineNumbers**: `boolean`

#### rectangularSelection?

> `optional` **rectangularSelection**: `boolean`

#### searchKeymap?

> `optional` **searchKeymap**: `boolean`

#### tabSize?

> `optional` **tabSize**: `number`

***

### className?

> `optional` **className**: `string`

Defined in: [src/types/editor.ts:27](https://github.com/jcubic/10xDevs/blob/8643271036ed0399a2b11ac87568ff44ec315445/src/types/editor.ts#L27)

***

### height?

> `optional` **height**: `string`

Defined in: [src/types/editor.ts:5](https://github.com/jcubic/10xDevs/blob/8643271036ed0399a2b11ac87568ff44ec315445/src/types/editor.ts#L5)

***

### onChange()?

> `optional` **onChange**: (`value`) => `void`

Defined in: [src/types/editor.ts:3](https://github.com/jcubic/10xDevs/blob/8643271036ed0399a2b11ac87568ff44ec315445/src/types/editor.ts#L3)

#### Parameters

##### value

`string`

#### Returns

`void`

***

### onEditorReady()?

> `optional` **onEditorReady**: (`editorRef`) => `void`

Defined in: [src/types/editor.ts:28](https://github.com/jcubic/10xDevs/blob/8643271036ed0399a2b11ac87568ff44ec315445/src/types/editor.ts#L28)

#### Parameters

##### editorRef

[`EditorRef`](EditorRef.md)

#### Returns

`void`

***

### onSave()?

> `optional` **onSave**: () => `void`

Defined in: [src/types/editor.ts:29](https://github.com/jcubic/10xDevs/blob/8643271036ed0399a2b11ac87568ff44ec315445/src/types/editor.ts#L29)

#### Returns

`void`

***

### placeholder?

> `optional` **placeholder**: `string`

Defined in: [src/types/editor.ts:4](https://github.com/jcubic/10xDevs/blob/8643271036ed0399a2b11ac87568ff44ec315445/src/types/editor.ts#L4)

***

### readOnly?

> `optional` **readOnly**: `boolean`

Defined in: [src/types/editor.ts:7](https://github.com/jcubic/10xDevs/blob/8643271036ed0399a2b11ac87568ff44ec315445/src/types/editor.ts#L7)

***

### selectedLine?

> `optional` **selectedLine**: `number`

Defined in: [src/types/editor.ts:8](https://github.com/jcubic/10xDevs/blob/8643271036ed0399a2b11ac87568ff44ec315445/src/types/editor.ts#L8)

***

### value?

> `optional` **value**: `string`

Defined in: [src/types/editor.ts:2](https://github.com/jcubic/10xDevs/blob/8643271036ed0399a2b11ac87568ff44ec315445/src/types/editor.ts#L2)

***

### width?

> `optional` **width**: `string`

Defined in: [src/types/editor.ts:6](https://github.com/jcubic/10xDevs/blob/8643271036ed0399a2b11ac87568ff44ec315445/src/types/editor.ts#L6)
