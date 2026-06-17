# OctoAcme Project Management Docs

OctoAcme project management docs centralize our processes for initiating, planning, executing, releasing, and improving projects. They describe roles, artifacts, rhythms, and checklists we use to deliver value iteratively and safely.

## Overview of OctoAcme Project Management Processes

OctoAcme's project management approach is designed to take work from idea to delivery in a structured, repeatable way. The process starts with **project initiation**, where teams validate the business need, define a measurable objective, identify stakeholders, and prepare a lightweight project one-pager with goals, success metrics, milestones, risks, and resource needs. Once an initiative is approved, it moves into **planning**, where the team holds a kickoff, builds a prioritized backlog, estimates scope, defines the Definition of Done, maps dependencies, and creates a release plan and milestone map. Across the lifecycle, the emphasis is on iterative delivery, clear ownership, and data-informed decisions.

The documentation highlights clearly defined **roles and personas**. The **Project Manager (PM)** coordinates schedules, risks, communications, and delivery execution. The **Product Manager (PdM)** owns the problem definition, prioritization, and success measurement. Developers implement features, write tests, collaborate on reviews, and help identify technical risks, while QA/testing validates quality and acceptance criteria. Stakeholders provide input and approvals at key decision points. These roles work together to maintain alignment from initiation through execution and release.

During **execution and tracking**, OctoAcme relies on a project board with standard workflow states such as Backlog, Ready, In Progress, In Review, QA, and Done. The team uses small pull requests when possible, links PRs to issues, includes acceptance criteria in PR descriptions, and requires automated testing and linting before review. Progress is tracked through daily standups, weekly delivery syncs, demos at sprint or milestone end, and metrics such as velocity, burndown, and key product or operational dashboards. Risks and blockers are reviewed regularly, with escalation paths from team-level triage up through PM, Product Lead, and sponsor-level escalation when needed.

Quality and communication are treated as ongoing disciplines rather than afterthoughts. OctoAcme expects unit, integration, and smoke tests where applicable, plus security scanning and manual QA for feature acceptance when needed. Release management includes pre-release checks like passing CI, drafted release notes, rollback planning, and post-deploy verification. Communication is structured around weekly PM-PdM syncs, regular stakeholder updates, and a single source of truth for status. After releases, incidents, or milestones, the team holds retrospectives to capture lessons learned and turn them into action items, reinforcing continuous improvement over time.

## Process Documents

- [**OctoAcme Project Management Overview**](./octoacme-project-management-overview.md) — High-level introduction to OctoAcme's approach, roles, and key artifacts
- [**Project Initiation Guide**](./octoacme-project-initiation.md) — Steps to validate and authorize work, align stakeholders, and create a lightweight plan
- [**Project Planning**](./octoacme-project-planning.md) — Turning an approved initiative into an actionable plan and backlog for delivery
- [**Execution & Tracking**](./octoacme-execution-and-tracking.md) — Guidance for managing day-to-day execution and tracking progress toward milestones
- [**Risk Management & Communication**](./octoacme-risks-and-communication.md) — How to identify, manage, and communicate risks and dependencies
- [**Release & Deployment Guide**](./octoacme-release-and-deployment.md) — Standardized process for releasing features to production
- [**Retrospective & Continuous Improvement**](./octoacme-retrospective-and-continuous-improvement.md) — Capturing learnings and converting them into actionable improvements
- [**Roles & Personas**](./octoacme-roles-and-personas.md) — Definitions of typical roles and responsibilities used across OctoAcme projects

## How to Use These Docs

- **New team members**: Start with the [Project Management Overview](./octoacme-project-management-overview.md) for a broad introduction, then dive into specific docs as needed for your role.
- **Project setup**: Use the [Initiation Guide](./octoacme-project-initiation.md) and [Planning](./octoacme-project-planning.md) docs to set up a new project.
- **During delivery**: Refer to [Execution & Tracking](./octoacme-execution-and-tracking.md) and [Risk Management & Communication](./octoacme-risks-and-communication.md) as your primary guides.
- **Preparing for release**: Use the [Release & Deployment Guide](./octoacme-release-and-deployment.md) to plan and execute launches safely.
- **Learning and improving**: After each milestone or release, use the [Retrospective Guide](./octoacme-retrospective-and-continuous-improvement.md) to capture insights and drive continuous improvement.

Keep these docs updated as OctoAcme evolves. Use the [Process Doc Update issue template](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) to propose changes and improvements.
