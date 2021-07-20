---
author: Stefan-Stojanovic

tags:
  - coding

type: normal

category: coding

setupCode:
  startingPoint: |
    // 👋 Welcome to the JavaScript coding playground.

    // These are the arrays:
    let oddNumbers = [101, 23, 11, 8, 3, 83, 1];
    let evenNumbers = [12, 0, 37, 91, 99, 44, 76];

    // Type your code here:

---

# Adding & Sorting Two Arrays

---

## Content

> 👩‍💻 Your task is to:
> - **create a program that takes two arrays of numbers as input**
> - **joins them together into one array**
> - **sort them in ascending or descending order**

Use these two arrays:
```javascript
let oddNumbers = [101, 23, 11, 37, 3, 83, 1];
let evenNumbers = [12, 0, 8, 92, 98, 44, 76];
```

To achieve this, you can use some of the following concepts:
- array functions (`concat`, `sort`, ...)
- flow control (`if (age > 30) ...`)

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

You can concatenate the two arrays into a third one and then sort them.

> 💡 The `sort` method by default compares values as strings. This means that `101` comes before `2`. To fix this, pass in your own comparison function that returns the difference between the given numbers. 

Don't forget to print the resulting array.
