# OctoAcme Project Management Documentation

This folder is the central hub for OctoAcme's project management guidance. The documentation describes a lightweight but structured operating model built around customer-first prioritization, iterative delivery, clear ownership, data-informed decisions, and psychological safety. Projects move through a consistent lifecycle from initiation and planning through execution, release, and retrospective review so teams can deliver in small, testable increments while keeping scope, risks, and outcomes visible.

At the workflow level, OctoAcme starts by defining the business problem, success metrics, stakeholders, initial milestones, and early risks in a one-pager before moving into detailed planning. Planning converts approved work into a prioritized backlog with acceptance criteria, estimates, a Definition of Done, release milestones, and an initial QA approach. During execution, teams use a shared project board, daily standups, weekly delivery syncs, and end-of-sprint demos to track progress, surface blockers, and manage dependencies.

Roles are intentionally explicit. Project Managers coordinate timelines, documentation, risks, dependencies, and stakeholder communication; Product Managers own outcomes, prioritization, and success metrics; developers build and review solutions while helping identify technical risks; and QA/testing validates that work meets quality and acceptance expectations. Communication follows a regular cadence with weekly PM and product alignment, delivery-team standups, stakeholder updates, and clear escalation paths when blockers or incidents affect delivery.

Quality assurance is built into the delivery process rather than treated as a final step. Work is expected to meet documented acceptance criteria and the team's Definition of Done, with small pull requests, code review, automated tests, linting, security scans, and smoke checks before release. Releases also require rollback planning, post-deployment verification, and stakeholder communication. After milestones, releases, and incidents, teams run retrospectives to capture lessons learned and convert them into owned improvement actions.

## Quick Reference

| Document | Purpose | When to use it |
| --- | --- | --- |
| [octoacme-project-management-overview.md](octoacme-project-management-overview.md) | High-level introduction to OctoAcme's principles, lifecycle, roles, artifacts, and communication cadence. | Start here when you need the overall model or a quick orientation. |
| [octoacme-project-initiation.md](octoacme-project-initiation.md) | Describes how to validate a new idea, align stakeholders, and define initial success measures and milestones. | Use when shaping a new project or deciding whether it should move into planning. |
| [octoacme-project-planning.md](octoacme-project-planning.md) | Covers kickoff, backlog creation, estimation, Definition of Done, dependencies, and release planning. | Use after approval to turn an initiative into an actionable plan. |
| [octoacme-execution-and-tracking.md](octoacme-execution-and-tracking.md) | Explains day-to-day team rhythm, board workflow, pull request expectations, and delivery metrics. | Use while work is in progress to manage execution and reporting. |
| [octoacme-risks-and-communication.md](octoacme-risks-and-communication.md) | Documents the risk register, mitigation workflow, stakeholder updates, and escalation paths. | Use when tracking dependencies, risks, blockers, or stakeholder communication needs. |
| [octoacme-release-and-deployment.md](octoacme-release-and-deployment.md) | Standardizes release readiness, deployment steps, rollback planning, and release notes. | Use when preparing for staging, production deployment, or incident response during release. |
| [octoacme-retrospective-and-continuous-improvement.md](octoacme-retrospective-and-continuous-improvement.md) | Defines the retrospective format and how improvement actions are tracked over time. | Use after sprints, releases, milestones, or incidents to capture and act on learnings. |
| [octoacme-roles-and-personas.md](octoacme-roles-and-personas.md) | Provides role summaries, responsibilities, goals, and communication patterns for key personas. | Use when clarifying ownership, collaboration expectations, or role-specific responsibilities. |
| [Instructions](Instructions) | Summarizes the purpose of this documentation space and where process-related artifacts live. | Use when you need the repository-specific context for this Copilot Space. |

## Project Lifecycle At A Glance

1. Initiation: define the problem, goal, stakeholders, timeline, and initial risks.
2. Planning: create the backlog, estimates, Definition of Done, milestones, and test approach.
3. Execution: deliver in increments, review progress, and manage blockers and dependencies.
4. Release: verify readiness, deploy safely, validate outcomes, and communicate status.
5. Retrospective: capture learnings and feed improvements back into the backlog and process docs.