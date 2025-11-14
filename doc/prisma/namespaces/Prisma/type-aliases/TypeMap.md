[**10x-devs**](../../../../README.md)

***

[10x-devs](../../../../modules.md) / [prisma](../../../README.md) / [Prisma](../README.md) / TypeMap

# Type Alias: TypeMap\<ExtArgs, GlobalOmitOptions\>

> **TypeMap**\<`ExtArgs`, `GlobalOmitOptions`\> = `object` & `object`

Defined in: prisma-main/types/index.d.ts:668

## Type Declaration

### globalOmitOptions

> **globalOmitOptions**: `object`

#### globalOmitOptions.omit

> **omit**: `GlobalOmitOptions`

### meta

> **meta**: `object`

#### meta.modelProps

> **modelProps**: `"user"` \| `"session"` \| `"account"` \| `"verification"` \| `"note"`

#### meta.txIsolationLevel

> **txIsolationLevel**: [`TransactionIsolationLevel`](TransactionIsolationLevel.md)

### model

> **model**: `object`

#### model.Account

> **Account**: `object`

#### model.Account.fields

> **fields**: [`AccountFieldRefs`](../interfaces/AccountFieldRefs.md)

#### model.Account.operations

> **operations**: `object`

#### model.Account.operations.aggregate

> **aggregate**: `object`

#### model.Account.operations.aggregate.args

> **args**: [`AccountAggregateArgs`](AccountAggregateArgs.md)\<`ExtArgs`\>

#### model.Account.operations.aggregate.result

> **result**: `$Utils.Optional`\<[`AggregateAccount`](AggregateAccount.md)\>

#### model.Account.operations.count

> **count**: `object`

#### model.Account.operations.count.args

> **args**: [`AccountCountArgs`](AccountCountArgs.md)\<`ExtArgs`\>

#### model.Account.operations.count.result

> **result**: `$Utils.Optional`\<[`AccountCountAggregateOutputType`](AccountCountAggregateOutputType.md)\> \| `number`

#### model.Account.operations.create

> **create**: `object`

#### model.Account.operations.create.args

> **args**: [`AccountCreateArgs`](AccountCreateArgs.md)\<`ExtArgs`\>

#### model.Account.operations.create.result

> **result**: `$Utils.PayloadToResult`\<[`$AccountPayload`]($AccountPayload.md)\>

#### model.Account.operations.createMany

> **createMany**: `object`

#### model.Account.operations.createMany.args

> **args**: [`AccountCreateManyArgs`](AccountCreateManyArgs.md)\<`ExtArgs`\>

#### model.Account.operations.createMany.result

> **result**: [`BatchPayload`](BatchPayload.md)

#### model.Account.operations.delete

> **delete**: `object`

#### model.Account.operations.delete.args

> **args**: [`AccountDeleteArgs`](AccountDeleteArgs.md)\<`ExtArgs`\>

#### model.Account.operations.delete.result

> **result**: `$Utils.PayloadToResult`\<[`$AccountPayload`]($AccountPayload.md)\>

#### model.Account.operations.deleteMany

> **deleteMany**: `object`

#### model.Account.operations.deleteMany.args

> **args**: [`AccountDeleteManyArgs`](AccountDeleteManyArgs.md)\<`ExtArgs`\>

#### model.Account.operations.deleteMany.result

> **result**: [`BatchPayload`](BatchPayload.md)

#### model.Account.operations.findFirst

> **findFirst**: `object`

#### model.Account.operations.findFirst.args

> **args**: [`AccountFindFirstArgs`](AccountFindFirstArgs.md)\<`ExtArgs`\>

#### model.Account.operations.findFirst.result

> **result**: `$Utils.PayloadToResult`\<[`$AccountPayload`]($AccountPayload.md)\> \| `null`

#### model.Account.operations.findFirstOrThrow

> **findFirstOrThrow**: `object`

#### model.Account.operations.findFirstOrThrow.args

> **args**: [`AccountFindFirstOrThrowArgs`](AccountFindFirstOrThrowArgs.md)\<`ExtArgs`\>

