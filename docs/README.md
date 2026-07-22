# OctoAcme Project Management Documentation

## Overview

OctoAcme uses an iterative, customer-focused project management approach that emphasizes clear ownership, data-driven decisions, and continuous improvement. Our process guides projects from initiation through retrospective in a structured yet flexible way.

## Key Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has named PM and Product Lead roles
- **Data-informed**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Project Lifecycle

1. **Initiation** - Validate problem and stakeholder alignment
2. **Planning** - Break work into shippable increments
3. **Execution** - Build, test, review, and iterate
4. **Release** - Deploy and verify in production
5. **Retrospective** - Capture learnings and improve

## Project Management Process Overview

OctoAcme follows a structured, lifecycle-based approach to project management. Each project is backed by a Project Manager (PM) and Product Manager (PdM) who work closely with development teams. Projects begin with the **Initiation phase**, where business need is validated through a lightweight Project One-pager, stakeholder alignment is established, and a go/no-go decision is made.

Once approved, teams move into **Planning**, where work is broken into shippable increments with prioritized backlogs, acceptance criteria, and a Definition of Done. This structured approach ensures that projects launch with clarity on success metrics, timelines, and resource needs before development begins.

**Execution and tracking** are managed through a disciplined team rhythm that includes daily standups (15 minutes), weekly delivery syncs, and sprint-based work cycles. Teams use GitHub Projects for workflow management with columns spanning Backlog, Ready, In Progress, In Review, QA, and Done. Quality is embedded throughout execution via unit and integration tests, end-to-end smoke tests, and manual QA for feature acceptance. A tiered escalation process ensures blockers are addressed quickly without creating bottlenecks.

**Risk management and communication** are woven into the weekly cadence, with a Risk Register maintained to track identified issues by impact, likelihood, and mitigation status. Once work is complete, teams move through a formal **Release phase** with pre-release requirements including passing CI/security scans, drafted release notes, and a documented rollback plan, followed by a structured **Retrospective** where learnings are captured and converted into actionable improvements tracked back into the project backlog.

## Documentation

Navigate to specific guides based on your current project phase or information needs:

- [**Project Management Overview**](octoacme-project-management-overview.md) - High-level intro to OctoAcme's approach, core roles, key artifacts, and communication cadence
- [**Project Initiation**](octoacme-project-initiation.md) - Validate business need, align stakeholders, and authorize work
- [**Project Planning**](octoacme-project-planning.md) - Create actionable plans, prioritized backlogs, and dependency maps
- [**Execution & Tracking**](octoacme-execution-and-tracking.md) - Day-to-day management, quality assurance, and blocker escalation
- [**Risk Management & Communication**](octoacme-risks-and-communication.md) - Identify, track, and communicate risks and dependencies
- [**Release & Deployment**](octoacme-release-and-deployment.md) - Standardize production releases with safety checks and rollback plans
- [**Retrospective & Continuous Improvement**](octoacme-retrospective-and-continuous-improvement.md) - Capture learnings and drive iterative process improvements
- [**Roles & Personas**](octoacme-roles-and-personas.md) - Understand typical project roles, responsibilities, and communication patterns

## Getting Started

**New to OctoAcme?** Start with the [Project Management Overview](octoacme-project-management-overview.md) for a 5-minute introduction to our approach, roles, and key artifacts.

**Starting a new project?** Follow this path:
1. Read [Project Initiation](octoacme-project-initiation.md) to validate your idea
2. Move to [Project Planning](octoacme-project-planning.md) once approved
3. Refer to [Execution & Tracking](octoacme-execution-and-tracking.md) during delivery
4. Follow [Release & Deployment](octoacme-release-and-deployment.md) when ready to ship
5. Complete [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) to capture learnings

**Need clarity on roles?** See [Roles & Personas](octoacme-roles-and-personas.md) to understand typical responsibilities and how teams collaborate.

**Managing risks or communicating status?** Refer to [Risk Management & Communication](octoacme-risks-and-communication.md) for templates and escalation paths.

## Questions or Feedback?

Found a gap in the documentation? Have a process improvement idea? Create an issue using the [Add Content to Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template to propose updates.