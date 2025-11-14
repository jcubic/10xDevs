[**10x-devs**](../../../../README.md)

***

[10x-devs](../../../../modules.md) / [prisma](../../../README.md) / [Prisma](../README.md) / AccountUpdateArgs

# Type Alias: AccountUpdateArgs\<ExtArgs\>

> **AccountUpdateArgs**\<`ExtArgs`\> = `object`

Defined in: prisma-main/types/index.d.ts:4122

Account update

## Type Parameters

### ExtArgs

`ExtArgs` *extends* `$Extensions.InternalArgs` = `$Extensions.DefaultArgs`

## Properties

### data

> **data**: [`XOR`](XOR.md)\<[`AccountUpdateInput`](AccountUpdateInput.md), [`AccountUncheckedUpdateInput`](AccountUncheckedUpdateInput.md)\>

Defined in: prisma-main/types/index.d.ts:4138

The data needed to update a Account.

***

### include?

> `optional` **include**: [`AccountInclude`](AccountInclude.md)\<`ExtArgs`\> \| `null`

Defined in: prisma-main/types/index.d.ts:4134

Choose, which related nodes to fetch as well

***

### omit?

> `optional` **omit**: [`AccountOmit`](AccountOmit.md)\<`ExtArgs`\> \| `null`

Defined in: prisma-main/types/index.d.ts:4130

Omit specific fields from the Account

***

### select?

> `optional` **select**: [`AccountSelect`](AccountSelect.md)\<`ExtArgs`\> \| `null`

Defined in: prisma-main/types/index.d.ts:4126

Select specific fields to fetch from the Account

***

### where

> **where**: [`AccountWhereUniqueInput`](AccountWhereUniqueInput.md)

Defined in: prisma-main/types/index.d.ts:4142

Choose, which Account to update.
