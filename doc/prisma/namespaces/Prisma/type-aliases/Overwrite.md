[**10x-devs**](../../../../README.md)

***

[10x-devs](../../../../modules.md) / [prisma](../../../README.md) / [Prisma](../README.md) / Overwrite

# Type Alias: Overwrite\<O, O1\>

> **Overwrite**\<`O`, `O1`\> = `{ [K in keyof O]: K extends keyof O1 ? O1[K] : O[K] }` & `object`

Defined in: prisma-main/types/index.d.ts:500

## Type Parameters

### O

`O` *extends* `object`

### O1

`O1` *extends* `object`
