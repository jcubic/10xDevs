[**10x-devs**](../../../README.md)

***

[10x-devs](../../../modules.md) / [mocks/auth-client](../README.md) / setupMockSession

# Function: setupMockSession()

> **setupMockSession**(`authenticated`, `mockUseSession`, `options?`): \{ `data`: `null`; `error`: `null`; `isPending`: `boolean`; `isRefetching`: `boolean`; `refetch`: `Mock`\<`Procedure`\>; \} \| \{ `data`: \{ `session`: \{ `createdAt`: `Date`; `expiresAt`: `Date`; `id`: `string`; `ipAddress`: `null`; `token`: `string`; `updatedAt`: `Date`; `userAgent`: `null`; `userId`: `string`; \}; `user`: \{ `createdAt`: `Date`; `email`: `string`; `emailVerified`: `boolean`; `id`: `string`; `image`: `null`; `name`: `string`; `updatedAt`: `Date`; \}; \}; `error`: `null`; `isPending`: `boolean`; `isRefetching`: `boolean`; `refetch`: `Mock`\<`Procedure`\>; \}

Defined in: [src/mocks/auth-client.ts:44](https://github.com/jcubic/10xDevs/blob/8643271036ed0399a2b11ac87568ff44ec315445/src/mocks/auth-client.ts#L44)

## Parameters

### authenticated

`boolean`

### mockUseSession

`MockedFunction`\<() => `object`\>

### options?

#### isPending?

`boolean`

#### isRefetching?

`boolean`

#### refetch?

`Mock`\<`Procedure` \| `Constructable`\>

## Returns

\{ `data`: `null`; `error`: `null`; `isPending`: `boolean`; `isRefetching`: `boolean`; `refetch`: `Mock`\<`Procedure`\>; \} \| \{ `data`: \{ `session`: \{ `createdAt`: `Date`; `expiresAt`: `Date`; `id`: `string`; `ipAddress`: `null`; `token`: `string`; `updatedAt`: `Date`; `userAgent`: `null`; `userId`: `string`; \}; `user`: \{ `createdAt`: `Date`; `email`: `string`; `emailVerified`: `boolean`; `id`: `string`; `image`: `null`; `name`: `string`; `updatedAt`: `Date`; \}; \}; `error`: `null`; `isPending`: `boolean`; `isRefetching`: `boolean`; `refetch`: `Mock`\<`Procedure`\>; \}
