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
    // Your birthday is in 131 days

    // Type your code here:

---

# Happy Birthday

---

## Content

> 👩‍💻 Your task is to create a program:
> - **using the `Date` object**
> - **it should check if the current date is your birthday**
> - **If it is, print a happy birthday message**
> - **If not, output how many days until your birthday**

To achieve this, you can use the following concepts:
- Date methods(`now()`, `year()`, `month()`,...)

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

You will need two dates; one for today and another for your birthday.

This is how to create a date for June 23rd, 1912: 

```javascript
let birthday = new Date(1912, 5, 23);
// We use `5` for June because months are 0-indexed. 
```

If you don't pass anything into `Date` you get today.

```javascript
let today = new Date();
```

Dates in JavaScript are calculated in milliseconds.

To check if two dates are the same day, subtract one from the other and check if the difference is under 24 * 60 * 60 * 1000 (the number of milliseconds in a day):

```javascript
const MS_IN_DAY = 24 * 60 * 60 * 1000;

function isSameDay(date1, date2) {
  // get the positive difference in milliseconds
  let msDiff = Math.abs(date1 - date2);

  return msDiff < MS_IN_DAY;
}
```
