[**10x-devs**](../../../../README.md)

***

[10x-devs](../../../../modules.md) / [prisma](../../../README.md) / [Prisma](../README.md) / $SessionPayload

# Type Alias: $SessionPayload\<ExtArgs\>

> **$SessionPayload**\<`ExtArgs`\> = `object`

Defined in: prisma-main/types/index.d.ts:2478

## Type Parameters

### ExtArgs

`ExtArgs` *extends* `$Extensions.InternalArgs` = `$Extensions.DefaultArgs`

## Properties

### composites

> **composites**: `object`

Defined in: prisma-main/types/index.d.ts:2493

***

### name

> **name**: `"Session"`

Defined in: prisma-main/types/index.d.ts:2479

***

### objects

> **objects**: `object`

Defined in: prisma-main/types/index.d.ts:2480

#### user

> **user**: [`$UserPayload`]($UserPayload.md)\<`ExtArgs`\>

***

### scalars

> **scalars**: `$Extensions.GetPayloadResult`\<\{ `createdAt`: `Date`; `expiresAt`: `Date`; `id`: `string`; `ipAddress`: `string` \| `null`; `token`: `string`; `updatedAt`: `Date`; `userAgent`: `string` \| `null`; `userId`: `string`; \}, `ExtArgs`\[`"result"`\]\[`"session"`\]\>

Defined in: prisma-main/types/index.d.ts:2483
