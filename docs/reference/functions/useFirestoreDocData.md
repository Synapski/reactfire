[**ReactFire reference docs**](../README.md) • **Docs**

***

[ReactFire reference docs](../README.md) / useFirestoreDocData

# Function: useFirestoreDocData()

> **useFirestoreDocData**\<`T`\>(`ref`, `options`?): [`ObservableStatus`](../type-aliases/ObservableStatus.md)\<`T` \| `undefined`\>

Subscribe to Firestore Document changes and unwrap the document into a plain object

## Type Parameters

• **T** = `unknown`

## Parameters

• **ref**: `DocumentReference`\<`T`, `DocumentData`\>

• **options?**: [`ReactFireOptions`](../interfaces/ReactFireOptions.md)\<`T`\>

## Returns

[`ObservableStatus`](../type-aliases/ObservableStatus.md)\<`T` \| `undefined`\>

## Defined in

[src/firestore.tsx:62](https://github.com/Synapski/reactfire/blob/main/src/firestore.tsx#L62)