#### model.Account.operations.findFirstOrThrow.result

> **result**: `$Utils.PayloadToResult`\<[`$AccountPayload`]($AccountPayload.md)\>

#### model.Account.operations.findMany

> **findMany**: `object`

#### model.Account.operations.findMany.args

> **args**: [`AccountFindManyArgs`](AccountFindManyArgs.md)\<`ExtArgs`\>

#### model.Account.operations.findMany.result

> **result**: `$Utils.PayloadToResult`\<[`$AccountPayload`]($AccountPayload.md)\>[]

#### model.Account.operations.findUnique

> **findUnique**: `object`

#### model.Account.operations.findUnique.args

> **args**: [`AccountFindUniqueArgs`](AccountFindUniqueArgs.md)\<`ExtArgs`\>

#### model.Account.operations.findUnique.result

> **result**: `$Utils.PayloadToResult`\<[`$AccountPayload`]($AccountPayload.md)\> \| `null`

#### model.Account.operations.findUniqueOrThrow

> **findUniqueOrThrow**: `object`

#### model.Account.operations.findUniqueOrThrow.args

> **args**: [`AccountFindUniqueOrThrowArgs`](AccountFindUniqueOrThrowArgs.md)\<`ExtArgs`\>

#### model.Account.operations.findUniqueOrThrow.result

> **result**: `$Utils.PayloadToResult`\<[`$AccountPayload`]($AccountPayload.md)\>

#### model.Account.operations.groupBy

> **groupBy**: `object`

#### model.Account.operations.groupBy.args

> **args**: [`AccountGroupByArgs`](AccountGroupByArgs.md)\<`ExtArgs`\>

#### model.Account.operations.groupBy.result

> **result**: `$Utils.Optional`\<[`AccountGroupByOutputType`](AccountGroupByOutputType.md)\>[]

#### model.Account.operations.update

> **update**: `object`

#### model.Account.operations.update.args

> **args**: [`AccountUpdateArgs`](AccountUpdateArgs.md)\<`ExtArgs`\>

#### model.Account.operations.update.result

> **result**: `$Utils.PayloadToResult`\<[`$AccountPayload`]($AccountPayload.md)\>

#### model.Account.operations.updateMany

> **updateMany**: `object`

#### model.Account.operations.updateMany.args

> **args**: [`AccountUpdateManyArgs`](AccountUpdateManyArgs.md)\<`ExtArgs`\>

#### model.Account.operations.updateMany.result

> **result**: [`BatchPayload`](BatchPayload.md)

#### model.Account.operations.upsert

> **upsert**: `object`

#### model.Account.operations.upsert.args

> **args**: [`AccountUpsertArgs`](AccountUpsertArgs.md)\<`ExtArgs`\>

#### model.Account.operations.upsert.result

> **result**: `$Utils.PayloadToResult`\<[`$AccountPayload`]($AccountPayload.md)\>

#### model.Account.payload

> **payload**: [`$AccountPayload`]($AccountPayload.md)\<`ExtArgs`\>

#### model.Note

> **Note**: `object`

#### model.Note.fields

> **fields**: [`NoteFieldRefs`](../interfaces/NoteFieldRefs.md)

#### model.Note.operations

> **operations**: `object`

#### model.Note.operations.aggregate

> **aggregate**: `object`

#### model.Note.operations.aggregate.args

> **args**: [`NoteAggregateArgs`](NoteAggregateArgs.md)\<`ExtArgs`\>

#### model.Note.operations.aggregate.result

> **result**: `$Utils.Optional`\<[`AggregateNote`](AggregateNote.md)\>

#### model.Note.operations.count

> **count**: `object`

#### model.Note.operations.count.args

> **args**: [`NoteCountArgs`](NoteCountArgs.md)\<`ExtArgs`\>

#### model.Note.operations.count.result

> **result**: `$Utils.Optional`\<[`NoteCountAggregateOutputType`](NoteCountAggregateOutputType.md)\> \| `number`

#### model.Note.operations.create

> **create**: `object`

#### model.Note.operations.create.args

