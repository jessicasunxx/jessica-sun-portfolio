# Jessica Sun Portfolio

A static HTML/CSS portfolio website documenting creative embedded systems projects.

## Technical Overview

This is a static website built with vanilla HTML and CSS. No build tools, frameworks, or JavaScript are required.

## Project Structure

```
jessica-sun-portfolio/
├── index.html              # Home page
├── styles.css              # Global stylesheet
├── projects/
│   ├── 01-soldering-sculpture/
│   │   ├── index.html      # Project page
│   │   └── images/         # Project images
│   ├── 02-pcb-pendant/
│   │   ├── index.html      # Project page
│   │   └── images/         # Project images
│   └── 03-generative-art/
│       ├── index.html      # Project page
│       └── images/         # Project images and documentation
└── README.md
```

## Features

- **Responsive Design**: Mobile-friendly layout with CSS Grid and Flexbox
- **Navigation**: Home button on project pages for easy navigation back to the main portfolio
- **Clean Architecture**: Semantic HTML5 with organized CSS
- **No Dependencies**: Pure HTML/CSS, no external libraries or build process

## Styling

- **Color Scheme**: Dark blue gradient header (#0f172a to #1e293b) with light grey content area (#f9fafb)
- **Typography**: System font stack (SF Pro Text, Segoe UI, system-ui)
- **Layout**: CSS Grid for project cards, responsive breakpoint at 720px
- **Components**: Reusable button styles, project cards, and image grids

## Viewing Locally

1. Clone the repository
2. Open `index.html` in a web browser
3. No server required - works with `file://` protocol

## Deployment

Currently deployed on GitHub Pages at: `jessicasunxx.github.io/jessica-sun-portfolio`

## Browser Support

Works in all modern browsers that support:
- CSS Grid
- CSS Flexbox
- CSS Custom Properties (for future enhancements)

## File Organization

- **Root level**: Main portfolio page and global styles
- **Projects subdirectory**: Each project has its own folder with `index.html` and `images/` subfolder
- **Relative paths**: Project pages use `../../styles.css` to reference the root stylesheet
