# Utabiri — preview screens

Clickable placeholder mockups of the Utabiri MVP flow (play-money beta). Start here: **[flow index](https://andreolf.github.io/utabiri-preview/)**.

## Pages

| File | What it shows |
| --- | --- |
| `index.html` | Single-page preview: every mobile screen, the web version, MVP architecture and competitor comparison |
| `home.html` | Screen 1 — Soko / market feed |
| `market.html` | Screen 2 — market detail and bet slip |
| `portfolio.html` | Portfolio and open positions |
| `wallet.html` | Wallet and transaction history |
| `share-card.html` | WhatsApp/Telegram share card (OG image) |
| `web.html` | Desktop web layout |
| `og.png` | Link-preview image (1200×630), rendered from `og-source.html` with headless Chrome |

`style.css` holds the shared styles for every page; `index.html` adds only its one-pager layout on top.

## Running locally

Plain HTML and CSS, no build step. Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
```

## Publishing

The site is served by GitHub Pages from the `main` branch, so anything pushed to `main` goes live.

## Note on content

All markets, prices, dates and balances are illustrative placeholders, not live data.
