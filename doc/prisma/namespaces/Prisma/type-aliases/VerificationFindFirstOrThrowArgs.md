[**10x-devs**](../../../../README.md)

***

[10x-devs](../../../../modules.md) / [prisma](../../../README.md) / [Prisma](../README.md) / VerificationFindFirstOrThrowArgs

# Type Alias: VerificationFindFirstOrThrowArgs\<ExtArgs\>

> **VerificationFindFirstOrThrowArgs**\<`ExtArgs`\> = `object`

Defined in: prisma-main/types/index.d.ts:4911

Verification findFirstOrThrow

## Type Parameters

### ExtArgs

`ExtArgs` *extends* `$Extensions.InternalArgs` = `$Extensions.DefaultArgs`

## Properties

### cursor?

> `optional` **cursor**: [`VerificationWhereUniqueInput`](VerificationWhereUniqueInput.md)

Defined in: prisma-main/types/index.d.ts:4935

[Cursor Docs](https://www.prisma.io/docs/concepts/components/prisma-client/pagination#cursor-based-pagination)

Sets the position for searching for Verifications.

***

### distinct?

> `optional` **distinct**: [`VerificationScalarFieldEnum`](VerificationScalarFieldEnum.md) \| [`VerificationScalarFieldEnum`](VerificationScalarFieldEnum.md)[]

Defined in: prisma-main/types/index.d.ts:4953

[Distinct Docs](https://www.prisma.io/docs/concepts/components/prisma-client/distinct)

Filter by unique combinations of Verifications.

***

### omit?

> `optional` **omit**: [`VerificationOmit`](VerificationOmit.md)\<`ExtArgs`\> \| `null`

Defined in: prisma-main/types/index.d.ts:4919

Omit specific fields from the Verification

***

### orderBy?

> `optional` **orderBy**: [`VerificationOrderByWithRelationInput`](VerificationOrderByWithRelationInput.md) \| [`VerificationOrderByWithRelationInput`](VerificationOrderByWithRelationInput.md)[]

Defined in: prisma-main/types/index.d.ts:4929

[Sorting Docs](https://www.prisma.io/docs/concepts/components/prisma-client/sorting)

Determine the order of Verifications to fetch.

***

### select?

> `optional` **select**: [`VerificationSelect`](VerificationSelect.md)\<`ExtArgs`\> \| `null`

Defined in: prisma-main/types/index.d.ts:4915

Select specific fields to fetch from the Verification

***

### skip?

> `optional` **skip**: `number`

Defined in: prisma-main/types/index.d.ts:4947

[Pagination Docs](https://www.prisma.io/docs/concepts/components/prisma-client/pagination)

Skip the first `n` Verifications.

***

### take?

> `optional` **take**: `number`

Defined in: prisma-main/types/index.d.ts:4941

[Pagination Docs](https://www.prisma.io/docs/concepts/components/prisma-client/pagination)

Take `±n` Verifications from the position of the cursor.

***

### where?

> `optional` **where**: [`VerificationWhereInput`](VerificationWhereInput.md)

Defined in: prisma-main/types/index.d.ts:4923

Filter, which Verification to fetch.
