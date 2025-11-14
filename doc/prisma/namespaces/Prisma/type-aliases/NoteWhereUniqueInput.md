[**10x-devs**](../../../../README.md)

***

[10x-devs](../../../../modules.md) / [prisma](../../../README.md) / [Prisma](../README.md) / NoteWhereUniqueInput

# Type Alias: NoteWhereUniqueInput

> **NoteWhereUniqueInput** = [`AtLeast`](AtLeast.md)\<\{ `AND?`: [`NoteWhereInput`](NoteWhereInput.md) \| [`NoteWhereInput`](NoteWhereInput.md)[]; `content?`: [`StringNullableFilter`](StringNullableFilter.md)\<`"Note"`\> \| `string` \| `null`; `createdAt?`: [`DateTimeFilter`](DateTimeFilter.md)\<`"Note"`\> \| `Date` \| `string`; `name?`: [`StringFilter`](StringFilter.md)\<`"Note"`\> \| `string`; `NOT?`: [`NoteWhereInput`](NoteWhereInput.md) \| [`NoteWhereInput`](NoteWhereInput.md)[]; `noteId?`: [`IntFilter`](IntFilter.md)\<`"Note"`\> \| `number`; `noteId_userId?`: [`NoteNoteIdUserIdCompoundUniqueInput`](NoteNoteIdUserIdCompoundUniqueInput.md); `OR?`: [`NoteWhereInput`](NoteWhereInput.md)[]; `updatedAt?`: [`DateTimeFilter`](DateTimeFilter.md)\<`"Note"`\> \| `Date` \| `string`; `user?`: [`XOR`](XOR.md)\<[`UserScalarRelationFilter`](UserScalarRelationFilter.md), [`UserWhereInput`](UserWhereInput.md)\>; `userId?`: [`StringFilter`](StringFilter.md)\<`"Note"`\> \| `string`; \}, `"noteId_userId"`\>

Defined in: prisma-main/types/index.d.ts:6633
