[**10x-devs**](../../../../README.md)

***

[10x-devs](../../../../modules.md) / [prisma](../../../README.md) / [Prisma](../README.md) / VerificationUpsertArgs

# Type Alias: VerificationUpsertArgs\<ExtArgs\>

> **VerificationUpsertArgs**\<`ExtArgs`\> = `object`

Defined in: prisma-main/types/index.d.ts:5071

Verification upsert

## Type Parameters

### ExtArgs

`ExtArgs` *extends* `$Extensions.InternalArgs` = `$Extensions.DefaultArgs`

## Properties

### create

> **create**: [`XOR`](XOR.md)\<[`VerificationCreateInput`](VerificationCreateInput.md), [`VerificationUncheckedCreateInput`](VerificationUncheckedCreateInput.md)\>

Defined in: prisma-main/types/index.d.ts:5087

In case the Verification found by the `where` argument doesn't exist, create a new Verification with this data.

***

### omit?

> `optional` **omit**: [`VerificationOmit`](VerificationOmit.md)\<`ExtArgs`\> \| `null`

Defined in: prisma-main/types/index.d.ts:5079

Omit specific fields from the Verification

***

### select?

> `optional` **select**: [`VerificationSelect`](VerificationSelect.md)\<`ExtArgs`\> \| `null`

Defined in: prisma-main/types/index.d.ts:5075

Select specific fields to fetch from the Verification

***

### update

> **update**: [`XOR`](XOR.md)\<[`VerificationUpdateInput`](VerificationUpdateInput.md), [`VerificationUncheckedUpdateInput`](VerificationUncheckedUpdateInput.md)\>

Defined in: prisma-main/types/index.d.ts:5091

In case the Verification was found with the provided `where` argument, update it with this data.

***

### where

> **where**: [`VerificationWhereUniqueInput`](VerificationWhereUniqueInput.md)

Defined in: prisma-main/types/index.d.ts:5083

The filter to search for the Verification to update in case it exists.
