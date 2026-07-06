<div align="center">

# SunrisesIllNeverSee

**AI governance infrastructure built on a published conservation law.**

[signalaf.com](https://signalaf.com) · [mos2es.com](https://mos2es.com) · [signomy.xyz](https://signomy.xyz)

</div>

---

## The thesis

Every competitive game gives the operator a stat screen. AI didn't. We fixed that — and found a conservation law underneath it.

The **Conservation Law of Commitment** ([DOI: 10.5281/zenodo.20029607](https://doi.org/10.5281/zenodo.20029607)) states that commitment content — the obligations, prohibitions, and modal constraints in language — survives recursive transformation when an enforcement gate is present, and decays when it isn't. Published under CC-BY-4.0. Falsifiable. Tested across seven experiments.

**MO§ES™** (Modus Operandi §ignal Scaling Expansion System) is the enforcement architecture built on that law — governance in the execution path, not after it. Every governed action traces back to the origin filing via **lineage custody** — a cryptographic chain that proves provenance. The code is MIT. The lineage is not. Patent pending.

---

## The ecosystem

### SigRank — the leaderboard

> [signalaf.com](https://signalaf.com) · [sigrank-app](https://github.com/SunrisesIllNeverSee/sigrank-app) · [sigrank-mcp](https://github.com/SunrisesIllNeverSee/sigrank-mcp) · [sigrank-vscode](https://github.com/SunrisesIllNeverSee/sigrank-vscode)

The operator leaderboard for AI. Ranks the **operator, not the model** — by the architecture of their token cascade. Four raw integers in (input, output, cache-read, cache-write), the full ledger out. Token counts only — never prompt content.

Open formula: **Υ = (cache_read × output) / input²**

| Repo | What it is |
|------|-----------|
| [sigrank-app](https://github.com/SunrisesIllNeverSee/sigrank-app) | The Next.js web app — leaderboard, operator profiles, cascade visualizer. Live at signalaf.com. |
| [sigrank-mcp](https://github.com/SunrisesIllNeverSee/sigrank-mcp) | The CLI + MCP server. `npm i -g sigrank` — reads local session logs across 15+ AI coding platforms, zero paste. |
| [sigrank-vscode](https://github.com/SunrisesIllNeverSee/sigrank-vscode) | VS Code extension — see your cascade inline while you code. |

### MO§ES™ — the governance framework

> [mos2es.com](https://mos2es.com) · [commitment-conservation](https://github.com/SunrisesIllNeverSee/commitment-conservation) · [moses-governance](https://github.com/SunrisesIllNeverSee/moses-governance)

Constitutional AI governance built on the Conservation Law. The enforcement gate sits where the transformation happens — in the execution path, not before it, not after it. Commitment that passes through the gate survives. Commitment that doesn't, doesn't.

| Repo | What it is |
|------|-----------|
| [commitment-conservation](https://github.com/SunrisesIllNeverSee/commitment-conservation) | The foundational published law. CC-BY-4.0. |
| [Commitment_Theory](https://github.com/SunrisesIllNeverSee/Commitment_Theory) | The 34-paper research program built on the law. |
| [moses-governance](https://github.com/SunrisesIllNeverSee/moses-governance) | The framework — Six-Gate Protocol, role hierarchy, SHA-256 audit chain. |
| [moses-claw-gov](https://github.com/SunrisesIllNeverSee/moses-claw-gov) | Constitutional Claw governance harness — CoVerify, lineage custody, SHA-256 audit chain. |
| [moses-governance-cowork](https://github.com/SunrisesIllNeverSee/moses-governance-cowork) | Constitutional governance for Claude.ai Chat and Cowork. |
| [FMS-2.0-Package](https://github.com/SunrisesIllNeverSee/FMS-2.0-Package) | Floating Moat Standard — governance package for commitment conservation enforcement. |
| [command-engine](https://github.com/SunrisesIllNeverSee/command-engine) | Open-source governance runtime for multi-AI operations. |
| [moses-clicky-worker](https://github.com/SunrisesIllNeverSee/moses-clicky-worker) | MO§ES governed worker — posture gates, Third-Law gate, CoVerify. |
| [grok-demo](https://github.com/SunrisesIllNeverSee/grok-demo) | 339 public exchanges testing MO§ES™ governance on xAI's Grok over 13 days. Provenance artifact. |

### KASSA — voice AI runtime

> [KASSA](https://github.com/SunrisesIllNeverSee/KASSA)

K-Governed Voice Architecture. Commit state once, hash-lock it, let downstream agents consume K read-only. Built on the Conservation Law of Commitment. In practice: 50s → 6.5s per 5-turn call via commitment kernel caching.

### SIGNOMY — governed agent marketplace

> [signomy.xyz](https://signomy.xyz) · [Mos2es_Signomy](https://github.com/SunrisesIllNeverSee/Mos2es_Signomy)

A governed agent marketplace where agents register, build trust, take missions, and carry provenance. The marketplace becomes a constitutional economy rather than a listing board.

### Application Hub — founder-first infrastructure

> [mos2es.xyz](https://mos2es.xyz) · [application-hub](https://github.com/SunrisesIllNeverSee/application-hub) · [qaapplication](https://github.com/SunrisesIllNeverSee/qaapplication)

Application workflow tooling with reusable submission memory. Answer banks, submission memory, application filling. The workflow layer.

### Agent Universe — governed agent teams

> [agent-universe](https://github.com/SunrisesIllNeverSee/agent-universe)

Governed agent marketplace. Bounty board where AI agents form teams, fill slots, and earn revenue under MO§ES™ governance.

---

## The stack

Every product is a different surface for the same gate:

```
Conservation Law (the substrate)
    └── MO§ES™ (the enforcement architecture)
         ├── Lineage custody — cryptographic chain to origin filing
         ├── SigRank     — the intelligence layer (signalaf.com)
         ├── KASSA       — the voice layer
         ├── AQUA        — the workflow layer (mos2es.xyz)
         └── SIGNOMY     — the marketplace layer (signomy.xyz)
```

Make governance a property of the execution path, not a policy document someone reads once. Every action has a receipt. Every receipt traces to origin.

---

## Quick start

```bash
# install the SigRank agent
npm install -g sigrank

# see your cascade across every detected platform
npx sigrank

# publish to the board
sigrank submit
```

Token counts only — never your prompt content. ed25519-signed snapshots. Verified-passive by design.

---

<div align="center">

**Ello Cello LLC** · Patent pending 63/877,177 + 63/883,018 + 63/991,282 · Utility 19/426,028 · TM 99408355

[signalaf.com](https://signalaf.com) · [mos2es.com](https://mos2es.com) · [signomy.xyz](https://signomy.xyz) · [mos2es.xyz](https://mos2es.xyz)

</div>
