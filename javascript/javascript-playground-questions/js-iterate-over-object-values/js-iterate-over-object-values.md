---
author: Stefan-Stojanovic

tags:
  - coding

type: normal

category: coding

setupCode:
  startingPoint: |
    // 👋 Welcome to the JavaScript coding playground.

    let person = {
      name: 'Alan',
      surname: 'Turing',
      education: 'Sherborne School',
      country: 'England'
    };

    // Type your code here:
    
---

# Iterate over Object Values

---

## Content
  
> 👩‍💻 Your task is to write a program that: 
> - **iterates over each element of an object**
> - **outputs each of them to the console**

Example object to iterate:

```javascript
let person = {
  name: 'Alan', 
  surname: 'Turing', 
  education: 'Sherborne School', 
  country: 'England'
};
```

To achieve this, you can use the following concepts:
- variable creation `person = { name:'Alan', age:...}`
- flow control (`for...of`)
- Object global methods(`keys()`, `entries()`, ...)

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

Create the object and use a loop to go through each key-value pair.

Example:
```javascript
for (let [x, y] of Object.entries(obj)) {
  // ...
}
```
