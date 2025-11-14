[**10x-devs**](../../../../README.md)

***

[10x-devs](../../../../modules.md) / [components/notes/TopNavigationBar](../README.md) / default

# Variable: default

> `const` **default**: `NamedExoticComponent`\<`TopNavigationBarProps`\>

Defined in: [src/components/notes/TopNavigationBar.tsx:65](https://github.com/jcubic/10xDevs/blob/8643271036ed0399a2b11ac87568ff44ec315445/src/components/notes/TopNavigationBar.tsx#L65)

Renders the application's top navigation bar with branding and user controls.

## Param

Component props

## Param

Flag indicating unsaved content

## Param

Flag indicating authentication status

## Param

Handler for settings button click

## Param

Handler for logout button click

## Returns

Memoized navigation bar component

## Remarks

Memoized to prevent unnecessary re-renders when parent state changes.
Uses semantic HTML with `<header>` element for accessibility.
