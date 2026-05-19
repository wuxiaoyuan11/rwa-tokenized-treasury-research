# Tokenized Treasury and RWA Protocol Analysis: Market Growth, Risk Structure, and Product Design

## 1. Executive Summary

Real-world assets (RWA) are one of the clearest bridges between traditional finance and crypto infrastructure. Within RWA, tokenized U.S. Treasuries are the most institutionally legible category: the underlying assets are familiar, liquid, yield-bearing, and directly comparable with money market funds, bond funds, and cash-management products.

As of May 14, 2026, RWA.xyz reported $31.63 billion in distributed tokenized RWA value. Tokenized U.S. Treasuries accounted for $15.36 billion, or approximately 48.6% of that market. This makes tokenized Treasuries a core RWA category rather than a niche use case.

The key conclusion is that tokenized Treasuries are not simply "Treasuries onchain." They are hybrid financial products that combine traditional fund, custody, transfer-agent, compliance, and redemption infrastructure with blockchain-based settlement and distribution. The main analytical edge is therefore not token price prediction, but understanding legal claims, asset backing, redemption mechanics, custody, compliance, and yield sources.

## 2. Why Tokenized Treasuries Matter

Tokenized Treasuries matter because they connect familiar cash-management and fixed-income products with blockchain-based settlement, transfer, and distribution infrastructure. Unlike speculative crypto assets, tokenized Treasury products can be analyzed using traditional finance concepts such as fund shares, SPVs, custody, transfer agents, waterfalls, credit risk, redemption mechanics, and compliance.

This makes the category useful for evaluating how traditional financial products change when ownership records, transfer restrictions, and settlement processes move onchain. The key questions are not only technical, but also legal, operational, and market-structural:

- What does the token legally represent?
- Who owns or controls the underlying assets?
- How does redemption work in normal and stressed conditions?
- Does yield come from Treasury bills, repo, lending spreads, or incentives?
- Are transfers restricted by KYC, whitelists, or jurisdictional rules?

Tokenized Treasuries are therefore a useful anchor case for RWA analysis: they are simple enough to compare with traditional cash-management products, but complex enough to reveal the hybrid risks created when legal entities, custodians, smart contracts, and onchain transfer systems interact.

## 3. Market Overview

Market data supports using tokenized Treasuries as the anchor category for RWA analysis.

| Metric | Value | Source / Calculation |
|---|---:|---|
| Total distributed tokenized RWA value | $31.63B | RWA.xyz Market Overview, Distributed Asset Value |
| Distributed tokenized U.S. Treasury value | $15.36B | RWA.xyz U.S. Treasuries, Distributed Value |
| Tokenized U.S. Treasury share of tokenized RWA | 48.6% | $15.36B / $31.63B |

Tokenized Treasuries are also concentrated among several leading products:

| Rank | Product | Platform | Total Value |
|---:|---|---|---:|
| 1 | Circle USYC | Circle | $2.98B |
| 2 | BlackRock USD Institutional Digital Liquidity Fund / BUIDL | Securitize | $2.40B |
| 3 | Franklin OnChain U.S. Government Money Fund / BENJI | Franklin Templeton | $2.28B |
| 4 | Ondo U.S. Dollar Yield / USDY | Ondo | $2.15B |
| 5 | Janus Henderson Anemoy Treasury Fund / JTRSY | Centrifuge | $1.12B |

The product ranking shows that the market is shaped by both crypto-native distribution platforms and traditional asset managers. Circle and Ondo reflect crypto-native or crypto-adjacent distribution, while BlackRock, Franklin Templeton, and Janus Henderson indicate meaningful traditional asset manager participation.

The market is also multi-chain, although Ethereum remains dominant:

| Chain | Tokenized Treasury Value | Market Share |
|---|---:|---:|
| Ethereum | $8.3B | 54.0% |
| BNB Chain | $3.5B | 22.8% |
| Stellar | $854.3M | 5.6% |
| Solana | $565.0M | 3.7% |
| Plume | $516.1M | 3.4% |
| XRP Ledger | $403.6M | 2.6% |
| Avalanche C-Chain | $371.0M | 2.4% |
| Other | ~$849.0M | 5.5% |

Ethereum holds roughly 54.0% of tokenized Treasury value, but BNB Chain, Stellar, Solana, Plume, XRP Ledger, and Avalanche also have meaningful distribution. This suggests that tokenized Treasuries are becoming a multi-chain institutional asset category rather than a single-chain experiment.

