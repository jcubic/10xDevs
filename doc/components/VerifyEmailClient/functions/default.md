[**10x-devs**](../../../README.md)

***

[10x-devs](../../../modules.md) / [components/VerifyEmailClient](../README.md) / default

# Function: default()

> **default**(`props`): `Element`

Defined in: [src/components/VerifyEmailClient.tsx:138](https://github.com/jcubic/10xDevs/blob/8643271036ed0399a2b11ac87568ff44ec315445/src/components/VerifyEmailClient.tsx#L138)

Email verification result display with auto-redirect on success.

## Parameters

### props

`VerifyEmailClientProps`

Verification result props

## Returns

`Element`

Rendered verification result page

## Remarks

**Success Flow:**
1. Shows success alert with "Email Verified!" heading
2. Starts 3-second countdown timer
3. Displays countdown ("Redirecting in X seconds...")
4. Auto-redirects to `/login?message=email-verified`
5. User can skip countdown with "Sign In Now" button

**Error Flow:**
- Shows error alert with "Verification Failed" heading
- Displays error message (e.g., "Invalid token", "Token expired")
- Provides "Try Again" or "Register Again" button (based on isExpired)
- No auto-redirect (user must take action)

**Expired Token:**
- Special error state when `isExpired=true`
- Shows explanation: "Verification links expire after 24 hours"
- Button text changes to "Register Again"
- Redirects to `/register` instead of retry

**Accessibility:**
- Semantic heading hierarchy (h1)
- ARIA roles via Chakra Alert components
- Clear visual feedback (success=green, error=red)
- Countdown timer for auto-redirect awareness

## Examples

```tsx
// Success case
<VerifyEmailClient success={true} />
// Shows success message, counts down from 3, redirects to login
```

```tsx
// Error case
<VerifyEmailClient
  success={false}
  error="Invalid verification token"
/>
// Shows error message with retry button
```

```tsx
// Expired token case
<VerifyEmailClient
  success={false}
  error="This verification link has expired"
  isExpired={true}
/>
// Shows expired message with "Register Again" button
```
