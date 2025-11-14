[**10x-devs**](../../../../README.md)

***

[10x-devs](../../../../modules.md) / [prisma](../../../README.md) / [Prisma](../README.md) / GetNoteAggregateType

# Type Alias: GetNoteAggregateType\<T\>

> **GetNoteAggregateType**\<`T`\> = \{ \[P in keyof T & keyof AggregateNote\]: P extends "\_count" \| "count" ? T\[P\] extends true ? number : GetScalarType\<T\[P\], AggregateNote\[P\]\> : GetScalarType\<T\[P\], AggregateNote\[P\]\> \}

Defined in: prisma-main/types/index.d.ts:5287

## Type Parameters

### T

`T` *extends* [`NoteAggregateArgs`](NoteAggregateArgs.md)
