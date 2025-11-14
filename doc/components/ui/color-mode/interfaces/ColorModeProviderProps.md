[**10x-devs**](../../../../README.md)

***

[10x-devs](../../../../modules.md) / [components/ui/color-mode](../README.md) / ColorModeProviderProps

# Interface: ColorModeProviderProps

Defined in: [src/components/ui/color-mode.tsx:10](https://github.com/jcubic/10xDevs/blob/8643271036ed0399a2b11ac87568ff44ec315445/src/components/ui/color-mode.tsx#L10)

## Extends

- `ThemeProviderProps`

## Properties

### attribute?

> `optional` **attribute**: `Attribute` \| `Attribute`[]

Defined in: node\_modules/next-themes/dist/index.d.ts:41

HTML attribute modified based on the active theme. Accepts `class`, `data-*` (meaning any data attribute, `data-mode`, `data-color`, etc.), or an array which could include both

#### Inherited from

`ThemeProviderProps.attribute`

***

### children?

> `optional` **children**: `ReactNode`

Defined in: node\_modules/@types/react/index.d.ts:1414

#### Inherited from

`ThemeProviderProps.children`

***

### defaultTheme?

> `optional` **defaultTheme**: `string`

Defined in: node\_modules/next-themes/dist/index.d.ts:39

Default theme name (for v0.0.12 and lower the default was light). If `enableSystem` is false, the default theme is light

#### Inherited from

`ThemeProviderProps.defaultTheme`

***

### disableTransitionOnChange?

> `optional` **disableTransitionOnChange**: `boolean`

Defined in: node\_modules/next-themes/dist/index.d.ts:33

Disable all CSS transitions when switching themes

#### Inherited from

`ThemeProviderProps.disableTransitionOnChange`

***

### enableColorScheme?

> `optional` **enableColorScheme**: `boolean`

Defined in: node\_modules/next-themes/dist/index.d.ts:35

Whether to indicate to browsers which color scheme is used (dark or light) for built-in UI like inputs and buttons

#### Inherited from

`ThemeProviderProps.enableColorScheme`

***

### enableSystem?

> `optional` **enableSystem**: `boolean`

Defined in: node\_modules/next-themes/dist/index.d.ts:31

Whether to switch between dark and light themes based on prefers-color-scheme

#### Inherited from

`ThemeProviderProps.enableSystem`

***

### forcedTheme?

> `optional` **forcedTheme**: `string`

Defined in: node\_modules/next-themes/dist/index.d.ts:29

Forced theme name for the current page

#### Inherited from

`ThemeProviderProps.forcedTheme`

***

### nonce?

> `optional` **nonce**: `string`

Defined in: node\_modules/next-themes/dist/index.d.ts:45

Nonce string to pass to the inline script and style elements for CSP headers

#### Inherited from

`ThemeProviderProps.nonce`

***

### scriptProps?

> `optional` **scriptProps**: `ScriptProps`

Defined in: node\_modules/next-themes/dist/index.d.ts:47

Props to pass the inline script

#### Inherited from

`ThemeProviderProps.scriptProps`

***

### storageKey?

> `optional` **storageKey**: `string`

Defined in: node\_modules/next-themes/dist/index.d.ts:37

Key used to store theme setting in localStorage

#### Inherited from

`ThemeProviderProps.storageKey`

***

### themes?

> `optional` **themes**: `string`[]

Defined in: node\_modules/next-themes/dist/index.d.ts:27

List of all available theme names

#### Inherited from

`ThemeProviderProps.themes`

***

### value?

> `optional` **value**: `ValueObject`

Defined in: node\_modules/next-themes/dist/index.d.ts:43

Mapping of theme name to HTML attribute value. Object where key is the theme name and value is the attribute value

#### Inherited from

`ThemeProviderProps.value`
