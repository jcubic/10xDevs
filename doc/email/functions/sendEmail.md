[**10x-devs**](../../README.md)

***

[10x-devs](../../modules.md) / [email](../README.md) / sendEmail

# Function: sendEmail()

> **sendEmail**(`options`): `Promise`\<`void`\>

Defined in: [src/lib/email.ts:74](https://github.com/jcubic/10xDevs/blob/8643271036ed0399a2b11ac87568ff44ec315445/src/lib/email.ts#L74)

Sends an email via SMTP using configured nodemailer transport.

## Parameters

### options

`EmailOptions`

Email configuration options

## Returns

`Promise`\<`void`\>

Resolves when email is sent successfully

## Async

## Throws

Does not throw - errors are caught and logged to console

## Example

```ts
// Send verification email
await sendEmail({
  to: 'user@example.com',
  subject: 'Verify your email',
  text: 'Click here to verify: https://app.com/verify?token=abc123',
  html: '<p>Click <a href="https://app.com/verify?token=abc123">here</a> to verify</p>'
});
```

## Remarks

- Uses environment variables for SMTP configuration
- Port 465 uses secure: true, other ports use STARTTLS
- Errors are logged but not thrown to prevent auth flow interruption
- From address is set via SMTP_FROM_EMAIL environment variable
