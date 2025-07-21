# 📄 Landing Page Project

This is a basic landing page built using **HTML** and **CSS**. The purpose of this project is to demonstrate understanding of fundamental web development concepts, with a primary focus on using **Flexbox** to create responsive and organized layouts.

## 🚀 Project Overview

The landing page includes:
- A navigation bar with a logo and header links
- A prominent hero section with call-to-action
- An information section with boxes and descriptions
- A quote/testimonial section
- A final call-to-action section
- A footer

---

## 🛠 Technologies Used

- **HTML5**: For the structure and semantic layout of the page.
- **CSS3**: For styling, layout, and visual design.

---

## 📐 HTML Structure

The HTML file is structured with semantic elements:
- `<header>`: Contains the nav bar and hero content
- `<div>` sections: Used to group content like the info area, quote, CTA, etc.
- `<footer>`: Contains footer information

### Key HTML Elements:
- `ul` and `li`: For navigation links
- `div`: For layout containers
- `button`: For call-to-action interactions
- `p` and `a`: For text and links

---

## 🎨 CSS Features

### ✅ Basics
- `* { box-sizing: border-box; }` for consistent sizing
- `margin` and `padding` resets
- Font styling using system fonts

### ✅ Layout with Flexbox
- `display: flex` is used in nearly every major container:
  - `.nav-bar`: Space between logo and navigation links
  - `.header-contant`: Side-by-side layout for text and image
  - `.box-container`: Equal spacing for four information boxes
  - `.container-two`, `.container-three`: Center content vertically and horizontally
  - `.msgBox`: Space-between layout for text and button

### ✅ Background and Visuals
- Background color is applied to different sections (`header`, `.container-two`, `.container-three`)
- `.right` div in the hero section was prepared to hold a background image (just add `background-image`)
- Borders, rounded corners, and spacing used for visual separation

### ✅ Responsive Design Considerations
- Percent-based widths (e.g., `width: 70%`, `width: 50%`) are used for fluid resizing
- Flexbox enables flexible alignment without fixed positioning

---

## 🧪 How to Use

1. Clone the repository or download the files.
2. Ensure your image (e.g., `logo.png`) is placed correctly in the `images/` folder if you uncomment the background-image line.
3. Open `index.html` in any browser to view the landing page.

---

## 💡 Highlights

- Clean separation of structure (HTML) and style (CSS)
- Heavy usage of Flexbox to manage responsive layouts
- Consistent design language across sections
- Semantic HTML for better accessibility and maintainability

---

## 📚 What I Learned

Through this project, I solidified my understanding of:
- HTML layout principles
- CSS styling and best practices
- Flexbox as a layout model
- Creating structured, modular code for front-end development

---

## 📁 Folder Structure

project-root/
│
├── index.html
├── style.css
└── images/
        └── logo.png (optional)