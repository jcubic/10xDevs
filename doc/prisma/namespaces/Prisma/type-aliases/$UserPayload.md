[**10x-devs**](../../../../README.md)

***

[10x-devs](../../../../modules.md) / [prisma](../../../README.md) / [Prisma](../README.md) / $UserPayload

# Type Alias: $UserPayload\<ExtArgs\>

> **$UserPayload**\<`ExtArgs`\> = `object`

Defined in: prisma-main/types/index.d.ts:1442

## Type Parameters

### ExtArgs

`ExtArgs` *extends* `$Extensions.InternalArgs` = `$Extensions.DefaultArgs`

## Properties

### composites

> **composites**: `object`

Defined in: prisma-main/types/index.d.ts:1458

***

### name

> **name**: `"User"`

Defined in: prisma-main/types/index.d.ts:1443

***

### objects

> **objects**: `object`

Defined in: prisma-main/types/index.d.ts:1444

#### accounts

> **accounts**: [`$AccountPayload`]($AccountPayload.md)\<`ExtArgs`\>[]

#### notes

> **notes**: [`$NotePayload`]($NotePayload.md)\<`ExtArgs`\>[]

#### sessions

> **sessions**: [`$SessionPayload`]($SessionPayload.md)\<`ExtArgs`\>[]

***

### scalars

> **scalars**: `$Extensions.GetPayloadResult`\<\{ `createdAt`: `Date`; `email`: `string`; `emailVerified`: `boolean`; `id`: `string`; `image`: `string` \| `null`; `name`: `string`; `updatedAt`: `Date`; \}, `ExtArgs`\[`"result"`\]\[`"user"`\]\>

Defined in: prisma-main/types/index.d.ts:1449
