# OctoAcme Project Management Docs

This README provides an overview of project management processes at OctoAcme and links to all core process documentation. It serves as a centralized entry point for new team members and stakeholders to understand our project lifecycle, navigate to detailed process documents, and orient themselves with our delivery workflows.

## Overview

OctoAcme's project management approach emphasizes customer-first delivery, iterative development, and clear ownership across cross-functional teams. Every project follows a structured lifecycle—from Initiation through Planning, Execution, Release, and Retrospective—with defined artifacts, communication cadences, and decision gates at each stage. Our processes are designed to maximize transparency, reduce risk, and ensure measurable outcomes while maintaining psychological safety and continuous improvement.

## Key Roles & Workflows

Projects at OctoAcme are led collaboratively by a **Project Manager (PM)** who coordinates delivery, schedules, and risk management, and a **Product Manager (PdM)** who defines outcomes, prioritizes the backlog, and measures success. **Developers** implement features following clear acceptance criteria and maintain high test coverage, while **QA/Testing** teams validate quality standards. **Stakeholders** provide strategic input and approvals throughout the lifecycle.

The delivery workflow centers on GitHub Projects boards with columns for Backlog, Ready, In Progress, In Review, QA, and Done. Teams operate in sprints or iterations, holding daily standups, weekly delivery syncs, and end-of-sprint demos. Pull requests are kept small (≤400 lines when possible), include issue links and acceptance criteria, and require automated test and lint passes in CI before review and approval.

## Communication & Risk Management

Communication follows a predictable cadence: weekly syncs between PM and PdM, twice-weekly standups for delivery teams, and monthly stakeholder updates. All projects maintain a **Risk Register** tracking identified risks with impact, likelihood, ownership, and mitigation plans. Risks are reviewed at weekly syncs and escalated through defined paths—from team-level triage to PM, Product Lead, and Sponsor as needed. Stakeholders receive regular status updates using standardized templates covering progress, next steps, risks/blockers, and decisions needed.

## Quality & Continuous Improvement

Quality is built in through unit tests, integration tests, and end-to-end smoke tests for critical flows, with security scanning integrated into CI pipelines. Manual QA validates feature acceptance when needed. Releases follow a structured checklist ensuring all acceptance criteria are met, CI passes, release notes are drafted, and rollback plans are documented before deployment.

After each sprint, release, or milestone, teams hold **Retrospectives** to capture what went well, identify improvements, and create 2–3 prioritized action items with clear owners and timelines. These improvements are tracked in the project backlog and reviewed in weekly PM syncs, fostering a culture of measurable, iterative enhancement.

## Process Documents

The following documents provide detailed guidance for each stage of the project lifecycle:

- [Project Management Overview](octoacme-project-management-overview.md) — Core principles, roles, artifacts, and lifecycle summary
- [Project Initiation Guide](octoacme-project-initiation.md) — How to validate and authorize new work, create a one-pager, and align stakeholders
- [Project Planning](octoacme-project-planning.md) — Breaking work into shippable increments, estimating, and defining release plans
- [Execution & Tracking](octoacme-execution-and-tracking.md) — Day-to-day workflows, PR conventions, testing, and blocker escalation
- [Risk Management & Communication](octoacme-risks-and-communication.md) — Risk register, stakeholder communication templates, and escalation paths
- [Release & Deployment Guide](octoacme-release-and-deployment.md) — Pre-release requirements, deployment checklists, and rollback procedures
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — Running retrospectives and tracking improvement action items
- [Roles & Personas](octoacme-roles-and-personas.md) — Detailed role definitions and responsibilities for Developers, Product Managers, and Project Managers

## Audience & Usage Guidance

This README is intended for:
- **New team members** onboarding to OctoAcme projects
- **Project Managers and Product Managers** seeking process reference materials
- **Developers and QA** understanding delivery workflows and quality standards
- **Stakeholders** orienting themselves with project lifecycle and communication norms

Use this document as your first stop to understand the project management lifecycle at a high level, then navigate to the linked process documents for detailed guidance on specific workflows, templates, and checklists. Keep the Project Charter and key artifacts updated in your project repository, and add process-specific documents to `.copilot/` if you want GitHub Copilot Spaces to use them as context.
