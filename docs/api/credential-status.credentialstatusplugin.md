---
id: credential-status.credentialstatusplugin
title: CredentialStatusPlugin class
hide_title: true
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

## CredentialStatusPlugin class

> This API is provided as a preview for developers and may change based on feedback that we receive. Do not use this API in a production environment.

This plugin implements the [ICredentialStatusVerifier](./core.icredentialstatusverifier.md) interface.

This aggregates some to provide a second layer of validation when verifying Verifiable Credentials.

This is used for the discovery of information about the current status of a verifiable credential, such as whether it is suspended or revoked. The precise contents of the credential status information is determined by the specific `credentialStatus` type definition.

The results provided by this plugin depend on whether the required by the credential is installed.

<b>Signature:</b>

```typescript
export declare class CredentialStatusPlugin implements IAgentPlugin
```

<b>Implements:</b> [IAgentPlugin](./core.iagentplugin.md)

## Constructors

| Constructor                                                                            | Modifiers | Description                                                                                     |
| -------------------------------------------------------------------------------------- | --------- | ----------------------------------------------------------------------------------------------- |
| [(constructor)(registry)](./credential-status.credentialstatusplugin._constructor_.md) |           | <b><i>(BETA)</i></b> Constructs a new instance of the <code>CredentialStatusPlugin</code> class |

## Properties

| Property                                                         | Modifiers             | Type                                                             | Description          |
| ---------------------------------------------------------------- | --------------------- | ---------------------------------------------------------------- | -------------------- |
| [methods](./credential-status.credentialstatusplugin.methods.md) | <code>readonly</code> | [ICredentialStatusVerifier](./core.icredentialstatusverifier.md) | <b><i>(BETA)</i></b> |