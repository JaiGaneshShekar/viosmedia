# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a static website project for ViosMedia, a digital transformation and consulting company. The project contains a simple HTML/CSS website with no build process or dependencies.

## Project Structure

```
viosmedia/
├── Website/
│   ├── index.html          # Main HTML file for the ViosMedia website
│   ├── style.css           # CSS styles with custom properties and responsive design
│   └── viosMedia.jpg       # Company image asset
└── CLAUDE.md              # This file
```

## Architecture

- **Static Website**: Pure HTML/CSS implementation without frameworks
- **CSS Variables**: Uses CSS custom properties for consistent theming (primary-blue, secondary-dark, accent-white, light-gray)
- **Responsive Design**: Mobile-first approach with media queries for screens under 890px
- **Component Structure**: Organized as semantic HTML sections (hero, highlights, about, services, testimonials, values, careers, footer)

## Development Commands

Since this is a static website with no build process, development is straightforward:

- **Local Development**: Open `Website/index.html` directly in a browser or serve via a simple HTTP server
- **No build commands**: No package.json, webpack, or other build tools
- **No testing framework**: Pure static HTML/CSS with no test suite
- **No linting tools**: No ESLint, Prettier, or other code quality tools configured

## Key Design Patterns

- **CSS Architecture**: Organized with root variables, component-based styles, and responsive breakpoints
- **Color System**: Consistent use of CSS custom properties for brand colors
- **Layout**: Flexbox-based layouts with container max-width of 1200px
- **Typography**: Poppins font family as primary typeface
- **Interactive Elements**: Hover effects and transitions on buttons and navigation

## Missing Assets

The website references several image files in an `images/` directory that don't currently exist:
- `images/viosmedia-logo.png`
- `images/icon-facebook.png`
- `images/icon-linkedin.png` 
- `images/icon-twitter.png`