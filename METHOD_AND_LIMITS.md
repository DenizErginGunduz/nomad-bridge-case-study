# Method and limits

The source cohort is a pinned copy of [Nomad's public incident manifest](https://github.com/nomad-xyz/hack-data), curated after the event. Receipt and token-transfer logs are retained separately. Prices are fixed pre-incident reference proxies, not realized proceeds. The first-hop movement measure is capped per token at original receipts; it does not prove fungible-unit provenance. Case priority inherits the highest member priority rather than recalculating thresholds on a pooled value.

The frozen review rule order is: insufficient evidence; substantial direct return; immediate; enhanced; unresolved. The immediate tier requires either at least $1 million in priced original receipts, or at least $100,000 and at least 50% moved in each token's first hour. The T+24 and T+72 labels use the same manifest-derived receipt cohort, with later movement and return information visible at the later cutoff.

The baseline has 329 case IDs, with 60 immediate at T+24 and 53 at T+72. Under separate one-change price/threshold scenarios with membership held fixed, the immediate counts range from 49 to 63 and 43 to 56. At equal case budgets, a gross-value-only ranking covers more *gross original receipt value* than the policy queue at both cutoffs. At T+72 the policy queue covers slightly more of a *remaining-value proxy* than gross-value-only, while a residual-value-only ranking covers more. These are descriptive comparisons without blinded case outcomes or reviewer-time measurement; they do not establish better detection or efficiency.

**Open source boundary:** the pinned manifest's final included receipt is at 2022-08-02 00:05:49 UTC, whereas [Coinbase's incident analysis](https://www.coinbase.com/blog/nomad-bridge-incident-analysis) describes activity through 05:49 UTC. This discrepancy is unresolved. A chain-wide intake reconstruction is required before testing live discovery or incident-wide recall.

**Other limits:** one incident; retrospective cohort selection; earlier project-stage knowledge of some later labels; public RPC responses rather than independently validated chain state; missing prices for some tokens; incomplete downstream conversion and recovery paths; no authenticated ownership data; and no full dynamic call trace. Validation and replay were performed within the project; no external audit is claimed.

The public example exposes one source-to-case trail. The complete technical archive, including 23 core CSVs and saved RPC evidence, is retained separately for detailed review.

[Return to overview](README.md) · [Worked example](EVIDENCE_SAMPLE.md)

