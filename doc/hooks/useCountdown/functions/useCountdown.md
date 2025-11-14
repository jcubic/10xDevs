[**10x-devs**](../../../README.md)

***

[10x-devs](../../../modules.md) / [hooks/useCountdown](../README.md) / useCountdown

# Function: useCountdown()

> **useCountdown**(`options`): `number`

Defined in: [src/hooks/useCountdown.ts:72](https://github.com/jcubic/10xDevs/blob/8643271036ed0399a2b11ac87568ff44ec315445/src/hooks/useCountdown.ts#L72)

Custom hook for countdown timer functionality.
Counts down from initialCount to 0, calling onComplete when finished.

## Parameters

### options

`UseCountdownOptions`

Hook configuration options

## Returns

`number`

Current countdown value

## Example

```tsx
// Basic countdown
const count = useCountdown({
  initialCount: 30,
  onComplete: () => console.log('Done!')
});

// Conditional countdown
const count = useCountdown({
  initialCount: 60,
  onComplete: handleComplete,
  enabled: isWaiting
});
```

## Remarks

- Countdown ticks every 1 second
- onComplete callback is stored in ref to avoid stale closures
- Timer auto-stops at 0 and calls onComplete
- enabled flag allows pausing/resuming countdown
- Timer cleanup happens on unmount
- Re-initializing requires remounting the component
