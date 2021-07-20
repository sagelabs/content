---
author: Stefan-Stojanovic

tags:
  - coding

type: normal

category: coding

setupCode:
  startingPoint: |
    # 👋 Welcome to the Python coding playground. 
    # Example output:
    # 5! is equal to 120

    # Type your code here:
      
---

# Factorial Calculator

---

## Content

> 👩‍💻 Your task is to write a program that:
> - **takes a number as input**
> - **outputs its factorial value**

> A factorial of the number 5, written as `5!`, would be calculated as 5 x 4 x 3 x 2 x 1.


Example output:

```plain-text
5! is equal to 120
```

For the sake of learning, try not to use the built-in `math` modules' `factorial()` method.

To achieve this, you can use the following concepts:
- variable creation (`age = 18...`)
- flow control (`for...in`)

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

Start by creating two variables, for example, `number` and `result`.

One will store the inputted number, and the other will start from 1 and store the final number.

With a `for...in` loop, you can range from the first to the last number.

Inside the loop, multiply the `result` by each number in the loop.

Example print:
```python
print ("The factorial of {0} is {1} ".format(number,factorial))
```
Output:
```plain-text
The factorial of 5 is 120 
```
