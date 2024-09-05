[**ReactFire reference docs**](../README.md) • **Docs**

***

[ReactFire reference docs](../README.md) / ReactFireError

# Class: ReactFireError

## Extends

- `Error`

## Constructors

### new ReactFireError()

> **new ReactFireError**(`code`, `message`, `customData`?): [`ReactFireError`](ReactFireError.md)

#### Parameters

• **code**: `string`

• **message**: `string`

• **customData?**: `Record`\<`string`, `unknown`\>

#### Returns

[`ReactFireError`](ReactFireError.md)

#### Overrides

`Error.constructor`

#### Defined in

[src/index.ts:15](https://github.com/Synapski/reactfire/blob/main/src/index.ts#L15)

## Properties

### cause?

> `optional` **cause**: `unknown`

#### Inherited from

`Error.cause`

#### Defined in

node\_modules/.pnpm/typescript@5.5.4/node\_modules/typescript/lib/lib.es2022.error.d.ts:24

***

### code

> `readonly` **code**: `string`

#### Defined in

[src/index.ts:15](https://github.com/Synapski/reactfire/blob/main/src/index.ts#L15)

***

### customData?

> `optional` **customData**: `Record`\<`string`, `unknown`\>

#### Defined in

[src/index.ts:15](https://github.com/Synapski/reactfire/blob/main/src/index.ts#L15)

***

### message

> **message**: `string`

#### Inherited from

`Error.message`

#### Defined in

node\_modules/.pnpm/typescript@5.5.4/node\_modules/typescript/lib/lib.es5.d.ts:1077

***

### name

> `readonly` **name**: `"ReactFireError"` = `'ReactFireError'`

#### Overrides

`Error.name`

#### Defined in

[src/index.ts:13](https://github.com/Synapski/reactfire/blob/main/src/index.ts#L13)

***

### stack?

> `optional` **stack**: `string`

#### Inherited from

`Error.stack`

#### Defined in

node\_modules/.pnpm/typescript@5.5.4/node\_modules/typescript/lib/lib.es5.d.ts:1078

***

### prepareStackTrace()?

> `static` `optional` **prepareStackTrace**: (`err`, `stackTraces`) => `any`

Optional override for formatting stack traces

#### Parameters

• **err**: `Error`

• **stackTraces**: `CallSite`[]

#### Returns

`any`

#### See

https://v8.dev/docs/stack-trace-api#customizing-stack-traces

#### Inherited from

`Error.prepareStackTrace`

#### Defined in

node\_modules/.pnpm/@types+node@22.5.4/node\_modules/@types/node/globals.d.ts:143

***

### stackTraceLimit

> `static` **stackTraceLimit**: `number`

#### Inherited from

`Error.stackTraceLimit`

#### Defined in

node\_modules/.pnpm/@types+node@22.5.4/node\_modules/@types/node/globals.d.ts:145

## Methods

### captureStackTrace()

> `static` **captureStackTrace**(`targetObject`, `constructorOpt`?): `void`

Create .stack property on a target object

#### Parameters

• **targetObject**: `object`

• **constructorOpt?**: `Function`

#### Returns

`void`

#### Inherited from

`Error.captureStackTrace`

#### Defined in

node\_modules/.pnpm/@types+node@22.5.4/node\_modules/@types/node/globals.d.ts:136
