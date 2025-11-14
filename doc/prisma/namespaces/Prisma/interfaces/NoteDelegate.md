[**10x-devs**](../../../../README.md)

***

[10x-devs](../../../../modules.md) / [prisma](../../../README.md) / [Prisma](../README.md) / NoteDelegate

# Interface: NoteDelegate\<ExtArgs, GlobalOmitOptions\>

Defined in: prisma-main/types/index.d.ts:5389

## Type Parameters

### ExtArgs

`ExtArgs` *extends* `$Extensions.InternalArgs` = `$Extensions.DefaultArgs`

### GlobalOmitOptions

`GlobalOmitOptions` = \{ \}

## Indexable

\[`K`: `symbol`\]: `object`

## Properties

### fields

> `readonly` **fields**: [`NoteFieldRefs`](NoteFieldRefs.md)

Defined in: prisma-main/types/index.d.ts:5707

Fields of the Note model

## Methods

### aggregate()

> **aggregate**\<`T`\>(`args`): [`PrismaPromise`](../type-aliases/PrismaPromise.md)\<[`GetNoteAggregateType`](../type-aliases/GetNoteAggregateType.md)\<`T`\>\>

Defined in: prisma-main/types/index.d.ts:5626

Allows you to perform aggregations operations on a Note.
Note, that providing `undefined` is treated as the value not being there.
Read more here: https://pris.ly/d/null-undefined

#### Type Parameters

##### T

`T` *extends* [`NoteAggregateArgs`](../type-aliases/NoteAggregateArgs.md)\<`DefaultArgs`\>

#### Parameters

##### args

[`Subset`](../type-aliases/Subset.md)\<`T`, [`NoteAggregateArgs`](../type-aliases/NoteAggregateArgs.md)\>

Select which aggregations you would like to apply and on what fields.

#### Returns

[`PrismaPromise`](../type-aliases/PrismaPromise.md)\<[`GetNoteAggregateType`](../type-aliases/GetNoteAggregateType.md)\<`T`\>\>

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

> **count**\<`T`\>(`args?`): [`PrismaPromise`](../type-aliases/PrismaPromise.md)\<`T` *extends* `Record_2`\<`"select"`, `any`\> ? `T`\<`T`\>\[`"select"`\] *extends* `true` ? `number` : \{ \[P in string \| number \| symbol\]: P extends keyof NoteCountAggregateOutputType ? NoteCountAggregateOutputType\[P\<P\>\] : never \} : `number`\>

Defined in: prisma-main/types/index.d.ts:5592

Count the number of Notes.
Note, that providing `undefined` is treated as the value not being there.
Read more here: https://pris.ly/d/null-undefined

#### Type Parameters

##### T

`T` *extends* [`NoteCountArgs`](../type-aliases/NoteCountArgs.md)\<`DefaultArgs`\>

#### Parameters

##### args?

[`Subset`](../type-aliases/Subset.md)\<`T`, [`NoteCountArgs`](../type-aliases/NoteCountArgs.md)\<`DefaultArgs`\>\>

Arguments to filter Notes to count.

#### Returns

[`PrismaPromise`](../type-aliases/PrismaPromise.md)\<`T` *extends* `Record_2`\<`"select"`, `any`\> ? `T`\<`T`\>\[`"select"`\] *extends* `true` ? `number` : \{ \[P in string \| number \| symbol\]: P extends keyof NoteCountAggregateOutputType ? NoteCountAggregateOutputType\[P\<P\>\] : never \} : `number`\>

#### Example

```ts
// Count the number of Notes
const count = await prisma.note.count({
  where: {
    // ... the filter for the Notes we want to count
  }
})
```

***

### create()

> **create**\<`T`\>(`args`): [`Prisma__NoteClient`](Prisma__NoteClient.md)\<`GetFindResult`\<[`$NotePayload`](../type-aliases/$NotePayload.md)\<`ExtArgs`\>, `T`, `GlobalOmitOptions`\>, `never`, `ExtArgs`, `GlobalOmitOptions`\>

Defined in: prisma-main/types/index.d.ts:5479

Create a Note.

#### Type Parameters

##### T

`T` *extends* [`NoteCreateArgs`](../type-aliases/NoteCreateArgs.md)\<`DefaultArgs`\>

#### Parameters

##### args

[`SelectSubset`](../type-aliases/SelectSubset.md)\<`T`, [`NoteCreateArgs`](../type-aliases/NoteCreateArgs.md)\<`ExtArgs`\>\>

