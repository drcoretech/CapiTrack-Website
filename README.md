# CapiTrack — Autonomous Wealth & Expense Operating System

An Apple-keynote style luxury scrollytelling product showcase for **CapiTrack**: The local-first, zero-knowledge financial operating system for founders, freelancers, and modern businesses.

## Key Highlights
- **Sticky Card Stacking Architecture**: Smooth GSAP ScrollTrigger scrollytelling engine that stacks cards with dynamic depth scaling, brightness falloff, and blur.
- **Embedded Cinema Player**: Custom responsive video showcase player with audio controls, play/pause state management, timeline progress bar, and fullscreen support.
- **Bi-Directional Theme System**: Dark Mode (Obsidian / Emerald / Gold) and Light Mode (Clean Slate / Emerald) with animated SVG morphing icons and `localStorage` persistence.
- **100% Mobile & Tablet Responsive**: Tailored breakpoints for ultra-compact mobiles (360px), phones (640px), tablets (860px / 1024px), and ultra-wide desktops.
- **Zero Third-Party Tracking**: Completely local-first, zero analytics, zero external user data collection.

## File Structure
```
capitrack-showcase/
├── index.html        # Main standalone showcase application
├── netlify.toml      # Production security headers and asset caching rules
├── images/           # High-resolution screenshots and 30s showcase MP4
├── .gitignore        # Git ignore rules for clean commits
└── README.md         # Repository documentation
```

## Local Development
Open `index.html` directly in your browser or serve locally with any static HTTP server:

```bash
# Option 1: Python
python3 -m http.server 5500

# Option 2: Node npx serve
npx serve .
```

## Deployment
Pre-configured for 1-click deployment on **Netlify**, **Vercel**, or **GitHub Pages**.

- **Netlify**: Drag and drop the folder or zip directly into [app.netlify.com/drop](https://app.netlify.com/drop).
- **GitHub Pages**: Go to **Settings** &rarr; **Pages** &rarr; select `main` branch root `/`.

---
© 2026 drcoretech studio. All rights reserved.
