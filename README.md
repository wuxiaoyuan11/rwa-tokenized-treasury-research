# Tokenized Treasury & RWA Protocol Research

Independent research project analyzing tokenized U.S. Treasuries and real-world asset (RWA) protocols across market size, product structure, investor access, redemption mechanics, compliance, and risk.

## Research Thesis

Tokenized Treasuries are not simply "Treasuries onchain." They are hybrid financial products combining traditional fund, custody, transfer-agent, compliance, and redemption infrastructure with blockchain-based settlement and distribution.

The main analytical edge is not token price prediction, but understanding legal claims, asset backing, redemption mechanics, custody, compliance, and yield sources.

## Key Findings

- As of May 14, 2026, RWA.xyz reported `$31.63B` in distributed tokenized RWA value.
- Tokenized U.S. Treasuries represented `$15.36B`, or approximately `48.6%` of distributed tokenized RWA value.
- The top tokenized Treasury products included Circle USYC, BlackRock BUIDL, Franklin BENJI, Ondo USDY, and Janus Henderson JTRSY.
- Ethereum represented approximately `54.0%` of tokenized Treasury value, but the market was increasingly multi-chain across BNB Chain, Stellar, Solana, Plume, XRP Ledger, and Avalanche.
- Tokenized Treasury products differ materially by legal structure: fund shares, tokenized notes, fund interests, pool shares, and blockchain-integrated recordkeeping should not be treated as the same product.

## Protocols Covered

| Protocol / Issuer | Product(s) | Research Angle |
|---|---|---|
| Ondo Finance | OUSG / USDY | Crypto-native tokenized Treasury yield products |
| BlackRock / Securitize | BUIDL | Institutional tokenized liquidity fund |
| Franklin Templeton | BENJI / FOBXX | U.S.-registered money market fund with blockchain-integrated recordkeeping |
| Maple Finance | Cash management / lending pools | Onchain institutional credit and cash management |
| Centrifuge | JTRSY / RWA pools | Structured finance and asset-pool tokenization infrastructure |

## Deliverables

| Deliverable | File |
|---|---|
| Research memo | [`reports/research_memo.md`](reports/research_memo.md) |
| Market dashboard | [`reports/market_dashboard.md`](reports/market_dashboard.md) |
| Protocol comparison | [`reports/protocol_comparison.md`](reports/protocol_comparison.md) |
| Risk framework memo section | [`reports/risk_framework.md`](reports/risk_framework.md) |
| Risk scoring framework | [`frameworks/risk_scoring_framework.md`](frameworks/risk_scoring_framework.md) |
| Protocol comparison CSV | [`tables/protocol_comparison.csv`](tables/protocol_comparison.csv) |
| Source log | [`sources/source_log.md`](sources/source_log.md) |

## Project Structure

```text
rwa-tokenized-treasury-research/
├── README.md
├── reports/
│   ├── research_memo.md
│   ├── market_dashboard.md
│   ├── protocol_comparison.md
│   └── risk_framework.md
├── frameworks/
│   └── risk_scoring_framework.md
├── tables/
│   └── protocol_comparison.csv
└── sources/
    └── source_log.md
```

## Data Sources

Primary data and protocol references include:

- RWA.xyz Market Overview and U.S. Treasuries dashboard
- Ondo Finance documentation
- Securitize / BlackRock BUIDL public materials
- Franklin Templeton BENJI / FOBXX public materials
- Maple Finance documentation
- Centrifuge documentation

See [`sources/source_log.md`](sources/source_log.md) for source tracking.
