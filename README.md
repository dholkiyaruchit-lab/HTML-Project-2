# E-Grocery Super Market
<img width="1920" height="1727" alt="Grocery-Shop-12-03-2025_01_58_PM" src="https://github.com/user-attachments/assets/ad269282-3368-45b4-a783-254653d273e0" />


A simple responsive frontend for an e-grocery product listing page built with HTML and CSS. This project demonstrates a clean product grid, basic UI controls (search, sort, page size), and a modern card design suitable for a learning / portfolio assignment.

---

## Features

* Responsive product grid using flexbox.
* Product cards with image, category, name, rating (font-awesome stars), weight and price.
* Sort and page-size dropdowns and a basic search input (static - UI only).
* Neumorphism-inspired card styling.

---

## Project structure

```
E-Grocery/
├─ index.html         # Main HTML file
├─ style.css          # Styles for the page
├─ Assets/            # Images used for the products and logo
│  ├─ blinkit-logo.png
│  ├─ product-1.png
│  └─ ...
└─ README.md          # This file
```

---

## How to use

1. Clone or download the repository.
2. Open `index.html` in any modern browser (Chrome, Edge, Firefox).

Optional (for local development):

* Serve the folder with a simple static server (e.g., `npx http-server` or `python3 -m http.server`) to avoid any relative path issues.

---

## Suggestions / Next steps

* Make search, sort and pagination functional using JavaScript.
* Add a real cart system with localStorage to persist items.
* Replace static markup with data-driven rendering (e.g., JSON + JS or a small framework like React/Vue).
* Improve accessibility (ARIA attributes, keyboard focus states, semantic elements).
* Add responsive breakpoints for mobile/tablet.

---

## Styling notes

* Font Awesome v4.7 is used for star icons.
* The design uses soft shadows and rounded corners for a neumorphic look.

---

## Contributing

Feel free to open an issue or submit a pull request. For small fixes or feature additions:

1. Fork the repo
2. Create a branch `feature/your-change`
3. Commit and push
4. Open a PR describing your changes

---
