# Dharug Emoji Prototype — Starter (Vite + React + Tailwind)

This folder is **source code**. To get a public link with Netlify Drop you must first **build** and then upload the **dist/** folder.

## Quick start
```bash
npm install
npm run dev           # open http://localhost:5173
```

## Build and deploy (Netlify Drop)
```bash
npm run build         # creates the dist/ folder
# then open https://app.netlify.com/drop and drag the dist/ folder in
```
> Drag **dist/** (not the project root). Netlify Drop hosts static files only.

## GitHub Pages
- Set `base` in vite.config.ts to `'/dharug-emoji/'` (your repo name)
- `npm run build`
- Publish `dist/` via gh-pages or GitHub Actions.