> **args**: [`NoteCreateArgs`](NoteCreateArgs.md)\<`ExtArgs`\>

#### model.Note.operations.create.result

> **result**: `$Utils.PayloadToResult`\<[`$NotePayload`]($NotePayload.md)\>

#### model.Note.operations.createMany

> **createMany**: `object`

#### model.Note.operations.createMany.args

> **args**: [`NoteCreateManyArgs`](NoteCreateManyArgs.md)\<`ExtArgs`\>

#### model.Note.operations.createMany.result

> **result**: [`BatchPayload`](BatchPayload.md)

#### model.Note.operations.delete

> **delete**: `object`

#### model.Note.operations.delete.args

> **args**: [`NoteDeleteArgs`](NoteDeleteArgs.md)\<`ExtArgs`\>

#### model.Note.operations.delete.result

> **result**: `$Utils.PayloadToResult`\<[`$NotePayload`]($NotePayload.md)\>

#### model.Note.operations.deleteMany

> **deleteMany**: `object`

#### model.Note.operations.deleteMany.args

> **args**: [`NoteDeleteManyArgs`](NoteDeleteManyArgs.md)\<`ExtArgs`\>

#### model.Note.operations.deleteMany.result

> **result**: [`BatchPayload`](BatchPayload.md)

#### model.Note.operations.findFirst

> **findFirst**: `object`

#### model.Note.operations.findFirst.args

> **args**: [`NoteFindFirstArgs`](NoteFindFirstArgs.md)\<`ExtArgs`\>

#### model.Note.operations.findFirst.result

> **result**: `$Utils.PayloadToResult`\<[`$NotePayload`]($NotePayload.md)\> \| `null`

#### model.Note.operations.findFirstOrThrow

> **findFirstOrThrow**: `object`

#### model.Note.operations.findFirstOrThrow.args

> **args**: [`NoteFindFirstOrThrowArgs`](NoteFindFirstOrThrowArgs.md)\<`ExtArgs`\>

#### model.Note.operations.findFirstOrThrow.result

> **result**: `$Utils.PayloadToResult`\<[`$NotePayload`]($NotePayload.md)\>

#### model.Note.operations.findMany

> **findMany**: `object`

#### model.Note.operations.findMany.args

> **args**: [`NoteFindManyArgs`](NoteFindManyArgs.md)\<`ExtArgs`\>

#### model.Note.operations.findMany.result

> **result**: `$Utils.PayloadToResult`\<[`$NotePayload`]($NotePayload.md)\>[]

#### model.Note.operations.findUnique

> **findUnique**: `object`

#### model.Note.operations.findUnique.args

> **args**: [`NoteFindUniqueArgs`](NoteFindUniqueArgs.md)\<`ExtArgs`\>

#### model.Note.operations.findUnique.result

> **result**: `$Utils.PayloadToResult`\<[`$NotePayload`]($NotePayload.md)\> \| `null`

#### model.Note.operations.findUniqueOrThrow

> **findUniqueOrThrow**: `object`

#### model.Note.operations.findUniqueOrThrow.args

> **args**: [`NoteFindUniqueOrThrowArgs`](NoteFindUniqueOrThrowArgs.md)\<`ExtArgs`\>

#### model.Note.operations.findUniqueOrThrow.result

> **result**: `$Utils.PayloadToResult`\<[`$NotePayload`]($NotePayload.md)\>

#### model.Note.operations.groupBy

> **groupBy**: `object`

#### model.Note.operations.groupBy.args

> **args**: [`NoteGroupByArgs`](NoteGroupByArgs.md)\<`ExtArgs`\>

#### model.Note.operations.groupBy.result

> **result**: `$Utils.Optional`\<[`NoteGroupByOutputType`](NoteGroupByOutputType.md)\>[]

#### model.Note.operations.update

> **update**: `object`

#### model.Note.operations.update.args

> **args**: [`NoteUpdateArgs`](NoteUpdateArgs.md)\<`ExtArgs`\>

#### model.Note.operations.update.result

> **result**: `$Utils.PayloadToResult`\<[`$NotePayload`]($NotePayload.md)\>

