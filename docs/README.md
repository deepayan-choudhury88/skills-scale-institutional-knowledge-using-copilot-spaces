# OctoAcme Project Management Documentation

## Quick Start

Welcome to OctoAcme's project management guidance. This collection standardizes how we run projects to deliver value consistently. Whether you're a new team member onboarding or looking for specific process guidance, this README serves as your central hub for all project management documentation.

---

## OctoAcme Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has named leads with defined responsibilities
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

---

## Project Management Overview

OctoAcme follows a structured five-phase project lifecycle: **Initiation**, **Planning**, **Execution**, **Release**, and **Retrospective**. 

### Key Workflows & Practices

**Initiation & Planning**: During initiation, teams validate business needs and create a lightweight Project One-pager that establishes success metrics, stakeholder alignment, and a high-level timeline. The planning phase transforms approved initiatives into actionable backlogs with prioritized, estimated work items and a defined release plan.

**Execution & Quality**: Execution focuses on iterative delivery using GitHub Projects with standardized workflows (branching conventions, small PRs ≤400 lines, mandatory CI checks, and at least one approval before merging). Quality is embedded throughout via unit tests, integration tests, end-to-end smoke tests, CI-based security scanning, and manual QA for feature acceptance.

**Release & Learning**: Release and deployment are governed by pre-release checklists, smoke tests, and rollback playbooks. Finally, retrospectives are held after each sprint, release, or milestone to capture learnings and drive continuous improvement through prioritized action items.

### Roles & Communication

OctoAcme emphasizes **clear ownership** across four primary personas:
- **Project Managers**: Coordinate delivery, manage risks and schedules, facilitate stakeholder communication
- **Product Managers**: Define outcomes, prioritize the backlog, measure success through data-driven decisions
- **Developers**: Implement features, write tests, participate in reviews, surface technical risks
- **QA/Testing**: Validate quality and acceptance criteria

Communication is structured through a consistent rhythm: daily standups (15 min), weekly delivery syncs, twice-weekly team standups, monthly stakeholder updates, and a three-level escalation path (Team → PM → Product Lead → Sponsor) to triage issues efficiently.

---

## Documentation Index

### Foundation & Overview

- **[Project Management Overview](./octoacme-project-management-overview.md)** — How OctoAcme runs projects, core roles, key artifacts, and communication cadence
- **[Roles & Personas](./octoacme-roles-and-personas.md)** — Detailed responsibilities, goals, and communication styles for Developers, Product Managers, and Project Managers

### Project Lifecycle

- **[Project Initiation](./octoacme-project-initiation.md)** — Validating ideas, confirming business needs, stakeholder alignment, and go/no-go decision gates
- **[Project Planning](./octoacme-project-planning.md)** — Breaking work into shippable increments, creating prioritized backlogs, estimating scope, and defining release plans
- **[Execution & Tracking](./octoacme-execution-and-tracking.md)** — Day-to-day delivery, quality standards, testing requirements, reporting metrics, and blocker escalation procedures
- **[Release & Deployment](./octoacme-release-and-deployment.md)** — Standardized release processes, deployment checklists, rollback procedures, and release notes templates
- **[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)** — Capturing learnings, running effective retrospectives, tracking action items, and building a continuous improvement culture

### Cross-Cutting Concerns

- **[Risk Management & Communication](./octoacme-risks-and-communication.md)** — Risk identification and lifecycle, maintaining risk registers, stakeholder communication templates, and escalation paths

---

## How to Use These Docs

Each document is self-contained and includes:
- **Purpose**: Why the document exists and when to use it
- **Checklists**: Step-by-step guidance to ensure completeness
- **Templates**: Ready-to-use formats for plans, status reports, and action items
- **Decision gates**: Clear criteria for moving between project phases
- **Examples**: Practical scenarios and sample interactions

### Getting Started

**For Project Managers**: Start with [Project Initiation](./octoacme-project-initiation.md), then move to [Project Planning](./octoacme-project-planning.md) and [Execution & Tracking](./octoacme-execution-and-tracking.md).

**For Product Managers**: Review [Project Management Overview](./octoacme-project-management-overview.md) and [Roles & Personas](./octoacme-roles-and-personas.md), then reference [Project Initiation](./octoacme-project-initiation.md) for defining success metrics.

**For Developers**: Familiarize yourself with [Roles & Personas](./octoacme-roles-and-personas.md) and [Execution & Tracking](./octoacme-execution-and-tracking.md) for quality and workflow standards.

**For New Team Members**: Start with [Project Management Overview](./octoacme-project-management-overview.md), then explore [Roles & Personas](./octoacme-roles-and-personas.md) to understand your team's structure and responsibilities.

### Using These Docs in Copilot Spaces

These documents are maintained as versioned artifacts in this repository and can be connected to Copilot Spaces to provide context-specific assistance. Reference these docs when:
- Setting up a new project or Copilot Space
- Onboarding team members to project processes
- Standardizing workflows across teams
- Establishing governance and quality gates

---

## Key Artifacts at a Glance

| Artifact | Purpose | Owner | Frequency |
|----------|---------|-------|-----------|
| Project One-pager | Define problem, goals, success metrics | PM/PdM | Per project |
| Risk Register | Track and monitor project risks | PM | Weekly updates |
| Project Backlog | Prioritized list of work items | PdM | Ongoing |
| Sprint/Iteration Plan | Team commitments for a timebox | PM/Team | Per sprint |
| Status Report | Weekly progress and blockers | PM | Weekly |
| Release Notes | Document changes and deployment info | PM/Dev | Per release |
| Retrospective Notes | Capture learnings and action items | PM/Team | Post-sprint/release |

---

## Questions or Feedback?

These documents evolve with our practices. If you have questions, find gaps, or want to suggest improvements:

1. Check the relevant document for answers
2. Raise an issue using the ["Add Content to Project Management Process Docs"](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template
3. Propose updates via pull request

We value your input in making these processes clear and effective for the entire team.
