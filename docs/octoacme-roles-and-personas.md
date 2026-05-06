# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

> **See also:** [Roles & Personas Interaction Matrix](octoacme-roles-and-personas-interaction-matrix.md) for a RACI-style responsibility matrix and ceremony ownership guide.

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

### Interactions with Other Roles
- **Product Manager:** Receive and clarify feature specs and acceptance criteria; flag technical trade-offs.
- **Project Manager:** Report blockers, progress, and estimates; participate in planning ceremonies.
- **UX/UI Designer:** Consume design assets and prototypes; raise implementation constraints early.
- **QA/Testing:** Hand off completed features for validation; address defects and regression feedback.
- **DevOps Engineer:** Coordinate on environment configuration, CI/CD pipelines, and deployment readiness.
- **Data Analyst:** Instrument features with agreed metrics; share observability data after release.
- **Stakeholders:** Present demos and gather early feedback at sprint reviews.

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

### Interactions with Other Roles
- **Project Manager:** Align on scope, timelines, and risk trade-offs weekly; jointly own release readiness decisions.
- **Developers:** Provide clear acceptance criteria; review demos and validate delivered functionality.
- **UX/UI Designer:** Define user problems and review design solutions to ensure they address customer needs.
- **Business Analyst:** Collaborate on requirements gathering and process mapping during initiation and planning.
- **Data Analyst:** Define success metrics together; review post-release impact data to inform backlog prioritization.
- **Stakeholders:** Gather inputs, present roadmap updates, and confirm prioritization decisions.

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

### Interactions with Other Roles
- **Product Manager:** Weekly alignment on scope and priorities; jointly present status to stakeholders.
- **Developers:** Remove blockers, track progress on the board, and communicate capacity constraints.
- **Scrum Master:** Partner on ceremony facilitation and agile process health; share sprint metrics.
- **DevOps Engineer:** Track deployment readiness and environmental risks in the risk register.
- **Business Analyst:** Receive requirements documentation and process maps to feed into the project plan.
- **Stakeholders:** Provide regular status updates, escalate decisions, and manage expectations on timeline and scope.

---

## QA / Testing

### Role Summary
QA/Testing validates that features meet acceptance criteria and quality standards before they reach production. They design test plans, execute tests, and advocate for quality throughout the delivery lifecycle.

### Responsibilities
- Design and maintain test plans, test cases, and acceptance test suites
- Execute functional, regression, and exploratory testing
- Log and track defects; verify fixes before closure
- Review acceptance criteria during planning to ensure testability
- Champion quality practices, including CI test coverage

### Goals
- Ensure releases meet the Definition of Done
- Reduce defect escape rate to production
- Shift quality left by catching issues early in the cycle

### Typical Communication
- Sprint review and planning participation
- Defect reports and test results shared via project board
- Pre-release sign-off confirmation to Project Manager

### Interactions with Other Roles
- **Product Manager:** Review acceptance criteria for completeness and testability before work starts.
- **Project Manager:** Report test status, outstanding defects, and release readiness at each milestone.
- **Developers:** Collaborate on test coverage; receive completed features for validation; return defects for rework.
- **DevOps Engineer:** Coordinate on CI pipeline test gates and staging environment stability.
- **UX/UI Designer:** Validate UI against design specifications and accessibility standards.

---

## Stakeholders

### Role Summary
Stakeholders provide business context, funding, approvals, and strategic direction. They are kept informed throughout the project and are critical decision-makers at key gates.

### Responsibilities
- Define and validate business objectives and success criteria
- Provide timely approvals and decisions when escalated
- Review and accept deliverables at defined milestones
- Advocate for the project within the broader organization

### Goals
- Ensure the project delivers expected business value
- Minimize surprises through proactive communication
- Provide clear direction when trade-offs are required

### Typical Communication
- Kick-off meeting attendance and milestone reviews
- Weekly or bi-weekly status report consumption
- Ad-hoc escalation responses

### Interactions with Other Roles
- **Product Manager:** Align on roadmap priorities, review business metrics, and approve major scope changes.
- **Project Manager:** Receive status reports and respond to escalations on risks and timeline changes.
- **Business Analyst:** Provide detailed business context and validate requirements documentation.
- **Developers:** Participate in sprint demos to provide early feedback on delivered features.

---

## UX/UI Designer

### Role Summary
UX/UI Designers ensure that product interfaces are intuitive, accessible, and aligned with user needs. They translate requirements into design artifacts that guide development and protect the end-user experience.

### Responsibilities
- Conduct user research and synthesize findings into actionable insights
- Create wireframes, prototypes, and high-fidelity design specifications
- Define user flows, interaction patterns, and accessibility standards
- Collaborate with Product Manager to validate design decisions against user needs
- Conduct usability reviews and iterate on designs based on feedback

### Goals
- Deliver designs that improve user satisfaction and task completion rates
- Ensure consistency across the product's visual and interaction language
- Reduce rework by resolving usability issues before development begins

### Typical Communication
- Design reviews and prototype walkthroughs with Product and Development teams
- Annotated design assets handed off via design tool (e.g., Figma)
- Participation in sprint planning to clarify design requirements

### Interactions with Other Roles
- **Product Manager:** Receive prioritized problem statements; co-validate design decisions against user and business goals.
- **Project Manager:** Communicate design milestone progress and flag dependencies on research or stakeholder review.
- **Developers:** Hand off annotated design specs; resolve implementation questions during development sprints.
- **QA/Testing:** Provide design specifications for UI acceptance testing and accessibility checks.
- **Business Analyst:** Collaborate on understanding user workflows and existing process pain points that inform design.
- **Stakeholders:** Present prototypes for early feedback before development investment is made.

