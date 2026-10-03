# OctoAcme Project Management Docs

Welcome to the OctoAcme Project Management Documentation Suite. This is your central hub for understanding how OctoAcme runs projects, manages resources, communicates with stakeholders, and delivers value consistently.

## Overview

The OctoAcme project management suite provides standardized guidance for running cross-functional projects. Our approach emphasizes customer value, iterative delivery, clear ownership, and data-informed decisions.

### Core Principles

- **Customer-first**: Prioritize customer value and usability.
- **Iterative delivery**: Deliver small, testable increments.
- **Clear ownership**: Each project has a named Project Manager (PM) and Product Lead.
- **Data-informed decisions**: Measure impact and iterate based on evidence.
- **Psychological safety**: Encourage feedback and learning.

## How OctoAcme Runs Projects: A Quick Summary

OctoAcme's project management process is structured around a clear lifecycle: initiation, planning, execution, release, and retrospective. The team begins by validating the business need, identifying stakeholders, and creating a lightweight project one-pager with goals, success metrics, timeline, risks, and resource needs. Once the initiative is approved, the team moves into planning, where the backlog is prioritized, dependencies and risks are captured, and a release plan with milestones is defined. Throughout execution, work is tracked via project boards, sprint planning, and a documented Definition of Done, with emphasis on small, testable increments and regular stakeholder visibility.

The operating model is built around core roles and shared accountability. Product and project leaders define outcomes and manage scope, while developers, QA, and cross-functional stakeholders contribute to implementation, validation, and decision-making. Clear ownership, with a named Project Manager and Product Lead for each effort, keeps work aligned to customer value while making responsibilities visible and predictable.

Communication is a central part of the process. OctoAcme uses recurring rituals such as daily standups, weekly delivery or PM syncs, demos, and milestone-based stakeholder updates to surface progress, risks, and decisions. Escalation paths are defined so that issues move from the team to the PM, then to the Product Lead or sponsor depending on impact. Risk and communication management includes status templates, stakeholder segmentation, and a single source of truth for project updates.

Quality assurance is embedded into the workflow rather than treated as a final step. Development practices require clear acceptance criteria, PR review standards, CI checks, and testing at multiple levels including unit, integration, and smoke testing for critical flows. Security scanning, manual QA, and release readiness checks are part of the standard before deployment. Retrospectives are used to capture lessons learned, assign action items, and improve the process over time, creating a practical, repeatable project rhythm that balances speed, accountability, and risk management.

## Quick Navigation

### Core Guides

- **[Project Management Overview](./octoacme-project-management-overview.md)** — Start here for principles, roles, artifact descriptions, and the project lifecycle
- **[Roles & Personas](./octoacme-roles-and-personas.md)** — Understand the responsibilities and goals of Developers, Product Managers, and Project Managers

### Project Lifecycle

1. **[Project Initiation](./octoacme-project-initiation.md)** — Validate ideas, align stakeholders, and create a project one-pager
2. **[Project Planning](./octoacme-project-planning.md)** — Break work into actionable increments, estimate scope, and identify dependencies
3. **[Execution & Tracking](./octoacme-execution-and-tracking.md)** — Manage day-to-day delivery, track progress, and run effective standups
4. **[Risk Management & Communication](./octoacme-risks-and-communication.md)** — Identify and escalate risks, maintain stakeholder communication
5. **[Release & Deployment](./octoacme-release-and-deployment.md)** — Ship to production safely with pre-release checks and rollback plans
6. **[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings and iterate on the process

## How to Use This Documentation

### For New Team Members
Start with the **Project Management Overview** and **Roles & Personas** docs to understand the framework and your team's responsibilities. Then explore the lifecycle guides as you join projects.

### For Project Leads
Use the **Project Initiation** and **Project Planning** guides when kicking off a new effort. Reference **Execution & Tracking** and **Risk Management & Communication** during delivery. Use **Release & Deployment** as you approach the end of a phase. Run a **Retrospective** after each milestone or release.

### For Copilot Spaces
Add process-specific docs to `.copilot/` to enable Copilot Spaces to reference them as context when providing project management guidance. This allows Copilot to deliver personalized advice based on OctoAcme's practices.

## Key Artifacts

Across the project lifecycle, you'll create and maintain:

- **Project Charter / One-pager** — Problem, goal, success metrics, stakeholders, timeline, risks
- **Backlog** — Prioritized list of work with acceptance criteria and estimates
- **Project Board** — Visual tracking of work in progress (Backlog → Ready → In Progress → In Review → QA → Done)
- **Risk Register** — Identified risks, impact, likelihood, owner, and mitigation plans
- **Release Notes** — Summary of changes, migration steps, known issues
- **Retrospective Notes** — What went well, what to improve, action items with owners and due dates

## Communication Cadence

- **Daily standups** (15 min) — Progress, blockers, dependencies
- **Weekly PM sync** — PM + PdM alignment on priorities and risks
- **Twice-weekly delivery sync** — Team standup and progress review
- **Monthly stakeholder updates** — High-level status and key decisions
- **Ad-hoc escalations** — Issues that need immediate attention

## Getting Started

1. **Read the Overview** to understand OctoAcme's principles and roles
2. **Follow the Lifecycle** guides when starting a new project
3. **Reference Specific Docs** as needed during execution
4. **Update the Risk Register** weekly during delivery
5. **Run a Retrospective** after milestones to capture learnings

## Questions?

If you have questions about OctoAcme's project management process, check the relevant guide or reach out to your Project Manager or Product Lead. These docs are living artifacts — if you spot gaps or improvements, please contribute via the [Add Content to Process Docs issue template](.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml).
