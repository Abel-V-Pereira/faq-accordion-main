---
# FAQ Accordion — Frontend Mentor

## Overview

This repository contains my implementation of the Frontend Mentor "FAQ accordion" challenge. The goal is to build a responsive, accessible accordion that matches the provided design (see `/design`).

### The challenge

Users should be able to:

- Toggle an answer when its question is clicked
- Navigate and toggle answers using keyboard only (focus + Enter/Space)
- See a responsive design that matches the mobile and desktop layouts
- Observe clear hover/focus states for interactive elements

### Links

- Solution (FAQ Accordion): https://github.com/Abel-V-Pereira/faq-accordion-main
- Live site: https://abel-v-pereira.github.io/faq-accordion-main/

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

- Frontend Mentor — [@Abel-V-Pereira](https://www.frontendmentor.io/profile/Abel-V-Pereira)

## Acknowledgments

Thanks to Frontend Mentor for the challenge and design assets.

---
