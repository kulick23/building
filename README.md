# Building Landing Page

A modern, responsive real-estate landing page built with plain HTML, CSS, and vanilla JavaScript.

## Overview
This project showcases a clean promotional website for a residential development brand. The page is designed to be fast, lightweight, and easy to deploy on GitHub Pages.

## Highlights
- Modern responsive layout (desktop, tablet, mobile)
- Sticky header with scroll effect
- Mobile navigation menu (burger toggle)
- Hero section with clear call-to-action
- Image gallery slider with previous/next controls
- Contact form with basic client-side validation
- Clean visual style with custom typography and gradients

## Tech Stack
- HTML5
- CSS3 (custom properties + media queries)
- Vanilla JavaScript (no frameworks)

## Project Structure
```text
.
├── index.html
├── styles/
│   └── style.css
└── assets/
    ├── icons/
    └── images/
```

## Run Locally
Because this is a static project, you can run it with any local server.

### Option 1: VS Code Live Server
1. Open the project in VS Code.
2. Start Live Server from `index.html`.
3. Open the generated local URL in your browser.

### Option 2: Python HTTP Server
```bash
cd /path/to/building
python3 -m http.server 5500
```
Then open: `http://127.0.0.1:5500`

## Deploy to GitHub Pages
1. Push your repository to GitHub.
2. Open `Settings` -> `Pages`.
3. In **Build and deployment**:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/ (root)`
4. Save and wait for deployment.

Your site URL will be:
`https://<your-username>.github.io/<repository-name>/`

## Notes
- Main entry point: `index.html`
- All assets use relative paths, so GitHub Pages works out of the box.
- If styles do not update after deploy, do a hard refresh in the browser.
