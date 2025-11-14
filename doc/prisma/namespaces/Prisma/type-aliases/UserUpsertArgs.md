[**10x-devs**](../../../../README.md)

***

[10x-devs](../../../../modules.md) / [prisma](../../../README.md) / [Prisma](../README.md) / UserUpsertArgs

# Type Alias: UserUpsertArgs\<ExtArgs\>

> **UserUpsertArgs**\<`ExtArgs`\> = `object`

Defined in: prisma-main/types/index.d.ts:2115

User upsert

## Type Parameters

### ExtArgs

`ExtArgs` *extends* `$Extensions.InternalArgs` = `$Extensions.DefaultArgs`

## Properties

### create

> **create**: [`XOR`](XOR.md)\<[`UserCreateInput`](UserCreateInput.md), [`UserUncheckedCreateInput`](UserUncheckedCreateInput.md)\>

Defined in: prisma-main/types/index.d.ts:2135

In case the User found by the `where` argument doesn't exist, create a new User with this data.

***

### include?

> `optional` **include**: [`UserInclude`](UserInclude.md)\<`ExtArgs`\> \| `null`

Defined in: prisma-main/types/index.d.ts:2127

Choose, which related nodes to fetch as well

***

### omit?

> `optional` **omit**: [`UserOmit`](UserOmit.md)\<`ExtArgs`\> \| `null`

Defined in: prisma-main/types/index.d.ts:2123

Omit specific fields from the User

***

### select?

> `optional` **select**: [`UserSelect`](UserSelect.md)\<`ExtArgs`\> \| `null`

Defined in: prisma-main/types/index.d.ts:2119

Select specific fields to fetch from the User

***

### update

> **update**: [`XOR`](XOR.md)\<[`UserUpdateInput`](UserUpdateInput.md), [`UserUncheckedUpdateInput`](UserUncheckedUpdateInput.md)\>

Defined in: prisma-main/types/index.d.ts:2139

In case the User was found with the provided `where` argument, update it with this data.

***

### where

> **where**: [`UserWhereUniqueInput`](UserWhereUniqueInput.md)

Defined in: prisma-main/types/index.d.ts:2131

The filter to search for the User to update in case it exists.
