[**10x-devs**](../../../README.md)

***

[10x-devs](../../../modules.md) / [actions/auth](../README.md) / signOutAction

# Function: signOutAction()

> **signOutAction**(): `Promise`\<`void`\>

Defined in: [src/app/actions/auth.ts:318](https://github.com/jcubic/10xDevs/blob/8643271036ed0399a2b11ac87568ff44ec315445/src/app/actions/auth.ts#L318)

Server action for signing out the current user.
Clears the user's session and authentication cookies.

## Returns

`Promise`\<`void`\>

Resolves when sign out is complete

## Async

## Example

```tsx
<button onClick={async () => await signOutAction()}>
  Sign Out
</button>
```

## Remarks

- Errors during sign out are logged but not thrown
- Safe to call even if no active session exists
- Redirects are handled by the client-side router
