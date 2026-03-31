# CLAUDE.md — LAC School Accessibility Landing Page

## Project
25 landing page iterations for the School Accessibility Platform + 1 gallery page.
Assignment 1 for MPCS 51238 (Design, Build, Ship, Spring 2026).

## Tech Stack
- Pure HTML + CSS only. No JavaScript, no frameworks, no external APIs.
- Google Fonts via CSS `@import` is allowed.
- Deploy on Vercel (static site, root index.html as entry point).

## Structure
- `index.html` + `gallery.css` — gallery page at root
- `versions/v1/` through `versions/v25/` — each has `index.html` + `style.css`

## Content: School Accessibility Platform
The platform maps 532,650 K-12 schools across 21 LAC countries with travel-time accessibility analysis.

### Core Story: "The School Race"
Visual race metaphor comparing a US kid (~10 min walk to school) vs. a kid in Vaupés, Colombia (2+ hours). Shows inequality through cute icons and proportional race tracks.

### Key Stats
- 532,650 schools mapped (447K public + 86K private)
- 21 countries covered
- 94% coverage vs official universe
- 96% georeferenced
- Panama pilot: 98.1% within 30 min motorized

## Style Preferences
- Each version should be self-contained (own CSS, no shared stylesheets between versions)
- Every version links back to gallery with `<a href="/">`
- Responsive design at minimum 320px, 768px, 1024px, 1440px
