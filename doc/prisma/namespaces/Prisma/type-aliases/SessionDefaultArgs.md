[**10x-devs**](../../../../README.md)

***

[10x-devs](../../../../modules.md) / [prisma](../../../README.md) / [Prisma](../README.md) / SessionDefaultArgs

# Type Alias: SessionDefaultArgs\<ExtArgs\>

> **SessionDefaultArgs**\<`ExtArgs`\> = `object`

Defined in: prisma-main/types/index.d.ts:3215

Session without action

## Type Parameters

### ExtArgs

`ExtArgs` *extends* `$Extensions.InternalArgs` = `$Extensions.DefaultArgs`

## Properties

### include?

> `optional` **include**: [`SessionInclude`](SessionInclude.md)\<`ExtArgs`\> \| `null`

Defined in: prisma-main/types/index.d.ts:3227

Choose, which related nodes to fetch as well

***

### omit?

> `optional` **omit**: [`SessionOmit`](SessionOmit.md)\<`ExtArgs`\> \| `null`

Defined in: prisma-main/types/index.d.ts:3223

Omit specific fields from the Session

***

### select?

> `optional` **select**: [`SessionSelect`](SessionSelect.md)\<`ExtArgs`\> \| `null`

Defined in: prisma-main/types/index.d.ts:3219

Select specific fields to fetch from the Session
