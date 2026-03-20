# FAQ Section implemented with CSS Accordion

## Overview
A responsive and accessible Frequently Asked Questions (FAQ) page built using pure HTML/CSS. This project demonstrates how to create a functional accordion component without any JavaScript, using the "checkbox hack" for state management and smooth CSS transitions for animations.

## Objective
CSS Accordion Component
Objective: Build an accordion where content sections expand and
collapse on click.
Requirements:
Use the checkbox hack (a hidden checkbox input with a label) or
the 
:target
 pseudo-class to control the open/closed state of each
section.
Apply CSS transitions to animate the expansion and collapse of
content areas.
Allow multiple sections to be open simultaneously (if desired) or
restrict it to one open section at a time.

## Solution Implemented
- **Checkbox Hack Logic**: Utilized hidden `<input type="checkbox">` elements paired with `<label>` tags. This allows us to use the `:checked` pseudo-class to toggle styles on neighboring elements.
- **Pure CSS Transitions**: Used `max-height` transitions to animate the opening and closing of content sections, providing a smooth user experience.
- **Multiple Sections Support**: By using checkboxes instead of radio buttons, users can open multiple accordion items at once, which is ideal for FAQ pages.
- **Modern UI**: Styled with a clean, minimalist aesthetic featuring a subtle chevron icon that rotates dynamically and a focus on readable typography using the Inter font family.

## Requirements
- Each accordion section must expand/collapse on click.
- Animations must be applied to the expansion/collapse process.
- No JavaScript should be used for the core functionality.

## Setup Instructions
1. Navigate to the `task-8` directory on your local machine.
2. Open the `index.html` file in any modern web browser.
3. Ensure you have an active internet connection to load the "Inter" font from Google Fonts, or the browser will fall back to default system sans-serif fonts.

## Dependencies
- None (No external frameworks or libraries are required for this pure HTML/CSS implementation).
- Optional: Google Fonts (for the 'Inter' typeface).
