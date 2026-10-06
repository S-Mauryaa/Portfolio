# Saurabh Portfolio

A personal portfolio website for Saurabh, built as a dark, immersive single-page experience with animated visuals and a premium editorial aesthetic. The site is intentionally lightweight and dependency-light, making it easy to run locally or adapt for personal use.

## Overview

This project presents:

- A bold hero section with strong portfolio branding
- Animated background visuals and motion-driven effects
- Structured sections for portfolio content and identity
- A static HTML/CSS/JS setup with no complex build pipeline

## Project Structure

```text
.
├── main.html              # Main portfolio page and all page logic/styles
├── package.json           # Dependency manifest
├── package-lock.json      # Lockfile for npm dependencies
├── portrait.png           # Portrait image asset
├── image.png              # Supporting site asset
├── secret-pathways-assets/# Fonts and generated visual assets
└── README.md              # Project documentation
```

## Tech Stack

- HTML5
- CSS3
- JavaScript
- npm dependency: `@designcodeio/threeui`

## Run the Project Locally

Because this is a static front-end project, you can preview it without a build step.

### Option 1: Open directly

Open `main.html` in a browser.

### Option 2: Serve it locally

From the project root, run:

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000/main.html
```

## Notes

- No framework or bundler is required for local viewing.
- Most design and content are embedded directly in `main.html`.
- The visual style and layout are easy to customize by editing the HTML and CSS inside that file.

## Customization

To personalize the portfolio:

1. Update the page title and metadata in `main.html`
2. Replace images in the project root or asset folders
3. Edit the text content and sections in the HTML body
4. Adjust colors, spacing, and motion in the CSS variables and style block

## Author

Saurabh