---

## Data Analyst

### Role Summary
Data Analysts generate insights from product and operational metrics to support evidence-based decision-making. They define measurement frameworks, build reports, and surface trends that inform product direction and project health.

### Responsibilities
- Define and instrument key metrics aligned with product success criteria
- Build dashboards and reports for project and product health monitoring
- Analyze user behavior and business data to surface actionable insights
- Support post-release impact measurement and retrospective analysis
- Identify data quality issues and recommend improvements

### Goals
- Make success and failure visible through clear, reliable metrics
- Enable data-driven prioritization and decision-making
- Reduce time from data collection to actionable insight

### Typical Communication
- Data briefings and dashboard walkthroughs with Product Manager and leadership
- Post-release metric summaries shared after each deployment
- Ad-hoc analysis requests fulfilled within agreed SLAs

### Interactions with Other Roles
- **Product Manager:** Jointly define success metrics during initiation; share post-release impact analyses.
- **Project Manager:** Provide project health dashboards (velocity, defect trends) to support status reporting.
- **Developers:** Coordinate on analytics instrumentation and data pipeline requirements.
- **DevOps Engineer:** Align on observability tooling and data pipeline reliability.
- **Stakeholders:** Present business-impact metrics and trend summaries at milestone reviews.

---

## DevOps Engineer

### Role Summary
DevOps Engineers maintain the infrastructure, CI/CD pipelines, and deployment tooling that enable reliable, fast delivery. They reduce operational risk and improve development efficiency through automation and observability.

### Responsibilities
- Build and maintain CI/CD pipelines for automated testing, builds, and deployments
- Manage environments (development, staging, production) and infrastructure as code
- Monitor system health, respond to incidents, and conduct post-incident reviews
- Implement and maintain security scanning and compliance checks in pipelines
- Support rollback and disaster recovery procedures

### Goals
- Maximize deployment frequency while minimizing failure rate and recovery time
- Ensure environment parity between staging and production
- Provide full observability into system performance and reliability

### Typical Communication
- Deployment status updates to Project Manager and development team
- Incident notifications and post-incident summaries
- Environment readiness confirmations before each release

### Interactions with Other Roles
- **Project Manager:** Report environment risks, deployment schedules, and incident impacts on project timelines.
- **Developers:** Collaborate on pipeline configuration, environment setup, and deployment readiness; support debugging of CI failures.
- **QA/Testing:** Provide stable staging environments for test execution; integrate automated test gates into pipelines.
- **Data Analyst:** Ensure observability tooling and data pipelines are reliable and properly monitored.
- **Stakeholders:** Communicate operational reliability metrics and incident impact at milestone reviews.

---

## Business Analyst

### Role Summary
Business Analysts bridge business needs and technical solutions. They gather, document, and validate requirements, map existing processes, and ensure that delivered features solve the right problems for the right stakeholders.

### Responsibilities
- Elicit and document business requirements through stakeholder interviews and workshops
- Produce process maps, user stories, and acceptance criteria
- Identify gaps between current and desired states
- Facilitate requirements sign-off with stakeholders and Product Manager
- Support change management and user adoption activities

### Goals
- Ensure requirements are complete, unambiguous, and agreed upon before development begins
- Reduce scope creep and rework caused by poorly understood requirements
- Accelerate alignment between business and technical teams

### Typical Communication
- Requirements workshops and review sessions with stakeholders and Product Manager
- Process diagrams and requirements documentation shared in the project repo
- Regular check-ins with Project Manager to confirm requirements progress against plan

### Interactions with Other Roles
- **Product Manager:** Co-develop requirements and acceptance criteria; align on priority and scope before sprint planning.
- **Project Manager:** Provide requirements documentation on schedule to feed into the project plan and kickoff.
- **Developers:** Clarify requirements and acceptance criteria during sprint planning and throughout development.
- **UX/UI Designer:** Share process maps and user workflow documentation that informs design decisions.
- **Stakeholders:** Lead requirements elicitation sessions; obtain formal sign-off on documented requirements.

---

## Scrum Master

### Role Summary
The Scrum Master facilitates agile ceremonies, removes impediments, and coaches the team on agile best practices. They protect the team's ability to deliver by creating the conditions for effective collaboration and continuous improvement.

### Responsibilities
- Facilitate sprint planning, daily standups, sprint reviews, and retrospectives
- Identify and remove blockers escalating to Project Manager when needed
- Track and follow up on retrospective action items
- Coach team members on agile principles and practices
- Monitor sprint health metrics (velocity, scope change, burndown)

### Goals
- Maintain a consistent, sustainable delivery cadence
- Continuously improve team practices through actionable retrospectives
- Reduce the time blockers remain unresolved

### Typical Communication
- Daily standup facilitation
- Sprint retrospective summaries shared with the team and Project Manager
- Blocker and impediment escalation reports

### Interactions with Other Roles
- **Project Manager:** Share sprint health metrics and blocker escalations; co-own ceremony calendar and delivery rhythm.
- **Product Manager:** Ensure backlog is ready for sprint planning; flag capacity or scope concerns before sprint start.
- **Developers:** Remove day-to-day impediments; facilitate team problem-solving and continuous improvement conversations.
- **QA/Testing:** Ensure testing work is included in sprint planning and velocity tracking.
- **Stakeholders:** Facilitate sprint reviews to gather feedback and demonstrate progress.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- For a structured view of who owns what activity, see the [Roles & Personas Interaction Matrix](octoacme-roles-and-personas-interaction-matrix.md).

