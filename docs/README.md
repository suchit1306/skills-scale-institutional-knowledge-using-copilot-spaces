# OctoAcme Project Management Docs

This directory is the central hub for OctoAcme project management process documentation and provides shared context for planning, delivering, and improving cross-functional work.

OctoAcme manages projects through a structured lifecycle that starts with project initiation and carries through planning, execution, release, and retrospective learning. Teams begin by clarifying the business need, measurable goals, stakeholders, timeline, early risks, and resource needs in a lightweight one-pager. Once an initiative is approved, the team moves into planning to create a prioritized backlog, define acceptance criteria and the Definition of Done, map dependencies, and establish milestones and release plans.

Delivery depends on clear role ownership across the lifecycle. Project Managers (PMs) coordinate plans, schedules, risks, dependencies, and stakeholder communication so work stays aligned and visible. Product Managers (PdMs) define the problem, prioritize the roadmap and backlog, and measure outcomes. Developers design, build, test, and review implementation details, while QA partners validate quality and feature acceptance. Stakeholders contribute requirements, decisions, and approvals at key checkpoints.

Execution is managed through consistent team rhythms and visible tracking. OctoAcme uses project boards such as GitHub Projects with standard workflow states like Backlog, Ready, In Progress, In Review, QA, and Done. Teams review progress in daily standups, weekly delivery syncs, and sprint or milestone demos, while pull requests are expected to link to issues, include acceptance criteria, and pass automated checks before review. Progress and health are measured through delivery signals such as velocity, burndown, usage, errors, and latency, with escalation paths for blockers and business-impacting risks.

Quality, communication, and continuous improvement are built into the process rather than treated as final steps. Teams apply unit, integration, and smoke testing where appropriate, combine CI and security scanning with manual QA when needed, and prepare release notes, rollback plans, and post-deployment verification before shipping. Communication follows a regular cadence through PM/PdM syncs, stakeholder updates, and a single source of truth for status. After milestones, releases, or incidents, teams hold retrospectives to capture lessons learned, assign action items, and improve the process iteratively.

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
