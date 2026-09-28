# Digitize Ideas --- HTML & CSS Website

A modern, visually focused website concept built from scratch using
**HTML5 and CSS3**. The project focuses on recreating a bold
creative-agency style landing page with large typography, bright colors,
flexible layouts, and image-based visual elements.

## Project Overview

**Digitize Ideas** is a front-end design practice project created to
explore:

-   Modern landing-page layouts
-   Large, expressive typography
-   CSS Flexbox layouts
-   Responsive spacing and sizing
-   Custom Google Fonts
-   Image backgrounds
-   Buttons and visual UI elements
-   Clean HTML structure
-   CSS-based styling without a JavaScript framework

The current version is primarily a **UI/design implementation** using
HTML and CSS.

## Technologies Used

-   **HTML5** --- Page structure and semantic markup
-   **CSS3** --- Layout, typography, colors, spacing, and visual styling
-   **Google Fonts** --- Custom typography
-   **Unsplash** --- Background imagery used in the visual section

## Project Structure

``` text
Digitize-Ideas/
│
├── index.html
├── style.css
└── README.md
```

> The exact filenames may vary depending on the local project setup.

## Main Sections

### Navigation

The navigation contains links such as:

-   About Us
-   Project
-   Services
-   Let's Talk

The navigation is built using CSS Flexbox for horizontal alignment and
spacing.

### Hero Section

The hero section is the main visual area of the website and contains:

-   Decorative two-dot element
-   Large **"Digitize Ideas"** heading
-   Image-based video-style element
-   Play button
-   Supporting description text

The layout uses Flexbox to position the heading and supporting content
side by side.

## Design Approach

The design uses a bright lime-green background with dark typography and
subtle green text accents.

Example colors:

``` css
background-color: #d5ff40;
color: #0e1403;
color: #39520d;
```

The project also uses large typography and rounded elements to create a
contemporary creative-agency aesthetic.

## Typography

The project uses **Raleway** as the primary font family.

Example:

``` css
* {
    font-family: 'Raleway', sans-serif;
}
```

Google Fonts can be loaded in the HTML `<head>` using the Google Fonts
stylesheet.

## CSS Techniques Used

### Flexbox

Flexbox is used for navigation and hero layouts:

``` css
display: flex;
justify-content: space-between;
align-items: center;
```

The right side of the hero section also uses:

``` css
display: flex;
flex-direction: column;
justify-content: space-between;
```

This allows the video element and description text to automatically
occupy the available vertical space.

### Responsive Typography

Large headings can use viewport-based units such as:

``` css
font-size: 13vw;
```

This allows the typography to scale with the browser viewport rather
than relying only on a fixed pixel value.

### Background Images

The visual/video-style element uses an image as a CSS background:

``` css
background-image: url('IMAGE_URL');
background-size: cover;
background-position: center;
```

## Getting Started

### 1. Clone or download the project

Download the project files to your computer.

### 2. Open the project

Open the project folder in a code editor such as **Visual Studio Code**.

### 3. Run the website

Open `index.html` in a browser.

For development, using the **Live Server** extension in Visual Studio
Code is recommended.

## Future Improvements

Possible improvements for future versions include:

-   Fully responsive mobile and tablet layouts
-   Additional website sections
-   Working navigation links
-   Real HTML5 video integration
-   Hover animations
-   CSS transitions and micro-interactions
-   Scroll-based animations
-   Accessibility improvements
-   SEO metadata
-   JavaScript interactions
-   Optimized local image assets

## Learning Goals

This project is being developed as a practical front-end design exercise
to improve understanding of:

1.  HTML page structure
2.  CSS Flexbox
3.  Typography and font management
4.  Responsive sizing
5.  Spacing and alignment
6.  Background images
7.  Component-like CSS organization
8.  Translating a visual reference into a working webpage

## Status

**Status:** In Development

The current project focuses on the visual design and front-end
implementation using HTML and CSS. Interactive functionality and
additional sections can be added as development continues.

## Author

**Tejas Dhadve**

UI/UX & Graphic Designer

------------------------------------------------------------------------

### License

This project is a personal learning/design project. Images, fonts, and
other third-party assets remain the property of their respective owners
and are used according to their applicable licenses.
