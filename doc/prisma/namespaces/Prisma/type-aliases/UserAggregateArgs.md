[**10x-devs**](../../../../README.md)

***

[10x-devs](../../../../modules.md) / [prisma](../../../README.md) / [Prisma](../README.md) / UserAggregateArgs

# Type Alias: UserAggregateArgs\<ExtArgs\>

> **UserAggregateArgs**\<`ExtArgs`\> = `object`

Defined in: prisma-main/types/index.d.ts:1309

## Type Parameters

### ExtArgs

`ExtArgs` *extends* `$Extensions.InternalArgs` = `$Extensions.DefaultArgs`

## Properties

### \_count?

> `optional` **\_count**: `true` \| [`UserCountAggregateInputType`](UserCountAggregateInputType.md)

Defined in: prisma-main/types/index.d.ts:1343

[Aggregation Docs](https://www.prisma.io/docs/concepts/components/prisma-client/aggregations)

Count returned Users

***

### \_max?

> `optional` **\_max**: [`UserMaxAggregateInputType`](UserMaxAggregateInputType.md)

Defined in: prisma-main/types/index.d.ts:1355

[Aggregation Docs](https://www.prisma.io/docs/concepts/components/prisma-client/aggregations)

Select which fields to find the maximum value

***

### \_min?

> `optional` **\_min**: [`UserMinAggregateInputType`](UserMinAggregateInputType.md)

Defined in: prisma-main/types/index.d.ts:1349

[Aggregation Docs](https://www.prisma.io/docs/concepts/components/prisma-client/aggregations)

Select which fields to find the minimum value

***

### cursor?

> `optional` **cursor**: [`UserWhereUniqueInput`](UserWhereUniqueInput.md)

Defined in: prisma-main/types/index.d.ts:1325

[Cursor Docs](https://www.prisma.io/docs/concepts/components/prisma-client/pagination#cursor-based-pagination)

Sets the start position

***

### orderBy?

> `optional` **orderBy**: [`UserOrderByWithRelationInput`](UserOrderByWithRelationInput.md) \| [`UserOrderByWithRelationInput`](UserOrderByWithRelationInput.md)[]

Defined in: prisma-main/types/index.d.ts:1319

[Sorting Docs](https://www.prisma.io/docs/concepts/components/prisma-client/sorting)

Determine the order of Users to fetch.

***

### skip?

> `optional` **skip**: `number`

Defined in: prisma-main/types/index.d.ts:1337

[Pagination Docs](https://www.prisma.io/docs/concepts/components/prisma-client/pagination)

Skip the first `n` Users.

***

### take?

> `optional` **take**: `number`

Defined in: prisma-main/types/index.d.ts:1331

[Pagination Docs](https://www.prisma.io/docs/concepts/components/prisma-client/pagination)

Take `±n` Users from the position of the cursor.

***

### where?

> `optional` **where**: [`UserWhereInput`](UserWhereInput.md)

Defined in: prisma-main/types/index.d.ts:1313

Filter which User to aggregate.
