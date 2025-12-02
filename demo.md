---
marp: true
theme: default
paginate: true
background-color: #f0f0f0
font-size: 1.2em
title: "Custom Styled Presentation"
transition: slide
style: |
  section {
    background-color: #f7f7f7;
    font-family: 'Arial', sans-serif;
  }
  h1 {
    color: #3498db;
    font-size: 3em;
  }
  h2 {
    color: #2ecc71;
    font-size: 2.5em;
  }
  p {
    color: #333;
    font-size: 1.2em;
  }

---

<!-- Slide 1 -->
# Product Documentation

Welcome to the product documentation presentation for our software!

---

<!-- Slide 2 -->
## Your Email

For any questions, feel free to reach out to us at:

**23f3000795@ds.study.iitm.ac.in**

---

<!-- Slide 3 -->
## Custom Theme and Styling

In this slide, we will demonstrate custom theme and styling for Marp.

### Example Custom Styling

```css
section {
  font-family: "Arial", sans-serif;
  color: #333;
}

h1 {
  color: #2c3e50;
}

h2 {
  color: #34495e;
}
```
---

<!-- Slide 5 -->
## Algorithmic Complexity
Here is an example of an algorithmic complexity:
$$
O(n \log n) 
$$

This means the time complexity of the algorithm grows at a rate of $n \log n$.

---

<!-- Slide 6 -->

![bg](images/bg_img.jpg)

---


### Explanation of Marp Directives Used:
1. **`marp: true`**: Tells Marp to treat this as a slide deck.
2. **`theme: default`**: Specifies the default theme for the presentation. You can replace this with other built-in themes like `gaia`, `uncover`, or create your own custom theme.
3. **`paginate: true`**: Enables pagination, so each slide will have a page number.
