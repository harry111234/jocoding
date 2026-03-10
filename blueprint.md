# Blueprint: Lotto Number Generator

## Overview

This application is a simple, user-friendly lottery number generator. It provides a clean, interactive interface for users to generate random lottery numbers. The design is modern, visually appealing, and responsive, ensuring a great experience on both desktop and mobile devices. Now with Dark/Light mode support.

## Project Outline

### Initial Version

*   **HTML Structure (`index.html`):**
    *   A main container for the application.
    *   A title heading.
    *   A button to trigger the number generation.
    *   A container to display the generated lottery balls.
*   **Styling (`style.css`):**
    *   **Layout:** Centered layout for the application.
    *   **Typography:** Clear and readable fonts.
    *   **Color Scheme:** A vibrant and engaging color palette.
    *   **Lottery Balls:** Styled circles to represent the lottery balls, each with a distinct color based on the number range.
    *   **Button:** A styled button with hover and active states.
    *   **Responsive Design:** Media queries to ensure the layout adapts to different screen sizes.
*   **JavaScript Logic (`main.js`):**
    *   An event listener on the "Generate" button.
    *   A function to generate an array of 6 unique random numbers between 1 and 45.
    *   A function to create and display the lottery ball elements in the UI.
    *   A function to assign colors to the balls based on their number.

### Version 1.1: Dark Mode Support

*   **Theme Toggle:** Added a button to switch between Dark and Light modes.
*   **CSS Variables:** Introduced CSS variables for consistent theme management.
*   **Persistence:** Theme preference is saved in `localStorage` to persist across page reloads.

## Current Plan

- [x] Create the basic HTML structure for the lottery number generator.
- [x] Implement the JavaScript logic to generate and display the numbers.
- [x] Apply modern and responsive CSS to style the application.
- [x] Add Dark/Light mode theme toggle.
