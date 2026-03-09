# OctoAcme Project Management Documentation

Welcome to OctoAcme's project management documentation. This directory contains structured guides and templates that define how we initiate, plan, execute, release, and improve our projects.

## Purpose

This documentation centralizes our project management methodology, making it easy for all team members to understand our approach, access process guides, and maintain consistency across initiatives.

## Core Principles

OctoAcme project management is built on these core principles:

- **Customer-First**: Prioritize customer value and usability in all decisions.
- **Iterative Delivery**: Deliver small, testable increments and gather feedback early.
- **Clear Ownership**: Each project has a named Project Manager (PM) and Product Manager (PdM).
- **Data-Informed Decisions**: Measure impact and iterate based on evidence.
- **Psychological Safety**: Encourage feedback, learning, and continuous improvement.

## Project Lifecycle

Every OctoAcme project follows a structured five-stage lifecycle:

### 1. **Initiation**
Validate business need, align stakeholders, and define project objectives.
- Deliverable: Project One-pager (Problem, Goal, Success Metrics)
- Gate: Sponsor/stakeholder approval to move to Planning

### 2. **Planning**
Break work into shippable increments and create an actionable plan.
- Deliverable: Prioritized backlog, acceptance criteria, Definition of Done, risk register
- Gate: Kickoff held, team availability confirmed

### 3. **Execution**
Build, test, and iterate based on acceptance criteria and team cadence.
- Cadence: Daily standups, weekly delivery syncs, demos at milestone end
- Tracking: Project board (Backlog → Ready → In Progress → In Review → QA → Done)

### 4. **Release**
Deploy to production with standardized checklists and risk mitigation.
- Checklist: Pre-release validation, deployment steps, post-deploy verification, rollback plan
- Communication: Release notes and stakeholder announcements

### 5. **Retrospective & Continuous Improvement**
Capture learnings and convert them into actionable improvements.
- Meeting: 45–75 minute timeboxed retrospective after sprint or release
- Outcome: Action items tracked in backlog with clear owners and timelines

## Key Roles

| Role | Responsibility | Key Output |
|------|----------------|-----------|
| **Project Manager** | Coordinates delivery, schedules, risks, communications | Status updates, risk register, escalations |
| **Product Manager** | Defines outcomes, prioritizes backlog, measures success | Product strategy, backlog prioritization, metrics |
| **Developers** | Implement features, write tests, participate in design | Code, PRs, technical estimates |
| **QA/Testing** | Validate quality and acceptance criteria | Test plans, acceptance sign-off |
| **Stakeholders** | Provide inputs, strategic alignment, approvals | Decisions, requirements, budget authorization |

For detailed role descriptions and personas, see [Roles and Personas](./octoacme-roles-and-personas.md).

## Key Artifacts

Throughout the project lifecycle, we maintain these core artifacts:

- **Project Charter / One-pager**: Problem statement, objectives, success metrics, stakeholders, timeline
- **Backlog**: Prioritized list of work items with acceptance criteria and estimates
- **Risk Register**: Identified risks, impact/probability assessment, mitigation plans, status
- **Definition of Done (DoD)**: Checklist of criteria an item must meet before being marked complete
- **Release Notes**: Change summary, migration steps, known issues, rollback guidance
- **Retrospective Notes**: Learnings, action items, owners, and due dates
- **Project Board**: Visual tracking of work status from backlog through done

## Process Documents

### Quick Navigation
- **New to OctoAcme?** Start with [Project Management Overview](./octoacme-project-management-overview.md)
- **Starting a new project?** Follow [Project Initiation Guide](./octoacme-project-initiation.md)
- **Ready to plan work?** Read [Project Planning](./octoacme-project-planning.md)
- **In execution?** Reference [Execution & Tracking](./octoacme-execution-and-tracking.md)
- **Managing risks?** See [Risk Management & Communication](./octoacme-risks-and-communication.md)
- **Preparing to release?** Follow [Release & Deployment Guide](./octoacme-release-and-deployment.md)
- **Wrapping up?** Run a [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- **Understanding team roles?** Review [Roles and Personas](./octoacme-roles-and-personas.md)

### Full Document List
1. [**Project Management Overview**](./octoacme-project-management-overview.md) — Introduction to OctoAcme's approach, principles, roles, and high-level lifecycle
2. [**Project Initiation Guide**](./octoacme-project-initiation.md) — Steps to validate, authorize, and launch a new project
3. [**Project Planning**](./octoacme-project-planning.md) — How to scope, estimate, and plan work for delivery
4. [**Execution & Tracking**](./octoacme-execution-and-tracking.md) — Daily rhythms, workflows, quality standards, and blocker escalation
5. [**Risk Management & Communication**](./octoacme-risks-and-communication.md) — How to identify, track, and communicate risks and dependencies
6. [**Release & Deployment Guide**](./octoacme-release-and-deployment.md) — Standardized process for deploying to production safely
7. [**Retrospective & Continuous Improvement**](./octoacme-retrospective-and-continuous-improvement.md) — How to capture learnings and iterate on process
8. [**Roles and Personas**](./octoacme-roles-and-personas.md) — Definitions of core project roles and responsibilities

## Communication Cadence

- **Daily**: Team standups (15 min) — progress, blockers, dependencies
- **Weekly**: PM + PdM sync — alignment on backlog, risks, roadmap
- **Twice Weekly**: Delivery team standups (or as agreed)
- **Monthly**: Stakeholder updates — high-level progress and strategic alignment
- **As Needed**: Escalations and incident communication

## How to Use This Documentation

1. **For New Team Members**: Start with the [Overview](./octoacme-project-management-overview.md) and [Roles and Personas](./octoacme-roles-and-personas.md) to understand our methodology and how you fit in.

2. **For Project Leads**: Use the lifecycle guides (Initiation → Planning → Execution → Release → Retrospective) as a checklist and reference for each project phase.

3. **For Process Improvement**: Process updates and lessons learned are captured in GitHub Issues using the [Add Content to Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template. This keeps documentation living and version-controlled.

4. **In Your Copilot Space**: Add these docs to your Copilot Space context to ground Copilot's guidance in OctoAcme's processes.

## Contributing to This Documentation

Found a gap in our processes? Have a suggestion or improvement?

1. Open an issue using the [**Add Content to Project Management Process Docs**](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template.
2. Include:
   - Which document needs updating (or if it's a new document)
   - Summary of the new content
   - Rationale and stakeholder context
   - Suggested content (optional)
3. Discussion and approval will happen in the issue thread.
4. Updates are then merged into the repository and versioned.

## Questions?

If you have questions about how OctoAcme runs projects, check the relevant process document above or reach out to your Project Manager or Product Manager.

---

**Last Updated**: 2026-03-09  
**Maintained By**: OctoAcme Project Management Office
