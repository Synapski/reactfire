[**ReactFire reference docs**](../README.md) • **Docs**

***

[ReactFire reference docs](../README.md) / useStorageDownloadURL

# Function: useStorageDownloadURL()

> **useStorageDownloadURL**\<`T`\>(`ref`, `options`?): [`ObservableStatus`](../type-aliases/ObservableStatus.md)\<`string` \| `T`\>

Subscribe to a storage ref's download URL

## Type Parameters

• **T** = `string`

## Parameters

• **ref**: `StorageReference`

reference to the blob you want to download

• **options?**: [`ReactFireOptions`](../interfaces/ReactFireOptions.md)\<`T`\>

## Returns

[`ObservableStatus`](../type-aliases/ObservableStatus.md)\<`string` \| `T`\>

## Defined in

[src/storage.tsx:29](https://github.com/Synapski/reactfire/blob/main/src/storage.tsx#L29)
