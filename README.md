# Emerging Tech Board Update

Q1 2026 Quarterly Briefing website for the **City of Austin Emerging Technology Board**.

Built following the [COA AI Template](https://github.com/crypticpy/COA_AI_Template) design system.

## Live Preview

Open `index.html` in a browser, or run a local server:

```bash
python3 -m http.server 8080
# Then visit http://localhost:8080
```

## Deployment (GitHub Pages)

1. Push this repository to GitHub
2. Go to **Settings > Pages**
3. Under "Source", select **Deploy from a branch**
4. Select `main` branch and `/ (root)` folder
5. Save

The site will be available at `https://[username].github.io/[repo-name]/`

## Design System

Based on the **City of Austin AI Template**:

| Token           | Value     | Usage                     |
| --------------- | --------- | ------------------------- |
| Brand Blue      | `#44499C` | Primary actions, headings |
| Brand Blue Dark | `#22254E` | Dark backgrounds, footer  |
| Brand Green     | `#009F4D` | Success states, accents   |
| Brand Faded     | `#f7f6f5` | Light backgrounds         |

**Typography:** Geist (Google Fonts)

## Features

- Official City of Austin logo and branding
- Glass morphism header (matching COA template)
- Dark mode support with persistence
- Responsive design (mobile-first)
- Smooth scroll navigation
- Card hover animations with left border accent
- Scroll-triggered fade-in animations
- Print stylesheet
- Accessibility: skip links, ARIA labels, keyboard navigation

## Structure

```
/
├── index.html      # Single-page site (Tailwind CDN)
├── .nojekyll       # Bypasses Jekyll on GitHub Pages
└── README.md
```

## Content Sections

1. **Hero** - Quarter badge, title, meeting info, CTAs
2. **Top 3 Priorities** - Must-read highlights with numbered cards
3. **All Topics** - 8 technology briefing cards in 2-column grid
4. **Resources** - External links, Austin-specific links, meeting info
5. **Footer** - COA branding and disclaimer

## Topics Covered

1. Agentic AI for Municipal Workflows
2. Autonomous Mobility Integration
3. Drone-as-First-Responder (DFR) + BVLOS
4. Edge-AI Traffic Safety Stack
5. Predictive Water Maintenance
6. Regional Digital Twins
7. Privacy-Enhancing Cryptography (PEC)
8. Post-Quantum Cryptography (PQC)
