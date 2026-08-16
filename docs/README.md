# OctoAcme Project Management Documentation

## Overview
OctoAcme runs projects with a customer-first, iterative approach that emphasizes clear ownership, measurable outcomes, and continuous improvement. Our process guides teams from lightweight initiation through planning, execution, release, and retrospective phases. These docs collect the core principles, ceremonies, artifacts, and role expectations the team uses to plan, deliver, and learn.

## Project Management Processes Summary
OctoAcme organizes work around a clear, iterative project lifecycle that starts with a lightweight initiation (Project One-pager) and moves into planning, execution, release, and retrospective phases. Early work focuses on validating the problem, stakeholders, success metrics, and a high-level timeline before creating a prioritized backlog and release plan. Planning uses standard artifacts—one-pagers, backlog items with acceptance criteria, a Definition of Done, and a Risk Register—so work is decomposed into shippable increments during sprint/iteration planning. Day-to-day execution is managed on a project board with columns like Backlog, Ready, In Progress, In Review, QA, and Done to visualize flow and surface dependencies.

Key workflows include a disciplined pull request process (small PRs—target <= 400 lines—linked to issues and acceptance criteria, with CI checks and at least one approval required) and a release pipeline that distinguishes patch, minor, and major releases. Pre-release and deployment checklists require passing CI and security scans, drafted release notes, smoke tests in staging, a rollback plan, and post-deploy verification. The release playbook also includes an incident/rollback procedure and stakeholder communication steps.

Roles and responsibilities are explicitly defined so ownership and expectations are clear: Product Managers set outcomes and success metrics; Project Managers coordinate schedules, risks, and communication; Developers implement and test features; and QA validates acceptance criteria. These personas are used throughout the docs to shape who runs kickoffs, owns the Risk Register entries, facilitates retrospectives, and tracks action items back into the backlog.

Communication and quality assurance are embedded into the rhythm and tooling: short daily standups (15 minutes) to surface blockers, weekly delivery syncs and PM–PdM alignments, and monthly stakeholder updates. QA practices require unit tests, integration tests where applicable, and end-to-end smoke tests for critical flows; security scanning runs in CI and manual QA is used for feature acceptance when needed. Risk management is formalized via a register (ID, description, impact, likelihood, owner, mitigation, status) and escalation paths—from team triage through PM and Product Lead up to sponsor-level escalation—so risks are assessed, mitigated, and communicated on a predictable cadence.

## Project Lifecycle
1. Initiation — Validate problem, stakeholders, and outcomes (one-pager).
2. Planning — Convert approved initiatives into a prioritized backlog, estimates, DoD, and release plan.
3. Execution — Implement, test, review, and integrate using the project board and PR policy.
4. Release — Deploy using the release checklist, smoke tests, and rollback procedures.
5. Close & Improve — Run retrospectives, convert action items to backlog work, and iterate.

## Documentation by Phase

### Overview
- **[Project Management Overview](./octoacme-project-management-overview.md)** — Concise introduction to OctoAcme's approach, roles, and key artifacts

### Initiation
- **[Project Initiation Guide](./octoacme-project-initiation.md)** — Define initial steps, validate need, align stakeholders
- **[Roles and Personas](./octoacme-roles-and-personas.md)** — Understand team roles and responsibilities

### Planning
- **[Project Planning](./octoacme-project-planning.md)** — Break work into shippable increments, identify risks

### Execution
- **[Execution & Tracking](./octoacme-execution-and-tracking.md)** — Manage day-to-day execution and progress
- **[Risk Management & Communication](./octoacme-risks-and-communication.md)** — Identify and manage risks

### Release
- **[Release & Deployment Guide](./octoacme-release-and-deployment.md)** — Standardize releases and deployments

### Close & Improve
- **[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings and iterate

## Quick Start (by role)
- Product Managers: Read Overview, Initiation, Roles and Personas, Planning.
- Project Managers: Read Overview, Planning, Execution & Tracking, Risk Management.
- Developers: Read Execution & Tracking, Release & Deployment, Roles and Personas.
- QA: Read Execution & Tracking, Retrospectives, Release & Deployment.

## Where to start
1. Read this README and the Project Management Overview.
2. If you’re proposing a new project or feature, complete the Project One-pager (Initiation).
3. Follow Planning to create backlog items with acceptance criteria and DoD.
4. Use the Execution docs and PR workflow during delivery; add risks to the Risk Register.
5. Finish with Release steps and a Retrospective to capture improvements.
