[**10x-devs**](../../../../README.md)

***

[10x-devs](../../../../modules.md) / [prisma](../../../README.md) / [Prisma](../README.md) / AccountDelegate

# Interface: AccountDelegate\<ExtArgs, GlobalOmitOptions\>

Defined in: prisma-main/types/index.d.ts:3515

## Type Parameters

### ExtArgs

`ExtArgs` *extends* `$Extensions.InternalArgs` = `$Extensions.DefaultArgs`

### GlobalOmitOptions

`GlobalOmitOptions` = \{ \}

## Indexable

\[`K`: `symbol`\]: `object`

## Properties

### fields

> `readonly` **fields**: [`AccountFieldRefs`](AccountFieldRefs.md)

Defined in: prisma-main/types/index.d.ts:3833

Fields of the Account model

## Methods

### aggregate()

> **aggregate**\<`T`\>(`args`): [`PrismaPromise`](../type-aliases/PrismaPromise.md)\<[`GetAccountAggregateType`](../type-aliases/GetAccountAggregateType.md)\<`T`\>\>

Defined in: prisma-main/types/index.d.ts:3752

Allows you to perform aggregations operations on a Account.
Note, that providing `undefined` is treated as the value not being there.
Read more here: https://pris.ly/d/null-undefined

#### Type Parameters

##### T

`T` *extends* [`AccountAggregateArgs`](../type-aliases/AccountAggregateArgs.md)\<`DefaultArgs`\>

#### Parameters

##### args

[`Subset`](../type-aliases/Subset.md)\<`T`, [`AccountAggregateArgs`](../type-aliases/AccountAggregateArgs.md)\>

Select which aggregations you would like to apply and on what fields.

#### Returns

[`PrismaPromise`](../type-aliases/PrismaPromise.md)\<[`GetAccountAggregateType`](../type-aliases/GetAccountAggregateType.md)\<`T`\>\>

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

> **count**\<`T`\>(`args?`): [`PrismaPromise`](../type-aliases/PrismaPromise.md)\<`T` *extends* `Record_2`\<`"select"`, `any`\> ? `T`\<`T`\>\[`"select"`\] *extends* `true` ? `number` : \{ \[P in string \| number \| symbol\]: P extends keyof AccountCountAggregateOutputType ? AccountCountAggregateOutputType\[P\<P\>\] : never \} : `number`\>

Defined in: prisma-main/types/index.d.ts:3718

Count the number of Accounts.
Note, that providing `undefined` is treated as the value not being there.
Read more here: https://pris.ly/d/null-undefined

#### Type Parameters

##### T

`T` *extends* [`AccountCountArgs`](../type-aliases/AccountCountArgs.md)\<`DefaultArgs`\>

#### Parameters

##### args?

[`Subset`](../type-aliases/Subset.md)\<`T`, [`AccountCountArgs`](../type-aliases/AccountCountArgs.md)\<`DefaultArgs`\>\>

Arguments to filter Accounts to count.

#### Returns

[`PrismaPromise`](../type-aliases/PrismaPromise.md)\<`T` *extends* `Record_2`\<`"select"`, `any`\> ? `T`\<`T`\>\[`"select"`\] *extends* `true` ? `number` : \{ \[P in string \| number \| symbol\]: P extends keyof AccountCountAggregateOutputType ? AccountCountAggregateOutputType\[P\<P\>\] : never \} : `number`\>

#### Example

```ts
// Count the number of Accounts
const count = await prisma.account.count({
  where: {
    // ... the filter for the Accounts we want to count
  }
})
```

***

### create()

> **create**\<`T`\>(`args`): [`Prisma__AccountClient`](Prisma__AccountClient.md)\<`GetFindResult`\<[`$AccountPayload`](../type-aliases/$AccountPayload.md)\<`ExtArgs`\>, `T`, `GlobalOmitOptions`\>, `never`, `ExtArgs`, `GlobalOmitOptions`\>

Defined in: prisma-main/types/index.d.ts:3605

Create a Account.

#### Type Parameters

##### T

`T` *extends* [`AccountCreateArgs`](../type-aliases/AccountCreateArgs.md)\<`DefaultArgs`\>

#### Parameters

##### args

[`SelectSubset`](../type-aliases/SelectSubset.md)\<`T`, [`AccountCreateArgs`](../type-aliases/AccountCreateArgs.md)\<`ExtArgs`\>\>

Arguments to create a Account.

#### Returns

