[**10x-devs**](../../../../README.md)

***

[10x-devs](../../../../modules.md) / [components/ui/tooltip](../README.md) / TooltipProps

# Interface: TooltipProps

Defined in: [src/components/ui/tooltip.tsx:4](https://github.com/jcubic/10xDevs/blob/8643271036ed0399a2b11ac87568ff44ec315445/src/components/ui/tooltip.tsx#L4)

## Extends

- `TooltipRootProps`

## Properties

### aria-label?

> `optional` **aria-label**: `string`

Defined in: node\_modules/@zag-js/tooltip/dist/index.d.mts:69

Custom label for the tooltip.

#### Inherited from

`ChakraTooltip.RootProps.aria-label`

***

### children?

> `optional` **children**: `ReactNode`

Defined in: node\_modules/@chakra-ui/react/dist/types/components/tooltip/tooltip.d.ts:15

#### Inherited from

`ChakraTooltip.RootProps.children`

***

### closeDelay?

> `optional` **closeDelay**: `number`

Defined in: node\_modules/@zag-js/tooltip/dist/index.d.mts:33

The close delay of the tooltip.

#### Default

```ts
150
```

#### Inherited from

`ChakraTooltip.RootProps.closeDelay`

***

### closeOnClick?

> `optional` **closeOnClick**: `boolean`

Defined in: node\_modules/@zag-js/tooltip/dist/index.d.mts:53

Whether the tooltip should close on click

#### Default

```ts
true
```

#### Inherited from

`ChakraTooltip.RootProps.closeOnClick`

***

### closeOnEscape?

> `optional` **closeOnEscape**: `boolean`

Defined in: node\_modules/@zag-js/tooltip/dist/index.d.mts:43

Whether to close the tooltip when the Escape key is pressed.

#### Default

```ts
true
```

#### Inherited from

`ChakraTooltip.RootProps.closeOnEscape`

***

### closeOnPointerDown?

> `optional` **closeOnPointerDown**: `boolean`

Defined in: node\_modules/@zag-js/tooltip/dist/index.d.mts:38

Whether to close the tooltip on pointerdown.

#### Default

```ts
true
```

#### Inherited from

`ChakraTooltip.RootProps.closeOnPointerDown`

***

### closeOnScroll?

> `optional` **closeOnScroll**: `boolean`

Defined in: node\_modules/@zag-js/tooltip/dist/index.d.mts:48

Whether the tooltip should close on scroll

#### Default

```ts
true
```

#### Inherited from

`ChakraTooltip.RootProps.closeOnScroll`

***

### content

> **content**: `ReactNode`

Defined in: [src/components/ui/tooltip.tsx:8](https://github.com/jcubic/10xDevs/blob/8643271036ed0399a2b11ac87568ff44ec315445/src/components/ui/tooltip.tsx#L8)

***

### contentProps?

> `optional` **contentProps**: `TooltipContentProps`

Defined in: [src/components/ui/tooltip.tsx:9](https://github.com/jcubic/10xDevs/blob/8643271036ed0399a2b11ac87568ff44ec315445/src/components/ui/tooltip.tsx#L9)

***

### defaultOpen?

> `optional` **defaultOpen**: `boolean`

Defined in: node\_modules/@zag-js/tooltip/dist/index.d.mts:86

The initial open state of the tooltip when rendered.
Use when you don't need to control the open state of the tooltip.

#### Inherited from

`ChakraTooltip.RootProps.defaultOpen`

***

### disabled?

> `optional` **disabled**: `boolean`

Defined in: [src/components/ui/tooltip.tsx:10](https://github.com/jcubic/10xDevs/blob/8643271036ed0399a2b11ac87568ff44ec315445/src/components/ui/tooltip.tsx#L10)

Whether the tooltip is disabled

#### Overrides

`ChakraTooltip.RootProps.disabled`

***

### id?

> `optional` **id**: `string`

Defined in: node\_modules/@zag-js/types/dist/index.d.mts:1471

The unique identifier of the machine.

#### Inherited from

`ChakraTooltip.RootProps.id`

***

### ids?

> `optional` **ids**: `Partial`\<\{ `arrow`: `string`; `content`: `string`; `positioner`: `string`; `trigger`: `string`; \}\>

Defined in: node\_modules/@zag-js/tooltip/dist/index.d.mts:23

The ids of the elements in the tooltip. Useful for composition.

#### Inherited from

`ChakraTooltip.RootProps.ids`

***

### immediate?

> `optional` **immediate**: `boolean`

Defined in: node\_modules/@zag-js/presence/dist/index.d.mts:17

Whether to synchronize the present change immediately or defer it to the next frame

#### Inherited from

`ChakraTooltip.RootProps.immediate`

***

### interactive?

> `optional` **interactive**: `boolean`

Defined in: node\_modules/@zag-js/tooltip/dist/index.d.mts:61

Whether the tooltip's content is interactive.
In this mode, the tooltip will remain open when user hovers over the content.

#### See

https://www.w3.org/TR/WCAG21/#content-on-hover-or-focus

#### Default

```ts
false
```

#### Inherited from

`ChakraTooltip.RootProps.interactive`

***

### lazyMount?

> `optional` **lazyMount**: `boolean`

Defined in: node\_modules/@ark-ui/react/dist/utils/render-strategy.d.ts:7

Whether to enable lazy mounting

#### Default

```ts
false
```

#### Inherited from

`ChakraTooltip.RootProps.lazyMount`

***

### onExitComplete?

> `optional` **onExitComplete**: `VoidFunction`

Defined in: node\_modules/@zag-js/presence/dist/index.d.mts:13

Function called when the animation ends in the closed state

#### Inherited from

`ChakraTooltip.RootProps.onExitComplete`

***

### onOpenChange()?

> `optional` **onOpenChange**: (`details`) => `void`

Defined in: node\_modules/@zag-js/tooltip/dist/index.d.mts:65

Function called when the tooltip is opened.

#### Parameters

##### details

`OpenChangeDetails`

#### Returns

`void`

#### Inherited from

`ChakraTooltip.RootProps.onOpenChange`

***

### open?

> `optional` **open**: `boolean`

Defined in: node\_modules/@zag-js/tooltip/dist/index.d.mts:81

The controlled open state of the tooltip

#### Inherited from

`ChakraTooltip.RootProps.open`

***

### openDelay?

> `optional` **openDelay**: `number`

Defined in: node\_modules/@zag-js/tooltip/dist/index.d.mts:28

The open delay of the tooltip.

#### Default

```ts
400
```

#### Inherited from

`ChakraTooltip.RootProps.openDelay`

***

### portalled?

> `optional` **portalled**: `boolean`

Defined in: [src/components/ui/tooltip.tsx:6](https://github.com/jcubic/10xDevs/blob/8643271036ed0399a2b11ac87568ff44ec315445/src/components/ui/tooltip.tsx#L6)

***

### portalRef?

> `optional` **portalRef**: `RefObject`\<`HTMLElement` \| `null`\>

Defined in: [src/components/ui/tooltip.tsx:7](https://github.com/jcubic/10xDevs/blob/8643271036ed0399a2b11ac87568ff44ec315445/src/components/ui/tooltip.tsx#L7)

***

### positioning?

> `optional` **positioning**: `PositioningOptions`

Defined in: node\_modules/@zag-js/tooltip/dist/index.d.mts:73

The user provided options used to position the popover content

#### Inherited from

`ChakraTooltip.RootProps.positioning`

***

### present?

> `optional` **present**: `boolean`

Defined in: node\_modules/@zag-js/presence/dist/index.d.mts:9

Whether the node is present (controlled by the user)

#### Inherited from

`ChakraTooltip.RootProps.present`

***

### recipe?

> `optional` **recipe**: `SlotRecipeDefinition`\<`string`, `SlotRecipeVariantRecord`\<`string`\>\>

Defined in: node\_modules/@chakra-ui/react/dist/types/styled-system/generated/recipes.gen.d.ts:1562

#### Inherited from

`ChakraTooltip.RootProps.recipe`

***

### showArrow?

> `optional` **showArrow**: `boolean`

Defined in: [src/components/ui/tooltip.tsx:5](https://github.com/jcubic/10xDevs/blob/8643271036ed0399a2b11ac87568ff44ec315445/src/components/ui/tooltip.tsx#L5)

***

### skipAnimationOnMount?

> `optional` **skipAnimationOnMount**: `boolean`

Defined in: node\_modules/@ark-ui/react/dist/components/presence/use-presence.d.ts:9

Whether to allow the initial presence animation.

#### Default

```ts
false
```

#### Inherited from

`ChakraTooltip.RootProps.skipAnimationOnMount`

***

### unmountOnExit?

> `optional` **unmountOnExit**: `boolean`

Defined in: node\_modules/@ark-ui/react/dist/utils/render-strategy.d.ts:12

Whether to unmount on exit.

#### Default

```ts
false
```

#### Inherited from

`ChakraTooltip.RootProps.unmountOnExit`

***

### unstyled?

> `optional` **unstyled**: `boolean`

Defined in: node\_modules/@chakra-ui/react/dist/types/styled-system/factory.types.d.ts:11

If `true`, the element will opt out of the theme styles.

#### Inherited from

`ChakraTooltip.RootProps.unstyled`
