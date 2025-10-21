```markdown
# OctoAcme Project Management Docs

Welcome to the OctoAcme Project Management documentation. This README is a landing page for our process documents and provides a concise overview of how OctoAcme plans, executes, and improves projects.

OctoAcme runs projects through a lightweight, iterative lifecycle: Initiation → Planning → Execution & Tracking → Release & Deployment → Retrospective & Continuous Improvement. Initiation centers on a Project One-pager to validate the problem, define success metrics, and identify stakeholders. Approved initiatives move into planning where work is broken into prioritized, shippable backlog items with clear acceptance criteria, estimates, and a release plan. Execution emphasizes short feedback loops, visible progress tracking, and escalation for blockers. Releases follow a pre-release checklist (CI, security scans, smoke tests, rollback plans) and are followed by post-deploy verification and a retrospective to capture improvements.

Day-to-day workflows center on a project board (Backlog → Ready → In Progress → In Review → QA → Done), a pull-request-driven delivery model with automated CI checks, and a team rhythm of brief daily standups, weekly delivery syncs, and periodic demos. Pull requests should be small and include issue links and acceptance criteria; automated tests and at least one reviewer approval are required before merging. Metrics such as velocity and success metrics defined in the Project One-pager are tracked to inform decisions.

Roles are intentionally separated: Product Managers define outcomes and priorities; Project Managers coordinate delivery, risks, and stakeholder communication; Developers build and test; QA validates acceptance; Stakeholders give input and approvals. Communication is regular and templated — weekly status templates, monthly stakeholder summaries, and incident triage messages — and risks are tracked in a Risk Register with clear owners and escalation paths. Quality is enforced via unit/integration tests, CI security scans, smoke tests, PR review policies, and pre-release checklists. Retrospectives convert learnings into tracked action items to drive continuous improvement.

Process documentation index:
- [Project Management Overview](./octoacme-project-management-overview.md)
- [Project Initiation Guide](./octoacme-project-initiation.md)
- [Project Planning](./octoacme-project-planning.md)
- [Execution & Tracking](./octoacme-execution-and-tracking.md)
- [Risk Management & Communication](./octoacme-risks-and-communication.md)
- [Release & Deployment Guide](./octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](./octoacme-roles-and-personas.md)

How to contribute
- To add or update a process doc, use the ".github/ISSUE_TEMPLATE/Add Content to Project Management Process Docs" template.
- Place new process documents in docs/ and reference them from this README.
```
