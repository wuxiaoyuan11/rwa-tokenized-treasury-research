# Risk Framework

## Risk Framework

The core risk question for RWA products is not simply whether an asset is onchain. The more important question is what the token legally represents, what assets back it, who controls custody and redemption, and where yield comes from. For this reason, the framework scores each product across seven dimensions: asset quality, legal claim, custody and cash management, redemption and liquidity, smart contract and oracle risk, compliance and investor eligibility, and rate / yield risk.

## Scoring Method

The initial framework uses equal weighting across the seven dimensions. Each dimension receives a score from 1 to 5:

- 1 = weak, opaque, high risk, or difficult to diligence
- 3 = acceptable but with meaningful limitations
- 5 = strong, transparent, institution-grade, and operationally mature

Equal weighting is appropriate for the initial research memo because the goal is to compare different RWA product structures transparently rather than build a formal credit rating model. The products in this report are not identical: BENJI and BUIDL are closer to fund structures, Ondo combines fund-style and tokenized-note products, Maple is closer to institutional credit, and Centrifuge is closer to structured asset-pool infrastructure. Equal weighting keeps the comparison simple and avoids overfitting the framework to one product type.

For a real listing or investment due diligence process, the framework should be adjusted toward a weighted model. Asset quality and legal claim should receive the highest weights because they determine whether the token holder has a clear and enforceable claim on high-quality underlying assets. Redemption liquidity and custody should also receive high weights because they determine whether investors can recover value under normal and stressed conditions. Smart contract risk, compliance, and yield risk remain important, but for most RWA products the most material risks sit at the boundary between the legal structure, underlying assets, service providers, and redemption process.

## Risk Score Summary

| Protocol | Asset Quality | Legal Claim | Custody | Liquidity | Smart Contract | Compliance | Yield Risk | Average | Overall View |
|---|---:|---:|---:|---:|---:|---:|---:|---:|---|
| BENJI | 5 | 5 | 5 | 4 | 3 | 5 | 5 | 4.6 | Clearest regulated-fund structure; blockchain adds recordkeeping and transfer functionality rather than replacing fund infrastructure. |
| BUIDL | 5 | 4 | 5 | 4 | 3 | 5 | 5 | 4.4 | Institution-grade asset quality and infrastructure, with the main limitation being permissioned access and transfer restrictions. |
| Ondo | 4 | 3 | 3 | 4 | 3 | 4 | 4 | 3.6 | Strong product-market fit, but OUSG and USDY have different legal structures and mechanics that require product-by-product diligence. |
| Maple | 3 | 3 | 3 | 3 | 3 | 4 | 3 | 3.1 | Useful RWA credit model, but risk depends heavily on borrower quality, collateral, underwriting, and pool liquidity. |
| Centrifuge | 3 | 3 | 3 | 3 | 3 | 4 | 3 | 3.1 | Strong structured-finance relevance, but risk is highly pool-specific and requires diligence at the issuer and asset-pool level. |

## Interpretation

BENJI and BUIDL score highest because they are closest to institution-grade fund structures backed by short-duration government securities, cash, and repurchase agreements. BENJI has the clearest legal framing because one BENJI token represents one share of a U.S.-registered money market fund. BUIDL also has strong asset quality and institutional credibility through BlackRock and Securitize, but its access and transferability are permissioned.

Ondo scores slightly lower because it contains more product-structure variation. OUSG is closer to NAV-based tokenized Treasury fund exposure, while USDY is a tokenized note with accumulating and rebasing versions. This does not make Ondo weak, but it means investors must evaluate each product separately rather than treating all Ondo Treasury products as the same.

Maple and Centrifuge score lower because their products move beyond low-risk Treasury exposure into credit and structured-asset risk. Maple requires analysis of borrower quality, collateral, underwriting standards, pool liquidity, and default recovery. Centrifuge requires pool-level diligence because each pool can have different assets, issuers, share classes, redemption rules, and service providers. Their lower scores reflect higher analytical complexity, not necessarily lower platform quality.

## Key Takeaway

RWA products transform some crypto-native risks into traditional financial risks, but they also create hybrid risks at the boundary between legal entities, custodians, smart contracts, transfer restrictions, and redemption processes. A strong RWA analyst should therefore combine traditional credit and fund diligence with blockchain infrastructure analysis.
