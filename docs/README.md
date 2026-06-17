# OctoAcme Project Management Docs

This directory is the central hub for OctoAcme project management process documentation. It gives new team members a quick view of how projects move from idea to delivery, who is involved, how teams communicate, and how quality and risk are managed along the way.

## Overview and Core Principles

OctoAcme uses a structured, iterative project management approach for cross-functional product, service, and integration work. Projects move through a common lifecycle of initiation, planning, execution, release, and retrospective learning so teams can stay aligned while still delivering in small, testable increments.

The approach is grounded in a few consistent principles:

- **Customer-first prioritization:** focus work on customer and business value.
- **Iterative delivery:** ship in small, testable increments instead of large handoffs.
- **Clear ownership:** assign a named Project Manager (PM) and Product Manager (PdM)/Product Lead.
- **Data-informed decisions:** use success metrics, delivery signals, and operational data to guide trade-offs.
- **Psychological safety:** encourage feedback, transparency, and continuous improvement.

Key artifacts across the lifecycle include the project one-pager, roadmap and release plan, prioritized backlog, acceptance criteria and Definition of Done, risk register, and retrospective action items.

## Key Workflows and Processes

| Stage | Purpose | Typical outputs |
| --- | --- | --- |
| **Initiation** | Validate the business need, define measurable goals, identify stakeholders, and decide whether to proceed. | Project one-pager, stakeholder list, communication plan, initial timeline, initial risks, resource needs |
| **Planning** | Turn an approved idea into an actionable delivery plan. | Prioritized backlog, acceptance criteria, estimates, Definition of Done, dependency map, release timeline, initial QA approach |
| **Execution & Tracking** | Deliver work in visible increments while managing progress, blockers, and quality. | Updated project board, small PRs linked to issues, demos/reviews, metrics dashboards, weekly risk updates |
| **Release & Deployment** | Ship changes safely and communicate readiness and outcomes. | Passing CI and security scans, release notes, rollback plan, smoke test results, stakeholder announcement |
| **Retrospective & Continuous Improvement** | Capture lessons learned and turn them into follow-up actions. | Retrospective notes, prioritized action items, owners, due dates, success criteria |

## Personas and Roles

- **Project Managers (PMs):** coordinate delivery plans, schedules, risks, dependencies, meetings, and stakeholder communication.
- **Product Managers (PdMs)/Product Leads:** define the problem, set goals and success metrics, prioritize the roadmap and backlog, and measure outcomes.
- **Developers:** design, build, test, review, and document implementation work while helping estimate scope and identify technical risks.
- **QA/Testing partners:** validate quality, confirm acceptance criteria, and support feature acceptance and release readiness.
- **Stakeholders and sponsors:** provide requirements, decisions, approvals, and escalation support at key checkpoints.

## Communication Strategies and Cadence

OctoAcme uses a predictable communication rhythm so teams can stay aligned without losing momentum:

- **Daily standups (15 minutes):** progress, blockers, and dependencies
- **Weekly PM/PdM and delivery syncs:** scope alignment, risk review, status updates, and decisions
- **Sprint or milestone demos/reviews:** show progress and gather feedback
- **Monthly stakeholder updates:** communicate health, milestones, and decisions needed
- **Ad-hoc escalations:** raise urgent blockers, incidents, or business-impacting risks quickly

Teams are expected to keep a single source of truth for status, such as the project README, project board, or release documentation. Weekly updates typically cover progress, next steps, risks or blockers, and asks or decisions needed.

## Quality Assurance and Testing Practices

Quality is built into delivery rather than left until the end:

- write **unit tests** for new logic
- add **integration tests** where systems or components interact
- run **end-to-end smoke tests** for critical flows before release
- require **automated tests and linting in CI** before review
- run **security scanning in CI**
- use **manual QA** when feature acceptance or workflow validation requires it

During execution, pull requests should stay small when possible, link to the relevant issue, include acceptance criteria, and receive at least one approval before merging, unless the team defines a stricter policy.

## Risk Management and Escalation

Risk management starts during planning and continues through execution and release. Teams maintain a risk register with an ID, description, impact, likelihood, owner, mitigation plan, and status. Risks are reviewed regularly in weekly syncs and updated as conditions change.

Escalation follows a clear path:

1. **Team-level triage** during daily execution for routine blockers
2. **PM escalation** to the Product Lead and dependent teams for cross-team or schedule risks
3. **Sponsor-level escalation** for business-impacting issues
4. **Security incident escalation** through the security incident runbook and Security on-call

## Process Documents

- [Project Management Overview](./octoacme-project-management-overview.md)
- [Project Initiation Guide](./octoacme-project-initiation.md)
- [Project Planning](./octoacme-project-planning.md)
- [Execution & Tracking](./octoacme-execution-and-tracking.md)
- [Risk Management & Communication](./octoacme-risks-and-communication.md)
- [Release & Deployment Guide](./octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](./octoacme-roles-and-personas.md)

## How to Use These Docs

- **If you are starting a new project:** begin with the overview and initiation guides, then move into planning once the work is approved.
- **If you are a PM or PdM:** use the planning, execution, risk, and release docs to manage scope, status, dependencies, communications, and delivery readiness.
- **If you are a developer or QA partner:** use the roles, execution, release, and retrospective docs to understand day-to-day expectations for implementation, validation, and feedback.
- **If you are a stakeholder or sponsor:** review the overview, initiation, and risk/communication docs for decision points, status expectations, and escalation paths.
- **If you are working by lifecycle stage:** follow the docs in order from initiation to planning, execution, release, and retrospective/continuous improvement.

## Proposing Changes

To propose additions or updates to these process docs, open a GitHub issue with the **Add Content to Project Management Process Docs** issue template in `.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml`. Use that template to identify the target document, summarize the requested change, explain the rationale, and capture any suggested content or acceptance criteria for review.
