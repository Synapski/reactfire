[**ReactFire reference docs**](../README.md) • **Docs**

***

[ReactFire reference docs](../README.md) / AuthCheck

# Function: ~~AuthCheck()~~

> **AuthCheck**(`__namedParameters`): `JSX.Element`

## Parameters

• **\_\_namedParameters**: [`AuthCheckProps`](../interfaces/AuthCheckProps.md)

## Returns

`JSX.Element`

## Deprecated

Use `useSigninCheck` instead

Conditionally render children based on signed-in status and [custom claims](https://firebase.google.com/docs/auth/admin/custom-claims).

Meant for Concurrent mode only (`<FirebaseAppProvider suspense=true />`). [More detail](https://github.com/FirebaseExtended/reactfire/issues/325#issuecomment-827654376).

## Defined in

[src/auth.tsx:247](https://github.com/Synapski/reactfire/blob/main/src/auth.tsx#L247)
