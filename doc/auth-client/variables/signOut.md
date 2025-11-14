[**10x-devs**](../../README.md)

***

[10x-devs](../../modules.md) / [auth-client](../README.md) / signOut

# Variable: signOut()

> **signOut**: \<`FetchOptions`\>(...`data`) => `Promise`\<`BetterFetchResponse`\<\{ `success`: `boolean`; \}, \{ `code?`: `string`; `message?`: `string`; \}, `FetchOptions`\[`"throw"`\] *extends* `true` ? `true` : `false`\>\>

Defined in: [src/lib/auth-client.ts:79](https://github.com/jcubic/10xDevs/blob/8643271036ed0399a2b11ac87568ff44ec315445/src/lib/auth-client.ts#L79)

## Type Parameters

### FetchOptions

`FetchOptions` *extends* `object`

## Parameters

### data

...\[`Prettify`\<\{ `fetchOptions?`: `FetchOptions`; `query?`: `Record`\<`string`, `any`\>; \}\>?, `FetchOptions`?\]

## Returns

`Promise`\<`BetterFetchResponse`\<\{ `success`: `boolean`; \}, \{ `code?`: `string`; `message?`: `string`; \}, `FetchOptions`\[`"throw"`\] *extends* `true` ? `true` : `false`\>\>
