<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@firebase/auth](./auth.md) &gt; [signInWithCredential](./auth.signinwithcredential.md)

## signInWithCredential() function

Asynchronously signs in with the given credentials.

<b>Signature:</b>

```typescript
export declare function signInWithCredential(auth: externs.Auth, credential: externs.AuthCredential): Promise<externs.UserCredential>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  auth | externs.[Auth](./auth-types.auth.md) | The Auth instance. |
|  credential | externs.[AuthCredential](./auth-types.authcredential.md) | The auth credential. |

<b>Returns:</b>

Promise&lt;externs.[UserCredential](./auth-types.usercredential.md)<!-- -->&gt;

## Remarks

An [AuthProvider](./auth-types.authprovider.md) can be used to generate the credential.
