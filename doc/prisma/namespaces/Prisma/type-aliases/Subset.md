[**10x-devs**](../../../../README.md)

***

[10x-devs](../../../../modules.md) / [prisma](../../../README.md) / [Prisma](../README.md) / Subset

# Type Alias: Subset\<T, U\>

> **Subset**\<`T`, `U`\> = `{ [key in keyof T]: key extends keyof U ? T[key] : never }`

Defined in: prisma-main/types/index.d.ts:397

Subset

## Type Parameters

### T

`T`

### U

`U`

## Desc

From `T` pick properties that exist in `U`. Simple version of Intersection
