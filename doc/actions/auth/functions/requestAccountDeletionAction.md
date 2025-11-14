[**10x-devs**](../../../README.md)

***

[10x-devs](../../../modules.md) / [actions/auth](../README.md) / requestAccountDeletionAction

# Function: requestAccountDeletionAction()

> **requestAccountDeletionAction**(): `Promise`\<\{ `confirmationUrl?`: `undefined`; `message`: `string`; `requiresConfirmation?`: `undefined`; `success?`: `undefined`; \} \| \{ `confirmationUrl`: `string`; `message`: `string`; `requiresConfirmation`: `boolean`; `success`: `boolean`; \} \| \{ `confirmationUrl?`: `undefined`; `message`: `string`; `requiresConfirmation?`: `undefined`; `success`: `boolean`; \}\>

Defined in: [src/app/actions/auth.ts:357](https://github.com/jcubic/10xDevs/blob/8643271036ed0399a2b11ac87568ff44ec315445/src/app/actions/auth.ts#L357)

Server action to request account deletion via email confirmation.
Sends a confirmation email with a deletion link that expires in 24 hours.

## Returns

`Promise`\<\{ `confirmationUrl?`: `undefined`; `message`: `string`; `requiresConfirmation?`: `undefined`; `success?`: `undefined`; \} \| \{ `confirmationUrl`: `string`; `message`: `string`; `requiresConfirmation`: `boolean`; `success`: `boolean`; \} \| \{ `confirmationUrl?`: `undefined`; `message`: `string`; `requiresConfirmation?`: `undefined`; `success`: `boolean`; \}\>

State object with success status, confirmation URL (dev mode), or error messages

## Async

## Example

```tsx
<button onClick={async () => {
  const result = await requestAccountDeletionAction();
  if (result.success) {
    console.log('Confirmation email sent');
  }
}}>
  Delete Account
</button>
```

## Remarks

- Requires active user session
- Creates verification token valid for 24 hours
- Development mode: returns confirmation URL directly without sending email
- Production mode: sends email with deletion confirmation link
- Deletion is permanent and removes all user data and notes
- Email includes warning about irreversible data loss
