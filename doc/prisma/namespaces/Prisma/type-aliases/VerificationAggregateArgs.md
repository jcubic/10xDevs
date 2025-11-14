[**10x-devs**](../../../../README.md)

***

[10x-devs](../../../../modules.md) / [prisma](../../../README.md) / [Prisma](../README.md) / VerificationAggregateArgs

# Type Alias: VerificationAggregateArgs\<ExtArgs\>

> **VerificationAggregateArgs**\<`ExtArgs`\> = `object`

Defined in: prisma-main/types/index.d.ts:4315

## Type Parameters

### ExtArgs

`ExtArgs` *extends* `$Extensions.InternalArgs` = `$Extensions.DefaultArgs`

## Properties

### \_count?

> `optional` **\_count**: `true` \| [`VerificationCountAggregateInputType`](VerificationCountAggregateInputType.md)

Defined in: prisma-main/types/index.d.ts:4349

[Aggregation Docs](https://www.prisma.io/docs/concepts/components/prisma-client/aggregations)

Count returned Verifications

***

### \_max?

> `optional` **\_max**: [`VerificationMaxAggregateInputType`](VerificationMaxAggregateInputType.md)

Defined in: prisma-main/types/index.d.ts:4361

[Aggregation Docs](https://www.prisma.io/docs/concepts/components/prisma-client/aggregations)

Select which fields to find the maximum value

***

### \_min?

> `optional` **\_min**: [`VerificationMinAggregateInputType`](VerificationMinAggregateInputType.md)

Defined in: prisma-main/types/index.d.ts:4355

[Aggregation Docs](https://www.prisma.io/docs/concepts/components/prisma-client/aggregations)

Select which fields to find the minimum value

***

### cursor?

> `optional` **cursor**: [`VerificationWhereUniqueInput`](VerificationWhereUniqueInput.md)

Defined in: prisma-main/types/index.d.ts:4331

[Cursor Docs](https://www.prisma.io/docs/concepts/components/prisma-client/pagination#cursor-based-pagination)

Sets the start position

***

### orderBy?

> `optional` **orderBy**: [`VerificationOrderByWithRelationInput`](VerificationOrderByWithRelationInput.md) \| [`VerificationOrderByWithRelationInput`](VerificationOrderByWithRelationInput.md)[]

Defined in: prisma-main/types/index.d.ts:4325

[Sorting Docs](https://www.prisma.io/docs/concepts/components/prisma-client/sorting)

Determine the order of Verifications to fetch.

***

### skip?

> `optional` **skip**: `number`

Defined in: prisma-main/types/index.d.ts:4343

[Pagination Docs](https://www.prisma.io/docs/concepts/components/prisma-client/pagination)

Skip the first `n` Verifications.

***

### take?

> `optional` **take**: `number`

Defined in: prisma-main/types/index.d.ts:4337

[Pagination Docs](https://www.prisma.io/docs/concepts/components/prisma-client/pagination)

Take `±n` Verifications from the position of the cursor.

***

### where?

> `optional` **where**: [`VerificationWhereInput`](VerificationWhereInput.md)

Defined in: prisma-main/types/index.d.ts:4319

Filter which Verification to aggregate.