Arguments to create a Note.

#### Returns

[`Prisma__NoteClient`](Prisma__NoteClient.md)\<`GetFindResult`\<[`$NotePayload`](../type-aliases/$NotePayload.md)\<`ExtArgs`\>, `T`, `GlobalOmitOptions`\>, `never`, `ExtArgs`, `GlobalOmitOptions`\>

#### Example

```ts
// Create one Note
const Note = await prisma.note.create({
  data: {
    // ... data to create a Note
  }
})
```

***

### createMany()

> **createMany**\<`T`\>(`args?`): [`PrismaPromise`](../type-aliases/PrismaPromise.md)\<[`BatchPayload`](../type-aliases/BatchPayload.md)\>

Defined in: prisma-main/types/index.d.ts:5493

Create many Notes.

#### Type Parameters

##### T

`T` *extends* [`NoteCreateManyArgs`](../type-aliases/NoteCreateManyArgs.md)\<`DefaultArgs`\>

#### Parameters

##### args?

[`SelectSubset`](../type-aliases/SelectSubset.md)\<`T`, [`NoteCreateManyArgs`](../type-aliases/NoteCreateManyArgs.md)\<`ExtArgs`\>\>

Arguments to create many Notes.

#### Returns

[`PrismaPromise`](../type-aliases/PrismaPromise.md)\<[`BatchPayload`](../type-aliases/BatchPayload.md)\>

#### Example

```ts
// Create many Notes
const note = await prisma.note.createMany({
  data: [
    // ... provide data here
  ]
})
```

***

### delete()

> **delete**\<`T`\>(`args`): [`Prisma__NoteClient`](Prisma__NoteClient.md)\<`GetFindResult`\<[`$NotePayload`](../type-aliases/$NotePayload.md)\<`ExtArgs`\>, `T`, `GlobalOmitOptions`\>, `never`, `ExtArgs`, `GlobalOmitOptions`\>

Defined in: prisma-main/types/index.d.ts:5507

Delete a Note.

#### Type Parameters

##### T

`T` *extends* [`NoteDeleteArgs`](../type-aliases/NoteDeleteArgs.md)\<`DefaultArgs`\>

#### Parameters

##### args

[`SelectSubset`](../type-aliases/SelectSubset.md)\<`T`, [`NoteDeleteArgs`](../type-aliases/NoteDeleteArgs.md)\<`ExtArgs`\>\>

Arguments to delete one Note.

#### Returns

[`Prisma__NoteClient`](Prisma__NoteClient.md)\<`GetFindResult`\<[`$NotePayload`](../type-aliases/$NotePayload.md)\<`ExtArgs`\>, `T`, `GlobalOmitOptions`\>, `never`, `ExtArgs`, `GlobalOmitOptions`\>

#### Example

```ts
// Delete one Note
const Note = await prisma.note.delete({
  where: {
    // ... filter to delete one Note
  }
})
```

***

### deleteMany()

> **deleteMany**\<`T`\>(`args?`): [`PrismaPromise`](../type-aliases/PrismaPromise.md)\<[`BatchPayload`](../type-aliases/BatchPayload.md)\>

Defined in: prisma-main/types/index.d.ts:5538

Delete zero or more Notes.

#### Type Parameters

##### T

`T` *extends* [`NoteDeleteManyArgs`](../type-aliases/NoteDeleteManyArgs.md)\<`DefaultArgs`\>

#### Parameters

##### args?

[`SelectSubset`](../type-aliases/SelectSubset.md)\<`T`, [`NoteDeleteManyArgs`](../type-aliases/NoteDeleteManyArgs.md)\<`ExtArgs`\>\>

Arguments to filter Notes to delete.

#### Returns

[`PrismaPromise`](../type-aliases/PrismaPromise.md)\<[`BatchPayload`](../type-aliases/BatchPayload.md)\>

#### Example

```ts
// Delete a few Notes
const { count } = await prisma.note.deleteMany({
  where: {
    // ... provide filter here
  }
})
```

***

### findFirst()

> **findFirst**\<`T`\>(`args?`): [`Prisma__NoteClient`](Prisma__NoteClient.md)\<`GetFindResult`\<[`$NotePayload`](../type-aliases/$NotePayload.md)\<`ExtArgs`\>, `T`, `GlobalOmitOptions`\> \| `null`, `null`, `ExtArgs`, `GlobalOmitOptions`\>