#### model.Note.operations.updateMany

> **updateMany**: `object`

#### model.Note.operations.updateMany.args

> **args**: [`NoteUpdateManyArgs`](NoteUpdateManyArgs.md)\<`ExtArgs`\>

#### model.Note.operations.updateMany.result

> **result**: [`BatchPayload`](BatchPayload.md)

#### model.Note.operations.upsert

> **upsert**: `object`

#### model.Note.operations.upsert.args

> **args**: [`NoteUpsertArgs`](NoteUpsertArgs.md)\<`ExtArgs`\>

#### model.Note.operations.upsert.result

> **result**: `$Utils.PayloadToResult`\<[`$NotePayload`]($NotePayload.md)\>

#### model.Note.payload

> **payload**: [`$NotePayload`]($NotePayload.md)\<`ExtArgs`\>

#### model.Session

> **Session**: `object`

#### model.Session.fields

> **fields**: [`SessionFieldRefs`](../interfaces/SessionFieldRefs.md)

#### model.Session.operations

> **operations**: `object`

#### model.Session.operations.aggregate

> **aggregate**: `object`

#### model.Session.operations.aggregate.args

> **args**: [`SessionAggregateArgs`](SessionAggregateArgs.md)\<`ExtArgs`\>

#### model.Session.operations.aggregate.result

> **result**: `$Utils.Optional`\<[`AggregateSession`](AggregateSession.md)\>

#### model.Session.operations.count

> **count**: `object`

#### model.Session.operations.count.args

> **args**: [`SessionCountArgs`](SessionCountArgs.md)\<`ExtArgs`\>

#### model.Session.operations.count.result

> **result**: `$Utils.Optional`\<[`SessionCountAggregateOutputType`](SessionCountAggregateOutputType.md)\> \| `number`

#### model.Session.operations.create

> **create**: `object`

#### model.Session.operations.create.args

> **args**: [`SessionCreateArgs`](SessionCreateArgs.md)\<`ExtArgs`\>

#### model.Session.operations.create.result

> **result**: `$Utils.PayloadToResult`\<[`$SessionPayload`]($SessionPayload.md)\>

#### model.Session.operations.createMany

> **createMany**: `object`

#### model.Session.operations.createMany.args

> **args**: [`SessionCreateManyArgs`](SessionCreateManyArgs.md)\<`ExtArgs`\>

#### model.Session.operations.createMany.result

> **result**: [`BatchPayload`](BatchPayload.md)

#### model.Session.operations.delete

> **delete**: `object`

#### model.Session.operations.delete.args

> **args**: [`SessionDeleteArgs`](SessionDeleteArgs.md)\<`ExtArgs`\>

#### model.Session.operations.delete.result

> **result**: `$Utils.PayloadToResult`\<[`$SessionPayload`]($SessionPayload.md)\>

#### model.Session.operations.deleteMany

> **deleteMany**: `object`

#### model.Session.operations.deleteMany.args

> **args**: [`SessionDeleteManyArgs`](SessionDeleteManyArgs.md)\<`ExtArgs`\>

#### model.Session.operations.deleteMany.result

> **result**: [`BatchPayload`](BatchPayload.md)

#### model.Session.operations.findFirst

> **findFirst**: `object`

#### model.Session.operations.findFirst.args

> **args**: [`SessionFindFirstArgs`](SessionFindFirstArgs.md)\<`ExtArgs`\>

#### model.Session.operations.findFirst.result

> **result**: `$Utils.PayloadToResult`\<[`$SessionPayload`]($SessionPayload.md)\> \| `null`

#### model.Session.operations.findFirstOrThrow

> **findFirstOrThrow**: `object`

#### model.Session.operations.findFirstOrThrow.args

> **args**: [`SessionFindFirstOrThrowArgs`](SessionFindFirstOrThrowArgs.md)\<`ExtArgs`\>

#### model.Session.operations.findFirstOrThrow.result

> **result**: `$Utils.PayloadToResult`\<[`$SessionPayload`]($SessionPayload.md)\>

#### model.Session.operations.findMany

> **findMany**: `object`

