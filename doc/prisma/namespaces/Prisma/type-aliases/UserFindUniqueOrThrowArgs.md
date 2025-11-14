[**10x-devs**](../../../../README.md)

***

[10x-devs](../../../../modules.md) / [prisma](../../../README.md) / [Prisma](../README.md) / UserFindUniqueOrThrowArgs

# Type Alias: UserFindUniqueOrThrowArgs\<ExtArgs\>

> **UserFindUniqueOrThrowArgs**\<`ExtArgs`\> = `object`

Defined in: prisma-main/types/index.d.ts:1865

User findUniqueOrThrow

## Type Parameters

### ExtArgs

`ExtArgs` *extends* `$Extensions.InternalArgs` = `$Extensions.DefaultArgs`

## Properties

### include?

> `optional` **include**: [`UserInclude`](UserInclude.md)\<`ExtArgs`\> \| `null`

Defined in: prisma-main/types/index.d.ts:1877

Choose, which related nodes to fetch as well

***

### omit?

> `optional` **omit**: [`UserOmit`](UserOmit.md)\<`ExtArgs`\> \| `null`

Defined in: prisma-main/types/index.d.ts:1873

Omit specific fields from the User

***

### select?

> `optional` **select**: [`UserSelect`](UserSelect.md)\<`ExtArgs`\> \| `null`

Defined in: prisma-main/types/index.d.ts:1869

Select specific fields to fetch from the User

***

### where

> **where**: [`UserWhereUniqueInput`](UserWhereUniqueInput.md)

Defined in: prisma-main/types/index.d.ts:1881

Filter, which User to fetch.
