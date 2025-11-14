[**10x-devs**](../README.md)

***

[10x-devs](../modules.md) / auth-client

# auth-client

## Description

Client-side authentication utilities for React components.
Provides hooks and methods for sign in, sign up, sign out, and session management.

## Dependencies

- better-auth/react: Client-side authentication framework

## Remarks

- Uses NEXT_PUBLIC_BETTER_AUTH_URL or falls back to window.location.origin
- Only works in client components (marked with 'use client')
- Session state is managed via React hooks and automatically synchronized

## Example

```tsx
'use client';
import { useSession, signIn, signOut } from '@/lib/auth-client';

export default function MyComponent() {
  const { data: session, isPending } = useSession();

  if (isPending) return <div>Loading...</div>;

  if (session) {
    return (
      <div>
        <p>Welcome, {session.user.name}!</p>
        <button onClick={() => signOut()}>Sign Out</button>
      </div>
    );
  }

  return <button onClick={() => signIn.email({ email, password })}>Sign In</button>;
}
```

## Variables

- [authClient](variables/authClient.md)
- [signIn](variables/signIn.md)
- [signOut](variables/signOut.md)
- [signUp](variables/signUp.md)
- [useSession](variables/useSession.md)
