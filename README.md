# AIWMC-Quantis-Demo-1.0-
Public Documentation for AIWMC Quantis, Stress testing your business before money spent, use instant invoicing or download analysis for 1 seconds in PDF with you messy inputs
# AIWMC Quantis

> AI-powered business validation and financial intelligence SaaS.  
> **Live product: [aiwmcquantis.com](https://aiwmcquantis.com)**

---

## What it does

Quantis turns unstructured business descriptions into structured, benchmarked financial validation. A founder describes a business; Quantis returns:

- A revenue model with channel breakdown
- Unit economics anchored to industry medians
- An operating cost structure
- A ranked list of risk factors with severity and mitigation
- Sector benchmarks for comparison

Every claim is traceable to a benchmark row or a stated assumption. No black-box generation.

## Documentation in this repo

| Document | What's in it |
|---|---|
| **[architecture.md](./architecture.md)** | System design, component responsibilities, data flow, tech tradeoffs |
| **[api-contracts/openapi.yaml](./api-contracts/openapi.yaml)** | Public REST API specification (OpenAPI 3.0) |
| **[failure-modes.md](./failure-modes.md)** | Production failure modes from the first 90 days, and how Quantis 2.0 addresses each |

## What's not in this repo

The production source code, prompt templates, benchmark dataset, and scoring logic are private. For a walkthrough under NDA, reach out via [LinkedIn](https://www.linkedin.com/in/bogdan-jeltov-6218b9324).

## Why this is in public

Quantis is the FDE loop compressed into a product: sit close to a real problem (founders making bets on incomplete information), instrument it, ship a working system, iterate against user feedback. The documents in this repo show how that loop actually runs in production — architecture, API contracts, and the failure modes that show up when the system meets real users.
