# Minnowbrook Analytic Reasoning Seminar 2026 — Website

## Overview

Static website for the Minnowbrook Analytic Reasoning Seminar, June 3–6, 2026 at Blue Mountain Lake, NY. Organized by Kristopher Micinski, Syracuse University.

Hosted on GitHub Pages via GitHub Actions — automatic deployment on push to `main`.

## Structure

- `index.html` — Single-page site (all content)
- `css/style.css` — All styles
- `assets/images/hero.jpg` — Optimized hero photo (2400px wide, JPEG, 732KB)
- `.github/workflows/deploy.yml` — GitHub Pages deployment workflow

## Tech Stack

- Pure HTML + CSS — no build step, no JavaScript, no frameworks
- Google Fonts: Cormorant Garamond (display headings) + Inter (body text)
- GitHub Pages for hosting

## Design

- Color palette blends Syracuse University orange (`#F76900`) with Adirondack-inspired deep navy (`#0F2744`) and lake blues (`#2E6B8A`)
- Hero section: full-viewport panoramic lake photo with dark overlay and centered text
- Detail cards: white cards with orange top-border accent
- Alternating section backgrounds (cream / warm gray) for visual rhythm
- Responsive: breakpoints at 900px, 768px, 480px

## Deployment

Push to `main` → GitHub Actions deploys automatically. No build step required.

To enable: Go to repo Settings → Pages → Source → select "GitHub Actions."

## Content Guidelines

- **Never invent or fabricate content** — no made-up speakers, schedules, or details
- Only add information confirmed by the organizer
- Keep the site minimal and elegant
- When adding speakers or schedule, follow the established visual patterns
- Maintain the Syracuse + Adirondack design language

## Local Preview

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```
