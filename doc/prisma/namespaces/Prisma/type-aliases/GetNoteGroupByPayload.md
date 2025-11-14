[**10x-devs**](../../../../README.md)

***

[10x-devs](../../../../modules.md) / [prisma](../../../README.md) / [Prisma](../README.md) / GetNoteGroupByPayload

# Type Alias: GetNoteGroupByPayload\<T\>

> **GetNoteGroupByPayload**\<`T`\> = [`PrismaPromise`](PrismaPromise.md)\<[`PickEnumerable`](PickEnumerable.md)\<[`NoteGroupByOutputType`](NoteGroupByOutputType.md), `T`\[`"by"`\]\> & `{ [P in keyof T & keyof NoteGroupByOutputType]: P extends "_count" ? T[P] extends boolean ? number : GetScalarType<T[P], NoteGroupByOutputType[P]> : GetScalarType<T[P], NoteGroupByOutputType[P]> }`[]\>

Defined in: prisma-main/types/index.d.ts:5326

## Type Parameters

### T

`T` *extends* [`NoteGroupByArgs`](NoteGroupByArgs.md)