#### model.Session.operations.findMany.args

> **args**: [`SessionFindManyArgs`](SessionFindManyArgs.md)\<`ExtArgs`\>

#### model.Session.operations.findMany.result

> **result**: `$Utils.PayloadToResult`\<[`$SessionPayload`]($SessionPayload.md)\>[]

#### model.Session.operations.findUnique

> **findUnique**: `object`

#### model.Session.operations.findUnique.args

> **args**: [`SessionFindUniqueArgs`](SessionFindUniqueArgs.md)\<`ExtArgs`\>

#### model.Session.operations.findUnique.result

> **result**: `$Utils.PayloadToResult`\<[`$SessionPayload`]($SessionPayload.md)\> \| `null`

#### model.Session.operations.findUniqueOrThrow

> **findUniqueOrThrow**: `object`

#### model.Session.operations.findUniqueOrThrow.args

> **args**: [`SessionFindUniqueOrThrowArgs`](SessionFindUniqueOrThrowArgs.md)\<`ExtArgs`\>

#### model.Session.operations.findUniqueOrThrow.result

> **result**: `$Utils.PayloadToResult`\<[`$SessionPayload`]($SessionPayload.md)\>

#### model.Session.operations.groupBy

> **groupBy**: `object`

#### model.Session.operations.groupBy.args

> **args**: [`SessionGroupByArgs`](SessionGroupByArgs.md)\<`ExtArgs`\>

#### model.Session.operations.groupBy.result

> **result**: `$Utils.Optional`\<[`SessionGroupByOutputType`](SessionGroupByOutputType.md)\>[]

#### model.Session.operations.update

> **update**: `object`

#### model.Session.operations.update.args

> **args**: [`SessionUpdateArgs`](SessionUpdateArgs.md)\<`ExtArgs`\>

#### model.Session.operations.update.result

> **result**: `$Utils.PayloadToResult`\<[`$SessionPayload`]($SessionPayload.md)\>

#### model.Session.operations.updateMany

> **updateMany**: `object`

#### model.Session.operations.updateMany.args

> **args**: [`SessionUpdateManyArgs`](SessionUpdateManyArgs.md)\<`ExtArgs`\>

#### model.Session.operations.updateMany.result

> **result**: [`BatchPayload`](BatchPayload.md)

#### model.Session.operations.upsert

> **upsert**: `object`

#### model.Session.operations.upsert.args

> **args**: [`SessionUpsertArgs`](SessionUpsertArgs.md)\<`ExtArgs`\>

#### model.Session.operations.upsert.result

> **result**: `$Utils.PayloadToResult`\<[`$SessionPayload`]($SessionPayload.md)\>

#### model.Session.payload

> **payload**: [`$SessionPayload`]($SessionPayload.md)\<`ExtArgs`\>

#### model.User

> **User**: `object`

#### model.User.fields

> **fields**: [`UserFieldRefs`](../interfaces/UserFieldRefs.md)

#### model.User.operations

> **operations**: `object`

#### model.User.operations.aggregate

> **aggregate**: `object`

#### model.User.operations.aggregate.args

> **args**: [`UserAggregateArgs`](UserAggregateArgs.md)\<`ExtArgs`\>

#### model.User.operations.aggregate.result

> **result**: `$Utils.Optional`\<[`AggregateUser`](AggregateUser.md)\>

#### model.User.operations.count

> **count**: `object`

#### model.User.operations.count.args

> **args**: [`UserCountArgs`](UserCountArgs.md)\<`ExtArgs`\>

#### model.User.operations.count.result

> **result**: `$Utils.Optional`\<[`UserCountAggregateOutputType`](UserCountAggregateOutputType.md)\> \| `number`

#### model.User.operations.create

> **create**: `object`

#### model.User.operations.create.args

> **args**: [`UserCreateArgs`](UserCreateArgs.md)\<`ExtArgs`\>

#### model.User.operations.create.result

> **result**: `$Utils.PayloadToResult`\<[`$UserPayload`]($UserPayload.md)\>

#### model.User.operations.createMany

> **createMany**: `object`

