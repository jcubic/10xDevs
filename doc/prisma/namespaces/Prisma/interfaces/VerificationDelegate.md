[**10x-devs**](../../../../README.md)

***

[10x-devs](../../../../modules.md) / [prisma](../../../README.md) / [Prisma](../README.md) / VerificationDelegate

# Interface: VerificationDelegate\<ExtArgs, GlobalOmitOptions\>

Defined in: prisma-main/types/index.d.ts:4456

## Type Parameters

### ExtArgs

`ExtArgs` *extends* `$Extensions.InternalArgs` = `$Extensions.DefaultArgs`

### GlobalOmitOptions

`GlobalOmitOptions` = \{ \}

## Indexable

\[`K`: `symbol`\]: `object`

## Properties

### fields

> `readonly` **fields**: [`VerificationFieldRefs`](VerificationFieldRefs.md)

Defined in: prisma-main/types/index.d.ts:4774

Fields of the Verification model

## Methods

### aggregate()

> **aggregate**\<`T`\>(`args`): [`PrismaPromise`](../type-aliases/PrismaPromise.md)\<[`GetVerificationAggregateType`](../type-aliases/GetVerificationAggregateType.md)\<`T`\>\>

Defined in: prisma-main/types/index.d.ts:4693

Allows you to perform aggregations operations on a Verification.
Note, that providing `undefined` is treated as the value not being there.
Read more here: https://pris.ly/d/null-undefined

#### Type Parameters

##### T

`T` *extends* [`VerificationAggregateArgs`](../type-aliases/VerificationAggregateArgs.md)\<`DefaultArgs`\>

#### Parameters

##### args

[`Subset`](../type-aliases/Subset.md)\<`T`, [`VerificationAggregateArgs`](../type-aliases/VerificationAggregateArgs.md)\>

Select which aggregations you would like to apply and on what fields.

#### Returns

[`PrismaPromise`](../type-aliases/PrismaPromise.md)\<[`GetVerificationAggregateType`](../type-aliases/GetVerificationAggregateType.md)\<`T`\>\>

#### Example

```ts
// Ordered by age ascending
// Where email contains prisma.io
// Limited to the 10 users
const aggregations = await prisma.user.aggregate({
  _avg: {
    age: true,
  },
  where: {
    email: {
      contains: "prisma.io",
    },
  },
  orderBy: {
    age: "asc",
  },
  take: 10,
})
```

***

### count()

> **count**\<`T`\>(`args?`): [`PrismaPromise`](../type-aliases/PrismaPromise.md)\<`T` *extends* `Record_2`\<`"select"`, `any`\> ? `T`\<`T`\>\[`"select"`\] *extends* `true` ? `number` : \{ \[P in string \| number \| symbol\]: P extends keyof VerificationCountAggregateOutputType ? VerificationCountAggregateOutputType\[P\<P\>\] : never \} : `number`\>

Defined in: prisma-main/types/index.d.ts:4659

Count the number of Verifications.
Note, that providing `undefined` is treated as the value not being there.
Read more here: https://pris.ly/d/null-undefined

#### Type Parameters

##### T

`T` *extends* [`VerificationCountArgs`](../type-aliases/VerificationCountArgs.md)\<`DefaultArgs`\>

#### Parameters

##### args?

[`Subset`](../type-aliases/Subset.md)\<`T`, [`VerificationCountArgs`](../type-aliases/VerificationCountArgs.md)\<`DefaultArgs`\>\>

Arguments to filter Verifications to count.

#### Returns

[`PrismaPromise`](../type-aliases/PrismaPromise.md)\<`T` *extends* `Record_2`\<`"select"`, `any`\> ? `T`\<`T`\>\[`"select"`\] *extends* `true` ? `number` : \{ \[P in string \| number \| symbol\]: P extends keyof VerificationCountAggregateOutputType ? VerificationCountAggregateOutputType\[P\<P\>\] : never \} : `number`\>

#### Example

```ts
// Count the number of Verifications
const count = await prisma.verification.count({
  where: {
    // ... the filter for the Verifications we want to count
  }
})
```

