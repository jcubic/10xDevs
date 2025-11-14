[**10x-devs**](../../../README.md)

***

[10x-devs](../../../modules.md) / [actions/auth](../README.md) / signUpAction

# Function: signUpAction()

> **signUpAction**(`_prevState`, `formData`): `Promise`\<\{ `email?`: `undefined`; `errors`: \{ `email?`: `string`[]; `name?`: `string`[]; `password?`: `string`[]; \}; `message`: `string`; `success?`: `undefined`; \} \| \{ `email?`: `undefined`; `errors?`: `undefined`; `message`: `string`; `success?`: `undefined`; \} \| \{ `email`: `string`; `errors?`: `undefined`; `message`: `string`; `success`: `boolean`; \} \| \{ `email`: `string`; `errors?`: `undefined`; `message?`: `undefined`; `success`: `boolean`; \}\>

Defined in: [src/app/actions/auth.ts:129](https://github.com/jcubic/10xDevs/blob/8643271036ed0399a2b11ac87568ff44ec315445/src/app/actions/auth.ts#L129)

Server action for user sign up with email and password.
Creates a new user account with email verification in production.

## Parameters

### \_prevState

[`FormDataState`](../interfaces/FormDataState.md)

Previous form state (unused, required by useActionState)

### formData

`FormData`

Form data containing email, password, and name

## Returns

`Promise`\<\{ `email?`: `undefined`; `errors`: \{ `email?`: `string`[]; `name?`: `string`[]; `password?`: `string`[]; \}; `message`: `string`; `success?`: `undefined`; \} \| \{ `email?`: `undefined`; `errors?`: `undefined`; `message`: `string`; `success?`: `undefined`; \} \| \{ `email`: `string`; `errors?`: `undefined`; `message`: `string`; `success`: `boolean`; \} \| \{ `email`: `string`; `errors?`: `undefined`; `message?`: `undefined`; `success`: `boolean`; \}\>

State object with success status, errors, or messages

## Async

## Throws

Does not throw - returns error state instead

## Example

```tsx
const [state, action] = useActionState(signUpAction, {});

<form action={action}>
  <input name="email" type="email" required />
  <input name="password" type="password" minLength={8} required />
  <input name="name" type="text" required />
  <button type="submit">Sign Up</button>
</form>
```

## Remarks

- Password must be at least 8 characters
- In production: sends verification email, requires email confirmation
- In development: auto-signs in user without email verification
- Creates welcome note for new users via auth database hooks
- Returns `success: true` without message to trigger auto-redirect in dev mode
