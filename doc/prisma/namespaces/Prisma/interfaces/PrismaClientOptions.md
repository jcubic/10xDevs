[**10x-devs**](../../../../README.md)

***

[10x-devs](../../../../modules.md) / [prisma](../../../README.md) / [Prisma](../README.md) / PrismaClientOptions

# Interface: PrismaClientOptions

Defined in: prisma-main/types/index.d.ts:1034

## Properties

### adapter?

> `optional` **adapter**: `SqlDriverAdapterFactory` \| `null`

Defined in: prisma-main/types/index.d.ts:1085

Instance of a Driver Adapter, e.g., like one provided by `@prisma/adapter-planetscale`

***

### datasources?

> `optional` **datasources**: [`Datasources`](../type-aliases/Datasources.md)

Defined in: prisma-main/types/index.d.ts:1038

Overwrites the datasource url from your schema.prisma file

***

### datasourceUrl?

> `optional` **datasourceUrl**: `string`

Defined in: prisma-main/types/index.d.ts:1042

Overwrites the datasource url from your schema.prisma file

***

### errorFormat?

> `optional` **errorFormat**: [`ErrorFormat`](../type-aliases/ErrorFormat.md)

Defined in: prisma-main/types/index.d.ts:1046

#### Default

```ts
"colorless"
```

***

### log?

> `optional` **log**: ([`LogLevel`](../type-aliases/LogLevel.md) \| [`LogDefinition`](../type-aliases/LogDefinition.md))[]

Defined in: prisma-main/types/index.d.ts:1071

#### Example

```
// Shorthand for `emit: 'stdout'`
log: ['query', 'info', 'warn', 'error']

// Emit as events only
log: [
  { emit: 'event', level: 'query' },
  { emit: 'event', level: 'info' },
  { emit: 'event', level: 'warn' }
  { emit: 'event', level: 'error' }
]

/ Emit as events and log to stdout
og: [
 { emit: 'stdout', level: 'query' },
 { emit: 'stdout', level: 'info' },
 { emit: 'stdout', level: 'warn' }
 { emit: 'stdout', level: 'error' }

```
Read more in our [docs](https://www.prisma.io/docs/reference/tools-and-interfaces/prisma-client/logging#the-log-option).

***

### omit?

> `optional` **omit**: [`GlobalOmitConfig`](../type-aliases/GlobalOmitConfig.md)

Defined in: prisma-main/types/index.d.ts:1100

Global configuration for omitting model fields by default.

#### Example

```
const prisma = new PrismaClient({
  omit: {
    user: {
      password: true
    }
  }
})
```

***

### transactionOptions?

> `optional` **transactionOptions**: `object`

Defined in: prisma-main/types/index.d.ts:1077

The default values for transactionOptions
maxWait ?= 2000
timeout ?= 5000

#### isolationLevel?

> `optional` **isolationLevel**: [`TransactionIsolationLevel`](../type-aliases/TransactionIsolationLevel.md)

#### maxWait?

> `optional` **maxWait**: `number`

#### timeout?

> `optional` **timeout**: `number`
