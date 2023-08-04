---
id: did-provider-jwk.jwkdidprovider.updateidentifier
title: JwkDIDProvider.updateIdentifier() method
hide_title: true
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

## JwkDIDProvider.updateIdentifier() method

> This API is provided as a preview for developers and may change based on feedback that we receive. Do not use this API in a production environment.

**Signature:**

```typescript
updateIdentifier(args: {
        did: string;
        kms?: string;
        alias?: string;
        options?: any;
    }, context: IAgentContext<IKeyManager>): Promise<IIdentifier>;
```

## Parameters

| Parameter | Type                                                                                             | Description |
| --------- | ------------------------------------------------------------------------------------------------ | ----------- |
| args      | { did: string; kms?: string; alias?: string; options?: any; }                                    |             |
| context   | [IAgentContext](./core-types.iagentcontext.md)&lt;[IKeyManager](./core-types.ikeymanager.md)&gt; |             |

**Returns:**

Promise&lt;[IIdentifier](./core-types.iidentifier.md)&gt;