[**ReactFire reference docs**](../README.md) • **Docs**

***

[ReactFire reference docs](../README.md) / useFirestoreCollectionData

# Function: useFirestoreCollectionData()

> **useFirestoreCollectionData**\<`T`\>(`query`, `options`?): [`ObservableStatus`](../type-aliases/ObservableStatus.md)\<`T`[]\>

Subscribe to a Firestore collection and unwrap the snapshot into an array.

## Type Parameters

• **T** = `DocumentData`

## Parameters

• **query**: `Query`\<`T`, `DocumentData`\>

• **options?**: [`ReactFireOptions`](../interfaces/ReactFireOptions.md)\<`T`[]\>

## Returns

[`ObservableStatus`](../type-aliases/ObservableStatus.md)\<`T`[]\>

## Defined in

[src/firestore.tsx:96](https://github.com/Synapski/reactfire/blob/main/src/firestore.tsx#L96)
