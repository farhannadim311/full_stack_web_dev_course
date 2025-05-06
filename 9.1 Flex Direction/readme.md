# Flex Direction - Vertical Rainbow Stack

This project demonstrates how to use **CSS Flexbox** with `flex-direction: column` to vertically stack elements with equal height. It also uses **universal selectors** and **direct child combinators** to style the layout.

## 📄 Project Overview
- A `.container` holds seven colored boxes, each representing a color of the rainbow.
- The container uses:
  - `display: inline-flex`
  - `flex-direction: column`
  - `border: 5px solid gold`
- Each child `div` inside `.container` is styled with a unique background color and fixed height using `flex-basis`.

## 🛠️ Technologies Used
- HTML5
- CSS3 (Flexbox & Selectors)

## 🎯 Features
- `.container`:
  - Acts as a **vertical flex container** (`flex-direction: column`).
  - Each color box stacks top-to-bottom.
  - Width auto-adjusts (due to `inline-flex`), and content height is fixed at `100px`.
- Child elements:
  - Targeted using the **direct child selector** (`.container > div`).
  - Each `div` uses `flex-basis: 100px` for consistent sizing.
  - Styled with a full range of rainbow colors.

## 🎨 Colors Used
| Class     | Color Code   | Name     |
|-----------|--------------|----------|
| `.red`    | `#eb4d4b`     | Red      |
| `.orange` | `#f0932b`     | Orange   |
| `.yellow` | `#f6e58d`     | Yellow   |
| `.green`  | `#6ab04c`     | Green    |
| `.blue`   | `#4834d4`     | Blue     |
| `.indigo` | `#30336b`     | Indigo   |
| `.purple` | `#be2edd`     | Purple   |

## 📚 Learning Outcomes
- Understand how `flex-direction: column` stacks elements vertically.
- Use `flex-basis` to control individual child height.
- Use **combinator selectors** like `>` to target direct children in CSS.
- Practice using **semantic class names** for styling based on content.

---

> **Hint:** To make the stack horizontal instead, simply change `flex-direction: column` to `row`!
