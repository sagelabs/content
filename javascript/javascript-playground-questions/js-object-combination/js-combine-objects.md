---
author: Stefan-Stojanovic

tags:
  - coding

type: normal

category: coding

setupCode:
  startingPoint: |
    // 👋 Welcome to the JavaScript coding playground.
    
    // Type your code here:
    let o1 = { }
    let o2 = { }
    
---

# Combine Objects

---

## Content

> 👩‍💻 Your task is to create a function that:
> - **takes two objects as input**
> - **combines them**
> - **returns a single object**

To achieve this, you can use the following concepts:
- variable creation (`age = 33`).
- function declaration (`function something(x) { ... }`)

Learning is best when we give it an honest try. Even if we make a mistake, we'll remember it and do better next time.

That being said, if you're not sure how to get started, check out this footnote[1]. 

When you're finished, feel free to share your solution with the community, join in on discussions and upvote solutions from your fellow learners!

Remember, learning is more effective when we do it with others.

> 💡 Take a look at [how you can format text using markdown](https://www.enki.com/glossary/general/markdown-formatting).

> 💡 The guidelines above are just suggestions. Feel free to include other concepts in your solution as you see fit. The implementation is up to you.

> 🤓 Happy learning! Open the playground and start coding!


---

## Footnotes

[1: Hints]

Start by defining your function with your choice of name. It should take two objects as input.

Inside the function, you can add one object to another using `Object.assign()` or object spread operator `...`.

Here's one way:

```javascript
let o1 = { name: 'enki' };
let o2 = { isFun: true };
let combined = { ...o1, ...o2 };
```

Outside of the function create the two objects.

Call your function with the two objects inside a `console.log` statement.
