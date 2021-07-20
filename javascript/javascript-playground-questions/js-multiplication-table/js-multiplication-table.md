---
author: Stefan-Stojanovic

tags:
  - coding

type: normal

category: coding

setupCode:
  startingPoint: |
    // 👋 Welcome to the JavaScript coding playground.

    // Example output: 
    // 1   2   3   4   5
    // 2   4   6   8  10
    // 3   6   9  12  15 
    // 4   8  12  16  20
    // 5  10  15  20  25

    // Type your code here:

---

# Multiplication Table

---

## Content

> 👩‍💻 Your task is to create a program that:
> - **takes a number between 1 and 10 as input**
> - **outputs a multiplication table for that number**

If the input is `5`, the output should look similar to this:
```javascript
1, 2, 3, 4, 5
2, 4, 6, 8, 10
3, 6, 9, 12, 15
4, 8, 12, 16, 20
5, 10, 15, 20, 25
```

To achieve this, you can use the following concepts:
- variable creation (`age = 25`)
- built-in (`range()`)
- flow control (`for...of`)

As a bonus, print the table with equal spacing between each number, like this:

```javascript
1       2       3       4       5
2       4       6       8       10
3       6       9       12      15
4       8       12      16      20
5       10      15      20      25
```

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

Use two loops to print the table. Both loops cycle from 1 to the given number.

The outer loop prints each row and the inner loop builds the row string.

Here's a pseudocode example:

```plain-text
for i = 1 to 5
  row = ''
  for j = 1 to 5
    row += (i * j) + ' ' // add a space after each cell
  print(row + '\n')
```
