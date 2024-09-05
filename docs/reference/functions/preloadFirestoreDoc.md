[**ReactFire reference docs**](../README.md) • **Docs**

***

[ReactFire reference docs](../README.md) / preloadFirestoreDoc

# Function: preloadFirestoreDoc()

> **preloadFirestoreDoc**(`refProvider`): `Promise`\<`SuspenseSubject`\<`DocumentSnapshot`\<`DocumentData`, `DocumentData`\>\>\>

Preload a subscription to a Firestore document reference.

Use this to warm up `useFirestoreDoc` for a specific document

## Parameters

• **refProvider**

## Returns

`Promise`\<`SuspenseSubject`\<`DocumentSnapshot`\<`DocumentData`, `DocumentData`\>\>\>

## Defined in

[src/firestore.tsx:28](https://github.com/Synapski/reactfire/blob/main/src/firestore.tsx#L28)
