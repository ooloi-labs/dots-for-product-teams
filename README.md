# Dots for Product Teams — Landing Page

A static marketing landing page for **Dots**, an AI-powered qualitative data analysis tool that helps product teams surface insights from scattered user data.

---

## About the Product

Dots aggregates qualitative data from multiple sources — interviews, support tickets, NPS surveys, app store reviews, and more — and uses AI to surface patterns, themes, and traceable insights. It's built for Product Teams, UX Researchers, and Customer Success teams.

---

## Page Sections

| # | Section | Description |
|---|---------|-------------|
| 1 | Hero | Headline, CTA buttons, and an embedded product demo video |
| 2 | Problem | Four pain points: scattered signals, analysis paralysis, shallow AI outputs, organizational blind spots |
| 3 | Solution | What Dots brings — data flow diagram and feature cards |
| 4 | How It Works | Four-step process: Add context → Bring data → Understand signals → Act |
| 5 | Who It's For | Persona cards for Product Teams, UX Researchers, Customer Success & Support |
| 6 | CTA | Final call-to-action linking to the demo booking page |

---

## Tech Stack

- **Pure HTML + CSS** — no JavaScript frameworks or build tools
- **Google Fonts** — DM Sans and DM Serif Display (loaded via CDN)
- **No dependencies** — nothing to install

---

## Getting Started

Just open the file in a browser:

```bash
open index.html
```

No build step, no server, no package manager required.

---

## Customization

### Colors & Theming
All design tokens are defined as CSS custom properties at the top of the `<style>` block:

```css
:root {
  --bg: #FFFFFF;
  --accent: #22C55E;
  --text: #0D0D0D;
  --radius: 12px;
  /* ...and more */
}
```

Edit these variables to restyle the entire page consistently.

### CTA Link
The "Book a demo" button points to:
```
https://getdots.in/contact
```
Update this in the final `<div class="cta-section">` if the URL changes.

### Coming Soon Integrations
The data flow section includes two placeholder integrations marked with a "soon" badge:
- Mixpanel
- Amplitude

Remove the `coming-soon` class or update the labels when these integrations go live.

---

## Browser Support

Works in all modern browsers. Uses:
- CSS custom properties
- `position: sticky` (navbar)
- `radial-gradient` (hero blobs)
- CSS Grid and Flexbox

No polyfills needed for current browser versions.
