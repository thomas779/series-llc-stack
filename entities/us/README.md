# US LLC

> This repo assumes LLC formation. Other structures (C-corp, S-corp, DUNA, etc.) are not covered.

The key advantage of a US LLC over a foreign entity (HK, SG, etc.) is **ACH access** — it unlocks zero/low-fee stablecoin on/off-ramps. Foreign entities typically have to wire out or use local currency rails instead.

## Jurisdictions

| Jurisdiction | Notes |
|---|---|
| [Wyoming](./wyoming/) | Series LLC via Otoco. High privacy. Non-resident friendly. |
| Delaware | 🔜 Planned |

Wyoming and Delaware share the same KYB provider landscape below. Jurisdiction-specific differences (formation, costs, privacy) are documented in each folder.

## KYB Providers

### ✅ Accepted

| Provider | Type | Notes |
|---|---|---|
| Mercury | Business Banking | Main business account. USD wire/ACH + USDC on/off-ramp |
| Meow | Business Banking | Zero-fee USDC on/off-ramp, central distribution hub |
| Kraken Business | Crypto Exchange | [Zero-fee conversions for USDC and USDG](https://support.kraken.com/articles/free-stablecoin-conversions) |
| OKX Business | Crypto Exchange | [Zero-fee USDG conversions, custodial US treasury yield access](https://www.okx.com/en-eu/learn/usdg) |

### ❌ Not Compatible

| Provider | Type |
|---|---|
| Altitude | Business Banking |
| Paxos | Stablecoin / Payments |
| Brex | Business Banking |
| Coinbase | Crypto Exchange |
| [Native Markets](https://usdh.com/) | Brokerage, Stablecoin |

> PRs welcome — if you've tested a US LLC with a provider not listed, add your outcome and residency profile.

## Notes

- KYB approval depends heavily on how the application is structured, not just entity type or residency
- Personal (KYC) options depend on your residency — see [residency/](../../residency/) for services by jurisdiction
