# OctoAcme Project Management Docs

Welcome to the OctoAcme Program/Project Management documentation hub. These docs consolidate our project processes, artifacts, and templates so teams can onboard quickly, run predictable delivery, and iterate safely.

Overview
OctoAcme follows an iterative, outcome-driven lifecycle that emphasizes customer value, clear ownership, and continuous improvement. Work progresses through Initiation (one-pager and stakeholder alignment), Planning (backlog, estimates, Definition of Done), Execution (small increments, PR-driven delivery, CI), Release (checklists, smoke tests, rollback plans), and Close (retrospectives and tracked action items). Our approach promotes small, testable changes, defined responsibilities, and evidence-based decisions informed by metrics and retrospectives.

Workflows & Roles
Key workflows include a project board (Backlog → Ready → In Progress → In Review → QA → Done), a PR-first delivery pattern (small PRs, link PRs to issues, CI + linting + security scans run before review), and a lightweight risk register with owners and mitigations. Core roles are Product Manager (defines outcomes and prioritizes), Project Manager (coordinates delivery, schedules, and risks), Developers (implement and test), QA (validate acceptance), and Stakeholders (input and approvals). Communication happens via a regular rhythm: daily standups, weekly delivery syncs, sprint demos, and monthly stakeholder updates.

Quality & Communication
Quality assurance relies on unit and integration tests, end-to-end smoke tests for critical flows, CI security scanning, and manual QA where necessary. Blocker escalation follows a clear path (team → PM → Product Lead → Sponsor) and incident communication follows a blameless triage + post-incident retrospective pattern. Retrospectives produce prioritized action items that feed improvements back into the backlog.

Docs Index
- [Project Management Overview](./octoacme-project-management-overview.md)
- [Project Initiation Guide](./octoacme-project-initiation.md)
- [Project Planning](./octoacme-project-planning.md)
- [Execution & Tracking](./octoacme-execution-and-tracking.md)
- [Risk Management & Communication](./octoacme-risks-and-communication.md)
- [Release & Deployment Guide](./octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](./octoacme-roles-and-personas.md)

These docs are living artifacts. Please open PRs to suggest improvements, and add any process-specific artifacts (for use by Copilot Spaces) into `.copilot/` if needed.