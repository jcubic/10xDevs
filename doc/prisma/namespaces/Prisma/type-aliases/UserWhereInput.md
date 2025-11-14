[**10x-devs**](../../../../README.md)

***

[10x-devs](../../../../modules.md) / [prisma](../../../README.md) / [Prisma](../README.md) / UserWhereInput

# Type Alias: UserWhereInput

> **UserWhereInput** = `object`

Defined in: prisma-main/types/index.d.ts:6312

Deep Input Types

## Properties

### accounts?

> `optional` **accounts**: [`AccountListRelationFilter`](AccountListRelationFilter.md)

Defined in: prisma-main/types/index.d.ts:6323

***

### AND?

> `optional` **AND**: `UserWhereInput` \| `UserWhereInput`[]

Defined in: prisma-main/types/index.d.ts:6313

***

### createdAt?

> `optional` **createdAt**: [`DateTimeFilter`](DateTimeFilter.md)\<`"User"`\> \| `Date` \| `string`

Defined in: prisma-main/types/index.d.ts:6321

***

### email?

> `optional` **email**: [`StringFilter`](StringFilter.md)\<`"User"`\> \| `string`

Defined in: prisma-main/types/index.d.ts:6318

***

### emailVerified?

> `optional` **emailVerified**: [`BoolFilter`](BoolFilter.md)\<`"User"`\> \| `boolean`

Defined in: prisma-main/types/index.d.ts:6319

***

### id?

> `optional` **id**: [`StringFilter`](StringFilter.md)\<`"User"`\> \| `string`

Defined in: prisma-main/types/index.d.ts:6316

***

### image?

> `optional` **image**: [`StringNullableFilter`](StringNullableFilter.md)\<`"User"`\> \| `string` \| `null`

Defined in: prisma-main/types/index.d.ts:6320

***

### name?

> `optional` **name**: [`StringFilter`](StringFilter.md)\<`"User"`\> \| `string`

Defined in: prisma-main/types/index.d.ts:6317

***

### NOT?

> `optional` **NOT**: `UserWhereInput` \| `UserWhereInput`[]

Defined in: prisma-main/types/index.d.ts:6315

***

### notes?

> `optional` **notes**: [`NoteListRelationFilter`](NoteListRelationFilter.md)

Defined in: prisma-main/types/index.d.ts:6324

***

### OR?

> `optional` **OR**: `UserWhereInput`[]

Defined in: prisma-main/types/index.d.ts:6314

***

### sessions?

> `optional` **sessions**: [`SessionListRelationFilter`](SessionListRelationFilter.md)

Defined in: prisma-main/types/index.d.ts:6325

***

### updatedAt?

> `optional` **updatedAt**: [`DateTimeFilter`](DateTimeFilter.md)\<`"User"`\> \| `Date` \| `string`

Defined in: prisma-main/types/index.d.ts:6322
