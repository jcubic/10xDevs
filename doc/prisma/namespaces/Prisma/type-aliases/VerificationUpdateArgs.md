[**10x-devs**](../../../../README.md)

***

[10x-devs](../../../../modules.md) / [prisma](../../../README.md) / [Prisma](../README.md) / VerificationUpdateArgs

# Type Alias: VerificationUpdateArgs\<ExtArgs\>

> **VerificationUpdateArgs**\<`ExtArgs`\> = `object`

Defined in: prisma-main/types/index.d.ts:5031

Verification update

## Type Parameters

### ExtArgs

`ExtArgs` *extends* `$Extensions.InternalArgs` = `$Extensions.DefaultArgs`

## Properties

### data

> **data**: [`XOR`](XOR.md)\<[`VerificationUpdateInput`](VerificationUpdateInput.md), [`VerificationUncheckedUpdateInput`](VerificationUncheckedUpdateInput.md)\>

Defined in: prisma-main/types/index.d.ts:5043

The data needed to update a Verification.

***

### omit?

> `optional` **omit**: [`VerificationOmit`](VerificationOmit.md)\<`ExtArgs`\> \| `null`

Defined in: prisma-main/types/index.d.ts:5039

Omit specific fields from the Verification

***

### select?

> `optional` **select**: [`VerificationSelect`](VerificationSelect.md)\<`ExtArgs`\> \| `null`

Defined in: prisma-main/types/index.d.ts:5035

Select specific fields to fetch from the Verification

***

### where

> **where**: [`VerificationWhereUniqueInput`](VerificationWhereUniqueInput.md)

Defined in: prisma-main/types/index.d.ts:5047

Choose, which Verification to update.
