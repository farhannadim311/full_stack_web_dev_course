# CSS Grid Placement Project

This project demonstrates advanced use of **CSS Grid** for layout positioning and **Flexbox** for centering content inside grid items. Emoji-based content blocks (🤠, 👨‍🚀, 📖) are positioned creatively across a responsive grid.

## 📄 Project Overview

- A 3-column, 2-row grid using fractional units.
- Grid items include:
  - 🤠 Cowboy: spans **2 columns** on the first row.
  - 👨‍🚀 Astronaut: placed in **second row**, spanning **2 columns**.
  - 📖 Book: spans **both rows vertically** using `grid-row: span 2`.

Each item is also centered within its grid cell using **Flexbox**.

## 🛠️ Technologies Used

- HTML5
- CSS3 (Grid Layout + Flexbox)

## 🧱 Layout Details

| Emoji     | Class       | Grid Placement                        | Color     |
|-----------|-------------|----------------------------------------|-----------|
| 🤠 Cowboy | `.cowboy`   | `grid-column: span 2` (1st row)        | `#00B9FF` |
| 👨‍🚀 Astro | `.astronaut`| `grid-area: 2 / 1 / 3 / 3` (row 2, span 2 cols) | `#03989E` |
| 📖 Book   | `.book`     | `grid-row: span 2` (entire right col)  | `#E58331` |

The grid is responsive thanks to `1fr 1fr 1.5fr` columns and a `3rem` gap for spacing.

## ✨ Styling Highlights

- `.item` class uses:
  - `display: flex`
  - `align-items: center`
  - `justify-content: center`
  - To center emojis in both axes.
- All sections have large `font-size: 5rem` emojis and unique background colors.
- Layout fills the entire viewport (`height: 100vh`).

## 📚 Learning Outcomes

- Understand how to use:
  - `grid-column`, `grid-row`, and `grid-area` for exact grid placement.
  - `display: flex` inside grid items for centering content.
  - Combined use of **Grid** for layout and **Flexbox** for alignment.
- Practice creating **visually balanced** and **semantic** component arrangements.

---

> **Tip:** Try resizing your screen or swapping emoji content to make the layout more interactive or thematic (e.g., with real content blocks instead of emoji).
