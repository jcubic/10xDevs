[**10x-devs**](../../../../README.md)

***

[10x-devs](../../../../modules.md) / [prisma](../../../README.md) / [Prisma](../README.md) / NoteAggregateArgs

# Type Alias: NoteAggregateArgs\<ExtArgs\>

> **NoteAggregateArgs**\<`ExtArgs`\> = `object`

Defined in: prisma-main/types/index.d.ts:5226

## Type Parameters

### ExtArgs

`ExtArgs` *extends* `$Extensions.InternalArgs` = `$Extensions.DefaultArgs`

## Properties

### \_avg?

> `optional` **\_avg**: [`NoteAvgAggregateInputType`](NoteAvgAggregateInputType.md)

Defined in: prisma-main/types/index.d.ts:5266

[Aggregation Docs](https://www.prisma.io/docs/concepts/components/prisma-client/aggregations)

Select which fields to average

***

### \_count?

> `optional` **\_count**: `true` \| [`NoteCountAggregateInputType`](NoteCountAggregateInputType.md)

Defined in: prisma-main/types/index.d.ts:5260

[Aggregation Docs](https://www.prisma.io/docs/concepts/components/prisma-client/aggregations)

Count returned Notes

***

### \_max?

> `optional` **\_max**: [`NoteMaxAggregateInputType`](NoteMaxAggregateInputType.md)

Defined in: prisma-main/types/index.d.ts:5284

[Aggregation Docs](https://www.prisma.io/docs/concepts/components/prisma-client/aggregations)

Select which fields to find the maximum value

***

### \_min?

> `optional` **\_min**: [`NoteMinAggregateInputType`](NoteMinAggregateInputType.md)

Defined in: prisma-main/types/index.d.ts:5278

[Aggregation Docs](https://www.prisma.io/docs/concepts/components/prisma-client/aggregations)

Select which fields to find the minimum value

***

### \_sum?

> `optional` **\_sum**: [`NoteSumAggregateInputType`](NoteSumAggregateInputType.md)

Defined in: prisma-main/types/index.d.ts:5272

[Aggregation Docs](https://www.prisma.io/docs/concepts/components/prisma-client/aggregations)

Select which fields to sum

***

### cursor?

> `optional` **cursor**: [`NoteWhereUniqueInput`](NoteWhereUniqueInput.md)

Defined in: prisma-main/types/index.d.ts:5242

[Cursor Docs](https://www.prisma.io/docs/concepts/components/prisma-client/pagination#cursor-based-pagination)

Sets the start position

***

### orderBy?

> `optional` **orderBy**: [`NoteOrderByWithRelationInput`](NoteOrderByWithRelationInput.md) \| [`NoteOrderByWithRelationInput`](NoteOrderByWithRelationInput.md)[]

Defined in: prisma-main/types/index.d.ts:5236

[Sorting Docs](https://www.prisma.io/docs/concepts/components/prisma-client/sorting)

Determine the order of Notes to fetch.

***

### skip?

> `optional` **skip**: `number`

Defined in: prisma-main/types/index.d.ts:5254

[Pagination Docs](https://www.prisma.io/docs/concepts/components/prisma-client/pagination)

Skip the first `n` Notes.

***

### take?

> `optional` **take**: `number`

Defined in: prisma-main/types/index.d.ts:5248

[Pagination Docs](https://www.prisma.io/docs/concepts/components/prisma-client/pagination)

Take `±n` Notes from the position of the cursor.

***

### where?

> `optional` **where**: [`NoteWhereInput`](NoteWhereInput.md)

Defined in: prisma-main/types/index.d.ts:5230

Filter which Note to aggregate.
