# OctoAcme Project Management Process Documentation

Welcome to the OctoAcme project management documentation library. This folder contains comprehensive guides for running projects at OctoAcme, from initiation through retrospective and continuous improvement.

## Overview

OctoAcme follows a structured, customer-first approach to project delivery with clear ownership, iterative delivery, data-informed decisions, and a culture of psychological safety. This documentation captures our processes, roles, and best practices to help teams execute consistently and scale institutional knowledge across the organization.

### Key Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named Project Manager (PM) and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Project Management Lifecycle

OctoAcme projects follow a five-phase lifecycle: **Initiation → Planning → Execution → Release → Retrospective**. Each phase has defined activities, deliverables, and decision gates to ensure alignment and quality.

### Phase Overview

OctoAcme follows a structured, lifecycle-based approach to project management that emphasizes customer value, iterative delivery, and clear ownership. During **Initiation**, teams validate business needs by creating a lightweight One-pager that defines the problem, goals, success metrics, and stakeholders, then secure sponsor alignment before proceeding. **Planning** transforms approved initiatives into actionable backlogs by breaking work into shippable increments, estimating scope, defining acceptance criteria, and mapping dependencies.

**Execution** is governed by a structured team rhythm and a project board workflow with columns for Backlog, Ready, In Progress, In Review, QA, and Done. Teams conduct daily standups (15 minutes) to flag progress and blockers, hold weekly delivery syncs to review status and risks, and maintain small pull requests (≤400 lines) with clear issue links and acceptance criteria. Quality is embedded throughout via unit tests, integration tests, end-to-end smoke tests, security scanning in CI, and manual QA for feature acceptance.

The organization defines three core roles—**Product Manager** (defines outcomes and prioritizes), **Project Manager** (coordinates delivery and manages risks), and **Developers** (implement and collaborate on design)—with clear separation of concerns and a weekly PM-PdM sync to maintain alignment. **Release** is standardized with pre-release checklists and post-release verification protocols. Finally, **Retrospectives** held after each sprint or milestone capture learnings and convert them into prioritized action items, embedding continuous improvement into the project lifecycle.

## Core Processes & Lifecycle

| Process | Document | Purpose |
|---------|----------|----------|
| **Project Initiation** | [octoacme-project-initiation.md](octoacme-project-initiation.md) | Validate business need, align stakeholders, and make go/no-go decision |
| **Project Planning** | [octoacme-project-planning.md](octoacme-project-planning.md) | Break work into shippable increments and create an actionable plan |
| **Execution & Tracking** | [octoacme-execution-and-tracking.md](octoacme-execution-and-tracking.md) | Manage day-to-day execution, track progress toward milestones |
| **Risk Management & Communication** | [octoacme-risks-and-communication.md](octoacme-risks-and-communication.md) | Identify, assess, monitor risks and keep stakeholders informed |
| **Release & Deployment** | [octoacme-release-and-deployment.md](octoacme-release-and-deployment.md) | Standardize release procedures and reduce deployment risk |
| **Retrospective & Improvement** | [octoacme-retrospective-and-continuous-improvement.md](octoacme-retrospective-and-continuous-improvement.md) | Capture learnings and drive continuous improvements |

## Reference Materials

- **[Project Management Overview](octoacme-project-management-overview.md)** — High-level introduction to roles, principles, and communication cadence
- **[Roles & Personas](octoacme-roles-and-personas.md)** — Definitions of core roles: Developer, Product Manager, Project Manager, and Stakeholders

## For New Team Members

Welcome to the team! Here's how to get oriented:

1. **Start with the Overview**: Read this README to understand OctoAcme's project management approach and principles.
2. **Learn the Roles**: Check out [Roles & Personas](octoacme-roles-and-personas.md) to understand the core roles and responsibilities.
3. **Understand the Big Picture**: Review the [Project Management Overview](octoacme-project-management-overview.md) for context on communication cadence and key artifacts.
4. **Reference Specific Processes**: As you work on projects, reference the specific process document that matches your current phase (initiation, planning, execution, release, or retrospective).

## Common Scenarios

| Scenario | Next Steps |
|----------|----------|
| Starting a new project | Read [Project Initiation Guide](octoacme-project-initiation.md) and complete the initiation checklist |
| Planning a project after approval | Read [Project Planning](octoacme-project-planning.md) and create your backlog and release plan |
| Tracking daily work and progress | Reference [Execution & Tracking](octoacme-execution-and-tracking.md) for team rhythm and workflows |
| Managing risks or blockers | Check [Risk Management & Communication](octoacme-risks-and-communication.md) for escalation paths and templates |
| Preparing for release | Use the [Release & Deployment Guide](octoacme-release-and-deployment.md) checklist and release notes template |
| After a sprint or milestone | Run a retrospective using [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) |

## Contributing to Process Documentation

OctoAcme process documentation is living documentation that evolves with our organization. We welcome feedback and contributions to keep these guides relevant and useful.

### To Update or Add Content

1. Open an issue using the **"Add Content to Project Management Process Docs"** template (stored in `.github/ISSUE_TEMPLATE/`)
2. Include:
   - Which process document you want to update (or if creating a new one)
   - Summary of the new content or update
   - Rationale for the change
   - Suggested content (optional)
3. A team member will review your contribution and merge it if it aligns with our processes and improves clarity

### Acceptance Criteria

Content should meet these standards:
- Aligns with existing process docs and OctoAcme principles
- Improves clarity or closes a documented gap
- Has been reviewed with relevant stakeholders (if needed)

## Questions or Feedback?

If you have questions about these processes or suggestions for improvements, please open an issue or reach out to your Project Manager or Product Lead.

---

**Last updated**: August 2026
**Maintained by**: OctoAcme Project Management Community