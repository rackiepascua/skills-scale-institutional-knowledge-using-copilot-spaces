# OctoAcme Project Management Documentation

Welcome to the OctoAcme project management process library. This repository folder contains our standard process documents and serves as the single source of truth for how we plan, execute, release, and learn from projects.

## Quick Navigation

- **[Project Management Overview](./octoacme-project-management-overview.md)** — High-level introduction to our approach, roles, and key artifacts
- **[Project Initiation](./octoacme-project-initiation.md)** — How to validate and authorize new work
- **[Project Planning](./octoacme-project-planning.md)** — Breaking work into actionable plans and backlogs
- **[Execution & Tracking](./octoacme-execution-and-tracking.md)** — Managing day-to-day delivery and progress
- **[Risk Management & Communication](./octoacme-risks-and-communication.md)** — Identifying and managing risks, stakeholder updates
- **[Release & Deployment](./octoacme-release-and-deployment.md)** — Standardizing releases to production
- **[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)** — Capturing learnings and iterating
- **[Roles and Personas](./octoacme-roles-and-personas.md)** — Typical roles and responsibilities in our projects

## Brief Overview of OctoAcme Project Management Processes

OctoAcme follows an iterative, outcome-driven lifecycle that begins with a lightweight initiation and moves through planning, execution, release, and retrospective phases. Initiation captures the business problem, stakeholders, and success metrics in a concise Project One-pager and uses a decision gate to confirm readiness for planning. During planning, teams break work into shippable increments, define acceptance criteria and a Definition of Done, estimate effort, and map dependencies and milestones.

Execution emphasizes clear workflows and fast feedback: teams use a project board with well-defined columns (Backlog, Ready, In Progress, In Review, QA, Done) and follow a pull request process that favors small changes, linked issues, CI checks, and required approvals. Regular team rhythms — daily standups for blockers, weekly delivery syncs for status and risks, and demos at the end of sprints or milestones — keep work aligned and visible. A lightweight risk register and escalation paths ensure issues are surfaced and resolved promptly.

Quality and release practices are integrated into the delivery pipeline. Developers add unit and integration tests, teams run end-to-end smoke tests for critical flows, and CI enforces tests, linting, and security scans before merges. Releases require a pre-release checklist, rollback plans, and post-deploy verifications; incident playbooks guide rapid triage and recovery when needed. Continuous improvement is supported through timeboxed retrospectives that produce prioritized action items tracked back into the backlog and reviewed in weekly PM syncs.

## Getting Started

New team members should start with the [Project Management Overview](./octoacme-project-management-overview.md) to understand principles and core roles. Then follow the phase documents in order as a project progresses: Initiation → Planning → Execution → Release → Retrospective. Use the checklists in each document to confirm completeness and add suggested improvements through the process doc update workflow.

## Maintaining These Docs

- Keep each phase document focused and example-driven.
- Add new or updated content via the `.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml` workflow (create an issue titled "[Process Doc Update]: ...").
- Review and update the README when new process docs are added or when major changes to workflows occur.

---

(Automatically generated from: docs/ directory process documents)
