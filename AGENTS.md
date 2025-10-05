# Agent Guidelines for 10xDevs

## Commands

- `npm run dev` - Start development server
- `npm run build` - Build for production (uses turbopack)
- `npm run lint` - Run ESLint
- `npm run prettier` - Format code with Prettier
- No test framework configured

## Tech Stack

Next.js, TypeScript, Chakra UI v3, Prisma, MySQL, Firebase Auth, CSS Modules

## Code Style

- Use single quotes, semicolons, 2-space tabs, 90 char line width, no trailing commas
- Imports: Use `@/` for src imports, type imports with `import type`
- Components: Use TypeScript, Readonly props, client/server components as needed
- Naming: camelCase for variables/functions, PascalCase for components
- Error handling: Use TypeScript strict mode, no empty object types allowed

## Project Structure

- `src/app/` - Next.js app router pages
- `src/components/ui/` - Generic UI components
- `prisma/` - Database schema
- Use path alias `@/*` for src imports

## Next.js 15+ Features & Breaking Changes

### Async Request APIs (Breaking Changes)

- `cookies()`, `headers()`, `draftMode()` from `next/headers` are now async - use `await`
- `params` and `searchParams` in pages/layouts/route handlers are Promise-based - use `await`
- For client components, use React's `use()` hook to unwrap Promise-based props

### Caching Changes

- `fetch()` requests NOT cached by default - use `{ cache: 'force-cache' }` to cache
- GET Route Handlers not cached by default - export `dynamic = 'force-static'` to cache
- Client router cache disabled - use `staleTimes` config to enable

### Configuration Updates

- Use `serverExternalPackages` (not `experimental.serverComponentsExternalPackages`)
- Use `bundlePagesRouterDependencies` (not `experimental.bundlePagesExternals`)

### React 19 Support

- Full React 19 compatibility
- Use `use()` hook for Promise-based props in client components
- Updated TypeScript types

### Migration

- Use `npx @next/codemod@canary upgrade latest` for automatic updates
- Temporary compatibility modes available with warning messages

## Chakra UI v3 Breaking Changes & Features

### Component Structure Changes

- Components now use namespaced structure (e.g., `Accordion.Root`, `Accordion.Item`)
- `Modal` renamed to `Dialog`
- `Collapse` renamed to `Collapsible`
- `FormControl` replaced with `Field` component

### Prop Changes

- `colorScheme` → `colorPalette`
- `isOpen` → `open`, `isDisabled` → `disabled`, `isInvalid` → `invalid`
- `spacing` → `gap` (Stack component)
- `noOfLines` → `lineClamp`, `truncated` → `truncate`
- Boolean props simplified: `isActive` removed (use `data-active`)

### Theme System

- Use `createSystem()` instead of `extendTheme()`
- Token values must be wrapped in `{ value: "..." }` objects
- `ChakraProvider` now takes `value` prop instead of `theme`
- Color transparency: Use `"blue.200/16"` instead of `transparentize()`

### Provider Setup

```tsx
import { ChakraProvider, defaultSystem } from "@chakra-ui/react"
// Use defaultSystem or custom system with createSystem()
<ChakraProvider value={defaultSystem}>
```

### Breaking Removals

- `@emotion/styled` and `framer-motion` no longer required
- `forwardRef` from Chakra (use React's `forwardRef`)
- `fallbackSrc` from Image component
- `isExternal` from Link (use `target="_blank" rel="noopener noreferrer"`)

### New Features

- Better TypeScript support with improved prop inference
- CSS-in-JS performance improvements
- Enhanced accessibility
- `asChild` prop for styling Next.js components
