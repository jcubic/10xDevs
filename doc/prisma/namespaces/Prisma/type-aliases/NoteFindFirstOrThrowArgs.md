[**10x-devs**](../../../../README.md)

***

[10x-devs](../../../../modules.md) / [prisma](../../../README.md) / [Prisma](../README.md) / NoteFindFirstOrThrowArgs

# Type Alias: NoteFindFirstOrThrowArgs\<ExtArgs\>

> **NoteFindFirstOrThrowArgs**\<`ExtArgs`\> = `object`

Defined in: prisma-main/types/index.d.ts:5857

Note findFirstOrThrow

## Type Parameters

### ExtArgs

`ExtArgs` *extends* `$Extensions.InternalArgs` = `$Extensions.DefaultArgs`

## Properties

### cursor?

> `optional` **cursor**: [`NoteWhereUniqueInput`](NoteWhereUniqueInput.md)

Defined in: prisma-main/types/index.d.ts:5885

[Cursor Docs](https://www.prisma.io/docs/concepts/components/prisma-client/pagination#cursor-based-pagination)

Sets the position for searching for Notes.

***

### distinct?

> `optional` **distinct**: [`NoteScalarFieldEnum`](NoteScalarFieldEnum.md) \| [`NoteScalarFieldEnum`](NoteScalarFieldEnum.md)[]

Defined in: prisma-main/types/index.d.ts:5903

[Distinct Docs](https://www.prisma.io/docs/concepts/components/prisma-client/distinct)

Filter by unique combinations of Notes.

***

### include?

> `optional` **include**: [`NoteInclude`](NoteInclude.md)\<`ExtArgs`\> \| `null`

Defined in: prisma-main/types/index.d.ts:5869

Choose, which related nodes to fetch as well

***

### omit?

> `optional` **omit**: [`NoteOmit`](NoteOmit.md)\<`ExtArgs`\> \| `null`

Defined in: prisma-main/types/index.d.ts:5865

Omit specific fields from the Note

***

### orderBy?

> `optional` **orderBy**: [`NoteOrderByWithRelationInput`](NoteOrderByWithRelationInput.md) \| [`NoteOrderByWithRelationInput`](NoteOrderByWithRelationInput.md)[]

Defined in: prisma-main/types/index.d.ts:5879

[Sorting Docs](https://www.prisma.io/docs/concepts/components/prisma-client/sorting)

Determine the order of Notes to fetch.

***

### select?

> `optional` **select**: [`NoteSelect`](NoteSelect.md)\<`ExtArgs`\> \| `null`

Defined in: prisma-main/types/index.d.ts:5861

Select specific fields to fetch from the Note

***

### skip?

> `optional` **skip**: `number`

Defined in: prisma-main/types/index.d.ts:5897

[Pagination Docs](https://www.prisma.io/docs/concepts/components/prisma-client/pagination)

Skip the first `n` Notes.

***

### take?

> `optional` **take**: `number`

Defined in: prisma-main/types/index.d.ts:5891

[Pagination Docs](https://www.prisma.io/docs/concepts/components/prisma-client/pagination)

Take `±n` Notes from the position of the cursor.

***

### where?

> `optional` **where**: [`NoteWhereInput`](NoteWhereInput.md)

Defined in: prisma-main/types/index.d.ts:5873

Filter, which Note to fetch.