***

### create()

> **create**\<`T`\>(`args`): [`Prisma__VerificationClient`](Prisma__VerificationClient.md)\<`GetFindResult`\<[`$VerificationPayload`](../type-aliases/$VerificationPayload.md)\<`ExtArgs`\>, `T`, `GlobalOmitOptions`\>, `never`, `ExtArgs`, `GlobalOmitOptions`\>

Defined in: prisma-main/types/index.d.ts:4546

Create a Verification.

#### Type Parameters

##### T

`T` *extends* [`VerificationCreateArgs`](../type-aliases/VerificationCreateArgs.md)\<`DefaultArgs`\>

#### Parameters

##### args

[`SelectSubset`](../type-aliases/SelectSubset.md)\<`T`, [`VerificationCreateArgs`](../type-aliases/VerificationCreateArgs.md)\<`ExtArgs`\>\>

Arguments to create a Verification.

#### Returns

[`Prisma__VerificationClient`](Prisma__VerificationClient.md)\<`GetFindResult`\<[`$VerificationPayload`](../type-aliases/$VerificationPayload.md)\<`ExtArgs`\>, `T`, `GlobalOmitOptions`\>, `never`, `ExtArgs`, `GlobalOmitOptions`\>

#### Example

```ts
// Create one Verification
const Verification = await prisma.verification.create({
  data: {
    // ... data to create a Verification
  }
})
```

***

### createMany()

> **createMany**\<`T`\>(`args?`): [`PrismaPromise`](../type-aliases/PrismaPromise.md)\<[`BatchPayload`](../type-aliases/BatchPayload.md)\>

Defined in: prisma-main/types/index.d.ts:4560

Create many Verifications.

#### Type Parameters

##### T

`T` *extends* [`VerificationCreateManyArgs`](../type-aliases/VerificationCreateManyArgs.md)\<`DefaultArgs`\>

#### Parameters

##### args?

[`SelectSubset`](../type-aliases/SelectSubset.md)\<`T`, [`VerificationCreateManyArgs`](../type-aliases/VerificationCreateManyArgs.md)\<`ExtArgs`\>\>

Arguments to create many Verifications.

#### Returns

[`PrismaPromise`](../type-aliases/PrismaPromise.md)\<[`BatchPayload`](../type-aliases/BatchPayload.md)\>

#### Example

```ts
// Create many Verifications
const verification = await prisma.verification.createMany({
  data: [
    // ... provide data here
  ]
})
```

***

### delete()

> **delete**\<`T`\>(`args`): [`Prisma__VerificationClient`](Prisma__VerificationClient.md)\<`GetFindResult`\<[`$VerificationPayload`](../type-aliases/$VerificationPayload.md)\<`ExtArgs`\>, `T`, `GlobalOmitOptions`\>, `never`, `ExtArgs`, `GlobalOmitOptions`\>

Defined in: prisma-main/types/index.d.ts:4574

Delete a Verification.

#### Type Parameters

##### T

`T` *extends* [`VerificationDeleteArgs`](../type-aliases/VerificationDeleteArgs.md)\<`DefaultArgs`\>

#### Parameters

##### args

[`SelectSubset`](../type-aliases/SelectSubset.md)\<`T`, [`VerificationDeleteArgs`](../type-aliases/VerificationDeleteArgs.md)\<`ExtArgs`\>\>

Arguments to delete one Verification.

#### Returns

[`Prisma__VerificationClient`](Prisma__VerificationClient.md)\<`GetFindResult`\<[`$VerificationPayload`](../type-aliases/$VerificationPayload.md)\<`ExtArgs`\>, `T`, `GlobalOmitOptions`\>, `never`, `ExtArgs`, `GlobalOmitOptions`\>

#### Example

```ts
// Delete one Verification
const Verification = await prisma.verification.delete({
  where: {
    // ... filter to delete one Verification
  }
})
```

***

### deleteMany()

> **deleteMany**\<`T`\>(`args?`): [`PrismaPromise`](../type-aliases/PrismaPromise.md)\<[`BatchPayload`](../type-aliases/BatchPayload.md)\>

