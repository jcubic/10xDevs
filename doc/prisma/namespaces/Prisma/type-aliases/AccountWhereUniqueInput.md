[**10x-devs**](../../../../README.md)

***

[10x-devs](../../../../modules.md) / [prisma](../../../README.md) / [Prisma](../README.md) / AccountWhereUniqueInput

# Type Alias: AccountWhereUniqueInput

> **AccountWhereUniqueInput** = [`AtLeast`](AtLeast.md)\<\{ `accessToken?`: [`StringNullableFilter`](StringNullableFilter.md)\<`"Account"`\> \| `string` \| `null`; `accessTokenExpiresAt?`: [`DateTimeNullableFilter`](DateTimeNullableFilter.md)\<`"Account"`\> \| `Date` \| `string` \| `null`; `accountId?`: [`StringFilter`](StringFilter.md)\<`"Account"`\> \| `string`; `AND?`: [`AccountWhereInput`](AccountWhereInput.md) \| [`AccountWhereInput`](AccountWhereInput.md)[]; `createdAt?`: [`DateTimeFilter`](DateTimeFilter.md)\<`"Account"`\> \| `Date` \| `string`; `id?`: `string`; `idToken?`: [`StringNullableFilter`](StringNullableFilter.md)\<`"Account"`\> \| `string` \| `null`; `NOT?`: [`AccountWhereInput`](AccountWhereInput.md) \| [`AccountWhereInput`](AccountWhereInput.md)[]; `OR?`: [`AccountWhereInput`](AccountWhereInput.md)[]; `password?`: [`StringNullableFilter`](StringNullableFilter.md)\<`"Account"`\> \| `string` \| `null`; `providerId?`: [`StringFilter`](StringFilter.md)\<`"Account"`\> \| `string`; `refreshToken?`: [`StringNullableFilter`](StringNullableFilter.md)\<`"Account"`\> \| `string` \| `null`; `refreshTokenExpiresAt?`: [`DateTimeNullableFilter`](DateTimeNullableFilter.md)\<`"Account"`\> \| `Date` \| `string` \| `null`; `scope?`: [`StringNullableFilter`](StringNullableFilter.md)\<`"Account"`\> \| `string` \| `null`; `updatedAt?`: [`DateTimeFilter`](DateTimeFilter.md)\<`"Account"`\> \| `Date` \| `string`; `user?`: [`XOR`](XOR.md)\<[`UserScalarRelationFilter`](UserScalarRelationFilter.md), [`UserWhereInput`](UserWhereInput.md)\>; `userId?`: [`StringFilter`](StringFilter.md)\<`"Account"`\> \| `string`; \}, `"id"`\>

Defined in: prisma-main/types/index.d.ts:6493
