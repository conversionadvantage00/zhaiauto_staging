# Zhai Auto microsite (staging)

Dealer microsite for **Zhai Auto, George** (Peugeot, Citroën, Opel, Jeep, Fiat), built and managed by [Conversion Advantage](https://conversionadvantage.co.za).

- **This repo:** staging / preview site, served by GitHub Pages at https://conversionadvantage00.github.io/zhaiauto_staging/
- **Live site:** published from the separate `zhaiauto_live` repo once approved here.

## Please don't edit files here directly

The files in this repo are exports. The master working copy (with the built-in editor, build notes and backups) lives in the Zhai Auto client folder on the Conversion Advantage Google Drive. Changes made directly on GitHub will be overwritten by the next export.

## What's in the repo

| Path | What it is |
|---|---|
| `index.html` | The whole one-page site (layout, code and stock data in one file) |
| `privacy.html` | POPIA privacy notice, linked from the footer and the form consent box |
| `img/` | Car photos (`img/cars/`), site images, brand logos, video loops, favicons and phone-sized copies (`img/m/`) |

## How updates happen

1. Stock is checked weekly against the dealer's cars.co.za listings (Pre-owned and Demo models), plus monthly specials.
2. Changes are made in the master working copy, checked (pre-launch check) and exported.
3. The export is committed here and pushed; the staging link is reviewed.
4. The same files are copied to `zhaiauto_live` and pushed.
