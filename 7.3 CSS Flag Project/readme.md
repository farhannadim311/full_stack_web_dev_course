# CSS Flag Project - Flag of Laos

This project recreates the **Flag of Laos** using pure HTML and CSS, focusing on combining selectors, positioning, and styling without altering the original HTML structure.

## 📄 Project Overview
- Built a 900px by 600px flag layout with precise layering.
- Created a red background with a centered horizontal blue stripe and a white circle in the middle.
- Placed custom text ("The Flag" and "of Laos") inside different parts of the layout using only CSS styling.

## 🛠️ Technologies Used
- HTML5
- CSS3

## 🎯 Features
- `.flag`:
  - 900px wide, 600px tall.
  - Background color: **#CE1126** (red).
  - Contains a nested `<div>` representing the blue middle stripe.
- `.flag > div`:
  - 300px tall blue stripe (`#002868`), positioned vertically centered using `top: 150px`.
- `.flag > div > div`:
  - 200px by 200px **white circle** created using `border-radius: 50%`, centered inside the blue stripe.
- Typography:
  - Main heading (`The Flag`) styled in **white** and large font size (`5rem`).
  - Inner text (`of Laos`) inside the white circle styled in **black**.
- Carefully combined and nested selectors to control styling without adding extra classes or IDs.

## 📚 Learning Outcomes
- How to structure a multi-layered design using only HTML and CSS.
- How to combine parent-child selectors effectively (`>`) to target nested elements.
- Using **relative** and **absolute positioning** to precisely place elements.
- Managing **CSS specificity** to override inherited styles correctly.
- Building complex layouts with minimal HTML and clean CSS.

---

> **Note:** No extra classes, IDs, or elements were added — only selector combinations and CSS properties were used, following the project's constraints.
