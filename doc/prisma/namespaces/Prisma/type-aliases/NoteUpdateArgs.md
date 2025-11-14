[**10x-devs**](../../../../README.md)

***

[10x-devs](../../../../modules.md) / [prisma](../../../README.md) / [Prisma](../README.md) / NoteUpdateArgs

# Type Alias: NoteUpdateArgs\<ExtArgs\>

> **NoteUpdateArgs**\<`ExtArgs`\> = `object`

Defined in: prisma-main/types/index.d.ts:5989

Note update

## Type Parameters

### ExtArgs

`ExtArgs` *extends* `$Extensions.InternalArgs` = `$Extensions.DefaultArgs`

## Properties

### data

> **data**: [`XOR`](XOR.md)\<[`NoteUpdateInput`](NoteUpdateInput.md), [`NoteUncheckedUpdateInput`](NoteUncheckedUpdateInput.md)\>

Defined in: prisma-main/types/index.d.ts:6005

The data needed to update a Note.

***

### include?

> `optional` **include**: [`NoteInclude`](NoteInclude.md)\<`ExtArgs`\> \| `null`

Defined in: prisma-main/types/index.d.ts:6001

Choose, which related nodes to fetch as well

***

### omit?

> `optional` **omit**: [`NoteOmit`](NoteOmit.md)\<`ExtArgs`\> \| `null`

Defined in: prisma-main/types/index.d.ts:5997

Omit specific fields from the Note

***

### select?

> `optional` **select**: [`NoteSelect`](NoteSelect.md)\<`ExtArgs`\> \| `null`

Defined in: prisma-main/types/index.d.ts:5993

Select specific fields to fetch from the Note

***

### where

> **where**: [`NoteWhereUniqueInput`](NoteWhereUniqueInput.md)

Defined in: prisma-main/types/index.d.ts:6009

Choose, which Note to update.
