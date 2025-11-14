[**10x-devs**](../../README.md)

***

[10x-devs](../../modules.md) / [auth-client](../README.md) / signIn

# Variable: signIn

> **signIn**: `object` & `object`

Defined in: [src/lib/auth-client.ts:79](https://github.com/jcubic/10xDevs/blob/8643271036ed0399a2b11ac87568ff44ec315445/src/lib/auth-client.ts#L79)

## Type Declaration

### social()

> **social**: \<`FetchOptions`\>(...`data`) => `Promise`\<`BetterFetchResponse`\<`NonNullable`\<\{ `redirect`: `boolean`; `token`: `string`; `url`: `undefined`; `user`: \{ `createdAt`: `Date`; `email`: `string`; `emailVerified`: `boolean`; `id`: `string`; `image`: `string` \| `null` \| `undefined`; `name`: `string`; `updatedAt`: `Date`; \}; \} \| \{ `redirect`: `boolean`; `url`: `string`; \}\>, \{ `code?`: `string`; `message?`: `string`; \}, `FetchOptions`\[`"throw"`\] *extends* `true` ? `true` : `false`\>\>

#### Type Parameters

##### FetchOptions

`FetchOptions` *extends* `object`

#### Parameters

##### data

...\[`Prettify`\<`object` & `object`\>, `FetchOptions`?\]

#### Returns

`Promise`\<`BetterFetchResponse`\<`NonNullable`\<\{ `redirect`: `boolean`; `token`: `string`; `url`: `undefined`; `user`: \{ `createdAt`: `Date`; `email`: `string`; `emailVerified`: `boolean`; `id`: `string`; `image`: `string` \| `null` \| `undefined`; `name`: `string`; `updatedAt`: `Date`; \}; \} \| \{ `redirect`: `boolean`; `url`: `string`; \}\>, \{ `code?`: `string`; `message?`: `string`; \}, `FetchOptions`\[`"throw"`\] *extends* `true` ? `true` : `false`\>\>

## Type Declaration

### email()

> **email**: \<`FetchOptions`\>(...`data`) => `Promise`\<`BetterFetchResponse`\<\{ `redirect`: `boolean`; `token`: `string`; `url`: `string` \| `undefined`; `user`: \{ `createdAt`: `Date`; `email`: `string`; `emailVerified`: `boolean`; `id`: `string`; `image`: `string` \| `null` \| `undefined`; `name`: `string`; `updatedAt`: `Date`; \}; \}, \{ `code?`: `string`; `message?`: `string`; \}, `FetchOptions`\[`"throw"`\] *extends* `true` ? `true` : `false`\>\>

#### Type Parameters

##### FetchOptions

`FetchOptions` *extends* `object`

#### Parameters

##### data

...\[`Prettify`\<`object` & `object`\>, `FetchOptions`?\]

#### Returns

`Promise`\<`BetterFetchResponse`\<\{ `redirect`: `boolean`; `token`: `string`; `url`: `string` \| `undefined`; `user`: \{ `createdAt`: `Date`; `email`: `string`; `emailVerified`: `boolean`; `id`: `string`; `image`: `string` \| `null` \| `undefined`; `name`: `string`; `updatedAt`: `Date`; \}; \}, \{ `code?`: `string`; `message?`: `string`; \}, `FetchOptions`\[`"throw"`\] *extends* `true` ? `true` : `false`\>\>
