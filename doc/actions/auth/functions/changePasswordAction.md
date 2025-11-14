[**10x-devs**](../../../README.md)

***

[10x-devs](../../../modules.md) / [actions/auth](../README.md) / changePasswordAction

# Function: changePasswordAction()

> **changePasswordAction**(`_prevState`, `formData`): `Promise`\<\{ `errors`: \{ `confirmPassword?`: `string`[]; `currentPassword?`: `string`[]; `newPassword?`: `string`[]; \}; `message`: `string`; `success?`: `undefined`; \} \| \{ `errors?`: `undefined`; `message`: `string`; `success?`: `undefined`; \} \| \{ `errors`: \{ `currentPassword`: `string`[]; \} \| `undefined`; `message`: `string`; `success?`: `undefined`; \} \| \{ `errors?`: `undefined`; `message`: `string`; `success`: `boolean`; \}\>

Defined in: [src/app/actions/auth.ts:569](https://github.com/jcubic/10xDevs/blob/8643271036ed0399a2b11ac87568ff44ec315445/src/app/actions/auth.ts#L569)

Server action to change user password.
Validates current password and updates to new password.

## Parameters

### \_prevState

[`FormDataState`](../interfaces/FormDataState.md)

Previous form state (unused)

### formData

`FormData`

Form data with currentPassword, newPassword, confirmPassword

## Returns

`Promise`\<\{ `errors`: \{ `confirmPassword?`: `string`[]; `currentPassword?`: `string`[]; `newPassword?`: `string`[]; \}; `message`: `string`; `success?`: `undefined`; \} \| \{ `errors?`: `undefined`; `message`: `string`; `success?`: `undefined`; \} \| \{ `errors`: \{ `currentPassword`: `string`[]; \} \| `undefined`; `message`: `string`; `success?`: `undefined`; \} \| \{ `errors?`: `undefined`; `message`: `string`; `success`: `boolean`; \}\>

State object with success status or error messages

## Async

## Example

```tsx
const [state, action] = useActionState(changePasswordAction, {});

<form action={action}>
  <input name="currentPassword" type="password" required />
  <input name="newPassword" type="password" minLength={8} required />
  <input name="confirmPassword" type="password" required />
</form>
```

## Remarks

- Requires active user session
- Only available for email/password accounts (not OAuth-only)
- New password must be at least 8 characters
- New password must differ from current password
- Passwords must match between newPassword and confirmPassword
- Does not revoke other sessions (revokeOtherSessions: false)
- Returns field-specific errors for validation failures
