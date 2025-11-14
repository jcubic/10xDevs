[**10x-devs**](../README.md)

***

[10x-devs](../modules.md) / email

# email

## Description

Email service for sending transactional emails via SMTP.
Used for email verification, password reset, and account deletion confirmation.

## Dependencies

- nodemailer: SMTP client for sending emails

## Remarks

- Requires SMTP environment variables: SMTP_HOST, SMTP_PORT, SMTP_USERNAME, SMTP_PASSWORD, SMTP_FROM_EMAIL
- Errors are logged to console but do not throw to prevent breaking auth flows
- Port 465 uses secure connection, other ports use STARTTLS

## Example

```ts
await sendEmail({
  to: 'user@example.com',
  subject: 'Welcome!',
  html: '<h1>Welcome to our app!</h1>',
  text: 'Welcome to our app!'
});
```

## Functions

- [sendEmail](functions/sendEmail.md)
