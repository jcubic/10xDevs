[**10x-devs**](../../../README.md)

***

[10x-devs](../../../modules.md) / [test/utils](../README.md) / renderHook

# Function: renderHook()

> **renderHook**\<`Result`, `Props`, `Q`, `Container`, `BaseElement`\>(`render`, `options?`): [`RenderHookResult`](../interfaces/RenderHookResult.md)\<`Result`, `Props`\>

Defined in: node\_modules/@testing-library/react/types/index.d.ts:263

Allows you to render a hook within a test React component without having to
create that component yourself.

## Type Parameters

### Result

`Result`

### Props

`Props`

### Q

`Q` *extends* [`Queries`](../interfaces/Queries.md) = [`queries`](../namespaces/queries/README.md)

### Container

`Container` *extends* `Container` = `HTMLElement`

### BaseElement

`BaseElement` *extends* `Container` = `Container`

## Parameters

### render

(`initialProps`) => `Result`

### options?

[`RenderHookOptions`](../interfaces/RenderHookOptions.md)\<`Props`, `Q`, `Container`, `BaseElement`\>

## Returns

[`RenderHookResult`](../interfaces/RenderHookResult.md)\<`Result`, `Props`\>
