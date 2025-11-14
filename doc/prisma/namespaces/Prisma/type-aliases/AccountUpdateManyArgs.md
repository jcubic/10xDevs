[**10x-devs**](../../../../README.md)

***

[10x-devs](../../../../modules.md) / [prisma](../../../README.md) / [Prisma](../README.md) / AccountUpdateManyArgs

# Type Alias: AccountUpdateManyArgs\<ExtArgs\>

> **AccountUpdateManyArgs**\<`ExtArgs`\> = `object`

Defined in: prisma-main/types/index.d.ts:4148

Account updateMany

## Type Parameters

### ExtArgs

`ExtArgs` *extends* `$Extensions.InternalArgs` = `$Extensions.DefaultArgs`

## Properties

### data

> **data**: [`XOR`](XOR.md)\<[`AccountUpdateManyMutationInput`](AccountUpdateManyMutationInput.md), [`AccountUncheckedUpdateManyInput`](AccountUncheckedUpdateManyInput.md)\>

Defined in: prisma-main/types/index.d.ts:4152

The data used to update Accounts.

***

### limit?

> `optional` **limit**: `number`

Defined in: prisma-main/types/index.d.ts:4160

Limit how many Accounts to update.

***

### where?

> `optional` **where**: [`AccountWhereInput`](AccountWhereInput.md)

Defined in: prisma-main/types/index.d.ts:4156

Filter which Accounts to update
