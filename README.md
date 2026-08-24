# Ericka's Portfolio 🌿

A personal portfolio website built for the MATA Technologies Inc. Skills Showcase Challenge
(Web Development Intern Challenge).

## Description

A single-page portfolio with a botanical, garden-journal visual theme — sage green, warm
beige, and a peachy accent — featuring a Home section with a short bio, a Projects section
showcasing three real projects, and a Contact section with a client-side-validated form.

## Technologies used

- HTML5
- CSS3 (custom properties, Grid/Flexbox, no framework)
- Vanilla JavaScript (no dependencies)
- Google Fonts: Fraunces (display) + Quicksand (body)

## Features

- Fully responsive (mobile, tablet, desktop)
- Smooth-scroll navigation with active-section highlighting
- Mobile hamburger menu
- Dark mode toggle that saves your preference (`localStorage`)
- Scroll-triggered reveal animation on project cards
- Contact form with inline validation and a success toast (no backend — per brief)
- Respects `prefers-reduced-motion`

## Setup instructions

No build step required.

1. Clone the repo
2. Open `index.html` in a browser — that's it

To deploy on GitHub Pages: Settings → Pages → set source to the `main` branch, root folder.

**Live site:** _add your deployed link here once published_

## Before you publish

- [ ] Replace `assets/profile-placeholder.svg` with a real photo (swap the `<img src>` in
      `index.html`'s hero section)
- [ ] Swap the three project SVG placeholders in `assets/` for real screenshots
- [ ] Fill in the `href="#"` repo/demo links on each project card
- [ ] Update the bio copy in the Home section to sound like you
- [ ] Add your real email/socials to the Contact section if you want them listed

## Folder structure

```
portfolio/
├── index.html
├── style.css
├── script.js
├── README.md
└── assets/
    ├── profile-placeholder.svg
    ├── project-hydronet.svg
    ├── project-chatbot.svg
    └── project-gallery.svg
```
