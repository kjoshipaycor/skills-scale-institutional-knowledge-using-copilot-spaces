# OctoAcme Project Management Docs

## Overview

This README serves as the central entry point for OctoAcme's project management process documentation. OctoAcme follows an iterative, customer-first delivery model built on clear ownership, transparent communication, and data-informed decisions. Projects move through five well-defined stages:

1. **Initiation** – validate the business need, align stakeholders, and produce a Project One-pager with SMART goals and success metrics.
2. **Planning** – break work into shippable increments, prioritize the backlog, define the Definition of Done, and build a milestone-based release plan.
3. **Execution** – build and test in short sprints tracked on a shared project board.
4. **Release** – deploy through an automated pipeline with pre-release smoke tests, rollback plans, and post-deploy verification.
5. **Close & Retrospective** – capture learnings and convert them into backlog action items for continuous improvement.

## Roles & Personas

OctoAcme projects are staffed with clearly defined roles to establish ownership and accountability at every stage:

- **Project Manager (PM)** – owns delivery coordination, schedules, risk registers, and cross-team communication.
- **Product Manager (PdM)** – defines the problem statement, prioritizes the roadmap, and validates outcomes against success metrics.
- **Developers** – implement features to acceptance criteria, write and maintain tests, and participate actively in design and code reviews.
- **QA** – validates quality and acceptance criteria through unit, integration, and end-to-end smoke tests.
- **Stakeholders** – provide inputs, approvals, and business context throughout the lifecycle, from initial go/no-go decisions through milestone reviews and release announcements.
- **Scrum Master / Agile Coach** – facilitates agile ceremonies, removes impediments, and coaches the team on process health.
- **UX Designer / Researcher** – designs and validates user experiences; translates user insights into actionable designs.
- **Release Manager** – plans, coordinates, and oversees all production deployments and the release calendar.
- **Data Analyst** – defines key metrics, builds dashboards, and provides data-driven insights to support decision-making.
- **Business Analyst** – elicits and documents requirements, maps workflows, and bridges business and technology teams.
- **Engineering Manager / Tech Lead** – provides technical leadership, people management, and architectural guidance.
- **Security / Compliance** – ensures security and regulatory requirements are met throughout the delivery lifecycle.

See [Roles & Personas](octoacme-roles-and-personas.md) for detailed responsibilities, goals, and interaction points for each role.

## Communication & Risk Management

OctoAcme maintains a structured communication cadence to keep all parties aligned:

- **Daily standups** (15 minutes) – focused on progress and blockers.
- **Weekly PM + PdM sync** – reviews progress, surfaces risks, and updates the risk register.
- **Monthly stakeholder updates** – reports on milestones, metrics, and upcoming decisions.

Risks are tracked in a Risk Register (ID, impact, likelihood, owner, mitigation) and reviewed every week. Blockers escalate from team-level triage → PM → Product Lead → Sponsor, with a dedicated security incident runbook for security-related issues. All project status is maintained in a single source of truth—the project README or release doc—so every stakeholder has consistent, up-to-date information.

## Quality Assurance & Release Practices

Quality is enforced throughout the development lifecycle. All pull requests are kept small (≤ 400 lines where possible), must include issue links and acceptance criteria, and require at least one approval after passing automated CI checks that include unit tests, integration tests, linting, and security scanning. Before any release, acceptance criteria must be fully met, CI and security scans must pass, release notes must be drafted, and smoke tests must be prepared and run in a staging environment. Deployments follow an automated pipeline with post-deploy verification and a documented rollback/incident playbook. After each sprint, release, or significant incident, the team holds a **retrospective** to surface what went well and what can improve, producing 2–3 prioritized action items tracked in the backlog to drive continuous improvement.

---

## Process Documents

| Document | Description |
|---|---|
| [Project Management Overview](octoacme-project-management-overview.md) | Principles, core roles, key artifacts, and lifecycle at a glance |
| [Project Initiation Guide](octoacme-project-initiation.md) | How to validate and authorize new work, and create a Project One-pager |
| [Project Planning](octoacme-project-planning.md) | Turning an approved initiative into a backlog, release plan, and milestones |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Day-to-day workflows, PR conventions, quality practices, and blocker escalation |
| [Risk Management & Communication](octoacme-risks-and-communication.md) | Risk register, stakeholder communication templates, and escalation paths |
| [Release & Deployment Guide](octoacme-release-and-deployment.md) | Pre-release checklist, deployment pipeline, rollback, and release notes |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Running retros, tracking action items, and building a culture of improvement |
| [Roles & Personas](octoacme-roles-and-personas.md) | Detailed responsibilities and communication norms for each project role |
| [RACI Matrix](octoacme-raci-matrix.md) | Role-to-activity responsibility mapping across all lifecycle stages |
| [Definition of Ready / Done](octoacme-definition-of-ready-done.md) | Shared criteria for backlog readiness and completion |
| [Risk Register Template](octoacme-risk-register-template.md) | Template and guidance for tracking, scoring, and escalating risks |
| [Decision Log Template](octoacme-decision-log-template.md) | Template for recording significant project decisions and their rationale |
