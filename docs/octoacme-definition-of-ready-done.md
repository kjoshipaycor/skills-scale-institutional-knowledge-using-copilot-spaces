# OctoAcme — Definition of Ready & Definition of Done

## Purpose
Establish shared, team-agreed criteria for when a backlog item is ready to be worked on (Definition of Ready) and when a piece of work is considered complete (Definition of Done). Using both consistently reduces rework, prevents items from entering sprints prematurely, and ensures releases meet quality standards.

> **Owners:** Defined by the full delivery team (PdM, PM, EM, QA, Developers) and facilitated by the Scrum Master. Review and update these definitions at each major retrospective.
>
> See also: [RACI Matrix](octoacme-raci-matrix.md) for who approves DoR/DoD changes.

---

## Definition of Ready (DoR)

A backlog item is **Ready** to be pulled into a sprint when ALL of the following are true:

### User Story / Feature Items

- [ ] User story is written in a standard format: _"As a [persona], I want [action], so that [benefit]."_
- [ ] Acceptance criteria are clear, testable, and agreed upon by PdM, QA, and the development team
- [ ] Business Analyst or PdM has reviewed and confirmed requirements are unambiguous
- [ ] UX designs or wireframes are available for UI-facing work (or explicitly noted as not required)
- [ ] Dependencies on other teams or services are identified and tracked
- [ ] Security or compliance requirements have been identified (flagged by Security/Compliance if applicable)
- [ ] Work item is estimated (story points or T-shirt size) by the development team
- [ ] Item is prioritized and ranked in the backlog by the Product Manager
- [ ] No unresolved blockers exist at the time of sprint planning

### Bug / Defect Items

- [ ] Steps to reproduce are documented
- [ ] Expected vs. actual behavior is clearly stated
- [ ] Severity and priority are assigned (QA or PM)
- [ ] Affected version / environment is identified

### DoR Checklist Usage
Use this checklist during **backlog refinement** sessions. Items that do not meet DoR should be refined before the next sprint planning, not pulled into the sprint.

---

## Definition of Done (DoD)

A work item is **Done** when ALL of the following criteria are met:

### Development

- [ ] Code is implemented according to acceptance criteria
- [ ] Code is reviewed and approved by at least one peer (Engineering Manager or designated reviewer)
- [ ] All automated tests (unit, integration) pass in CI
- [ ] No new linting or static analysis errors introduced
- [ ] Security scanning in CI shows no new critical or high-severity vulnerabilities

### Quality Assurance

- [ ] QA has executed the agreed test plan for the item
- [ ] All acceptance criteria are verified and signed off by QA
- [ ] Any defects found during QA are resolved or explicitly deferred with stakeholder agreement
- [ ] Regression tests have been run (or scope of regression is documented)

### Documentation & Communication

- [ ] Code-level documentation (comments, README updates) is complete where needed
- [ ] User-facing changes are captured in the release notes draft
- [ ] Any impacted process docs are updated

### Deployment

- [ ] Feature is deployed to the staging environment and verified
- [ ] Feature is behind a feature flag if it is not yet ready for all users (when applicable)
- [ ] Rollback steps are documented if the feature requires special handling

### Acceptance

- [ ] Product Manager has accepted the implementation against the defined success criteria
- [ ] For compliance-sensitive features: Security/Compliance sign-off is obtained

### DoD Checklist Usage
Use this checklist as the PR description template and during **sprint review** to confirm items before marking them done on the project board.

---

## DoR / DoD at Each Lifecycle Stage

| Stage | DoR in use? | DoD in use? |
|---|---|---|
| Initiation | – | One-pager review checklist (see [Project Initiation](octoacme-project-initiation.md)) |
| Planning | ✅ Backlog refinement | ✅ DoD agreed and documented |
| Execution | ✅ Sprint planning gate | ✅ PR and sprint review gate |
| Release | – | ✅ Release readiness checklist (see [Release & Deployment](octoacme-release-and-deployment.md)) |
| Retrospective | – | ✅ Action item DoD: owner, due date, success criteria |

---

## Related Documents

- [RACI Matrix](octoacme-raci-matrix.md)
- [Roles & Personas](octoacme-roles-and-personas.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
