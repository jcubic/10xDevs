[**10x-devs**](../../../README.md)

***

[10x-devs](../../../modules.md) / [actions/auth](../README.md) / getUserAuthMethod

# Function: getUserAuthMethod()

> **getUserAuthMethod**(): `Promise`\<\{ `hasPassword`: `boolean`; \}\>

Defined in: [src/app/actions/auth.ts:512](https://github.com/jcubic/10xDevs/blob/8643271036ed0399a2b11ac87568ff44ec315445/src/app/actions/auth.ts#L512)

Checks if the current user has password authentication enabled.
Used to determine if password change is available.

## Returns

`Promise`\<\{ `hasPassword`: `boolean`; \}\>

Object indicating if user has password auth

## Async

## Example

```tsx
const { hasPassword } = await getUserAuthMethod();
if (hasPassword) {
  // Show password change form
} else {
  // Show OAuth-only message
}
```

## Remarks

- Returns false if no active session
- Only checks for 'credential' provider (email/password)
- OAuth-only users will have hasPassword: false
- Used in settings page to conditionally show password change form
