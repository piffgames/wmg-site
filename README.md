# Word Mining Game — Website

This repo powers the official WMG website deployed on Cloudflare Pages.

## Structure
```
index.html        ← Main website (homepage, features, leaderboard sidebar)
game/
  index.html      ← The game file (copy WMG_v12.html here, rename to index.html)
```

## Setup
1. Copy your latest `WMG_v12.html` into `game/` and rename it `index.html`
2. In `index.html`, replace the `FIREBASE_CONFIG` values with your actual config from the game file
3. Push to GitHub → Cloudflare Pages auto-deploys
