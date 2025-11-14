[**10x-devs**](../../../../README.md)

***

[10x-devs](../../../../modules.md) / [prisma](../../../README.md) / [Prisma](../README.md) / SessionCreateArgs

# Type Alias: SessionCreateArgs\<ExtArgs\>

> **SessionCreateArgs**\<`ExtArgs`\> = `object`

Defined in: prisma-main/types/index.d.ts:3072

Session create

## Type Parameters

### ExtArgs

`ExtArgs` *extends* `$Extensions.InternalArgs` = `$Extensions.DefaultArgs`

## Properties

### data

> **data**: [`XOR`](XOR.md)\<[`SessionCreateInput`](SessionCreateInput.md), [`SessionUncheckedCreateInput`](SessionUncheckedCreateInput.md)\>

Defined in: prisma-main/types/index.d.ts:3088

The data needed to create a Session.

***

### include?

> `optional` **include**: [`SessionInclude`](SessionInclude.md)\<`ExtArgs`\> \| `null`

Defined in: prisma-main/types/index.d.ts:3084

Choose, which related nodes to fetch as well

***

### omit?

> `optional` **omit**: [`SessionOmit`](SessionOmit.md)\<`ExtArgs`\> \| `null`

Defined in: prisma-main/types/index.d.ts:3080

Omit specific fields from the Session

***

### select?

> `optional` **select**: [`SessionSelect`](SessionSelect.md)\<`ExtArgs`\> \| `null`

Defined in: prisma-main/types/index.d.ts:3076

Select specific fields to fetch from the Session
