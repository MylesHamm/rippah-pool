# Rippah Pool — The Masters 2026

Live leaderboard for the Masters pool. Fetches scores from ESPN every 3 minutes.

## Deploy to GitHub Pages

1. Create a new repo on GitHub (e.g. `rippah-pool`)
2. Push `index.html` to the `main` branch
3. Go to **Settings → Pages → Source → Deploy from branch → main → / (root)**
4. Your site will be live at `https://yourusername.github.io/rippah-pool/`

## Updating Picks

Edit the `D` object in `index.html` — it's near the top of the `<script>` tag:

```js
const D={
  Calvini:["Scottie Scheffler","","","",""],
  Logan:["Ludvig Åberg","Jason Day","","",""],
  ...
};
```

Commit and push — GitHub Pages updates in ~60 seconds.

## Side Bets

Side bet scores are stored in each viewer's browser (localStorage). Enter them in the Props tab.

## Sponsored by Dubra Vodka
