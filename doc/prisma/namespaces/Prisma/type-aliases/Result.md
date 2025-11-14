[**10x-devs**](../../../../README.md)

***

[10x-devs](../../../../modules.md) / [prisma](../../../README.md) / [Prisma](../README.md) / Result

# Type Alias: Result\<T, A, F\>

> **Result**\<`T`, `A`, `F`\> = `T` *extends* `object` ? `GetResult`\<`T`\[`symbol`\]\[`"types"`\]\[`"payload"`\], `A`, `F`\> : `GetResult`\<\{ `composites`: \{ \}; `name`: `""`; `objects`: \{ \}; `scalars`: \{ \}; \}, \{ \}, `F`\>

Defined in: prisma-main/types/runtime/library.d.ts:3215

## Type Parameters

### T

`T`

### A

`A`

### F

`F` *extends* `Operation`
