# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a web presentation project for **Proper Barber Club**, a membership-only grooming club in downtown Halifax. The project is a single-page landing site showcasing the brand, which emphasizes premium service, technology-enabled appointments, and an exclusive membership model.

## Brand Identity

**Colors:**
- Primary Background: `#1C2B40` (dark blue)
- Accent/CTA Color: `#CF9E54` (gold)
- White: `#ffffff`

**Typography:**
- Buttons and CTAs: Raleway (Google Fonts)
- Body text: System fonts stack

**Brand Assets Location:**
- Logo: `images/logo-with-bg.png`
- Brand guidelines: `AssetsandExamples/Proper Barber Brand Guide v II.pdf`
- Color scheme reference: `AssetsandExamples/New Colour Scheme.png`
- Complete website copy: `AssetsandExamples/content.txt`

## Project Structure

```
/
├── index.html              # Main landing page
├── images/                 # Logo and image assets
├── Fonts/                  # Custom fonts (if any)
└── AssetsandExamples/      # Brand assets, PDFs, and content reference
    └── content.txt         # All website copy organized by sections
```

## Development

This is a static HTML/CSS website with no build process or dependencies. Changes can be previewed by opening `index.html` directly in a browser.

**Key Design Principles:**
- Mobile-first responsive design with breakpoints at 768px and 480px
- Centered layouts using flexbox
- Smooth hover transitions and interactions
- Clean, minimal aesthetic matching the "premium, tech-enabled" brand positioning

## Content Reference

All website copy is available in `AssetsandExamples/content.txt`, organized into sections:
1. Hero Section
2. What Makes Proper Different
3. Membership Tiers (Proper Member $48, Premium $78, VIP $108)
4. How It Works
5. FAQ
6. Apply/Join
7. Member Testimonials

Refer to this file when implementing new sections or updating copy.

## Design Guidelines

- Button styling should use the gold accent color (`#CF9E54`) with 2px borders and 8px rounded corners
- Maintain generous spacing (50px+ gaps) for a clean, premium feel
- Logo should be sized proportionally and never distorted
- All interactive elements should have smooth hover states with subtle transforms and shadows