Defined in: prisma-main/types/index.d.ts:5431

Find the first Note that matches the filter.
Note, that providing `undefined` is treated as the value not being there.
Read more here: https://pris.ly/d/null-undefined

#### Type Parameters

##### T

`T` *extends* [`NoteFindFirstArgs`](../type-aliases/NoteFindFirstArgs.md)\<`DefaultArgs`\>

#### Parameters

##### args?

[`SelectSubset`](../type-aliases/SelectSubset.md)\<`T`, [`NoteFindFirstArgs`](../type-aliases/NoteFindFirstArgs.md)\<`ExtArgs`\>\>

Arguments to find a Note

#### Returns

[`Prisma__NoteClient`](Prisma__NoteClient.md)\<`GetFindResult`\<[`$NotePayload`](../type-aliases/$NotePayload.md)\<`ExtArgs`\>, `T`, `GlobalOmitOptions`\> \| `null`, `null`, `ExtArgs`, `GlobalOmitOptions`\>

#### Example

```ts
// Get one Note
const note = await prisma.note.findFirst({
  where: {
    // ... provide filter here
  }
})
```

***

### findFirstOrThrow()

> **findFirstOrThrow**\<`T`\>(`args?`): [`Prisma__NoteClient`](Prisma__NoteClient.md)\<`GetFindResult`\<[`$NotePayload`](../type-aliases/$NotePayload.md)\<`ExtArgs`\>, `T`, `GlobalOmitOptions`\>, `never`, `ExtArgs`, `GlobalOmitOptions`\>

Defined in: prisma-main/types/index.d.ts:5447

Find the first Note that matches the filter or
throw `PrismaKnownClientError` with `P2025` code if no matches were found.
Note, that providing `undefined` is treated as the value not being there.
Read more here: https://pris.ly/d/null-undefined

#### Type Parameters

##### T

`T` *extends* [`NoteFindFirstOrThrowArgs`](../type-aliases/NoteFindFirstOrThrowArgs.md)\<`DefaultArgs`\>

#### Parameters

##### args?

[`SelectSubset`](../type-aliases/SelectSubset.md)\<`T`, [`NoteFindFirstOrThrowArgs`](../type-aliases/NoteFindFirstOrThrowArgs.md)\<`ExtArgs`\>\>

Arguments to find a Note

#### Returns

[`Prisma__NoteClient`](Prisma__NoteClient.md)\<`GetFindResult`\<[`$NotePayload`](../type-aliases/$NotePayload.md)\<`ExtArgs`\>, `T`, `GlobalOmitOptions`\>, `never`, `ExtArgs`, `GlobalOmitOptions`\>

#### Example

```ts
// Get one Note
const note = await prisma.note.findFirstOrThrow({
  where: {
    // ... provide filter here
  }
})
```

***

### findMany()

> **findMany**\<`T`\>(`args?`): [`PrismaPromise`](../type-aliases/PrismaPromise.md)\<`GetFindResult`\<[`$NotePayload`](../type-aliases/$NotePayload.md)\<`ExtArgs`\>, `T`, `GlobalOmitOptions`\>[]\>

Defined in: prisma-main/types/index.d.ts:5465

Find zero or more Notes that matches the filter.
Note, that providing `undefined` is treated as the value not being there.
Read more here: https://pris.ly/d/null-undefined

#### Type Parameters

##### T

`T` *extends* [`NoteFindManyArgs`](../type-aliases/NoteFindManyArgs.md)\<`DefaultArgs`\>

#### Parameters

##### args?

[`SelectSubset`](../type-aliases/SelectSubset.md)\<`T`, [`NoteFindManyArgs`](../type-aliases/NoteFindManyArgs.md)\<`ExtArgs`\>\>

Arguments to filter and select certain fields only.

#### Returns

[`PrismaPromise`](../type-aliases/PrismaPromise.md)\<`GetFindResult`\<[`$NotePayload`](../type-aliases/$NotePayload.md)\<`ExtArgs`\>, `T`, `GlobalOmitOptions`\>[]\>

#### Example

```ts
// Get all Notes
const notes = await prisma.note.findMany()

// Get first 10 Notes
const notes = await prisma.note.findMany({ take: 10 })

// Only select the `noteId`
const noteWithNoteIdOnly = await prisma.note.findMany({ select: { noteId: true } })
```

***

### findUnique()

