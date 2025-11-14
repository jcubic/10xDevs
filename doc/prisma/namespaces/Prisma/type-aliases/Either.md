[**10x-devs**](../../../../README.md)

***

[10x-devs](../../../../modules.md) / [prisma](../../../README.md) / [Prisma](../README.md) / \_\_Either

# Type Alias: \_\_Either\<O, K\>

> **\_\_Either**\<`O`, `K`\> = `Omit`\<`O`, `K`\> & `{ [P in K]: Prisma__Pick<O, P & keyof O> }`\[`K`\]

Defined in: prisma-main/types/index.d.ts:462

From ts-toolbelt

## Type Parameters

### O

`O` *extends* `object`

### K

`K` *extends* [`Key`](Key.md)
