# OctoAcme Project Management Documentation

Welcome to the OctoAcme project management process documentation. This folder contains guides and templates for running projects collaboratively, delivering customer value, and continuously improving our processes.

## Quick Overview

OctoAcme uses a **five-phase lifecycle** to structure all project work:

1. **Initiation** — Validate business need, align stakeholders, and create a lightweight project one-pager
2. **Planning** — Break work into shippable increments, estimate scope, and define clear acceptance criteria
3. **Execution** — Build, test, review, and iterate with a consistent team rhythm and quality standards
4. **Release** — Deploy to production with standardized checklists, smoke tests, and rollback plans
5. **Close & Retrospective** — Capture learnings and convert them into actionable improvements

## Core Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named Project Manager (PM) and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Key Roles

- **Project Manager (PM)** — Coordinates delivery, manages schedules, risks, and communications
- **Product Manager (PdM)** — Defines outcomes, prioritizes the backlog, and measures success
- **Developers** — Implement features while collaborating on design and maintaining quality standards
- **QA/Testing** — Validates quality and acceptance criteria
- **Stakeholders** — Provide inputs, approvals, and strategic direction

## Team Rhythm & Communication

- **Daily standups** (15 min) — Focus on progress, blockers, and dependencies
- **Weekly delivery sync** — Review progress, updates, and flagged risks
- **Weekly PM + PdM sync** — Strategic alignment and planning
- **Monthly stakeholder updates** — High-level status and key milestones
- **Sprint demos/reviews** — Show progress and gather feedback at the end of each sprint or milestone

## Key Workflows

### Planning & Backlog Management
- Prioritized backlog with clear acceptance criteria
- Scope estimated using T-shirt sizing or story points
- Definition of Done documented before work begins
- Dependencies and integration points identified upfront

### Execution & Quality Assurance
- Pull Request workflow with small PRs (≤ 400 lines when possible)
- Automated testing and linting in CI before review
- At least one approval required before merging
- Unit tests, integration tests, and end-to-end smoke tests for critical flows
- Security scanning in CI
- Manual QA for feature acceptance when needed

### Risk Management
- Risk Register capturing ID, description, impact, probability, owner, and mitigation
- Three-level escalation path:
  - Level 1: Team-level triage in daily standup
  - Level 2: PM escalates to Product Lead and dependent teams
  - Level 3: Sponsor-level escalation for business-impacting issues
- Weekly risk review in syncs and continuous monitoring

### Release & Deployment
- Three release types: Patch (hotfixes), Minor (incremental features), Major (significant changes)
- Pre-release checklist ensuring acceptance criteria met, CI passing, and rollback plans documented
- Deployment to staging with smoke tests before production
- Post-deploy verification and stakeholder announcement

### Continuous Improvement
- Retrospectives after each sprint, release, or milestone (45–75 minutes)
- Capture what went well, what could improve, and actionable items (2–3 per retro)
- Track and measure impact of improvements
- Review outstanding action items in weekly syncs

## Documentation Structure

This folder contains:

- **`octoacme-project-management-overview.md`** — High-level introduction to OctoAcme's approach, roles, and artifacts
- **`octoacme-project-initiation.md`** — Steps to validate and authorize new work, align stakeholders, and create a lightweight plan
- **`octoacme-project-planning.md`** — Guidance for breaking work into shippable increments and managing dependencies
- **`octoacme-execution-and-tracking.md`** — Day-to-day execution, team rhythm, PR workflows, and quality assurance
- **`octoacme-risks-and-communication.md`** — Risk management, escalation paths, and stakeholder communication templates
- **`octoacme-release-and-deployment.md`** — Standardized release and deployment processes with checklists and playbooks
- **`octoacme-retrospective-and-continuous-improvement.md`** — How to run retrospectives and track improvements
- **`octoacme-roles-and-personas.md`** — Definitions of typical roles and responsibilities
- **`octoacme-roles-and-personas.md`** — Definitions of typical roles (Developers, Product Managers, Project Managers, Scrum Masters, UX Designers, QA Leads, Release Managers, Business Analysts) and their responsibilities
- **`octoacme-roles-overview-matrix.md`** — Quick reference matrix showing role interactions, responsibility boundaries, and how roles collaborate across the project lifecycle

## Getting Started

1. **New to OctoAcme?** Start with [`octoacme-project-management-overview.md`](./octoacme-project-management-overview.md) for a concise introduction.
2. **Kicking off a project?** Follow the steps in [`octoacme-project-initiation.md`](./octoacme-project-initiation.md).
3. **In execution?** Reference [`octoacme-execution-and-tracking.md`](./octoacme-execution-and-tracking.md) for day-to-day guidance.
4. **Ready to release?** Check [`octoacme-release-and-deployment.md`](./octoacme-release-and-deployment.md).
5. **Running a retrospective?** See [`octoacme-retrospective-and-continuous-improvement.md`](./octoacme-retrospective-and-continuous-improvement.md).

## Contributing

To suggest updates or add new content to these process documents, please use the issue template: **"Add Content to Project Management Process Docs"** (`.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml`).

---

For questions or feedback on these processes, reach out to your Project Manager or Product Lead.
