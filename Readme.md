# Sticky Sidebar

A simple implementation of a sticky sidebar using only HTML and CSS. This project demonstrates how to create a sidebar that stays fixed at the top of the page when scrolling, improving user experience for navigation or additional content.

## Features
- **Sticky Sidebar**: The sidebar remains visible and stays fixed at the top of the page while scrolling the main content area.
- **Responsive Layout**: The layout is created using Flexbox, which adapts to different screen sizes.

## Sticky Behavior (Minimal CSS)

To achieve the sticky behavior for the sidebar, you only need the following two lines of CSS:

```css
.sidebar {
    position: sticky;
    top: 0;
}
```

- `position: sticky;` makes the sidebar "stick" when you scroll past it.
- `top: 0;` ensures that the sidebar sticks at the top of the viewport when it reaches the top. (try giving it a value of 5%)

These are the only lines required to make the sidebar sticky. The rest of the styles are purely for aesthetics and layout.

## Code Explanation

### HTML Structure

- The layout consists of two main sections: `.main` (for the main content) and `.sidebar` (for the sticky sidebar).
- The `wrapper` class contains both sections, arranged horizontally using Flexbox.

### Aesthetic CSS Styling

The additional styles are used to improve the design and user experience but are not necessary for the sticky behavior itself.

- **Flexbox Layout**: The `.wrapper` class uses `display: flex` to arrange the `.main` and `.sidebar` side by side.
- **Container Styles**: Borders, padding, and background colors are applied to visually separate the sections and make the layout more modern.
- **Sidebar Styling**: The sidebar has a subtle shadow, rounded corners, and hover effects to enhance the visual appeal and interactivity.

## How to Use

1. Clone the repository or download the files.
2. Open `index.html` in your browser.
3. Scroll the page to see the sticky sidebar in action.

## License

This project is open-source and available under the MIT License.
