---
author: kapnobatai136

category: must-know

aspects:
  - introduction

type: normal

---

# Benefits of Filters

---
## Content

When working with simple zaps, you might not even need to include filters in your flow. As the size of the zaps increase, and the size of the data you are working with (e.g. production database), the necessity of filters will become apparent.

Let's take another look at a filter step:

![filter-setup-and-testing](https://img.enkipro.com/25eaef765da3856792a1ae9f92ddfea3.png)

Notice the `+AND` and `+OR` buttons in the bottom left corner. What these do is add another constraint (the one we have now says that the `'Has Access?'` column must contain the `'Yes'` value), and depending on the type:
- `+AND` - both constrains must pass **at the same time**
- `+OR` - **at least one** of the constraints must pass

You can already see how very complicated logic can be created, which is bound to make your work more efficient.