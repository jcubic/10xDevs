[**10x-devs**](../../../../README.md)

***

[10x-devs](../../../../modules.md) / [prisma](../../../README.md) / [Prisma](../README.md) / XOR

# Type Alias: XOR\<T, U\>

> **XOR**\<`T`, `U`\> = `T` *extends* `object` ? `U` *extends* `object` ? [`Without`](Without.md)\<`T`, `U`\> & `U` \| [`Without`](Without.md)\<`U`, `T`\> & `T` : `U` : `T`

Defined in: prisma-main/types/index.d.ts:430

XOR is needed to have a real mutually exclusive union type
https://stackoverflow.com/questions/42123407/does-typescript-support-mutually-exclusive-types

## Type Parameters

### T

`T`

### U

`U`
