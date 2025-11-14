[**10x-devs**](../../../../README.md)

***

[10x-devs](../../../../modules.md) / [prisma](../../../README.md) / [Prisma](../README.md) / UserUpdateManyArgs

# Type Alias: UserUpdateManyArgs\<ExtArgs\>

> **UserUpdateManyArgs**\<`ExtArgs`\> = `object`

Defined in: prisma-main/types/index.d.ts:2097

User updateMany

## Type Parameters

### ExtArgs

`ExtArgs` *extends* `$Extensions.InternalArgs` = `$Extensions.DefaultArgs`

## Properties

### data

> **data**: [`XOR`](XOR.md)\<[`UserUpdateManyMutationInput`](UserUpdateManyMutationInput.md), [`UserUncheckedUpdateManyInput`](UserUncheckedUpdateManyInput.md)\>

Defined in: prisma-main/types/index.d.ts:2101

The data used to update Users.

***

### limit?

> `optional` **limit**: `number`

Defined in: prisma-main/types/index.d.ts:2109

Limit how many Users to update.

***

### where?

> `optional` **where**: [`UserWhereInput`](UserWhereInput.md)

Defined in: prisma-main/types/index.d.ts:2105

Filter which Users to update
