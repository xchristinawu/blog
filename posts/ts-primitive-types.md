---
category: TypeScript
created: '2023-09-05'
description: Primitive Types in TypeScript
title: Primitive Types
---
Primitive types are:
- not objects
- have no methods or properties
- are immutable

This does not mean that a variable assigned a primitive value can not be reassigned to a new value. It means that the existing value can not be altered in the way that objects and arrays can be. There are no methods or utilities provided to mutate primitive values.

TypeScript recognizes seven primitive types:
- bigint
- boolean
- null
- number
- string
- symbol
- undefined

```typescript
// the variable animal is declared to be type string
let animal: string;

// animal is allowed to be assigned and reassigned string values
animal = "panda";
animal = "hippo";
```


