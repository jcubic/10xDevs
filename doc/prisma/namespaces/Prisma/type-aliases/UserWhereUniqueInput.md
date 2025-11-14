[**10x-devs**](../../../../README.md)

***

[10x-devs](../../../../modules.md) / [prisma](../../../README.md) / [Prisma](../README.md) / UserWhereUniqueInput

# Type Alias: UserWhereUniqueInput

> **UserWhereUniqueInput** = [`AtLeast`](AtLeast.md)\<\{ `accounts?`: [`AccountListRelationFilter`](AccountListRelationFilter.md); `AND?`: [`UserWhereInput`](UserWhereInput.md) \| [`UserWhereInput`](UserWhereInput.md)[]; `createdAt?`: [`DateTimeFilter`](DateTimeFilter.md)\<`"User"`\> \| `Date` \| `string`; `email?`: `string`; `emailVerified?`: [`BoolFilter`](BoolFilter.md)\<`"User"`\> \| `boolean`; `id?`: `string`; `image?`: [`StringNullableFilter`](StringNullableFilter.md)\<`"User"`\> \| `string` \| `null`; `name?`: [`StringFilter`](StringFilter.md)\<`"User"`\> \| `string`; `NOT?`: [`UserWhereInput`](UserWhereInput.md) \| [`UserWhereInput`](UserWhereInput.md)[]; `notes?`: [`NoteListRelationFilter`](NoteListRelationFilter.md); `OR?`: [`UserWhereInput`](UserWhereInput.md)[]; `sessions?`: [`SessionListRelationFilter`](SessionListRelationFilter.md); `updatedAt?`: [`DateTimeFilter`](DateTimeFilter.md)\<`"User"`\> \| `Date` \| `string`; \}, `"id"` \| `"email"`\>

Defined in: prisma-main/types/index.d.ts:6342
