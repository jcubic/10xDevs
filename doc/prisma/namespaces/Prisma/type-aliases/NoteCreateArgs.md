[**10x-devs**](../../../../README.md)

***

[10x-devs](../../../../modules.md) / [prisma](../../../README.md) / [Prisma](../README.md) / NoteCreateArgs

# Type Alias: NoteCreateArgs\<ExtArgs\>

> **NoteCreateArgs**\<`ExtArgs`\> = `object`

Defined in: prisma-main/types/index.d.ts:5956

Note create

## Type Parameters

### ExtArgs

`ExtArgs` *extends* `$Extensions.InternalArgs` = `$Extensions.DefaultArgs`

## Properties

### data

> **data**: [`XOR`](XOR.md)\<[`NoteCreateInput`](NoteCreateInput.md), [`NoteUncheckedCreateInput`](NoteUncheckedCreateInput.md)\>

Defined in: prisma-main/types/index.d.ts:5972

The data needed to create a Note.

***

### include?

> `optional` **include**: [`NoteInclude`](NoteInclude.md)\<`ExtArgs`\> \| `null`

Defined in: prisma-main/types/index.d.ts:5968

Choose, which related nodes to fetch as well

***

### omit?

> `optional` **omit**: [`NoteOmit`](NoteOmit.md)\<`ExtArgs`\> \| `null`

Defined in: prisma-main/types/index.d.ts:5964

Omit specific fields from the Note

***

### select?

> `optional` **select**: [`NoteSelect`](NoteSelect.md)\<`ExtArgs`\> \| `null`

Defined in: prisma-main/types/index.d.ts:5960

Select specific fields to fetch from the Note
