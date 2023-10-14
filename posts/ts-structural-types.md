---
category: TypeScript
created: '2023-09-05'
description: Structural Types in TypeScript
title: Structural Types
---
- Tuple
- Enum
- Any
- Union
- Literal
- FUnction
- Void
Literal Types
```typescript
// type alias
type Price = 45 | 55 | 65

const properties : {
	price: Price
} = {
	price: 45
}
```