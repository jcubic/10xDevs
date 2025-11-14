[**10x-devs**](../../../../README.md)

***

[10x-devs](../../../../modules.md) / [prisma](../../../README.md) / [Prisma](../README.md) / \_Strict

# Type Alias: \_Strict\<U, _U\>

> **\_Strict**\<`U`, `_U`\> = `U` *extends* `unknown` ? `U` & [`OptionalFlat`](OptionalFlat.md)\<[`_Record`](Record.md)\<`Exclude`\<[`Keys`](Keys.md)\<`_U`\>, keyof `U`\>, `never`\>\> : `never`

Defined in: prisma-main/types/index.d.ts:539

## Type Parameters

### U

`U`

### _U

`_U` = `U`
