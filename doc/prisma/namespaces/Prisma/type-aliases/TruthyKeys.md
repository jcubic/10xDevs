[**10x-devs**](../../../../README.md)

***

[10x-devs](../../../../modules.md) / [prisma](../../../README.md) / [Prisma](../README.md) / TruthyKeys

# Type Alias: TruthyKeys\<T\>

> **TruthyKeys**\<`T`\> = keyof \{ \[K in keyof T as T\[K\] extends false \| undefined \| null ? never : K\]: K \}

Defined in: prisma-main/types/index.d.ts:387

## Type Parameters

### T

`T`
