[**10x-devs**](../../../../README.md)

***

[10x-devs](../../../../modules.md) / [prisma](../../../README.md) / [Prisma](../README.md) / FieldPaths

# Type Alias: FieldPaths\<T, U\>

> **FieldPaths**\<`T`, `U`\> = [`IsObject`](IsObject.md)\<`T`\> *extends* [`True`](True.md) ? `U` : `T`

Defined in: prisma-main/types/index.d.ts:605

## Type Parameters

### T

`T`

### U

`U` = `Omit`\<`T`, `"_avg"` \| `"_sum"` \| `"_count"` \| `"_min"` \| `"_max"`\>
