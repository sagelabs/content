---
author: catalin
type: normal
category: must-know
notes: 'https://insights.enki.com/#/contrib/others/55c83ba83f06ab320051aa8a?search=kha'
practiceQuestion:
  formats:
    - fill-in-the-gap
    - type-in-the-gap
  context: standalone
revisionQuestion:
  formats:
    - fill-in-the-gap
  context: standalone
---

# How Range Operations Work


---

## Content

A range can refer to an arbitrary, ordered sequence of values within a list-like container. The boundaries of a range are often represented by indexes.

Strings can be thought of as a list of characters. Hence, a substring is essentially a range in the original string. 
You can use the `substring()` method to extract a part of a string. The result will be returned **as a new value** while the original string isn't mutated. 

The syntax is:

```java
String.substring(
  int startIndex,
  int endIndex
);
```

Let's take a look at an example:

```java
"Enki".substring(0, 2);
```

The result will be `"En"`. This is because the method starts at the value of `startIndex`, includes everything in-between, but the value of `endIndex` **is excluded**.

There are many more methods that need specifying a range, and all of them use this rule.

```java
List<Integer> myList = new ArrayList<Integer>();
for (int i = 0; i <= 4; i++) {
  myList.add(i);
}
System.out.println(myList);
// [0, 1, 2, 3, 4]

List<Integer> newList = myList.subList(0, 3);
System.out.println(newList);
// [0, 1, 2]
```


---

## Practice

What would be the return value of the following method:

```java
"beautiful".substring(4, 6);
// ???
```

- `ti`
- `ut`
- `if`
- `be`
- `ul`

---

## Revision

When calling the following function:

```java
"test".substring(1,3)
```

The output will ??? the character with index 3.

- `exclude`
- `include`
