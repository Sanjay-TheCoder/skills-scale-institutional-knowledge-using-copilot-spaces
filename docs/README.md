# OctoAcme Project Management Docs

Welcome to the OctoAcme Project Management Documentation. This folder contains comprehensive guides for running projects at OctoAcme—from initial concept through retrospective and continuous improvement.

## What is OctoAcme?

OctoAcme is a customer-first, iterative project management approach built on clear ownership, data-informed decisions, and psychological safety. Our methodology emphasizes delivering measurable value through well-coordinated cross-functional teams.

## OctoAcme Project Management Approach

OctoAcme's project management framework integrates clear roles, structured communication, and quality discipline across a five-phase lifecycle. Work begins with validated business need and a lightweight project one-pager that defines the problem, goals, success metrics, stakeholders, timeline, risks, and team roles. Once approved, teams move into planning where the backlog is prioritized, acceptance criteria are defined, dependencies are surfaced, and a release plan is created. This ensures every project has a visible path from concept to delivery.

The operating model centers on explicit roles with distinct responsibilities: Product Managers define customer value and prioritize outcomes; Project Managers coordinate scheduling, communications, and risks; Developers design, build, and test software against acceptance criteria; QA validates quality; and Stakeholders provide strategic input. Communication is structured and regular—daily standups surface blockers, weekly delivery syncs review progress and risks, and milestone demos confirm value and alignment. Throughout execution, teams maintain a risk register, use project boards for transparency, and keep documentation as a single source of truth.

Quality assurance is continuous rather than a final checkpoint. The process requires clear acceptance criteria, unit and integration testing, small pull requests with at least one approval before merge, and security scanning in CI. Post-release verification and retrospectives help teams learn from both successes and incidents. Risk management is proactive—risks are identified during planning, assessed for impact and likelihood, mitigated through action plans, and reviewed in weekly syncs. Stakeholder communication is intentional, with regular status updates, escalation paths that move from team level to PM to Product Lead to Sponsor, and dedicated incident communication playbooks.

## Project Lifecycle Overview

Every OctoAcme project follows five key phases:

1. **Initiation**: Validate business need, align stakeholders, and create a lightweight plan
2. **Planning**: Break work into shippable increments, identify dependencies, and align timelines
3. **Execution**: Build, test, review, and iterate with regular standups and demos
4. **Release**: Deploy to production with confidence through pre-release verification and rollback planning
5. **Retrospective**: Capture learnings and convert them into actionable improvements

## Core Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named PM and Product Manager
- **Data-informed**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Process Documentation

### Getting Started
- **[OctoAcme Project Management Overview](./octoacme-project-management-overview.md)** — Start here to understand roles, artifacts, and communication cadence
- **[OctoAcme Roles & Personas](./octoacme-roles-and-personas.md)** — Understand typical roles and responsibilities

### Project Phases
- **[Project Initiation Guide](./octoacme-project-initiation.md)** — Validate and authorize new work
- **[Project Planning](./octoacme-project-planning.md)** — Turn initiatives into actionable plans
- **[Execution & Tracking](./octoacme-execution-and-tracking.md)** — Manage day-to-day delivery
- **[Release & Deployment Guide](./octoacme-release-and-deployment.md)** — Standardize production releases
- **[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings and iterate

### Cross-Cutting Concerns
- **[Risk Management & Communication](./octoacme-risks-and-communication.md)** — Manage risks, dependencies, and stakeholder communication

## How to Use These Docs

**For Project Managers**: Start with [Project Management Overview](./octoacme-project-management-overview.md), then follow the phase-specific guides

**For Product Managers**: See [Project Initiation](./octoacme-project-initiation.md) and [Risk & Communication](./octoacme-risks-and-communication.md)

**For Developers**: Review [Execution & Tracking](./octoacme-execution-and-tracking.md) and your project's acceptance criteria

**For New Team Members**: Start with [Roles & Personas](./octoacme-roles-and-personas.md), then read the [Overview](./octoacme-project-management-overview.md)

## Contributing to These Docs

These documents are living artifacts. If you identify gaps, improvements, or new best practices, please create an issue using the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template.
