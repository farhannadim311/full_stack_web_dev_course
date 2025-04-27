# CSS Float Practice - Cat and Dog Layout

This project demonstrates the use of **CSS float** and **clear** properties to control element positioning and create a two-column responsive layout with wrapped text and a clear footer.

## 📄 Project Overview
- Created two main sections:
  - A **cat** section floated to the **left**.
  - A **dog** section floated to the **right**.
- Added images inside each section and allowed paragraph text to **wrap around** the images.
- Ensured the footer appears **below** both sections using the `clear: both` property.

## 🛠️ Technologies Used
- HTML5
- CSS3

## 🎯 Features
- `.cat`:
  - Floated **left**.
  - Aquamarine background color.
  - Contains a cat image (`cat.jpeg`) floated left inside the div.
  - Paragraph wraps around the image.
- `.dog`:
  - Floated **right**.
  - Coral background color.
  - Contains a dog image (`dog.jpeg`) floated left inside the div.
  - Paragraph wraps around the image.
- `footer`:
  - Centered text.
  - Blueviolet background.
  - Uses `clear: both` to move below both floated sections.
- Both `.cat` and `.dog` divs are **inline-block** with **40% width**.

## 📚 Learning Outcomes
- How to float elements to create multi-column layouts.
- How to wrap text around floated images.
- Importance of `clear: both` to prevent layout overlap.
- How combining `float`, `display: inline-block`, and `clear` can build flexible web page structures.

---

> **Note:** Floats are powerful for layout, but modern designs often prefer Flexbox or CSS Grid for more flexibility and fewer quirks!
