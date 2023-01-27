---
id: core.icredentialverifier.verifypresentation
title: ICredentialVerifier.verifyPresentation() method
hide_title: true
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

## ICredentialVerifier.verifyPresentation() method

Verifies a Verifiable Presentation JWT or LDS Format.

<b>Signature:</b>

```typescript
verifyPresentation(args: IVerifyPresentationArgs, context: VerifierAgentContext): Promise<IVerifyResult>;
```

## Parameters

| Parameter | Type                                                         | Description                                                                                  |
| --------- | ------------------------------------------------------------ | -------------------------------------------------------------------------------------------- |
| args      | [IVerifyPresentationArgs](./core.iverifypresentationargs.md) | Arguments necessary to verify a VerifiableCredential                                         |
| context   | [VerifierAgentContext](./core.verifieragentcontext.md)       | This reserved param is automatically added and handled by the framework, \*do not override\* |

<b>Returns:</b>

Promise&lt;[IVerifyResult](./core.iverifyresult.md)&gt;

- a promise that resolves to an object containing a `verified` boolean property and an optional `error` for details

## Remarks

Please see [Verifiable Credential data model](https://www.w3.org/TR/vc-data-model/#presentations)