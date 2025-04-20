# UU-MWD-500-ZM-AP2
**Assignment 2 – Design a Website for Your University Department**

## Overview

This repository contains a responsive, accessible, static website for the Computer Science Department at XYZ University. It demonstrates:
- Semantic HTML5 structure (`<header>`, `<nav>`, `<main>`, `<footer>`)
- Modern CSS3 layout (Grid, Flexbox) and media queries
- A CSS‑only image slideshow on the homepage
- Hero banners on each page
- Card‑based content sections for programs, faculty, and news
- A styled contact form with Google Form embed
- A Google Map embed for campus location
- Consistent, maintainable CSS in a single stylesheet

## Audience

Prospective students and faculty seeking information about the department’s offerings, people, and events.

## Project Requirements

- **Navigation**: Header, navigation bar with active‑link highlighting
- **Layout**: Hero banner or slideshow on each page; main content areas (about, programs, faculty, news, contact)
- **Multimedia & Embeds**: CSS‑only slideshow (`index.html`); Google Form and Google Map embeds on the Contact page
- **Responsive & Accessible**: Mobile‑first design with breakpoints at 600px and 768px; semantic tags, label associations, focus states for form controls
- **Assets**: Open‑license banners, icons, and headshots in `assets/`

## Wireframe Sketch

```
[ HEADER ]
[ HERO BANNER or SLIDESHOW ]
[ MAIN CONTENT ]
  • About   (two‑col)
  • Programs (card grid)
  • Faculty  (photo grid)
  • News    (card grid)
  • Contact (form + form embed + map + social)
[ FOOTER ]
```

## Site‑Map / File Structure

```
/
├── index.html            ← Home + CSS slideshow
├── about.html            ← About + hero banner + two‑col
├── programs/
│   ├── undergrad.html    ← Undergrad programs (cards)
│   └── grad.html         ← Graduate programs (cards)
├── faculty.html          ← Faculty photo grid
├── news.html             ← News & events (card grid)
├── contact.html          ← Contact form + Google Form + Map + social links
├── styles/
│   └── styles.css        ← Single stylesheet for entire site
└── assets/
    ├── header-banner.png
    ├── icons/
    │   ├── programs-icon.svg
    │   └── faculty-icon.svg
    ├── photos/
    │   ├── slide1.jpg
    │   ├── slide2.jpg
    │   └── slide3.jpg
    └── faculty/
        ├── jane-doe.jpg
        └── john-smith.jpg
```

## How to Run & View

### 1. Clone the Repository (Recommended)
```bash
git clone https://github.com/alindaByamukama/UU-MWD-500-ZM-AP2.git
cd UU-MWD-500-ZM-AP2
```

### 2. Directly Open Files (Fallback)
1. Download or unzip the project folder.
2. Locate any `.html` file (e.g., `index.html`).
3. Double‑click to open in your browser.  
> **Note:** Some browsers may block iframe embeds when opened via `file://`. If sections appear blank, use a local server.

### 3. Run a Simple Local Server (Optional)
- **Python 3**:
  ```bash
  python -m http.server 8000
  ```
  Open `http://localhost:8000/index.html` in your browser.

- **Node.js http-server**:
  ```bash
  npm install -g http-server
  http-server -p 8000
  ```
  Open `http://localhost:8000`.

## Deployment

- **GitHub Pages Link**: <a href="https://alindabyamukama.github.io/UU-MWD-500-ZM-AP2/" target="_blank">Hosted Project can be found at this address.</a>