[`Prisma__AccountClient`](Prisma__AccountClient.md)\<`GetFindResult`\<[`$AccountPayload`](../type-aliases/$AccountPayload.md)\<`ExtArgs`\>, `T`, `GlobalOmitOptions`\>, `never`, `ExtArgs`, `GlobalOmitOptions`\>

#### Example

```ts
// Create one Account
const Account = await prisma.account.create({
  data: {
    // ... data to create a Account
  }
})
```

***

### createMany()

> **createMany**\<`T`\>(`args?`): [`PrismaPromise`](../type-aliases/PrismaPromise.md)\<[`BatchPayload`](../type-aliases/BatchPayload.md)\>

Defined in: prisma-main/types/index.d.ts:3619

Create many Accounts.

#### Type Parameters

##### T

`T` *extends* [`AccountCreateManyArgs`](../type-aliases/AccountCreateManyArgs.md)\<`DefaultArgs`\>

#### Parameters

##### args?

[`SelectSubset`](../type-aliases/SelectSubset.md)\<`T`, [`AccountCreateManyArgs`](../type-aliases/AccountCreateManyArgs.md)\<`ExtArgs`\>\>

Arguments to create many Accounts.

#### Returns

[`PrismaPromise`](../type-aliases/PrismaPromise.md)\<[`BatchPayload`](../type-aliases/BatchPayload.md)\>

#### Example

```ts
// Create many Accounts
const account = await prisma.account.createMany({
  data: [
    // ... provide data here
  ]
})
```

***

### delete()

> **delete**\<`T`\>(`args`): [`Prisma__AccountClient`](Prisma__AccountClient.md)\<`GetFindResult`\<[`$AccountPayload`](../type-aliases/$AccountPayload.md)\<`ExtArgs`\>, `T`, `GlobalOmitOptions`\>, `never`, `ExtArgs`, `GlobalOmitOptions`\>

Defined in: prisma-main/types/index.d.ts:3633

Delete a Account.

#### Type Parameters

##### T

`T` *extends* [`AccountDeleteArgs`](../type-aliases/AccountDeleteArgs.md)\<`DefaultArgs`\>

#### Parameters

##### args

[`SelectSubset`](../type-aliases/SelectSubset.md)\<`T`, [`AccountDeleteArgs`](../type-aliases/AccountDeleteArgs.md)\<`ExtArgs`\>\>

Arguments to delete one Account.

#### Returns

[`Prisma__AccountClient`](Prisma__AccountClient.md)\<`GetFindResult`\<[`$AccountPayload`](../type-aliases/$AccountPayload.md)\<`ExtArgs`\>, `T`, `GlobalOmitOptions`\>, `never`, `ExtArgs`, `GlobalOmitOptions`\>

#### Example

```ts
// Delete one Account
const Account = await prisma.account.delete({
  where: {
    // ... filter to delete one Account
  }
})
```

***

### deleteMany()

> **deleteMany**\<`T`\>(`args?`): [`PrismaPromise`](../type-aliases/PrismaPromise.md)\<[`BatchPayload`](../type-aliases/BatchPayload.md)\>

Defined in: prisma-main/types/index.d.ts:3664

Delete zero or more Accounts.

#### Type Parameters

##### T

`T` *extends* [`AccountDeleteManyArgs`](../type-aliases/AccountDeleteManyArgs.md)\<`DefaultArgs`\>

#### Parameters

##### args?

[`SelectSubset`](../type-aliases/SelectSubset.md)\<`T`, [`AccountDeleteManyArgs`](../type-aliases/AccountDeleteManyArgs.md)\<`ExtArgs`\>\>

Arguments to filter Accounts to delete.

#### Returns

[`PrismaPromise`](../type-aliases/PrismaPromise.md)\<[`BatchPayload`](../type-aliases/BatchPayload.md)\>

#### Example

```ts
// Delete a few Accounts
const { count } = await prisma.account.deleteMany({
  where: {
    // ... provide filter here
  }
})
```

***

### findFirst()

> **findFirst**\<`T`\>(`args?`): [`Prisma__AccountClient`](Prisma__AccountClient.md)\<`GetFindResult`\<[`$AccountPayload`](../type-aliases/$AccountPayload.md)\<`ExtArgs`\>, `T`, `GlobalOmitOptions`\> \| `null`, `null`, `ExtArgs`, `GlobalOmitOptions`\>

Defined in: prisma-main/types/index.d.ts:3557

Find the first Account that matches the filter.
Note, that providing `undefined` is treated as the value not being there.
Read more here: https://pris.ly/d/null-undefined

