[**10x-devs**](../../README.md)

***

[10x-devs](../../modules.md) / actions/auth

# actions/auth

## Description

Server actions for authentication operations.
Provides form handlers for sign up, sign in, password management, account deletion,
email verification, and password reset flows.

## Dependencies

- next/headers: Server-side header access for Better Auth
- zod: Schema validation for form inputs
- @/lib/auth: Server-side authentication instance
- @/lib/email: Email service for notifications
- @/lib/prisma: Database client for account queries

## Remarks

- All functions are server actions (marked with 'use server')
- Email verification is required in production, disabled in development
- Password requirements: minimum 8 characters
- All functions return FormDataState for useActionState hook compatibility
- Account deletion requires email confirmation with 24-hour expiry

## Example

```tsx
'use client';
import { useActionState } from 'react';
import { signInAction } from '@/app/actions/auth';

export default function SignInForm() {
  const [state, action, pending] = useActionState(signInAction, {});

  return (
    <form action={action}>
      <input name="email" type="email" required />
      <input name="password" type="password" required />
      {state.message && <p>{state.message}</p>}
      <button disabled={pending}>Sign In</button>
    </form>
  );
}
```

## Interfaces

- [FormDataState](interfaces/FormDataState.md)

## Functions

- [changePasswordAction](functions/changePasswordAction.md)
- [forgotPasswordAction](functions/forgotPasswordAction.md)
- [getUserAuthMethod](functions/getUserAuthMethod.md)
- [requestAccountDeletionAction](functions/requestAccountDeletionAction.md)
- [resetPasswordAction](functions/resetPasswordAction.md)
- [signInAction](functions/signInAction.md)
- [signOutAction](functions/signOutAction.md)
- [signUpAction](functions/signUpAction.md)
- [verifyEmailAction](functions/verifyEmailAction.md)