Defined in: prisma-main/types/index.d.ts:4605

Delete zero or more Verifications.

#### Type Parameters

##### T

`T` *extends* [`VerificationDeleteManyArgs`](../type-aliases/VerificationDeleteManyArgs.md)\<`DefaultArgs`\>

#### Parameters

##### args?

[`SelectSubset`](../type-aliases/SelectSubset.md)\<`T`, [`VerificationDeleteManyArgs`](../type-aliases/VerificationDeleteManyArgs.md)\<`ExtArgs`\>\>

Arguments to filter Verifications to delete.

#### Returns

[`PrismaPromise`](../type-aliases/PrismaPromise.md)\<[`BatchPayload`](../type-aliases/BatchPayload.md)\>

#### Example

```ts
// Delete a few Verifications
const { count } = await prisma.verification.deleteMany({
  where: {
    // ... provide filter here
  }
})
```

***

### findFirst()

> **findFirst**\<`T`\>(`args?`): [`Prisma__VerificationClient`](Prisma__VerificationClient.md)\<`GetFindResult`\<[`$VerificationPayload`](../type-aliases/$VerificationPayload.md)\<`ExtArgs`\>, `T`, `GlobalOmitOptions`\> \| `null`, `null`, `ExtArgs`, `GlobalOmitOptions`\>

Defined in: prisma-main/types/index.d.ts:4498

Find the first Verification that matches the filter.
Note, that providing `undefined` is treated as the value not being there.
Read more here: https://pris.ly/d/null-undefined

#### Type Parameters

##### T

`T` *extends* [`VerificationFindFirstArgs`](../type-aliases/VerificationFindFirstArgs.md)\<`DefaultArgs`\>

#### Parameters

##### args?

[`SelectSubset`](../type-aliases/SelectSubset.md)\<`T`, [`VerificationFindFirstArgs`](../type-aliases/VerificationFindFirstArgs.md)\<`ExtArgs`\>\>

Arguments to find a Verification

#### Returns

[`Prisma__VerificationClient`](Prisma__VerificationClient.md)\<`GetFindResult`\<[`$VerificationPayload`](../type-aliases/$VerificationPayload.md)\<`ExtArgs`\>, `T`, `GlobalOmitOptions`\> \| `null`, `null`, `ExtArgs`, `GlobalOmitOptions`\>

#### Example

```ts
// Get one Verification
const verification = await prisma.verification.findFirst({
  where: {
    // ... provide filter here
  }
})
```

***

### findFirstOrThrow()

> **findFirstOrThrow**\<`T`\>(`args?`): [`Prisma__VerificationClient`](Prisma__VerificationClient.md)\<`GetFindResult`\<[`$VerificationPayload`](../type-aliases/$VerificationPayload.md)\<`ExtArgs`\>, `T`, `GlobalOmitOptions`\>, `never`, `ExtArgs`, `GlobalOmitOptions`\>

Defined in: prisma-main/types/index.d.ts:4514

Find the first Verification that matches the filter or
throw `PrismaKnownClientError` with `P2025` code if no matches were found.
Note, that providing `undefined` is treated as the value not being there.
Read more here: https://pris.ly/d/null-undefined

#### Type Parameters

##### T

`T` *extends* [`VerificationFindFirstOrThrowArgs`](../type-aliases/VerificationFindFirstOrThrowArgs.md)\<`DefaultArgs`\>

#### Parameters

##### args?

[`SelectSubset`](../type-aliases/SelectSubset.md)\<`T`, [`VerificationFindFirstOrThrowArgs`](../type-aliases/VerificationFindFirstOrThrowArgs.md)\<`ExtArgs`\>\>

Arguments to find a Verification

#### Returns

[`Prisma__VerificationClient`](Prisma__VerificationClient.md)\<`GetFindResult`\<[`$VerificationPayload`](../type-aliases/$VerificationPayload.md)\<`ExtArgs`\>, `T`, `GlobalOmitOptions`\>, `never`, `ExtArgs`, `GlobalOmitOptions`\>

