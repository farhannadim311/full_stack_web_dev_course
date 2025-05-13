# Chessboard Layout Using CSS Grid

This project recreates an 8x8 chessboard using **pure HTML and CSS**, leveraging **CSS Grid** for layout and custom colors for squares.

## ♟️ Project Overview

- The chessboard is structured using a `.container` div with a **CSS Grid** of 8 columns and 8 rows.
- Each square is a `div` with either the `.white` or `.black` class.
- The alternating pattern is hard-coded using HTML for demonstration purposes.

## 🛠️ Technologies Used

- HTML5
- CSS3 (Grid Layout)

## 🎯 Features

- **Container**:
  - `display: grid`
  - `grid-template-columns: repeat(8, 1fr)`
  - `grid-template-rows: repeat(8, 1fr)`
  - Fixed size: **800px x 800px** (100px per square)

- **Square Styling**:
  - Each square is exactly `100px x 100px`.
  - `.white`: `#f0d9b5` (light wood tone)
  - `.black`: `#b58863` (dark wood tone)

## ✅ Learning Outcomes

- How to use **CSS Grid** to define a structured 2D layout.
- Manually alternating `.white` and `.black` divs to simulate a chessboard pattern.
- Understanding the use of `fr` units and fixed dimensions in a grid system.
- Applying custom color schemes for a realistic board appearance.

## 📌 Limitations

- The color pattern is hard-coded. For scalability and automation, consider generating the grid dynamically using JavaScript or a server-side language.
