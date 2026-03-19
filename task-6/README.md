# Tabbed Content Interface

## Objective
Create an interactive, tabbed interface where clicking on a tab reveals specific content sections without using JavaScript.

## Requirements
- **Input Toggles**: Utilize radio buttons or checkboxes (hidden from view) along with labels to serve as tabs.
- **State Management**: Use the `:checked` pseudo-class to display the corresponding content while hiding others.
- **Smooth Animations**: Incorporate smooth transitions when switching between different tabs.

## Attainment
This interface was achieved using the **"Radio Button Hack"** for state logic:
1.  **Hidden Inputs**: Radio buttons are placed at the top level of the container but are hidden from view (`display: none`).
2.  **Labels as Tabs**: Clicking on a `<label>` associated with an input's ID triggers that radio button's `checked` state.
3.  **Sliding Content**: Using the `~` (general sibling) selector, CSS detects which radio is checked and applies a `transform: translateX()` to a wrapper div. This creates a polished horizontal sliding effect between the "Log In" and "Sign Up" forms.
4.  **Animated Highlight**: A background "pill" slider was created using the same sibling logic to highlight the currently active tab.

## Setup Instructions
1.  Navigate to the `task-6` directory.
2.  Open `index.html` in any modern web browser.
3.  Click on the "Log In" or "Sign Up" tabs to witness the smooth horizontal sliding transition between forms.

## Dependencies & Resources
- **Fonts**: [Google Fonts - Outfit](https://fonts.google.com/specimen/Outfit) (loaded via CDN).
- **Styling**: Vanilla CSS (no external libraries like Bootstrap or Tailwind required).
- **Frameworks**: None. This project is built entirely with pure HTML and CSS.