#### model.User.operations.createMany.args

> **args**: [`UserCreateManyArgs`](UserCreateManyArgs.md)\<`ExtArgs`\>

#### model.User.operations.createMany.result

> **result**: [`BatchPayload`](BatchPayload.md)

#### model.User.operations.delete

> **delete**: `object`

#### model.User.operations.delete.args

> **args**: [`UserDeleteArgs`](UserDeleteArgs.md)\<`ExtArgs`\>

#### model.User.operations.delete.result

> **result**: `$Utils.PayloadToResult`\<[`$UserPayload`]($UserPayload.md)\>

#### model.User.operations.deleteMany

> **deleteMany**: `object`

#### model.User.operations.deleteMany.args

> **args**: [`UserDeleteManyArgs`](UserDeleteManyArgs.md)\<`ExtArgs`\>

#### model.User.operations.deleteMany.result

> **result**: [`BatchPayload`](BatchPayload.md)

#### model.User.operations.findFirst

> **findFirst**: `object`

#### model.User.operations.findFirst.args

> **args**: [`UserFindFirstArgs`](UserFindFirstArgs.md)\<`ExtArgs`\>

#### model.User.operations.findFirst.result

> **result**: `$Utils.PayloadToResult`\<[`$UserPayload`]($UserPayload.md)\> \| `null`

#### model.User.operations.findFirstOrThrow

> **findFirstOrThrow**: `object`

#### model.User.operations.findFirstOrThrow.args

> **args**: [`UserFindFirstOrThrowArgs`](UserFindFirstOrThrowArgs.md)\<`ExtArgs`\>

#### model.User.operations.findFirstOrThrow.result

> **result**: `$Utils.PayloadToResult`\<[`$UserPayload`]($UserPayload.md)\>

#### model.User.operations.findMany

> **findMany**: `object`

#### model.User.operations.findMany.args

> **args**: [`UserFindManyArgs`](UserFindManyArgs.md)\<`ExtArgs`\>

#### model.User.operations.findMany.result

> **result**: `$Utils.PayloadToResult`\<[`$UserPayload`]($UserPayload.md)\>[]

#### model.User.operations.findUnique

> **findUnique**: `object`

#### model.User.operations.findUnique.args

> **args**: [`UserFindUniqueArgs`](UserFindUniqueArgs.md)\<`ExtArgs`\>

#### model.User.operations.findUnique.result

> **result**: `$Utils.PayloadToResult`\<[`$UserPayload`]($UserPayload.md)\> \| `null`

#### model.User.operations.findUniqueOrThrow

> **findUniqueOrThrow**: `object`

#### model.User.operations.findUniqueOrThrow.args

> **args**: [`UserFindUniqueOrThrowArgs`](UserFindUniqueOrThrowArgs.md)\<`ExtArgs`\>

#### model.User.operations.findUniqueOrThrow.result

> **result**: `$Utils.PayloadToResult`\<[`$UserPayload`]($UserPayload.md)\>

#### model.User.operations.groupBy

> **groupBy**: `object`

#### model.User.operations.groupBy.args

> **args**: [`UserGroupByArgs`](UserGroupByArgs.md)\<`ExtArgs`\>

#### model.User.operations.groupBy.result

> **result**: `$Utils.Optional`\<[`UserGroupByOutputType`](UserGroupByOutputType.md)\>[]

#### model.User.operations.update

> **update**: `object`

#### model.User.operations.update.args

> **args**: [`UserUpdateArgs`](UserUpdateArgs.md)\<`ExtArgs`\>

#### model.User.operations.update.result

> **result**: `$Utils.PayloadToResult`\<[`$UserPayload`]($UserPayload.md)\>

#### model.User.operations.updateMany

> **updateMany**: `object`

#### model.User.operations.updateMany.args

> **args**: [`UserUpdateManyArgs`](UserUpdateManyArgs.md)\<`ExtArgs`\>

#### model.User.operations.updateMany.result

> **result**: [`BatchPayload`](BatchPayload.md)

#### model.User.operations.upsert

> **upsert**: `object`

#### model.User.operations.upsert.args

