# OctoAcme Project Management Overview

## Purpose
Provide a concise, shareable introduction to how OctoAcme runs projects so new teammates can quickly understand our approach, roles, and key artifacts.

## Scope
Applies to all cross-functional projects that deliver product features, services, or integrations.

## Principles
- Customer-first: prioritize customer value and usability.
- Iterative delivery: deliver small, testable increments.
- Clear ownership: each project has a named Project Manager (PM) and Product Lead.
- Data-informed decisions: measure impact and iterate based on evidence.
- Psychological safety: encourage feedback and learning.

## Core Roles
- Project Manager (PM): coordinates delivery, schedules, risk, communications.
- Product Manager (PdM): defines outcomes, prioritizes backlog, and measures success.
- Developers: implement features, collaborate on design and testability.
- QA/Testing: validate quality and acceptance criteria.
- Release Manager: coordinates release readiness, deployment, verification, and rollback readiness when applicable.
- UX/Design Lead: represents user needs and ensures usable, accessible designs.
- Data/Analytics Lead: defines success metrics and uses instrumentation and analysis to guide decisions.
- Security/Compliance Lead: identifies and manages security and compliance obligations.
- Stakeholders: provide inputs and approvals.

Assign each role to a named person or clarify that responsibilities are shared when a project does not have a dedicated role. The role is still accountable for the work, even if a person has a different title.

## Key Artifacts
- Project Charter / One-pager
- Roadmap and Release Plan
- Sprint/Iteration Backlog
- Acceptance Criteria & Definition of Done
- Risk and dependency register
- Release readiness checklist
- Instrumentation and success-metrics plan
- Security and compliance decision log
- Retrospective notes and action items

## Lifecycle (high-level)
1. Initiation: problem statement, stakeholders, high-level timeline.
2. Planning: scope, resources, milestones, dependencies, quality, release, accessibility, data, security, and compliance needs.
3. Execution: build, test, review, iterate, and validate outcomes.
4. Release: deploy, verify, announce, and confirm rollback readiness.
5. Close & Retrospective: capture learnings, confirm outcome measures, and define next steps.

## Communication Cadence
- Weekly sync between PM + PdM
- Twice-weekly standups for delivery team (or as agreed)
- Monthly stakeholder updates
- Release readiness reviews before production releases
- Design reviews for significant UX or accessibility decisions
- Data and experiment reviews for outcome measurement
- Security/compliance reviews when requirements or high-risk changes apply
- Ad-hoc escalations as needed

## How to use these docs
- Keep the Project Charter updated in the project repo.
- Use `octoacme-roles-and-personas.md` to identify ownership and cross-role handoffs.
- Add process-specific docs into `.copilot/` if you want Copilot Spaces to use them as context.
