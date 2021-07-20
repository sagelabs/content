---
author: Stefan-Stojanovic

tags:
  - coding

type: normal

category: coding

setupCode:
  startingPoint: |
    // 👋 Welcome to the JavaScript coding playground. 
    // You can use these:
    
    let string1 = "Was it a car or a cat I saw"
    let string2 = "Hey how are you"
    
    // Type your code here:

---

# Is it a Palindrome?

---

## Content

> 👩‍💻 Your task is to create a function that:
> - **takes a string as input**
> - **checks if the string is a palindrome**
> - **test a palindrome and a non-palindrome string to confirm it works**

Example `string`s to test:
```javascript
let string1 = "Was it a car or a cat I saw"
let string2 = "Hey how are you"
```

To achieve this, you can use the following concepts:
- string methods (`.split()`)
- control flow (`if x > 1`, `for`)
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

Your loop only needs to go up to half the `string` and check if the first character equals the last, second character equals second to last, and so on.