> **args**: [`UserUpsertArgs`](UserUpsertArgs.md)\<`ExtArgs`\>

#### model.User.operations.upsert.result

> **result**: `$Utils.PayloadToResult`\<[`$UserPayload`]($UserPayload.md)\>

#### model.User.payload

> **payload**: [`$UserPayload`]($UserPayload.md)\<`ExtArgs`\>

#### model.Verification

> **Verification**: `object`

#### model.Verification.fields

> **fields**: [`VerificationFieldRefs`](../interfaces/VerificationFieldRefs.md)

#### model.Verification.operations

> **operations**: `object`

#### model.Verification.operations.aggregate

> **aggregate**: `object`

#### model.Verification.operations.aggregate.args

> **args**: [`VerificationAggregateArgs`](VerificationAggregateArgs.md)\<`ExtArgs`\>

#### model.Verification.operations.aggregate.result

> **result**: `$Utils.Optional`\<[`AggregateVerification`](AggregateVerification.md)\>

#### model.Verification.operations.count

> **count**: `object`

#### model.Verification.operations.count.args

> **args**: [`VerificationCountArgs`](VerificationCountArgs.md)\<`ExtArgs`\>

#### model.Verification.operations.count.result

> **result**: `$Utils.Optional`\<[`VerificationCountAggregateOutputType`](VerificationCountAggregateOutputType.md)\> \| `number`

#### model.Verification.operations.create

> **create**: `object`

#### model.Verification.operations.create.args

> **args**: [`VerificationCreateArgs`](VerificationCreateArgs.md)\<`ExtArgs`\>

#### model.Verification.operations.create.result

> **result**: `$Utils.PayloadToResult`\<[`$VerificationPayload`]($VerificationPayload.md)\>

#### model.Verification.operations.createMany

> **createMany**: `object`

#### model.Verification.operations.createMany.args

> **args**: [`VerificationCreateManyArgs`](VerificationCreateManyArgs.md)\<`ExtArgs`\>

#### model.Verification.operations.createMany.result

> **result**: [`BatchPayload`](BatchPayload.md)

#### model.Verification.operations.delete

> **delete**: `object`

#### model.Verification.operations.delete.args

> **args**: [`VerificationDeleteArgs`](VerificationDeleteArgs.md)\<`ExtArgs`\>

#### model.Verification.operations.delete.result

> **result**: `$Utils.PayloadToResult`\<[`$VerificationPayload`]($VerificationPayload.md)\>

#### model.Verification.operations.deleteMany

> **deleteMany**: `object`

#### model.Verification.operations.deleteMany.args

> **args**: [`VerificationDeleteManyArgs`](VerificationDeleteManyArgs.md)\<`ExtArgs`\>

#### model.Verification.operations.deleteMany.result

> **result**: [`BatchPayload`](BatchPayload.md)

#### model.Verification.operations.findFirst

> **findFirst**: `object`

#### model.Verification.operations.findFirst.args

> **args**: [`VerificationFindFirstArgs`](VerificationFindFirstArgs.md)\<`ExtArgs`\>

#### model.Verification.operations.findFirst.result

> **result**: `$Utils.PayloadToResult`\<[`$VerificationPayload`]($VerificationPayload.md)\> \| `null`

#### model.Verification.operations.findFirstOrThrow

> **findFirstOrThrow**: `object`

#### model.Verification.operations.findFirstOrThrow.args

> **args**: [`VerificationFindFirstOrThrowArgs`](VerificationFindFirstOrThrowArgs.md)\<`ExtArgs`\>

#### model.Verification.operations.findFirstOrThrow.result

> **result**: `$Utils.PayloadToResult`\<[`$VerificationPayload`]($VerificationPayload.md)\>

#### model.Verification.operations.findMany

> **findMany**: `object`

#### model.Verification.operations.findMany.args

> **args**: [`VerificationFindManyArgs`](VerificationFindManyArgs.md)\<`ExtArgs`\>

#### model.Verification.operations.findMany.result

> **result**: `$Utils.PayloadToResult`\<[`$VerificationPayload`]($VerificationPayload.md)\>[]

