# OctoAcme Project Management — Documentation Hub

This README serves as the central entry point for understanding and navigating the OctoAcme project management process docs. Whether you're onboarding to the team or looking to refresh your understanding of how we work, start here.

## Overview

OctoAcme projects follow a structured lifecycle: **Initiation → Planning → Execution → Release → Retrospective**. Every project begins with a lightweight one-pager that validates the idea, aligns stakeholders, establishes success metrics, identifies early risks, and reaches a go/no-go decision before any significant work begins. Planning converts that approved initiative into a prioritized backlog with clear acceptance criteria, estimates, a Definition of Done, dependency mapping, a release plan, and an initial QA approach — ensuring the team is aligned before the first line of code is written.

During execution, work is tracked on a project board (Backlog → Ready → In Progress → In Review → QA → Done) with small, focused pull requests, mandatory CI checks (tests, linting, security scanning), and at least one required review before merging. The team stays coordinated through daily standups, weekly delivery syncs, and end-of-sprint demos. Blockers are escalated through a three-level path — team triage, PM/Product Lead escalation, and sponsor involvement for business-impacting issues — while a risk register is kept current throughout. When a release is ready, pre-release checks confirm all acceptance criteria are met, smoke tests pass, rollback plans are documented, and stakeholders receive clear deployment communications; post-deploy verification closes the loop.

Risks and communication are managed proactively: a running risk register tracks impact, likelihood, owner, and mitigation for every identified risk, and stakeholders receive regular structured updates using a single source of truth for project status. After each sprint, release, or major milestone the team runs a retrospective to capture what went well, what could improve, and 2–3 concrete action items with owners and due dates — those items feed back into the backlog and are reviewed in the weekly PM sync to keep the improvement cycle alive.

### Roles at a Glance

| Role | Core Responsibility |
|---|---|
| **Project Manager (PM)** | Coordinates delivery, schedules, risks, and cross-team communication |
| **Product Manager (PdM)** | Defines outcomes, owns the backlog, measures success |
| **Developers** | Implement features, write tests, participate in design and code review |
| **QA/Testing** | Validates quality and acceptance criteria |
| **Stakeholders** | Provide inputs, approvals, and business context |

---

## Document Index

| Document | Description |
|---|---|
| [Project Management Overview](octoacme-project-management-overview.md) | Principles, core roles, key artifacts, and the high-level project lifecycle |
| [Project Initiation](octoacme-project-initiation.md) | One-pager template, stakeholder alignment, and go/no-go decision gate |
| [Project Planning](octoacme-project-planning.md) | Backlog creation, acceptance criteria, estimation, DoD, and release planning |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Project board workflows, PR conventions, CI, standups, metrics, and escalation |
| [Risks & Communication](octoacme-risks-and-communication.md) | Risk register, stakeholder updates, incident communication, and escalation paths |
| [Release & Deployment](octoacme-release-and-deployment.md) | Pre-release checks, smoke tests, rollback planning, and deployment verification |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Retrospective structure, action item tracking, and continuous improvement culture |
| [Roles & Personas](octoacme-roles-and-personas.md) | Detailed responsibilities and communication patterns for each role |
