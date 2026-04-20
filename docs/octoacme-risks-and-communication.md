# OctoAcme — Risk Management & Communication

## Purpose
Explain how to identify, manage, and communicate risks and dependencies.

> **Related resources:** [Risk Register Template](octoacme-risk-register-template.md) | [Decision Log Template](octoacme-decision-log-template.md) | [RACI Matrix](octoacme-raci-matrix.md) | [Roles & Personas](octoacme-roles-and-personas.md)

## Risk Register
Maintain a simple table with:
- ID
- Description
- Impact (High/Med/Low)
- Likelihood (High/Med/Low)
- Owner
- Mitigation plan
- Status

> Use the **[Risk Register Template](octoacme-risk-register-template.md)** for the full table format, scoring matrix, and escalation thresholds.

## Risk Lifecycle
- Identify: during planning and ongoing execution
- Assess: estimate impact and likelihood
- Mitigate: reduced via actions, contingency plans
- Monitor: review at weekly syncs and update status

## Stakeholder Communication
- Identify stakeholder groups and communication needs (e.g., engineering, sales, support)
- Provide regular updates (weekly or milestone-based)
- Use a single source of truth (project README or release doc) for status

## Communication Templates
Weekly Status Template:
- Progress this week:
- Next steps:
- Risks & blockers:
- Ask / decisions needed:

Incident Communication
- Triage summary
- Actions being taken
- Expected timeline
- Post-incident blameless retrospective scheduled

## Escalation Paths
- Team-level -> PM -> Product Lead -> Sponsor
- For security incidents, follow the security incident runbook and notify Security on-call
- Record key risk decisions and escalation outcomes in the [Decision Log](octoacme-decision-log-template.md)
