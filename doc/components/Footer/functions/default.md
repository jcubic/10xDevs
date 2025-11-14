[**10x-devs**](../../../README.md)

***

[10x-devs](../../../modules.md) / [components/Footer](../README.md) / default

# Function: default()

> **default**(): `Element`

Defined in: [src/components/Footer.tsx:76](https://github.com/jcubic/10xDevs/blob/8643271036ed0399a2b11ac87568ff44ec315445/src/components/Footer.tsx#L76)

Application footer with copyright and license information.

## Returns

`Element`

Rendered footer with copyright text

## Remarks

**Display:**
- Copyright year dynamically generated from current date
- Format: "Copyright (C) YYYY Author Name <email> | License"
- Link to author's personal website (https://jakub.jankiewicz.org/)

**Styling:**
- Subtle background (`bg.subtle`)
- Top border for visual separation
- Small font size (xs)
- Muted text color
- Minimal padding (1px vertical, 4px horizontal)
- Centered text

**License:**
- AGPL-3.0-or-later (GNU Affero General Public License v3.0 or later)
- Suitable for open-source web applications

## Example

```tsx
// Output: "Copyright (C) 2025 Jakub T. Jankiewicz <jcubic@onet.pl> | AGPL-3.0-or-later"
<Footer />
```
