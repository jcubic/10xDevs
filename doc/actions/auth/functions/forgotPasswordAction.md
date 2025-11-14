[**10x-devs**](../../../README.md)

***

[10x-devs](../../../modules.md) / [actions/auth](../README.md) / forgotPasswordAction

# Function: forgotPasswordAction()

> **forgotPasswordAction**(`_prevState`, `formData`): `Promise`\<\{ `email?`: `undefined`; `errors`: \{ `email?`: `string`[]; \}; `message`: `string`; `success?`: `undefined`; \} \| \{ `email`: `string`; `errors?`: `undefined`; `message?`: `undefined`; `success`: `boolean`; \} \| \{ `email?`: `undefined`; `errors?`: `undefined`; `message`: `string`; `success?`: `undefined`; \}\>

Defined in: [src/app/actions/auth.ts:797](https://github.com/jcubic/10xDevs/blob/8643271036ed0399a2b11ac87568ff44ec315445/src/app/actions/auth.ts#L797)

Server action to initiate password reset flow.
Sends password reset email with token-based reset link.

## Parameters

### \_prevState

[`FormDataState`](../interfaces/FormDataState.md)

Previous form state (unused)

### formData

`FormData`

Form data containing user email

## Returns

`Promise`\<\{ `email?`: `undefined`; `errors`: \{ `email?`: `string`[]; \}; `message`: `string`; `success?`: `undefined`; \} \| \{ `email`: `string`; `errors?`: `undefined`; `message?`: `undefined`; `success`: `boolean`; \} \| \{ `email?`: `undefined`; `errors?`: `undefined`; `message`: `string`; `success?`: `undefined`; \}\>

State object with success status and email, or error message

## Async

## Example

```tsx
const [state, action] = useActionState(forgotPasswordAction, {});

<form action={action}>
  <input name="email" type="email" required />
  <button type="submit">Send Reset Link</button>
</form>

{state.success && <p>Reset link sent to {state.email}</p>}
```

## Remarks

- Always returns success to prevent email enumeration attacks
- Sends email with password reset link to /reset-password page
- Reset link includes token for authentication
- Email is sent via Better Auth's forgetPassword API
- Base URL determined from BETTER_AUTH_URL environment variable
