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

## Release Managers

### Role Summary
Release Managers coordinate release readiness and the safe movement of approved changes into production environments.

### Responsibilities
- Maintain the release calendar and deployment sequence
- Coordinate deployment windows, approvals, and communications
- Verify operational and rollback readiness with engineering and QA
- Track release evidence, issues, and follow-up actions
- Facilitate go/no-go decisions and incident handoffs

### Goals
- Deliver predictable, low-risk releases
- Ensure every release has clear ownership and rollback procedures
- Improve repeatability and release traceability

### Typical Communication
- Release readiness reviews and go/no-go meetings
- Deployment plans and release runbooks
- Release status updates to stakeholders

### Interactions
- Partners with the Project Manager on schedules, dependencies, risks, and approvals.
- Works with Developers on deployment packages, configuration, rollback steps, and operational checks.
- Works with QA/Testing on acceptance evidence and release-specific validation.
- Escalates unresolved release risks to the Project Manager and relevant stakeholders.

---

## UX/Design Leads

### Role Summary
UX/Design Leads translate user and customer needs into accessible, consistent, and usable product experiences.

### Responsibilities
- Facilitate discovery and clarify user problems
- Create and validate workflows, prototypes, and interaction specifications
- Define accessibility, usability, and design-system requirements
- Facilitate usability testing and incorporate findings
- Support developers and QA with design intent and review

### Goals
- Improve usability, accessibility, and consistency
- Reduce rework caused by late or unclear design decisions
- Ensure implementation reflects validated user needs

### Typical Communication
- Discovery and design workshops
- Prototypes, design specifications, and usability findings
- Design reviews and accessibility checks

### Interactions
- Collaborates with Product Managers on problem framing, priority, and solution validation.
- Works with Developers and QA/Testing to clarify feasible behavior and acceptance criteria.
- Brings user feedback and design risks to planning and stakeholder reviews.
- Escalates unresolved experience or accessibility conflicts to the Product Manager and Project Manager.

---

## Data/Analytics Leads

### Role Summary
Data/Analytics Leads define how project outcomes will be measured, validate data quality, and convert evidence into recommendations.

### Responsibilities
- Define outcome, product, and operational success metrics
- Design instrumentation and analytics requirements
- Create dashboards and reporting plans
- Validate measurement quality and interpret experiment or usage results
- Recommend adjustments based on evidence

### Goals
- Make project outcomes measurable and observable
- Improve the quality and speed of data-informed decisions
- Detect data gaps before they affect prioritization or reporting

### Typical Communication
- Metrics planning and instrumentation reviews
- Dashboards and analysis summaries
- Experiment readouts and decision recommendations

### Interactions
- Partners with Product Managers to translate outcomes into success metrics and questions.
- Works with Developers to implement and test instrumentation and event schemas.
- Works with QA/Testing to validate measurement and data quality.
- Provides Project Managers with evidence for status, risks, and trade-offs.

---

## Security/Compliance Leads

### Role Summary
Security/Compliance Leads identify applicable obligations and help the team design, deliver, and evidence secure and compliant solutions.

### Responsibilities
- Identify security, privacy, regulatory, and contractual requirements
- Coordinate threat, architecture, and control reviews
- Advise developers and operators on required safeguards
- Track risks, exceptions, remediation, and approval evidence
- Verify that compliance claims and release controls are supportable

### Goals
- Reduce avoidable security and compliance risk
- Make obligations explicit and testable
- Improve auditability and evidence quality

### Typical Communication
- Security and compliance reviews
- Risk and exception records
- Remediation plans and approval evidence

### Interactions
- Works with Product Managers and Project Managers to balance requirements, risk, scope, and schedule.
- Advises Developers on secure design and required fixes.
- Works with QA/Testing to define and verify control checks.
- Escalates unacceptable risk or missing approvals through the Project Manager and appropriate stakeholders.

---

## Role Interaction and Handoff Guidance

Use the following guidance to assign ownership without making every project carry a full specialist team:

| Role | Primary handoff | Collaborates with | Escalation point |
| --- | --- | --- | --- |
| Product Manager | Defines outcome and acceptance intent | Project Manager, Developers, UX/Design, Data/Analytics | Project Manager and relevant stakeholders |
| Project Manager | Coordinates plan, risks, and decisions | All delivery and specialist roles | Sponsor or accountable stakeholder |
| Developer | Implements approved behavior and safeguards | Product Manager, UX/Design, QA/Testing, Data/Analytics, Security/Compliance | Project Manager and technical lead |
| QA/Testing | Provides quality and acceptance evidence | Developers, Product Manager, Release Manager, UX/Design | Project Manager |
| Release Manager | Confirms readiness and executes or coordinates release | Project Manager, Developers, QA/Testing | Project Manager and release authority |
| UX/Design Lead | Defines and validates the intended experience | Product Manager, Developers, QA/Testing | Product Manager |
| Data/Analytics Lead | Defines and validates outcome evidence | Product Manager, Developers, QA/Testing, Project Manager | Product Manager |
| Security/Compliance Lead | Defines obligations and validates safeguards | Product Manager, Developers, QA/Testing, Project Manager | Project Manager or compliance authority |

Assign a named owner for each applicable role in the Project Charter or delivery plan. If a dedicated role is absent, document who is responsible for the work and preserve the handoff, evidence, and escalation requirements.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
