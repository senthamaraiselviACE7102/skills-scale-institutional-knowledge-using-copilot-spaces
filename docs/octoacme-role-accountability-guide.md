# OctoAcme — Role Accountability Guide

## Purpose
Clarify ownership, decision-making, and handoffs across the project lifecycle so teams can reduce ambiguity, improve coordination, and make escalations faster.

## How to use this guide
- Use this guide alongside `octoacme-roles-and-personas.md`
- Tailor accountability assignments to the size and complexity of the project
- Review role coverage during initiation and again before release
- Update responsibilities when major scope, staffing, or dependency changes occur

## Lightweight RACI definitions
- **R — Responsible:** does the work
- **A — Accountable:** owns the outcome and final decision
- **C — Consulted:** provides input before action or decision
- **I — Informed:** kept updated on progress or outcome

## Lifecycle accountability map

| Activity | PM | PdM | Dev | QA | TPM | Tech Lead | Release Manager | SRE / Platform | UX | Security | Support / CS | Stakeholders |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Define project goals and success metrics | C | A | I | I | I | I | I | I | C | I | I | C |
| Create project plan and milestones | A | C | I | I | C | C | I | I | I | I | I | C |
| Prioritize backlog | C | A | C | I | I | C | I | I | C | I | C | I |
| Define technical approach | I | C | C | I | I | A | I | C | I | C | I | I |
| Validate acceptance criteria | C | A | C | R | I | C | I | I | C | I | I | I |
| Manage cross-team dependencies | A | C | I | I | R | C | I | I | I | I | I | C |
| Coordinate release readiness | C | I | C | R | I | C | A | C | I | I | C | I |
| Execute deployment | I | I | C | C | I | C | A | R | I | I | I | I |
| Respond to incident | C | I | C | I | I | C | C | A | I | C | C | I |
| Communicate customer impact | C | C | I | I | I | I | C | C | I | I | A | I |
| Run retrospective and track actions | A | C | C | C | I | C | I | I | I | I | I | I |

## Recommended handoff checkpoints

### Initiation to Planning
Before moving into planning:
- Problem statement and success metrics are documented
- Stakeholders are identified
- Initial risks and dependencies are captured
- Core roles are assigned

### Planning to Execution
Before active delivery begins:
- Backlog items have acceptance criteria
- Ownership for technical decisions is clear
- QA approach is defined
- Cross-team dependencies and escalation paths are documented

### Execution to Release
Before release:
- Testing and quality checks are complete
- Release communications are prepared
- Rollback and support plans are documented
- Operational readiness has been confirmed

### Release to Support / Follow-up
After release:
- Post-release verification is complete
- Known issues and customer-facing guidance are documented
- Support and incident contacts are clear
- Follow-up actions are assigned

### Retrospective follow-through
After retrospectives:
- Top action items have owners and due dates
- Actions are tracked in the backlog or issue tracker
- Learnings are folded back into process docs where applicable
