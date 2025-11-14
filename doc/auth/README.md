[**10x-devs**](../README.md)

***

[10x-devs](../modules.md) / auth

# auth

## Description

Server-side authentication configuration using Better Auth.
Provides email/password authentication, OAuth (GitHub), email verification,
password reset, and automatic welcome note creation for new users.

## Dependencies

- better-auth: Authentication framework
- @/lib/prisma: Database client
- @/lib/email: Email service for verification and password reset

## Remarks

- Email verification is required in production, disabled in development
- In development mode, password reset links are logged to console
- Database adapter switches between MySQL (prod/dev) and SQLite (CI)
- Creates a welcome note for each new user on first account creation

## Variables

- [auth](variables/auth.md)