> **findUnique**\<`T`\>(`args`): [`Prisma__NoteClient`](Prisma__NoteClient.md)\<`GetFindResult`\<[`$NotePayload`](../type-aliases/$NotePayload.md)\<`ExtArgs`\>, `T`, `GlobalOmitOptions`\> \| `null`, `null`, `ExtArgs`, `GlobalOmitOptions`\>

Defined in: prisma-main/types/index.d.ts:5402

Find zero or one Note that matches the filter.

#### Type Parameters

##### T

`T` *extends* [`NoteFindUniqueArgs`](../type-aliases/NoteFindUniqueArgs.md)\<`DefaultArgs`\>

#### Parameters

##### args

[`SelectSubset`](../type-aliases/SelectSubset.md)\<`T`, [`NoteFindUniqueArgs`](../type-aliases/NoteFindUniqueArgs.md)\<`ExtArgs`\>\>

Arguments to find a Note

#### Returns

[`Prisma__NoteClient`](Prisma__NoteClient.md)\<`GetFindResult`\<[`$NotePayload`](../type-aliases/$NotePayload.md)\<`ExtArgs`\>, `T`, `GlobalOmitOptions`\> \| `null`, `null`, `ExtArgs`, `GlobalOmitOptions`\>

#### Example

```ts
// Get one Note
const note = await prisma.note.findUnique({
  where: {
    // ... provide filter here
  }
})
```

***

### findUniqueOrThrow()

> **findUniqueOrThrow**\<`T`\>(`args`): [`Prisma__NoteClient`](Prisma__NoteClient.md)\<`GetFindResult`\<[`$NotePayload`](../type-aliases/$NotePayload.md)\<`ExtArgs`\>, `T`, `GlobalOmitOptions`\>, `never`, `ExtArgs`, `GlobalOmitOptions`\>

Defined in: prisma-main/types/index.d.ts:5416

Find one Note that matches the filter or throw an error with `error.code='P2025'`
if no matches were found.

#### Type Parameters

##### T

`T` *extends* [`NoteFindUniqueOrThrowArgs`](../type-aliases/NoteFindUniqueOrThrowArgs.md)\<`DefaultArgs`\>

#### Parameters

##### args

[`SelectSubset`](../type-aliases/SelectSubset.md)\<`T`, [`NoteFindUniqueOrThrowArgs`](../type-aliases/NoteFindUniqueOrThrowArgs.md)\<`ExtArgs`\>\>

Arguments to find a Note

#### Returns

[`Prisma__NoteClient`](Prisma__NoteClient.md)\<`GetFindResult`\<[`$NotePayload`](../type-aliases/$NotePayload.md)\<`ExtArgs`\>, `T`, `GlobalOmitOptions`\>, `never`, `ExtArgs`, `GlobalOmitOptions`\>

#### Example

```ts
// Get one Note
const note = await prisma.note.findUniqueOrThrow({
  where: {
    // ... provide filter here
  }
})
```

***

### groupBy()

> **groupBy**\<`T`, `HasSelectOrTake`, `OrderByArg`, `OrderFields`, `ByFields`, `ByValid`, `HavingFields`, `HavingValid`, `ByEmpty`, `InputErrors`\>(`args`): `object` *extends* `InputErrors` ? [`GetNoteGroupByPayload`](../type-aliases/GetNoteGroupByPayload.md)\<`T`\> : [`PrismaPromise`](../type-aliases/PrismaPromise.md)\<`InputErrors`\>

Defined in: prisma-main/types/index.d.ts:5646

Group by Note.
Note, that providing `undefined` is treated as the value not being there.
Read more here: https://pris.ly/d/null-undefined

#### Type Parameters

##### T

`T` *extends* [`NoteGroupByArgs`](../type-aliases/NoteGroupByArgs.md)\<`DefaultArgs`\>

##### HasSelectOrTake

`HasSelectOrTake` *extends* `0` \| `1`

##### OrderByArg

`OrderByArg` *extends* \{ `orderBy`: [`NoteOrderByWithAggregationInput`](../type-aliases/NoteOrderByWithAggregationInput.md) \| [`NoteOrderByWithAggregationInput`](../type-aliases/NoteOrderByWithAggregationInput.md)[] \| `undefined`; \} \| \{ `orderBy?`: [`NoteOrderByWithAggregationInput`](../type-aliases/NoteOrderByWithAggregationInput.md) \| [`NoteOrderByWithAggregationInput`](../type-aliases/NoteOrderByWithAggregationInput.md)[]; \}

##### OrderFields

