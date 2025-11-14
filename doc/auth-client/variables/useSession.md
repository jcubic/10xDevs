[**10x-devs**](../../README.md)

***

[10x-devs](../../modules.md) / [auth-client](../README.md) / useSession

# Variable: useSession()

> **useSession**: () => `object`

Defined in: [src/lib/auth-client.ts:79](https://github.com/jcubic/10xDevs/blob/8643271036ed0399a2b11ac87568ff44ec315445/src/lib/auth-client.ts#L79)

## Returns

`object`

### data

> **data**: \{ `session`: \{ `createdAt`: `Date`; `expiresAt`: `Date`; `id`: `string`; `ipAddress?`: `string` \| `null`; `token`: `string`; `updatedAt`: `Date`; `userAgent?`: `string` \| `null`; `userId`: `string`; \}; `user`: \{ `createdAt`: `Date`; `email`: `string`; `emailVerified`: `boolean`; `id`: `string`; `image?`: `string` \| `null`; `name`: `string`; `updatedAt`: `Date`; \}; \} \| `null`

### error

> **error**: `BetterFetchError` \| `null`

### isPending

> **isPending**: `boolean`

### isRefetching

> **isRefetching**: `boolean`

### refetch()

> **refetch**: (`queryParams?`) => `void`

#### Parameters

##### queryParams?

###### query?

`SessionQueryParams`

#### Returns

`void`
