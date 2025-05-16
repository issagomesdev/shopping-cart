# 🛒 Shopping Cart — Interactive Product Showcase

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)

![Preview](https://shopping-cart.byissa.tech/products/preview.png)

<p align="center">
  <a href="#about">About</a> •
  <a href="#features">Features</a> •
  <a href="#structure">Structure</a> •
  <a href="#technologies">Technologies</a> •
  <a href="#how_to_use">How to Use</a>
</p>

<h2 id="about">📌 About</h2>

**Shopping Cart** is a responsive and dynamic frontend-only shopping experience, created as part of a portfolio project. It allows users to interact with a product list, simulate a shopping experience, and view product galleries in an elegant modal layout.

This project demonstrates DOM manipulation, modular CSS, dynamic UI updates, and image gallery interaction — all without external libraries.

[![project](https://img.shields.io/badge/📱Visit_this_project-000?style=for-the-badge&logo=project)](https://shopping-cart.byissa.tech)

<h2 id="features">✨ Features</h2>

- 🛍 Add items to cart with quantity control (no duplication)
- ➕ Automatic quantity increase when re-adding an existing product
- 🧾 View product details with image gallery
- 🗑 Remove individual items or clear entire cart
- 🧮 See total price and number of items in cart
- 📱 Fully responsive layout for desktop and mobile

<h2 id="structure">📁 Structure</h2>

```txt
🛒 shopping-cart/
├─ ✂ index.html                # Main page
├─ ✂ style.css                 # Global styles
├─ ✂ script.js                 # Application logic
📂 products/                   # Products images and gallery
 ├─ ...                     
 └─ 📂 images/                 # Products gallery
    └─ ...                 
```

<h2 id="technologies">🧪 Technologies</h2>

- HTML5
- CSS3
- JavaScript

No dependencies. Everything runs in the browser.

<h2 id="how_to_use">🚀 How to Use</h2>

1. Open `index.html` in your browser to access the landing page.  
2. Click the 🛒 icon on a product to add it to the cart.  
3. Click the ℹ️ icon on a product to view more details and browse its image gallery.  
4. In the cart, update quantities, remove individual items, or clear all at once.  
5. The total price and item count update dynamically as you make changes.