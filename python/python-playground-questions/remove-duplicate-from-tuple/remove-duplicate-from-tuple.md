---
author: Stefan-Stojanovic

tags:
  - coding

type: normal

category: coding

setupCode:
  startingPoint: |
    # 👋 Welcome to the Python coding playground. 
    # Tuple in question:

    myTuple = (
      "Stefan", "Mark", "Joane",
      "Steven", "Natasha", "Mark", 
      "Steven", "Mark", "Natasha"
    )

    # Type your code here:
    
    
---

# Remove Duplicate Values From a Tuple

---

## Content

> 👩‍💻 Your task is to define a function that:
> - **takes a tuple as input**
> - **removes the duplicate values**
> - **returns the new tuple**

Example tuple to use:
```python
myTuple = (
  "Stefan", "Mark", "Joane", 
  "Steven", "Natasha", "Mark", 
  "Steven", "Mark", "Natasha"
)
```

To achieve this, you can use the following concepts:
- function definition (`def something(x):`)
- flow control (`if(x > 1)`, `for...in...:`)

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

Start by defining and naming your function.

Ex:
```python
def duplicateRemoval(t):
```

You can convert the `tuple` to a `list`, use the `.count()` `list` method to see which value appears two or more times, then remove the duplicates using `.remove()`.

Don't forget to convert the `list` back to a `tuple` before returning it.