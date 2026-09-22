### Sarmad Khan

CTO at [Magnus Mage](https://magnusmage.com) and [Xyress](https://xyress.com). I work where AI systems and blockchains meet, and lately on making both of them survive the move to post-quantum cryptography.

Most of my time goes into architecture and R&D: consensus and node design, key management, cryptographic protocols, and the infrastructure that lets an AI system prove what it did. I still write a lot of the code, mostly Go, TypeScript and Python.

---

**What I'm working on**

- **Xyress.** Verifiable AI infrastructure. Cryptographic proof anchoring for AI activity, with a unified identity layer so every model, operator and user action can be traced to someone accountable.
- **Post-quantum migration for ledgers.** Hybrid Ed25519 + ML-DSA signatures, crypto-agile key formats, and rollout plans that do not strand users halfway through.
- **Verifiable inference.** Tamper-evident receipts, Merkle batched anchoring, and where TEEs and zkML fit on top.

**Background**

Since 2019 the team at Magnus Mage has taken blockchain and AI platforms from research to production for clients in Pakistan, the UAE and beyond. That includes several L1 mainnets launched from scratch (Libonomy, Haidrun, CreataChain among them), consensus engines, node clients, wallets and explorers, plus AI systems for fraud detection and data pipelines.

A lot of the early chain work was built on Tendermint and the Cosmos SDK. The Libonomy node and AI engine repos pinned below are from that period.

---

**Open R&D**

| Repo | What it is |
|---|---|
| [hybrid-pq-sig](https://github.com/evdatsion/hybrid-pq-sig) | Composite Ed25519 + ML-DSA-65 signatures in Go, with a height based migration policy for chains |
| [inference-anchor](https://github.com/evdatsion/inference-anchor) | Tamper-evident AI inference receipts, batched into Merkle trees and anchored on chain |
| [architecture-notes](https://github.com/evdatsion/architecture-notes) | ADRs and field notes on PQC migration, BFT in production and verifiable AI |

**Tools I reach for**

Go, TypeScript, Python, Rust when it earns its place · Cosmos SDK, CometBFT, libp2p, EVM · PyTorch, vector stores, LLM serving · Kubernetes, Terraform, AWS

**Interested in talking about**

Post-quantum migration plans for chains and custody, verifiable and auditable AI for regulated industries, and protocol architecture reviews.

[magnusmage.com](https://magnusmage.com) · [xyress.com](https://xyress.com)
