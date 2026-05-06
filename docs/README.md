# OctoAcme Project Management Docs

Welcome! This README serves as a landing page for all OctoAcme project management process documents. The docs in this folder centralize project management knowledge so it is searchable and version-controlled, improving onboarding for new team members, reducing single-person dependency, and enabling consistent, repeatable execution across projects.

---

## OctoAcme Project Management Process Overview

OctoAcme's project management approach follows a lightweight, end-to-end lifecycle with clear ownership and repeatable artifacts. Work moves from **Initiation** (confirm the business need, stakeholders, success metrics, and an initial risk list) into **Planning** (kickoff, prioritized backlog with acceptance criteria, estimates, Definition of Done, dependency mapping, and a release plan), then through **Execution & Tracking**, **Release & Deployment**, and finally **Close & Retrospective** where learnings are captured and converted into improvements. Across all phases the process emphasizes iterative delivery of small, testable increments and using shared, repo-based documentation as the single source of truth (e.g., one-pager/charter, backlog, risk register, release notes, and retrospective action items). A decision gate after initiation ensures work proceeds only when success metrics are clear, stakeholders agree on priority, and team availability is confirmed.

Roles and responsibilities are explicitly defined to reduce ambiguity and single-person dependency. A **Project Manager (PM)** coordinates delivery, schedules, risks, and communications; a **Product Manager/Product Lead** defines outcomes, prioritizes the backlog, and measures success; **Developers** design, implement, and maintain tests and documentation; and **QA/Testing** validates quality and acceptance criteria. **Stakeholders** provide inputs and approvals at key moments. Day-to-day execution is managed through a project board (e.g., GitHub Projects) with standard columns (Backlog → Ready → In Progress → In Review → QA → Done), supported by daily standups focused on blockers and dependencies, weekly delivery syncs, and demos/reviews at sprint or milestone boundaries.

Communication is structured through recurring PM/Product alignment, regular stakeholder updates, and clear escalation paths. Teams use a single source of truth (project README or release doc) for status, a standard Weekly Status Template (progress, next steps, risks & blockers, decisions needed), and dedicated incident communication formats (triage summary, actions, expected timeline, post-incident retrospective). Escalation follows a defined path: team-level triage → PM escalation to Product Lead and dependent teams → sponsor-level escalation for business-impacting issues, with special handling for security incidents via the security incident runbook and Security on-call notification.

Quality assurance is built into day-to-day delivery and release practices. Pull requests are kept small (≤ 400 lines when possible), link to issues and acceptance criteria, and require CI-driven tests and linting to pass before review, plus at least one approval before merging. Testing covers unit tests for new logic, integration tests where applicable, end-to-end smoke tests for critical flows, security scanning in CI, and manual QA for feature acceptance when needed. Releases require all acceptance criteria to be met, passing CI and security scans, drafted release notes, and a documented rollback/mitigation plan; after deployment, teams run post-deploy verification checks and use retrospectives to capture improvements and feed action items back into the backlog.

---

## Process Documents Index

| Document | Description |
|---|---|
| [Project Management Overview](octoacme-project-management-overview.md) | Principles, core roles, key artifacts, and lifecycle at a glance |
| [Project Initiation Guide](octoacme-project-initiation.md) | Validating and authorizing new work; one-pager template and initiation checklist |
| [Project Planning](octoacme-project-planning.md) | Turning an approved initiative into a backlog, release plan, and milestones |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Day-to-day team rhythm, board workflow, PR process, and quality practices |
| [Risk Management & Communication](octoacme-risks-and-communication.md) | Risk register, escalation paths, weekly status template, and incident communication |
| [Release & Deployment Guide](octoacme-release-and-deployment.md) | Pre-release requirements, deployment checklist, rollback playbook, and release notes template |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Running retrospectives, tracking action items, and building a continuous improvement culture |
| [Roles and Personas](octoacme-roles-and-personas.md) | Detailed responsibilities and communication patterns for each role |
