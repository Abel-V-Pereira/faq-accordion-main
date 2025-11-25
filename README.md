---
# FAQ Accordion — Frontend Mentor

![Design preview for the FAQ accordion coding challenge](design/desktop-design.jpg)

## Overview

This repository contains my implementation of the Frontend Mentor "FAQ accordion" challenge. The goal is to build a responsive, accessible accordion that matches the provided design (see `/design`).

### The challenge

Users should be able to:

- Toggle an answer when its question is clicked
- Navigate and toggle answers using keyboard only (focus + Enter/Space)
- See a responsive design that matches the mobile and desktop layouts
- Observe clear hover/focus states for interactive elements

### Links

- Solution (this repo): https://github.com/your-username/faq-accordion
- Live site: https://your-live-site-url.com

## Screenshot

Add a screenshot of your finished solution to `/screenshot.jpg` and update the image above. The `/design` folder contains `mobile-design.jpg` and `desktop-design.jpg` for reference.

## Built with

- Semantic HTML5
- CSS custom properties
- Flexbox
- Responsive design (mobile-first)
- Minimal JavaScript for the accordion behaviour

## How to run locally

You can open `index.html` directly in your browser, but serving the project via a local server is recommended for consistent asset loading.

Using Python 3 (works in Bash on Windows):

```bash
python -m http.server 8000
```

Then open `http://localhost:8000` in your browser.

Or use VS Code's Live Server extension and open the folder.

## What I learned

- Using a single, responsive card layout with CSS Flexbox and a left visual panel for the title.
- How background shorthand parses `position/size` and why `center/cover` vs `center/auto` change behaviour.
- Structuring accessible accordion HTML so keyboard users can navigate using `tab` + `Enter`/`Space`.

## Continued development

- Add smooth height transitions for expanding/collapsing answers without layout shift.
- Improve accessibility by adding ARIA attributes (`aria-expanded`, `aria-controls`) and IDs for answers.
- Add unit/integration tests for keyboard interactions.

## Author

- Your Name — https://your-website.example
- Frontend Mentor — [@yourusername](https://www.frontendmentor.io/profile/yourusername)

## Acknowledgments

Thanks to Frontend Mentor for the challenge and design assets. Use the `/design` images as a visual guide when matching spacing and colors.

---
