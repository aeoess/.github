# AEOESS — Governance for the Agent Economy

AI agents represent companies and people. They spend real money, access sensitive data, negotiate contracts, and talk to other agents. **No one can verify who they are. No one controls what they do. No one can shut them down when things go wrong.**

The **Agent Passport System** is the open protocol that makes every agent accountable. Cryptographic identity, scoped delegation, earned reputation, gateway enforcement, 4-gate commerce, Merkle attribution, institutional governance. 86 modules. 1,656 tests. One npm install.

## What We Ship

| Package | What | Install |
|---------|------|---------|
<<<<<<< Updated upstream
| [agent-passport-system](https://github.com/aeoess/agent-passport-system) | SDK — 54 core + 32 v2 constitutional modules. Ed25519 identity, delegation, revocation, reputation, commerce, enforcement, data governance, encrypted messaging | `npm i agent-passport-system` |
| [agent-passport-system-mcp](https://github.com/aeoess/agent-passport-mcp) | MCP server — 121 tools. Works with Claude Desktop, Cursor, Windsurf, any MCP client | `npx agent-passport-system-mcp` |
| [@aeoess/storage-sqlite](https://github.com/aeoess/agent-passport-storage-sqlite) | SQLite persistence — WAL mode, atomic transactions, GDPR tombstoning. Gateway state survives restarts | `npm i @aeoess/storage-sqlite` |
| [Python SDK](https://pypi.org/project/agent-passport-system/) | Python wrapper for the protocol | `pip install agent-passport-system` |
| [aeoess.com](https://aeoess.com) | Protocol docs, working group, threat model, comparison, FAQ, ship log | [aeoess.com](https://aeoess.com) |

## The Protocol

**Identity** — Ed25519 cryptographic passports, delegation chains with monotonic narrowing, cascade revocation. **Reputation** — Bayesian trust scoring, 5 tiers, cryptographic scarring. **Enforcement** — ProxyGateway boundary: scope check, spend limit, values floor, revocation recheck at execution. **Commerce** — 4-gate checkout, human approval, cumulative spend tracking. **Attribution** — Merkle proofs, contribution ledger, settlement. **Institutional** — Charters, offices, approval policies, federation, reserves. **Communication** — E2E encrypted with forward secrecy. **Data governance** — Access receipts, derivation chains, consent revocation, purpose drift detection.
=======
| [agent-passport-system](https://github.com/aeoess/agent-passport-system) | SDK — 56 core modules + 32 v2 constitutional modules, 1707 tests, Ed25519 identity, delegation chains, cascade revocation, values floor, Merkle attribution, signed communication, policy engine, coordination, agentic commerce, ProxyGateway enforcement, E2E encrypted messaging, data lifecycle governance, Intent Network | `npm i agent-passport-system` |
| [agent-passport-system-mcp](https://github.com/aeoess/agent-passport-mcp) | MCP server — 121 tools across all modules. Works with Claude Desktop, Cursor, Windsurf, any MCP client | `npx agent-passport-system-mcp` |
| [@aeoess/storage-sqlite](https://github.com/aeoess/agent-passport-storage-sqlite) | SQLite persistence — WAL mode, atomic transactions, GDPR tombstoning, signed checkpoints. Gateway state survives restarts. | `npm i @aeoess/storage-sqlite` |
| [aeoess.com](https://aeoess.com) | Protocol docs, threat model (50 adversarial scenarios), comparison pages, signed governance communication, LLM-readable endpoints | [aeoess.com](https://aeoess.com) |

## The Protocol

**56 core modules + 32 v2 constitutional modules. 1707 tests. Zero heavy dependencies. Running code. MCP server included.**
>>>>>>> Stashed changes

## Framework Integration

Works alongside any agent framework. Adapters for [CrewAI](https://github.com/aeoess/agent-passport-system/blob/main/examples/crewai-governance.ts), [LangChain](https://github.com/aeoess/agent-passport-system/blob/main/src/adapters/langchain.ts), [Google ADK](https://github.com/aeoess/agent-passport-system/blob/main/src/adapters/adk.ts), and [A2A](https://github.com/aeoess/agent-passport-system/blob/main/src/adapters/a2a.ts).

## Standards

- **IETF Internet-Draft**: draft-pidlisnyi-aps-00
- **WG ratified specs**: QSP-1 (encrypted transport), DID Resolution, Entity Verification, Execution Attestation
- **Papers**: [The Agent Social Contract](https://doi.org/10.5281/zenodo.18749779) · [Monotonic Narrowing](https://doi.org/10.5281/zenodo.18932404) · [Faceted Authority Attenuation](https://doi.org/10.5281/zenodo.19260073)
- **Cited by**: [PDR in Production](https://doi.org/10.5281/zenodo.19323172) (Nanook & Gerundium, 2026) — independent validation of APS Bayesian model + structuralVerdict/trustVerdict separation

## Working Group

Building interoperability standards with AgentID, qntm, OATR, ArkForge, Guardian, Kanoniv, Network AI. [Join →](https://aeoess.com/working-group.html)

## Links

- [aeoess.com](https://aeoess.com) — Governance for the Agent Economy
- [llms.txt](https://aeoess.com/llms.txt) — Machine-readable protocol summary
- [llms-full.txt](https://aeoess.com/llms-full.txt) — Complete technical reference (for AI agents)
- [Dev log](https://aeoess.com/blog.html) — Day-by-day build record, started Feb 18, 2026
- [Working Group](https://aeoess.com/working-group.html) — Ratified specs, participants, how to join
- [The Agent Times](https://theagenttimes.com) — First production deployment of APS governance

## License

Apache-2.0 — Copyright 2024-2026 Tymofii Pidlisnyi
