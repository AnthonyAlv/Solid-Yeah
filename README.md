# Simple-Utils

Tiny TypeScript utility library with:
- `capitalize` — capitalize a string's first letter  
- `Maybe<T>` — a small convenience type  
- `orElse` — return fallback if value is null/undefined  

## Usage

```ts
import { capitalize, orElse } from "simple-utils";

console.log(capitalize("hello")); // "Hello"
console.log(orElse(null, 42)); // 42
