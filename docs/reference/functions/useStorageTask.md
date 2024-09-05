[**ReactFire reference docs**](../README.md) • **Docs**

***

[ReactFire reference docs](../README.md) / useStorageTask

# Function: useStorageTask()

> **useStorageTask**\<`T`\>(`task`, `ref`, `options`?): [`ObservableStatus`](../type-aliases/ObservableStatus.md)\<`UploadTaskSnapshot` \| `T`\>

Subscribe to the progress of a storage task

## Type Parameters

• **T** = `unknown`

## Parameters

• **task**: `UploadTask`

the task you want to listen to

• **ref**: `StorageReference`

reference to the blob the task is acting on

• **options?**: [`ReactFireOptions`](../interfaces/ReactFireOptions.md)\<`T`\>

## Returns

[`ObservableStatus`](../type-aliases/ObservableStatus.md)\<`UploadTaskSnapshot` \| `T`\>

## Defined in

[src/storage.tsx:16](https://github.com/Synapski/reactfire/blob/main/src/storage.tsx#L16)
