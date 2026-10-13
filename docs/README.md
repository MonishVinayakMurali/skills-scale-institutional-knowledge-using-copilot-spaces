# OctoAcme Project Management Docs

This folder collects OctoAcme's program and project management process documents. Use this README as a single discovery point that links to each process doc, provides a short summary, and explains how to propose updates.

Quick links

- [Project management overview](docs/octoacme-project-management-overview.md)
- [Project initiation](docs/octoacme-project-initiation.md)
- [Project planning](docs/octoacme-project-planning.md)
- [Execution and tracking](docs/octoacme-execution-and-tracking.md)
- [Risks and communication](docs/octoacme-risks-and-communication.md)
- [Release and deployment](docs/octoacme-release-and-deployment.md)
- [Retrospective and continuous improvement](docs/octoacme-retrospective-and-continuous-improvement.md)
- [Roles and personas](docs/octoacme-roles-and-personas.md)

Overview of OctoAcme project management processes

- Initiation: Validate the business need, capture a concise one-pager (problem, goal, success metrics), identify stakeholders, and decide whether to proceed to planning.
- Planning: Turn an approved initiative into an actionable plan and prioritized backlog. Define milestones, estimates, acceptance criteria, risks, and the release plan.
- Execution & tracking: Coordinate day-to-day delivery through a clear team rhythm (standups, delivery syncs, demos), use the project board to manage flow, enforce PR quality gates and CI, and regularly report progress.
- Risks & communication: Maintain a simple risk register (ID, impact, likelihood, owner, mitigation), communicate via weekly status updates, and follow escalation paths for blockers and incidents.
- Release & deployment: Follow pre-release checks (CI, security scans, release notes, rollback plans), run staging and smoke tests, and perform post-deploy verifications.
- Retrospective & continuous improvement: Run timeboxed retrospectives, capture action items into the backlog, and measure the impact of process improvements.
- Roles & personas: Clarify responsibilities for PM, PdM, developers, QA, and other stakeholders so ownership and expectations are explicit.

One-line summaries for each doc

- Project management overview — A concise introduction to how OctoAcme runs projects, core principles, roles, and key artifacts.
- Project initiation — Steps and minimum deliverables to validate and authorize work (one-pager, stakeholder alignment, decision gate).
- Project planning — How to break approved initiatives into a plan, estimate work, define DoD, and identify dependencies and risks.
- Execution & tracking — Day-to-day execution guidance: team rhythm, PR workflow, testing, reporting, and blocker escalation.
- Risks & communication — Guidance on maintaining the risk register, stakeholder comms, incident messages, and escalation paths.
- Release & deployment — Release types, pre-release requirements, deployment checklist, and rollback/playbook.
- Retrospective & continuous improvement — How to run retrospectives, prioritize action items, and track improvements.
- Roles & personas — Role summaries and responsibilities used across OctoAcme process docs.

How to propose edits

To propose additions or updates to these process docs, please use the template: `.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml`. Create an issue describing which doc to update, a summary of the change, the rationale, and proposed content. Link the issue from your PR so reviewers can trace the change request.

Contributor guidance

- Keep each process doc focused and actionable.
- Link PRs to the related issue when changing process docs.
- Keep changes small and reviewable — split large updates into multiple PRs if needed.

