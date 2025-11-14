[**10x-devs**](../../README.md)

***

[10x-devs](../../modules.md) / [auth](../README.md) / auth

# Variable: auth

> `const` **auth**: `Auth`\<\{ `baseURL`: `string` \| `undefined`; `database`: (`options`) => `DBAdapter`\<`BetterAuthOptions`\>; `databaseHooks`: \{ `account`: \{ `create`: \{ `after`: (`account`) => `Promise`\<`void`\>; \}; \}; \}; `emailAndPassword`: \{ `enabled`: `true`; `requireEmailVerification`: `boolean`; `sendResetPassword`: (`__namedParameters`) => `Promise`\<`void`\>; \}; `emailVerification`: \{ `autoSignInAfterVerification`: `true`; `sendVerificationEmail`: (`__namedParameters`) => `Promise`\<`void`\>; \}; `plugins`: \[\{ `hooks`: \{ `after`: `object`[]; \}; `id`: `"next-cookies"`; \}\]; `secret`: `string` \| `undefined`; `socialProviders?`: \{ `github`: \{ `clientId`: `string`; `clientSecret`: `string`; \}; \}; `telemetry`: \{ `enabled`: `false`; \}; \}\>

Defined in: [src/lib/auth.ts:56](https://github.com/jcubic/10xDevs/blob/8643271036ed0399a2b11ac87568ff44ec315445/src/lib/auth.ts#L56)

Authentication instance configured with Better Auth.

## Constant

auth - Better Auth instance

## Example

```ts
// In server components or API routes
import { auth } from '@/lib/auth';

const session = await auth.api.getSession({ headers: await headers() });
if (session?.user) {
  console.log('User is authenticated:', session.user.email);
}
```

## Remarks

- GitHub OAuth is only enabled if GITHUB_CLIENT_ID and GITHUB_CLIENT_SECRET are set
- Database hooks create a welcome note for new users on first account creation
- Email verification and password reset use different logic in development vs production
- Telemetry is disabled for privacy
