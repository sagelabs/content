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
    # The character z appears only 2 times

    # Type your code here:
      
---

# Least Frequent Character

---

## Content

> 👩‍💻 Your task is to write a program that:
> - **takes a string as input**
> - **determines which characters appear the least**
> - **print the least occurring character along with its number of occurrences**

To achieve this, you can use the following concepts:
- flow control (`for...in`, `if (age > 1)...`)
- variable creation (`age = 33`)

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

Use a loop to cycle through every character and save it in an empty dictionary. 

Within the loop you can check if the character already exists, if it does, increase its count and if it doesn't, add it.

Here's one example of a dictionary:
```python
{
  a: 5,
  b: 3,
  # ...
}
```

After the loop is made, output the least occurring value from the dictionary.

Here's one way you can get the least occurring character from a dictionary: 

```python
min(dict, key = dict.get))
```