## 4. Product Taxonomy

Tokenized Treasuries should be analyzed as financial products first and crypto tokens second. They can be compared with several traditional instruments:

| Product Type | Similarities | Differences |
|---|---|---|
| Money market funds | Short-duration assets, cash management, NAV or stable-value objective, regulated fund operations | Tokenized ownership records, wallet access, programmable transfer restrictions |
| Bond funds | Fixed-income exposure and rate sensitivity | Tokenized Treasury products often emphasize short-duration cash-like assets rather than duration risk |
| ABS / structured credit | Asset pools, investor claims, service providers, legal documentation, cash-flow rules | Tokenized products add blockchain settlement, smart contracts, whitelists, and onchain transfer records |
| Private credit pools | Credit underwriting, borrower risk, collateral, liquidity constraints | Onchain pool shares and vault infrastructure change distribution and reporting mechanics |

The critical point is that "tokenized Treasury" is not a single legal form. A token may represent a fund share, a note, a pool interest, or a blockchain-based record of a traditional financial claim. Analysis should therefore begin with legal structure and investor rights, not APY.

## 5. Protocol Comparison

The five protocols in this report represent different RWA product structures:

1. Ondo designs crypto-native tokenized Treasury yield products.
2. BlackRock BUIDL is an institutional liquidity fund tokenized through Securitize.
3. Franklin BENJI represents shares of a U.S.-registered money market fund with blockchain-integrated recordkeeping.
4. Maple represents onchain institutional credit and cash-management pools.
5. Centrifuge provides tokenization infrastructure for asset pools, private credit, structured credit, and fund products.

| Protocol | Product Type | Underlying Assets | Investor Access | Yield Source | Main Strength | Main Weakness |
|---|---|---|---|---|---|---|
| Ondo Finance | OUSG: tokenized Treasury fund-style exposure; USDY: yield-bearing tokenized note | OUSG: short-term Treasuries, Treasury / money market funds, cash-like assets; USDY: short-term Treasuries, short-duration Treasury ETFs, bank deposits, and related dollar assets | OUSG: qualified-access investors; USDY: qualifying non-U.S. investors | Treasury and cash-management yield reflected through NAV, token price appreciation, or rebasing depending on product | Strong crypto-native distribution and flexible product design | OUSG and USDY use different legal forms and mechanics, so diligence must be product-specific |
| BlackRock / Securitize | Tokenized institutional liquidity fund | Cash, U.S. Treasury bills, and repurchase agreements | Qualified institutional investors onboarded through Securitize | Income from short-duration cash-management assets; dividends distributed through token mechanics | Strong institutional credibility from BlackRock and tokenization infrastructure from Securitize | Permissioned access and transfers limit open crypto composability |
| Franklin Templeton | U.S.-registered government money market fund share represented by BENJI token | U.S. government securities, cash, and repurchase agreements | Investors onboarded through Franklin / Benji channels, subject to fund and jurisdiction requirements | Money market fund income | Clearest regulated-fund comparison; one BENJI represents one FOBXX share | Blockchain features still depend on traditional fund and transfer-agent infrastructure |
| Maple Finance | Onchain institutional credit marketplace and cash-management pools | Treasury bills, reverse repos, secured institutional loans, and pool-specific credit assets | Permissioned / eligible lenders depending on pool; KYC and AML checks | Treasury / repo yield for cash management; borrower interest and credit spreads for lending pools | Extends RWA analysis beyond Treasuries into private credit and institutional lending | Higher credit, borrower, counterparty, collateral, and liquidity risk |
| Centrifuge | RWA tokenization infrastructure for pools, funds, private credit, and structured assets | Depends on pool: Treasuries, private credit, receivables, real estate, fund interests, or other RWAs | Whitelisted / eligible investors depending on pool rules | Pool-specific cash flows, fund income, Treasury yield, or structured credit returns | Closest to ABS-style thinking: pools, issuers, share classes, service providers, waterfalls | Risk is highly pool-specific and harder to assess at platform level |

This comparison shows why RWA should not be treated as one product category. Ondo uses crypto-native product design to distribute Treasury-like yield. BUIDL represents BlackRock's institutional liquidity fund tokenized through Securitize. BENJI represents shares of Franklin Templeton's U.S.-registered money market fund. Maple shifts the focus from Treasuries to institutional credit. Centrifuge is closest to structured finance, providing infrastructure for issuers to create tokenized pools with share classes, investor restrictions, and pool-specific cash-flow rules.

