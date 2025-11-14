[**10x-devs**](../../../../README.md)

***

[10x-devs](../../../../modules.md) / [prisma](../../../README.md) / [Prisma](../README.md) / VerificationFindFirstArgs

# Type Alias: VerificationFindFirstArgs\<ExtArgs\>

> **VerificationFindFirstArgs**\<`ExtArgs`\> = `object`

Defined in: prisma-main/types/index.d.ts:4863

Verification findFirst

## Type Parameters

### ExtArgs

`ExtArgs` *extends* `$Extensions.InternalArgs` = `$Extensions.DefaultArgs`

## Properties

### cursor?

> `optional` **cursor**: [`VerificationWhereUniqueInput`](VerificationWhereUniqueInput.md)

Defined in: prisma-main/types/index.d.ts:4887

[Cursor Docs](https://www.prisma.io/docs/concepts/components/prisma-client/pagination#cursor-based-pagination)

Sets the position for searching for Verifications.

***

### distinct?

> `optional` **distinct**: [`VerificationScalarFieldEnum`](VerificationScalarFieldEnum.md) \| [`VerificationScalarFieldEnum`](VerificationScalarFieldEnum.md)[]

Defined in: prisma-main/types/index.d.ts:4905

[Distinct Docs](https://www.prisma.io/docs/concepts/components/prisma-client/distinct)

Filter by unique combinations of Verifications.

***

### omit?

> `optional` **omit**: [`VerificationOmit`](VerificationOmit.md)\<`ExtArgs`\> \| `null`

Defined in: prisma-main/types/index.d.ts:4871

Omit specific fields from the Verification

***

### orderBy?

> `optional` **orderBy**: [`VerificationOrderByWithRelationInput`](VerificationOrderByWithRelationInput.md) \| [`VerificationOrderByWithRelationInput`](VerificationOrderByWithRelationInput.md)[]

Defined in: prisma-main/types/index.d.ts:4881

[Sorting Docs](https://www.prisma.io/docs/concepts/components/prisma-client/sorting)

Determine the order of Verifications to fetch.

***

### select?

> `optional` **select**: [`VerificationSelect`](VerificationSelect.md)\<`ExtArgs`\> \| `null`

Defined in: prisma-main/types/index.d.ts:4867

Select specific fields to fetch from the Verification

***

### skip?

> `optional` **skip**: `number`

Defined in: prisma-main/types/index.d.ts:4899

[Pagination Docs](https://www.prisma.io/docs/concepts/components/prisma-client/pagination)

Skip the first `n` Verifications.

***

### take?

> `optional` **take**: `number`

Defined in: prisma-main/types/index.d.ts:4893

[Pagination Docs](https://www.prisma.io/docs/concepts/components/prisma-client/pagination)

Take `±n` Verifications from the position of the cursor.

***

### where?

> `optional` **where**: [`VerificationWhereInput`](VerificationWhereInput.md)

Defined in: prisma-main/types/index.d.ts:4875

Filter, which Verification to fetch.
