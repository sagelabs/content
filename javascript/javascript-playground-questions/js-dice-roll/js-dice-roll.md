---
author: Stefan-Stojanovic

tags:
  - coding

type: normal

category: coding

setupCode:
  startingPoint: |
    // 👋 Welcome to the JavaScript coding playground.
    
    import Math.random;
    // Type your code here:

---

# Dice Roll

---

## Content

> 👩‍💻 Your task is to:
> - **use the Math.random module**
> - **create a function that operates like a dice roll**
> - **every time you execute it, you should get a number between 1 and 6.**

To achieve this, you can use the following concepts:
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

`Math.random` returns a number between 0 and 1.

To make that number be between 1 and 6, we can use the following logic:

```js
let result = Math.floor(Math.random() * 6) + 1;
```
