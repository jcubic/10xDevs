[**10x-devs**](../../README.md)

***

[10x-devs](../../modules.md) / [prisma](../README.md) / PrismaClient

# Class: PrismaClient\<ClientOptions, U, ExtArgs\>

Defined in: prisma-main/types/index.d.ts:56

##  Prisma Client ʲˢ

Type-safe database client for TypeScript & Node.js

## Example

```
const prisma = new PrismaClient()
// Fetch zero or more Users
const users = await prisma.user.findMany()
```

Read more in our [docs](https://www.prisma.io/docs/reference/tools-and-interfaces/prisma-client).

## Type Parameters

### ClientOptions

`ClientOptions` *extends* [`PrismaClientOptions`](../namespaces/Prisma/interfaces/PrismaClientOptions.md) = [`PrismaClientOptions`](../namespaces/Prisma/interfaces/PrismaClientOptions.md)

### U

`U` = `"log"` *extends* keyof `ClientOptions` ? `ClientOptions`\[`"log"`\] *extends* ([`LogLevel`](../namespaces/Prisma/type-aliases/LogLevel.md) \| [`LogDefinition`](../namespaces/Prisma/type-aliases/LogDefinition.md))[] ? [`GetEvents`](../namespaces/Prisma/type-aliases/GetEvents.md)\<`ClientOptions`\[`"log"`\]\> : `never` : `never`

### ExtArgs

`ExtArgs` *extends* `$Extensions.InternalArgs` = `$Extensions.DefaultArgs`

## Indexable

\[`K`: `symbol`\]: `object`

## Constructors

### Constructor

> **new PrismaClient**\<`ClientOptions`, `U`, `ExtArgs`\>(`optionsArg?`): `PrismaClient`\<`ClientOptions`, `U`, `ExtArgs`\>

Defined in: prisma-main/types/index.d.ts:78

##  Prisma Client ʲˢ

Type-safe database client for TypeScript & Node.js

#### Parameters

##### optionsArg?

[`Subset`](../namespaces/Prisma/type-aliases/Subset.md)\<`ClientOptions`, [`PrismaClientOptions`](../namespaces/Prisma/interfaces/PrismaClientOptions.md)\>

#### Returns

`PrismaClient`\<`ClientOptions`, `U`, `ExtArgs`\>

#### Example

```
const prisma = new PrismaClient()
// Fetch zero or more Users
const users = await prisma.user.findMany()
```

Read more in our [docs](https://www.prisma.io/docs/reference/tools-and-interfaces/prisma-client).

## Properties

### $extends

> **$extends**: `ExtendsHook`\<`"extends"`, [`TypeMapCb`](../namespaces/Prisma/interfaces/TypeMapCb.md)\<`ClientOptions`\>, `ExtArgs`, [`TypeMap`](../namespaces/Prisma/type-aliases/TypeMap.md)\<`InternalArgs` & `ExtArgs`, `ClientOptions` *extends* `object` ? `OmitOptions` : `object`\>\>

Defined in: prisma-main/types/index.d.ts:156

## Accessors

### account

#### Get Signature

> **get** **account**(): [`AccountDelegate`](../namespaces/Prisma/interfaces/AccountDelegate.md)\<`ExtArgs`, `ClientOptions`\>

Defined in: prisma-main/types/index.d.ts:188

`prisma.account`: Exposes CRUD operations for the **Account** model.
 * Example usage:
 * ```ts
 * // Fetch zero or more Accounts
 * const accounts = await prisma.account.findMany()
 * ```

##### Returns

[`AccountDelegate`](../namespaces/Prisma/interfaces/AccountDelegate.md)\<`ExtArgs`, `ClientOptions`\>

***

### note

#### Get Signature

> **get** **note**(): [`NoteDelegate`](../namespaces/Prisma/interfaces/NoteDelegate.md)\<`ExtArgs`, `ClientOptions`\>

Defined in: prisma-main/types/index.d.ts:208

`prisma.note`: Exposes CRUD operations for the **Note** model.
 * Example usage:
 * ```ts
 * // Fetch zero or more Notes
 * const notes = await prisma.note.findMany()
 * ```

##### Returns

[`NoteDelegate`](../namespaces/Prisma/interfaces/NoteDelegate.md)\<`ExtArgs`, `ClientOptions`\>

***

### session

#### Get Signature

> **get** **session**(): [`SessionDelegate`](../namespaces/Prisma/interfaces/SessionDelegate.md)\<`ExtArgs`, `ClientOptions`\>

Defined in: prisma-main/types/index.d.ts:178

`prisma.session`: Exposes CRUD operations for the **Session** model.
 * Example usage:
 * ```ts
 * // Fetch zero or more Sessions
 * const sessions = await prisma.session.findMany()
 * ```

##### Returns

[`SessionDelegate`](../namespaces/Prisma/interfaces/SessionDelegate.md)\<`ExtArgs`, `ClientOptions`\>

***

### user

#### Get Signature

> **get** **user**(): [`UserDelegate`](../namespaces/Prisma/interfaces/UserDelegate.md)\<`ExtArgs`, `ClientOptions`\>

Defined in: prisma-main/types/index.d.ts:168

`prisma.user`: Exposes CRUD operations for the **User** model.
 * Example usage:
 * ```ts
 * // Fetch zero or more Users
 * const users = await prisma.user.findMany()
 * ```

##### Returns

[`UserDelegate`](../namespaces/Prisma/interfaces/UserDelegate.md)\<`ExtArgs`, `ClientOptions`\>

***

### verification

#### Get Signature

> **get** **verification**(): [`VerificationDelegate`](../namespaces/Prisma/interfaces/VerificationDelegate.md)\<`ExtArgs`, `ClientOptions`\>

Defined in: prisma-main/types/index.d.ts:198

`prisma.verification`: Exposes CRUD operations for the **Verification** model.
 * Example usage:
 * ```ts
 * // Fetch zero or more Verifications
 * const verifications = await prisma.verification.findMany()
 * ```

##### Returns

[`VerificationDelegate`](../namespaces/Prisma/interfaces/VerificationDelegate.md)\<`ExtArgs`, `ClientOptions`\>

## Methods

### $connect()

> **$connect**(): `Promise`\<`void`\>

Defined in: prisma-main/types/index.d.ts:84

Connect with the database

#### Returns

`Promise`\<`void`\>

***

### $disconnect()

> **$disconnect**(): `Promise`\<`void`\>

Defined in: prisma-main/types/index.d.ts:89

Disconnect from the database

#### Returns

`Promise`\<`void`\>

***

### $executeRaw()

> **$executeRaw**\<`T`\>(`query`, ...`values`): [`PrismaPromise`](../namespaces/Prisma/type-aliases/PrismaPromise.md)\<`number`\>

Defined in: prisma-main/types/index.d.ts:100

Executes a prepared raw query and returns the number of affected rows.

#### Type Parameters

##### T

`T` = `unknown`

#### Parameters

##### query

`TemplateStringsArray` | [`Sql`](../namespaces/Prisma/classes/Sql.md)

##### values

...`any`[]

#### Returns

[`PrismaPromise`](../namespaces/Prisma/type-aliases/PrismaPromise.md)\<`number`\>

#### Example

```
const result = await prisma.$executeRaw`UPDATE User SET cool = ${true} WHERE email = ${'user@email.com'};`
```

Read more in our [docs](https://www.prisma.io/docs/reference/tools-and-interfaces/prisma-client/raw-database-access).

***

### $executeRawUnsafe()

> **$executeRawUnsafe**\<`T`\>(`query`, ...`values`): [`PrismaPromise`](../namespaces/Prisma/type-aliases/PrismaPromise.md)\<`number`\>

Defined in: prisma-main/types/index.d.ts:112

Executes a raw query and returns the number of affected rows.
Susceptible to SQL injections, see documentation.

#### Type Parameters

##### T

`T` = `unknown`

#### Parameters

##### query

`string`

##### values

...`any`[]

#### Returns

[`PrismaPromise`](../namespaces/Prisma/type-aliases/PrismaPromise.md)\<`number`\>

#### Example

```
const result = await prisma.$executeRawUnsafe('UPDATE User SET cool = $1 WHERE email = $2 ;', true, 'user@email.com')
```

Read more in our [docs](https://www.prisma.io/docs/reference/tools-and-interfaces/prisma-client/raw-database-access).

***

### $on()

> **$on**\<`V`\>(`eventType`, `callback`): `PrismaClient`

Defined in: prisma-main/types/index.d.ts:79

#### Type Parameters

##### V

`V`

#### Parameters

##### eventType

`V`

##### callback

(`event`) => `void`

#### Returns

`PrismaClient`

***

### $queryRaw()

> **$queryRaw**\<`T`\>(`query`, ...`values`): [`PrismaPromise`](../namespaces/Prisma/type-aliases/PrismaPromise.md)\<`T`\>

Defined in: prisma-main/types/index.d.ts:123

Performs a prepared raw query and returns the `SELECT` data.

#### Type Parameters

##### T

`T` = `unknown`

#### Parameters

##### query

`TemplateStringsArray` | [`Sql`](../namespaces/Prisma/classes/Sql.md)

##### values

...`any`[]

#### Returns

[`PrismaPromise`](../namespaces/Prisma/type-aliases/PrismaPromise.md)\<`T`\>

#### Example

```
const result = await prisma.$queryRaw`SELECT * FROM User WHERE id = ${1} OR email = ${'user@email.com'};`
```

Read more in our [docs](https://www.prisma.io/docs/reference/tools-and-interfaces/prisma-client/raw-database-access).

***

### $queryRawUnsafe()

> **$queryRawUnsafe**\<`T`\>(`query`, ...`values`): [`PrismaPromise`](../namespaces/Prisma/type-aliases/PrismaPromise.md)\<`T`\>

Defined in: prisma-main/types/index.d.ts:135

Performs a raw query and returns the `SELECT` data.
Susceptible to SQL injections, see documentation.

#### Type Parameters

##### T

`T` = `unknown`

#### Parameters

##### query

`string`

##### values

...`any`[]

#### Returns

[`PrismaPromise`](../namespaces/Prisma/type-aliases/PrismaPromise.md)\<`T`\>

#### Example

```
const result = await prisma.$queryRawUnsafe('SELECT * FROM User WHERE id = $1 OR email = $2;', 1, 'user@email.com')
```

Read more in our [docs](https://www.prisma.io/docs/reference/tools-and-interfaces/prisma-client/raw-database-access).

***

### $transaction()

#### Call Signature

> **$transaction**\<`P`\>(`arg`, `options?`): `Promise`\<`UnwrapTuple`\<`P`\>\>

Defined in: prisma-main/types/index.d.ts:151

Allows the running of a sequence of read/write operations that are guaranteed to either succeed or fail as a whole.

##### Type Parameters

###### P

`P` *extends* [`PrismaPromise`](../namespaces/Prisma/type-aliases/PrismaPromise.md)\<`any`\>[]

##### Parameters

###### arg

\[`...P[]`\]

###### options?

###### isolationLevel?

[`TransactionIsolationLevel`](../namespaces/Prisma/type-aliases/TransactionIsolationLevel.md)

##### Returns

`Promise`\<`UnwrapTuple`\<`P`\>\>

##### Example

```
const [george, bob, alice] = await prisma.$transaction([
  prisma.user.create({ data: { name: 'George' } }),
  prisma.user.create({ data: { name: 'Bob' } }),
  prisma.user.create({ data: { name: 'Alice' } }),
])
```

Read more in our [docs](https://www.prisma.io/docs/concepts/components/prisma-client/transactions).

#### Call Signature

> **$transaction**\<`R`\>(`fn`, `options?`): `Promise`\<`R`\>

Defined in: prisma-main/types/index.d.ts:153

Allows the running of a sequence of read/write operations that are guaranteed to either succeed or fail as a whole.

##### Type Parameters

###### R

`R`

##### Parameters

###### fn

(`prisma`) => `Promise`\<`R`\>

###### options?

###### isolationLevel?

[`TransactionIsolationLevel`](../namespaces/Prisma/type-aliases/TransactionIsolationLevel.md)

###### maxWait?

`number`

###### timeout?

`number`

##### Returns

`Promise`\<`R`\>

##### Example

```
const [george, bob, alice] = await prisma.$transaction([
  prisma.user.create({ data: { name: 'George' } }),
  prisma.user.create({ data: { name: 'Bob' } }),
  prisma.user.create({ data: { name: 'Alice' } }),
])
```

Read more in our [docs](https://www.prisma.io/docs/concepts/components/prisma-client/transactions).
