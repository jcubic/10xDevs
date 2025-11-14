[**10x-devs**](../../../../README.md)

***

[10x-devs](../../../../modules.md) / [prisma](../../../README.md) / [Prisma](../README.md) / SessionFindManyArgs

# Type Alias: SessionFindManyArgs\<ExtArgs\>

> **SessionFindManyArgs**\<`ExtArgs`\> = `object`

Defined in: prisma-main/types/index.d.ts:3025

Session findMany

## Type Parameters

### ExtArgs

`ExtArgs` *extends* `$Extensions.InternalArgs` = `$Extensions.DefaultArgs`

## Properties

### cursor?

> `optional` **cursor**: [`SessionWhereUniqueInput`](SessionWhereUniqueInput.md)

Defined in: prisma-main/types/index.d.ts:3053

[Cursor Docs](https://www.prisma.io/docs/concepts/components/prisma-client/pagination#cursor-based-pagination)

Sets the position for listing Sessions.

***

### distinct?

> `optional` **distinct**: [`SessionScalarFieldEnum`](SessionScalarFieldEnum.md) \| [`SessionScalarFieldEnum`](SessionScalarFieldEnum.md)[]

Defined in: prisma-main/types/index.d.ts:3066

***

### include?

> `optional` **include**: [`SessionInclude`](SessionInclude.md)\<`ExtArgs`\> \| `null`

Defined in: prisma-main/types/index.d.ts:3037

Choose, which related nodes to fetch as well

***

### omit?

> `optional` **omit**: [`SessionOmit`](SessionOmit.md)\<`ExtArgs`\> \| `null`

Defined in: prisma-main/types/index.d.ts:3033

Omit specific fields from the Session

***

### orderBy?

> `optional` **orderBy**: [`SessionOrderByWithRelationInput`](SessionOrderByWithRelationInput.md) \| [`SessionOrderByWithRelationInput`](SessionOrderByWithRelationInput.md)[]

Defined in: prisma-main/types/index.d.ts:3047

[Sorting Docs](https://www.prisma.io/docs/concepts/components/prisma-client/sorting)

Determine the order of Sessions to fetch.

***

### select?

> `optional` **select**: [`SessionSelect`](SessionSelect.md)\<`ExtArgs`\> \| `null`

Defined in: prisma-main/types/index.d.ts:3029

Select specific fields to fetch from the Session

***

### skip?

> `optional` **skip**: `number`

Defined in: prisma-main/types/index.d.ts:3065

[Pagination Docs](https://www.prisma.io/docs/concepts/components/prisma-client/pagination)

Skip the first `n` Sessions.

***

### take?

> `optional` **take**: `number`

Defined in: prisma-main/types/index.d.ts:3059

[Pagination Docs](https://www.prisma.io/docs/concepts/components/prisma-client/pagination)

Take `±n` Sessions from the position of the cursor.

***

### where?

> `optional` **where**: [`SessionWhereInput`](SessionWhereInput.md)

Defined in: prisma-main/types/index.d.ts:3041

Filter, which Sessions to fetch.
