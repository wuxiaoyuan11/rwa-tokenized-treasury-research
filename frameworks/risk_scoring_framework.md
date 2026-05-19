# RWA Risk Scoring Framework

Use a 1 to 5 score for each dimension.

- 1 = weak, opaque, high risk, or difficult to diligence
- 3 = acceptable but with meaningful limitations
- 5 = strong, transparent, institution-grade, and operationally mature

## Dimensions

| Dimension | Key Questions | Score |
|---|---|---:|
| Asset Quality | Are the assets Treasuries, repos, money market funds, private credit, ABS, or loans? How transparent and liquid are they? |  |
| Legal Claim | Does the token represent fund shares, beneficial interests, debt claims, notes, or only economic exposure? |  |
| Custody and Cash Management | Who holds the assets and cash? Are custodians, administrators, transfer agents, and auditors named? |  |
| Redemption and Liquidity | Can investors redeem daily, instantly, periodically, or only through secondary liquidity? Are gates or fees possible? |  |
| Smart Contract and Oracle Risk | Are contracts audited? Are permissions, upgradeability, price feeds, and token transfer restrictions disclosed? |  |
| Compliance and Investor Eligibility | Is KYC required? Are investors limited to qualified purchasers, accredited investors, or non-US persons? |  |
| Rate / Yield Risk | Is the yield directly tied to Treasury bills, lending spreads, leverage, credit risk, or protocol incentives? |  |

## Scoring Output

| Protocol | Asset Quality | Legal Claim | Custody | Liquidity | Smart Contract | Compliance | Yield Risk | Average | Overall View |
|---|---:|---:|---:|---:|---:|---:|---:|---:|---|
| Ondo | 4 | 3 | 3 | 4 | 3 | 4 | 4 | 3.6 | Strong product-market fit, but OUSG and USDY have different legal structures and mechanics that require product-by-product diligence. |
| BUIDL | 5 | 4 | 5 | 4 | 3 | 5 | 5 | 4.4 | Institution-grade asset quality and infrastructure, with the main limitation being permissioned access and transfer restrictions. |
| BENJI | 5 | 5 | 5 | 4 | 3 | 5 | 5 | 4.6 | Clearest regulated-fund structure; blockchain adds recordkeeping and transfer functionality rather than replacing fund infrastructure. |
| Maple | 3 | 3 | 3 | 3 | 3 | 4 | 3 | 3.1 | Useful RWA credit model, but risk depends heavily on borrower quality, collateral, underwriting, and pool liquidity. |
| Centrifuge | 3 | 3 | 3 | 3 | 3 | 4 | 3 | 3.1 | Strong structured-finance relevance, but risk is highly pool-specific and requires diligence at the issuer and asset-pool level. |

## Score Rationale

| Protocol | Rationale |
|---|---|
| Ondo | Asset quality is relatively strong because products are tied to Treasuries and cash-management assets. Legal claim receives a mid score because OUSG and USDY use different structures: fund-style exposure versus tokenized note. Liquidity is strong but still subject to product terms, limits, and redemption processes. |
| BUIDL | Asset quality, custody, compliance, and yield risk score highly because the product is BlackRock-managed and backed by cash, Treasury bills, and repos. Smart contract score is lower because the product still depends on permissioned tokenization infrastructure and transfer controls. |
| BENJI | BENJI scores highest because it is closest to a traditional regulated money market fund share, with clearer fund structure and transfer-agent recordkeeping. The lower smart contract score reflects that blockchain adds operational rails but does not remove technical and permissioning risks. |
| Maple | Maple has more credit risk than Treasury products. Scores are moderate because pool risk depends on borrower underwriting, counterparty quality, collateral, liquidity, and recovery. It is useful for RWA analysis but requires deeper credit diligence. |
| Centrifuge | Centrifuge is scored moderately because each pool can differ materially by issuer, asset type, share class, redemption terms, and service providers. The platform is analytically powerful, but risk cannot be assessed only at the platform level. |
