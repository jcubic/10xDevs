[**10x-devs**](../../../../README.md)

***

[10x-devs](../../../../modules.md) / [prisma](../../../README.md) / [Prisma](../README.md) / UserDeleteArgs

# Type Alias: UserDeleteArgs\<ExtArgs\>

> **UserDeleteArgs**\<`ExtArgs`\> = `object`

Defined in: prisma-main/types/index.d.ts:2145

User delete

## Type Parameters

### ExtArgs

`ExtArgs` *extends* `$Extensions.InternalArgs` = `$Extensions.DefaultArgs`

## Properties

### include?

> `optional` **include**: [`UserInclude`](UserInclude.md)\<`ExtArgs`\> \| `null`

Defined in: prisma-main/types/index.d.ts:2157

Choose, which related nodes to fetch as well

***

### omit?

> `optional` **omit**: [`UserOmit`](UserOmit.md)\<`ExtArgs`\> \| `null`

Defined in: prisma-main/types/index.d.ts:2153

Omit specific fields from the User

***

### select?

> `optional` **select**: [`UserSelect`](UserSelect.md)\<`ExtArgs`\> \| `null`

Defined in: prisma-main/types/index.d.ts:2149

Select specific fields to fetch from the User

***

### where

> **where**: [`UserWhereUniqueInput`](UserWhereUniqueInput.md)

Defined in: prisma-main/types/index.d.ts:2161

Filter which User to delete.
