# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

> **Related resources:** [RACI Matrix](octoacme-raci-matrix.md) | [Definition of Ready / Done](octoacme-definition-of-ready-done.md) | [Risk Register Template](octoacme-risk-register-template.md) | [Decision Log Template](octoacme-decision-log-template.md)

---

## Table of Contents
- [Developers](#developers)
- [Product Managers](#product-managers)
- [Project Managers](#project-managers)
- [QA / Testing](#qa--testing)
- [Stakeholders](#stakeholders)
- [Scrum Master / Agile Coach](#scrum-master--agile-coach)
- [UX Designer / Researcher](#ux-designer--researcher)
- [Release Manager](#release-manager)
- [Data Analyst](#data-analyst)
- [Business Analyst](#business-analyst)
- [Engineering Manager / Tech Lead](#engineering-manager--tech-lead)
- [Security / Compliance](#security--compliance)
- [How these personas are used in the exercise](#how-these-personas-are-used-in-the-exercise)

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

### Interaction Points
- **Product Manager** – receive acceptance criteria, clarify feature intent, and surface technical constraints
- **Project Manager** – report progress, flag blockers, and estimate work items
- **QA/Testing** – hand off features for validation; address defects raised
- **Engineering Manager/Tech Lead** – align on technical approach, code quality standards, and architectural decisions
- **UX Designer** – implement designs and request clarification on interaction details

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

### Interaction Points
- **Project Manager** – align on scope, timeline, and resource trade-offs; resolve prioritization conflicts
- **Developers** – provide requirements, acceptance criteria, and user context
- **Stakeholders** – gather business inputs, communicate roadmap decisions, and validate outcomes
- **UX Designer/Researcher** – incorporate user research insights into backlog prioritization
- **Business Analyst** – collaborate on requirements elicitation and solution design
- **Data Analyst** – define success metrics and review data-driven insights

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

### Interaction Points
- **Product Manager** – align on scope changes, priority shifts, and go/no-go decisions
- **Engineering Manager/Tech Lead** – coordinate on staffing, technical dependencies, and capacity
- **Release Manager** – coordinate deployment scheduling and release readiness sign-off
- **Scrum Master/Agile Coach** – collaborate on process health and impediment resolution
- **Stakeholders** – provide regular status updates and escalate decisions requiring business input

---

## QA / Testing

### Role Summary
QA/Testing engineers validate that features meet acceptance criteria, quality standards, and user expectations before release. They champion quality throughout the delivery lifecycle.

### Responsibilities
- Develop and maintain test plans and test cases aligned to acceptance criteria
- Execute unit, integration, regression, and end-to-end smoke tests
- Log, prioritize, and track defects to resolution
- Contribute to the Definition of Done and Definition of Ready
- Participate in sprint planning and retrospectives to surface quality risks early

### Goals
- Prevent defects from reaching production
- Ensure all acceptance criteria are verifiably met before release
- Continuously improve test coverage and automation

### Typical Communication
- Bug reports and defect triage in the issue tracker
- Test results summaries shared at sprint reviews and pre-release gates
- Collaboration on Definition of Ready/Done (see [Definition of Ready / Done](octoacme-definition-of-ready-done.md))

### Interaction Points
- **Developers** – review acceptance criteria together, report defects, and verify fixes
- **Product Manager** – clarify acceptance criteria and validate feature intent
- **Release Manager** – provide test results sign-off as part of pre-release gates
- **Project Manager** – flag quality risks and testing blockers that may affect release timelines

---

## Stakeholders

### Role Summary
Stakeholders are individuals or groups with a business interest in project outcomes. They provide strategic direction, approve key decisions, and validate that delivered value meets business needs.

### Responsibilities
- Provide business context and priorities during initiation and planning
- Review and approve the Project One-pager and significant scope changes
- Participate in milestone reviews and release announcements
- Make or escalate decisions that require business authority
- Provide timely feedback on delivered features

### Goals
- Ensure delivered outcomes align with business strategy and customer needs
- Stay informed of project progress, risks, and decisions
- Enable the delivery team by resolving blockers that require business authority

### Typical Communication
- Monthly stakeholder updates (or milestone-based briefings)
- Ad-hoc requests for decisions and approvals
- Release announcements and retrospective summaries

### Interaction Points
- **Product Manager** – primary point of contact for roadmap decisions and business-value validation
- **Project Manager** – receive regular status updates and risk escalations
- **Business Analyst** – review requirements and validate business process alignment

---

## Scrum Master / Agile Coach

### Role Summary
The Scrum Master or Agile Coach facilitates agile ceremonies, removes team impediments, and continuously improves team processes. They serve the team rather than directing work.

### Responsibilities
- Facilitate Scrum events (standups, sprint planning, reviews, retrospectives)
- Identify and remove process blockers and organizational impediments
- Coach team members on agile principles and practices
- Shield the team from unplanned interruptions during sprints
- Track and surface process metrics (cycle time, sprint velocity, impediment age)

### Goals
- Maintain a healthy, sustainable team pace
- Continuously improve process efficiency and team satisfaction
- Ensure ceremonies are purposeful and time-boxed

### Typical Communication
- Retrospective facilitation and action item tracking (see [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md))
- Impediment logs and escalations to the Project Manager
- Process health dashboards shared with engineering leadership

### Interaction Points
- **Project Manager** – collaborate on timeline impacts of impediments; escalate blockers that require business or cross-team action
- **Developers** – support in removing day-to-day blockers and protecting sprint commitments
- **Product Manager** – ensure backlog refinement sessions are efficient and acceptance criteria are clear
- **Engineering Manager/Tech Lead** – align on team capacity and technical process improvements

---

## UX Designer / Researcher

### Role Summary
UX Designers and Researchers ensure that features are intuitive, accessible, and meet real user needs. They translate user insights into actionable designs that the development team can implement.

### Responsibilities
- Conduct user research (interviews, usability tests, surveys) to inform design decisions
- Create wireframes, prototypes, and high-fidelity designs
- Define and maintain design systems and interaction patterns
- Participate in backlog refinement to validate user story clarity
- Review implemented features against design intent

### Goals
- Ensure delivered features are usable, accessible, and desirable
- Reduce rework caused by unclear or untested design assumptions
- Create a consistent, high-quality user experience across the product

### Typical Communication
- Design reviews and critiques with Product and Engineering teams
- Usability test reports shared with the Product Manager
- Design handoff documentation (specs, assets) for Developers

### Interaction Points
- **Product Manager** – collaborate on problem framing, user research priorities, and feature definition
- **Developers** – provide design specs and assets; answer implementation questions during development
- **Business Analyst** – align on workflow requirements and user journey maps
- **QA/Testing** – review implementations for fidelity to designs and usability acceptance criteria

---

## Release Manager

### Role Summary
Release Managers plan, coordinate, and oversee all production deployments. They own the release calendar, coordinate cross-team readiness, and ensure every deployment is safe, visible, and reversible.

### Responsibilities
- Maintain the release calendar and communicate deployment windows
- Coordinate release readiness sign-offs from Engineering, QA, and Product
- Manage the deployment pipeline and rollback procedures
- Draft and distribute release notes and deployment announcements
- Drive post-release verification and incident response if issues arise

### Goals
- Release reliably and on schedule with minimal production incidents
- Ensure all stakeholders are informed before, during, and after each release
- Maintain a documented rollback path for every deployment

### Typical Communication
- Pre-release readiness meetings with QA, Engineering, and PM
- Release announcements to stakeholders and support teams
- Post-release incident reports and retrospectives (see [Release & Deployment Guide](octoacme-release-and-deployment.md))

### Interaction Points
- **Project Manager** – align on release timing and confirm scope freeze milestones
- **Developers / Engineering Manager** – confirm code is merged, CI is passing, and release branches are stable
- **QA/Testing** – receive test results sign-off before deployment
- **Security/Compliance** – confirm security scans and compliance checks are complete
- **Stakeholders** – communicate release content, timing, and any customer-facing impacts

---

## Data Analyst

### Role Summary
Data Analysts define key metrics, build dashboards, and translate project and product data into actionable insights that guide decision-making.

### Responsibilities
- Define and instrument key performance indicators (KPIs) and success metrics
- Build and maintain dashboards for project and product health
- Analyze data to surface trends, anomalies, and opportunities
- Provide data-driven input to retrospectives and planning sessions
- Collaborate with engineers to ensure data pipelines are reliable and instrumented

### Goals
- Give teams timely, accurate data to make confident decisions
- Measure the impact of delivered features against defined success metrics
- Identify early signals of risk or opportunity from product usage data

### Typical Communication
- Metric review reports shared at sprint reviews and stakeholder updates
- Ad-hoc analysis in response to PM or Stakeholder questions
- Dashboard documentation shared with the delivery team

### Interaction Points
- **Product Manager** – co-define success metrics and review outcome data to inform prioritization
- **Project Manager** – provide data for progress reporting and milestone reviews
- **Developers** – collaborate on instrumentation and data pipeline reliability
- **Stakeholders** – present data summaries and business impact reports

---

## Business Analyst

### Role Summary
Business Analysts bridge the gap between business needs and technical solutions. They elicit, document, and validate requirements, ensuring all parties share a common understanding of what needs to be built and why.

### Responsibilities
- Facilitate requirements elicitation workshops with stakeholders and subject-matter experts
- Document functional and non-functional requirements with clear traceability
- Map business workflows and identify process improvement opportunities
- Support the Product Manager in backlog refinement and acceptance criteria authoring
- Validate that delivered features meet documented requirements

### Goals
- Eliminate ambiguity in requirements before work begins
- Ensure delivered solutions trace back to validated business needs
- Reduce rework caused by misunderstood or missing requirements

### Typical Communication
- Requirements documentation and workflow diagrams shared with the full delivery team
- Review sessions with Stakeholders and Product Manager to validate requirements
- Handoff to Developers and QA with annotated acceptance criteria

### Interaction Points
- **Product Manager** – collaborate on user story creation, backlog refinement, and roadmap alignment
- **Stakeholders** – facilitate requirements gathering and validate business process alignment
- **Developers** – clarify requirements and resolve ambiguity during implementation
- **QA/Testing** – ensure test cases trace to documented acceptance criteria
- **UX Designer** – align on user workflows and interaction models

---

## Engineering Manager / Tech Lead

### Role Summary
Engineering Managers and Tech Leads provide technical leadership and people management that enables the development team to deliver high-quality software sustainably. They bridge strategy and execution.

### Responsibilities
- Establish and maintain technical standards, architecture patterns, and code review practices
- Support developer growth through mentoring, feedback, and career development
- Manage team capacity, staffing, and cross-team technical dependencies
- Participate in planning to assess feasibility, decompose work, and surface technical risks
- Drive technical debt prioritization and platform health initiatives

### Goals
- Deliver technically sound solutions that are maintainable and scalable
- Build a healthy, high-performing engineering team
- Ensure technical risks are visible and mitigated before they impact delivery

### Typical Communication
- Architecture decision records (ADRs) and technical design reviews
- 1:1s and team retrospectives for people and process health
- Engineering status updates to Project Manager and Stakeholders as needed

### Interaction Points
- **Project Manager** – align on capacity, scheduling, and technical risk impacts on delivery timelines
- **Product Manager** – provide technical feasibility input and propose alternative solutions
- **Developers** – mentor, code-review, and remove technical blockers
- **Security/Compliance** – co-own security architecture decisions and vulnerability remediation
- **Release Manager** – confirm deployment readiness from an engineering perspective

---

## Security / Compliance

### Role Summary
Security and Compliance roles ensure that the product and its delivery process meet security, privacy, and regulatory requirements. They integrate security considerations throughout the lifecycle rather than as a gate at the end.

### Responsibilities
- Define security requirements and standards applicable to the project
- Review architecture and code for security vulnerabilities
- Ensure CI pipelines include security scanning and dependency checks
- Conduct or coordinate compliance audits, penetration tests, and risk assessments
- Manage and communicate security incidents in coordination with the delivery team

### Goals
- Prevent security vulnerabilities from reaching production
- Ensure regulatory compliance obligations are met on time
- Shift security left—embed it into planning and development rather than treating it as a final gate

### Typical Communication
- Security review reports shared with Engineering Manager and Project Manager
- Compliance checklists integrated into the release checklist (see [Release & Deployment Guide](octoacme-release-and-deployment.md))
- Incident notifications and post-incident reports following the escalation path

### Interaction Points
- **Engineering Manager/Tech Lead** – co-own security architecture and prioritize vulnerability remediation
- **Developers** – review code for security issues; provide secure coding guidance
- **Release Manager** – confirm security scans and compliance checks before production deployment
- **Project Manager** – flag compliance risks that may affect project timeline or scope

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Refer to the [RACI Matrix](octoacme-raci-matrix.md) to understand which roles are Responsible, Accountable, Consulted, or Informed for common project activities.