#### Example

```ts
// Get one Verification
const verification = await prisma.verification.findFirstOrThrow({
  where: {
    // ... provide filter here
  }
})
```

***

### findMany()

> **findMany**\<`T`\>(`args?`): [`PrismaPromise`](../type-aliases/PrismaPromise.md)\<`GetFindResult`\<[`$VerificationPayload`](../type-aliases/$VerificationPayload.md)\<`ExtArgs`\>, `T`, `GlobalOmitOptions`\>[]\>

Defined in: prisma-main/types/index.d.ts:4532

Find zero or more Verifications that matches the filter.
Note, that providing `undefined` is treated as the value not being there.
Read more here: https://pris.ly/d/null-undefined

#### Type Parameters

##### T

`T` *extends* [`VerificationFindManyArgs`](../type-aliases/VerificationFindManyArgs.md)\<`DefaultArgs`\>

#### Parameters

##### args?

[`SelectSubset`](../type-aliases/SelectSubset.md)\<`T`, [`VerificationFindManyArgs`](../type-aliases/VerificationFindManyArgs.md)\<`ExtArgs`\>\>

Arguments to filter and select certain fields only.

#### Returns

[`PrismaPromise`](../type-aliases/PrismaPromise.md)\<`GetFindResult`\<[`$VerificationPayload`](../type-aliases/$VerificationPayload.md)\<`ExtArgs`\>, `T`, `GlobalOmitOptions`\>[]\>

#### Example

```ts
// Get all Verifications
const verifications = await prisma.verification.findMany()

// Get first 10 Verifications
const verifications = await prisma.verification.findMany({ take: 10 })

// Only select the `id`
const verificationWithIdOnly = await prisma.verification.findMany({ select: { id: true } })
```

***

### findUnique()

> **findUnique**\<`T`\>(`args`): [`Prisma__VerificationClient`](Prisma__VerificationClient.md)\<`GetFindResult`\<[`$VerificationPayload`](../type-aliases/$VerificationPayload.md)\<`ExtArgs`\>, `T`, `GlobalOmitOptions`\> \| `null`, `null`, `ExtArgs`, `GlobalOmitOptions`\>

Defined in: prisma-main/types/index.d.ts:4469

Find zero or one Verification that matches the filter.

#### Type Parameters

##### T

`T` *extends* [`VerificationFindUniqueArgs`](../type-aliases/VerificationFindUniqueArgs.md)\<`DefaultArgs`\>

#### Parameters

##### args

[`SelectSubset`](../type-aliases/SelectSubset.md)\<`T`, [`VerificationFindUniqueArgs`](../type-aliases/VerificationFindUniqueArgs.md)\<`ExtArgs`\>\>

Arguments to find a Verification

#### Returns

[`Prisma__VerificationClient`](Prisma__VerificationClient.md)\<`GetFindResult`\<[`$VerificationPayload`](../type-aliases/$VerificationPayload.md)\<`ExtArgs`\>, `T`, `GlobalOmitOptions`\> \| `null`, `null`, `ExtArgs`, `GlobalOmitOptions`\>

#### Example

```ts
// Get one Verification
const verification = await prisma.verification.findUnique({
  where: {
    // ... provide filter here
  }
})
```

***

### findUniqueOrThrow()

> **findUniqueOrThrow**\<`T`\>(`args`): [`Prisma__VerificationClient`](Prisma__VerificationClient.md)\<`GetFindResult`\<[`$VerificationPayload`](../type-aliases/$VerificationPayload.md)\<`ExtArgs`\>, `T`, `GlobalOmitOptions`\>, `never`, `ExtArgs`, `GlobalOmitOptions`\>

Defined in: prisma-main/types/index.d.ts:4483

Find one Verification that matches the filter or throw an error with `error.code='P2025'`
if no matches were found.

#### Type Parameters

##### T

`T` *extends* [`VerificationFindUniqueOrThrowArgs`](../type-aliases/VerificationFindUniqueOrThrowArgs.md)\<`DefaultArgs`\>

