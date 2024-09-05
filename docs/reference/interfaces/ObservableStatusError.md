[**ReactFire reference docs**](../README.md) • **Docs**

***

[ReactFire reference docs](../README.md) / ObservableStatusError

# Interface: ObservableStatusError\<T\>

## Extends

- `ObservableStatusBase`\<`T`\>

## Type Parameters

• **T**

## Properties

### data

> **data**: `undefined` \| `T`

The most recent value.

If `initialData` is passed in, the first value of `data` will be the valuea provided in `initialData` **UNLESS** the underlying observable is ready, in which case it will skip `initialData`.

#### Inherited from

`ObservableStatusBase.data`

#### Defined in

[src/useObservable.ts:56](https://github.com/Synapski/reactfire/blob/main/src/useObservable.ts#L56)

***

### error

> **error**: `Error`

Any error that may have occurred in the underlying observable

#### Overrides

`ObservableStatusBase.error`

#### Defined in

[src/useObservable.ts:75](https://github.com/Synapski/reactfire/blob/main/src/useObservable.ts#L75)

***

### firstValuePromise

> **firstValuePromise**: `Promise`\<`void`\>

Promise that resolves after first emit from observable

#### Inherited from

`ObservableStatusBase.firstValuePromise`

#### Defined in

[src/useObservable.ts:64](https://github.com/Synapski/reactfire/blob/main/src/useObservable.ts#L64)

***

### hasEmitted

> **hasEmitted**: `boolean`

Indicates whether the hook has emitted a value at some point

If `initialData` is passed in, this will be `true`.

#### Inherited from

`ObservableStatusBase.hasEmitted`

#### Defined in

[src/useObservable.ts:46](https://github.com/Synapski/reactfire/blob/main/src/useObservable.ts#L46)

***

### isComplete

> **isComplete**: `true`

If this is `true`, the hook will be emitting no further items.

#### Overrides

`ObservableStatusBase.isComplete`

#### Defined in

[src/useObservable.ts:74](https://github.com/Synapski/reactfire/blob/main/src/useObservable.ts#L74)

***

### status

> **status**: `"error"`

The loading status.

- `loading`: Waiting for the first value from an observable
- `error`: Something went wrong. Check `ObservableStatus.error` for more details
- `success`: The hook has emitted at least one value

If `initialData` is passed in, this will skip `loading` and go straight to `success`.

#### Overrides

`ObservableStatusBase.status`

#### Defined in

[src/useObservable.ts:73](https://github.com/Synapski/reactfire/blob/main/src/useObservable.ts#L73)
