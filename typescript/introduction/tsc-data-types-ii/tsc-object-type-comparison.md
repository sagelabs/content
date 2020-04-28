---
author: kapnobatai136

type: normal

category: must-know

aspects:
  - introduction

---

# `Object` vs `object` vs `{}`

---
## Content

TypeScript has 3 ways to represent an object with slightly different behaviors.

Since any defined value in JavaScript is an object[1], the `Object` type can be used to represent any type that is considered to contain a value:

```ts
let num: Object = 3;
let str: Object = 'enki';
let arr: Object = [1, 2, 3];
// ...
// only null and undefined give an error
let n: Object = null; // error
let u: Object = undefined; // error
```

This often leads to confusion. Usually by "object" we only mean collections of values (e.g. maps, sets, arrays, plain objects), but not primitive values[2] (e.g. numbers or strings).

This is why it is recommended to use the `object` type:

```ts
let arr: object = [1, 2, 3];
let obj: object = { enki: true };
let map: object = new Map([["enki", "cool"]])
// ...
// primitive values give an error
let str: object = 'enki'; // error
let num: object = 3; // error
let n: object = null; // error
let u: object = undefined; // error
```

The type `{}` is used to represent a JavaScript object with a specific shape.

```ts
let empty: {} = {};

const Enki: {
  job: string,
  isFun: boolean,
} = { job: "teach", isFun: true };
```

Assigning values that aren't part of the shape will cause errors:

```ts
empty.name = 'oops'; // Property 'name' does not exist on type '{}'
Enki.age = 5; // Property 'age' does not exist on type '{ job: string; isFun: boolean; }'
```

---
## Practice

Which statement will throw an error?

```ts
const a: Object = { enki: 'fun' };

const b: object = { enki: 'fun' };

const c: { enki: string } = { enki: 'fun' };
```

???

* None of them
* b
* a
* c

---
## Revision

Which statement will throw an error?

```ts
const a: Object = 5;

const b: object = 5;

const c: object = { enki: true };

const d: Object = { enki: true };
```

???

* b
* a
* c
* d

---
## Footnotes

[1:Objects]

All values besides `null` and `undefined` are a form of object in JavaScript. A quick test to verify if something is an object is to try and access a property on it and see if it errors.

```js
// use anything as x
x = 'anything'
// if this throws, then
// its not an object
(x).enki
```

For example, these values are all objects:

```js
(3).enki // undefined
('enki').enki // undefined
({ enki: 1 }).enki // 1
```

Only these throw an error:

```js
(undefined).enki // Uncaught TypeError: Cannot read property 'property' of undefined
(null).enki // Uncaught TypeError: Cannot read property 'property' of null
```

[2:Primitive Values]
The following types are considered to be primitive:
- `number`
- `string`
- `boolean`
- `bigint`
- `symbol`
- `null`
- `undefined`