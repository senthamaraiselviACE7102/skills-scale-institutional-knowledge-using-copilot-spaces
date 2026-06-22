# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

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

---

## QA / Testing

### Role Summary
QA and Testing roles validate that delivered work meets acceptance criteria, quality expectations, and release readiness standards before changes reach customers.

### Responsibilities
- Define and execute test plans for features, fixes, and regressions
- Validate acceptance criteria and document test results
- Identify defects, clarify reproduction steps, and partner with developers on resolution
- Support release readiness by verifying critical flows and smoke tests
- Contribute to improving quality practices across the team

### Goals
- Prevent defects from reaching production
- Improve confidence in releases
- Ensure test coverage aligns with product and delivery risk

### Typical Communication
- Works with Developers to reproduce and resolve defects
- Aligns with Product Managers on acceptance expectations
- Coordinates with Project Managers on test status and release readiness
- Participates in demos, reviews, and go/no-go discussions

---

## Technical Program Managers (TPM)

### Role Summary
Technical Program Managers coordinate complex, cross-team initiatives that require structured dependency management, milestone tracking, and technical-delivery alignment.

### Responsibilities
- Drive program-level planning across teams and workstreams
- Track milestones, dependencies, and cross-team risks
- Maintain visibility into critical path items and escalation needs
- Support coordination for major launches or multi-team initiatives
- Help teams align plans, timelines, and ownership

### Goals
- Reduce delivery risk across multi-team efforts
- Improve predictability for cross-functional programs
- Ensure dependencies are surfaced and managed early

### Typical Communication
- Partners with Project Managers on schedules and escalations
- Aligns with Product Managers on priorities and delivery sequencing
- Works with Tech Leads and engineering contributors to unblock dependencies
- Communicates status and risks to stakeholders for larger initiatives

---

## Tech Leads

### Role Summary
Tech Leads provide technical direction for implementation, guide architectural choices, and help the team balance delivery speed with maintainability and quality.

### Responsibilities
- Define or review technical approaches for major work
- Guide implementation decisions and architecture trade-offs
- Support estimation with technical context and risk identification
- Mentor developers and review design or code quality decisions
- Coordinate technical readiness for releases and operational handoffs

### Goals
- Deliver technically sound solutions
- Reduce rework and technical ambiguity
- Improve engineering consistency and maintainability

### Typical Communication
- Collaborates closely with Developers during implementation
- Advises Product Managers and Project Managers on technical scope and risk
- Partners with QA on testability and quality concerns
- Coordinates with Security and Platform roles on cross-cutting needs

---

## Release Managers

### Role Summary
Release Managers coordinate the planning, readiness, and execution of releases to reduce deployment risk and improve communication across teams.

### Responsibilities
- Maintain release calendars and deployment schedules
- Confirm completion of release checklists and readiness criteria
- Coordinate staging, production rollout, and rollback planning
- Ensure release notes and stakeholder communications are prepared
- Track release-specific risks, approvals, and post-release follow-up

### Goals
- Improve release predictability
- Reduce failed or chaotic deployments
- Create clear release ownership and communication paths

### Typical Communication
- Works with Project Managers on timing and coordination
- Partners with QA on release readiness validation
- Coordinates with SRE / Platform Engineers on deployment execution
- Notifies Stakeholders and Support teams of release timing and impact

---

## SRE / Platform Engineers

### Role Summary
SRE and Platform Engineers support service reliability, observability, deployment health, and operational readiness for production systems.

### Responsibilities
- Maintain observability, alerting, and operational tooling
- Support incident response, triage, and service recovery
- Help define reliability requirements for critical systems
- Review deployment readiness, rollback strategies, and runbooks
- Partner with teams to improve resilience and reduce recurring incidents

### Goals
- Improve system reliability and operational readiness
- Reduce incident frequency and mean time to recovery
- Strengthen visibility into production health

### Typical Communication
- Works with Developers and Tech Leads on reliability requirements
- Coordinates with Release Managers during deployment planning
- Supports Project Managers during escalations and incident follow-up
- Communicates operational concerns and trends to relevant stakeholders

---

## UX Researchers / Designers

### Role Summary
UX Researchers and Designers ensure solutions are usable, accessible, and aligned with user needs through research, design, and validation.

### Responsibilities
- Conduct user research and synthesize findings
- Create designs, flows, prototypes, or usability recommendations
- Help define user-centered acceptance criteria
- Validate designs with stakeholders and users when appropriate
- Support teams in making informed usability trade-offs

### Goals
- Improve customer experience and usability
- Reduce ambiguity in user-facing requirements
- Ensure solutions reflect real user needs

### Typical Communication
- Works with Product Managers to shape priorities and requirements
- Collaborates with Developers on implementation details
- Partners with QA to validate intended user behavior
- Shares insights with Stakeholders to support decision-making

---

## Security Engineers

### Role Summary
Security Engineers help teams identify, assess, and reduce security risk throughout planning, implementation, release, and incident response.

### Responsibilities
- Review security-sensitive changes and architecture decisions
- Perform threat modeling or risk assessment where needed
- Recommend mitigations, controls, and remediation priorities
- Support security testing, scanning, and incident response preparation
- Help teams document security-related operational expectations

### Goals
- Reduce the likelihood and impact of security issues
- Improve consistency in secure delivery practices
- Surface security risks early in the lifecycle

### Typical Communication
- Advises Developers and Tech Leads on secure implementation patterns
- Works with Project Managers to escalate significant risk or remediation needs
- Aligns with Product Managers on priority and trade-offs for security work
- Coordinates with SRE / Platform Engineers on incident and operational controls

---

## Support / Customer Success Leads

### Role Summary
Support and Customer Success Leads represent customer impact after release, helping teams understand operational pain points, recurring issues, and communication needs.

### Responsibilities
- Triage customer-reported issues and communicate impact
- Share recurring themes, adoption blockers, and support insights
- Coordinate release communications and readiness for customer-facing changes
- Help define support plans or known-issue guidance for launches
- Feed customer outcomes back into backlog and improvement discussions

### Goals
- Improve customer experience after release
- Shorten time to understand and respond to customer-impacting issues
- Strengthen the feedback loop between delivery teams and customers

### Typical Communication
- Works with Project Managers and Release Managers on communication planning
- Shares customer impact data with Product Managers for prioritization
- Coordinates with Developers, QA, and SRE on issue triage and resolution
- Helps Stakeholders understand adoption and support implications

---

## Stakeholders

### Role Summary
Stakeholders provide business context, approvals, feedback, and organizational alignment for project outcomes.

### Responsibilities
- Provide input on goals, constraints, and success measures
- Review milestones, major risks, and outcome progress
- Support prioritization, decisions, and escalations when needed
- Approve direction at key checkpoints when applicable

### Goals
- Ensure project outcomes align with business needs
- Maintain visibility into delivery progress and risk
- Support timely decision-making

### Typical Communication
- Receive regular project and milestone updates
- Participate in kickoff, reviews, and decision checkpoints
- Provide feedback on outcomes, priorities, and business impact

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
