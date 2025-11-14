[**10x-devs**](../../../../README.md)

***

[10x-devs](../../../../modules.md) / [prisma](../../../README.md) / [Prisma](../README.md) / GetAccountAggregateType

# Type Alias: GetAccountAggregateType\<T\>

> **GetAccountAggregateType**\<`T`\> = \{ \[P in keyof T & keyof AggregateAccount\]: P extends "\_count" \| "count" ? T\[P\] extends true ? number : GetScalarType\<T\[P\], AggregateAccount\[P\]\> : GetScalarType\<T\[P\], AggregateAccount\[P\]\> \}

Defined in: prisma-main/types/index.d.ts:3389

## Type Parameters

### T

`T` *extends* [`AccountAggregateArgs`](AccountAggregateArgs.md)
