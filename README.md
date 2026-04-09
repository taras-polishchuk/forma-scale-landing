# FORMA Scale — Landing Page

> **Know Your Body. Own Your Progress.**

A single-page product landing site for the **FORMA Smart Scale** — a next-generation body composition scale that measures 17 metrics in 10 seconds.

---

## 📋 Table of Contents

- [About the Project](#about-the-project)
- [Page Sections](#page-sections)
- [Product Overview](#product-overview)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Features & Design Highlights](#features--design-highlights)
- [Browser Support](#browser-support)

---

## About the Project

This repository contains the complete source code for the **FORMA Scale** marketing landing page. The page is built as a self-contained `index.html` file — no build tools, no frameworks, no dependencies beyond a Google Fonts import. It is ready to deploy to any static hosting platform (GitHub Pages, Netlify, Vercel, etc.).

---

## Page Sections

| # | Section | Description |
|---|---------|-------------|
| 1 | **Hero** | Headline, sub-copy, animated scale illustration, floating metric cards, and key stats (17 metrics · 98% accuracy · 12-month warranty) |
| 2 | **Press Strip** | Scrolling marquee of featured publications (TechCrunch, Wired, Forbes, The Verge, etc.) |
| 3 | **Benefits** | Six benefit cards: 17 Metrics in 10s, Syncs Everywhere, 8 User Profiles, 18-Month Battery, Clinical Accuracy, Companion App CTA |
| 4 | **Metrics** | Full-width stats bar (17 metrics · 98% accuracy · 4.9★ rating · 50K+ customers) with animated counters |
| 5 | **Showcase** | Tabbed deep-dive into Body Composition, Smart App, and Design with a live device preview |
| 6 | **Reviews** | Carousel of 5 verified customer reviews (4.9 stars, 4,200+ reviews) |
| 7 | **FAQ** | Accordion with 6 questions covering accuracy, family profiles, integrations, standalone use, warranty, and shipping |
| 8 | **CTA** | Closing conversion section with trust badges (Secure Checkout, Free US Shipping, 30-Day Returns, 12-Month Warranty) |
| 9 | **Footer** | Navigation links and copyright |

---

## Product Overview

**FORMA Smart Scale** — $149

| Feature | Detail |
|---------|--------|
| Body metrics | 17 (body fat %, muscle mass, BMI, bone density, visceral fat, hydration, and more) |
| Measurement time | ~10 seconds |
| Technology | 4-electrode Bioelectrical Impedance Analysis (BIA) |
| Accuracy | ±0.1 kg · <2% deviation from DEXA scans |
| Max load | 180 kg |
| Surface | 4 mm tempered glass |
| Battery | 3 × AAA (~18 months) |
| User profiles | Up to 8 (auto-recognition via Bluetooth) |
| App compatibility | iOS 14+ · Android 8+ |
| Integrations | Apple Health, Google Fit, Fitbit, Garmin Connect, MyFitnessPal |
| Colors | Midnight · Arctic White |
| Warranty | 12 months |
| Returns | 30-day no-questions-asked |
| Shipping | Free US shipping · International available |

---

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Markup | HTML5 (semantic) |
| Styles | CSS3 — custom properties, CSS Grid, Flexbox, animations, `clamp()`, `backdrop-filter` |
| Scripts | Vanilla JavaScript (ES6+) — Intersection Observer, scroll events, carousel, accordion, tab switching |
| Fonts | [Inter](https://fonts.google.com/specimen/Inter) via Google Fonts (weights 300–900) |
| Icons | Inline SVG + emoji |
| Hosting | Static file — no server required |

---

## Getting Started

No build step required. Clone the repo and open the file in a browser:

```bash
git clone https://github.com/taras-polishchuk/forma-scale-landing.git
cd forma-scale-landing
open index.html        # macOS
# or
start index.html       # Windows
# or
xdg-open index.html    # Linux
```

To serve locally with live reload (optional):

```bash
npx serve .
# or
python3 -m http.server 8080
```

Then visit `http://localhost:8080`.

---

## Project Structure

```
forma-scale-landing/
└── index.html   # Entire landing page (HTML + CSS + JS in one file)
```

All styles are written in a `<style>` block inside `<head>`, and all scripts are written in a `<script>` block before `</body>`. No external CSS or JS files are required.

---

## Features & Design Highlights

- **Dark theme** — deep `#0a0a0f` background with indigo/violet gradient accents (`#5b6ef5` → `#a78bfa`)
- **Animated hero** — floating scale SVG illustration, orbiting rings, animated metric cards, and auto-incrementing stat counters
- **Scroll progress bar** — thin gradient bar at the top of the viewport tracks reading progress
- **Sticky nav** — transparent on load, blurs and darkens on scroll
- **Reveal animations** — elements fade and slide up as they enter the viewport via `IntersectionObserver`
- **Responsive layout** — mobile-first breakpoints at 768px and 480px; hamburger menu for mobile navigation
- **Press marquee** — infinite-scrolling logo strip using CSS `@keyframes`
- **Review carousel** — touch/click navigable with dot indicators
- **FAQ accordion** — smooth CSS height transition on open/close
- **Sticky purchase bar** — slides up from the bottom after scrolling past the hero
- **No dependencies** — zero npm packages, zero build step, single deployable file

---

## Browser Support

| Browser | Support |
|---------|---------|
| Chrome 90+ | ✅ |
| Firefox 88+ | ✅ |
| Safari 14+ | ✅ |
| Edge 90+ | ✅ |
| Mobile Chrome / Safari | ✅ |

---

© 2026 FORMA Technologies, Inc.
