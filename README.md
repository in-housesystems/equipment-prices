# Equipment Prices

Side-by-side supplier prices for In-House Systems LLC Path A print-cell equipment and consumables.

Same SKU, different suppliers. Capital equipment can open a quote mail draft (Jack sends it). Consumables are buy-it-now only.

## Live

https://in-housesystems.com/equipment-prices/

GitHub Pages serves this static folder from the repo root (`base` `/equipment-prices/`).

## Data

Public prices are baked in `data/prices.json` and inlined in `index.html`. Pages cannot scrape live dealer sites (CORS). Refresh the JSON, rebuild `index.html` if you change the generator, and stamp a new "as of" date.

## Rules

- Do not invent prices.
- Label every figure list / quote / estimate, with source URL and date.
- Do not auto-send email.
- Do not put personal Gmail or Round Rock on the public page.
