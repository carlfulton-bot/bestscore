# BestScore

Simple volleyball scorekeeper. Single HTML file, no build step.

## Deploy to Cloudflare Pages

1. In Cloudflare → Workers & Pages → Create application → Pages → Connect to Git
2. Select this repo (`carlfulton-bot/bestscore`)
3. Framework preset: None
4. Build command: leave empty
5. Build output directory: `/`
6. Deploy
7. Add custom domain `bestscore.app` in the Pages project settings

LocalStorage keeps scores between refreshes. Fully offline-capable once loaded.