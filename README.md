### Sarmad Khan

CTO at [Magnus Mage](https://magnusmage.com) and [Xyress](https://xyress.com). I build AI systems and blockchain protocols, and a growing share of my R&D goes into the place they overlap: AI that can prove what it did, and ledgers that will still be safe once post-quantum attacks are practical.

My work sits between architecture and code. I set the technical direction, write the design records, and still ship a lot of the Go, Python and TypeScript myself.

---

**Current work**

- **Xyress: verifiable AI infrastructure.** A platform for proving AI actions to banks, regulators and operators. One identity for every person, company, model and device (Sigil), an immutable evidence trail that anchors model decisions at inference time (Witness), multi-model orchestration that flags where models disagree (Synod), AI-assisted security monitoring (Vigil), and research tracks on model ranking and managed agent execution. It deploys on a public chain, in managed enclaves, on federated chains such as Hyperledger Fabric, or as bridged proofs from off-chain systems.
- **CreataChain: modular Layer 0.** Dual-chain architecture with Zenith and Catena, the EVM-compatible Creata Virtual Machine, and the Lunar Link interchain protocol for asset and message transfer across heterogeneous chains. I work deep in the protocol: consensus and node engineering, cross-chain messaging, SDKs and wallets, and the current R&D on post-quantum signatures and AI/ML components. CreataChain is in an interoperability sandbox with LuLu Financial in Abu Dhabi.
- **RBE (Resolve Before It Escalates): voice AI for government services.** A multilingual voice agent (Arabic, English, Urdu) that checks worker wage and settlement questions against the worker's contract, WPS record and the labour rule in force for that month. Speech-to-text, agent workflows with per-node tool scoping and text-to-speech run on ElevenLabs. The control plane is deterministic: the LLM explains, it never calculates or decides, every case ends at a human reviewer, and everything is audited append-only. Built for the Ignyte x ElevenLabs Future of Voice AI Challenge 2026.

---

**AI and ML**

- LLM systems: retrieval augmented generation, agentic workflows with scoped tool calling, multi-model orchestration and disagreement detection, structured output and function calling
- Reliability and safety: grounding checks, eval harnesses, guardrails, deterministic control planes around probabilistic models, human in the loop review
- Model work: fine-tuning with LoRA and QLoRA, embeddings and vector search, quantization and optimized inference serving
- Applied ML: fraud and anomaly detection, classification over on-chain and transactional data, feature pipelines and MLOps (model registry, drift monitoring, reproducible training)
- Voice AI: STT, TTS and real-time conversational agents across Arabic, English and Urdu
- Verifiable AI: cryptographic inference receipts, on-chain anchoring, TEE attestation and where zkML is worth its cost

**Blockchain and cryptography**

- Protocol design: Layer 0 and Layer 1 architecture, BFT consensus, node clients, state storage and sync, governance and upgrade paths
- Interoperability: cross-chain messaging, relayers and bridges, light client verification
- Execution: EVM and custom VM integration, smart contracts, SDKs, wallets and explorers
- Post-quantum cryptography: ML-DSA (FIPS 204), ML-KEM (FIPS 203), SLH-DSA (FIPS 205), hybrid classical and PQ signatures, crypto-agile key and transaction formats, migration planning for live networks
- Applied crypto: key management, HSM and remote signer setups, Merkle structures, commitments, identity and access models

---

**Open R&D**

| Repo | What it is |
|---|---|
| [rbe-mohre](https://github.com/magnusmage/rbe-mohre) | Voice AI agent for labour rights checks with a deterministic, audited control plane |
| [hybrid-pq-sig](https://github.com/evdatsion/hybrid-pq-sig) | Composite Ed25519 + ML-DSA-65 signatures in Go, with a height based migration policy for chains |
| [inference-anchor](https://github.com/evdatsion/inference-anchor) | Tamper-evident AI inference receipts, batched into Merkle trees and anchored on chain |
| [architecture-notes](https://github.com/evdatsion/architecture-notes) | ADRs and field notes on PQC migration, BFT in production and verifiable AI |

**Stack**

| Area | Tools |
|---|---|
| Languages | Go, Python, TypeScript, Rust, Solidity |
| AI and ML | PyTorch, Hugging Face, LangGraph, vLLM, ElevenLabs, OpenAI and Anthropic APIs, pgvector, FAISS, MLflow |
| Blockchain | Cosmos SDK, CometBFT, EVM, Hyperledger Fabric, libp2p, Foundry, Hardhat |
| Cryptography | cloudflare/circl, liboqs, Go crypto, HSM and remote signers |
| Backend | FastAPI, gRPC, PostgreSQL, MongoDB, Redis, Kafka |
| Platform | AWS, Kubernetes, Terraform, Docker, GitHub Actions, Cloudflare |

**Background**

Since 2019 Magnus Mage has taken blockchain and AI platforms from research to production for clients in the UAE, Pakistan and beyond: several mainnets launched from scratch, permissioned enterprise chains, consensus engines, wallets and explorers, and AI systems for fraud detection and data pipelines.

**Happy to talk about**

Post-quantum migration for chains and custody, verifiable and auditable AI for regulated industries, voice and agent systems in government services, and protocol architecture reviews.

[magnusmage.com](https://magnusmage.com) · [xyress.com](https://xyress.com)
