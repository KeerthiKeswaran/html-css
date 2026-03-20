# CodeHive | Pure CSS Multi-Page Simulator

A high-performance, developer-focused blog portal built using **advanced CSS modern techniques**. This project demonstrates the power of CSS by simulating a multi-page application experience without a single line of JavaScript.

## Objective
Create a fully functional, multi-section website that simulates the experience of navigating between different pages—all without any JavaScript.

## Solution Overview
The solution leverages the native power of the browser's URL fragment mapping and modern CSS pseudo-selectors to manage application state.

### Key Implementation Details:
*   **State Management via `:target`**: The core "page switching" logic is built using the `:target` pseudo-class. Navigation links point to content IDs (e.g., `#dsa`), which the CSS then uses to toggle visibility.
*   **Default Visibility with `:has()`**: To solve the classic CSS-only problem of showing a "Home" page by default, the project uses the modern `:has()` selector to detect if any sub-section is active and hide the landing page automatically.
*   **Pure CSS Carousel**: The home page features a fully interactive image-less carousel using radio button inputs and label mapping to drive horizontal translations.
*   **Premium Transitions**: All navigation events trigger a 0.4s fade-and-slide animation to mimic the feel of a modern single-page application (SPA).
*   **Asset-Free Design**: To ensure lightning-fast load times and clean aesthetics, the design uses carefully curated CSS linear gradients instead of external image assets.

## Requirements
*   **Navigation Logic**: Use the `:target` pseudo-class to display and hide different "pages" or sections of content.
*   **Animation**: Incorporate CSS animations and transitions to simulate page transitions (such as fading or sliding effects).
*   **Accessibility**: Design an accessible navigation menu that works across different devices and screen sizes.
*   **Modern CSS**: Ensure that the entire experience is responsive and leverages advanced CSS techniques (e.g., combining Flexbox, Grid, and pseudo-classes) to manage layout and state transitions.

## Setup Instructions
This is a standard HTML/CSS project and requires no compilation or local server to run.

1.  **Clone or Download** the project folder.
2.  Locate the folder containing `index.html` and `style.css`.
3.  **Open `index.html`** in any modern web browser (Chrome, Firefox, Safari, or Edge).

## Dependencies
This project has **Zero Dependencies**. 
*   No JavaScript required.
*   No external libraries (Tailwind, React, etc.) required.
*   No image assets required (All visuals are CSS-generated).
*   **Note**: Uses Google Fonts (Inter and Roboto) for premium typography.
