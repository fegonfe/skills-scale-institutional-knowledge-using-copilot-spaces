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

## Engineering Leads

### Role Summary
Engineering Leads set technical direction and are accountable for the team's engineering quality and delivery health.

### Responsibilities
- Guide architecture, technical design, and engineering standards
- Make technical trade-off and escalation decisions
- Support estimation, sequencing, and delivery-risk management
- Mentor Developers and coordinate technical work across teams

### Goals
- Deliver sustainable technical solutions that meet product commitments
- Maintain code quality, reliability, and team delivery predictability
- Reduce technical risk and unplanned rework

### Typical Communication
- Technical design reviews and architecture decision records
- Regular delivery and risk alignment with Product Managers and Project Managers
- Coaching, code reviews, and day-to-day collaboration with Developers

### Role Interactions
Engineering Leads translate Product Manager priorities into technical approaches, partner with Project Managers on scope and delivery risks, and enable Developers through technical guidance and decisions.

---

## QA / Test Leads

### Role Summary
QA / Test Leads own the quality strategy and provide clear validation evidence for product changes.

### Responsibilities
- Define test strategy, quality gates, and acceptance-validation plans
- Coordinate test execution, defect triage, and quality reporting
- Identify quality risks and recommend release-readiness decisions
- Improve test coverage, automation, and defect-prevention practices

### Goals
- Prevent customer-impacting defects
- Provide timely, reliable quality signals for delivery decisions
- Increase confidence in releases through effective validation

### Typical Communication
- Test plans, quality dashboards, and defect-triage meetings
- Regular quality and release-readiness updates with Project Managers
- Collaboration on acceptance criteria with Product Managers and test coverage with Developers

### Role Interactions
QA / Test Leads clarify acceptance criteria with Product Managers, coordinate quality work and risks with Project Managers, and work with Developers to prevent, investigate, and resolve defects.

---

## Release Managers / Deployment Leads

### Role Summary
Release Managers / Deployment Leads coordinate release readiness and safe deployment of approved changes.

### Responsibilities
- Plan release schedules, deployment windows, and readiness reviews
- Confirm release criteria, approvals, rollback plans, and stakeholder notifications
- Coordinate deployment execution and monitor post-release outcomes
- Manage release risks, incidents, and communications during deployment

### Goals
- Deliver predictable, low-risk releases
- Minimize deployment disruption and recovery time
- Keep stakeholders informed of release status and impact

### Typical Communication
- Release calendars, readiness checklists, and go/no-go meetings
- Deployment updates and incident communications
- Coordination with Project Managers, QA / Test Leads, and Platform / DevOps Engineers

### Role Interactions
Release Managers / Deployment Leads align release scope and timing with Product Managers and Project Managers, rely on Developers and QA / Test Leads for readiness evidence, and coordinate deployments with Platform / DevOps Engineers.

---

## Security / Compliance Partners

### Role Summary
Security / Compliance Partners help teams identify, manage, and document security and regulatory risks throughout delivery.

### Responsibilities
- Review designs, changes, and processes for security and compliance requirements
- Define security controls, risk treatments, and required evidence
- Advise on threat modeling, secure development practices, and incident response
- Escalate material security or compliance risks to accountable stakeholders

### Goals
- Reduce security vulnerabilities and compliance exposure
- Enable teams to meet applicable policies and regulatory obligations
- Integrate security early enough to avoid late delivery surprises

### Typical Communication
- Design and risk reviews, security advisories, and compliance assessments
- Risk-register updates with Project Managers
- Requirement clarification with Product Managers and secure-design collaboration with Developers

### Role Interactions
Security / Compliance Partners help Product Managers account for security requirements, work with Project Managers to track risk decisions, and advise Developers on secure implementation and remediation.

---

## Platform / DevOps Engineers

### Role Summary
Platform / DevOps Engineers provide the environments, automation, observability, and infrastructure capabilities required for reliable delivery.

### Responsibilities
- Build and maintain CI/CD pipelines, environments, and infrastructure dependencies
- Improve deployment automation, monitoring, alerting, and operational reliability
- Support incident response, capacity planning, and operational troubleshooting
- Partner on infrastructure security, resilience, and cost management

### Goals
- Make delivery fast, repeatable, and reliable
- Improve service availability, observability, and recovery capability
- Reduce operational toil for Developers

### Typical Communication
- Infrastructure change reviews, operational dashboards, and incident channels
- Deployment planning with Release Managers / Deployment Leads
- Ongoing enablement and troubleshooting with Developers

### Role Interactions
Platform / DevOps Engineers enable Developers with delivery tooling and environments, coordinate operational dependencies with Project Managers, and provide feasibility and reliability input to Product Managers.

---

## Customer / User Representatives

### Role Summary
Customer / User Representatives bring direct user needs, usability insights, and business context into product and delivery decisions.

### Responsibilities
- Share user feedback, workflows, and pain points
- Participate in discovery, usability validation, and acceptance feedback
- Clarify business impact and customer priorities
- Communicate adoption concerns and post-release feedback

### Goals
- Ensure delivered solutions address real user needs
- Improve usability, adoption, and customer satisfaction
- Help teams validate value before and after release

### Typical Communication
- User interviews, feedback sessions, demos, and usability reviews
- Feedback summaries and prioritization discussions with Product Managers
- Stakeholder updates coordinated through Project Managers

### Role Interactions
Customer / User Representatives inform Product Manager prioritization and acceptance decisions, help Developers understand user workflows during discovery and demos, and work with Project Managers to coordinate feedback and stakeholder expectations.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
