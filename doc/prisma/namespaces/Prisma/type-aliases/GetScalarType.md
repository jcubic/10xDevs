[**10x-devs**](../../../../README.md)

***

[10x-devs](../../../../modules.md) / [prisma](../../../README.md) / [Prisma](../README.md) / GetScalarType

# Type Alias: GetScalarType\<T, O\>

> **GetScalarType**\<`T`, `O`\> = `O` *extends* `object` ? `{ [P in keyof T]: P extends keyof O ? O[P] : never }` : `never`

Defined in: prisma-main/types/index.d.ts:599

Used by group by

## Type Parameters

### T

`T`

### O

`O`
