[**10x-devs**](../../../../README.md)

***

[10x-devs](../../../../modules.md) / [prisma](../../../README.md) / [Prisma](../README.md) / SessionWhereUniqueInput

# Type Alias: SessionWhereUniqueInput

> **SessionWhereUniqueInput** = [`AtLeast`](AtLeast.md)\<\{ `AND?`: [`SessionWhereInput`](SessionWhereInput.md) \| [`SessionWhereInput`](SessionWhereInput.md)[]; `createdAt?`: [`DateTimeFilter`](DateTimeFilter.md)\<`"Session"`\> \| `Date` \| `string`; `expiresAt?`: [`DateTimeFilter`](DateTimeFilter.md)\<`"Session"`\> \| `Date` \| `string`; `id?`: `string`; `ipAddress?`: [`StringNullableFilter`](StringNullableFilter.md)\<`"Session"`\> \| `string` \| `null`; `NOT?`: [`SessionWhereInput`](SessionWhereInput.md) \| [`SessionWhereInput`](SessionWhereInput.md)[]; `OR?`: [`SessionWhereInput`](SessionWhereInput.md)[]; `token?`: `string`; `updatedAt?`: [`DateTimeFilter`](DateTimeFilter.md)\<`"Session"`\> \| `Date` \| `string`; `user?`: [`XOR`](XOR.md)\<[`UserScalarRelationFilter`](UserScalarRelationFilter.md), [`UserWhereInput`](UserWhereInput.md)\>; `userAgent?`: [`StringNullableFilter`](StringNullableFilter.md)\<`"Session"`\> \| `string` \| `null`; `userId?`: [`StringFilter`](StringFilter.md)\<`"Session"`\> \| `string`; \}, `"id"` \| `"token"`\>

Defined in: prisma-main/types/index.d.ts:6412
