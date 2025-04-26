# Combining CSS Selectors - To-Do List Project

This project demonstrates the use of **combined CSS selectors** to style a simple HTML to-do list with nested elements.

## 📄 Project Overview
- Styled a basic to-do list structure using **multiple types of CSS selectors**:
  - Grouped selectors (`h1, h2`)
  - Child selectors (`.box > .done`)
  - Descendant selectors (`.box li`)
  - Class-specific selectors (`li.done`)
  - Combined element and class selectors (`ul p.done`).

## 🛠️ Technologies Used
- HTML5
- CSS3

## 🎯 Features
- Styled `<h1>` and `<h2>` headers to have a **blueviolet** color.
- Applied a **firebrick** color to paragraphs with class `.done` that are **direct children** of `.box`.
- Styled all list items inside `.box` to have a **blue** color.
- Overrode specific list items (`<li>`) with class `.done` to **seagreen** color.
- Reduced the font size (`0.5rem`) for `<p>` tags with `.done` class that are inside a `<ul>`.

## 📚 Learning Outcomes
- How to use **grouped selectors** to style multiple elements at once.
- How to use **child selectors** (`>`) vs **descendant selectors** (space ` `) properly.
- How to override styles for specific elements using **class-specific targeting**.
- How to combine tag names and classes for **more precise CSS control**.

---

> **Note:** The CSS rules carefully combine tag names, classes, and structural relationships 
