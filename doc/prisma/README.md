[**10x-devs**](../README.md)

***

[10x-devs](../modules.md) / prisma

# prisma

## Description

Unified Prisma client for database operations with environment-based schema selection.
Provides a singleton Prisma client that switches between MySQL (production/development)
and SQLite (CI/test) based on environment variables.

## Dependencies

- ../../prisma-main/types: MySQL schema types (production/development)
- ../../prisma-e2e/types: SQLite schema types (CI/test)

## Remarks

- Both schemas are identical in structure, only the database engine differs
- In CI environment, uses SQLite for faster, isolated testing
- In production/development, uses MySQL for persistence and scalability
- Singleton pattern prevents multiple instances in hot-reload during development
- Re-exports all Prisma types from prisma-main for consistent imports

## Important

ALWAYS import Prisma types from this module, never directly from schema directories:
```ts
// ✅ Correct
import prisma, { type Note, type User } from '@/lib/prisma';

// ❌ Wrong - Do not import from schema directories
import { type Note } from '@prisma/client';
import { type Note } from '../../prisma-main/types';
```

## Example

```ts
import prisma, { type Note } from '@/lib/prisma';

// Create a note
const note = await prisma.note.create({
  data: {
    noteId: 1,
    name: 'My Note',
    content: 'Hello world',
    userId: 'user123'
  }
});

// Query notes
const notes = await prisma.note.findMany({
  where: { userId: 'user123' }
});
```

## Namespaces

- [Prisma](namespaces/Prisma/README.md)

## Classes

- [PrismaClient](classes/PrismaClient.md)

## Type Aliases

- [Account](type-aliases/Account.md)
- [Note](type-aliases/Note.md)
- [PrismaPromise](type-aliases/PrismaPromise.md)
- [Session](type-aliases/Session.md)
- [User](type-aliases/User.md)
- [Verification](type-aliases/Verification.md)

## Variables

- [default](variables/default.md)
