[**10x-devs**](../../../README.md)

***

[10x-devs](../../../modules.md) / [actions/auth](../README.md) / verifyEmailAction

# Function: verifyEmailAction()

> **verifyEmailAction**(`token`): `Promise`\<\{ `error`: `string`; `isExpired`: `boolean`; `success`: `boolean`; \} \| \{ `error?`: `undefined`; `isExpired?`: `undefined`; `success`: `boolean`; \}\>

Defined in: [src/app/actions/auth.ts:703](https://github.com/jcubic/10xDevs/blob/8643271036ed0399a2b11ac87568ff44ec315445/src/app/actions/auth.ts#L703)

Server action to verify user email address using a verification token.
Called when user clicks email verification link.

## Parameters

### token

`string`

Email verification token from the verification link

## Returns

`Promise`\<\{ `error`: `string`; `isExpired`: `boolean`; `success`: `boolean`; \} \| \{ `error?`: `undefined`; `isExpired?`: `undefined`; `success`: `boolean`; \}\>

Verification result

## Async

## Example

```tsx
// In verify-email page
const token = searchParams.get('token');
const result = await verifyEmailAction(token);

if (result.success) {
  // Show success message and redirect
} else if (result.isExpired) {
  // Show resend verification option
}
```

## Remarks

- Token is generated during sign-up and sent via email
- Tokens can expire or become invalid
- Returns isExpired flag for expired/invalid tokens
- Successful verification enables full account access
- Does not require active session (token provides authentication)
