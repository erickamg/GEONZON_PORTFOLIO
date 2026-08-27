# Ericka's Portfolio 

A personal portfolio website showcasing my skills, projects, and background as a BS Information Technology student.

## Description

A single-page portfolio in a clean green-and-beige color palette, featuring a Home section with a short bio, a Projects section showcasing three real projects, and a Contact section with a client-side-validated form.

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
2. Open `index.html` in a browser

To deploy on GitHub Pages: Settings → Pages → set source to the `main` branch, root folder.

**Live site:** _add your deployed link here once published_

## Before you publish

- [ ] Fill in the `href="#"` repo/demo links on each project card
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
