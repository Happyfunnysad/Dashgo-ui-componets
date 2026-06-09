# Dashgo — editable source-verified SVG frames

These SVG files were exported from the rendered DOM of the uploaded Dashgo React frontend. They are not screenshots: backgrounds, cards, borders, controls and SVG icons are vector elements; labels and values remain SVG `<text>` layers.

## Import into Figma
Drag SVG files onto the canvas or use **File → Place image**. Figma will import vectors and text as editable layers. Use the PNG previews only as contact sheets.

## Folders
- `desktop/` — 28 editable desktop frames
- `mobile/` — 5 editable responsive frames

## Fidelity note
The files use the actual browser layout and computed styles from the source code. Browser-only effects such as complex shadows, native form rendering and some clipping behavior may be simplified during SVG conversion. The included PNG contact sheets are for verification only.

## Source entry points
- `frontend/src/pages/Dashboard.tsx`
- `frontend/src/pages/LoginPage.tsx`
- `frontend/src/pages/Settings.tsx`
- `frontend/src/pages/TailscalePage.tsx`
- `frontend/src/components/Sidebar.tsx`
- `frontend/src/components/LogsModal.tsx`
- `frontend/src/components/tailscale/DeleteDeviceDialog.tsx`
- `frontend/src/index.css`
