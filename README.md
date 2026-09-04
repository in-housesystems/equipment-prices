# Equipment Prices

https://in-housesystems.com/equipment-prices/

Side-by-side supplier prices for In-House Systems LLC Path A print-cell equipment and consumables.

Jack uses this to compare dealers on the same SKU. In-House Systems LLC does not sell these SKUs. Capital rows can open one quote mail draft (Jack sends it). Consumable rows buy on the supplier page.

## Update prices

Edit only `data/prices.json`. Bump `asOf` and `asOfLabel`. Commit; GitHub Pages ships it. The live page fetches that file. There is no live scrape.

Quotes typed in the app stay on this computer. They are not published prices. Export JSON if you later want a row in `data/prices.json`. The app never commits, never sends, and never uploads.

## Rules

- Do not invent prices.
- Label every figure list / quote / estimate, with source URL and date.
- Total we can compare is published price plus that supplier’s required extra only. Shipping and tax are unknown.
- Do not auto-send email. Mailto drafts only, From `jpatterson@in-housesystems.com`.
- Do not put personal Gmail or Round Rock on the public page.
