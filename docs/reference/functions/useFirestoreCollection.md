[**ReactFire reference docs**](../README.md) • **Docs**

***

[ReactFire reference docs](../README.md) / useFirestoreCollection

# Function: useFirestoreCollection()

> **useFirestoreCollection**\<`T`\>(`query`, `options`?): [`ObservableStatus`](../type-aliases/ObservableStatus.md)\<`QuerySnapshot`\<`T`\>\>

Subscribe to a Firestore collection

## Type Parameters

• **T** = `DocumentData`

## Parameters

• **query**: `Query`\<`T`, `DocumentData`\>

• **options?**: [`ReactFireOptions`](../interfaces/ReactFireOptions.md)\<`T`[]\>

## Returns

[`ObservableStatus`](../type-aliases/ObservableStatus.md)\<`QuerySnapshot`\<`T`\>\>

## Defined in

[src/firestore.tsx:86](https://github.com/Synapski/reactfire/blob/main/src/firestore.tsx#L86)
