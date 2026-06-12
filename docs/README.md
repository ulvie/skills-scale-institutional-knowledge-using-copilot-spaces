# OctoAcme Project Management Docs

Welcome to OctoAcme's centralized project management process documentation. This README provides a concise overview of our project management approach and serves as an entry point to all process guides.

## OctoAcme Project Management — Overview

OctoAcme follows an **iterative, outcomes-driven project management approach** grounded in customer value delivery and clear ownership. Our methodology spans five core lifecycle phases:

### Initiation
Teams validate business needs, align stakeholders, and produce a lightweight **Project One-pager** that articulates the problem statement, measurable success metrics, and required resources. A decision gate ensures only well-scoped work moves forward.

### Planning
Work is broken into **shippable increments** with defined acceptance criteria. Dependencies are mapped, timelines are established, and the entire team—including Product Managers, Project Managers, Developers, and QA—shares a common understanding of scope and success before execution begins.

### Execution & Tracking
Delivery operates on a disciplined **team rhythm**: daily standups (15 min) surface progress and blockers, weekly delivery syncs review advancement against milestones, and work is tracked on GitHub Projects boards. Pull requests stay small (≤400 lines when possible), require automated CI checks and peer review before merging, and are linked to issues with clear acceptance criteria. **Quality is embedded**: unit tests, integration tests, end-to-end smoke tests, and security scanning occur throughout.

### Risk Management & Communication
A **Risk Register** tracks identified issues by ID, Impact, Likelihood, Owner, Mitigation, and Status, reviewed consistently during weekly syncs. Defined escalation paths (Team → PM → Product Lead → Sponsor) clarify decision authority. Weekly PM-PdM syncs, twice-weekly team standups, and monthly stakeholder updates create multiple feedback loops for alignment.

### Release & Retrospective
Pre-release checklists verify acceptance criteria are met, CI/security scans pass, smoke tests are prepared, and rollback plans are documented. After each sprint, release, or milestone, structured retrospectives capture learnings and assign 2–3 prioritized action items with clear owners and due dates, reinforcing a culture of continuous improvement.

---

## Key Roles & Personas

- **Project Manager (PM):** Coordinates delivery, manages schedules, risks, and communications.
- **Product Manager (PdM):** Defines outcomes, prioritizes the backlog, and measures success.
- **Developers:** Implement features, collaborate on design and testability.
- **QA/Testing:** Validate quality and acceptance criteria.
- **Stakeholders:** Provide inputs and approvals.

---

## Core Principles

- **Customer-first:** Prioritize customer value and usability.
- **Iterative delivery:** Deliver small, testable increments.
- **Clear ownership:** Each project has a named PM and Product Lead.
- **Data-informed decisions:** Measure impact and iterate based on evidence.
- **Psychological safety:** Encourage feedback and learning.

---

## Links to Process Docs

| Document | Purpose |
|----------|---------|
| [Project Management Overview](octoacme-project-management-overview.md) | Introduction to OctoAcme's approach, roles, and key artifacts. |
| [Project Initiation Guide](octoacme-project-initiation.md) | Define initial steps to validate work, align stakeholders, and create a lightweight plan. |
| [Project Planning](octoacme-project-planning.md) | Turn an approved initiative into an actionable plan and backlog for delivery. |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Guidance for managing day-to-day execution and tracking progress toward milestones. |
| [Risk Management & Communication](octoacme-risks-and-communication.md) | Identify, manage, and communicate risks and dependencies. |
| [Release & Deployment Guide](octoacme-release-and-deployment.md) | Standardize how OctoAcme releases features to production to reduce risk. |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Capture learnings and convert them into actionable improvements. |
| [Roles & Personas](octoacme-roles-and-personas.md) | Define typical roles and responsibilities used in OctoAcme projects. |

---

## How to Use These Docs

- **For new team members:** Start with this README, then explore the [Project Management Overview](octoacme-project-management-overview.md) and [Roles & Personas](octoacme-roles-and-personas.md).
- **For project teams:** Keep the project one-pager and README updated in your project repo. Follow the relevant process doc guides for each lifecycle phase.
- **For Copilot Spaces:** Add process-specific docs into `.copilot/` to ground Copilot Spaces in your team's processes and get context-specific guidance.
- **For continuous improvement:** Reference the [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) guide after each milestone or release to capture learnings and action items.

---

## Contributing

Have feedback or ideas to improve these process docs? Create an issue using the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template.
