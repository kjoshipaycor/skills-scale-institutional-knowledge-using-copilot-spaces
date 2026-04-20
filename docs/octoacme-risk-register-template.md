# OctoAcme — Risk Register Template

## Purpose
Track, assess, and manage risks throughout the project lifecycle. A well-maintained risk register keeps the full team aware of potential threats, ensures each risk has a named owner, and documents agreed mitigations so nothing falls through the cracks.

> **Owner:** Project Manager maintains the register. Risk entries are contributed by all roles and reviewed at weekly syncs.
>
> See also: [RACI Matrix](octoacme-raci-matrix.md) | [Risk Management & Communication](octoacme-risks-and-communication.md)

---

## How to Use This Template

1. Copy the table below into your project's risk register (project board, wiki, or dedicated doc).
2. Add a new row for each identified risk.
3. Review the register at every weekly PM sync. Update **Status** and **Mitigation** columns as risks evolve.
4. Close risks when they are resolved or no longer applicable; archive rather than delete so history is preserved.

---

## Risk Register

| ID | Category | Description | Impact | Likelihood | Risk Score | Owner | Mitigation Plan | Contingency | Status | Last Updated |
|---|---|---|---|---|---|---|---|---|---|---|
| R-001 | _e.g., Technical_ | _Brief description of the risk_ | H / M / L | H / M / L | _see scoring below_ | _Role or name_ | _Actions to reduce probability or impact_ | _What we do if the risk materializes_ | Open / Mitigated / Closed | YYYY-MM-DD |
| R-002 | | | | | | | | | | |

### Categories (examples)
- **Technical** – architecture, third-party dependencies, technical debt
- **Resource** – staffing, skill gaps, availability
- **Schedule** – timeline, milestone dependencies
- **Scope** – requirement changes, unclear acceptance criteria
- **Compliance / Security** – regulatory, data privacy, vulnerability
- **External** – vendor, partner, market condition

### Impact & Likelihood Scale

| Level | Impact | Likelihood |
|---|---|---|
| **H** (High) | Significant delay, cost overrun, or quality failure | Likely to occur (>60% probability) |
| **M** (Medium) | Moderate impact on schedule or quality; manageable | Possible (30–60% probability) |
| **L** (Low) | Minor inconvenience; easily absorbed | Unlikely (<30% probability) |

### Risk Score Matrix

| | **H Impact** | **M Impact** | **L Impact** |
|---|---|---|---|
| **H Likelihood** | 🔴 Critical | 🟠 High | 🟡 Medium |
| **M Likelihood** | 🟠 High | 🟡 Medium | 🟢 Low |
| **L Likelihood** | 🟡 Medium | 🟢 Low | 🟢 Low |

---

## Risk Lifecycle

1. **Identify** – Any team member can raise a risk at any time. Capture it in the register promptly.
2. **Assess** – PM and risk owner assign Impact, Likelihood, and Risk Score at the next weekly sync.
3. **Plan Mitigation** – Risk owner documents the mitigation plan and contingency within one week of identification.
4. **Monitor** – Review at every weekly PM sync. Update status and mitigation effectiveness.
5. **Close / Escalate** – Close resolved risks. Escalate Critical/High risks to the sponsor per the escalation path (see [Risk Management & Communication](octoacme-risks-and-communication.md)).

---

## Escalation Thresholds

| Risk Score | Required Action |
|---|---|
| 🔴 Critical | Immediate escalation to Sponsor; mitigation plan required within 24 hours |
| 🟠 High | Escalate to Product Lead and PM; mitigation plan required within one week |
| 🟡 Medium | PM owns mitigation; reviewed at weekly sync |
| 🟢 Low | Logged and monitored; no escalation required |

---

## Roles & Responsibilities for Risk Management

| Role | Responsibility |
|---|---|
| Project Manager | Maintains the register; facilitates weekly risk review |
| Product Manager | Flags scope and market risks; approves scope-change mitigations |
| Engineering Manager / Tech Lead | Identifies and owns technical risks |
| Security / Compliance | Identifies and owns compliance and security risks |
| QA / Testing | Raises quality and testing risks |
| Release Manager | Raises and owns release and deployment risks |
| All team members | Can and should raise new risks at any time |

---

## Related Documents

- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [RACI Matrix](octoacme-raci-matrix.md)
- [Decision Log Template](octoacme-decision-log-template.md)
- [Project Planning](octoacme-project-planning.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
