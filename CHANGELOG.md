# Equipment Prices changelog

Newest first. This is the human list of what went live. GitHub still has the technical commits.

## Sep 4, 2026 — One catalog file

- The live page loads prices from `data/prices.json` only
- Dropped the extra copy of the catalog that used to sit inside the HTML and had to stay in lockstep
- If that file fails to load, the page shows an error instead of an empty table
- Compare tables, Best buyable rules, and dollar figures did not change

## Sep 2, 2026 — Ranked tables

- Replaced the first same-day supplier-card page with one ranked compare table per SKU
- Capital / Consumables tabs, print-cell kits at the top of Capital, then tables
- Best buyable is the lowest in-stock published total. Same-price in-stock rows share it. A cheaper sold-out row is labeled cheaper but sold out and never wins
- Capital rows can still open one quote mail draft (Jack sends it). Consumable rows still buy on the supplier page
- You can type a private quote on this computer. It ranks in the table as Your quote and never wins Best buyable
