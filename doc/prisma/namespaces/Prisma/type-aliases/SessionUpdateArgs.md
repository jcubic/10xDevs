[**10x-devs**](../../../../README.md)

***

[10x-devs](../../../../modules.md) / [prisma](../../../README.md) / [Prisma](../README.md) / SessionUpdateArgs

# Type Alias: SessionUpdateArgs\<ExtArgs\>

> **SessionUpdateArgs**\<`ExtArgs`\> = `object`

Defined in: prisma-main/types/index.d.ts:3105

Session update

## Type Parameters

### ExtArgs

`ExtArgs` *extends* `$Extensions.InternalArgs` = `$Extensions.DefaultArgs`

## Properties

### data

> **data**: [`XOR`](XOR.md)\<[`SessionUpdateInput`](SessionUpdateInput.md), [`SessionUncheckedUpdateInput`](SessionUncheckedUpdateInput.md)\>

Defined in: prisma-main/types/index.d.ts:3121

The data needed to update a Session.

***

### include?

> `optional` **include**: [`SessionInclude`](SessionInclude.md)\<`ExtArgs`\> \| `null`

Defined in: prisma-main/types/index.d.ts:3117

Choose, which related nodes to fetch as well

***

### omit?

> `optional` **omit**: [`SessionOmit`](SessionOmit.md)\<`ExtArgs`\> \| `null`

Defined in: prisma-main/types/index.d.ts:3113

Omit specific fields from the Session

***

### select?

> `optional` **select**: [`SessionSelect`](SessionSelect.md)\<`ExtArgs`\> \| `null`

Defined in: prisma-main/types/index.d.ts:3109

Select specific fields to fetch from the Session

***

### where

> **where**: [`SessionWhereUniqueInput`](SessionWhereUniqueInput.md)

Defined in: prisma-main/types/index.d.ts:3125

Choose, which Session to update.
