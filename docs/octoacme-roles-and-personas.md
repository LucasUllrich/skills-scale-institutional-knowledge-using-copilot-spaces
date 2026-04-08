# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.
It describes responsibilities, goals, and how each role commonly interacts with others. Use these definitions for clearer ownership, onboarding, and RACI mapping across activities.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers (PdM)

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers (PM)

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## QA Engineer (Quality Assurance)

### Role Summary
Ensures releases meet quality, reliability, and acceptance standards while enabling efficient verification.

### Responsibilities
- Author and execute manual and automated test plans
- Define acceptance test criteria and test cases
- Collaborate with Developers to reproduce and isolate bugs
- Maintain test automation coverage and pipelines
- Sign off on release readiness per defined quality gates

### Interaction
- Works closely with Developers and Automation Engineers to keep test suites stable and fast
- Partners with PM and PdM to understand acceptance criteria and risk tolerance
- Coordinates with Technical Writers for test/QA notes in release documentation

---

## UX Designer

### Role Summary
Advocates for user needs and ensures the product delivers usable, delightful experiences.

### Responsibilities
- Conduct user research, usability testing, and synthesis
- Create wireframes, prototypes, and interaction specifications
- Define UX acceptance criteria and accessibility checks
- Help validate product decisions with user-centered evidence

### Interaction
- Collaborates with PdM on problem framing and success criteria
- Works with Developers to ensure design feasibility and handoff quality
- Supports QA with UX-focused test cases and acceptance checks

---

## Data Analyst

### Role Summary
Surfaces actionable insights and provides reporting on product and project metrics to inform decisions.

### Responsibilities
- Define success metrics in collaboration with PdM and PM
- Implement and validate instrumentation (events, metrics)
- Maintain dashboards and run analyses post-launch
- Identify signals that require product or process changes

### Interaction
- Partners with PdM for success measurement and outcome analysis
- Advises PM on progress and impact reporting for stakeholders
- Works with Developers and Automation Engineers on reliable telemetry

---

## Technical Writer

### Role Summary
Maintains clear, accurate, and up-to-date product and process documentation for internal and external audiences.

### Responsibilities
- Document features, APIs, runbooks, and process guides
- Create onboarding materials and user-facing help content
- Maintain changelogs and release notes
- Ensure docs reflect current design and behavior after releases

### Interaction
- Works with PdM, Developers, and QA to gather technical and usage details
- Collaborates with PM to ensure process documentation is accessible and followed
- Partners with Customer Success for user-facing content and FAQs

---

## Automation Engineer (CI/CD / SRE-focused)

### Role Summary
Improves build, test, and deployment automation to accelerate delivery and reduce manual risk.

### Responsibilities
- Design and maintain CI/CD pipelines, test runners, and deployment automation
- Implement environment standardization and infrastructure-as-code where applicable
- Monitor and improve pipeline reliability and performance
- Enable self-service workflows for the delivery team

### Interaction
- Works with Developers and QA to integrate tests and ensure pipelines provide fast feedback
- Coordinates with PM for release windows and rollback strategies
- Supports Technical Writers with runbook and deployment docs

---

## Customer Success Manager (CSM) / Support Lead

### Role Summary
Captures real-world user feedback and ensures product decisions consider customer needs post-launch.

### Responsibilities
- Triage, track, and escalate customer issues and feature requests
- Collect satisfaction signals (NPS, CSAT) and relay trends to product teams
- Coordinate customer communications for incidents or product changes
- Help prioritize support-driven backlog items

### Interaction
- Provides PdM with user-facing context and feature-impact reports
- Informs PM and Developers of critical customer-impacting issues for prioritization
- Works with Technical Writers to maintain clear support resources and FAQs

---

## Using these personas

- For new projects, list proposed role participation in the Project One-pager "Proposed team / roles".
- During planning, explicitly assign owners and collaborators for each backlog item (Owner vs. Contributor).
- Use the process checklists (docs/octoacme-process-checklists.md) for release, QA, and handoffs.
- When in doubt, refer to the RACI summaries in the checklists doc to resolve confusion about who is Responsible/Accountable/Consulted/Informed.

---

## Example interactions (short)
- Feature design: PdM (A), UX (R), Dev (R), QA (C), TechWriter (C), PM (I)
- Release coordination: PM (A), Dev (R), QA (R), Automation (C), CSM (I), PdM (I)
- Incident response: Dev (R), PM (A), CSM (I), Automation (C), TechWriter (C)

Use these definitions to reduce ambiguity, speed onboarding, and create a clear trail of ownership across the project lifecycle.