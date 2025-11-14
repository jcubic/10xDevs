[**10x-devs**](../../../../README.md)

***

[10x-devs](../../../../modules.md) / [prisma](../../../README.md) / [Prisma](../README.md) / AccountUpsertArgs

# Type Alias: AccountUpsertArgs\<ExtArgs\>

> **AccountUpsertArgs**\<`ExtArgs`\> = `object`

Defined in: prisma-main/types/index.d.ts:4166

Account upsert

## Type Parameters

### ExtArgs

`ExtArgs` *extends* `$Extensions.InternalArgs` = `$Extensions.DefaultArgs`

## Properties

### create

> **create**: [`XOR`](XOR.md)\<[`AccountCreateInput`](AccountCreateInput.md), [`AccountUncheckedCreateInput`](AccountUncheckedCreateInput.md)\>

Defined in: prisma-main/types/index.d.ts:4186

In case the Account found by the `where` argument doesn't exist, create a new Account with this data.

***

### include?

> `optional` **include**: [`AccountInclude`](AccountInclude.md)\<`ExtArgs`\> \| `null`

Defined in: prisma-main/types/index.d.ts:4178

Choose, which related nodes to fetch as well

***

### omit?

> `optional` **omit**: [`AccountOmit`](AccountOmit.md)\<`ExtArgs`\> \| `null`

Defined in: prisma-main/types/index.d.ts:4174

Omit specific fields from the Account

***

### select?

> `optional` **select**: [`AccountSelect`](AccountSelect.md)\<`ExtArgs`\> \| `null`

Defined in: prisma-main/types/index.d.ts:4170

Select specific fields to fetch from the Account

***

### update

> **update**: [`XOR`](XOR.md)\<[`AccountUpdateInput`](AccountUpdateInput.md), [`AccountUncheckedUpdateInput`](AccountUncheckedUpdateInput.md)\>

Defined in: prisma-main/types/index.d.ts:4190

In case the Account was found with the provided `where` argument, update it with this data.

***

### where

> **where**: [`AccountWhereUniqueInput`](AccountWhereUniqueInput.md)

Defined in: prisma-main/types/index.d.ts:4182

The filter to search for the Account to update in case it exists.
