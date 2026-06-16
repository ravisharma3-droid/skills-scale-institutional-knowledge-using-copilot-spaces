# OctoAcme Project Management Processes

Welcome to the OctoAcme project management documentation. This folder contains comprehensive guidance for running projects from initiation through closure, ensuring consistency, quality, and stakeholder alignment across all delivery efforts.

## Overview

OctoAcme uses a structured, iterative approach to project management grounded in these core principles:

- **Customer-first**: Prioritize customer value and usability in every decision
- **Iterative delivery**: Deliver small, testable increments to reduce risk and enable feedback
- **Clear ownership**: Each project has named Project Manager (PM) and Product Lead roles
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback, learning, and continuous improvement

## Project Lifecycle

OctoAcme projects follow a five-phase lifecycle:

1. **Initiation** — Validate business need, align stakeholders, define success criteria
2. **Planning** — Break work into shippable increments, identify dependencies, create backlog
3. **Execution** — Build, test, review, and iterate with daily standups and weekly syncs
4. **Release** — Deploy to production with smoke tests, verification, and rollback plans
5. **Close & Retrospective** — Capture learnings and convert them into actionable improvements

## Core Roles

- **Project Manager (PM)**: Coordinates delivery, manages schedules, risks, and communications
- **Product Manager (PdM)**: Defines outcomes, prioritizes backlog, measures success
- **Developers**: Implement features, collaborate on design, ensure testability and quality
- **QA/Testing**: Validates quality and acceptance criteria before release
- **Stakeholders**: Provide inputs, approvals, and strategic guidance

See [OctoAcme Personas](./octoacme-roles-and-personas.md) for detailed role definitions and responsibilities.

## Process Documents

### [OctoAcme Project Management Overview](./octoacme-project-management-overview.md)
High-level introduction to OctoAcme's approach, principles, roles, and key artifacts. Start here if you're new to our processes.

### [OctoAcme Project Initiation Guide](./octoacme-project-initiation.md)
Guidance for validating and authorizing new work. Covers problem statement, stakeholder alignment, success criteria, and the decision to move into planning.
- **Key Deliverable**: Project One-pager
- **Decision Gate**: Success metrics clear, stakeholders aligned, team available

### [OctoAcme Project Planning](./octoacme-project-planning.md)
Turn approved initiatives into actionable plans and prioritized backlogs. Covers backlog creation, estimation, risk management, and release planning.
- **Key Activities**: Kickoff, backlog prioritization, dependency mapping, DoD definition
- **Key Artifact**: Prioritized backlog with acceptance criteria and risk register

### [OctoAcme Execution & Tracking](./octoacme-execution-and-tracking.md)
Guidance for day-to-day execution, progress tracking, and maintaining delivery momentum. Covers standups, PR workflows, quality standards, and blocker escalation.
- **Team Rhythm**: Daily standups, weekly delivery sync, sprint demos
- **Quality Standards**: Unit tests, integration tests, security scanning, manual QA
- **Key Metrics**: Velocity, burndown, success metrics, error rates, latency

### [OctoAcme Risk Management & Communication](./octoacme-risks-and-communication.md)
Explain how to identify, manage, and communicate risks, dependencies, and stakeholder updates. Covers risk registers, escalation paths, and incident response.
- **Risk Lifecycle**: Identify → Assess → Mitigate → Monitor
- **Escalation Paths**: Team-level → PM → Product Lead → Sponsor
- **Communication Cadence**: Weekly status updates, monthly stakeholder briefings

### [OctoAcme Release & Deployment Guide](./octoacme-release-and-deployment.md)
Standardize release processes to reduce risk and improve observability. Covers release types, pre-release requirements, deployment checklists, and rollback procedures.
- **Release Types**: Patch (hotfixes), Minor (features), Major (breaking changes)
- **Pre-release Checklist**: All AC met, CI passing, security scans, smoke tests, rollback plan
- **Post-deploy**: Verification, stakeholder announcement, incident playbook

### [OctoAcme Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
Capture learnings after sprints, releases, or incidents and convert them into actionable improvements. Covers retrospective structure, action item tracking, and continuous improvement culture.
- **When**: After each sprint, release, or milestone
- **Structure**: What went well, improvements, action items with owners and due dates
- **Key Outcome**: Iterative improvements that increase team velocity and quality

### [OctoAcme Personas](./octoacme-roles-and-personas.md)
Detailed definitions of typical roles and responsibilities: Developers, Product Managers, and Project Managers. Use these personas to frame scenarios and guide role-specific interactions.

## Key Artifacts & Templates

Across these processes, you'll create and maintain:

- **Project Charter / One-pager** — Problem, goal, success metrics, stakeholders, timeline, risks
- **Prioritized Backlog** — With acceptance criteria, estimates, and ownership
- **Risk Register** — ID, description, impact, likelihood, mitigation, owner, status
- **Release Plan & Milestones** — Timeline and key delivery dates
- **Definition of Done (DoD)** — Quality and acceptance standards for all work
- **Retrospective Notes & Action Items** — Learnings and iterative improvements
- **Release Notes** — Summary of changes, migration steps, known issues

## Communication Cadence

- **Daily**: Standups (15 min) — Progress, blockers, dependencies
- **Weekly**: PM + PdM sync, delivery team standups (2x), risk register review
- **Bi-weekly/Monthly**: Stakeholder updates and status reports
- **Ad-hoc**: Escalations, incident response, cross-team coordination

## Quick Start

**New to OctoAcme?**
1. Read [OctoAcme Project Management Overview](./octoacme-project-management-overview.md) for the big picture
2. Review [OctoAcme Personas](./octoacme-roles-and-personas.md) to understand your role
3. Navigate to the relevant phase document based on where your project is in the lifecycle

**Starting a new project?**
1. Follow [OctoAcme Project Initiation Guide](./octoacme-project-initiation.md) to validate the idea
2. Move to [OctoAcme Project Planning](./octoacme-project-planning.md) once approved
3. Use [OctoAcme Execution & Tracking](./octoacme-execution-and-tracking.md) during delivery

**Managing risks or escalating issues?**
- Reference [OctoAcme Risk Management & Communication](./octoacme-risks-and-communication.md) for escalation paths and communication templates

**Ready to release?**
- Follow [OctoAcme Release & Deployment Guide](./octoacme-release-and-deployment.md) for pre-release checks and deployment procedures

**Wrapping up a project?**
- Use [OctoAcme Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) to capture learnings and plan improvements

## Contributing to Process Docs

Found a gap, want to clarify a process, or propose an improvement? Open an issue using the **[Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)** template in `.github/ISSUE_TEMPLATE/`.

---

**Last Updated**: June 2026  
**Maintained by**: OctoAcme Project Management Community
