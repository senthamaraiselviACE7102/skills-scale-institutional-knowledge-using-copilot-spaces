# OctoAcme Project Management Docs

This directory centralizes OctoAcme's project management process documentation so teammates can quickly find, understand, and apply the team's standard ways of working. It serves as a starting point for navigating the canonical process docs, understanding how projects move from idea to delivery, and reducing reliance on informal or siloed knowledge.

## Process Documents

- [Project Management Overview](./octoacme-project-management-overview.md)
- [Project Initiation Guide](./octoacme-project-initiation.md)
- [Project Planning](./octoacme-project-planning.md)
- [Execution & Tracking](./octoacme-execution-and-tracking.md)
- [Risk Management & Communication](./octoacme-risks-and-communication.md)
- [Release & Deployment Guide](./octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](./octoacme-roles-and-personas.md)

## Overview of OctoAcme Project Management Processes

OctoAcme uses a lightweight but structured project management lifecycle that moves through initiation, planning, execution, release, and retrospective improvement. Projects begin by validating the business need, defining measurable goals, identifying stakeholders, capturing early risks, and documenting the work in a project one-pager. Once approved, planning turns the initiative into a prioritized backlog with acceptance criteria, estimates, dependencies, milestones, and a release plan so teams can deliver in manageable increments.

Roles and responsibilities are clearly defined to support accountability and cross-functional collaboration. Project Managers coordinate schedules, risks, documentation, and stakeholder communication, while Product Managers define outcomes, prioritize the backlog, and measure success. Developers implement features, contribute to planning and estimation, and identify technical risks, while QA or testing contributors validate feature quality and acceptance criteria. Stakeholders and sponsors provide input, alignment, and escalation support when needed.

Execution is supported by visible workflows and regular communication rhythms. Teams use project boards with stages such as Backlog, Ready, In Progress, In Review, QA, Done to track progress and dependencies. Recommended team practices include standups, weekly delivery or PM/PdM syncs, sprint or milestone demos, and regular stakeholder updates. Risks are tracked in a risk register and escalated through defined paths from team-level triage to PM and Product Lead involvement, and then to sponsor-level escalation for business-impacting issues.

Quality assurance is built into both development and release processes rather than treated as a final step. Teams are encouraged to keep pull requests small, include linked issues and acceptance criteria, and rely on CI checks such as tests, linting, and security scanning before review. Quality practices include unit tests for new logic, integration testing where appropriate, end-to-end smoke tests for critical flows, and manual QA when needed. Before release, teams confirm acceptance criteria, passing CI, release notes, rollback planning, and post-deployment verification, then use retrospectives to capture lessons learned and improve future execution.

## How to Contribute

To request additions or updates to these process documents:

- Use the issue template in `.github/ISSUE_TEMPLATE/`
- Select the **Add Content to Project Management Process Docs** template
- Describe the document to update, the proposed content, and the rationale for the change
- If possible, include suggested wording, examples, or checklist updates to speed review

When making documentation changes, keep updates aligned with the existing process docs so this directory remains a reliable and consistent source of truth for OctoAcme project management practices.
