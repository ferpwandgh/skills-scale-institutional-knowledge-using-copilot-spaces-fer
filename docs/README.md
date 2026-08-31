# OctoAcme Project Management Docs

Welcome to the OctoAcme Project Management documentation. This folder contains comprehensive guides for running projects successfully across the organization.

## Overview

**OctoAcme** is a project management approach built on five core principles that guide how teams plan, execute, and deliver value:

- **Customer-first**: Prioritize customer value and usability in every decision.
- **Iterative delivery**: Deliver small, testable increments rather than large monolithic releases.
- **Clear ownership**: Each project has named roles (Project Manager, Product Manager, Developers, QA) with defined responsibilities.
- **Data-informed decisions**: Measure impact, track metrics, and iterate based on evidence.
- **Psychological safety**: Encourage feedback, learning, and continuous improvement.

### Workflows & Delivery Approach

OctoAcme follows a lifecycle-based approach that moves projects through five stages: **Initiation**, **Planning**, **Execution**, **Release**, and **Close & Retrospective**. Each stage is supported by structured processes—from validating business need and stakeholder alignment during initiation, through breaking work into shippable increments in planning, to day-to-day execution using project boards with columns (Backlog, Ready, In Progress, In Review, QA, Done). Pull requests follow a lightweight discipline (≤400 lines, CI passes, one approval required), and quality is maintained through unit tests, integration tests, end-to-end smoke tests, security scanning, and manual QA when needed.

### Roles & Clear Ownership

Three core delivery roles drive each project: the **Project Manager (PM)** coordinates schedules, risks, and communications; the **Product Manager (PdM)** defines outcomes, prioritizes the backlog, and measures success; and **Developers** implement features while collaborating on design and testability. Stakeholders and QA teams provide inputs and validation. This clear ownership structure, paired with a communication cadence of weekly PM/PdM syncs, twice-weekly standups, and monthly stakeholder updates, ensures alignment and reduces single-points-of-failure.

### Risk & Communication Discipline

A **Risk Register** (ID, Description, Impact, Likelihood, Owner, Mitigation, Status) is maintained throughout the project lifecycle and reviewed weekly. Escalation follows a clear path: Team-level triage → PM escalation → Product Lead → Sponsor. Weekly status templates and incident communication playbooks keep stakeholders informed of progress, blockers, and decisions. This proactive communication and risk visibility help prevent surprises and enable rapid response to issues.

## Project Lifecycle & Guides

### 1. Initiation
📄 [OctoAcme Project Initiation Guide](./octoacme-project-initiation.md)  
Validate business need, align stakeholders, and create a lightweight plan.

### 2. Planning
📄 [OctoAcme Project Planning](./octoacme-project-planning.md)  
Break work into shippable increments, identify dependencies, and align timelines.

### 3. Execution & Tracking
📄 [OctoAcme Execution & Tracking](./octoacme-execution-and-tracking.md)  
Manage day-to-day execution, coordinate team rhythm, and track progress.

### 4. Risk Management & Communication
📄 [OctoAcme Risk Management & Communication](./octoacme-risks-and-communication.md)  
Identify, manage, and communicate risks and dependencies throughout the project.

### 5. Release & Deployment
📄 [OctoAcme Release & Deployment Guide](./octoacme-release-and-deployment.md)  
Standardize releases to production and manage deployment processes.

### 6. Retrospective & Continuous Improvement
📄 [OctoAcme Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)  
Capture learnings and convert them into actionable improvements.

## Reference Materials

📄 [OctoAcme Project Management Overview](./octoacme-project-management-overview.md)  
High-level introduction to roles, artifacts, and communication cadence.

📄 [OctoAcme Roles and Personas](./octoacme-roles-and-personas.md)  
Detailed descriptions of key roles (Developers, Product Managers, Project Managers) and their responsibilities.

## Quick Start for Teams

1. **Starting a new project?** Begin with [Project Initiation](./octoacme-project-initiation.md)
2. **Need to understand the process?** Start with [Project Management Overview](./octoacme-project-management-overview.md)
3. **Looking for templates or checklists?** Check the relevant phase guide for your needs
4. **Want to understand roles and responsibilities?** See [Roles and Personas](./octoacme-roles-and-personas.md)

## Project Lifecycle at a Glance

```
┌─────────────┐    ┌──────────┐    ┌───────────┐    ┌─────────┐    ┌────────────────┐
│ Initiation  │───→│ Planning │───→│ Execution │───→│ Release │───→│ Close & Retro  │
│             │    │          │    │           │    │         │    │                │
│ • One-pager │    │ • Backlog│    │ • Standups│    │ • Smoke │    │ • Retrospective│
│ • Align     │    │ • Estimate│   │ • PR work │    │   tests │    │ • Action items │
│ • Approve   │    │ • Risk   │    │ • Testing │    │ • Deploy│    │ • Close-out    │
└─────────────┘    └──────────┘    └───────────┘    └─────────┘    └────────────────┘
```

## Key Artifacts & Templates

Throughout the project lifecycle, you'll create and maintain several key artifacts:

- **Project One-pager** — Problem, Goal, Success Metrics, Stakeholders, Timeline, Risks
- **Risk Register** — ID, Description, Impact, Likelihood, Owner, Mitigation, Status
- **Project Board** — Backlog, Ready, In Progress, In Review, QA, Done
- **Sprint Backlog** — Prioritized stories with acceptance criteria and estimates
- **Weekly Status Update** — Progress, Next Steps, Risks & Blockers, Ask/Decisions
- **Release Notes** — Release name, date, summary, notable changes, migration steps
- **Retrospective Notes** — What went well, improvements, action items

## Communication Cadence

Stay aligned with regular touchpoints:

- **Daily**: Standups (15 min) — progress, blockers, dependencies
- **Weekly**: PM/PdM sync — roadmap, priorities, risks
- **Twice-weekly**: Delivery team standups (or per sprint agreement)
- **Monthly**: Stakeholder updates — progress, releases, next priorities
- **Ad-hoc**: Escalations and incident communication

---

**Last Updated:** August 31, 2026  
**Maintained by:** OctoAcme Project Management Team
