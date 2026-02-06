# Decision Log

This directory contains the **Decision Log** (Architecture Decision Records / ADR-like)
for the Agentic Software Team.

The purpose is to keep a **version-controlled, human-readable memory**
of why key decisions were made.

This is NOT agent memory.
This is explicit, auditable state stored as repository artifacts.

---

## Why this exists

Multi-agent workflows fail when:

- decisions are not traceable
- assumptions are forgotten
- agents refactor without understanding intent
- contradictions accumulate over time

Decision logs prevent this by recording:

- what was decided
- why it was decided
- what alternatives were considered
- what risks are acknowledged
- when the decision can be revisited

---

## Rules

1. Only log **meaningful** decisions (irreversible or high-impact)
2. Decisions must be written in plain language
3. Assumptions must be explicit
4. Include alternatives and trade-offs
5. Include a "Revisit" condition when applicable
6. Every decision must have an owner and date

---

## Format

Each decision file uses this template:

- Title
- Status (Proposed / Accepted / Superseded)
- Context
- Decision
- Alternatives considered
- Consequences
- Revisit conditions
- References (optional)

---

## Naming

Files use incremental numbering:

- `0001-...`
- `0002-...`

---

## Relationship to Governance

Decision Log works alongside:

- `/rules/agent-governance.md`
- `/docs/agent-communication-model.md`
- `/docs/agent-memory-policy.md`

Governance defines control.
Decision Log defines traceable rationale.
