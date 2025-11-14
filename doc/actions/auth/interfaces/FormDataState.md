[**10x-devs**](../../../README.md)

***

[10x-devs](../../../modules.md) / [actions/auth](../README.md) / FormDataState

# Interface: FormDataState

Defined in: [src/app/actions/auth.ts:63](https://github.com/jcubic/10xDevs/blob/8643271036ed0399a2b11ac87568ff44ec315445/src/app/actions/auth.ts#L63)

State object returned by all auth form actions.
Used with React's useActionState hook for form handling.

 FormDataState

## Properties

### confirmationUrl?

> `optional` **confirmationUrl**: `string`

Defined in: [src/app/actions/auth.ts:69](https://github.com/jcubic/10xDevs/blob/8643271036ed0399a2b11ac87568ff44ec315445/src/app/actions/auth.ts#L69)

URL for confirmation (development mode only)

***

### email?

> `optional` **email**: `string`

Defined in: [src/app/actions/auth.ts:67](https://github.com/jcubic/10xDevs/blob/8643271036ed0399a2b11ac87568ff44ec315445/src/app/actions/auth.ts#L67)

Email address (for verification flows)

***

### errors?

> `optional` **errors**: `Record`\<`string`, `string`[]\>

Defined in: [src/app/actions/auth.ts:64](https://github.com/jcubic/10xDevs/blob/8643271036ed0399a2b11ac87568ff44ec315445/src/app/actions/auth.ts#L64)

Field-specific validation errors

***

### message?

> `optional` **message**: `string`

Defined in: [src/app/actions/auth.ts:65](https://github.com/jcubic/10xDevs/blob/8643271036ed0399a2b11ac87568ff44ec315445/src/app/actions/auth.ts#L65)

General success or error message

***

### requiresConfirmation?

> `optional` **requiresConfirmation**: `boolean`

Defined in: [src/app/actions/auth.ts:68](https://github.com/jcubic/10xDevs/blob/8643271036ed0399a2b11ac87568ff44ec315445/src/app/actions/auth.ts#L68)

Whether additional confirmation is needed

***

### success?

> `optional` **success**: `boolean`

Defined in: [src/app/actions/auth.ts:66](https://github.com/jcubic/10xDevs/blob/8643271036ed0399a2b11ac87568ff44ec315445/src/app/actions/auth.ts#L66)

Whether the action completed successfully
