# Equipment Prices

https://in-housesystems.com/equipment-prices/

Side-by-side supplier prices for In-House Systems LLC Path A print-cell equipment and consumables.

Same SKU, different suppliers. Capital rows can open one quote mail draft (Jack sends it). Consumable rows buy on the supplier page. In-House Systems LLC does not sell these SKUs.

## This ship (Architecture Edit 1)

Single catalog source: the live page fetches `data/prices.json`. There is no inline `#price-data` copy to keep in lockstep. `404.html` matches `index.html`.

Screen (unchanged): short hero, Capital / Consumables tabs, print-cell kits, then one ranked compare table per SKU. No supplier cards.

Dropped: supplier cards; Copy / CSV / Draft RFQs / print toolbars; RFQ pack box; Gaps flags; Tied MAP and Best bid; the word landed; Source as a second capital button; print-pack / print-kit CSS.

Added: plain-word columns (Supplier, Kind, Published price, Extra required, Total we can compare, Stock, Note, Action). Best buyable is the lowest in-stock published total. Same-price in-stock rows share Best buyable (same price). A cheaper sold-out row is labeled cheaper but sold out and never wins. Add your quote on each capital SKU (this computer only) and Export JSON.

Kits: Formlabs split, Formlabs complete (wash/cure already in the $12,006 package), SprintRay complete-system $20,000 + Die & Model 2 ($20,149). SprintRay is request, so it cannot win buyable. ProWash S / ProCure 2 stay optional add-ons and are not added to that total.

## Two ways a number gets on this page

### 1. Published price

Edit only `data/prices.json`. Bump `asOf` / `asOfLabel`. Commit; GitHub Pages ships it. The live page fetches that file. There is no live scrape and no inline catalog copy to keep in lockstep.

### 2. Private quote

Type the quote in the app on this computer. It is stored under `equipment-prices:quotes` and ranked as Kind “Your quote”. It never wins Best buyable. Export JSON if you later want that row in `prices.json`. The app never commits, never sends, and never uploads.

## Live

GitHub Pages serves this static folder from the repo root (`base` `/equipment-prices/`).

## Rules

- Do not invent prices.
- Label every figure list / quote / estimate, with source URL and date.
- Total we can compare is published price plus that supplier’s required extra only. Shipping and tax are unknown.
- Do not auto-send email. Mailto drafts only, From `jpatterson@in-housesystems.com`.
- Do not put personal Gmail or Round Rock on the public page.
