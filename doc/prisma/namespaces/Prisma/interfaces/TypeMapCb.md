[**10x-devs**](../../../../README.md)

***

[10x-devs](../../../../modules.md) / [prisma](../../../README.md) / [Prisma](../README.md) / TypeMapCb

# Interface: TypeMapCb\<ClientOptions\>

Defined in: prisma-main/types/index.d.ts:664

## Extends

- `Fn`\<\{ `extArgs`: `$Extensions.InternalArgs`; \}, `$Utils.Record`\<`string`, `any`\>\>

## Type Parameters

### ClientOptions

`ClientOptions` = \{ \}

## Properties

### params

> **params**: `object`

Defined in: prisma-main/types/runtime/library.d.ts:1432

#### extArgs

> **extArgs**: `InternalArgs`

#### Inherited from

`$Utils.Fn.params`

***

### returns

> **returns**: [`TypeMap`](../type-aliases/TypeMap.md)\<`InternalArgs`, `ClientOptions` *extends* `object` ? `OmitOptions` : `object`\>

Defined in: prisma-main/types/index.d.ts:665

#### Overrides

`$Utils.Fn.returns`
