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
    # The first N primes are:
    # 2, 3, 5, 7, 11, 13, ...

    # Type your code here:

---

# Prime Printer

---

## Content

> 👩‍💻 Your task is to create a program that:
> - **outputs the first 15 prime numbers**

> A prime number is a number that is only divisible by 1 and itself.

The first 15 primes fall in the range `2`-`50`. Some of them are 2, 3, 5, 7, 11, 13, and so on.

2 is only divisible by 1 and itself, making it prime. 4 is not prime because it is divisible by 1, 2, and itself.

To achieve this, you can use some of the following concepts:
- loops (`for...in...`)
- built-in function (`range()`)
- flow control (`if (age > 30) ...`)

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

Create a `for x in...` loop that will range from 2 to 50. 

Then use a conditional statement to check if a number is larger than 1 (all primes are). 

Inside the conditional use a second loop in the range of 2 to `x`.

If `x` divided by the second loop variable is equal to 0 break out of the loop, otherwise output the prime.
