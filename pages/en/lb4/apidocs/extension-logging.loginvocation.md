---
lang: en
title: 'API docs: extension-logging.loginvocation'
keywords: LoopBack 4.0, LoopBack 4
sidebar: lb4_sidebar
editurl: https://github.com/strongloop/loopback-next/tree/master/extensions/logging
permalink: /doc/en/lb4/apidocs.extension-logging.loginvocation.html
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@loopback/extension-logging](./extension-logging.md) &gt; [logInvocation](./extension-logging.loginvocation.md)

## logInvocation() function

 decorator for method invocations.

<b>Signature:</b>

```typescript
export declare function logInvocation(): (target: any, method?: string | undefined, methodDescriptor?: TypedPropertyDescriptor<any> | undefined) => any;
```
<b>Returns:</b>

`(target: any, method?: string | undefined, methodDescriptor?: TypedPropertyDescriptor<any> | undefined) => any`

## Example


```ts
import {logInvocation} from '@loopback/extension-logging';

export class HelloController {
  @logInvocation()
  hello(name: string) {
    return `Hello, ${name}`;
  }
}

```

