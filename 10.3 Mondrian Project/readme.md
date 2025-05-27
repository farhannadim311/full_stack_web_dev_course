# Mondrian Project 🎨

This project is a **CSS Grid-based recreation** of a famous abstract painting by artist **Piet Mondrian**. It features precise layout control using modern CSS properties and showcases an artistic composition entirely with code.

## 🧱 Project Overview

- Uses **CSS Grid** to divide the canvas into rectangular regions with varying background colors and spans.
- The canvas dimensions are **748px x 748px** with a `9px` gap simulating thick black lines.
- No images or SVGs — this Mondrian-style artwork is entirely built with HTML and CSS.

## 🛠️ Technologies Used

- HTML5
- CSS3 (Grid Layout)

## 🎨 Color Palette

| Color Name | Hex Code   |
|------------|------------|
| White      | `#F0F1EC`  |
| Red        | `#E72F24`  |
| Black Line | `#000000`  |
| Dark Black | `#232629`  |
| Blue       | `#004592`  |
| Yellow     | `#F9D01E`  |

## 📐 Layout Details

- `.container`: Main grid container
  - `grid-template-columns: 320px 198px 153px 50px`
  - `grid-template-rows: 414px 130px 155px 22px`
  - `gap: 9px` to simulate line separation

- Special placements:
  - `.white1`: spans 3 columns (`grid-column: span 3`)
  - `.white2`: spans 2 rows
  - `.white3`: `grid-area: 2 / 2 / 4 / 4` — custom positioned region
  - `.white4`: spans 2 rows
  - `.blue`: includes an extra `border-bottom` to simulate thicker separation

## 🧠 Learning Outcomes

- Master `grid-template-columns` and `grid-template-rows` to create structured canvas-like layouts
- Use `grid-area`, `grid-column`, and `grid-row` to position elements with precision
- Apply background colors, borders, and spacing to simulate line art
- Practice visually aligning layout purely through **code-based design**

---

> **Tip:** This project is a great CSS exercise in combining artistic thinking with code. Try tweaking dimensions or colors to create your own Mondrian-style layouts!
