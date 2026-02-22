# Cursor Landing Page — HTML/CSS Clone

A static recreation of the [Cursor.com](https://cursor.com) landing page, built with pure HTML and CSS. No JavaScript, no frameworks.

---

## Getting Started

No build step required. Open the file directly in your browser:

```bash
# Double-click index.html, or use VS Code Live Server
```

---

## Sections

| Section | Description |
|---|---|
| Header | Sticky nav with logo, links, and action buttons |
| Hero | Headline, subtitle, CTA, and a mock code editor with AI chat overlay |
| Trusted By | Company logo strip |
| Feature Blocks | Chat with codebase, Tab Autocomplete, Privacy Mode |
| More Features | Docs Integration, Auto-Debug, Lint Fixes, Codebase Indexing |
| Testimonials | Three-column testimonial cards |
| Use Cases | Refactoring, Debugging, Understanding |
| Changelog | Dated release notes |
| Team | Team introduction with CTA |
| Final CTA | Full-width download prompt |
| Footer | Four-column links grid |

---

## Design Tokens

| Variable | Value | Usage |
|---|---|---|
| `--bg-primary` | `#000000` | Page background |
| `--bg-secondary` | `#0C0C0C` | Section backgrounds |
| `--text-primary` | `#FFFFFF` | Headings, buttons |
| `--text-secondary` | `#A1A1A1` | Body text, nav links |
| `--accent` | `#37996B` | Green accent |
| `--border-color` | `#333333` | Dividers, card borders |
| `--font-sans` | `Inter` | Body and UI font |
| `--font-mono` | `JetBrains Mono` | Code blocks |

---

## Tech Stack

- HTML5
- Vanilla CSS — custom properties, Flexbox, CSS Grid, `backdrop-filter`
- Google Fonts — Inter and JetBrains Mono

---

## Notes

- Desktop-first design; no responsive breakpoints.
- All navigation links use placeholder `#` hrefs.
- The hero code editor uses syntax-highlighted `<span>` tags to simulate an IDE UI.
- No JavaScript — all transitions and hover states are CSS-only.
