# OctoAcme Project Management Docs

## Overview

This README is the central entry point for OctoAcme's project management process documentation. It provides a brief summary of our approach, key principles, and direct links to each core process guide so that new teammates and stakeholders can quickly find the resource they need.

## Project Management Practices Summary

OctoAcme runs projects with a lightweight but explicit end-to-end lifecycle and a consistent set of artifacts to keep work aligned and measurable. Work starts in **Initiation**, where the team validates the business need and authorizes effort via a **Project One-pager** (problem, SMART goal/objective, success metrics), a stakeholder list with a communication plan, a high-level timeline and milestones, initial risks and dependencies, and resourcing assumptions. A clear decision gate ("approve to move into planning") ensures projects only proceed once success metrics, stakeholder priority, and team availability are confirmed. From there, **Planning** converts the approved initiative into a prioritized and estimated backlog of shippable increments, with explicit **acceptance criteria** and a **Definition of Done (DoD)**, plus a release timeline and milestone map.

Day-to-day **Execution & Tracking** emphasizes iterative delivery with strong visibility. Teams use a project board with a standard flow of **Backlog → Ready → In Progress → In Review → QA → Done**, and maintain a steady rhythm of **daily standups**, a **weekly delivery sync**, and demos at the end of each sprint or milestone. Engineering execution is reinforced through a PR workflow that prefers small, focused PRs, requires linking issues and acceptance criteria in the PR description, runs CI checks (tests, lint, security scanning) before review, and requires at least one approval before merge. Progress is measured using delivery signals like velocity/burndown alongside the success metrics defined in the one-pager.

Roles and ownership are intentionally explicit to reduce ambiguity and improve accountability. The named **Project Manager (PM)** handles delivery coordination, schedules, risk and dependency management, meeting facilitation, documentation, and cross-team communications. The **Product Manager (PdM)** owns problem definition, success metrics, prioritization, trade-offs, and measuring impact. **Developers** design, build, and test features while surfacing technical risks; **QA/Testing** validates quality and acceptance criteria; and **Stakeholders** provide inputs and approvals. Communication and quality assurance are treated as ongoing practices: a defined cadence (weekly PM+PdM alignment, standups, monthly stakeholder updates) keeps everyone informed, while risks are tracked in a **Risk Register** with a clear escalation path. Quality is enforced through DoD, unit and integration tests, CI pipelines, security scanning, end-to-end smoke tests before release, and a post-release **blameless retrospective** that produces owned, time-bound action items tracked back into the backlog for continuous improvement.

## Available Process Docs

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](octoacme-roles-and-personas.md)
