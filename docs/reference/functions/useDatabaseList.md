[**ReactFire reference docs**](../README.md) • **Docs**

***

[ReactFire reference docs](../README.md) / useDatabaseList

# Function: useDatabaseList()

> **useDatabaseList**\<`T`\>(`ref`, `options`?): [`ObservableStatus`](../type-aliases/ObservableStatus.md)\<`QueryChange`[] \| `T`[]\>

Subscribe to a Realtime Database list

## Type Parameters

• **T** = `object`

## Parameters

• **ref**: `Query` \| `DatabaseReference`

Reference to the DB List you want to listen to

• **options?**: [`ReactFireOptions`](../interfaces/ReactFireOptions.md)\<`T`[]\>

## Returns

[`ObservableStatus`](../type-aliases/ObservableStatus.md)\<`QueryChange`[] \| `T`[]\>

## Defined in

[src/database.tsx:48](https://github.com/Synapski/reactfire/blob/main/src/database.tsx#L48)
