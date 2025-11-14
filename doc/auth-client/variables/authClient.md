[**10x-devs**](../../README.md)

***

[10x-devs](../../modules.md) / [auth-client](../README.md) / authClient

# Variable: authClient

> `const` **authClient**: `object` & `object` & `object` & `object` & `object` & `object` & `object` & `object` & `object` & `object` & `object` & `object` & `object` & `object` & `object` & `object` & `object` & `object` & `object` & `object` & `object` & `object` & `object` & `object` & `object` & `object` & `object` & `object`

Defined in: [src/lib/auth-client.ts:52](https://github.com/jcubic/10xDevs/blob/8643271036ed0399a2b11ac87568ff44ec315445/src/lib/auth-client.ts#L52)

Client-side authentication client instance.

## Type Declaration

### signIn

> **signIn**: `object`

#### signIn.social()

> **social**: \<`FetchOptions`\>(...`data`) => `Promise`\<`BetterFetchResponse`\<`NonNullable`\<\{ `redirect`: `boolean`; `token`: `string`; `url`: `undefined`; `user`: \{ `createdAt`: `Date`; `email`: `string`; `emailVerified`: `boolean`; `id`: `string`; `image`: ... \| ... \| ...; `name`: `string`; `updatedAt`: `Date`; \}; \} \| \{ `redirect`: `boolean`; `url`: `string`; \}\>, \{ `code?`: `string`; `message?`: `string`; \}, `FetchOptions`\[`"throw"`\] *extends* `true` ? `true` : `false`\>\>

##### Type Parameters

###### FetchOptions

`FetchOptions` *extends* `object`

##### Parameters

###### data

...\[`Prettify`\<`object` & `object`\>, `FetchOptions`?\]

##### Returns

`Promise`\<`BetterFetchResponse`\<`NonNullable`\<\{ `redirect`: `boolean`; `token`: `string`; `url`: `undefined`; `user`: \{ `createdAt`: `Date`; `email`: `string`; `emailVerified`: `boolean`; `id`: `string`; `image`: ... \| ... \| ...; `name`: `string`; `updatedAt`: `Date`; \}; \} \| \{ `redirect`: `boolean`; `url`: `string`; \}\>, \{ `code?`: `string`; `message?`: `string`; \}, `FetchOptions`\[`"throw"`\] *extends* `true` ? `true` : `false`\>\>

## Type Declaration

### signOut()

> **signOut**: \<`FetchOptions`\>(...`data`) => `Promise`\<`BetterFetchResponse`\<\{ `success`: `boolean`; \}, \{ `code?`: `string`; `message?`: `string`; \}, `FetchOptions`\[`"throw"`\] *extends* `true` ? `true` : `false`\>\>

#### Type Parameters

##### FetchOptions

`FetchOptions` *extends* `object`

#### Parameters

##### data

...\[`Prettify`\<\{ `fetchOptions?`: `FetchOptions`; `query?`: `Record`\<`string`, `any`\>; \}\>?, `FetchOptions`?\]

#### Returns

`Promise`\<`BetterFetchResponse`\<\{ `success`: `boolean`; \}, \{ `code?`: `string`; `message?`: `string`; \}, `FetchOptions`\[`"throw"`\] *extends* `true` ? `true` : `false`\>\>

## Type Declaration

### signIn

> **signIn**: `object`

#### signIn.email()

> **email**: \<`FetchOptions`\>(...`data`) => `Promise`\<`BetterFetchResponse`\<\{ `redirect`: `boolean`; `token`: `string`; `url`: `string` \| `undefined`; `user`: \{ `createdAt`: `Date`; `email`: `string`; `emailVerified`: `boolean`; `id`: `string`; `image`: `string` \| `null` \| `undefined`; `name`: `string`; `updatedAt`: `Date`; \}; \}, \{ `code?`: `string`; `message?`: `string`; \}, `FetchOptions`\[`"throw"`\] *extends* `true` ? `true` : `false`\>\>

##### Type Parameters

###### FetchOptions

`FetchOptions` *extends* `object`

##### Parameters

###### data

...\[`Prettify`\<`object` & `object`\>, `FetchOptions`?\]

##### Returns

`Promise`\<`BetterFetchResponse`\<\{ `redirect`: `boolean`; `token`: `string`; `url`: `string` \| `undefined`; `user`: \{ `createdAt`: `Date`; `email`: `string`; `emailVerified`: `boolean`; `id`: `string`; `image`: `string` \| `null` \| `undefined`; `name`: `string`; `updatedAt`: `Date`; \}; \}, \{ `code?`: `string`; `message?`: `string`; \}, `FetchOptions`\[`"throw"`\] *extends* `true` ? `true` : `false`\>\>

## Type Declaration

### forgetPassword()

> **forgetPassword**: \<`FetchOptions`\>(...`data`) => `Promise`\<`BetterFetchResponse`\<\{ `status`: `boolean`; \}, \{ `code?`: `string`; `message?`: `string`; \}, `FetchOptions`\[`"throw"`\] *extends* `true` ? `true` : `false`\>\>

#### Type Parameters

##### FetchOptions

`FetchOptions` *extends* `object`

#### Parameters

##### data

...\[`Prettify`\<`object` & `object`\>, `FetchOptions`?\]

#### Returns

`Promise`\<`BetterFetchResponse`\<\{ `status`: `boolean`; \}, \{ `code?`: `string`; `message?`: `string`; \}, `FetchOptions`\[`"throw"`\] *extends* `true` ? `true` : `false`\>\>

## Type Declaration

### resetPassword()

> **resetPassword**: \<`FetchOptions`\>(...`data`) => `Promise`\<`BetterFetchResponse`\<\{ `status`: `boolean`; \}, \{ `code?`: `string`; `message?`: `string`; \}, `FetchOptions`\[`"throw"`\] *extends* `true` ? `true` : `false`\>\>

#### Type Parameters

##### FetchOptions

`FetchOptions` *extends* `object`

#### Parameters

##### data

...\[`Prettify`\<`object` & `object`\>, `FetchOptions`?\]

#### Returns

`Promise`\<`BetterFetchResponse`\<\{ `status`: `boolean`; \}, \{ `code?`: `string`; `message?`: `string`; \}, `FetchOptions`\[`"throw"`\] *extends* `true` ? `true` : `false`\>\>

## Type Declaration

### verifyEmail()

> **verifyEmail**: \<`FetchOptions`\>(...`data`) => `Promise`\<`BetterFetchResponse`\<`NonNullable`\<`void` \| \{ `status`: `boolean`; `user`: \{ `createdAt`: `Date`; `email`: `string`; `emailVerified`: `boolean`; `id`: `string`; `image`: `string` \| `null` \| `undefined`; `name`: `string`; `updatedAt`: `Date`; \}; \} \| \{ `status`: `boolean`; `user`: `null`; \}\>, \{ `code?`: `string`; `message?`: `string`; \}, `FetchOptions`\[`"throw"`\] *extends* `true` ? `true` : `false`\>\>

#### Type Parameters

##### FetchOptions

`FetchOptions` *extends* `object`

#### Parameters

##### data

...\[`Prettify`\<\{ `fetchOptions?`: `FetchOptions`; `query`: \{ `callbackURL?`: `string`; `token`: `string`; \}; \}\>, `FetchOptions`?\]

#### Returns

`Promise`\<`BetterFetchResponse`\<`NonNullable`\<`void` \| \{ `status`: `boolean`; `user`: \{ `createdAt`: `Date`; `email`: `string`; `emailVerified`: `boolean`; `id`: `string`; `image`: `string` \| `null` \| `undefined`; `name`: `string`; `updatedAt`: `Date`; \}; \} \| \{ `status`: `boolean`; `user`: `null`; \}\>, \{ `code?`: `string`; `message?`: `string`; \}, `FetchOptions`\[`"throw"`\] *extends* `true` ? `true` : `false`\>\>

## Type Declaration

### sendVerificationEmail()

> **sendVerificationEmail**: \<`FetchOptions`\>(...`data`) => `Promise`\<`BetterFetchResponse`\<\{ `status`: `boolean`; \}, \{ `code?`: `string`; `message?`: `string`; \}, `FetchOptions`\[`"throw"`\] *extends* `true` ? `true` : `false`\>\>

#### Type Parameters

##### FetchOptions

`FetchOptions` *extends* `object`

#### Parameters

##### data

...\[`Prettify`\<`object` & `object`\>, `FetchOptions`?\]

#### Returns

`Promise`\<`BetterFetchResponse`\<\{ `status`: `boolean`; \}, \{ `code?`: `string`; `message?`: `string`; \}, `FetchOptions`\[`"throw"`\] *extends* `true` ? `true` : `false`\>\>

## Type Declaration

### changeEmail()

> **changeEmail**: \<`FetchOptions`\>(...`data`) => `Promise`\<`BetterFetchResponse`\<\{ `status`: `boolean`; \}, \{ `code?`: `string`; `message?`: `string`; \}, `FetchOptions`\[`"throw"`\] *extends* `true` ? `true` : `false`\>\>

#### Type Parameters

##### FetchOptions

`FetchOptions` *extends* `object`

#### Parameters

##### data

...\[`Prettify`\<`object` & `object`\>, `FetchOptions`?\]

#### Returns

`Promise`\<`BetterFetchResponse`\<\{ `status`: `boolean`; \}, \{ `code?`: `string`; `message?`: `string`; \}, `FetchOptions`\[`"throw"`\] *extends* `true` ? `true` : `false`\>\>

## Type Declaration

### changePassword()

> **changePassword**: \<`FetchOptions`\>(...`data`) => `Promise`\<`BetterFetchResponse`\<\{ `token`: `string` \| `null`; `user`: \{ `createdAt`: `Date`; `email`: `string`; `emailVerified`: `boolean`; `id`: `string`; `image`: `string` \| `null` \| `undefined`; `name`: `string`; `updatedAt`: `Date`; \}; \}, \{ `code?`: `string`; `message?`: `string`; \}, `FetchOptions`\[`"throw"`\] *extends* `true` ? `true` : `false`\>\>

#### Type Parameters

##### FetchOptions

`FetchOptions` *extends* `object`

#### Parameters

##### data

...\[`Prettify`\<`object` & `object`\>, `FetchOptions`?\]

#### Returns

`Promise`\<`BetterFetchResponse`\<\{ `token`: `string` \| `null`; `user`: \{ `createdAt`: `Date`; `email`: `string`; `emailVerified`: `boolean`; `id`: `string`; `image`: `string` \| `null` \| `undefined`; `name`: `string`; `updatedAt`: `Date`; \}; \}, \{ `code?`: `string`; `message?`: `string`; \}, `FetchOptions`\[`"throw"`\] *extends* `true` ? `true` : `false`\>\>

## Type Declaration

### deleteUser()

> **deleteUser**: \<`FetchOptions`\>(...`data`) => `Promise`\<`BetterFetchResponse`\<\{ `message`: `string`; `success`: `boolean`; \}, \{ `code?`: `string`; `message?`: `string`; \}, `FetchOptions`\[`"throw"`\] *extends* `true` ? `true` : `false`\>\>

#### Type Parameters

##### FetchOptions

`FetchOptions` *extends* `object`

#### Parameters

##### data

...\[`Prettify`\<`object` & `object`\>?, `FetchOptions`?\]

#### Returns

`Promise`\<`BetterFetchResponse`\<\{ `message`: `string`; `success`: `boolean`; \}, \{ `code?`: `string`; `message?`: `string`; \}, `FetchOptions`\[`"throw"`\] *extends* `true` ? `true` : `false`\>\>

## Type Declaration

### resetPassword

> **resetPassword**: `object`

#### resetPassword.:token()

> **:token**: \<`FetchOptions`\>(...`data`) => `Promise`\<`BetterFetchResponse`\<`never`, \{ `code?`: `string`; `message?`: `string`; \}, `FetchOptions`\[`"throw"`\] *extends* `true` ? `true` : `false`\>\>

##### Type Parameters

###### FetchOptions

`FetchOptions` *extends* `object`

##### Parameters

###### data

...\[`Prettify`\<\{ `fetchOptions?`: `FetchOptions`; `query`: \{ `callbackURL`: `string`; \}; \}\>, `FetchOptions`?\]

##### Returns

`Promise`\<`BetterFetchResponse`\<`never`, \{ `code?`: `string`; `message?`: `string`; \}, `FetchOptions`\[`"throw"`\] *extends* `true` ? `true` : `false`\>\>

## Type Declaration

### requestPasswordReset()

> **requestPasswordReset**: \<`FetchOptions`\>(...`data`) => `Promise`\<`BetterFetchResponse`\<\{ `message`: `string`; `status`: `boolean`; \}, \{ `code?`: `string`; `message?`: `string`; \}, `FetchOptions`\[`"throw"`\] *extends* `true` ? `true` : `false`\>\>

#### Type Parameters

##### FetchOptions

`FetchOptions` *extends* `object`

#### Parameters

##### data

...\[`Prettify`\<`object` & `object`\>, `FetchOptions`?\]

#### Returns

`Promise`\<`BetterFetchResponse`\<\{ `message`: `string`; `status`: `boolean`; \}, \{ `code?`: `string`; `message?`: `string`; \}, `FetchOptions`\[`"throw"`\] *extends* `true` ? `true` : `false`\>\>

## Type Declaration

### resetPassword

> **resetPassword**: `object`

#### resetPassword.:token()

> **:token**: \<`FetchOptions`\>(...`data`) => `Promise`\<`BetterFetchResponse`\<`never`, \{ `code?`: `string`; `message?`: `string`; \}, `FetchOptions`\[`"throw"`\] *extends* `true` ? `true` : `false`\>\>

##### Type Parameters

###### FetchOptions

`FetchOptions` *extends* `object`

##### Parameters

###### data

...\[`Prettify`\<\{ `fetchOptions?`: `FetchOptions`; `query`: \{ `callbackURL`: `string`; \}; \}\>, `FetchOptions`?\]

##### Returns

`Promise`\<`BetterFetchResponse`\<`never`, \{ `code?`: `string`; `message?`: `string`; \}, `FetchOptions`\[`"throw"`\] *extends* `true` ? `true` : `false`\>\>

## Type Declaration

### revokeSession()

> **revokeSession**: \<`FetchOptions`\>(...`data`) => `Promise`\<`BetterFetchResponse`\<\{ `status`: `boolean`; \}, \{ `code?`: `string`; `message?`: `string`; \}, `FetchOptions`\[`"throw"`\] *extends* `true` ? `true` : `false`\>\>

#### Type Parameters

##### FetchOptions

`FetchOptions` *extends* `object`

#### Parameters

##### data

...\[`Prettify`\<`object` & `object`\>, `FetchOptions`?\]

#### Returns

`Promise`\<`BetterFetchResponse`\<\{ `status`: `boolean`; \}, \{ `code?`: `string`; `message?`: `string`; \}, `FetchOptions`\[`"throw"`\] *extends* `true` ? `true` : `false`\>\>

## Type Declaration

### revokeSessions()

> **revokeSessions**: \<`FetchOptions`\>(...`data`) => `Promise`\<`BetterFetchResponse`\<\{ `status`: `boolean`; \}, \{ `code?`: `string`; `message?`: `string`; \}, `FetchOptions`\[`"throw"`\] *extends* `true` ? `true` : `false`\>\>

#### Type Parameters

##### FetchOptions

`FetchOptions` *extends* `object`

#### Parameters

##### data

...\[`Prettify`\<\{ `fetchOptions?`: `FetchOptions`; `query?`: `Record`\<`string`, `any`\>; \}\>?, `FetchOptions`?\]

#### Returns

`Promise`\<`BetterFetchResponse`\<\{ `status`: `boolean`; \}, \{ `code?`: `string`; `message?`: `string`; \}, `FetchOptions`\[`"throw"`\] *extends* `true` ? `true` : `false`\>\>

## Type Declaration

### revokeOtherSessions()

> **revokeOtherSessions**: \<`FetchOptions`\>(...`data`) => `Promise`\<`BetterFetchResponse`\<\{ `status`: `boolean`; \}, \{ `code?`: `string`; `message?`: `string`; \}, `FetchOptions`\[`"throw"`\] *extends* `true` ? `true` : `false`\>\>

#### Type Parameters

##### FetchOptions

`FetchOptions` *extends* `object`

#### Parameters

##### data

...\[`Prettify`\<\{ `fetchOptions?`: `FetchOptions`; `query?`: `Record`\<`string`, `any`\>; \}\>?, `FetchOptions`?\]

#### Returns

`Promise`\<`BetterFetchResponse`\<\{ `status`: `boolean`; \}, \{ `code?`: `string`; `message?`: `string`; \}, `FetchOptions`\[`"throw"`\] *extends* `true` ? `true` : `false`\>\>

## Type Declaration

### linkSocial()

> **linkSocial**: \<`FetchOptions`\>(...`data`) => `Promise`\<`BetterFetchResponse`\<\{ `redirect`: `boolean`; `url`: `string`; \}, \{ `code?`: `string`; `message?`: `string`; \}, `FetchOptions`\[`"throw"`\] *extends* `true` ? `true` : `false`\>\>

#### Type Parameters

##### FetchOptions

`FetchOptions` *extends* `object`

#### Parameters

##### data

...\[`Prettify`\<`object` & `object`\>, `FetchOptions`?\]

#### Returns

`Promise`\<`BetterFetchResponse`\<\{ `redirect`: `boolean`; `url`: `string`; \}, \{ `code?`: `string`; `message?`: `string`; \}, `FetchOptions`\[`"throw"`\] *extends* `true` ? `true` : `false`\>\>

## Type Declaration

### listAccounts()

> **listAccounts**: \<`FetchOptions`\>(...`data`) => `Promise`\<`BetterFetchResponse`\<`object`[], \{ `code?`: `string`; `message?`: `string`; \}, `FetchOptions`\[`"throw"`\] *extends* `true` ? `true` : `false`\>\>

#### Type Parameters

##### FetchOptions

`FetchOptions` *extends* `object`

#### Parameters

##### data

...\[`Prettify`\<\{ `fetchOptions?`: `FetchOptions`; `query?`: `Record`\<`string`, `any`\>; \}\>?, `FetchOptions`?\]

#### Returns

`Promise`\<`BetterFetchResponse`\<`object`[], \{ `code?`: `string`; `message?`: `string`; \}, `FetchOptions`\[`"throw"`\] *extends* `true` ? `true` : `false`\>\>

## Type Declaration

### deleteUser

> **deleteUser**: `object`

#### deleteUser.callback()

> **callback**: \<`FetchOptions`\>(...`data`) => `Promise`\<`BetterFetchResponse`\<\{ `message`: `string`; `success`: `boolean`; \}, \{ `code?`: `string`; `message?`: `string`; \}, `FetchOptions`\[`"throw"`\] *extends* `true` ? `true` : `false`\>\>

##### Type Parameters

###### FetchOptions

`FetchOptions` *extends* `object`

##### Parameters

###### data

...\[`Prettify`\<\{ `fetchOptions?`: `FetchOptions`; `query`: \{ `callbackURL?`: `string`; `token`: `string`; \}; \}\>, `FetchOptions`?\]

##### Returns

`Promise`\<`BetterFetchResponse`\<\{ `message`: `string`; `success`: `boolean`; \}, \{ `code?`: `string`; `message?`: `string`; \}, `FetchOptions`\[`"throw"`\] *extends* `true` ? `true` : `false`\>\>

## Type Declaration

### unlinkAccount()

> **unlinkAccount**: \<`FetchOptions`\>(...`data`) => `Promise`\<`BetterFetchResponse`\<\{ `status`: `boolean`; \}, \{ `code?`: `string`; `message?`: `string`; \}, `FetchOptions`\[`"throw"`\] *extends* `true` ? `true` : `false`\>\>

#### Type Parameters

##### FetchOptions

`FetchOptions` *extends* `object`

#### Parameters

##### data

...\[`Prettify`\<`object` & `object`\>, `FetchOptions`?\]

#### Returns

`Promise`\<`BetterFetchResponse`\<\{ `status`: `boolean`; \}, \{ `code?`: `string`; `message?`: `string`; \}, `FetchOptions`\[`"throw"`\] *extends* `true` ? `true` : `false`\>\>

## Type Declaration

### refreshToken()

> **refreshToken**: \<`FetchOptions`\>(...`data`) => `Promise`\<`BetterFetchResponse`\<`any`, \{ `code?`: `string`; `message?`: `string`; \}, `FetchOptions`\[`"throw"`\] *extends* `true` ? `true` : `false`\>\>

#### Type Parameters

##### FetchOptions

`FetchOptions` *extends* `object`

#### Parameters

##### data

...\[`Prettify`\<`object` & `object`\>, `FetchOptions`?\]

#### Returns

`Promise`\<`BetterFetchResponse`\<`any`, \{ `code?`: `string`; `message?`: `string`; \}, `FetchOptions`\[`"throw"`\] *extends* `true` ? `true` : `false`\>\>

## Type Declaration

### getAccessToken()

> **getAccessToken**: \<`FetchOptions`\>(...`data`) => `Promise`\<`BetterFetchResponse`\<\{ `accessToken`: `string`; `accessTokenExpiresAt`: `Date` \| `undefined`; `idToken`: `string` \| `undefined`; `scopes`: `string`[]; \}, \{ `code?`: `string`; `message?`: `string`; \}, `FetchOptions`\[`"throw"`\] *extends* `true` ? `true` : `false`\>\>

#### Type Parameters

##### FetchOptions

`FetchOptions` *extends* `object`

#### Parameters

##### data

...\[`Prettify`\<`object` & `object`\>, `FetchOptions`?\]

#### Returns

`Promise`\<`BetterFetchResponse`\<\{ `accessToken`: `string`; `accessTokenExpiresAt`: `Date` \| `undefined`; `idToken`: `string` \| `undefined`; `scopes`: `string`[]; \}, \{ `code?`: `string`; `message?`: `string`; \}, `FetchOptions`\[`"throw"`\] *extends* `true` ? `true` : `false`\>\>

## Type Declaration

### accountInfo()

> **accountInfo**: \<`FetchOptions`\>(...`data`) => `Promise`\<`BetterFetchResponse`\<\{ `data`: `Record`\<`string`, `any`\>; `user`: `OAuth2UserInfo`; \}, \{ `code?`: `string`; `message?`: `string`; \}, `FetchOptions`\[`"throw"`\] *extends* `true` ? `true` : `false`\>\>

#### Type Parameters

##### FetchOptions

`FetchOptions` *extends* `object`

#### Parameters

##### data

...\[`Prettify`\<`object` & `object`\>, `FetchOptions`?\]

#### Returns

`Promise`\<`BetterFetchResponse`\<\{ `data`: `Record`\<`string`, `any`\>; `user`: `OAuth2UserInfo`; \}, \{ `code?`: `string`; `message?`: `string`; \}, `FetchOptions`\[`"throw"`\] *extends* `true` ? `true` : `false`\>\>

## Type Declaration

### signUp

> **signUp**: `object`

#### signUp.email()

> **email**: \<`FetchOptions`\>(...`data`) => `Promise`\<`BetterFetchResponse`\<`NonNullable`\<\{ `token`: `null`; `user`: \{ `createdAt`: `Date`; `email`: `string`; `emailVerified`: `boolean`; `id`: `string`; `image`: ... \| ... \| ...; `name`: `string`; `updatedAt`: `Date`; \}; \} \| \{ `token`: `string`; `user`: \{ `createdAt`: `Date`; `email`: `string`; `emailVerified`: `boolean`; `id`: `string`; `image`: ... \| ... \| ...; `name`: `string`; `updatedAt`: `Date`; \}; \}\>, \{ `code?`: `string`; `message?`: `string`; \}, `FetchOptions`\[`"throw"`\] *extends* `true` ? `true` : `false`\>\>

##### Type Parameters

###### FetchOptions

`FetchOptions` *extends* `object`

##### Parameters

###### data

...\[`Prettify`\<\{ `callbackURL?`: `string`; `email`: `string`; `fetchOptions?`: `FetchOptions`; `image?`: `string`; `name`: `string`; `password`: `string`; \}\>, `FetchOptions`?\]

##### Returns

`Promise`\<`BetterFetchResponse`\<`NonNullable`\<\{ `token`: `null`; `user`: \{ `createdAt`: `Date`; `email`: `string`; `emailVerified`: `boolean`; `id`: `string`; `image`: ... \| ... \| ...; `name`: `string`; `updatedAt`: `Date`; \}; \} \| \{ `token`: `string`; `user`: \{ `createdAt`: `Date`; `email`: `string`; `emailVerified`: `boolean`; `id`: `string`; `image`: ... \| ... \| ...; `name`: `string`; `updatedAt`: `Date`; \}; \}\>, \{ `code?`: `string`; `message?`: `string`; \}, `FetchOptions`\[`"throw"`\] *extends* `true` ? `true` : `false`\>\>

## Type Declaration

### updateUser()

> **updateUser**: \<`FetchOptions`\>(...`data`) => `Promise`\<`BetterFetchResponse`\<\{ `status`: `boolean`; \}, \{ `code?`: `string`; `message?`: `string`; \}, `FetchOptions`\[`"throw"`\] *extends* `true` ? `true` : `false`\>\>

#### Type Parameters

##### FetchOptions

`FetchOptions` *extends* `object`

#### Parameters

##### data

...\[`Prettify`\<`InferUserUpdateCtx`\<\{ `baseURL`: `string`; \}, `FetchOptions`\>\>?, `FetchOptions`?\]

#### Returns

`Promise`\<`BetterFetchResponse`\<\{ `status`: `boolean`; \}, \{ `code?`: `string`; `message?`: `string`; \}, `FetchOptions`\[`"throw"`\] *extends* `true` ? `true` : `false`\>\>

## Type Declaration

### listSessions()

> **listSessions**: \<`FetchOptions`\>(...`data`) => `Promise`\<`BetterFetchResponse`\<`Prettify`\<\{ `createdAt`: `Date`; `expiresAt`: `Date`; `id`: `string`; `ipAddress?`: `string` \| `null`; `token`: `string`; `updatedAt`: `Date`; `userAgent?`: `string` \| `null`; `userId`: `string`; \}\>[], \{ `code?`: `string`; `message?`: `string`; \}, `FetchOptions`\[`"throw"`\] *extends* `true` ? `true` : `false`\>\>

#### Type Parameters

##### FetchOptions

`FetchOptions` *extends* `object`

#### Parameters

##### data

...\[`Prettify`\<\{ `fetchOptions?`: `FetchOptions`; `query?`: `Record`\<`string`, `any`\>; \}\>?, `FetchOptions`?\]

#### Returns

`Promise`\<`BetterFetchResponse`\<`Prettify`\<\{ `createdAt`: `Date`; `expiresAt`: `Date`; `id`: `string`; `ipAddress?`: `string` \| `null`; `token`: `string`; `updatedAt`: `Date`; `userAgent?`: `string` \| `null`; `userId`: `string`; \}\>[], \{ `code?`: `string`; `message?`: `string`; \}, `FetchOptions`\[`"throw"`\] *extends* `true` ? `true` : `false`\>\>

## Type Declaration

### getSession()

> **getSession**: \<`FetchOptions`\>(...`data`) => `Promise`\<`BetterFetchResponse`\<\{ `session`: \{ `createdAt`: `Date`; `expiresAt`: `Date`; `id`: `string`; `ipAddress?`: `string` \| `null`; `token`: `string`; `updatedAt`: `Date`; `userAgent?`: `string` \| `null`; `userId`: `string`; \}; `user`: \{ `createdAt`: `Date`; `email`: `string`; `emailVerified`: `boolean`; `id`: `string`; `image?`: `string` \| `null`; `name`: `string`; `updatedAt`: `Date`; \}; \} \| `null`, \{ `code?`: `string`; `message?`: `string`; \}, `FetchOptions`\[`"throw"`\] *extends* `true` ? `true` : `false`\>\>

#### Type Parameters

##### FetchOptions

`FetchOptions` *extends* `object`

#### Parameters

##### data

...\[`Prettify`\<\{ `fetchOptions?`: `FetchOptions`; `query?`: \{ `disableCookieCache?`: `unknown`; `disableRefresh?`: `unknown`; \}; \}\>?, `FetchOptions`?\]

#### Returns

`Promise`\<`BetterFetchResponse`\<\{ `session`: \{ `createdAt`: `Date`; `expiresAt`: `Date`; `id`: `string`; `ipAddress?`: `string` \| `null`; `token`: `string`; `updatedAt`: `Date`; `userAgent?`: `string` \| `null`; `userId`: `string`; \}; `user`: \{ `createdAt`: `Date`; `email`: `string`; `emailVerified`: `boolean`; `id`: `string`; `image?`: `string` \| `null`; `name`: `string`; `updatedAt`: `Date`; \}; \} \| `null`, \{ `code?`: `string`; `message?`: `string`; \}, `FetchOptions`\[`"throw"`\] *extends* `true` ? `true` : `false`\>\>

## Type Declaration

### $ERROR\_CODES

> **$ERROR\_CODES**: `object`

#### $ERROR\_CODES.ACCOUNT\_NOT\_FOUND

> `readonly` **ACCOUNT\_NOT\_FOUND**: `"Account not found"`

#### $ERROR\_CODES.CREDENTIAL\_ACCOUNT\_NOT\_FOUND

> `readonly` **CREDENTIAL\_ACCOUNT\_NOT\_FOUND**: `"Credential account not found"`

#### $ERROR\_CODES.EMAIL\_CAN\_NOT\_BE\_UPDATED

> `readonly` **EMAIL\_CAN\_NOT\_BE\_UPDATED**: `"Email can not be updated"`

#### $ERROR\_CODES.EMAIL\_NOT\_VERIFIED

> `readonly` **EMAIL\_NOT\_VERIFIED**: `"Email not verified"`

#### $ERROR\_CODES.FAILED\_TO\_CREATE\_SESSION

> `readonly` **FAILED\_TO\_CREATE\_SESSION**: `"Failed to create session"`

#### $ERROR\_CODES.FAILED\_TO\_CREATE\_USER

> `readonly` **FAILED\_TO\_CREATE\_USER**: `"Failed to create user"`

#### $ERROR\_CODES.FAILED\_TO\_GET\_SESSION

> `readonly` **FAILED\_TO\_GET\_SESSION**: `"Failed to get session"`

#### $ERROR\_CODES.FAILED\_TO\_GET\_USER\_INFO

> `readonly` **FAILED\_TO\_GET\_USER\_INFO**: `"Failed to get user info"`

#### $ERROR\_CODES.FAILED\_TO\_UNLINK\_LAST\_ACCOUNT

> `readonly` **FAILED\_TO\_UNLINK\_LAST\_ACCOUNT**: `"You can't unlink your last account"`

#### $ERROR\_CODES.FAILED\_TO\_UPDATE\_USER

> `readonly` **FAILED\_TO\_UPDATE\_USER**: `"Failed to update user"`

#### $ERROR\_CODES.ID\_TOKEN\_NOT\_SUPPORTED

> `readonly` **ID\_TOKEN\_NOT\_SUPPORTED**: `"id_token not supported"`

#### $ERROR\_CODES.INVALID\_EMAIL

> `readonly` **INVALID\_EMAIL**: `"Invalid email"`

#### $ERROR\_CODES.INVALID\_EMAIL\_OR\_PASSWORD

> `readonly` **INVALID\_EMAIL\_OR\_PASSWORD**: `"Invalid email or password"`

#### $ERROR\_CODES.INVALID\_PASSWORD

> `readonly` **INVALID\_PASSWORD**: `"Invalid password"`

#### $ERROR\_CODES.INVALID\_TOKEN

> `readonly` **INVALID\_TOKEN**: `"Invalid token"`

#### $ERROR\_CODES.PASSWORD\_TOO\_LONG

> `readonly` **PASSWORD\_TOO\_LONG**: `"Password too long"`

#### $ERROR\_CODES.PASSWORD\_TOO\_SHORT

> `readonly` **PASSWORD\_TOO\_SHORT**: `"Password too short"`

#### $ERROR\_CODES.PROVIDER\_NOT\_FOUND

> `readonly` **PROVIDER\_NOT\_FOUND**: `"Provider not found"`

#### $ERROR\_CODES.SESSION\_EXPIRED

> `readonly` **SESSION\_EXPIRED**: `"Session expired. Re-authenticate to perform this action."`

#### $ERROR\_CODES.SOCIAL\_ACCOUNT\_ALREADY\_LINKED

> `readonly` **SOCIAL\_ACCOUNT\_ALREADY\_LINKED**: `"Social account already linked"`

#### $ERROR\_CODES.USER\_ALREADY\_EXISTS

> `readonly` **USER\_ALREADY\_EXISTS**: `"User already exists."`

#### $ERROR\_CODES.USER\_ALREADY\_EXISTS\_USE\_ANOTHER\_EMAIL

> `readonly` **USER\_ALREADY\_EXISTS\_USE\_ANOTHER\_EMAIL**: `"User already exists. Use another email."`

#### $ERROR\_CODES.USER\_ALREADY\_HAS\_PASSWORD

> `readonly` **USER\_ALREADY\_HAS\_PASSWORD**: `"User already has a password. Provide that to delete the account."`

#### $ERROR\_CODES.USER\_EMAIL\_NOT\_FOUND

> `readonly` **USER\_EMAIL\_NOT\_FOUND**: `"User email not found"`

#### $ERROR\_CODES.USER\_NOT\_FOUND

> `readonly` **USER\_NOT\_FOUND**: `"User not found"`

### $fetch

> **$fetch**: `BetterFetch`\<\{ `auth?`: \{ `token`: `string` \| `Promise`\<`string` \| `undefined`\> \| () => `string` \| `Promise`\<... \| ...\> \| `undefined` \| `undefined`; `type`: `"Bearer"`; \} \| \{ `password`: `string` \| () => `string` \| `undefined` \| `undefined`; `type`: `"Basic"`; `username`: `string` \| () => `string` \| `undefined` \| `undefined`; \} \| \{ `prefix`: `string` \| () => `string` \| `undefined` \| `undefined`; `type`: `"Custom"`; `value`: `string` \| () => `string` \| `undefined` \| `undefined`; \}; `baseURL`: `string`; `body?`: `any`; `cache?`: `RequestCache`; `credentials?`: `RequestCredentials`; `customFetchImpl`: `FetchEsque`; `disableValidation?`: `boolean`; `duplex?`: `"full"` \| `"half"`; `errorSchema?`: `StandardSchemaV1`\<`unknown`, `unknown`\>; `headers?`: HeadersInit & (HeadersInit \| \{ accept: "application/json" \| "text/plain" \| "application/octet-stream"; "content-type": "application/json" \| "text/plain" \| "application/octet-stream" \| "application/x-www-form-urlencoded" \| "multipart/form-data"; authorization: "Bearer" \| "Basic"; \}); `hookOptions?`: \{ `cloneResponse?`: `boolean`; \}; `integrity?`: `string`; `jsonParser`: (`text`) => `any`; `keepalive?`: `boolean`; `method`: `string`; `mode?`: `RequestMode`; `onRetry?`: (`response`) => `void` \| `Promise`\<`void`\>; `output?`: `StandardSchemaV1`\<`unknown`, `unknown`\> \| \{(`blobParts?`, `options?`): `Blob`; `prototype`: `Blob`; \} \| \{(`fileBits`, `fileName`, `options?`): `File`; `prototype`: `File`; \}; `params?`: `any`; `plugins`: (`BetterFetchPlugin` \| \{ `hooks`: \{ `onError`: (`context`) => ... \| ... \| `undefined`; `onRequest`: \<`T`\>(`context`) => ... \| ... \| ... \| `undefined`; `onResponse`: (`context`) => ... \| ... \| ... \| ... \| `undefined`; `onSuccess`: (`context`) => ... \| ... \| `undefined`; \}; `id`: `string`; `name`: `string`; \} \| \{ `hooks`: \{ `onSuccess`: `void`; \}; `id`: `string`; `name`: `string`; \})[]; `priority?`: `RequestPriority`; `query?`: `any`; `redirect?`: `RequestRedirect`; `referrer?`: `string`; `referrerPolicy?`: `ReferrerPolicy`; `retry?`: `RetryOptions`; `retryAttempt?`: `number`; `signal?`: `AbortSignal` \| `null`; `throw?`: `boolean`; `timeout?`: `number`; `window?`: `null`; \}, `unknown`, `unknown`, \{ \}\>

### $Infer

> **$Infer**: `object`

#### $Infer.Session

> **Session**: `object`

#### $Infer.Session.session

> **session**: `object`

#### $Infer.Session.session.createdAt

> **createdAt**: `Date`

#### $Infer.Session.session.expiresAt

> **expiresAt**: `Date`

#### $Infer.Session.session.id

> **id**: `string`

#### $Infer.Session.session.ipAddress?

> `optional` **ipAddress**: `string` \| `null`

#### $Infer.Session.session.token

> **token**: `string`

#### $Infer.Session.session.updatedAt

> **updatedAt**: `Date`

#### $Infer.Session.session.userAgent?

> `optional` **userAgent**: `string` \| `null`

#### $Infer.Session.session.userId

> **userId**: `string`

#### $Infer.Session.user

> **user**: `object`

#### $Infer.Session.user.createdAt

> **createdAt**: `Date`

#### $Infer.Session.user.email

> **email**: `string`

#### $Infer.Session.user.emailVerified

> **emailVerified**: `boolean`

#### $Infer.Session.user.id

> **id**: `string`

#### $Infer.Session.user.image?

> `optional` **image**: `string` \| `null`

#### $Infer.Session.user.name

> **name**: `string`

#### $Infer.Session.user.updatedAt

> **updatedAt**: `Date`

### $store

> **$store**: `object`

#### $store.atoms

> **atoms**: `Record`\<`string`, `nanostores.WritableAtom`\<`any`\>\>

#### $store.listen()

> **listen**: (`signal`, `listener`) => `void`

##### Parameters

###### signal

`"$sessionSignal"` | `Omit`\<`string`, `"$sessionSignal"`\>

###### listener

(`value`, `oldValue?`) => `void`

##### Returns

`void`

#### $store.notify()

> **notify**: (`signal?`) => `void`

##### Parameters

###### signal?

`"$sessionSignal"` | `Omit`\<`string`, `"$sessionSignal"`\>

##### Returns

`void`

### useSession()

> **useSession**: () => `object`

#### Returns

`object`

##### data

> **data**: \{ `session`: \{ `createdAt`: `Date`; `expiresAt`: `Date`; `id`: `string`; `ipAddress?`: `string` \| `null`; `token`: `string`; `updatedAt`: `Date`; `userAgent?`: `string` \| `null`; `userId`: `string`; \}; `user`: \{ `createdAt`: `Date`; `email`: `string`; `emailVerified`: `boolean`; `id`: `string`; `image?`: `string` \| `null`; `name`: `string`; `updatedAt`: `Date`; \}; \} \| `null`

##### error

> **error**: `BetterFetchError` \| `null`

##### isPending

> **isPending**: `boolean`

##### isRefetching

> **isRefetching**: `boolean`

##### refetch()

> **refetch**: (`queryParams?`) => `void`

###### Parameters

###### queryParams?

###### query?

`SessionQueryParams`

###### Returns

`void`

## Constant

authClient - Better Auth client instance

## Remarks

The baseURL is determined in the following order:
1. NEXT_PUBLIC_BETTER_AUTH_URL environment variable (if set)
2. window.location.origin (if in browser)
3. http://localhost:3000 (fallback for SSR)