`OrderFields` *extends* `"name"` \| `"createdAt"` \| `"updatedAt"` \| `"userId"` \| `"noteId"` \| `"content"`

##### ByFields

`ByFields` *extends* [`NoteScalarFieldEnum`](../type-aliases/NoteScalarFieldEnum.md)

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

\{ \[key in string \| number \| symbol\]: key extends keyof NoteGroupByArgs\<DefaultArgs\> ? T\[key\<key\>\] : never \} & `OrderByArg` & `InputErrors`

Group by arguments.

#### Returns

`object` *extends* `InputErrors` ? [`GetNoteGroupByPayload`](../type-aliases/GetNoteGroupByPayload.md)\<`T`\> : [`PrismaPromise`](../type-aliases/PrismaPromise.md)\<`InputErrors`\>

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

> **update**\<`T`\>(`args`): [`Prisma__NoteClient`](Prisma__NoteClient.md)\<`GetFindResult`\<[`$NotePayload`](../type-aliases/$NotePayload.md)\<`ExtArgs`\>, `T`, `GlobalOmitOptions`\>, `never`, `ExtArgs`, `GlobalOmitOptions`\>

Defined in: prisma-main/types/index.d.ts:5524

Update one Note.

#### Type Parameters

##### T

`T` *extends* [`NoteUpdateArgs`](../type-aliases/NoteUpdateArgs.md)\<`DefaultArgs`\>

#### Parameters

##### args

[`SelectSubset`](../type-aliases/SelectSubset.md)\<`T`, [`NoteUpdateArgs`](../type-aliases/NoteUpdateArgs.md)\<`ExtArgs`\>\>

Arguments to update one Note.

#### Returns

[`Prisma__NoteClient`](Prisma__NoteClient.md)\<`GetFindResult`\<[`$NotePayload`](../type-aliases/$NotePayload.md)\<`ExtArgs`\>, `T`, `GlobalOmitOptions`\>, `never`, `ExtArgs`, `GlobalOmitOptions`\>

#### Example

```ts
// Update one Note
const note = await prisma.note.update({
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

Defined in: prisma-main/types/index.d.ts:5557

Update zero or more Notes.
Note, that providing `undefined` is treated as the value not being there.
Read more here: https://pris.ly/d/null-undefined

#### Type Parameters

##### T

`T` *extends* [`NoteUpdateManyArgs`](../type-aliases/NoteUpdateManyArgs.md)\<`DefaultArgs`\>

#### Parameters

##### args

[`SelectSubset`](../type-aliases/SelectSubset.md)\<`T`, [`NoteUpdateManyArgs`](../type-aliases/NoteUpdateManyArgs.md)\<`ExtArgs`\>\>

Arguments to update one or more rows.

#### Returns

[`PrismaPromise`](../type-aliases/PrismaPromise.md)\<[`BatchPayload`](../type-aliases/BatchPayload.md)\>

#### Example

```ts
// Update many Notes
const note = await prisma.note.updateMany({
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

> **upsert**\<`T`\>(`args`): [`Prisma__NoteClient`](Prisma__NoteClient.md)\<`GetFindResult`\<[`$NotePayload`](../type-aliases/$NotePayload.md)\<`ExtArgs`\>, `T`, `GlobalOmitOptions`\>, `never`, `ExtArgs`, `GlobalOmitOptions`\>

Defined in: prisma-main/types/index.d.ts:5576

Create or update one Note.

#### Type Parameters

##### T

`T` *extends* [`NoteUpsertArgs`](../type-aliases/NoteUpsertArgs.md)\<`DefaultArgs`\>

#### Parameters

##### args

[`SelectSubset`](../type-aliases/SelectSubset.md)\<`T`, [`NoteUpsertArgs`](../type-aliases/NoteUpsertArgs.md)\<`ExtArgs`\>\>

Arguments to update or create a Note.

#### Returns

[`Prisma__NoteClient`](Prisma__NoteClient.md)\<`GetFindResult`\<[`$NotePayload`](../type-aliases/$NotePayload.md)\<`ExtArgs`\>, `T`, `GlobalOmitOptions`\>, `never`, `ExtArgs`, `GlobalOmitOptions`\>

#### Example

```ts
// Update or create a Note
const note = await prisma.note.upsert({
  create: {
    // ... data to create a Note
  },
  update: {
    // ... in case it already exists, update
  },
  where: {
    // ... the filter for the Note we want to update
  }
})
```