## 6. Risk Framework

The core risk question for RWA products is not whether the asset is onchain. The more important question is what the token legally represents, what assets back it, who controls custody and redemption, and where yield comes from.

This framework scores each product across seven dimensions:

- Asset quality
- Legal claim
- Custody and cash management
- Redemption and liquidity
- Smart contract and oracle risk
- Compliance and investor eligibility
- Rate / yield risk

The initial model uses equal weighting across the seven dimensions. Equal weighting is appropriate for a research memo because the goal is transparent comparison across different product structures rather than a formal credit rating. In a real listing or investment due diligence process, asset quality, legal claim, redemption liquidity, and custody should likely receive higher weights.

| Protocol | Asset Quality | Legal Claim | Custody | Liquidity | Smart Contract | Compliance | Yield Risk | Average | Overall View |
|---|---:|---:|---:|---:|---:|---:|---:|---:|---|
| BENJI | 5 | 5 | 5 | 4 | 3 | 5 | 5 | 4.6 | Clearest regulated-fund structure; blockchain adds recordkeeping and transfer functionality rather than replacing fund infrastructure. |
| BUIDL | 5 | 4 | 5 | 4 | 3 | 5 | 5 | 4.4 | Institution-grade asset quality and infrastructure, with the main limitation being permissioned access and transfer restrictions. |
| Ondo | 4 | 3 | 3 | 4 | 3 | 4 | 4 | 3.6 | Strong product-market fit, but OUSG and USDY have different legal structures and mechanics that require product-by-product diligence. |
| Maple | 3 | 3 | 3 | 3 | 3 | 4 | 3 | 3.1 | Useful RWA credit model, but risk depends heavily on borrower quality, collateral, underwriting, and pool liquidity. |
| Centrifuge | 3 | 3 | 3 | 3 | 3 | 4 | 3 | 3.1 | Strong structured-finance relevance, but risk is highly pool-specific and requires diligence at the issuer and asset-pool level. |

BENJI and BUIDL score highest because they are closest to institution-grade fund structures backed by short-duration government securities, cash, and repurchase agreements. Ondo scores lower because OUSG and USDY use different legal structures and token mechanics. Maple and Centrifuge score lower not because they are weaker platforms, but because their products move into credit and structured-asset risk, where borrower quality, collateral, liquidity, and issuer-specific terms matter more.

## 7. Listing and Due Diligence Checklist

If an exchange, asset manager, or platform wants to list or support an RWA product, it should review:

1. Asset composition and concentration
2. Legal claim and investor rights
3. Fund, note, SPV, or pool documentation
4. Custodian, administrator, transfer agent, auditor, and service providers
5. Redemption frequency, settlement timing, gates, fees, and liquidity limits
6. Smart contract audits, oracle design, upgrade permissions, and admin controls
7. KYC, transfer restrictions, investor eligibility, and jurisdictional limitations
8. Fee structure and yield source
9. Secondary market liquidity, market makers, and approved counterparties
10. Reporting frequency, NAV methodology, proof of reserves, and asset disclosure

The key diligence question is not only whether the asset is high quality, but whether the token holder has a clear, enforceable, and redeemable claim on that asset or its cash flows.

## 8. Conclusion

Tokenized Treasuries are a useful starting point for RWA research because they combine market scale, institutional participation, and clear links to traditional fixed-income products. However, the category is more complex than the phrase "Treasuries onchain" suggests. Products differ by legal form, investor eligibility, redemption mechanics, custody, yield distribution, and blockchain implementation.

This project also shows why traditional finance knowledge can be a differentiated advantage in Web3. A strong RWA analyst should understand not only blockchains and token standards, but also fund structures, credit risk, custody, liquidity, legal claims, and compliance. That combination is directly relevant for digital asset research, tokenization, RWA, crypto investment analyst, and product strategy roles.

## Data Sources

- RWA.xyz Market Overview and U.S. Treasuries dashboard, accessed May 14, 2026.
- Ondo Finance documentation for OUSG and USDY.
- Securitize / BlackRock BUIDL public materials.
- Franklin Templeton BENJI / FOBXX public materials.
- Maple Finance documentation for Cash Management and institutional lending pools.
- Centrifuge documentation for pools, investors, issuers, and tokenized RWA infrastructure.