#### Parameters

##### args

[`SelectSubset`](../type-aliases/SelectSubset.md)\<`T`, [`VerificationFindUniqueOrThrowArgs`](../type-aliases/VerificationFindUniqueOrThrowArgs.md)\<`ExtArgs`\>\>

Arguments to find a Verification

#### Returns

[`Prisma__VerificationClient`](Prisma__VerificationClient.md)\<`GetFindResult`\<[`$VerificationPayload`](../type-aliases/$VerificationPayload.md)\<`ExtArgs`\>, `T`, `GlobalOmitOptions`\>, `never`, `ExtArgs`, `GlobalOmitOptions`\>

#### Example

```ts
// Get one Verification
const verification = await prisma.verification.findUniqueOrThrow({
  where: {
    // ... provide filter here
  }
})
```

***

### groupBy()

> **groupBy**\<`T`, `HasSelectOrTake`, `OrderByArg`, `OrderFields`, `ByFields`, `ByValid`, `HavingFields`, `HavingValid`, `ByEmpty`, `InputErrors`\>(`args`): `object` *extends* `InputErrors` ? [`GetVerificationGroupByPayload`](../type-aliases/GetVerificationGroupByPayload.md)\<`T`\> : [`PrismaPromise`](../type-aliases/PrismaPromise.md)\<`InputErrors`\>

Defined in: prisma-main/types/index.d.ts:4713

Group by Verification.
Note, that providing `undefined` is treated as the value not being there.
Read more here: https://pris.ly/d/null-undefined

#### Type Parameters

##### T

`T` *extends* [`VerificationGroupByArgs`](../type-aliases/VerificationGroupByArgs.md)\<`DefaultArgs`\>

##### HasSelectOrTake

`HasSelectOrTake` *extends* `0` \| `1`

##### OrderByArg

`OrderByArg` *extends* \{ `orderBy`: [`VerificationOrderByWithAggregationInput`](../type-aliases/VerificationOrderByWithAggregationInput.md) \| [`VerificationOrderByWithAggregationInput`](../type-aliases/VerificationOrderByWithAggregationInput.md)[] \| `undefined`; \} \| \{ `orderBy?`: [`VerificationOrderByWithAggregationInput`](../type-aliases/VerificationOrderByWithAggregationInput.md) \| [`VerificationOrderByWithAggregationInput`](../type-aliases/VerificationOrderByWithAggregationInput.md)[]; \}

##### OrderFields

`OrderFields` *extends* `"value"` \| `"id"` \| `"createdAt"` \| `"updatedAt"` \| `"expiresAt"` \| `"identifier"`

##### ByFields

`ByFields` *extends* [`VerificationScalarFieldEnum`](../type-aliases/VerificationScalarFieldEnum.md)

##### ByValid

`ByValid` *extends* `0` \| `1`

##### HavingFields

`HavingFields` *extends* `string` \| `number` \| `symbol`

##### HavingValid

`HavingValid`

##### ByEmpty

`ByEmpty` *extends* `0` \| `1`

##### InputErrors

`InputErrors`

#### Parameters

##### args

\{ \[key in string \| number \| symbol\]: key extends keyof VerificationGroupByArgs\<DefaultArgs\> ? T\[key\<key\>\] : never \} & `OrderByArg` & `InputErrors`

Group by arguments.

#### Returns

`object` *extends* `InputErrors` ? [`GetVerificationGroupByPayload`](../type-aliases/GetVerificationGroupByPayload.md)\<`T`\> : [`PrismaPromise`](../type-aliases/PrismaPromise.md)\<`InputErrors`\>

#### Example

```ts
// Group by city, order by createdAt, get count
const result = await prisma.user.groupBy({
  by: ['city', 'createdAt'],
  orderBy: {
    createdAt: true
  },
  _count: {
    _all: true
  },
})
```

***

### update()

