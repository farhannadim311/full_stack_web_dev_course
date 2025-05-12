# Flexbox Pricing Table

This project is a clean and responsive **pricing table layout** built using **HTML and CSS Flexbox**. It displays three pricing tiers (Basic, Standard, Premium), and adapts to different screen sizes using media queries.

## 💡 Project Overview

- Displays three side-by-side pricing plans:
  - **Basic**
  - **Standard**
  - **Premium**
- Uses Flexbox to distribute the cards evenly across the page.
- Includes responsive layout behavior for smaller screens (≤1250px), stacking plans vertically.

## 🛠️ Technologies Used

- HTML5
- CSS3 (Flexbox + Media Queries)
- Google Fonts (`Sono`)

## 🎯 Features

| Plan     | Storage  | Users | Support               |
|----------|----------|-------|------------------------|
| Basic    | 10GB     | 1     | 🚫 No Support          |
| Standard | 50GB     | 5     | ✅ Phone & Email       |
| Premium  | 100GB    | 10    | ✅ 24/7 Full Support    |

- Each plan has:
  - A **title**, **price**, **feature list**, and a **call-to-action button**.
  - Rounded cards (`border-radius: 5px`) and clean text alignment.
  - Colored button (`#ff6600`) with white text.

## 📱 Responsive Behavior

- On large screens:
  - Pricing plans are arranged in a horizontal row.
- On small screens (max-width: 1250px):
  - The layout switches to a vertical stack for better readability and mobile accessibility.

## 📚 Learning Outcomes

- Use of **Flexbox layout** (`display: flex`, `justify-content`, `align-items`, `gap`, `flex: 1`).
- Creating **equal-width flexible cards** using `max-width` and `flex` properties.
- Writing **media queries** for responsive design.
- Styling call-to-action buttons and feature lists cleanly.

---

