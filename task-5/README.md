# Task 5: Blog Page with CSS-Only Modals

## Overview
This task involved building a modern, interactive blog page featuring a CSS-only modal popup system. The primary goal was to demonstrate how state and interactivity can be achieved in a web application using pure HTML and CSS without any JavaScript.

## Objectives & Implementation
- **Modal Interaction**: Attained using the `:target` pseudo-class. Links point to specific modal IDs, and the CSS toggles visibility and triggers animations when an element's ID matches the URL hash.
- **Auto-Hiding Notification**: Implemented a **3-second toast notification** triggered by social links. This was accomplished using a CSS `@keyframes` animation on the `:target` element that automatically fades and slides away the message.
- **Premium Aesthetics**: Combined glassmorphism (backdrop blur) with a custom `cubic-bezier` transition for smooth, high-end reveal effects of the modals.
- **Responsive Layout**: Designed with a mobile-first philosophy using **CSS Grid (auto-fit)** and explicit media queries to ensure a seamless experience across desktop, tablet, and mobile devices.
- **Navigation Flow**: Integrated "About" and "Contact" sections with internal anchor linking and a fixed back-to-top "Home" button.

## Setup Instructions
1.  Navigate to the `task-5` directory.
2.  Open `index.html` in your favorite web browser.
3.  Click on any **"Read More →"** button to open a post's detailed modal.
4.  Dismiss the modal using the **"&times;"** button (which clears the target back to the navbar).
5.  Click any social link in the contact section to see the auto-disappearing toast notification.

## Dependencies & Resources
- **Fonts**: [Google Fonts - Outfit](https://fonts.google.com/specimen/Outfit) (loaded via CDN).
- **Frameworks**: None. This project is built entirely with **Vanilla HTML and CSS** to demonstrate mastery over pure stylesheets.
- **Icons**: Simple CSS-based icons and standard character entities.
