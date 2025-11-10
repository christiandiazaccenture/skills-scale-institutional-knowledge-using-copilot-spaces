```markdown
# OctoAcme Project Management Docs — README

Welcome to the OctoAcme Project Management documentation. This README provides a concise orientation to how OctoAcme runs projects—principles, lifecycle, roles, communication cadence—and links to the detailed process documents in this folder to help onboard teammates and provide a single-entry point for delivery practices.

OctoAcme follows a lightweight, iterative lifecycle: Initiation → Planning → Execution → Release → Close & Retrospective. Initiation validates the problem, stakeholders, and success metrics with a one‑pager; planning turns approved initiatives into a prioritized backlog with estimates, a Definition of Done (DoD), and a release plan; execution uses small, testable increments tracked via a project board and a disciplined PR workflow; releases require pre‑release smoke tests and rollback plans; retrospectives capture learnings and convert them into tracked action items.

Day‑to‑day workflows emphasize the project board (Backlog, Ready, In Progress, In Review, QA, Done), small PRs with linked issues and clear acceptance criteria, and CI-driven quality gates (automated unit/integration tests, security scans, and smoke tests). Quality assurance combines automated testing, CI security scanning, targeted manual QA when required, and post‑deploy verification. The project enforces clear escalation paths and an execution checklist so deployments and incidents are handled predictably.

Roles and communication are explicitly defined to keep ownership and alignment clear. Core personas include Project Manager (delivery coordination, risk & status), Product Manager (outcomes and prioritization), Developers (implementation & tests), and QA (validation & acceptance). The communication cadence includes daily standups, weekly PM+PdM syncs, demo/review at sprint or milestone close, and monthly stakeholder updates; standardized weekly status and incident templates and a three‑level escalation path (team → PM → Product Lead → Sponsor) support predictable reporting and rapid issue handling.

## Process Documents
- [Project Management Overview](docs/octoacme-project-management-overview.md)
- [Project Initiation Guide](docs/octoacme-project-initiation.md)
- [Project Planning](docs/octoacme-project-planning.md)
- [Execution & Tracking](docs/octoacme-execution-and-tracking.md)
- [Risk Management & Communication](docs/octoacme-risks-and-communication.md)
- [Release & Deployment Guide](docs/octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](docs/octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](docs/octoacme-roles-and-personas.md)

## How to use this README
- Start with the Overview, then read Initiation and Planning when beginning a new project.
- Keep the Project One‑pager and release notes updated in the project repo as the single source of truth.
- Add project-specific process files into `.copilot/` if you want Copilot Spaces to index them as context.

## Acceptance Criteria
- Content aligns with existing documents in docs/
- README centralizes access for onboarding and reference
- README links to all process documents in this folder
```