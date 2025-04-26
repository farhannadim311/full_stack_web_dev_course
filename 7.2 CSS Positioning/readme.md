# CSS Positioning Exercise

This project demonstrates the use of **relative** and **absolute** positioning in CSS to place elements precisely on a webpage.

## 📄 Project Overview
- Created a large **blue box** (`.blue-box`) positioned **relatively** to the page.
- Placed a smaller **red circle** (`.red-circle`) **absolutely** inside the blue box.
- Used pixel-based offsets (`top`, `left`) to control exact placement.

## 🛠️ Technologies Used
- HTML5
- CSS3

## 🎯 Features
- `.blue-box`:
  - **500px** wide, **300px** tall.
  - Background color: **blue**.
  - Positioned **relative** to the page with an offset of `200px` from the top and left.
- `.red-circle`:
  - **200px x 200px** circle (using `border-radius: 50%`).
  - Background color: **red**.
  - Positioned **absolute** inside `.blue-box` with a `top: 150px` and `left: 250px` offset.

## 📚 Learning Outcomes
- Understand the difference between **relative** and **absolute** positioning.
- How a **relative** parent affects the positioning context of a **child** with `position: absolute`.
- How to use `top` and `left` CSS properties to control element location precisely.
- How to create circular shapes using `border-radius: 50%`.

---

> **Note:** Absolute positioning calculates from the nearest parent with `position: relative`. Here, the `.blue-box` acts as the positioning context for the `.red-circle`.
