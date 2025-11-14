[**10x-devs**](../../../../README.md)

***

[10x-devs](../../../../modules.md) / [components/notes/LeftPanel](../README.md) / default

# Variable: default

> `const` **default**: `NamedExoticComponent`\<`LeftPanelProps`\>

Defined in: [src/components/notes/LeftPanel.tsx:79](https://github.com/jcubic/10xDevs/blob/8643271036ed0399a2b11ac87568ff44ec315445/src/components/notes/LeftPanel.tsx#L79)

Renders the left sidebar panel with note list and management controls.

## Param

Component props

## Param

Array of note tree nodes

## Param

Handler for note selection

## Param

Handler for new note creation

## Param

Handler for note deletion

## Param

Async handler for note renaming

## Returns

Memoized left panel component

## Remarks

Manages local state for filtering and delete confirmation.
Filters notes by name (case-insensitive) and sorts by ID.
Shows asterisk prefix for notes with unsaved changes.
