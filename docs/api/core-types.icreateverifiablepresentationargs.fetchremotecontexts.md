---
id: core-types.icreateverifiablepresentationargs.fetchremotecontexts
title: ICreateVerifiablePresentationArgs.fetchRemoteContexts property
hide_title: true
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

## ICreateVerifiablePresentationArgs.fetchRemoteContexts property

When dealing with JSON-LD you also MUST provide the proper contexts. Set this to `true` ONLY if you want the `@context` URLs to be fetched in case they are not preloaded. The context definitions SHOULD rather be provided at startup instead of being fetched.

Defaults to `false`

<b>Signature:</b>

```typescript
fetchRemoteContexts?: boolean;
```