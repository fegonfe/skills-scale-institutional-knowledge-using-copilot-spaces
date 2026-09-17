# OctoAcme Project Management Docs

This folder contains OctoAcme's project management process documentation. Use this page as the starting point for understanding how we run projects and to find the right process document quickly.

## Overview of OctoAcme Project Management

OctoAcme follows a customer-first, iterative delivery lifecycle that moves work from initiation through planning, execution, release, and retrospective. Projects start with a one-pager that defines the problem, a SMART goal, success metrics, stakeholders, timeline, risks, and resource needs. Once stakeholders agree on priority, success measures, and team availability, the initiative is approved and moves into planning, which includes a kickoff, backlog creation, estimation, acceptance criteria, a Definition of Done, dependency identification, and release milestone mapping.

Roles are clearly defined. Project Managers coordinate schedules, risks, resources, meetings, documentation, and stakeholder communication. Product Managers define outcomes, prioritize the backlog, and measure customer and business impact. Developers implement and test features, participate in reviews, and surface technical risks, while QA and testing partners validate acceptance criteria and product quality. Stakeholders and sponsors provide input, approvals, and escalation support.

During execution, teams track work on a project board with stages such as Backlog, Ready, In Progress, In Review, QA, and Done. Work is delivered through small pull requests that reference issues and acceptance criteria, with automated tests and linting required before review and at least one approval before merging. Communication follows a regular rhythm of standups, weekly delivery syncs, demos, and stakeholder updates. Risks and dependencies are kept in a register, reviewed weekly, and escalated from the team to the PM, Product Lead, and sponsor when needed.

Quality assurance is embedded throughout the lifecycle: unit tests, integration tests, end-to-end smoke tests for critical flows, security scanning, manual QA when needed, and CI checks. Before release, acceptance criteria must be met, CI and security checks must pass, release notes and rollback plans must be prepared, and staging smoke tests must succeed. After deployment, teams verify the release, communicate it, and use incident response and retrospectives to capture lessons, prioritizing a small number of owned, time-bound improvements so feedback becomes measurable, continuous improvement.

## Documentation Index

- [OctoAcme Project Management Overview](octoacme-project-management-overview.md) — principles, roles, artifacts, and lifecycle at a glance.
- [Project Initiation](octoacme-project-initiation.md) — one-pager, goals, success metrics, and approval to proceed.
- [Project Planning](octoacme-project-planning.md) — kickoff, backlog, estimation, acceptance criteria, and milestones.
- [Execution and Tracking](octoacme-execution-and-tracking.md) — project board workflow, pull requests, and delivery cadence.
- [Risks and Communication](octoacme-risks-and-communication.md) — risk register, escalation paths, and stakeholder updates.
- [Release and Deployment](octoacme-release-and-deployment.md) — release readiness, deployment, verification, and rollback.
- [Retrospective and Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — retrospectives and action item follow-through.
- [Roles and Personas](octoacme-roles-and-personas.md) — responsibilities of PMs, PdMs, developers, QA, and stakeholders.

## Keeping This Index Current

When a process document is added, removed, or renamed in this folder, update the documentation index above in the same change so the links stay accurate.
