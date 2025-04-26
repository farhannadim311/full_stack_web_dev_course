# CSS Cascade Practice

This project demonstrates the behavior of **CSS Cascade** and **specificity** in a nested box layout.

## 📄 Project Overview
- Built a structure of nested `div` elements (`outer-box`, `box`, and `inner-box`).
- Applied different background colors and text colors to showcase how CSS rules cascade and which styles apply based on specificity and order.
- Linked an external `style.css` to the HTML.

## 🛠️ Technologies Used
- HTML5
- CSS3

## 🎯 Features
- `#outer-box` has a **purple** background color due to ID selector (`#outer-box`).
- `.box` elements have a **blue** background unless overridden.
- `.inner-box` elements override `.box` background to **red** (more specific due to additional class).
- Paragraphs (`<p>`) inside `.inner-box` with class `.white-text` are **white**.
- Paragraphs without `.white-text` class are **yellow** by default.
- Demonstrates **cascade order**, **specificity**, and **inheritance** principles.

## 📚 Learning Outcomes
- How ID selectors (`#id`) override class selectors (`.class`) due to higher specificity.
- How multiple classes on an element affect the final styling.
- How nested elements inherit or override styles based on the cascade.
- Importance of CSS ordering and specificity in determining final visual outcomes.

---

> **Note:** The `.white-text` class directly overrides the paragraph color to ensure readability over the red background of `.inner-box`.
