[**10x-devs**](../../../../README.md)

***

[10x-devs](../../../../modules.md) / [prisma](../../../README.md) / [Prisma](../README.md) / AccountWhereInput

# Type Alias: AccountWhereInput

> **AccountWhereInput** = `object`

Defined in: prisma-main/types/index.d.ts:6455

## Properties

### accessToken?

> `optional` **accessToken**: [`StringNullableFilter`](StringNullableFilter.md)\<`"Account"`\> \| `string` \| `null`

Defined in: prisma-main/types/index.d.ts:6463

***

### accessTokenExpiresAt?

> `optional` **accessTokenExpiresAt**: [`DateTimeNullableFilter`](DateTimeNullableFilter.md)\<`"Account"`\> \| `Date` \| `string` \| `null`

Defined in: prisma-main/types/index.d.ts:6466

***

### accountId?

> `optional` **accountId**: [`StringFilter`](StringFilter.md)\<`"Account"`\> \| `string`

Defined in: prisma-main/types/index.d.ts:6460

***

### AND?

> `optional` **AND**: `AccountWhereInput` \| `AccountWhereInput`[]

Defined in: prisma-main/types/index.d.ts:6456

***

### createdAt?

> `optional` **createdAt**: [`DateTimeFilter`](DateTimeFilter.md)\<`"Account"`\> \| `Date` \| `string`

Defined in: prisma-main/types/index.d.ts:6470

***

### id?

> `optional` **id**: [`StringFilter`](StringFilter.md)\<`"Account"`\> \| `string`

Defined in: prisma-main/types/index.d.ts:6459

***

### idToken?

> `optional` **idToken**: [`StringNullableFilter`](StringNullableFilter.md)\<`"Account"`\> \| `string` \| `null`

Defined in: prisma-main/types/index.d.ts:6465

***

### NOT?

> `optional` **NOT**: `AccountWhereInput` \| `AccountWhereInput`[]

Defined in: prisma-main/types/index.d.ts:6458

***

### OR?

> `optional` **OR**: `AccountWhereInput`[]

Defined in: prisma-main/types/index.d.ts:6457

***

### password?

> `optional` **password**: [`StringNullableFilter`](StringNullableFilter.md)\<`"Account"`\> \| `string` \| `null`

Defined in: prisma-main/types/index.d.ts:6469

***

### providerId?

> `optional` **providerId**: [`StringFilter`](StringFilter.md)\<`"Account"`\> \| `string`

Defined in: prisma-main/types/index.d.ts:6461

***

### refreshToken?

> `optional` **refreshToken**: [`StringNullableFilter`](StringNullableFilter.md)\<`"Account"`\> \| `string` \| `null`

Defined in: prisma-main/types/index.d.ts:6464

***

### refreshTokenExpiresAt?

> `optional` **refreshTokenExpiresAt**: [`DateTimeNullableFilter`](DateTimeNullableFilter.md)\<`"Account"`\> \| `Date` \| `string` \| `null`

Defined in: prisma-main/types/index.d.ts:6467

***

### scope?

> `optional` **scope**: [`StringNullableFilter`](StringNullableFilter.md)\<`"Account"`\> \| `string` \| `null`

Defined in: prisma-main/types/index.d.ts:6468

***

### updatedAt?

> `optional` **updatedAt**: [`DateTimeFilter`](DateTimeFilter.md)\<`"Account"`\> \| `Date` \| `string`

Defined in: prisma-main/types/index.d.ts:6471

***

### user?

> `optional` **user**: [`XOR`](XOR.md)\<[`UserScalarRelationFilter`](UserScalarRelationFilter.md), [`UserWhereInput`](UserWhereInput.md)\>

Defined in: prisma-main/types/index.d.ts:6472

***

### userId?

> `optional` **userId**: [`StringFilter`](StringFilter.md)\<`"Account"`\> \| `string`

Defined in: prisma-main/types/index.d.ts:6462
