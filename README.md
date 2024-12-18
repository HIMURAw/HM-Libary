# CSS Library

## Installation

You can integrate this CSS library into your project by following one of these methods:

### Option 1: Using CDN
To use the library via CDN, simply add the following `<link>` tag to the `<head>` section of your HTML:

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/hm-css/dist/library.min.css">
```

This project is a customizable and modern CSS library designed to help web developers quickly and easily style their websites. It includes a variety of pre-designed components such as buttons, cards, backgrounds, animations, and more. The library is lightweight, easy to integrate, and customizable, making it a great tool for any web project.

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Customization](#customization)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

This CSS library offers a collection of essential styles for modern web development. Whether you're building a simple personal website or a complex web application, this library provides the necessary tools to create a visually appealing and responsive design with minimal effort. It supports various color schemes, button styles, card designs, background effects, and animations, all of which are easy to customize.

## Features

- **Predefined Color Palettes**: A variety of vibrant colors like pink, purple, blue, and orange are available.
- **Buttons**: Multiple button styles with hover effects, animations, and responsive designs.
- **Cards**: Flexible and customizable card layouts with hover effects and shadows.
- **Backgrounds**: Gradient backgrounds, solid color backgrounds, and image backgrounds.
- **Animations**: Smooth hover and transition effects for interactive elements like buttons and cards.
- **Responsiveness**: The library is designed to be mobile-friendly and adaptable to various screen sizes.
- **Easy Customization**: Variables for colors, sizes, and other properties are provided for easy adjustments.

# Grid System - col-md

This grid system is designed to provide responsive layouts using 12 columns. The `hm-col-md-` class is used for medium-sized devices, typically tablets or devices with a screen width of 768px and above.

## Features

- The `col-md-` class applies when the screen width is **768px** or larger.
- The grid is based on a **12-column** layout.
- You can specify the width of each column for medium-sized devices using classes like `hm-col-md-1`, `hm-col-md-2`, etc., where the number corresponds to the number of columns the element should span.

## Usage

### HTML Structure

To use the `hm-col-md-` class, simply add it to the column element inside a `.hm-row` container. This will apply the grid system for medium-sized devices.

```html
<div class="hm-container">
  <div class="hm-row">
    <div class="hm-col-md-4">Column 1</div>
    <div class="hm-col-md-4">Column 2</div>
    <div class="hm-col-md-4">Column 3</div>
  </div>
</div>

## Input Styles

This library includes a variety of customizable input styles to enhance the user experience. You can easily integrate these input designs into your forms to make them more visually appealing and interactive.

### Available Input Styles

1. **Basic Input**: A simple input field with a border and padding.
   ```html
   <input type="text" class="hm-input" placeholder="Enter text">
   <input type="text" class="hm-input-under" placeholder="Enter text">
   <input type="text" class="hm-input-gradient-border" placeholder="Enter text">