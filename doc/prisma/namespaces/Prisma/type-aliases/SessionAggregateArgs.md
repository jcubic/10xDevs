[**10x-devs**](../../../../README.md)

***

[10x-devs](../../../../modules.md) / [prisma](../../../README.md) / [Prisma](../README.md) / SessionAggregateArgs

# Type Alias: SessionAggregateArgs\<ExtArgs\>

> **SessionAggregateArgs**\<`ExtArgs`\> = `object`

Defined in: prisma-main/types/index.d.ts:2348

## Type Parameters

### ExtArgs

`ExtArgs` *extends* `$Extensions.InternalArgs` = `$Extensions.DefaultArgs`

## Properties

### \_count?

> `optional` **\_count**: `true` \| [`SessionCountAggregateInputType`](SessionCountAggregateInputType.md)

Defined in: prisma-main/types/index.d.ts:2382

[Aggregation Docs](https://www.prisma.io/docs/concepts/components/prisma-client/aggregations)

Count returned Sessions

***

### \_max?

> `optional` **\_max**: [`SessionMaxAggregateInputType`](SessionMaxAggregateInputType.md)

Defined in: prisma-main/types/index.d.ts:2394

[Aggregation Docs](https://www.prisma.io/docs/concepts/components/prisma-client/aggregations)

Select which fields to find the maximum value

***

### \_min?

> `optional` **\_min**: [`SessionMinAggregateInputType`](SessionMinAggregateInputType.md)

Defined in: prisma-main/types/index.d.ts:2388

[Aggregation Docs](https://www.prisma.io/docs/concepts/components/prisma-client/aggregations)

Select which fields to find the minimum value

***

### cursor?

> `optional` **cursor**: [`SessionWhereUniqueInput`](SessionWhereUniqueInput.md)

Defined in: prisma-main/types/index.d.ts:2364

[Cursor Docs](https://www.prisma.io/docs/concepts/components/prisma-client/pagination#cursor-based-pagination)

Sets the start position

***

### orderBy?

> `optional` **orderBy**: [`SessionOrderByWithRelationInput`](SessionOrderByWithRelationInput.md) \| [`SessionOrderByWithRelationInput`](SessionOrderByWithRelationInput.md)[]

Defined in: prisma-main/types/index.d.ts:2358

[Sorting Docs](https://www.prisma.io/docs/concepts/components/prisma-client/sorting)

Determine the order of Sessions to fetch.

***

### skip?

> `optional` **skip**: `number`

Defined in: prisma-main/types/index.d.ts:2376

[Pagination Docs](https://www.prisma.io/docs/concepts/components/prisma-client/pagination)

Skip the first `n` Sessions.

***

### take?

> `optional` **take**: `number`

Defined in: prisma-main/types/index.d.ts:2370

[Pagination Docs](https://www.prisma.io/docs/concepts/components/prisma-client/pagination)

Take `±n` Sessions from the position of the cursor.

***

### where?

> `optional` **where**: [`SessionWhereInput`](SessionWhereInput.md)

Defined in: prisma-main/types/index.d.ts:2352

Filter which Session to aggregate.
