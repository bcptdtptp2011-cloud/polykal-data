# polykal-data

Free, open datasets from [PolyKal](https://polykal.net/), an independent, read-only site that compares Polymarket and Kalshi. PolyKal has no accounts, no ads and no referral links.

## Datasets

The live, continuously maintained files are served from polykal.net. This repository intentionally does not copy them, so you always get the current version with its own verification dates.

| Dataset | Live file | What it contains |
|---|---|---|
| Fee schedule | https://polykal.net/data/fees.json | Kalshi and Polymarket trading-fee formulas and constants, per-series Kalshi multipliers, Polymarket per-category rates, primary sources, verification dates and a changelog. Documentation: https://polykal.net/fee-schedule/ |
| Country availability | https://polykal.net/data/availability.json | Per-jurisdiction status of each platform as stated by the platform or regulator, with source URL, source type and verification date. |

Check the verification date fields inside each file before relying on a number. Both files record their sources.

## License and attribution

Both datasets are released under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). You may copy, redistribute and adapt them, including commercially, as long as you credit **PolyKal (polykal.net)** and link to the page you used, for example https://polykal.net/fee-schedule/.

Suggested citation: PolyKal. Prediction market fee schedule dataset (Kalshi and Polymarket). https://polykal.net/data/fees.json

## Notes

PolyKal is independent and not affiliated with Polymarket or Kalshi.

The data is for information only. It is not financial or legal advice.

Found an error or a changed fee? Email support@polykal.net with the source link.
