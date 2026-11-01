# Singapore haze monitor

Static single-page app. No build step, no dependencies, no API keys.

## Deploy on Vercel
1. Import this repository in the Vercel dashboard, or run `npx vercel --prod` in this folder.
2. Framework preset: Other. Build command: none. Output directory: leave blank (root).

## Data
- Haze (PSI and PM2.5), weather stations, rainfall and the 4 day outlook: National Environment Agency (NEA) via data.gov.sg, Singapore only.
- The readings are an embedded snapshot taken on 1 Nov 2026. Each dataset shows its own NEA reading time on the page.
- The page does not call the API yet, so values do not refresh until index.html is updated.
