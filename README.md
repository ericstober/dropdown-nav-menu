# Dropdown Navigation Menu

A lightweight and customizable dropwdown navigation menu built with HTML, CSS, and JavaScript. Perfect for integrating into modern web projects with ease and flexibility.

## Features

- **Responsive Design**: Adjusts seamlessly to various screen size and devices.
- **Customizable**: Easy to modify styles and behavior to suit your project needs.
- **Lightweight**: Minimal code for maximum performance.
- **Keyboard Accessible**: Supports keyboard navigation for enhanced usability.
- **Cross-Browser Compatibility**: Works on all modern browsers.

## Installation

1. Clone the repository:

```bash
   git clone https://github.com/ericstober/dropdown-nav-menu.git
   cd dropdown-nav-menu
```

2. Open the index.html file in your browser to view the menu.

## Usage

### HTML Structure

```html
<nav class="dropdown-nav">
  <ul>
    <li><a href="#">Home</a></li>
    <li>
      <a href="#">Services</a>
      <ul class="dropdown">
        <li><a href="#">Web Development</a></li>
        <li><a href="#">SEO</a></li>
        <li><a href="#">Content Writing</a></li>
      </ul>
    </li>
    <li><a href="#">About</a></li>
    <li><a href="#">Contact</a></li>
  </ul>
</nav>
```

### CSS

Include the provided `styles.css` file or use it as a reference to style your menu.

### JavaScript

The `script.js` file includes basic functionality for toggling the dropdown menus. Customize it as needed.

## Customization

### Styling

- Update the styles.css file to change colors, fonts, and spacing.

### Behavior

- Modify the script.js file to adjust dropdown behavior (e.g., hover vs. click).
