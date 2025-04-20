# UU-MWD-500-ZM-AP2
Assignment: Design a website for your universtiy department
## Department Website for Computer Science Department

## Overview

This project is a responsive, accessible, static website for the Computer Science Department at XYZ University. It demonstrates semantic HTML5, modern CSS3 layout techniques (Grid & Flexbox), original graphics, multimedia elements, and third-party service embeds.

## File Structure

```
├── favicon.ico
├── robots.txt
├── sitemap.xml
├── index.html
├── about.html
├── programs/
│   ├── undergrad.html
│   └── grad.html
├── faculty.html
├── news.html
├── contact.html
├── styles/
│   └── styles.css
├── scripts/
│   ├── slideshow.js
│   └── menu-toggle.js
├── assets/
│   ├── header-banner.png
│   ├── icons/
│   │   ├── programs-icon.svg
│   │   └── faculty-icon.svg
│   └── videos/
│       └── campus-tour.mp4  *(removed in final ZIP — hosted externally)*
└── site-map.txt
```

## Quick Setup & Usage

1. **Unzip** the project archive.
2. **View Locally**:
   - **Direct**: Double-click `index.html` to open in your browser.
   - **HTTP Server**:
     ```bash
     cd path/to/project
     python -m http.server 8000
     # or: npx http-server
     ```
     Then open `http://localhost:8000/`.
3. **Edit Content**:
   - HTML: modify `.html` files in the root and `programs/` folder.
   - Styles: update `styles/styles.css` for colors, typography, layout.
   - Scripts: adjust slideshow timing in `scripts/slideshow.js` or menu toggle behavior in `menu-toggle.js`.
4. **Embed Updates**:
   - Campus tour: update YouTube iframe URL in `index.html` (video is hosted externally).
   - Contact form: check embed URL in `contact.html` (Google Form).
   - Social feeds: update Twitter/X and Instagram embed code blocks in `index.html` or `contact.html`.

## Deployment

- Deploy to any static hosting service (GitHub Pages, Netlify, Vercel).
- Ensure `robots.txt` and `sitemap.xml` are served from the root.

## Credits

- **Graphics**: Custom header and icons created with Adobe Illustrator & Photoshop.
- **Third-Party Tools**:
  - Google Forms
  - Twitter Publish widgets
  - EmbedSocial for Instagram gallery
- **Testing & Validation**:
  - W3C HTML/CSS Validator
  - WAVE Accessibility Tool
  - Chrome DevTools Responsive Emulator