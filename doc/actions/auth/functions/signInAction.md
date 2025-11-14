[**10x-devs**](../../../README.md)

***

[10x-devs](../../../modules.md) / [actions/auth](../README.md) / signInAction

# Function: signInAction()

> **signInAction**(`_prevState`, `formData`): `Promise`\<\{ `errors`: \{ `email?`: `string`[]; `password?`: `string`[]; \}; `message`: `string`; `success?`: `undefined`; \} \| \{ `errors?`: `undefined`; `message`: `string`; `success?`: `undefined`; \} \| \{ `errors?`: `undefined`; `message?`: `undefined`; `success`: `boolean`; \}\>

Defined in: [src/app/actions/auth.ts:240](https://github.com/jcubic/10xDevs/blob/8643271036ed0399a2b11ac87568ff44ec315445/src/app/actions/auth.ts#L240)

Server action for user sign in with email and password.

## Parameters

### \_prevState

Previous form state (unused, required by useActionState)

#### errors?

`Record`\<`string`, `string`[]\>

#### message?

`string`

### formData

`FormData`

Form data containing email and password

## Returns

`Promise`\<\{ `errors`: \{ `email?`: `string`[]; `password?`: `string`[]; \}; `message`: `string`; `success?`: `undefined`; \} \| \{ `errors?`: `undefined`; `message`: `string`; `success?`: `undefined`; \} \| \{ `errors?`: `undefined`; `message?`: `undefined`; `success`: `boolean`; \}\>

State object with success status or error messages

## Async

## Example

```tsx
const [state, action] = useActionState(signInAction, {});

<form action={action}>
  <input name="email" type="email" required />
  <input name="password" type="password" required />
</form>
```

## Remarks

- Validates email format and password presence
- Returns specific error messages for invalid credentials
- Success state has no message to trigger auto-redirect
