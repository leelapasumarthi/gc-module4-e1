# OctoAcme Project Management Process Documentation

Welcome! This folder contains comprehensive guides for running projects at OctoAcme. Whether you're initiating a new project, planning a release, or running a retrospective, these docs will guide you through each stage of our process.

## Quick Start by Project Stage

- **Just starting a project?** → [Project Initiation Guide](./octoacme-project-initiation.md)
- **Moving into execution?** → [Execution & Tracking](./octoacme-execution-and-tracking.md)
- **Getting ready to release?** → [Release & Deployment Guide](./octoacme-release-and-deployment.md)
- **Learning from what happened?** → [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)

## All Process Documents

| Document | Purpose |
|----------|---------|
| [OctoAcme Project Management Overview](./octoacme-project-management-overview.md) | High-level introduction to OctoAcme's approach, core roles, and key artifacts |
| [Project Initiation Guide](./octoacme-project-initiation.md) | Initial steps to validate, authorize, and align on new work |
| [Project Planning](./octoacme-project-planning.md) | Break work into shippable increments and create an actionable plan |
| [Execution & Tracking](./octoacme-execution-and-tracking.md) | Day-to-day delivery management, team rhythms, and quality standards |
| [Risk Management & Communication](./octoacme-risks-and-communication.md) | Identify, manage, and communicate risks and dependencies |
| [Release & Deployment Guide](./octoacme-release-and-deployment.md) | Standardized release and deployment processes to reduce risk |
| [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) | Capture learnings and convert them to actionable improvements |
| [Roles & Personas](./octoacme-roles-and-personas.md) | Definitions of core roles and their responsibilities |

## OctoAcme Project Lifecycle

**1. Initiation** - Define the business need, identify stakeholders, confirm success metrics

**2. Planning** - Create a detailed plan, prioritized backlog, and release timeline

**3. Execution** - Build, test, review, and iterate with regular team rhythms and quality gates

**4. Release** - Deploy to production with rigorous pre-release checks and rollback plans

**5. Retrospective** - Capture learnings and drive continuous improvements

## Core Principles

- 🎯 **Customer-first**: Prioritize customer value and usability
- 📈 **Iterative delivery**: Deliver small, testable increments
- 👥 **Clear ownership**: Each project has a named PM and Product Lead
- 📊 **Data-informed**: Measure impact and iterate based on evidence
- 🤝 **Psychological safety**: Encourage feedback and learning

## OctoAcme Project Management Processes Overview

### The Framework

OctoAcme operates on a structured yet iterative project lifecycle designed to balance customer value delivery with team collaboration and risk management. The approach spans five key phases (Initiation, Planning, Execution, Release, and Retrospective) and applies consistently across all cross-functional projects that deliver product features, services, or integrations. Throughout each phase, lightweight but disciplined governance ensures alignment without excessive overhead.

### Key Roles and Responsibilities

OctoAcme defines three primary personas that drive project success:

- **Product Managers** own the product vision, prioritize the backlog, and measure outcomes through customer research and metrics
- **Project Managers** coordinate delivery activities, manage schedules, risks, and stakeholder communications to ensure timely, on-scope delivery
- **Developers** design, build, test, and deliver software while collaborating on acceptance criteria, participating in reviews, and identifying technical risks

Communication flows through weekly PM-PdM syncs, twice-weekly standups for delivery teams, and monthly stakeholder updates, with ad-hoc escalations for high-impact issues. This clear delineation of ownership prevents bottlenecks and ensures accountability across all project phases.

### Execution, Quality, and Risk Management

During execution, OctoAcme uses GitHub Projects with defined workflow columns (Backlog, Ready, In Progress, In Review, QA, Done) to maintain visibility and flow. Small Pull Requests (≤400 lines) with linked issues and acceptance criteria feed into automated CI pipelines that enforce testing, linting, and security scanning before review. 

Quality assurance combines:
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows
- Security scanning in CI
- Manual QA for feature acceptance

Risk management operates through a structured Risk Register that captures ID, description, impact, likelihood, mitigation, and status—reviewed and updated weekly during team syncs. Blocker escalation follows a three-level model: Level 1 team-level triage in standups, Level 2 PM escalation to Product Lead and dependent teams, and Level 3 sponsor-level escalation for business-impacting issues.

### Release and Continuous Improvement

OctoAcme releases follow a standardized checklist that includes passing CI/security scans, drafted release notes, documented rollback plans, and pre-release smoke tests across patch, minor, and major release types. Deployment moves through staging verification before production promotion using automated pipelines when possible, with post-deploy verifications and stakeholder announcements.

Every sprint, release, or milestone concludes with a 45–75 minute retrospective structured around what went well, what could improve, and 2–3 prioritized action items with clear owners and due dates. This continuous improvement cycle converts learnings into tracked backlog items, ensuring the team compounds progress while maintaining visibility into process refinements across the entire project lifecycle.

## Getting Help

- **Questions about a specific phase?** Refer to the relevant process document above
- **Need to understand a role?** Check [Roles & Personas](./octoacme-roles-and-personas.md)
- **Want to improve these docs?** Create an issue using the [Process Doc Update template](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)
