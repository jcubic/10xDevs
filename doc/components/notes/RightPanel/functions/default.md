[**10x-devs**](../../../../README.md)

***

[10x-devs](../../../../modules.md) / [components/notes/RightPanel](../README.md) / default

# Function: default()

> **default**(`props`): `Element`

Defined in: [src/components/notes/RightPanel.tsx:66](https://github.com/jcubic/10xDevs/blob/8643271036ed0399a2b11ac87568ff44ec315445/src/components/notes/RightPanel.tsx#L66)

Renders the right sidebar panel with header navigation.

## Parameters

### props

`RightPanelProps`

Component props

## Returns

`Element`

Right panel component

## Remarks

Filters headers by text content (case-insensitive).
Highlights header matching current editor line.
Shows empty state when no headers found or no matches.
