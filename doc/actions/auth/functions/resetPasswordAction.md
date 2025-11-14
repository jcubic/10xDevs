[**10x-devs**](../../../README.md)

***

[10x-devs](../../../modules.md) / [actions/auth](../README.md) / resetPasswordAction

# Function: resetPasswordAction()

> **resetPasswordAction**(`_prevState`, `formData`): `Promise`\<\{ `errors`: \{ `confirmPassword?`: `string`[]; `password?`: `string`[]; `token?`: `string`[]; \}; `message`: `string`; `success?`: `undefined`; \} \| \{ `errors?`: `undefined`; `message`: `string`; `success?`: `undefined`; \} \| \{ `errors?`: `undefined`; `message?`: `undefined`; `success`: `boolean`; \}\>

Defined in: [src/app/actions/auth.ts:884](https://github.com/jcubic/10xDevs/blob/8643271036ed0399a2b11ac87568ff44ec315445/src/app/actions/auth.ts#L884)

Server action to reset user password using a reset token.
Completes the password reset flow initiated by forgotPasswordAction.

## Parameters

### \_prevState

[`FormDataState`](../interfaces/FormDataState.md)

Previous form state (unused)

### formData

`FormData`

Form data with password, confirmPassword, and token

## Returns

`Promise`\<\{ `errors`: \{ `confirmPassword?`: `string`[]; `password?`: `string`[]; `token?`: `string`[]; \}; `message`: `string`; `success?`: `undefined`; \} \| \{ `errors?`: `undefined`; `message`: `string`; `success?`: `undefined`; \} \| \{ `errors?`: `undefined`; `message?`: `undefined`; `success`: `boolean`; \}\>

State object with success status or error messages

## Async

## Example

```tsx
const [state, action] = useActionState(resetPasswordAction, {});
const token = searchParams.get('token');

<form action={action}>
  <input type="hidden" name="token" value={token} />
  <input name="password" type="password" minLength={8} required />
  <input name="confirmPassword" type="password" required />
  <button type="submit">Reset Password</button>
</form>
```

## Remarks

- Token comes from email reset link query parameter
- Password must be at least 8 characters
- Passwords must match between password and confirmPassword
- Token can expire or become invalid
- Returns generic error for invalid/expired tokens
- Success allows immediate sign-in with new password
