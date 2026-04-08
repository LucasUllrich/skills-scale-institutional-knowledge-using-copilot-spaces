# OctoAcme — Process Checklists & RACI Summaries

This file contains practical checklists and a concise RACI guidance for common project activities. Use these checklists in project docs, PR templates, and release notes.

---

## Release Checklist (pre-release)
- [ ] All acceptance criteria completed and linked in PRs
- [ ] PRs reviewed and approvals obtained per repo policy
- [ ] CI and automated tests passing
- [ ] Security and dependency scans completed
- [ ] Release notes drafted and reviewed (TechWriter / PdM)
- [ ] Rollback / mitigation plan documented (PM / Automation)
- [ ] Stakeholders and support notified of release window (PM / CSM)
- [ ] Post-deploy verification plan defined

## Release Checklist (deployment)
- [ ] Deploy to staging and run smoke tests
- [ ] Conduct canary/gradual rollout if applicable
- [ ] Monitor key dashboards for anomalies during rollout
- [ ] Execute post-deploy verification checklist

## Release Checklist (post-release)
- [ ] Confirm monitoring and alerts are stable
- [ ] Collect early usage signals (Data Analyst)
- [ ] Update documentation and changelog (TechWriter)
- [ ] Close release card and link follow-up action items

---

## QA Checklist
- [ ] Acceptance criteria translated into test cases
- [ ] Automated tests cover new critical paths
- [ ] Manual exploratory tests executed for complex UX flows
- [ ] Regression smoke tests run and passed
- [ ] Test results documented in PR or test dashboard
- [ ] Known issues and mitigations listed in release docs

---

## Onboarding / Handoff Checklist for a New Feature
- [ ] Feature overview and objectives documented (PdM)
- [ ] Acceptance criteria and DoD in ticket
- [ ] Design assets and interaction notes provided (UX)
- [ ] Developer handoff: environment and run instructions (Dev)
- [ ] Test plan reviewed (QA)
- [ ] Release readiness criteria defined (PM)
- [ ] User-facing doc / help content drafted (TechWriter)
- [ ] Support playbook and escalation path set (CSM)

---

## Role Handoff Quick Guide
- Owner vs. contributor: "Owner" = R (responsible) for execution; "Accountable" = A (final decision/responsibility)
- Always list both an owner and at least one consulted party for cross-functional activities
- Add any deviations from the default RACI to the ticket and notify stakeholders

---

## Compact RACI table (common activities)

| Activity / Role               | PdM | PM | Dev | QA | UX | Data | TechWriter | Automation | CSM |
|-------------------------------|-----|----|-----|-----|-----|------|------------|-----------|-----|
| Define success metrics        | A   | I  | C   | I   | C   | R    | I          | I         | C   |
| Create backlog & priorities   | A   | C  | C   | I   | C   | I    | I          | I         | I   |
| Design & prototyping          | C   | I  | C   | I   | R   | I    | C          | I         | I   |
| Implementation & unit tests   | I   | I  | R   | C   | I   | I    | I          | C         | I   |
| Test & signoff                | I   | I  | C   | R   | C   | I    | I          | C         | I   |
| Release coordination          | I   | A  | R   | R   | I   | I    | I          | C         | I   |
| Post-release analysis         | A   | I  | C   | I   | I   | R    | I          | I         | C   |
| Documentation                 | C   | I  | C   | I   | C   | I    | R          | I         | C   |

Legend: R = Responsible, A = Accountable, C = Consulted, I = Informed

---

## How to use these checklists
- Include the relevant checklist section in your release or sprint checklist
- Make the QA and release checklists part of the PR template or the release issue template
- Adjust RACI per project if stakeholders differ; record exceptions in the project decision log