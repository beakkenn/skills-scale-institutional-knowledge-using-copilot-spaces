# OctoAcme Project Management Documentation

## Getting Started
Welcome to the OctoAcme project management framework. This README is the central entry point for our process documentation and helps new team members and stakeholders find the right guidance for each project stage.

## Overview
OctoAcme follows a lightweight, iterative project management approach that emphasizes clear ownership, measurable outcomes, and continuous improvement. Work progresses through a defined lifecycle: Initiation (validate problem and align stakeholders), Planning (create backlog, estimates, and a release plan), Execution & Tracking (iterative delivery with PR and CI practices), Release & Deployment (pre-release checks, smoke tests, rollback plans), and Close & Retrospective (capture learnings and track action items). Key artifacts include the Project One-pager, roadmap, backlog, acceptance criteria, risk register, and retrospective notes.

## High-level Summary
Teams organize work on a project board (Backlog → Ready → In Progress → In Review → QA → Done) and follow a pull request workflow that favors small, reviewable changes, links PRs to issues and acceptance criteria, and requires automated CI (tests and linting) and at least one approval before merging. Planning is timeboxed and focuses on shippable increments; risks and dependencies are tracked in a simple risk register and escalated along defined paths when necessary.

## Process Principles
- Customer-first: prioritize customer value and usability
- Iterative delivery: deliver small, testable increments
- Clear ownership: each project has a named Project Manager (PM) and Product Lead
- Data-informed decisions: measure impact and iterate based on evidence
- Psychological safety: encourage feedback and learning

## Quick Links by Project Stage

**1. Project Initiation**
- [Project Initiation Guide](octoacme-project-initiation.md) - Define business need, stakeholders, and initial timeline

**2. Project Planning**
- [Project Planning](octoacme-project-planning.md) - Create backlog, estimates, dependencies, and release plan

**3. Execution & Tracking**
- [Execution & Tracking](octoacme-execution-and-tracking.md) - Day-to-day delivery, quality standards, reporting

**4. Risk & Communication**
- [Risk Management & Communication](octoacme-risks-and-communication.md) - Identify, track, and escalate risks; manage stakeholder communication

**5. Release & Deployment**
- [Release & Deployment](octoacme-release-and-deployment.md) - Standardize release process and rollback procedures

**6. Retrospective & Continuous Improvement**
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) - Capture learnings and drive improvements

## Reference
- [Project Management Overview](octoacme-project-management-overview.md) - High-level framework, principles, roles, and communication cadence
- [Roles & Personas](octoacme-roles-and-personas.md) - Detailed role definitions and responsibilities

## Roles & Responsibilities (Quick Reference)
- Project Manager (PM): coordinates delivery, schedules, risks, and communications
- Product Manager (PdM): defines outcomes, prioritizes the backlog, and measures success
- Developers: implement features, write tests, and participate in reviews
- QA/Testing: validate quality and acceptance criteria
- Stakeholders: provide inputs and approvals

## Quality & Assurance Practices
- Unit and integration tests for new logic
- End-to-end smoke tests for critical flows before release
- Security scanning in CI
- Manual QA when required for acceptance
- Pre-release smoke tests in staging and documented rollback plans

## Communication Cadence & Meetings
- Daily standups for progress, blockers, and dependencies
- Weekly delivery syncs for progress, flagged risks, and demos
- Weekly PM + PdM alignment
- Monthly stakeholder updates
- Ad-hoc escalations and incident communication as needed

## How to use these docs
- Start with the Project Management Overview for principles and lifecycle
- Follow the Quick Links for stage-specific guidance
- Keep the Project One-pager and project README updated in the project repo
- Add process-specific docs into `.copilot/` if you want Copilot Spaces to use them as context

## Acceptance Criteria for this README
- [x] Content aligns with existing process docs
- [x] Update improves clarity and discoverability
- [ ] Proposed content has been reviewed with stakeholders (if needed)

---

## Brief Process Summary

OctoAcme structures work through a clear lifecycle: Initiation (one‑pagers and stakeholder alignment), Planning (kickoffs, prioritized backlog, estimates, Definition of Done, release timelines), Execution (iterative development with delivery tracking), Release (pre‑release checks, smoke tests, rollback plans), and Close & Retrospective (action items and continuous improvement). Key artifacts include the Project One‑pager, roadmap/release plan, sprint/iteration backlog, acceptance criteria/DoD, and a living risk register. Decision gates require clear success metrics and stakeholder agreement before moving from initiation into planning.

Operational workflows emphasize small, reviewable changes and visible work tracking. Teams use a project board with Backlog → Ready → In Progress → In Review → QA → Done, and a pull request workflow that favors small PRs (<= ~400 lines), links to issues and acceptance criteria, and requires CI (tests and linting) and at least one approval before merging. Planning uses timeboxed sprint planning and standard backlog templates to keep scope shippable and traceable.

Roles, communication, and quality practices are explicit: Product Manager defines outcomes and success metrics; Project Manager coordinates schedules, risks, and stakeholder communication; Developers implement and test; QA validates acceptance. Communication cadence includes daily standups, weekly delivery syncs, weekly PM+PdM alignment, monthly stakeholder updates, and defined escalation paths. Quality is enforced through automated tests, CI security scans, manual QA when needed, pre-release smoke tests, and a documented incident/rollback playbook. Retrospectives capture prioritized action items that are tracked into the backlog to drive measurable continuous improvement.