> **update**\<`T`\>(`args`): [`Prisma__VerificationClient`](Prisma__VerificationClient.md)\<`GetFindResult`\<[`$VerificationPayload`](../type-aliases/$VerificationPayload.md)\<`ExtArgs`\>, `T`, `GlobalOmitOptions`\>, `never`, `ExtArgs`, `GlobalOmitOptions`\>

Defined in: prisma-main/types/index.d.ts:4591

Update one Verification.

#### Type Parameters

##### T

`T` *extends* [`VerificationUpdateArgs`](../type-aliases/VerificationUpdateArgs.md)\<`DefaultArgs`\>

#### Parameters

##### args

[`SelectSubset`](../type-aliases/SelectSubset.md)\<`T`, [`VerificationUpdateArgs`](../type-aliases/VerificationUpdateArgs.md)\<`ExtArgs`\>\>

Arguments to update one Verification.

#### Returns

[`Prisma__VerificationClient`](Prisma__VerificationClient.md)\<`GetFindResult`\<[`$VerificationPayload`](../type-aliases/$VerificationPayload.md)\<`ExtArgs`\>, `T`, `GlobalOmitOptions`\>, `never`, `ExtArgs`, `GlobalOmitOptions`\>

#### Example

```ts
// Update one Verification
const verification = await prisma.verification.update({
  where: {
    // ... provide filter here
  },
  data: {
    // ... provide data here
  }
})
```

***

### updateMany()

> **updateMany**\<`T`\>(`args`): [`PrismaPromise`](../type-aliases/PrismaPromise.md)\<[`BatchPayload`](../type-aliases/BatchPayload.md)\>

Defined in: prisma-main/types/index.d.ts:4624

Update zero or more Verifications.
Note, that providing `undefined` is treated as the value not being there.
Read more here: https://pris.ly/d/null-undefined

#### Type Parameters

##### T

`T` *extends* [`VerificationUpdateManyArgs`](../type-aliases/VerificationUpdateManyArgs.md)\<`DefaultArgs`\>

#### Parameters

##### args

[`SelectSubset`](../type-aliases/SelectSubset.md)\<`T`, [`VerificationUpdateManyArgs`](../type-aliases/VerificationUpdateManyArgs.md)\<`ExtArgs`\>\>

Arguments to update one or more rows.

#### Returns

[`PrismaPromise`](../type-aliases/PrismaPromise.md)\<[`BatchPayload`](../type-aliases/BatchPayload.md)\>

#### Example

```ts
// Update many Verifications
const verification = await prisma.verification.updateMany({
  where: {
    // ... provide filter here
  },
  data: {
    // ... provide data here
  }
})
```

***

### upsert()

> **upsert**\<`T`\>(`args`): [`Prisma__VerificationClient`](Prisma__VerificationClient.md)\<`GetFindResult`\<[`$VerificationPayload`](../type-aliases/$VerificationPayload.md)\<`ExtArgs`\>, `T`, `GlobalOmitOptions`\>, `never`, `ExtArgs`, `GlobalOmitOptions`\>

Defined in: prisma-main/types/index.d.ts:4643

Create or update one Verification.

#### Type Parameters

##### T

`T` *extends* [`VerificationUpsertArgs`](../type-aliases/VerificationUpsertArgs.md)\<`DefaultArgs`\>

#### Parameters

##### args

[`SelectSubset`](../type-aliases/SelectSubset.md)\<`T`, [`VerificationUpsertArgs`](../type-aliases/VerificationUpsertArgs.md)\<`ExtArgs`\>\>

Arguments to update or create a Verification.

#### Returns

[`Prisma__VerificationClient`](Prisma__VerificationClient.md)\<`GetFindResult`\<[`$VerificationPayload`](../type-aliases/$VerificationPayload.md)\<`ExtArgs`\>, `T`, `GlobalOmitOptions`\>, `never`, `ExtArgs`, `GlobalOmitOptions`\>

#### Example

```ts
// Update or create a Verification
const verification = await prisma.verification.upsert({
  create: {
    // ... data to create a Verification
  },
  update: {
    // ... in case it already exists, update
  },
  where: {
    // ... the filter for the Verification we want to update
  }
})
```
