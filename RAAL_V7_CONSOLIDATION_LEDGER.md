# RAAL V7 Consolidation Ledger

**Canonical version:** 7.0.0
**Purpose:** Record the source, status, and precedence of the V7 canonical document set.

## Source and provenance

The request for this consolidation referred to supplied whitepaper and ledger content, but no such source text was included in the issue payload or repository. The V7 documents added here therefore consolidate the tracked repository documentation; they are not represented as a verbatim transcription of absent source material.

No historical V1–V6 release artifacts were available in the repository history reviewed for this document set. The repository identifies its architecture as V7.0; this ledger uses **7.0.0** as the canonical artifact-set version and does not infer additional historical lineage.

## Canonical artifacts

| Artifact | Authority and scope |
|---|---|
| [`RAAL_WHITEPAPER_V7.md`](RAAL_WHITEPAPER_V7.md) | Canonical V7 architecture, principles, intended lifecycle, governance, safety, and current implementation-status description. |
| [`RAAL_V7_CONSOLIDATION_LEDGER.md`](RAAL_V7_CONSOLIDATION_LEDGER.md) | Provenance, source mapping, lineage limits, and artifact precedence. |
| [`README.md`](README.md) | Repository landing page and top-level links to the canonical V7 artifacts. |

The whitepaper defines the canonical architecture narrative. This ledger defines the document set's provenance and precedence. Neither overrides implementation evidence from source code and tests.

## Consolidated repository sources

| Existing source | Content retained in the V7 set |
|---|---|
| [`README.md`](README.md) | Project vision, useful autonomy under human authority, and intended operating cycle. |
| [`architecture/ARCHITECTURE.md`](architecture/ARCHITECTURE.md) | Organism model, canonical layers, agent lifecycle, evolution, recovery, distributed nodes, and governance zones. |
| [`governance/GOVERNANCE.md`](governance/GOVERNANCE.md) | Human authority, governance principles and zones, evolution controls, emergency control, and capability-status vocabulary. |
| [`docs/architecture.md`](docs/architecture.md) | Current simulation scaffold components, data flow, extension points, and runtime safety limits. |
| [`docs/overview.md`](docs/overview.md) | Current implemented scope and explicit non-capabilities. |
| [`docs/safety.md`](docs/safety.md) | Simulation-only operating model and safety boundaries. |

## Status and interpretation

- Architectural layers and autonomous lifecycle flows are documented design intent, not claims of live operation.
- The current implementation is a Python simulation scaffold: planning is deterministic and bounded, execution records in-memory events, and no real-world actions are performed.
- Status claims must preserve the governance vocabulary: **DOCUMENTED**, **IMPLEMENTED**, **LIVE**, **DEGRADED / PARTIAL**, **NOT IMPLEMENTED**, and **NOT VERIFIED**.
- A document describing a capability is not evidence that the capability is running.

## Canonical naming and navigation

The primary whitepaper and ledger filenames are `RAAL_WHITEPAPER_V7.md` and `RAAL_V7_CONSOLIDATION_LEDGER.md` at the repository root. Root and documentation landing pages link to these names. Earlier or similarly named whitepapers may not supersede these canonical artifacts.
