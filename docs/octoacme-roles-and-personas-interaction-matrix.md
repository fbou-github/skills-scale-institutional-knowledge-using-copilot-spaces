# OctoAcme — Roles & Personas Interaction Matrix

This document provides a RACI-style responsibility matrix and ceremony ownership guide for OctoAcme projects. Use it alongside [Roles and Personas](octoacme-roles-and-personas.md) to remove ambiguity about who owns what.

> **Related docs:**
> - [Roles and Personas](octoacme-roles-and-personas.md) — full role descriptions and interaction details
> - [Project Initiation Guide](octoacme-project-initiation.md) — initiation checklist and one-pager template
> - [Project Planning](octoacme-project-planning.md) — backlog, sprints, and planning checklist
> - [Execution & Tracking](octoacme-execution-and-tracking.md) — day-to-day workflow and board conventions

---

## RACI Key

| Code | Meaning |
|------|---------|
| **R** | **Responsible** — does the work |
| **A** | **Accountable** — owns the outcome; approves |
| **C** | **Consulted** — provides input before/during |
| **I** | **Informed** — kept up to date on progress/decisions |

---

## Activity Responsibility Matrix

Role abbreviations used in the table:

| Abbr | Role |
|------|------|
| PdM | Product Manager |
| PM | Project Manager |
| Dev | Developer(s) |
| QA | QA / Testing |
| UX | UX/UI Designer |
| DA | Data Analyst |
| DO | DevOps Engineer |
| BA | Business Analyst |
| SM | Scrum Master |
| STK | Stakeholders |

### Initiation & Planning

| Activity | PdM | PM | Dev | QA | UX | DA | DO | BA | SM | STK |
|---|---|---|---|---|---|---|---|---|---|---|
| Define business need / problem statement | A | C | I | I | C | C | I | R | I | C |
| Document requirements and acceptance criteria | C | C | C | C | C | I | I | R/A | I | A |
| Define success metrics | A | C | I | I | I | R | I | C | I | C |
| Stakeholder alignment and sign-off | C | A | I | I | I | I | I | C | I | R |
| Create project plan and milestones | C | A | C | C | C | I | C | C | C | I |
| Confirm team capacity and roles | C | A | R | R | R | R | R | R | R | I |
| Kick-off meeting facilitation | C | A | I | I | I | I | I | I | R | C |

### Design

| Activity | PdM | PM | Dev | QA | UX | DA | DO | BA | SM | STK |
|---|---|---|---|---|---|---|---|---|---|---|
| User research and workflow mapping | C | I | I | I | A/R | C | I | C | I | C |
| Wireframes and prototypes | A | I | C | I | R | I | I | C | I | C |
| Design specification hand-off | C | I | A | C | R | I | I | I | I | I |
| Design review and approval | A | I | C | C | R | I | I | C | I | C |
| Accessibility review | C | I | C | R | A | I | I | I | I | I |

### Development & Execution

| Activity | PdM | PM | Dev | QA | UX | DA | DO | BA | SM | STK |
|---|---|---|---|---|---|---|---|---|---|---|
| Feature implementation | C | I | R/A | I | C | I | C | I | I | I |
| Code review | I | I | R/A | I | I | I | C | I | I | I |
| CI/CD pipeline setup and maintenance | I | I | C | C | I | I | R/A | I | I | I |
| Analytics instrumentation | C | I | R | I | I | A | C | I | I | I |
| Blocker identification and removal | C | C | R | C | C | I | C | I | A | I |
| Board and backlog maintenance | C | C | C | C | I | I | I | I | A | I |

### Quality & Testing

| Activity | PdM | PM | Dev | QA | UX | DA | DO | BA | SM | STK |
|---|---|---|---|---|---|---|---|---|---|---|
| Test plan creation | C | I | C | R/A | I | I | I | C | I | I |
| Feature / functional testing | I | I | C | R/A | I | I | I | I | I | I |
| UI / UX acceptance testing | C | I | C | R | A | I | I | I | I | I |
| Performance and security scanning | I | I | C | C | I | I | R/A | I | I | I |
| Defect logging and tracking | I | I | C | R/A | I | I | I | I | I | I |
| Release sign-off | A | A | C | R | C | I | C | I | I | I |

### Release & Deployment

| Activity | PdM | PM | Dev | QA | UX | DA | DO | BA | SM | STK |
|---|---|---|---|---|---|---|---|---|---|---|
| Release readiness confirmation | A | A | C | R | I | I | R | I | C | I |
| Deployment execution | I | I | C | I | I | I | R/A | I | I | I |
| Post-deploy verification | I | C | C | R | I | R | A | I | I | I |
| Release notes authoring | C | A | C | C | I | I | C | I | I | I |
| Rollback decision and execution | A | A | C | C | I | C | R | I | I | I |

### Retrospective & Continuous Improvement

| Activity | PdM | PM | Dev | QA | UX | DA | DO | BA | SM | STK |
|---|---|---|---|---|---|---|---|---|---|---|
| Retrospective facilitation | I | C | I | I | I | I | I | I | R/A | I |
| Action item capture | I | C | R | R | R | R | R | R | A | I |
| Action item follow-up | C | A | C | C | C | C | C | C | R | I |
| Process improvement proposals | C | C | R | R | C | C | C | C | A | I |
| Metrics review (velocity, quality) | C | C | I | I | I | R | I | I | A | C |

---

## Ceremony Ownership Guide

| Ceremony | Facilitator | Owner / Accountable | Required Attendees | Optional Attendees |
|---|---|---|---|---|
| Project Kick-off | Project Manager | Project Manager + Product Manager | PM, PdM, Dev, QA, BA, SM, STK | UX, DA, DO |
| Sprint Planning | Scrum Master | Scrum Master | Dev, QA, PM, PdM, SM | UX, BA |
| Daily Standup | Scrum Master | Scrum Master | Dev, QA, SM | PM |
| Design Review | UX/UI Designer | Product Manager | PdM, Dev, UX, QA | BA, STK |
| Sprint Review / Demo | Scrum Master | Product Manager | PdM, PM, Dev, QA, SM, STK | UX, DA, BA |
| Sprint Retrospective | Scrum Master | Scrum Master | Dev, QA, PM, SM | UX, DA, DO, BA |
| Risk & Status Sync | Project Manager | Project Manager | PM, PdM, STK | DO, BA, DA |
| Release Readiness Review | Project Manager | Project Manager + QA | PM, PdM, Dev, QA, DO | SM |
| Post-Incident Review | DevOps Engineer | Project Manager | PM, Dev, DO, QA | PdM, DA |
| Requirements Workshop | Business Analyst | Business Analyst | BA, PdM, STK | PM, UX |

---

## Key Handoff Points

These are the most common points where work transfers between roles. Clear handoffs reduce delay and rework.

| Handoff | From | To | Trigger | Artifact |
|---|---|---|---|---|
| Requirements → Design | Business Analyst | UX/UI Designer | Requirements sign-off | Requirements doc, process maps |
| Design → Development | UX/UI Designer | Developers | Design approved by PdM | Annotated design spec, prototype link |
| Development → QA | Developers | QA/Testing | Feature PR merged to staging | PR description, acceptance criteria |
| QA Sign-off → Release | QA/Testing | DevOps Engineer + PM | All tests pass, release sign-off | Test results, release checklist |
| Release → Data Review | DevOps Engineer | Data Analyst | Deployment completed | Deployment confirmation |
| Metrics Review → Backlog | Data Analyst | Product Manager | Post-release analysis complete | Metrics report |
| Blockers → Escalation | Scrum Master | Project Manager | Blocker unresolved after standup | Blocker log, escalation note |
