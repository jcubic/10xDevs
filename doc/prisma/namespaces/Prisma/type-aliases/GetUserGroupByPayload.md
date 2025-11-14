[**10x-devs**](../../../../README.md)

***

[10x-devs](../../../../modules.md) / [prisma](../../../README.md) / [Prisma](../README.md) / GetUserGroupByPayload

# Type Alias: GetUserGroupByPayload\<T\>

> **GetUserGroupByPayload**\<`T`\> = [`PrismaPromise`](PrismaPromise.md)\<[`PickEnumerable`](PickEnumerable.md)\<[`UserGroupByOutputType`](UserGroupByOutputType.md), `T`\[`"by"`\]\> & `{ [P in keyof T & keyof UserGroupByOutputType]: P extends "_count" ? T[P] extends boolean ? number : GetScalarType<T[P], UserGroupByOutputType[P]> : GetScalarType<T[P], UserGroupByOutputType[P]> }`[]\>

Defined in: prisma-main/types/index.d.ts:1394

## Type Parameters

### T

`T` *extends* [`UserGroupByArgs`](UserGroupByArgs.md)
