---
author: Stefan-Stojanovic

tags:
  - coding

type: normal

category: coding

setupCode:
  startingPoint: |
    # 👋 Welcome to the Python coding playground. 
    # Here is the list:
    
    numbers = [1, 3, 5, 7, 9, 10, 8, 6, 4, 2]

    # Type your code here:


---

# Beginning and End Pairs

---

## Content

> 👩‍💻 Your task is to write a program that will take a numbered list and:
> **print the first and last, second and second to last, and so on**

Example list:
```python
numbers = [1, 3, 5, 7, 9, 10, 8, 6, 4, 2]
```

The output should look like this:
```python
[1, 2]
[3, 4]
[5, 6]
[7, 8]
[9, 10]
```

To achieve this, you can use the following concepts:
- flow control (`while..`)

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

You only need to loop through half of the list.

To get the values in each loop cycle, take the loop counter index from the left and right sides of the list.

For eample, the third element from left and right of `newList` is:

Which looks like this:
```python
newList = [lst[3], lst[-(3+1)]]
```
