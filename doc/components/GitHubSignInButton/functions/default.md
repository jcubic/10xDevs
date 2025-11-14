[**10x-devs**](../../../README.md)

***

[10x-devs](../../../modules.md) / [components/GitHubSignInButton](../README.md) / default

# Function: default()

> **default**(): `Element`

Defined in: [src/components/GitHubSignInButton.tsx:118](https://github.com/jcubic/10xDevs/blob/8643271036ed0399a2b11ac87568ff44ec315445/src/components/GitHubSignInButton.tsx#L118)

GitHub OAuth sign-in button with loading state.

## Returns

`Element`

Rendered GitHub sign-in button

## Remarks

**Behavior:**
- Disabled during sign-in process to prevent double-clicks
- Button text changes to "Signing in..." during loading
- Redirects to homepage (`/`) after successful authentication
- Loading state persists until OAuth flow completes or errors

**OAuth Flow:**
- Uses Better Auth's `authClient.signIn.social()` method
- Provider: `github`
- Callback URL: `/` (homepage)
- Better Auth handles OAuth redirect and token exchange

**Error Handling:**
- Errors logged to console (for debugging)
- Loading state reset to allow retry
- No user-facing error message (consider adding toast notification)

**Security:**
- OAuth handled by Better Auth (secure token exchange)
- No credentials stored client-side
- GitHub app credentials configured server-side

**Accessibility:**
- Disabled state prevents multiple submissions
- Loading text provides feedback
- High contrast colors (white on dark gray)

## Example

```tsx
// User clicks button
// -> Button shows "Signing in..."
// -> Redirects to GitHub authorization page
// -> User authorizes app
// -> Redirects back to app
// -> Better Auth processes callback
// -> User signed in and redirected to "/"
<GitHubSignInButton />
```
