[**10x-devs**](../../../../README.md)

***

[10x-devs](../../../../modules.md) / [prisma](../../../README.md) / [Prisma](../README.md) / SessionWhereInput

# Type Alias: SessionWhereInput

> **SessionWhereInput** = `object`

Defined in: prisma-main/types/index.d.ts:6384

## Properties

### AND?

> `optional` **AND**: `SessionWhereInput` \| `SessionWhereInput`[]

Defined in: prisma-main/types/index.d.ts:6385

***

### createdAt?

> `optional` **createdAt**: [`DateTimeFilter`](DateTimeFilter.md)\<`"Session"`\> \| `Date` \| `string`

Defined in: prisma-main/types/index.d.ts:6391

***

### expiresAt?

> `optional` **expiresAt**: [`DateTimeFilter`](DateTimeFilter.md)\<`"Session"`\> \| `Date` \| `string`

Defined in: prisma-main/types/index.d.ts:6389

***

### id?

> `optional` **id**: [`StringFilter`](StringFilter.md)\<`"Session"`\> \| `string`

Defined in: prisma-main/types/index.d.ts:6388

***

### ipAddress?

> `optional` **ipAddress**: [`StringNullableFilter`](StringNullableFilter.md)\<`"Session"`\> \| `string` \| `null`

Defined in: prisma-main/types/index.d.ts:6393

***

### NOT?

> `optional` **NOT**: `SessionWhereInput` \| `SessionWhereInput`[]

Defined in: prisma-main/types/index.d.ts:6387

***

### OR?

> `optional` **OR**: `SessionWhereInput`[]

Defined in: prisma-main/types/index.d.ts:6386

***

### token?

> `optional` **token**: [`StringFilter`](StringFilter.md)\<`"Session"`\> \| `string`

Defined in: prisma-main/types/index.d.ts:6390

***

### updatedAt?

> `optional` **updatedAt**: [`DateTimeFilter`](DateTimeFilter.md)\<`"Session"`\> \| `Date` \| `string`

Defined in: prisma-main/types/index.d.ts:6392

***

### user?

> `optional` **user**: [`XOR`](XOR.md)\<[`UserScalarRelationFilter`](UserScalarRelationFilter.md), [`UserWhereInput`](UserWhereInput.md)\>

Defined in: prisma-main/types/index.d.ts:6396

***

### userAgent?

> `optional` **userAgent**: [`StringNullableFilter`](StringNullableFilter.md)\<`"Session"`\> \| `string` \| `null`

Defined in: prisma-main/types/index.d.ts:6394

***

### userId?

> `optional` **userId**: [`StringFilter`](StringFilter.md)\<`"Session"`\> \| `string`

Defined in: prisma-main/types/index.d.ts:6395
