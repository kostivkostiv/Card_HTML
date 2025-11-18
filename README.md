# Coffee Catalog — HTML & CSS Project

## Project Overview

ДЗ #1: Створення базової HTML-структури магазину кави

Це проста практика для виконання домашнього завдання, у якій я створив стилізовану картку товару за допомогою чистого HTML та інлайн-стилів.  
Мета роботи - потренувати навички верстки, роботи з семантичними тегами `<article>` та `<section>`, використання зображень та базової типографії.

## Screenshot

![Screenshot](./public/screenshot1.png)


**Homework #2:** Creating a Product Catalog with Semantic HTML5 Structure

This project is a practice exercise to build a coffee product catalog using **HTML5 semantic tags** and CSS for layout and styling.  
The main goals of this assignment were:

- Implement a **grid layout** of coffee products using `<ul>` and `<li>` elements.
- Create a **search form** with filters (price, sorting).
- Apply **semantic HTML5 tags** (`<main>`, `<section>`, `<article>`, `<aside>`) for better structure and accessibility.
- Use images and typographic styles to make the catalog visually appealing.

---

## Project Structure

HTML/
└─ src/
├─ index.html # Main HTML file
├─ styles.css # CSS styling

└─ public/
  └─ coffee.png # Sample product image


---

## Features

### Sidebar Search Form (`<aside>`)

- Search input field for keyword filtering.
- Price filter dropdown (`<select>`).
- Sort by dropdown (`<select>`).
- All form controls are styled for usability and clarity.

### Product Grid (`<section class="products">`)

- Products displayed in a **grid layout** using CSS Grid.
- Each product is an `<article>` inside an `<li>` item.
- Each product card includes:
  - Image of the coffee product (`<img>`).
  - Product name (`<h6>`).
  - Short description (`<p>`).
  - Price (`<p>`).

### Semantic Structure

- `<main>` contains the primary content.
- `<aside>` for search/filter controls.
- `<section>` wraps the products list.
- `<article>` for each individual product card.

---

## Screenshot

![Screenshot](image.png)

---

## Technologies Used

- HTML5
- CSS3
- Semantic elements (`<main>`, `<section>`, `<article>`, `<aside>`)
- CSS Grid for responsive product layout

---

## How to Use

1. Clone the repository or download the files.
2. Open `index.html` in a browser.
3. Use the search form on the sidebar to filter or sort products.
4. Enjoy the clean, semantic layout and product catalog display.

---

## Notes

- All CSS is written in a separate `styles.css` file.
- Images are placed in the `public` folder.
- Focused on **semantic HTML** and basic layout styling.
