[**10x-devs**](../../../../README.md)

***

[10x-devs](../../../../modules.md) / [prisma](../../../README.md) / [Prisma](../README.md) / NoteWhereInput

# Type Alias: NoteWhereInput

> **NoteWhereInput** = `object`

Defined in: prisma-main/types/index.d.ts:6609

## Properties

### AND?

> `optional` **AND**: `NoteWhereInput` \| `NoteWhereInput`[]

Defined in: prisma-main/types/index.d.ts:6610

***

### content?

> `optional` **content**: [`StringNullableFilter`](StringNullableFilter.md)\<`"Note"`\> \| `string` \| `null`

Defined in: prisma-main/types/index.d.ts:6616

***

### createdAt?

> `optional` **createdAt**: [`DateTimeFilter`](DateTimeFilter.md)\<`"Note"`\> \| `Date` \| `string`

Defined in: prisma-main/types/index.d.ts:6617

***

### name?

> `optional` **name**: [`StringFilter`](StringFilter.md)\<`"Note"`\> \| `string`

Defined in: prisma-main/types/index.d.ts:6615

***

### NOT?

> `optional` **NOT**: `NoteWhereInput` \| `NoteWhereInput`[]

Defined in: prisma-main/types/index.d.ts:6612

***

### noteId?

> `optional` **noteId**: [`IntFilter`](IntFilter.md)\<`"Note"`\> \| `number`

Defined in: prisma-main/types/index.d.ts:6613

***

### OR?

> `optional` **OR**: `NoteWhereInput`[]

Defined in: prisma-main/types/index.d.ts:6611

***

### updatedAt?

> `optional` **updatedAt**: [`DateTimeFilter`](DateTimeFilter.md)\<`"Note"`\> \| `Date` \| `string`

Defined in: prisma-main/types/index.d.ts:6618

***

### user?

> `optional` **user**: [`XOR`](XOR.md)\<[`UserScalarRelationFilter`](UserScalarRelationFilter.md), [`UserWhereInput`](UserWhereInput.md)\>

Defined in: prisma-main/types/index.d.ts:6619

***

### userId?

> `optional` **userId**: [`StringFilter`](StringFilter.md)\<`"Note"`\> \| `string`

Defined in: prisma-main/types/index.d.ts:6614
