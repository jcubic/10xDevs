[**10x-devs**](../../../../README.md)

***

[10x-devs](../../../../modules.md) / [prisma](../../../README.md) / [Prisma](../README.md) / validator

# Function: validator()

## Call Signature

> **validator**\<`V`\>(): \<`S`\>(`select`) => `S`

Defined in: prisma-main/types/runtime/library.d.ts:3967

### Type Parameters

#### V

`V`

### Returns

> \<`S`\>(`select`): `S`

#### Type Parameters

##### S

`S`

#### Parameters

##### select

[`Exact`](../type-aliases/Exact.md)\<`S`, `V`\>

#### Returns

`S`

## Call Signature

> **validator**\<`C`, `M`, `O`\>(`client`, `model`, `operation`): \<`S`\>(`select`) => `S`

Defined in: prisma-main/types/runtime/library.d.ts:3969

### Type Parameters

#### C

`C`

#### M

`M` *extends* `string` \| `number` \| `symbol`

#### O

`O` *extends* `"$queryRaw"` \| `"$queryRawUnsafe"` \| `"$executeRaw"` \| `"$executeRawUnsafe"` \| `"$runCommandRaw"` \| `"findUnique"` \| `"findMany"` \| `"findUniqueOrThrow"` \| `"findFirst"` \| `"findFirstOrThrow"` \| `"create"` \| `"createMany"` \| `"createManyAndReturn"` \| `"delete"` \| `"update"` \| `"deleteMany"` \| `"updateMany"` \| `"updateManyAndReturn"` \| `"upsert"` \| `"aggregate"` \| `"groupBy"` \| `"count"` \| `"findRaw"` \| `"aggregateRaw"`

### Parameters

#### client

`C`

#### model

`M`

#### operation

`O`

### Returns

> \<`S`\>(`select`): `S`

#### Type Parameters

##### S

`S`

#### Parameters

##### select

[`Exact`](../type-aliases/Exact.md)\<`S`, [`Args`](../type-aliases/Args.md)\<`C`\[`M`\], `O`\>\>

#### Returns

`S`

## Call Signature

> **validator**\<`C`, `M`, `O`, `P`\>(`client`, `model`, `operation`, `prop`): \<`S`\>(`select`) => `S`

Defined in: prisma-main/types/runtime/library.d.ts:3971

### Type Parameters

#### C

`C`

#### M

`M` *extends* `string` \| `number` \| `symbol`

#### O

`O` *extends* `"$queryRaw"` \| `"$queryRawUnsafe"` \| `"$executeRaw"` \| `"$executeRawUnsafe"` \| `"$runCommandRaw"` \| `"findUnique"` \| `"findMany"` \| `"findUniqueOrThrow"` \| `"findFirst"` \| `"findFirstOrThrow"` \| `"create"` \| `"createMany"` \| `"createManyAndReturn"` \| `"delete"` \| `"update"` \| `"deleteMany"` \| `"updateMany"` \| `"updateManyAndReturn"` \| `"upsert"` \| `"aggregate"` \| `"groupBy"` \| `"count"` \| `"findRaw"` \| `"aggregateRaw"`

#### P

`P` *extends* `string` \| `number` \| `symbol`

### Parameters

#### client

`C`

#### model

`M`

#### operation

`O`

#### prop

`P`

### Returns

> \<`S`\>(`select`): `S`

#### Type Parameters

##### S

`S`

#### Parameters

##### select

[`Exact`](../type-aliases/Exact.md)\<`S`, [`Args`](../type-aliases/Args.md)\<`C`\[`M`\], `O`\>\[`P`\]\>

#### Returns

`S`
