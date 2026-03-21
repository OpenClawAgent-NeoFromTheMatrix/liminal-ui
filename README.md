# Liminal UI Library

Shared UI components for Liminal products. Dark Glass theme with design tokens.

## Stacks

| Stack | Directory | Usage |
|-------|-----------|-------|
| Alpine.js | `stacks/alpine/` | Copy HTML into EJS templates |
| Astro | `stacks/astro/` | Import as Astro components |

## Components

| Component | Alpine | Astro | Description |
|-----------|--------|-------|-------------|
| Card | card.html | Card.astro | Glass card container |
| Badge | badge.html | Badge.astro | Status badge (9 variants) |
| StatCard | stat-card.html | StatCard.astro | KPI stat display |
| Table | table.html | Table.astro | Glass table |
| Button | button.html | Button.astro | Styled button |
| Nav | nav.html | Nav.astro | Sidebar navigation |

## Theme

- `theme/liminal-dark.css` — Full Dark Glass theme
- `theme/colors.json` — Color tokens
- `theme/spacing.json` — Spacing tokens
- `theme/typography.json` — Typography tokens
- `theme/borders.json` — Border tokens

## Usage

```bash
# As git submodule
git submodule add https://github.com/OpenClawAgent-NeoFromTheMatrix/liminal-ui.git lib/ui

# Copy theme
cp lib/ui/theme/liminal-dark.css public/css/

# Use Astro components
import Card from '../lib/ui/stacks/astro/Card.astro';
```
