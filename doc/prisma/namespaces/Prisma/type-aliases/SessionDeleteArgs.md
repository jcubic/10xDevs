[**10x-devs**](../../../../README.md)

***

[10x-devs](../../../../modules.md) / [prisma](../../../README.md) / [Prisma](../README.md) / SessionDeleteArgs

# Type Alias: SessionDeleteArgs\<ExtArgs\>

> **SessionDeleteArgs**\<`ExtArgs`\> = `object`

Defined in: prisma-main/types/index.d.ts:3179

Session delete

## Type Parameters

### ExtArgs

`ExtArgs` *extends* `$Extensions.InternalArgs` = `$Extensions.DefaultArgs`

## Properties

### include?

> `optional` **include**: [`SessionInclude`](SessionInclude.md)\<`ExtArgs`\> \| `null`

Defined in: prisma-main/types/index.d.ts:3191

Choose, which related nodes to fetch as well

***

### omit?

> `optional` **omit**: [`SessionOmit`](SessionOmit.md)\<`ExtArgs`\> \| `null`

Defined in: prisma-main/types/index.d.ts:3187

Omit specific fields from the Session

***

### select?

> `optional` **select**: [`SessionSelect`](SessionSelect.md)\<`ExtArgs`\> \| `null`

Defined in: prisma-main/types/index.d.ts:3183

Select specific fields to fetch from the Session

***

### where

> **where**: [`SessionWhereUniqueInput`](SessionWhereUniqueInput.md)

Defined in: prisma-main/types/index.d.ts:3195

Filter which Session to delete.
