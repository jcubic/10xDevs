[**10x-devs**](../../../../README.md)

***

[10x-devs](../../../../modules.md) / [prisma](../../../README.md) / [Prisma](../README.md) / SessionUpdateManyArgs

# Type Alias: SessionUpdateManyArgs\<ExtArgs\>

> **SessionUpdateManyArgs**\<`ExtArgs`\> = `object`

Defined in: prisma-main/types/index.d.ts:3131

Session updateMany

## Type Parameters

### ExtArgs

`ExtArgs` *extends* `$Extensions.InternalArgs` = `$Extensions.DefaultArgs`

## Properties

### data

> **data**: [`XOR`](XOR.md)\<[`SessionUpdateManyMutationInput`](SessionUpdateManyMutationInput.md), [`SessionUncheckedUpdateManyInput`](SessionUncheckedUpdateManyInput.md)\>

Defined in: prisma-main/types/index.d.ts:3135

The data used to update Sessions.

***

### limit?

> `optional` **limit**: `number`

Defined in: prisma-main/types/index.d.ts:3143

Limit how many Sessions to update.

***

### where?

> `optional` **where**: [`SessionWhereInput`](SessionWhereInput.md)

Defined in: prisma-main/types/index.d.ts:3139

Filter which Sessions to update
