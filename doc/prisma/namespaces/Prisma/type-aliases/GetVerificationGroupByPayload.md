[**10x-devs**](../../../../README.md)

***

[10x-devs](../../../../modules.md) / [prisma](../../../README.md) / [Prisma](../README.md) / GetVerificationGroupByPayload

# Type Alias: GetVerificationGroupByPayload\<T\>

> **GetVerificationGroupByPayload**\<`T`\> = [`PrismaPromise`](PrismaPromise.md)\<[`PickEnumerable`](PickEnumerable.md)\<[`VerificationGroupByOutputType`](VerificationGroupByOutputType.md), `T`\[`"by"`\]\> & `{ [P in keyof T & keyof VerificationGroupByOutputType]: P extends "_count" ? T[P] extends boolean ? number : GetScalarType<T[P], VerificationGroupByOutputType[P]> : GetScalarType<T[P], VerificationGroupByOutputType[P]> }`[]\>

Defined in: prisma-main/types/index.d.ts:4399

## Type Parameters

### T

`T` *extends* [`VerificationGroupByArgs`](VerificationGroupByArgs.md)
