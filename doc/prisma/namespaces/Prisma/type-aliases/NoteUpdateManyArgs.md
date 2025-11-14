[**10x-devs**](../../../../README.md)

***

[10x-devs](../../../../modules.md) / [prisma](../../../README.md) / [Prisma](../README.md) / NoteUpdateManyArgs

# Type Alias: NoteUpdateManyArgs\<ExtArgs\>

> **NoteUpdateManyArgs**\<`ExtArgs`\> = `object`

Defined in: prisma-main/types/index.d.ts:6015

Note updateMany

## Type Parameters

### ExtArgs

`ExtArgs` *extends* `$Extensions.InternalArgs` = `$Extensions.DefaultArgs`

## Properties

### data

> **data**: [`XOR`](XOR.md)\<[`NoteUpdateManyMutationInput`](NoteUpdateManyMutationInput.md), [`NoteUncheckedUpdateManyInput`](NoteUncheckedUpdateManyInput.md)\>

Defined in: prisma-main/types/index.d.ts:6019

The data used to update Notes.

***

### limit?

> `optional` **limit**: `number`

Defined in: prisma-main/types/index.d.ts:6027

Limit how many Notes to update.

***

### where?

> `optional` **where**: [`NoteWhereInput`](NoteWhereInput.md)

Defined in: prisma-main/types/index.d.ts:6023

Filter which Notes to update