#### Type Parameters

##### T

`T` *extends* [`AccountFindFirstArgs`](../type-aliases/AccountFindFirstArgs.md)\<`DefaultArgs`\>

#### Parameters

##### args?

[`SelectSubset`](../type-aliases/SelectSubset.md)\<`T`, [`AccountFindFirstArgs`](../type-aliases/AccountFindFirstArgs.md)\<`ExtArgs`\>\>

Arguments to find a Account

#### Returns

[`Prisma__AccountClient`](Prisma__AccountClient.md)\<`GetFindResult`\<[`$AccountPayload`](../type-aliases/$AccountPayload.md)\<`ExtArgs`\>, `T`, `GlobalOmitOptions`\> \| `null`, `null`, `ExtArgs`, `GlobalOmitOptions`\>

#### Example

```ts
// Get one Account
const account = await prisma.account.findFirst({
  where: {
    // ... provide filter here
  }
})
```

***

### findFirstOrThrow()

> **findFirstOrThrow**\<`T`\>(`args?`): [`Prisma__AccountClient`](Prisma__AccountClient.md)\<`GetFindResult`\<[`$AccountPayload`](../type-aliases/$AccountPayload.md)\<`ExtArgs`\>, `T`, `GlobalOmitOptions`\>, `never`, `ExtArgs`, `GlobalOmitOptions`\>

Defined in: prisma-main/types/index.d.ts:3573

Find the first Account that matches the filter or
throw `PrismaKnownClientError` with `P2025` code if no matches were found.
Note, that providing `undefined` is treated as the value not being there.
Read more here: https://pris.ly/d/null-undefined

#### Type Parameters

##### T

`T` *extends* [`AccountFindFirstOrThrowArgs`](../type-aliases/AccountFindFirstOrThrowArgs.md)\<`DefaultArgs`\>

#### Parameters

##### args?

[`SelectSubset`](../type-aliases/SelectSubset.md)\<`T`, [`AccountFindFirstOrThrowArgs`](../type-aliases/AccountFindFirstOrThrowArgs.md)\<`ExtArgs`\>\>

Arguments to find a Account

#### Returns

[`Prisma__AccountClient`](Prisma__AccountClient.md)\<`GetFindResult`\<[`$AccountPayload`](../type-aliases/$AccountPayload.md)\<`ExtArgs`\>, `T`, `GlobalOmitOptions`\>, `never`, `ExtArgs`, `GlobalOmitOptions`\>

#### Example

```ts
// Get one Account
const account = await prisma.account.findFirstOrThrow({
  where: {
    // ... provide filter here
  }
})
```

***

### findMany()

> **findMany**\<`T`\>(`args?`): [`PrismaPromise`](../type-aliases/PrismaPromise.md)\<`GetFindResult`\<[`$AccountPayload`](../type-aliases/$AccountPayload.md)\<`ExtArgs`\>, `T`, `GlobalOmitOptions`\>[]\>

Defined in: prisma-main/types/index.d.ts:3591

Find zero or more Accounts that matches the filter.
Note, that providing `undefined` is treated as the value not being there.
Read more here: https://pris.ly/d/null-undefined

#### Type Parameters

##### T

`T` *extends* [`AccountFindManyArgs`](../type-aliases/AccountFindManyArgs.md)\<`DefaultArgs`\>

#### Parameters

##### args?

[`SelectSubset`](../type-aliases/SelectSubset.md)\<`T`, [`AccountFindManyArgs`](../type-aliases/AccountFindManyArgs.md)\<`ExtArgs`\>\>

Arguments to filter and select certain fields only.

#### Returns

[`PrismaPromise`](../type-aliases/PrismaPromise.md)\<`GetFindResult`\<[`$AccountPayload`](../type-aliases/$AccountPayload.md)\<`ExtArgs`\>, `T`, `GlobalOmitOptions`\>[]\>

#### Example

```ts
// Get all Accounts
const accounts = await prisma.account.findMany()

// Get first 10 Accounts
const accounts = await prisma.account.findMany({ take: 10 })

// Only select the `id`
const accountWithIdOnly = await prisma.account.findMany({ select: { id: true } })
```

***

### findUnique()

> **findUnique**\<`T`\>(`args`): [`Prisma__AccountClient`](Prisma__AccountClient.md)\<`GetFindResult`\<[`$AccountPayload`](../type-aliases/$AccountPayload.md)\<`ExtArgs`\>, `T`, `GlobalOmitOptions`\> \| `null`, `null`, `ExtArgs`, `GlobalOmitOptions`\>

