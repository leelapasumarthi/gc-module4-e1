# Roles and Personas — OctoAcme

This document defines the roles and personas used across OctoAcme projects. It expands the existing role definitions to include Business Analyst, Quality Assurance Lead, Infrastructure/DevOps Engineer, and Customer Success Manager. Each persona includes responsibilities, required skills, key interactions, and their role in the project lifecycle.

## Purpose

Clarify responsibilities and interactions between project roles to improve accountability, reduce rework, and align with best practices.

---

## Business Analyst

Responsibilities:
- Gather, analyze, and document business requirements and user stories.
- Facilitate requirements workshops with stakeholders and product owners.
- Translate business needs into clear acceptance criteria.
- Maintain and refine the backlog in collaboration with the Product Owner.
- Support scope definition during project initiation and change requests.

Required skills:
- Business analysis and requirements elicitation techniques
- Strong communication and stakeholder facilitation
- Familiarity with user story and acceptance criteria writing
- Basic understanding of software development lifecycle (SDLC)

Key interactions:
- Reports to: Project Manager (matrix reporting may apply)
- Collaborates with: Product Owner, Development Team, QA Lead, Stakeholders
- Works closely with QA Lead to ensure acceptance criteria are testable

Role in project lifecycle:
- Initiation & Planning: Elicits requirements, defines scope and acceptance criteria
- Execution: Supports development and clarifies requirements
- Validation: Supports QA by validating acceptance criteria and participating in user acceptance testing (UAT)

---

## Quality Assurance Lead

Responsibilities:
- Define and own the testing strategy and quality standards for the project.
- Lead test planning, design, and execution (manual and automated as applicable).
- Track and report defects, quality metrics, and release readiness.
- Validate release readiness against agreed quality gates.
- Mentor and coordinate QA engineers/testers and manage test environments.

Required skills:
- Test strategy and test case design
- Familiarity with automation frameworks and test tooling (where applicable)
- Defect management and reporting
- Strong collaboration with development and infra teams

Key interactions:
- Reports to: Project Manager or Technical Lead
- Collaborates with: Development Team, Business Analyst, Infrastructure/DevOps
- Provides QA input to Product Owner and Project Manager on release decisions

Role in project lifecycle:
- Planning: Contributes to test strategy and environment needs
- Execution: Leads test execution and defect triage
- Release: Validates release readiness and coordinates regression/SMOKE testing

---

## Infrastructure / DevOps Engineer

Responsibilities:
- Plan and provision infrastructure required for development, test, staging, and production.
- Create and maintain CI/CD pipelines and automation scripts.
- Support deployment and release activities, including rollbacks and runbooks.
- Ensure monitoring, alerting, and system health checks are in place post-deployment.
- Collaborate on security, backup, and scalability concerns.

Required skills:
- Infrastructure as code (Terraform, CloudFormation, etc.)
- CI/CD tools (GitHub Actions, Jenkins, GitLab CI, etc.)
- Containerization and orchestration (Docker, Kubernetes)
- Monitoring and observability tooling

Key interactions:
- Reports to: Technical Lead or Project Manager
- Collaborates with: Development Team, QA Lead, Security team
- Supports Customer Success for production incidents and escalations

Role in project lifecycle:
- Planning: Defines environment and infrastructure requirements
- Execution: Builds and maintains environments and pipelines
- Release & Operations: Executes deployments, monitors production, supports incident response

---

## Customer Success Manager

Responsibilities:
- Ensure customers derive value from delivered features and releases.
- Serve as the primary post-release point of contact for customer feedback.
- Facilitate knowledge transfer, training, and adoption activities.
- Collect and surface customer feedback to Product and Project teams.
- Support retrospectives with customer-centric insights for continuous improvement.

Required skills:
- Strong customer-facing communication and relationship management
- Understanding of product usage, onboarding, and adoption metrics
- Ability to translate customer feedback into actionable product input

Key interactions:
- Primary point of contact for external stakeholders and customers
- Collaborates with: Project Manager, Product Owner, Support, and Engineering teams
- Feeds customer feedback into backlog/prioritization decisions

Role in project lifecycle:
- Pre-release: Coordinates customer communications about upcoming releases
- Post-release: Gathers feedback, runs training/onboarding, monitors customer satisfaction
- Continuous Improvement: Provides customer insights for product and process improvements

---

## Alignment with Existing Roles

These personas are intended to complement existing roles (Project Manager, Product Owner, Development Team, Technical Lead, Support). Use the templates in docs/templates/ to map responsibilities and ensure there are no conflicting ownership boundaries.

---

## Acceptance Criteria

- Content aligns with existing process docs and organizational terminology.
- Updates close identified documentation gaps regarding QA, Infra/DevOps, Business Analysis, and Customer Success.
- Document reviewed by stakeholders and added to docs/ as required per the issue.

