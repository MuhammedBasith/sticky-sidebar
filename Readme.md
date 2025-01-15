# Sticky Sidebar

A simple implementation of a sticky sidebar using only HTML and CSS. This project demonstrates how to create a sidebar that stays fixed at the top of the page when scrolling, providing a better user experience for navigation or additional content.

## Features
- **Sticky Sidebar**: The sidebar remains visible and stays in a fixed position while scrolling the main content area.
- **Responsive Layout**: The layout is created using Flexbox, which adapts to different screen sizes.

## Code Explanation

### HTML Structure

- The layout consists of two main sections: `.main` (for the main content) and `.sidebar` (for the sticky sidebar).
- The `wrapper` class contains both sections, arranged horizontally using Flexbox.

### CSS Styling

- **Flexbox Layout**: The `.wrapper` class uses `display: flex` to arrange the `.main` and `.sidebar` side by side.
- **Sticky Positioning**: The `.sidebar` uses `position: sticky` with `top: 0` to make it stick to the top of the viewport as the user scrolls down.
- **Styling**: Borders and padding are added to both `.main` and `.sidebar` to make them visually distinct, and a background color is applied to the body for contrast.

## How to Use

1. Clone the repository or download the files.
2. Open `index.html` in your browser.
3. Scroll the page to see the sticky sidebar in action.

## License

This project is open-source and available under the MIT License.