#### model.Verification.operations.findUnique

> **findUnique**: `object`

#### model.Verification.operations.findUnique.args

> **args**: [`VerificationFindUniqueArgs`](VerificationFindUniqueArgs.md)\<`ExtArgs`\>

#### model.Verification.operations.findUnique.result

> **result**: `$Utils.PayloadToResult`\<[`$VerificationPayload`]($VerificationPayload.md)\> \| `null`

#### model.Verification.operations.findUniqueOrThrow

> **findUniqueOrThrow**: `object`

#### model.Verification.operations.findUniqueOrThrow.args

> **args**: [`VerificationFindUniqueOrThrowArgs`](VerificationFindUniqueOrThrowArgs.md)\<`ExtArgs`\>

#### model.Verification.operations.findUniqueOrThrow.result

> **result**: `$Utils.PayloadToResult`\<[`$VerificationPayload`]($VerificationPayload.md)\>

#### model.Verification.operations.groupBy

> **groupBy**: `object`

#### model.Verification.operations.groupBy.args

> **args**: [`VerificationGroupByArgs`](VerificationGroupByArgs.md)\<`ExtArgs`\>

#### model.Verification.operations.groupBy.result

> **result**: `$Utils.Optional`\<[`VerificationGroupByOutputType`](VerificationGroupByOutputType.md)\>[]

#### model.Verification.operations.update

> **update**: `object`

#### model.Verification.operations.update.args

> **args**: [`VerificationUpdateArgs`](VerificationUpdateArgs.md)\<`ExtArgs`\>

#### model.Verification.operations.update.result

> **result**: `$Utils.PayloadToResult`\<[`$VerificationPayload`]($VerificationPayload.md)\>

#### model.Verification.operations.updateMany

> **updateMany**: `object`

#### model.Verification.operations.updateMany.args

> **args**: [`VerificationUpdateManyArgs`](VerificationUpdateManyArgs.md)\<`ExtArgs`\>

#### model.Verification.operations.updateMany.result

> **result**: [`BatchPayload`](BatchPayload.md)

#### model.Verification.operations.upsert

> **upsert**: `object`

#### model.Verification.operations.upsert.args

> **args**: [`VerificationUpsertArgs`](VerificationUpsertArgs.md)\<`ExtArgs`\>

#### model.Verification.operations.upsert.result

> **result**: `$Utils.PayloadToResult`\<[`$VerificationPayload`]($VerificationPayload.md)\>

#### model.Verification.payload

> **payload**: [`$VerificationPayload`]($VerificationPayload.md)\<`ExtArgs`\>

## Type Declaration

### other

> **other**: `object`

#### other.operations

> **operations**: `object`

#### other.operations.$executeRaw

> **$executeRaw**: `object`

#### other.operations.$executeRaw.args

> **args**: \[`TemplateStringsArray` \| [`Sql`](../classes/Sql.md), `any`[]\]

#### other.operations.$executeRaw.result

> **result**: `any`

#### other.operations.$executeRawUnsafe

> **$executeRawUnsafe**: `object`

#### other.operations.$executeRawUnsafe.args

> **args**: \[`string`, `any`[]\]

#### other.operations.$executeRawUnsafe.result

> **result**: `any`

#### other.operations.$queryRaw

> **$queryRaw**: `object`

#### other.operations.$queryRaw.args

> **args**: \[`TemplateStringsArray` \| [`Sql`](../classes/Sql.md), `any`[]\]

#### other.operations.$queryRaw.result

> **result**: `any`

#### other.operations.$queryRawUnsafe

> **$queryRawUnsafe**: `object`

#### other.operations.$queryRawUnsafe.args

> **args**: \[`string`, `any`[]\]

#### other.operations.$queryRawUnsafe.result

> **result**: `any`

#### other.payload

> **payload**: `any`

## Type Parameters

### ExtArgs

`ExtArgs` *extends* `$Extensions.InternalArgs` = `$Extensions.DefaultArgs`

### GlobalOmitOptions

`GlobalOmitOptions` = \{ \}
