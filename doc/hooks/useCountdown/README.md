[**10x-devs**](../../README.md)

***

[10x-devs](../../modules.md) / hooks/useCountdown

# hooks/useCountdown

## Description

Custom React hook for countdown timer functionality.
Provides a simple countdown timer that automatically calls a callback when reaching zero.

## Example

```tsx
function ResendButton() {
  const [canResend, setCanResend] = useState(false);
  const countdown = useCountdown({
    initialCount: 60,
    onComplete: () => setCanResend(true),
    enabled: !canResend
  });

  return (
    <button disabled={!canResend}>
      {canResend ? 'Resend Email' : `Wait ${countdown}s`}
    </button>
  );
}
```

## Functions

- [useCountdown](functions/useCountdown.md)
