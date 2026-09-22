# C001 | Source-to-case evidence trail

One receipt anchors the grouping rationale. The steps below link the public source record, an outbound transaction log, and deterministic contract-creation checks.

1. The [public Nomad incident manifest](https://github.com/nomad-xyz/hack-data) includes receipt event `0x1f5990ad8f4c9ded52c1df839d7ed3be8b6a01bbcaa35722863b0ff0a30227fb:340`, in block `15259463` at `2022-08-01 22:54:08 UTC`. Its recipient is `0x003a749b59b8ba34cefe91330a2d036e4945fc55`. The case workbook records a fixed pre-incident reference value of approximately $201,991 for its USDC receipt.
2. In the [same transaction](https://etherscan.io/tx/0x1f5990ad8f4c9ded52c1df839d7ed3be8b6a01bbcaa35722863b0ff0a30227fb), an outbound log at index `342` points to collector `0xbf293d5138a2a1ba407b43672643434c43827179`. The receipt and outbound logs are distinct records; the repeated transaction hash is not double-counted value.
3. The case workbook checks deterministic CREATE derivations for the top-level factory and child contract. For this example, the initiating address is `0xbf293d5138a2a1ba407b43672643434c43827179`, the factory is `0x955d64055e6a22f134e3b9a89a2b78fe3a301b9a` at nonce `14`, and the child is derived at nonce `2`. Both address checks passed in the saved evidence package. No dynamic call trace is claimed.

The full C001 group includes 200 in-manifest child recipients and 21 top-level creation transactions. Together, these records support a common deployment and execution origin. Beneficial ownership and the provenance of later fungible transfers remain unresolved.

[Return to overview](README.md) · [Method and limits](METHOD_AND_LIMITS.md)

