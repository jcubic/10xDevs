[**10x-devs**](../../../../README.md)

***

[10x-devs](../../../../modules.md) / [prisma](../../../README.md) / [Prisma](../README.md) / GetVerificationAggregateType

# Type Alias: GetVerificationAggregateType\<T\>

> **GetVerificationAggregateType**\<`T`\> = \{ \[P in keyof T & keyof AggregateVerification\]: P extends "\_count" \| "count" ? T\[P\] extends true ? number : GetScalarType\<T\[P\], AggregateVerification\[P\]\> : GetScalarType\<T\[P\], AggregateVerification\[P\]\> \}

Defined in: prisma-main/types/index.d.ts:4364

## Type Parameters

### T

`T` *extends* [`VerificationAggregateArgs`](VerificationAggregateArgs.md)
