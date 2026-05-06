# 🗺️ Series LLC Stack

> Community-maintained map for compliant, low-cost US entity setup with stablecoin treasury management and on/off-ramp flows.

This repo documents real-world KYB/KYC experiences across US entity types and residency profiles. The goal: help founders, nomads, and operators understand which providers actually accept you, how funds move, and what the full stack looks like — without expensive consultants or opaque advice.

## How to Navigate

There are two independent axes. Find yours and combine them.

**1. Your entity** → what the *business* can access (KYB)

| Entity | Status | Notes |
|---|---|---|
| [US LLC](./entities/us/) | ✅ Active | Wyoming + Delaware. KYB providers, ACH access. |
| → [Wyoming](./entities/us/wyoming/) | ✅ Active | Series LLC via Otoco. High privacy. |
| → Delaware | 🔜 Planned | — |

**2. Your residency** → what *you personally* can access (KYC)

| Residency | Status |
|---|---|
| [Global](./residency/global.md) | ✅ Services that work from anywhere |
| [Paraguay](./residency/paraguay.md) | ✅ Cedula-based, local exchanges, EU workarounds |
| Cayman Islands | 🔜 Planned |

The fund flow diagram in each entity folder shows how the two layers connect — business distributions flow into your personal accounts.

## Estimated Annual Costs (Ongoing)

| Item | Cost/yr |
|---|---|
| Proof of address service | ~$120 |
| Otoco entity maintenance | ~$100 |
| Accounting / yearly forms | ~$10 |
| **Total** | **~$230/yr** |

> Initial costs (residency permits, travel, setup) vary and are excluded.

## Stablecoin Orchestrators

Most crypto fintech on/off-ramp infrastructure runs on one of three rails:

| Orchestrator | Status | Notes |
|---|---|---|
| [bridge.xyz](https://bridge.xyz) | ⚠️ Use with caution | Shadow ban risk — accounts closed without explanation |
| [iron.xyz](https://iron.xyz) (now MoonPay) | ✅ Recommended | Best product; virtual cards, CLI terminal, build-your-own-bank API |
| [noah.com](https://noah.com) | 🔄 Evaluating | — |

## Privacy Stack

| Tool | Use Case |
|---|---|
| [privacypools.com](https://privacypools.com) | Compliant ETH mixer — seed your company wallet from a clean, verifiable source |
| [fluidkey](https://fluidkey.com) | Ephemeral keys — receive and rotate funds without triggering compliance flags |

## Repository Structure

```
series-llc-stack/
├── README.md                  ← You are here
├── entities/
│   └── us/
│       ├── README.md          ← KYB providers for any US LLC
│       └── wyoming/
│           ├── README.md      ← Wyoming-specific: formation, fund flow
│           └── image.png      ← Fund flow diagram
└── residency/
    ├── global.md              ← Personal services that work from anywhere
    └── paraguay.md            ← PY-specific: Cedula, local exchanges, EU workarounds
```

## Contributing

PRs welcome. When adding a provider, include:
- Entity type and jurisdiction
- Residency of applicant
- Outcome (accepted / not compatible)
- Any notable requirements or gotchas

## Need Help?

If your situation involves non-standard residency, specific on/off-ramp structuring, multi-entity coordination, or introductions to affordable compliance accountants — open an issue. Community members with relevant experience may be able to point you in the right direction.

## Disclaimer

For informational and educational purposes only. Nothing here constitutes legal, tax, or financial advice. Regulations vary by jurisdiction and change frequently.
