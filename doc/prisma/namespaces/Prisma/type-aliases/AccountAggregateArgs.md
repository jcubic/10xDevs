[**10x-devs**](../../../../README.md)

***

[10x-devs](../../../../modules.md) / [prisma](../../../README.md) / [Prisma](../README.md) / AccountAggregateArgs

# Type Alias: AccountAggregateArgs\<ExtArgs\>

> **AccountAggregateArgs**\<`ExtArgs`\> = `object`

Defined in: prisma-main/types/index.d.ts:3340

## Type Parameters

### ExtArgs

`ExtArgs` *extends* `$Extensions.InternalArgs` = `$Extensions.DefaultArgs`

## Properties

### \_count?

> `optional` **\_count**: `true` \| [`AccountCountAggregateInputType`](AccountCountAggregateInputType.md)

Defined in: prisma-main/types/index.d.ts:3374

[Aggregation Docs](https://www.prisma.io/docs/concepts/components/prisma-client/aggregations)

Count returned Accounts

***

### \_max?

> `optional` **\_max**: [`AccountMaxAggregateInputType`](AccountMaxAggregateInputType.md)

Defined in: prisma-main/types/index.d.ts:3386

[Aggregation Docs](https://www.prisma.io/docs/concepts/components/prisma-client/aggregations)

Select which fields to find the maximum value

***

### \_min?

> `optional` **\_min**: [`AccountMinAggregateInputType`](AccountMinAggregateInputType.md)

Defined in: prisma-main/types/index.d.ts:3380

[Aggregation Docs](https://www.prisma.io/docs/concepts/components/prisma-client/aggregations)

Select which fields to find the minimum value

***

### cursor?

> `optional` **cursor**: [`AccountWhereUniqueInput`](AccountWhereUniqueInput.md)

Defined in: prisma-main/types/index.d.ts:3356

[Cursor Docs](https://www.prisma.io/docs/concepts/components/prisma-client/pagination#cursor-based-pagination)

Sets the start position

***

### orderBy?

> `optional` **orderBy**: [`AccountOrderByWithRelationInput`](AccountOrderByWithRelationInput.md) \| [`AccountOrderByWithRelationInput`](AccountOrderByWithRelationInput.md)[]

Defined in: prisma-main/types/index.d.ts:3350

[Sorting Docs](https://www.prisma.io/docs/concepts/components/prisma-client/sorting)

Determine the order of Accounts to fetch.

***

### skip?

> `optional` **skip**: `number`

Defined in: prisma-main/types/index.d.ts:3368

[Pagination Docs](https://www.prisma.io/docs/concepts/components/prisma-client/pagination)

Skip the first `n` Accounts.

***

### take?

> `optional` **take**: `number`

Defined in: prisma-main/types/index.d.ts:3362

[Pagination Docs](https://www.prisma.io/docs/concepts/components/prisma-client/pagination)

Take `±n` Accounts from the position of the cursor.

***

### where?

> `optional` **where**: [`AccountWhereInput`](AccountWhereInput.md)

Defined in: prisma-main/types/index.d.ts:3344

Filter which Account to aggregate.
