[**10x-devs**](../../../../README.md)

***

[10x-devs](../../../../modules.md) / [prisma](../../../README.md) / [Prisma](../README.md) / NoteFindUniqueOrThrowArgs

# Type Alias: NoteFindUniqueOrThrowArgs\<ExtArgs\>

> **NoteFindUniqueOrThrowArgs**\<`ExtArgs`\> = `object`

Defined in: prisma-main/types/index.d.ts:5783

Note findUniqueOrThrow

## Type Parameters

### ExtArgs

`ExtArgs` *extends* `$Extensions.InternalArgs` = `$Extensions.DefaultArgs`

## Properties

### include?

> `optional` **include**: [`NoteInclude`](NoteInclude.md)\<`ExtArgs`\> \| `null`

Defined in: prisma-main/types/index.d.ts:5795

Choose, which related nodes to fetch as well

***

### omit?

> `optional` **omit**: [`NoteOmit`](NoteOmit.md)\<`ExtArgs`\> \| `null`

Defined in: prisma-main/types/index.d.ts:5791

Omit specific fields from the Note

***

### select?

> `optional` **select**: [`NoteSelect`](NoteSelect.md)\<`ExtArgs`\> \| `null`

Defined in: prisma-main/types/index.d.ts:5787

Select specific fields to fetch from the Note

***

### where

> **where**: [`NoteWhereUniqueInput`](NoteWhereUniqueInput.md)

Defined in: prisma-main/types/index.d.ts:5799

Filter, which Note to fetch.
