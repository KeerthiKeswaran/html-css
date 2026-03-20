# Task 7: Pure CSS Marvel Character Carousel

## Objective
Develop a high-performance, visually engaging image carousel using only **Pure CSS** (no JavaScript). The carousel must support both automatic cycling and manual navigation while being fully responsive.

## Project Overview
This project showcases a deck of Marvel characters with a premium user interface. It utilizes advanced CSS techniques to handle complex state management and animations.

### Key Features:
- **Auto-Cycle Animation**: Uses `@keyframes` to automatically transition between 9 Marvel characters.
- **Manual Navigation**: Implements hidden radio buttons and the `:checked` pseudo-class for precise manual control via arrows and navigation dots.
- **Dynamic Background**: A background layer that automatically syncs its blurred, low-opacity image with the current active slide.
- **Premium Themes**: Features a Marvel-inspired color palette (#ed1d24, Black, and White) with smooth scaling and grayscale hover transitions.
- **Semantic Structure**: Built with accessibility in mind using `<main>`, `<section>`, `<figure>`, and `<figcaption>`.

## Requirements Fulfilled
-  **CSS Animations**: Implemented `@keyframes autoCycle` for the sliding effect.
-  **Manual Selection**: Used `:checked` with radio buttons to toggle between slides and override the animation.
-  **Visual Engagement**: Added high-resolution image support, blurred background sync, and custom navigation arrows.
-  **Responsiveness**: Utilized `clamp()` and media queries to ensure the carousel fits perfectly on various screen sizes.

## Dependencies
- **Assets**: 9 character images (Iron Man, Captain America, Thor, Hulk, Black Widow, Hawkeye, Captain Marvel, Nebula, Thanos) located in the `/assets` folder.
- **Browser**: Modern web browser with support for CSS Flexbox, Grid, and Animations.

## Setup Instructions
1.  **Clone/Download** the project folder.
2.  Ensure the directory structure is as follows:
    ```text
    /task-7
    ├── index.html
    ├── style.css
    └── assets/
        └── (character images)
    ```
3.  Open `index.html` in any modern web browser to view the carousel.

## Technical Highlights
- **Arrow Logic**: Arrows are positioned outside the main container using an absolute wrapper. Only the arrows corresponding to the current state are displayed using `:checked` sibling combinators.
- **Transition Control**: The `autoCycle` animation is automatically disabled when a manual radio button is selected, ensuring the user's choice is respected.
- **Image Fitting**: Images are set to `object-fit: cover` with `object-position: top` to handle portrait aspect ratios (1688x2500) within the card frame.
