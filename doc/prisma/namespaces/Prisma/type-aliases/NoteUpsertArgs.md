[**10x-devs**](../../../../README.md)

***

[10x-devs](../../../../modules.md) / [prisma](../../../README.md) / [Prisma](../README.md) / NoteUpsertArgs

# Type Alias: NoteUpsertArgs\<ExtArgs\>

> **NoteUpsertArgs**\<`ExtArgs`\> = `object`

Defined in: prisma-main/types/index.d.ts:6033

Note upsert

## Type Parameters

### ExtArgs

`ExtArgs` *extends* `$Extensions.InternalArgs` = `$Extensions.DefaultArgs`

## Properties

### create

> **create**: [`XOR`](XOR.md)\<[`NoteCreateInput`](NoteCreateInput.md), [`NoteUncheckedCreateInput`](NoteUncheckedCreateInput.md)\>

Defined in: prisma-main/types/index.d.ts:6053

In case the Note found by the `where` argument doesn't exist, create a new Note with this data.

***

### include?

> `optional` **include**: [`NoteInclude`](NoteInclude.md)\<`ExtArgs`\> \| `null`

Defined in: prisma-main/types/index.d.ts:6045

Choose, which related nodes to fetch as well

***

### omit?

> `optional` **omit**: [`NoteOmit`](NoteOmit.md)\<`ExtArgs`\> \| `null`

Defined in: prisma-main/types/index.d.ts:6041

Omit specific fields from the Note

***

### select?

> `optional` **select**: [`NoteSelect`](NoteSelect.md)\<`ExtArgs`\> \| `null`

Defined in: prisma-main/types/index.d.ts:6037

Select specific fields to fetch from the Note

***

### update

> **update**: [`XOR`](XOR.md)\<[`NoteUpdateInput`](NoteUpdateInput.md), [`NoteUncheckedUpdateInput`](NoteUncheckedUpdateInput.md)\>

Defined in: prisma-main/types/index.d.ts:6057

In case the Note was found with the provided `where` argument, update it with this data.

***

### where

> **where**: [`NoteWhereUniqueInput`](NoteWhereUniqueInput.md)

Defined in: prisma-main/types/index.d.ts:6049

The filter to search for the Note to update in case it exists.
