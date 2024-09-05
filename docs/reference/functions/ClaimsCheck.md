[**ReactFire reference docs**](../README.md) • **Docs**

***

[ReactFire reference docs](../README.md) / ClaimsCheck

# Function: ~~ClaimsCheck()~~

> **ClaimsCheck**(`__namedParameters`): `Element`

## Parameters

• **\_\_namedParameters**: [`ClaimsCheckProps`](../interfaces/ClaimsCheckProps.md)

## Returns

`Element`

## Deprecated

Use `useSigninCheck` instead

Conditionally render children based on [custom claims](https://firebase.google.com/docs/auth/admin/custom-claims).

Meant for Concurrent mode only (`<FirebaseAppProvider suspense=true />`). [More detail](https://github.com/FirebaseExtended/reactfire/issues/325#issuecomment-827654376).

## Defined in

[src/auth.tsx:203](https://github.com/Synapski/reactfire/blob/main/src/auth.tsx#L203)
