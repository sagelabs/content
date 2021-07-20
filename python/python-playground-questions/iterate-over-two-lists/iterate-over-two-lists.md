---
author: Stefan-Stojanovic

tags:
  - coding

type: normal

category: coding

setupCode:
  startingPoint: |
    # 👋 Welcome to the Python coding playground. 
    # Lists to use:

    name = ['Stefan', 'Michael', 'Rebekah', "Natasha"]
    lastName = ['Stojanovic', 'Stevens', 'Mikaelson', "Romanoff"]

    # Type your code here:
  	  
---

# Iterate Over two Lists

---

## Content

> 👩‍💻 Your task is to write a program that:
> - **simultaneously iterates over two lists**
> - **prints a value from each list as a pair**

Example arrays:

```javascript
let names = ['Stefan', 'Michael', 'Rebekah', "Natasha"];
let lastNames = ['Stojanovic', 'Stevens', 'Mikaelson', "Romanoff"];
```

Example output:
```plain-text
Stefan Stojanovic
Michael Stevens
....
```

To achieve this, you can use the following concepts:
- flow control (`for...in`)
- built-in methods (`zip`)

Learning is best when we give it an honest try. Even if we make a mistake, we'll remember it and do better next time.

That being said, if you're not sure how to get started, check out this footnote[1]. 

When you're finished, feel free to share your solution with the community, join in on discussions, and upvote solutions from your fellow learners!

Remember, learning is more effective when we do it with others.

> 💡 Take a look at [how you can format text using markdown](https://www.enki.com/glossary/general/markdown-formatting).

> 💡 The guidelines above are just suggestions. Feel free to include other concepts in your solution as you see fit. The implementation is up to you.

> 🤓 Happy learning! Open the playground and start coding!

---

## Footnotes

[1: Hints]

You can use a `for...in` loop and the built-in `zip` method to go through both lists and output them pair by pair.
