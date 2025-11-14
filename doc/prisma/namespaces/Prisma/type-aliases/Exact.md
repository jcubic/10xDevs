[**10x-devs**](../../../../README.md)

***

[10x-devs](../../../../modules.md) / [prisma](../../../README.md) / [Prisma](../README.md) / Exact

# Type Alias: Exact\<A, W\>

> **Exact**\<`A`, `W`\> = `A` *extends* `unknown` ? `W` *extends* `A` ? `{ [K in keyof A]: Exact<A[K], W[K]> }` : `W` : `never` \| `A` *extends* `Narrowable` ? `A` : `never`

Defined in: prisma-main/types/runtime/library.d.ts:1192

## Type Parameters

### A

`A`

### W

`W`
