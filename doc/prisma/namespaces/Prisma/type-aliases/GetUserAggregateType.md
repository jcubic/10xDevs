[**10x-devs**](../../../../README.md)

***

[10x-devs](../../../../modules.md) / [prisma](../../../README.md) / [Prisma](../README.md) / GetUserAggregateType

# Type Alias: GetUserAggregateType\<T\>

> **GetUserAggregateType**\<`T`\> = \{ \[P in keyof T & keyof AggregateUser\]: P extends "\_count" \| "count" ? T\[P\] extends true ? number : GetScalarType\<T\[P\], AggregateUser\[P\]\> : GetScalarType\<T\[P\], AggregateUser\[P\]\> \}

Defined in: prisma-main/types/index.d.ts:1358

## Type Parameters

### T

`T` *extends* [`UserAggregateArgs`](UserAggregateArgs.md)
