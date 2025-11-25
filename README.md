# FAQ Accordion

A responsive, accessible FAQ accordion built from the [Frontend Mentor](https://www.frontendmentor.io/) challenge. Users can expand/collapse questions, navigate with keyboard, and enjoy a polished, mobile-friendly interface.

**Live site:** [https://abel-v-pereira.github.io/faq-accordion-main/](https://abel-v-pereira.github.io/faq-accordion-main/)

---

## Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [What I Learned](#what-i-learned)
- [Future Improvements](#future-improvements)

---

## Features

✓ **Interactive accordion** — Click a question to toggle its answer  
✓ **Keyboard accessible** — Navigate and toggle using `Tab`, `Enter`, or `Space`  
✓ **Responsive design** — Optimized for mobile (320px) and desktop (1440px+)  
✓ **Hover/focus states** — Clear visual feedback for interactive elements  
✓ **Semantic HTML** — Proper structure for accessibility and SEO  

---

## Tech Stack

- **HTML5** — Semantic markup
- **CSS3** — Flexbox, custom properties, media queries
- **JavaScript** — Minimal accordion toggle logic
- **Google Fonts** — Work Sans (variable weight, 100–900)

---

## Getting Started

### Option 1: Open directly in browser

```bash
# Navigate to the project folder and open index.html
start index.html   # Windows
open index.html    # macOS
xdg-open index.html # Linux
```

### Option 2: Serve locally (recommended for development)

**Using Python 3:**

```bash
cd /path/to/faq-accordion-main
python -m http.server 8000
# Then open http://localhost:8000
```

**Using VS Code Live Server extension:**

1. Install the [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) extension
2. Right-click `index.html` → "Open with Live Server"

---

## Project Structure

```
faq-accordion-main/
├── index.html              # Main HTML structure
├── styles/
│   ├── reset.css           # Global resets
│   └── style.css           # Layout, card, accordion styles
├── assets/
│   ├── images/             # Background pattern, star icon, etc.
│   └── fonts/              # Work Sans font files (optional local hosting)
├── design/                 # Reference designs (mobile, desktop)
├── README.md               # This file
└── style-guide.md          # Color palette and typography guide
```

---

## What I Learned

### 1. **CSS Background Shorthand**
   - The `background` shorthand syntax: `[color] [image] [repeat] [position]/[size]`
   - Why `center/cover` works but `center cover` doesn't — the `/` separates position from size
   - Using `center/auto` to center an image at its intrinsic size without scaling

### 2. **Flexbox Layout Strategy**
   - Building a two-panel card: left panel (purple title area) and right panel (questions)
   - Using `flex: 0 0 40%` to fix left panel width and `flex: 1 1 auto` for responsive right panel
   - Combining `justify-content: center` and `align-items: center` on body for true center alignment

### 3. **Responsive Design**
   - Mobile-first approach: start with mobile layout, use `@media (max-width: 720px)` for larger screens
   - Stacking flexbox panels vertically on small screens with `flex-direction: column`
   - Adjusting padding/font sizes per breakpoint for visual consistency

### 4. **Accessible Accordion Structure**
   - Using clickable `<p>` elements with proper semantics (not ideal — `<button>` is better)
   - Adding keyboard navigation: `Tab` to focus, `Enter`/`Space` to toggle
   - Styling focus states (e.g., `:focus`) to help keyboard users

---

## Future Improvements

- [ ] **ARIA attributes** — Add `aria-expanded`, `aria-controls`, and `aria-labelledby` for screen readers
- [ ] **Smooth transitions** — Animate answer height on expand/collapse with `max-height` CSS transitions
- [ ] **Keyboard handling** — Improve keyboard support with `ArrowUp`/`ArrowDown` to navigate between questions
- [ ] **Accessibility audit** — Test with screen readers (NVDA, JAWS) and keyboard-only navigation
- [ ] **Unit tests** — Add tests for toggle functionality and keyboard interactions
- [ ] **Performance** — Lazy-load images and optimize for Core Web Vitals

---

## Author

**Abel V. Pereira**

- Frontend Mentor: [@Abel-V-Pereira](https://www.frontendmentor.io/profile/Abel-V-Pereira)
- GitHub: [@Abel-V-Pereira](https://github.com/Abel-V-Pereira)

---

## Acknowledgments

- [Frontend Mentor](https://www.frontendmentor.io/) for the challenge, design assets, and inspiration
- The open-source community for tools and best practices
