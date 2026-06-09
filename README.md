# Dashgo UI Asset Pack

Editable source-derived assets for building new interfaces in the Dashgo visual language.

## Start here

1. Open `catalog/dashgo-ui-kit.svg` to inspect the kit.
2. Drag standalone SVG assets from `components/`, `icons/` and `templates/` into Figma.
3. Import `tokens/figma-variables.csv` into a variables workflow, or use `tokens/design-tokens.json` in code.
4. For React and Tailwind screens, reuse the files in `react/` and `tokens/tailwind-preset.js`.

## Included

- Editable primitive SVG assets: buttons, fields, toggles and status pills.
- Editable patterns: sidebar, mobile navigation, metric cards, row patterns, detail panel, settings card, loading skeleton and save bar.
- Blank desktop and mobile shell templates for new pages.
- Color, spacing, radius and typography tokens in CSS, JSON and CSV formats.
- React class presets and TypeScript tokens.

## Placeholder values

Reusable examples intentionally contain neutral placeholder labels and values instead of environment-specific data. This keeps the pack safe to reuse across projects without changing layout geometry, colors or component structure.

## Typography

The source app uses a system font stack. The SVG assets use `Segoe UI, Inter, Arial, sans-serif` with a mono fallback stack so imported text stays editable.
