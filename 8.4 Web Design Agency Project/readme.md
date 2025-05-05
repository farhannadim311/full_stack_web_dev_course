# Creative Agency Webpage

This project is a responsive landing page for a **Creative Design Agency**, built using HTML and CSS. It demonstrates layout design, image styling, text alignment, and mobile responsiveness without any JavaScript.


## 📄 Project Overview
- Header section with a **logo** and a bold **headline**.
- Two featured content cards:
  - **Beauty**: focuses on elegant, client-focused web design.
  - **Construction**: emphasizes professional, robust development using modern HTML/CSS.
- Clean and modern aesthetic using the **Poppins** Google Font.
- Fully **responsive layout** for mobile devices (≤ 680px width).

## 🛠️ Technologies Used
- HTML5
- CSS3
- Google Fonts

## 🎯 Features
- Float-based card layout with `left` and `right` alignment.
- Responsive design powered by a **media query** that:
  - Stacks `.card` elements vertically.
  - Adjusts `h1` font size and centers it on small screens.
  - Scales images fluidly using `object-fit: cover` and `width: 100%`.
- Flexbox used in `body` to ensure the footer stays pinned at the bottom.

## 💡 Learning Outcomes
- Apply **float** for side-by-side card layouts.
- Use `@media` queries for **responsive web design**.
- Combine **typography**, **spacing**, and **layout techniques** for clean UI.
- Understand the role of `flex-direction: column` and `flex: 1` in sticky footers.

## 📱 Responsive Breakpoint
| Viewport Width | Layout Behavior           |
|----------------|---------------------------|
| > 680px        | Cards float side-by-side  |
| ≤ 680px        | Cards stack vertically    |

## 🖼️ Assets
- Logo and images stored under `./assets/images/`.


> **Note:** This project avoids JavaScript to focus purely on **semantic HTML** and **modern CSS** for layout and styling.
