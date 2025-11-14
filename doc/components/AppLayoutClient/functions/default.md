[**10x-devs**](../../../README.md)

***

[10x-devs](../../../modules.md) / [components/AppLayoutClient](../README.md) / default

# Function: default()

> **default**(`props`): `Element`

Defined in: [src/components/AppLayoutClient.tsx:106](https://github.com/jcubic/10xDevs/blob/8643271036ed0399a2b11ac87568ff44ec315445/src/components/AppLayoutClient.tsx#L106)

Application layout wrapper with navigation, sidebar, content, and footer.

## Parameters

### props

`AppLayoutClientProps`

Layout slot contents

## Returns

`Element`

Rendered layout structure

## Navigation

slot)

## Sidebar

slot)

## Content

slot)

## Remarks

This component is the main layout container for the application. It receives
content from Next.js parallel routes and arranges them in a CSS grid layout.

**Slots:**
- `navigation`: Top navigation bar (user menu, title)
- `sidebar`: Left panel (notes tree, create button)
- `content`: Main content area (note editor)
- `children`: Additional content (modals, dialogs)

**Styling:**
- Uses CSS Modules for scoped styling (`MainNotesLayout.module.css`)
- Grid layout with flexible sidebar and content panels
- Footer always pinned to bottom

## Example

```tsx
<AppLayoutClient
  navigation={<TopNavigationBar />}
  sidebar={<LeftPanel />}
  content={<NoteEditor />}
/>
```
