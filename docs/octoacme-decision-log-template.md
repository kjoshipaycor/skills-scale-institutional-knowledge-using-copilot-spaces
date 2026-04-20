# OctoAcme — Decision Log Template

## Purpose
Record significant project decisions—what was decided, why, who made the call, and what alternatives were considered. A decision log reduces second-guessing, supports onboarding, and creates an audit trail that informs future retrospectives and planning cycles.

> **Owner:** Project Manager maintains the log. All roles are encouraged to submit decisions for logging.
>
> See also: [RACI Matrix](octoacme-raci-matrix.md) | [Risk Register Template](octoacme-risk-register-template.md)

---

## What to Log

Log a decision when it is:
- **Significant** – affects scope, timeline, architecture, budget, or team composition
- **Reversible only at cost** – undoing it would require substantial rework
- **Cross-functional** – involves trade-offs across multiple roles or teams
- **Frequently revisited** – team keeps re-debating the same topic

Minor or tactical decisions (e.g., variable naming, minor UI tweaks) do not need to be logged.

---

## How to Use This Template

1. Add a new entry for each loggable decision.
2. Complete all fields at the time the decision is made or immediately after.
3. Link related risks in the [Risk Register](octoacme-risk-register-template.md) when applicable.
4. Review open decisions at weekly PM syncs; mark superseded or reversed decisions appropriately.

---

## Decision Log

| ID | Date | Decision | Context / Problem | Options Considered | Decision Rationale | Decision Maker(s) | Consulted | Status | Related Risks / Links |
|---|---|---|---|---|---|---|---|---|---|
| D-001 | YYYY-MM-DD | _What was decided_ | _Why a decision was needed_ | _Option A; Option B; Option C_ | _Why this option was chosen_ | _Role or name_ | _Roles consulted_ | Open / Superseded / Reversed | _R-XXX or link_ |
| D-002 | | | | | | | | | |

---

## Decision Status Definitions

| Status | Meaning |
|---|---|
| **Open** | Decision stands; currently in effect |
| **Superseded** | A newer decision (reference by ID) replaces this one |
| **Reversed** | The decision was undone; record reason and date |

---

## Decision Entry Template (expanded)

Use the expanded format below for high-impact decisions where additional detail is warranted:

```
### Decision D-XXX: [Short title]

**Date:** YYYY-MM-DD
**Status:** Open

**Context**
[Describe the situation, problem, or question that required a decision.]

**Options Considered**
1. [Option A] – [Brief pros/cons]
2. [Option B] – [Brief pros/cons]
3. [Option C / Do nothing] – [Brief pros/cons]

**Decision**
[State what was decided clearly and concisely.]

**Rationale**
[Explain why this option was chosen over the alternatives.]

**Decision Maker(s)**
[Names or roles of those who made the final call.]

**Consulted**
[Names or roles of those whose input was sought.]

**Consequences**
[What follow-on actions or implications result from this decision?]

**Related Risks**
[Link to any risk register entries created or updated as a result.]
```

---

## Roles & Responsibilities for Decision Logging

| Role | Responsibility |
|---|---|
| Project Manager | Maintains the log; ensures decisions are captured promptly |
| Product Manager | Accountable for product and scope decisions; initiates log entries for roadmap changes |
| Engineering Manager / Tech Lead | Accountable for architectural and technical decisions |
| Business Analyst | Flags requirements decisions that affect traceability |
| Scrum Master / Agile Coach | Surfaces process decisions that should be logged for transparency |
| All team members | Raise decisions for logging; provide context and rationale |

---

## Related Documents

- [RACI Matrix](octoacme-raci-matrix.md)
- [Risk Register Template](octoacme-risk-register-template.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Project Planning](octoacme-project-planning.md)
- [Roles & Personas](octoacme-roles-and-personas.md)
