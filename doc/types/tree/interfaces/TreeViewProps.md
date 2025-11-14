[**10x-devs**](../../../README.md)

***

[10x-devs](../../../modules.md) / [types/tree](../README.md) / TreeViewProps

# Interface: TreeViewProps\<T\>

Defined in: [src/types/tree.ts:17](https://github.com/jcubic/10xDevs/blob/8643271036ed0399a2b11ac87568ff44ec315445/src/types/tree.ts#L17)

## Type Parameters

### T

`T` = `unknown`

## Properties

### data

> **data**: [`TreeNode`](TreeNode.md)\<`T`\>[]

Defined in: [src/types/tree.ts:18](https://github.com/jcubic/10xDevs/blob/8643271036ed0399a2b11ac87568ff44ec315445/src/types/tree.ts#L18)

***

### expandedNodeIds?

> `optional` **expandedNodeIds**: `string`[]

Defined in: [src/types/tree.ts:26](https://github.com/jcubic/10xDevs/blob/8643271036ed0399a2b11ac87568ff44ec315445/src/types/tree.ts#L26)

***

### generateName()?

> `optional` **generateName**: (`node`) => `string`

Defined in: [src/types/tree.ts:24](https://github.com/jcubic/10xDevs/blob/8643271036ed0399a2b11ac87568ff44ec315445/src/types/tree.ts#L24)

#### Parameters

##### node

[`TreeNode`](TreeNode.md)\<`T`\>

#### Returns

`string`

***

### generateTitle()?

> `optional` **generateTitle**: (`node`) => `string`

Defined in: [src/types/tree.ts:25](https://github.com/jcubic/10xDevs/blob/8643271036ed0399a2b11ac87568ff44ec315445/src/types/tree.ts#L25)

#### Parameters

##### node

[`TreeNode`](TreeNode.md)\<`T`\>

#### Returns

`string`

***

### onNodeCollapse()?

> `optional` **onNodeCollapse**: (`node`) => `void`

Defined in: [src/types/tree.ts:23](https://github.com/jcubic/10xDevs/blob/8643271036ed0399a2b11ac87568ff44ec315445/src/types/tree.ts#L23)

#### Parameters

##### node

[`TreeNode`](TreeNode.md)\<`T`\>

#### Returns

`void`

***

### onNodeDelete()?

> `optional` **onNodeDelete**: (`node`) => `void`

Defined in: [src/types/tree.ts:21](https://github.com/jcubic/10xDevs/blob/8643271036ed0399a2b11ac87568ff44ec315445/src/types/tree.ts#L21)

#### Parameters

##### node

[`TreeNode`](TreeNode.md)\<`T`\>

#### Returns

`void`

***

### onNodeExpand()?

> `optional` **onNodeExpand**: (`node`) => `void`

Defined in: [src/types/tree.ts:22](https://github.com/jcubic/10xDevs/blob/8643271036ed0399a2b11ac87568ff44ec315445/src/types/tree.ts#L22)

#### Parameters

##### node

[`TreeNode`](TreeNode.md)\<`T`\>

#### Returns

`void`

***

### onNodeRename()?

> `optional` **onNodeRename**: (`node`, `newName`) => `void`

Defined in: [src/types/tree.ts:20](https://github.com/jcubic/10xDevs/blob/8643271036ed0399a2b11ac87568ff44ec315445/src/types/tree.ts#L20)

#### Parameters

##### node

[`TreeNode`](TreeNode.md)\<`T`\>

##### newName

`string`

#### Returns

`void`

***

### onNodeSelect()?

> `optional` **onNodeSelect**: (`node`) => `void`

Defined in: [src/types/tree.ts:19](https://github.com/jcubic/10xDevs/blob/8643271036ed0399a2b11ac87568ff44ec315445/src/types/tree.ts#L19)

#### Parameters

##### node

[`TreeNode`](TreeNode.md)\<`T`\>

#### Returns

`void`

***

### title?

> `optional` **title**: `string`

Defined in: [src/types/tree.ts:27](https://github.com/jcubic/10xDevs/blob/8643271036ed0399a2b11ac87568ff44ec315445/src/types/tree.ts#L27)
