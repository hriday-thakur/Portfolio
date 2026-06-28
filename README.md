# Hriday Thakur — Portfolio

A personal portfolio website built from scratch with vanilla HTML, CSS, and JavaScript — no frameworks, no build step. Designed in a brutalist style with scroll-driven animations, an interactive resume viewer, and a creative work gallery.

**Live site:** https://hriday-thakur.github.io/Portfolio/

## Features

- Scroll-driven hero animation — name scales and merges into the page on scroll
- Sticky navigation bar that reveals after the intro animation completes
- Sections for Skills, Projects, Leadership Experience, Education, Certificates, Achievements, and Creative Work
- Creative Work section with category previews that open into a lightbox-style gallery
- In-browser resume viewer (PDF preview + download) via a modal
- Fully responsive — adapts layout and typography for mobile, tablet, and desktop
- Custom favicon, Open Graph, and Twitter Card metadata for link previews

## Tech Stack

- HTML5, CSS3 (custom properties, CSS Grid/Flexbox, no frameworks)
- Vanilla JavaScript (IntersectionObserver for scroll reveals, no libraries)
- No build tools — just static files

## Project Structure

```
Portfolio/
├── index.html
├── favicon.png
├── apple-touch-icon.png
├── og-image.png
└── assets/
    ├── resume/
    │   └── resume.pdf
    ├── personal/
    │   ├── profile_photo.jpg
    │   └── intro_photo.jpg
    ├── projects/
    ├── leadership/
    └── creative/
```

## Running Locally

No build step required — just open the file directly:

```bash
git clone https://github.com/hriday-thakur/Portfolio.git
cd Portfolio
open index.html   # or just double-click it
```

Or serve it locally to avoid relative-path issues with some browsers:

```bash
python3 -m http.server 8000
```
then visit `http://localhost:8000`.

## Deployment

Hosted via GitHub Pages, deployed from the `main` branch root. Any push to `main` updates the live site automatically.

## Contact

- Email: hridaythakur.in@gmail.com
- GitHub: [github.com/hriday-thakur](https://github.com/hriday-thakur)
- LinkedIn: [linkedin.com/in/hridaythakur](https://www.linkedin.com/in/hridaythakur/)
