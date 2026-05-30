# Changelog

All notable changes to The Agentic Product Standard are documented here.
The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/).

## [1.1.0] — 2026-05-30

### Added
- **[`AGENT_STANDARD.md`](AGENT_STANDARD.md)** — the single-agent operational standard: orchestrator plus eight sub-skills, Agent/Tool Contracts, runner flow, permission tiers (P0–P6), durable execution, the Definition of Done, and an Evidence & Sources appendix.
- **`templates/`** — framework-agnostic artifact-contracts: Agent Contract, Tool Contract, input/output schemas (TS + Python), message envelope, handoff contract, context pack, trace event, eval case + judge-calibration shapes, and a drop-in `CLAUDE.md`.
- **`agent-builder`** Claude Code skill — the single-agent track; reuses the ten existing sub-skills.

### Changed
- README now documents two tracks (build one agent / design a product); install copies both skills.
- CONTRIBUTING now permits framework-agnostic artifact-contracts in `templates/` (framework-specific code still excluded).

## [1.0.0] — 2026-05-29

### Added
- The canonical standard ([`STANDARD.md`](STANDARD.md)) in English.
- The five principles, the Autonomy Ladder (L0–L4), the five composition patterns, the single-vs-multi-agent decision, the seven-layer harness, and the Cycle of Trust.
- The 12-point production-readiness Definition of Done.
- The three-level eval pyramid and judge-calibration discipline (Husain/Shankar).
- The 12 anti-patterns and the 12-week build roadmap.
- The `agentic-product-architect` Claude Code skill set: one master skill routing to ten sub-skills (architecture, context, harness, tools/MCP, memory, durable execution, evals, framework selection, production readiness, antipatterns review).
