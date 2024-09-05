[**ReactFire reference docs**](../README.md) • **Docs**

***

[ReactFire reference docs](../README.md) / useDatabaseObject

# Function: useDatabaseObject()

> **useDatabaseObject**\<`T`\>(`ref`, `options`?): [`ObservableStatus`](../type-aliases/ObservableStatus.md)\<`QueryChange` \| `T`\>

Subscribe to a Realtime Database object

## Type Parameters

• **T** = `unknown`

## Parameters

• **ref**: `DatabaseReference`

Reference to the DB object you want to listen to

• **options?**: [`ReactFireOptions`](../interfaces/ReactFireOptions.md)\<`T`\>

## Returns

[`ObservableStatus`](../type-aliases/ObservableStatus.md)\<`QueryChange` \| `T`\>

## Defined in

[src/database.tsx:27](https://github.com/Synapski/reactfire/blob/main/src/database.tsx#L27)
