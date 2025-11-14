[**10x-devs**](../../../../README.md)

***

[10x-devs](../../../../modules.md) / [prisma](../../../README.md) / [Prisma](../README.md) / NoteFindManyArgs

# Type Alias: NoteFindManyArgs\<ExtArgs\>

> **NoteFindManyArgs**\<`ExtArgs`\> = `object`

Defined in: prisma-main/types/index.d.ts:5909

Note findMany

## Type Parameters

### ExtArgs

`ExtArgs` *extends* `$Extensions.InternalArgs` = `$Extensions.DefaultArgs`

## Properties

### cursor?

> `optional` **cursor**: [`NoteWhereUniqueInput`](NoteWhereUniqueInput.md)

Defined in: prisma-main/types/index.d.ts:5937

[Cursor Docs](https://www.prisma.io/docs/concepts/components/prisma-client/pagination#cursor-based-pagination)

Sets the position for listing Notes.

***

### distinct?

> `optional` **distinct**: [`NoteScalarFieldEnum`](NoteScalarFieldEnum.md) \| [`NoteScalarFieldEnum`](NoteScalarFieldEnum.md)[]

Defined in: prisma-main/types/index.d.ts:5950

***

### include?

> `optional` **include**: [`NoteInclude`](NoteInclude.md)\<`ExtArgs`\> \| `null`

Defined in: prisma-main/types/index.d.ts:5921

Choose, which related nodes to fetch as well

***

### omit?

> `optional` **omit**: [`NoteOmit`](NoteOmit.md)\<`ExtArgs`\> \| `null`

Defined in: prisma-main/types/index.d.ts:5917

Omit specific fields from the Note

***

### orderBy?

> `optional` **orderBy**: [`NoteOrderByWithRelationInput`](NoteOrderByWithRelationInput.md) \| [`NoteOrderByWithRelationInput`](NoteOrderByWithRelationInput.md)[]

Defined in: prisma-main/types/index.d.ts:5931

[Sorting Docs](https://www.prisma.io/docs/concepts/components/prisma-client/sorting)

Determine the order of Notes to fetch.

***

### select?

> `optional` **select**: [`NoteSelect`](NoteSelect.md)\<`ExtArgs`\> \| `null`

Defined in: prisma-main/types/index.d.ts:5913

Select specific fields to fetch from the Note

***

### skip?

> `optional` **skip**: `number`

Defined in: prisma-main/types/index.d.ts:5949

[Pagination Docs](https://www.prisma.io/docs/concepts/components/prisma-client/pagination)

Skip the first `n` Notes.

***

### take?

> `optional` **take**: `number`

Defined in: prisma-main/types/index.d.ts:5943

[Pagination Docs](https://www.prisma.io/docs/concepts/components/prisma-client/pagination)

Take `±n` Notes from the position of the cursor.

***

### where?

> `optional` **where**: [`NoteWhereInput`](NoteWhereInput.md)

Defined in: prisma-main/types/index.d.ts:5925

Filter, which Notes to fetch.
