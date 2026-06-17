# OctoAcme Project Management Docs

This directory is the central hub for OctoAcme project management process documentation and provides shared context for planning, delivering, and improving cross-functional work.

OctoAcme follows a structured lifecycle approach to project management that emphasizes customer value, iterative delivery, and clear ownership. The framework spans five phases: **Initiation** (validating business need and aligning stakeholders), **Planning** (breaking work into shippable increments), **Execution** (building, testing, and iterating), **Release** (deploying to production with minimal risk), and **Close & Retrospective** (capturing learnings). At the core of this process are three primary roles—**Project Manager** (coordinating delivery, schedules, and communications), **Product Manager** (defining outcomes and measuring success), and **Developers** (implementing features while collaborating on design and quality)—supported by QA/Testing and stakeholders. This multi-role model ensures clear ownership and decision-making authority at each stage.

Communication and risk management are woven throughout OctoAcme's approach. The team operates on a regular cadence of **daily standups** (15 minutes, focused on progress and blockers), **weekly delivery syncs** (tracking progress and flagged risks), and **monthly stakeholder updates**. A documented risk register is maintained with clear escalation paths: team-level triage → PM → Product Lead → Sponsor. Status communication follows consistent templates that highlight progress, next steps, blockers, and decisions needed. This transparency ensures that dependencies are surfaced early and cross-team coordination happens at the right frequency, reducing surprises and enabling proactive problem-solving.

Quality and execution are prioritized through structured workflows and checklists. The pull request process emphasizes small, reviewable changes (≤400 lines when possible), automated CI testing, linting, and security scanning before review. The project board uses standardized columns (Backlog, Ready, In Progress, In Review, QA, Done) to visualize work state, and each backlog item includes clear acceptance criteria and a Definition of Done. Before release, the team validates that all acceptance criteria are met, tests pass, release notes are drafted, and rollback plans are documented. This disciplined approach to planning, estimation (using T-shirt sizing or story points), and quality gates reduces rework and builds confidence in deliverables.

Finally, OctoAcme emphasizes continuous improvement through retrospectives held after sprints, releases, or important milestones. These sessions (typically 45–75 minutes) capture what went well, what could improve, and generate 2–3 prioritized action items with clear owners and due dates. These improvements feed back into the backlog and are tracked in weekly PM syncs, creating a feedback loop that makes the process itself more effective over time. By grounding decisions in data (velocity, burndown, success metrics), encouraging psychological safety, and treating retrospectives as routine, OctoAcme builds a culture of learning and sustainable delivery.

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
