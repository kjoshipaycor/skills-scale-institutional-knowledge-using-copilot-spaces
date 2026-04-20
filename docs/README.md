# OctoAcme Project Management Docs

## Overview

This README serves as the central entry point for OctoAcme's project management process documentation. OctoAcme follows an iterative, customer-first delivery model built on clear ownership, transparent communication, and data-informed decisions. Projects move through five well-defined stages: **Initiation** (validating the business need, aligning stakeholders, and producing a Project One-pager with SMART goals and success metrics), **Planning** (breaking work into shippable increments, prioritizing the backlog, defining the Definition of Done, and building a milestone-based release plan), **Execution** (building and testing in short sprints tracked on a shared project board), **Release** (deploying through an automated pipeline with pre-release smoke tests, rollback plans, and post-deploy verification), and **Close & Retrospective** (capturing learnings and converting them into backlog action items for continuous improvement).

## Roles & Personas

OctoAcme projects are staffed with clearly defined roles. The **Project Manager (PM)** owns delivery coordination, schedules, risk registers, and cross-team communication. The **Product Manager (PdM)** defines the problem statement, prioritizes the roadmap, and validates outcomes against success metrics. **Developers** implement features to acceptance criteria, write and maintain tests, and participate actively in design and code reviews. **QA** validates quality and acceptance criteria through unit, integration, and end-to-end smoke tests. **Stakeholders** provide inputs, approvals, and business context throughout the lifecycle—from initial go/no-go decisions at the end of Initiation through milestone reviews and release announcements.

## Communication & Risk Management

OctoAcme maintains a structured communication cadence to keep all parties aligned. The delivery team holds **daily standups** (15 minutes) focused on progress and blockers, while the PM and PdM meet in a **weekly sync** to review progress, surface risks, and update the risk register. **Monthly stakeholder updates** report on milestones, metrics, and upcoming decisions. Risks are tracked in a Risk Register (ID, impact, likelihood, owner, mitigation) and reviewed every week; blockers escalate from team-level triage → PM → Product Lead → Sponsor, with a dedicated security incident runbook for security-related issues. All project status is maintained in a single source of truth—the project README or release doc—so every stakeholder has consistent, up-to-date information.

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
