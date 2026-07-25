# NorthPeak Digital — Agency Website

A responsive one-page agency website built for the Digital Heroes 
Web Development Internship Task.

## Live URL
https://niyatipandey.github.io/northpeak-digital/

## Tech Stack
- HTML5 (semantic markup)
- CSS3 (Flexbox, Grid, custom properties)
- Vanilla JavaScript

## Sections
- Hero with live performance dashboard mockup
- Services grid (6 services)
- Client testimonials
- Pricing (3 tiers with featured card)
- Contact form with client-side validation
- Footer with credit line

## Design Decisions

### 1. Color Palette
Chose near-black (#0A0A0A) with muted gold (#C9A84C) as the accent 
instead of the common blue or dark themes most agency sites use. The 
goal was a premium, luxury feel that stands out among submissions while 
remaining professional and readable.

### 2. Dashboard Mockup
Built the hero mockup entirely in HTML, CSS, and SVG with no images. 
This keeps the site fast, fully responsive, and avoids any external 
asset requests — which directly contributed to the high Lighthouse 
Performance score.

### 3. Typography Pairing
Space Grotesk for headings — modern and geometric, gives the site 
personality. Manrope for body text — clean and highly readable at 
small sizes. Both loaded from Google Fonts with display=swap to 
prevent render blocking.

## Responsive Breakpoints
- 1440px — full desktop layout
- 768px — tablet, single column sections
- 360px — mobile, hidden nav replaced with hamburger menu

## Lighthouse Scores
- Desktop: 98 Performance, 100 Accessibility, 100 Best Practices, 90 SEO
- Mobile: 94 Performance, 100 Accessibility, 100 Best Practices, 90 SEO

## AI Usage
Used Claude to help with specific CSS snippets, layout fixes, and 
content copy. All design decisions — color palette, typography, layout 
structure, and section hierarchy — were made independently after 
researching agency site references. Code was reviewed and integrated 
manually, not blindly copy-pasted. The dashboard mockup concept and 
the brown/peach to luxury black-gold palette direction were original 
decisions made before any code was written.

## Inspiration
Referenced agency sites on Awwwards and land-book.com for layout 
direction. The final design takes a different visual approach — warm 
luxury palette, editorial typography, and a custom-built dashboard 
mockup — rather than following common agency site templates.