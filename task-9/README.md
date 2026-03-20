# Task 9: Complex Responsive Layout (ShopNext)

## Objective
Design a sophisticated webpage layout that combines CSS Grid and Flexbox techniques.

## Requirements
1. Use **CSS Grid** to structure the main layout and **Flexbox** to handle the alignment and spacing of inner elements.
2. Utilize **HTML & CSS** as the core technologies.
3. Create **overlapping elements** (using `position` and `z-index`) and **dynamic reordering** based on viewport size.
4. Implement a **sticky header or sidebar** that remains visible as the user scrolls.

## Solution Implemented
This project is a premium, Shopify-style e-commerce landing page called **ShopNext**. It demonstrates advanced CSS layout techniques:

- **Structural Layout (CSS Grid)**: The main layout uses nested CSS Grids to define areas for the Hero section, Catalog banners, Sidebar filters, and the Product Showcase.
- **Component Alignment (Flexbox)**:
    - **Header**: Flexbox handles the distribution of the logo, navigation links, and action buttons.
    - **Dropdown**: The category menu uses a 2-column Flexbox grid with a stable hover transition.
    - **Product Cards**: Flexbox ensures that titles, prices, and buttons are perfectly aligned vertically.
- **Visual Depth (Overlapping)**: The hero section features overlapping layers where content is positioned over a grid-based background.
- **Interactivity (Sticky Elements)**:
    - The **Header** is pinned to the top for constant navigation access.
    - The **Sidebar** uses `position: sticky` to remain visible while browsing through the products.
- **Responsiveness (Dynamic Reordering)**: Using CSS Media Queries, the grid structure is dynamically reordered for mobile devices. For example, the sidebar filters move from the left column to the bottom of the page to prioritize product visibility.

## Setup Instructions
1. Clone or download this repository.
2. Ensure you have the `assets` folder containing the product images in the same directory as `index.html`.
3. Open `index.html` in any modern web browser (Chrome, Firefox, Edge, or Safari).
4. Scroll through the page to observe the sticky behaviors and hover effects.
5. Resize the browser window to see the dynamic reordering and responsive layout in action.

## Dependencies
- **Google Fonts**: [Inter](https://fonts.google.com/specimen/Inter) for clean, modern typography.
- **Vanilla CSS**: No external frameworks or libraries were used.
