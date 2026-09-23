# OctoAcme Project Management Docs

## Overview

OctoAcme uses a structured, customer-first, iterative approach to project management that emphasizes clear ownership, data-informed decisions, and psychological safety. This collection of documents provides guidance for team members at all stages of a project lifecycle—from initial concept validation through retrospectives and continuous improvement.

## Project Management Lifecycle

### Initiation & Stakeholder Alignment
Projects begin with validation of the business problem and definition of success metrics. A lightweight one-pager documents the problem statement, objective, success metrics, primary stakeholders, timeline, risks, and proposed team. Stakeholders review and approve the initiative before the team proceeds to planning.

### Planning, Backlog & Dependencies
Once approved, the team conducts a kickoff meeting and creates a prioritized backlog with clear acceptance criteria. Work is estimated using story points or t-shirt sizing, the Definition of Done is documented, and dependencies and integration points are identified and tracked in a risk register.

### Iterative Execution & Quality Tracking
Delivery is organized into sprints or iterations with work tracked on a project board (Backlog → Ready → In Progress → In Review → QA → Done). Small pull requests are reviewed and tested through CI, linting, security scanning, and manual QA. Progress is monitored through daily standups, weekly delivery syncs, and demos at the end of each sprint or milestone.

### Risk & Communication Management
Risks are captured in a risk register with impact, probability, owner, and mitigation plan. Blockers are escalated from the delivery team to the Project Manager to the Product Lead to the Sponsor as needed. Stakeholders receive regular status updates, and a single source of truth (project README or release documentation) maintains consistency.

### Release & Deployment
Before release, all acceptance criteria must be met, CI/security scans must pass, release notes must be drafted, and a rollback plan must be documented. Releases are deployed to staging, validated with smoke tests, deployed to production, and verified post-deployment. A rollback procedure is in place for critical issues.

### Retrospectives & Continuous Improvement
After each sprint, release, or important milestone, the team holds a retrospective to capture learnings: what went well, what could improve, and 2–3 owned action items with due dates and success criteria. Action items are tracked and reviewed in weekly syncs.

## Core Roles

**Project Manager** — Coordinates delivery, manages schedules, risks, dependencies, and communications.  
**Product Manager** — Defines outcomes, prioritizes the backlog, and measures success.  
**Developers** — Implement features and fixes, collaborate on design and testability.  
**QA/Testing** — Validate quality and acceptance criteria.  
**Stakeholders** — Provide inputs, feedback, and approvals.

## Process Documents

- [Project Management Overview](octoacme-project-management-overview.md) — High-level introduction to OctoAcme principles, roles, artifacts, and lifecycle.
- [Project Initiation](octoacme-project-initiation.md) — Guidance for validating business need, aligning stakeholders, and deciding go/no-go.
- [Project Planning](octoacme-project-planning.md) — Steps to create a prioritized backlog, estimate work, and identify dependencies and risks.
- [Execution and Tracking](octoacme-execution-and-tracking.md) — Daily standups, sprint rhythms, PR workflow, quality assurance, and blocker escalation.
- [Risks and Communication](octoacme-risks-and-communication.md) — Risk register maintenance, stakeholder communication templates, and escalation paths.
- [Release and Deployment](octoacme-release-and-deployment.md) — Pre-release requirements, deployment checklist, rollback procedures, and release notes template.
- [Retrospective and Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — Running retrospectives, tracking action items, and building a continuous improvement culture.
- [Roles and Personas](octoacme-roles-and-personas.md) — Detailed responsibilities and goals for each team role.

## How to Use These Docs

- **New team members**: Start with the [Project Management Overview](octoacme-project-management-overview.md) to understand the OctoAcme approach.
- **Project kickoff**: Use the [Project Initiation](octoacme-project-initiation.md) guide and one-pager template.
- **Planning a project**: Follow the [Project Planning](octoacme-project-planning.md) guide to create your backlog, estimates, and risk register.
- **Daily delivery**: Refer to [Execution and Tracking](octoacme-execution-and-tracking.md) for standups, PR workflows, and escalation.
- **Managing risks and stakeholders**: Use [Risks and Communication](octoacme-risks-and-communication.md) templates and escalation paths.
- **Preparing a release**: Follow the [Release and Deployment](octoacme-release-and-deployment.md) checklist.
- **Retrospectives**: Use [Retrospective and Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) to capture learnings and track action items.
- **Understanding roles**: Consult [Roles and Personas](octoacme-roles-and-personas.md) for specific responsibilities and communication norms.

## Key Principles

- **Customer-first**: Prioritize customer value and usability.
- **Iterative delivery**: Deliver small, testable increments and gather feedback.
- **Clear ownership**: Each project has a named Project Manager and Product Lead.
- **Data-informed**: Measure impact and iterate based on evidence.
- **Psychological safety**: Encourage feedback, learning, and blameless problem-solving.
