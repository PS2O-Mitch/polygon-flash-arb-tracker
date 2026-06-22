# HonestFlashArbV2 — Live Performance Tracker

A zero-backend, read-only dashboard for the `HonestFlashArbV2` Polygon flash-loan
arbitrage contract. Static HTML (ethers.js + Chart.js from CDN) — no keys, no server.

**Live:** https://ps2o-mitch.github.io/polygon-flash-arb-tracker/

Open it, paste your deployed contract address (or append `?address=0xYourContract` to the
URL), and it reads the public `FlashCompleted` / `FlashRequested` events from a Polygon RPC
and shows status, total profit per asset, a cumulative-profit chart, and recent trades linked
to PolygonScan.

Contract source lives in a separate private repo.
