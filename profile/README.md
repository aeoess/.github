# AEOESS — Agentic Economy Orchestration Engine for Sovereign Systems

Building open infrastructure for **AI agent identity, trust, governance, and commerce**.

When AI agents from different creators, running different models, serving different humans need to collaborate — who is responsible, under what authority, according to what values, and who benefits?

The **Agent Passport System** answers this with cryptographic protocols, not promises.

## What We Ship

| Package | What | Install |
|---------|------|---------|
| [agent-passport-system](https://github.com/aeoess/agent-passport-system) | SDK — 53 core modules + 32 v2 constitutional modules, 1634 tests, Ed25519 identity, delegation chains, cascade revocation, values floor, Merkle attribution, signed communication, policy engine, coordination, agentic commerce, ProxyGateway enforcement, E2E encrypted messaging, data lifecycle governance, Intent Network | `npm i agent-passport-system` |
| [agent-passport-system-mcp](https://github.com/aeoess/agent-passport-mcp) | MCP server — 120 tools across all modules. Works with Claude Desktop, Cursor, Windsurf, any MCP client | `npx agent-passport-system-mcp` |
| [@aeoess/storage-sqlite](https://github.com/aeoess/agent-passport-storage-sqlite) | SQLite persistence — WAL mode, atomic transactions, GDPR tombstoning, signed checkpoints. Gateway state survives restarts. | `npm i @aeoess/storage-sqlite` |
| [aeoess.com](https://aeoess.com) | Protocol docs, threat model (50 adversarial scenarios), comparison pages, signed governance communication, LLM-readable endpoints | [aeoess.com](https://aeoess.com) |

## The Protocol

**53 core modules + 32 v2 constitutional modules. 1634 tests. Zero heavy dependencies. Running code. MCP server included.**

1. **Agent Passport** — Ed25519 cryptographic identity, delegation chains with scope narrowing, cascade revocation
2. **Human Values Floor** — 8 principles (F-001 to F-008), graduated enforcement (inline/audit/warn)
3. **Beneficiary Attribution** — Merkle proofs, contribution tracking through delegation chains
4. **Agent Agora** — Protocol-native signed message feeds with topics and threading
5. **Intent Architecture** — 3-signature policy chain (intent → evaluation → receipt)
6. **Coordination** — Full task lifecycle: brief → assign → evidence → review → deliverable → completion
7. **Integration Wiring** — Cross-layer bridges (commerce→policy, coordination→agora)
8. **Agentic Commerce** — 4-gate checkout pipeline, human approval, spend tracking

Plus: Principal Identity, Reputation-Gated Authority (Bayesian trust, 5 tiers), W3C DID & Verifiable Credentials, Google A2A Bridge, EU AI Act Compliance, ProxyGateway Enforcement, E2E Encrypted Messaging, Obligations, Governance Provenance, Identity Continuity & Key Rotation, Receipt Ledger, Feasibility Linting, Precedent Control, Bounded Escalation, Oracle Witness Diversity, Data Lifecycle Governance (6 modules), Decision Semantics, Entity Verification, StorageBackend Persistence Layer, and 32 v2 Constitutional Governance modules (separation of powers, circuit breakers, approval fatigue detection, epistemic isolation, blind evaluation, constitutional amendment, and more).

## Persistence (v1.25.0)

Gateway state survives restarts. `StorageBackend` interface with 20 methods. `@aeoess/storage-sqlite` provides production persistence: WAL mode, atomic transactions, GDPR tombstoning, signed checkpoints with external anchoring, startup integrity verification. Receipt bundles for portable, signed export/import.

## Working Group

4 ratified cross-project specs: QSP-1 (encrypted transport), DID Resolution, Entity Verification, Execution Attestation. Collaborating with AgentID, qntm, OATR, ArkForge, AgentNexus.

## Links

- [aeoess.com](https://aeoess.com) — Protocol docs, threat model, comparison
- [llms.txt](https://aeoess.com/llms.txt) — Machine-readable protocol summary
- [llms-full.txt](https://aeoess.com/llms-full.txt) — Complete technical reference
- [Research paper](https://doi.org/10.5281/zenodo.18749779) — "The Agent Social Contract"
- [Faceted Authority Attenuation](https://doi.org/10.5281/zenodo.19260073) — Product lattice model for AI agent governance (March 27, 2026)
- [Dev log](https://aeoess.com/blog.html) — Day-by-day build record

## License

Apache-2.0 — Copyright 2024-2026 Tymofii Pidlisnyi