Defined in: prisma-main/types/index.d.ts:3528

Find zero or one Account that matches the filter.

#### Type Parameters

##### T

`T` *extends* [`AccountFindUniqueArgs`](../type-aliases/AccountFindUniqueArgs.md)\<`DefaultArgs`\>

#### Parameters

##### args

[`SelectSubset`](../type-aliases/SelectSubset.md)\<`T`, [`AccountFindUniqueArgs`](../type-aliases/AccountFindUniqueArgs.md)\<`ExtArgs`\>\>

Arguments to find a Account

#### Returns

[`Prisma__AccountClient`](Prisma__AccountClient.md)\<`GetFindResult`\<[`$AccountPayload`](../type-aliases/$AccountPayload.md)\<`ExtArgs`\>, `T`, `GlobalOmitOptions`\> \| `null`, `null`, `ExtArgs`, `GlobalOmitOptions`\>

#### Example

```ts
// Get one Account
const account = await prisma.account.findUnique({
  where: {
    // ... provide filter here
  }
})
```

***

### findUniqueOrThrow()

> **findUniqueOrThrow**\<`T`\>(`args`): [`Prisma__AccountClient`](Prisma__AccountClient.md)\<`GetFindResult`\<[`$AccountPayload`](../type-aliases/$AccountPayload.md)\<`ExtArgs`\>, `T`, `GlobalOmitOptions`\>, `never`, `ExtArgs`, `GlobalOmitOptions`\>

Defined in: prisma-main/types/index.d.ts:3542

Find one Account that matches the filter or throw an error with `error.code='P2025'`
if no matches were found.

#### Type Parameters

##### T

`T` *extends* [`AccountFindUniqueOrThrowArgs`](../type-aliases/AccountFindUniqueOrThrowArgs.md)\<`DefaultArgs`\>

#### Parameters

##### args

[`SelectSubset`](../type-aliases/SelectSubset.md)\<`T`, [`AccountFindUniqueOrThrowArgs`](../type-aliases/AccountFindUniqueOrThrowArgs.md)\<`ExtArgs`\>\>

Arguments to find a Account

#### Returns

[`Prisma__AccountClient`](Prisma__AccountClient.md)\<`GetFindResult`\<[`$AccountPayload`](../type-aliases/$AccountPayload.md)\<`ExtArgs`\>, `T`, `GlobalOmitOptions`\>, `never`, `ExtArgs`, `GlobalOmitOptions`\>

#### Example

```ts
// Get one Account
const account = await prisma.account.findUniqueOrThrow({
  where: {
    // ... provide filter here
  }
})
```

***

### groupBy()

> **groupBy**\<`T`, `HasSelectOrTake`, `OrderByArg`, `OrderFields`, `ByFields`, `ByValid`, `HavingFields`, `HavingValid`, `ByEmpty`, `InputErrors`\>(`args`): `object` *extends* `InputErrors` ? [`GetAccountGroupByPayload`](../type-aliases/GetAccountGroupByPayload.md)\<`T`\> : [`PrismaPromise`](../type-aliases/PrismaPromise.md)\<`InputErrors`\>

Defined in: prisma-main/types/index.d.ts:3772

Group by Account.
Note, that providing `undefined` is treated as the value not being there.
Read more here: https://pris.ly/d/null-undefined

#### Type Parameters

##### T

`T` *extends* [`AccountGroupByArgs`](../type-aliases/AccountGroupByArgs.md)\<`DefaultArgs`\>

##### HasSelectOrTake

`HasSelectOrTake` *extends* `0` \| `1`

##### OrderByArg

`OrderByArg` *extends* \{ `orderBy`: [`AccountOrderByWithAggregationInput`](../type-aliases/AccountOrderByWithAggregationInput.md) \| [`AccountOrderByWithAggregationInput`](../type-aliases/AccountOrderByWithAggregationInput.md)[] \| `undefined`; \} \| \{ `orderBy?`: [`AccountOrderByWithAggregationInput`](../type-aliases/AccountOrderByWithAggregationInput.md) \| [`AccountOrderByWithAggregationInput`](../type-aliases/AccountOrderByWithAggregationInput.md)[]; \}

##### OrderFields

`OrderFields` *extends* `"id"` \| `"createdAt"` \| `"updatedAt"` \| `"userId"` \| `"accountId"` \| `"providerId"` \| `"accessToken"` \| `"refreshToken"` \| `"idToken"` \| `"accessTokenExpiresAt"` \| `"refreshTokenExpiresAt"` \| `"scope"` \| `"password"`

