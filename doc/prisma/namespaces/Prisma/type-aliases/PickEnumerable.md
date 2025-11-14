[**10x-devs**](../../../../README.md)

***

[10x-devs](../../../../modules.md) / [prisma](../../../README.md) / [Prisma](../README.md) / PickEnumerable

# Type Alias: PickEnumerable\<T, K\>

> **PickEnumerable**\<`T`, `K`\> = [`Prisma__Pick`](Prisma__Pick.md)\<`T`, [`MaybeTupleToUnion`](MaybeTupleToUnion.md)\<`K`\>\>

Defined in: prisma-main/types/index.d.ts:636

Like `Pick`, but additionally can also accept an array of keys

## Type Parameters

### T

`T`

### K

`K` *extends* [`Enumerable`](Enumerable.md)\<keyof `T`\> \| keyof `T`
