# Laundry Services - Responsive & Interactive Landing Page

A complete, modern, and highly interactive landing page for a laundry application. This project demonstrates advanced CSS techniques, including responsive design without frameworks, CSS-only state management, and custom keyframe animations.

## 📝 Project Overview

This project was built progressively through multiple phases to transform a static desktop layout into a fully responsive, engaging user experience. The core focus was to utilize pure CSS to handle layouts, mobile navigation logic, and animations without relying on JavaScript or external libraries like Bootstrap.

## ✨ Key Features Implemented

### 1. Fully Responsive Layout (Flexbox & Media Queries)
- Utilized `display: flex` and `flex-direction` to seamlessly rearrange the Hero section and Navbar across Desktop, Tablet (`<= 1024px`), and Mobile (`<= 768px`) breakpoints.
- Dynamically scales typography and image sizes to maintain visual balance on smaller screens.

### 2. CSS-Only Mobile Hamburger Menu
- Implemented a functional sliding mobile drawer menu strictly using HTML and CSS.
- Uses the `:focus` pseudo-class on a hidden button and the general sibling combinator (`~`) to trigger the menu's visibility on tap/click. 

### 3. Interactive CTA Button (Micro-interactions)
- Added smooth transition effects to the "Book a service today!" button.
- On hover, the button scales up (`scale(1.05)`) and tilts slightly (`rotate(-3deg)`) to encourage user interaction.

### 4. Dynamic Hero Image Animation
- Brought the 3D washing machine illustration to life using a custom CSS `@keyframes` animation (`orbitSqueeze`).
- The image continuously floats in a smooth orbit path (`translate`) while gently stretching and compressing (`scale`) to create a playful, bouncy effect.

## 🛠️ Technologies Used

- **HTML5:** Semantic structuring and sibling grouping for CSS-only logic.
- **CSS3:** - Advanced Flexbox mechanics
  - Media Queries for responsive design
  - Advanced selectors (`~`) and pseudo-classes (`:focus`, `:hover`)
  - CSS Transitions and `@keyframes` Animations

## 📂 File Structure

```text
📁 laundry-services-app
 ├── 📄 index.html          # Main HTML structure
 ├── 📄 style.css           # Contains all layout, responsive, and animation rule
 └── 📄 README.md           # Project documentation