##### ByFields

`ByFields` *extends* [`AccountScalarFieldEnum`](../type-aliases/AccountScalarFieldEnum.md)

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

\{ \[key in string \| number \| symbol\]: key extends keyof AccountGroupByArgs\<DefaultArgs\> ? T\[key\<key\>\] : never \} & `OrderByArg` & `InputErrors`

Group by arguments.

#### Returns

`object` *extends* `InputErrors` ? [`GetAccountGroupByPayload`](../type-aliases/GetAccountGroupByPayload.md)\<`T`\> : [`PrismaPromise`](../type-aliases/PrismaPromise.md)\<`InputErrors`\>

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

> **update**\<`T`\>(`args`): [`Prisma__AccountClient`](Prisma__AccountClient.md)\<`GetFindResult`\<[`$AccountPayload`](../type-aliases/$AccountPayload.md)\<`ExtArgs`\>, `T`, `GlobalOmitOptions`\>, `never`, `ExtArgs`, `GlobalOmitOptions`\>

Defined in: prisma-main/types/index.d.ts:3650

Update one Account.

#### Type Parameters

##### T

`T` *extends* [`AccountUpdateArgs`](../type-aliases/AccountUpdateArgs.md)\<`DefaultArgs`\>

#### Parameters

##### args

[`SelectSubset`](../type-aliases/SelectSubset.md)\<`T`, [`AccountUpdateArgs`](../type-aliases/AccountUpdateArgs.md)\<`ExtArgs`\>\>

Arguments to update one Account.

#### Returns

[`Prisma__AccountClient`](Prisma__AccountClient.md)\<`GetFindResult`\<[`$AccountPayload`](../type-aliases/$AccountPayload.md)\<`ExtArgs`\>, `T`, `GlobalOmitOptions`\>, `never`, `ExtArgs`, `GlobalOmitOptions`\>

#### Example

```ts
// Update one Account
const account = await prisma.account.update({
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

Defined in: prisma-main/types/index.d.ts:3683

Update zero or more Accounts.
Note, that providing `undefined` is treated as the value not being there.
Read more here: https://pris.ly/d/null-undefined

#### Type Parameters

##### T

`T` *extends* [`AccountUpdateManyArgs`](../type-aliases/AccountUpdateManyArgs.md)\<`DefaultArgs`\>

#### Parameters

##### args

[`SelectSubset`](../type-aliases/SelectSubset.md)\<`T`, [`AccountUpdateManyArgs`](../type-aliases/AccountUpdateManyArgs.md)\<`ExtArgs`\>\>

Arguments to update one or more rows.

#### Returns

[`PrismaPromise`](../type-aliases/PrismaPromise.md)\<[`BatchPayload`](../type-aliases/BatchPayload.md)\>

#### Example

```ts
// Update many Accounts
const account = await prisma.account.updateMany({
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

> **upsert**\<`T`\>(`args`): [`Prisma__AccountClient`](Prisma__AccountClient.md)\<`GetFindResult`\<[`$AccountPayload`](../type-aliases/$AccountPayload.md)\<`ExtArgs`\>, `T`, `GlobalOmitOptions`\>, `never`, `ExtArgs`, `GlobalOmitOptions`\>

Defined in: prisma-main/types/index.d.ts:3702

Create or update one Account.

#### Type Parameters

##### T

`T` *extends* [`AccountUpsertArgs`](../type-aliases/AccountUpsertArgs.md)\<`DefaultArgs`\>

#### Parameters

##### args

[`SelectSubset`](../type-aliases/SelectSubset.md)\<`T`, [`AccountUpsertArgs`](../type-aliases/AccountUpsertArgs.md)\<`ExtArgs`\>\>

Arguments to update or create a Account.

#### Returns

[`Prisma__AccountClient`](Prisma__AccountClient.md)\<`GetFindResult`\<[`$AccountPayload`](../type-aliases/$AccountPayload.md)\<`ExtArgs`\>, `T`, `GlobalOmitOptions`\>, `never`, `ExtArgs`, `GlobalOmitOptions`\>

#### Example

```ts
// Update or create a Account
const account = await prisma.account.upsert({
  create: {
    // ... data to create a Account
  },
  update: {
    // ... in case it already exists, update
  },
  where: {
    // ... the filter for the Account we want to update
  }
})
```
