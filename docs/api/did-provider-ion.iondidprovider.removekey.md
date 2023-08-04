---
id: did-provider-ion.iondidprovider.removekey
title: IonDIDProvider.removeKey() method
hide_title: true
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

## IonDIDProvider.removeKey() method

Removes a key from a DID Document

**Signature:**

```typescript
removeKey({ identifier, kid, options }: {
        identifier: IIdentifier;
        kid: string;
        options?: IUpdateOpts;
    }, context: IContext): Promise<any>;
```

## Parameters

| Parameter                    | Type                                                                                            | Description |
| ---------------------------- | ----------------------------------------------------------------------------------------------- | ----------- |
| { identifier, kid, options } | { identifier: [IIdentifier](./core-types.iidentifier.md); kid: string; options?: IUpdateOpts; } |             |
| context                      | IContext                                                                                        |             |

**Returns:**

Promise&lt;any&gt;

identifier provider specific response. Can be txHash, etc,