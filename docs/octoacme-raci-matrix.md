# OctoAcme — RACI Responsibility Matrix

## Purpose
Map every common project activity and artifact to the roles that are **R**esponsible, **A**ccountable, **C**onsulted, or **I**nformed. Use this matrix to eliminate ambiguity, prevent gaps, and support onboarding.

## RACI Key

| Code | Meaning |
|------|---------|
| **R** | **Responsible** — does the work |
| **A** | **Accountable** — owns the outcome; only one per row |
| **C** | **Consulted** — provides input before the work is done |
| **I** | **Informed** — notified after decisions or completion |

## Role Abbreviations

| Abbreviation | Role |
|---|---|
| PM | Project Manager |
| PdM | Product Manager |
| Dev | Developer(s) |
| QA | QA / Testing |
| EM | Engineering Manager / Tech Lead |
| SM | Scrum Master / Agile Coach |
| UX | UX Designer / Researcher |
| RM | Release Manager |
| BA | Business Analyst |
| DA | Data Analyst |
| Sec | Security / Compliance |
| Stk | Stakeholders |

---

## Initiation

| Activity / Artifact | PM | PdM | Dev | QA | EM | SM | UX | RM | BA | DA | Sec | Stk |
|---|---|---|---|---|---|---|---|---|---|---|---|---|
| Draft Project One-pager | R | A | C | – | C | – | C | – | C | – | – | C |
| Define success metrics | C | A | – | – | – | – | – | – | C | R | – | C |
| Stakeholder identification | R | A | – | – | – | – | – | – | C | – | – | I |
| Go / No-go decision | C | A | – | – | C | – | – | – | C | C | C | R |
| Initial risk identification | R | C | C | – | C | – | – | – | C | – | C | I |

---

## Planning

| Activity / Artifact | PM | PdM | Dev | QA | EM | SM | UX | RM | BA | DA | Sec | Stk |
|---|---|---|---|---|---|---|---|---|---|---|---|---|
| Backlog creation & prioritization | C | A | C | C | C | C | C | – | R | – | – | I |
| Requirements elicitation | C | A | C | – | C | – | C | – | R | – | – | C |
| Acceptance criteria authoring | C | C | C | C | – | – | C | – | R | – | – | – |
| Definition of Ready review | C | C | C | R | C | A | C | – | C | – | – | – |
| Definition of Done approval | C | C | R | R | A | C | C | – | C | – | C | I |
| Release plan & milestone map | A | C | C | C | C | – | – | R | – | – | – | I |
| Risk register population | R | C | C | C | C | – | – | C | C | – | C | I |
| Decision log setup | A | C | – | – | – | – | – | – | C | – | – | I |
| UX design & prototyping | – | C | C | – | – | – | A | – | C | – | – | I |
| Test plan drafting | C | C | C | A | C | – | – | C | C | – | – | – |
| Security requirements review | C | C | – | – | C | – | – | – | – | – | A | I |

---

## Execution

| Activity / Artifact | PM | PdM | Dev | QA | EM | SM | UX | RM | BA | DA | Sec | Stk |
|---|---|---|---|---|---|---|---|---|---|---|---|---|
| Feature implementation | – | – | A | – | C | – | – | – | – | – | – | – |
| Code review | – | – | R | – | A | – | – | – | – | – | – | – |
| Security code review | – | – | C | – | C | – | – | – | – | – | A | – |
| QA test execution | – | – | C | A | – | – | – | – | – | – | – | – |
| Defect triage | C | C | R | A | C | – | – | – | – | – | – | – |
| Blocker escalation | A | C | R | C | C | R | – | – | – | – | – | I |
| Sprint facilitation | C | C | C | C | C | A | – | – | – | – | – | – |
| Status reporting | A | I | I | I | I | C | – | I | – | I | I | I |
| Risk register updates | A | C | C | C | C | – | – | – | – | – | C | I |
| Metric dashboards | C | C | C | – | C | – | – | – | – | A | – | I |

---

## Release

| Activity / Artifact | PM | PdM | Dev | QA | EM | SM | UX | RM | BA | DA | Sec | Stk |
|---|---|---|---|---|---|---|---|---|---|---|---|---|
| Release readiness sign-off | C | C | C | R | R | – | – | A | – | – | R | I |
| Deployment execution | – | – | C | – | C | – | – | A | – | – | – | – |
| Smoke tests (post-deploy) | – | – | C | R | – | – | – | A | – | – | – | – |
| Release notes authoring | C | C | C | C | C | – | – | A | – | – | – | I |
| Release announcement | C | I | – | – | – | – | – | A | – | – | – | I |
| Rollback decision | C | C | C | C | A | – | – | R | – | – | – | I |
| Security scan sign-off | C | – | C | – | C | – | – | R | – | – | A | – |

---

## Retrospective & Continuous Improvement

| Activity / Artifact | PM | PdM | Dev | QA | EM | SM | UX | RM | BA | DA | Sec | Stk |
|---|---|---|---|---|---|---|---|---|---|---|---|---|
| Retrospective facilitation | C | C | C | C | C | A | C | C | – | – | – | – |
| Action item definition | C | C | C | C | C | R | – | – | – | – | – | – |
| Action item tracking | A | I | I | I | I | R | – | – | – | – | – | – |
| Metric impact review | C | A | – | – | – | – | – | – | – | R | – | I |
| Process improvement proposals | C | C | C | C | C | A | C | C | C | C | C | – |

---

## Related Documents

- [Roles & Personas](octoacme-roles-and-personas.md)
- [Definition of Ready / Done](octoacme-definition-of-ready-done.md)
- [Risk Register Template](octoacme-risk-register-template.md)
- [Decision Log Template](octoacme-decision-log-template.md)
- [Project Management Overview](octoacme-project-management-overview.md)
