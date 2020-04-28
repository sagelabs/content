---
author: kapnobatai136

type: normal

category: must-know

aspects:
  - introduction

links:
  - '(Try out the first example)[https://www.typescriptlang.org/play/index.html?ssl=1&ssc=1&pln=6&pc=1#code/PTAEBUE8AcFMGUDGAnAltALqAJrDtkBbVAO1gGdQMALWKmOgewDMAoEK20ANwEM1eAIwA2dEgFdCVRqEF1eoCYTnJ2YOYl7jydAO50A5qm51UWGmMkrQAVlaisS0AF5bAbnt5QjANYvFkqAAtKAAzG6gHCQyBMiMqp5Y5BjI-gDksCQ+qGkeDoqM0f7JqSHhaqCVVVUAenUVsfGysJraerBpyHTk4oIpvIgYpAagCiXDQA]{website}'
  - '(Type Inference)[https://en.wikipedia.org/wiki/Type_inference]{website}'

---

# Introduction to Types

---
## Content

A type in TypeScript is defined by its structure and the operations that can be performed on it.

For example, a `number` represents any numerical value and it can be subtracted but a `string` is a sequence of characters and it can't be subtracted.

> *Note*: Adding types is optional because any JavaScript code is also valid TypeScript. If you don't declare any types, TypeScript will figure them out for you.

```ts
// TypeScript determines the type of
// the variable num to be a number
// because we give it the number 5
let num = 5;
let ok = num - 3; // no error

let str = 'enki';
let nono = str - 3;
//         ^^^
// error because we're subtracting a string
```

TypeScript will try to guess as much of the type information as it can in order to provide safety without getting in the way[1].

---
## Practice

Will this code compile without errors?

```ts
let lesson = 'Remember, TS guesses the type';
let points = 10;
let result = points * lesson;
```

???

* B
* A

---
## Revision

Will this code compile without errors?

```ts
let points = '101';
let total = points + 2;
```

???

* No
* Yes


---
## Footnotes
[1: Type Inference]
The automatic detection of types is called *type inference*.

This means that all values in TypeScript have an implicit type if no type is declared.