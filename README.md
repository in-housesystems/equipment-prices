# Equipment Prices

https://in-housesystems.com/equipment-prices/

Side-by-side supplier prices for In-House Systems LLC Path A print-cell equipment and consumables.

Same SKU, different suppliers. Capital equipment can open a quote mail draft (Jack sends it). Consumables are buy-it-now only.

## This ship (Edit 1)

Ranked compare table under each capital SKU. Landed is published price plus required extra only; shipping and tax are unknown.

Bid pack: print, copy table, CSV (`SKU-as-of-2026-09-02`), and Draft RFQs as one mailto draft or quote-page link per supplier. The app never sends email.

Category jump chips hash to the first SKU in that group (`#vhf-e5`). Capital: Mill / Printer / Wash·cure / Scanner. Consumables: Resin / Wash chemistry / PPE / Trays.

Print-cell kits from existing SKUs: Formlabs split, Formlabs complete, SprintRay complete-system + Die & Model 2. SprintRay ProWash S / ProCure 2 are optional add-ons so the published complete-system figure is not stacked.

Dropped this ship: consumable Source buttons (Buy only) and the quote-card boilerplate paragraph.

## Live

GitHub Pages serves this static folder from the repo root (`base` `/equipment-prices/`).

## Data

Public prices are baked in `data/prices.json` and inlined in `index.html`. Pages cannot scrape live dealer sites (CORS). Refresh the JSON, rebuild `index.html` if you change the generator, and stamp a new "as of" date.

## Rules

- Do not invent prices.
- Label every figure list / quote / estimate, with source URL and date.
- Do not auto-send email.
- Do not put personal Gmail or Round Rock on the public page.
