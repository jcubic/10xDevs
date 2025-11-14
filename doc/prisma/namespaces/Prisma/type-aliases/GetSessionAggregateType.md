[**10x-devs**](../../../../README.md)

***

[10x-devs](../../../../modules.md) / [prisma](../../../README.md) / [Prisma](../README.md) / GetSessionAggregateType

# Type Alias: GetSessionAggregateType\<T\>

> **GetSessionAggregateType**\<`T`\> = \{ \[P in keyof T & keyof AggregateSession\]: P extends "\_count" \| "count" ? T\[P\] extends true ? number : GetScalarType\<T\[P\], AggregateSession\[P\]\> : GetScalarType\<T\[P\], AggregateSession\[P\]\> \}

Defined in: prisma-main/types/index.d.ts:2397

## Type Parameters

### T

`T` *extends* [`SessionAggregateArgs`](SessionAggregateArgs.md)
