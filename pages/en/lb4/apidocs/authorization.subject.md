---
lang: en
title: 'API docs: authorization.subject'
keywords: LoopBack 4.0, LoopBack 4
sidebar: lb4_sidebar
permalink: /doc/en/lb4/apidocs.authorization.subject.html
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@loopback/authorization](./authorization.md) &gt; [Subject](./authorization.subject.md)

## Subject interface

`Subject` represents both security state and operations for a single application user.

Such operations include: - authentication (login) - authorization (access control) - session access - logout

<b>Signature:</b>

```typescript
export interface Subject 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [principals](./authorization.subject.principals.md) | <code>Principal[]</code> |  |
|  [roles](./authorization.subject.roles.md) | <code>Role[]</code> |  |
|  [scopes](./authorization.subject.scopes.md) | <code>string[]</code> |  |

