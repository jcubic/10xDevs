[**10x-devs**](../../README.md)

***

[10x-devs](../../modules.md) / [prisma](../README.md) / default

# Variable: default

> `const` **default**: [`PrismaClient`](../classes/PrismaClient.md)\<\{ `adapter?`: `SqlDriverAdapterFactory` \| `null`; `datasources?`: `Datasources`; `datasourceUrl?`: `string`; `errorFormat?`: `ErrorFormat`; `log?`: (`LogLevel` \| `LogDefinition`)[]; `omit?`: `GlobalOmitConfig`; `transactionOptions?`: \{ `isolationLevel?`: `"Serializable"`; `maxWait?`: `number`; `timeout?`: `number`; \}; \}, `never`, `DefaultArgs`\>

Defined in: [src/lib/prisma.ts:132](https://github.com/jcubic/10xDevs/blob/8643271036ed0399a2b11ac87568ff44ec315445/src/lib/prisma.ts#L132)

Singleton Prisma client instance.
Automatically switches between MySQL and SQLite based on environment.

## Constant

prisma - Unified Prisma client

## Remarks

- In development: stored globally to persist across hot-reloads
- In production: created once per server instance
- In CI: uses SQLite for isolated, fast testing

## Example

```ts
import prisma from '@/lib/prisma';

// All Prisma operations work identically regardless of database engine
const users = await prisma.user.findMany();
const note = await prisma.note.create({ data: {...} });
```
