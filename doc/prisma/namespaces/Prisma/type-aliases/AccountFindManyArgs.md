[**10x-devs**](../../../../README.md)

***

[10x-devs](../../../../modules.md) / [prisma](../../../README.md) / [Prisma](../README.md) / AccountFindManyArgs

# Type Alias: AccountFindManyArgs\<ExtArgs\>

> **AccountFindManyArgs**\<`ExtArgs`\> = `object`

Defined in: prisma-main/types/index.d.ts:4042

Account findMany

## Type Parameters

### ExtArgs

`ExtArgs` *extends* `$Extensions.InternalArgs` = `$Extensions.DefaultArgs`

## Properties

### cursor?

> `optional` **cursor**: [`AccountWhereUniqueInput`](AccountWhereUniqueInput.md)

Defined in: prisma-main/types/index.d.ts:4070

[Cursor Docs](https://www.prisma.io/docs/concepts/components/prisma-client/pagination#cursor-based-pagination)

Sets the position for listing Accounts.

***

### distinct?

> `optional` **distinct**: [`AccountScalarFieldEnum`](AccountScalarFieldEnum.md) \| [`AccountScalarFieldEnum`](AccountScalarFieldEnum.md)[]

Defined in: prisma-main/types/index.d.ts:4083

***

### include?

> `optional` **include**: [`AccountInclude`](AccountInclude.md)\<`ExtArgs`\> \| `null`

Defined in: prisma-main/types/index.d.ts:4054

Choose, which related nodes to fetch as well

***

### omit?

> `optional` **omit**: [`AccountOmit`](AccountOmit.md)\<`ExtArgs`\> \| `null`

Defined in: prisma-main/types/index.d.ts:4050

Omit specific fields from the Account

***

### orderBy?

> `optional` **orderBy**: [`AccountOrderByWithRelationInput`](AccountOrderByWithRelationInput.md) \| [`AccountOrderByWithRelationInput`](AccountOrderByWithRelationInput.md)[]

Defined in: prisma-main/types/index.d.ts:4064

[Sorting Docs](https://www.prisma.io/docs/concepts/components/prisma-client/sorting)

Determine the order of Accounts to fetch.

***

### select?

> `optional` **select**: [`AccountSelect`](AccountSelect.md)\<`ExtArgs`\> \| `null`

Defined in: prisma-main/types/index.d.ts:4046

Select specific fields to fetch from the Account

***

### skip?

> `optional` **skip**: `number`

Defined in: prisma-main/types/index.d.ts:4082

[Pagination Docs](https://www.prisma.io/docs/concepts/components/prisma-client/pagination)

Skip the first `n` Accounts.

***

### take?

> `optional` **take**: `number`

Defined in: prisma-main/types/index.d.ts:4076

[Pagination Docs](https://www.prisma.io/docs/concepts/components/prisma-client/pagination)

Take `±n` Accounts from the position of the cursor.

***

### where?

> `optional` **where**: [`AccountWhereInput`](AccountWhereInput.md)

Defined in: prisma-main/types/index.d.ts:4058

Filter, which Accounts to fetch.
