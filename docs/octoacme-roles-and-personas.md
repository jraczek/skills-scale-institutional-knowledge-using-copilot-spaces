# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

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

## Product Managers

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

## Project Managers

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

## QA / Testing

### Role Summary
QA / Testing ensures planned work meets acceptance criteria, quality expectations, and release readiness standards. This role makes quality ownership visible across planning, execution, and release activities.

### Responsibilities
- Define or refine the test approach for new features, defects, and regressions
- Validate acceptance criteria with Product Managers before work is considered complete
- Partner with Developers to identify edge cases, automation gaps, and failure patterns
- Surface quality risks, escaped defects, and release-readiness concerns to the Project Manager
- Contribute test evidence, defect triage notes, and sign-off input for releases

### Goals
- Prevent avoidable defects from reaching customers
- Make release readiness measurable and transparent
- Improve confidence in changes through repeatable validation

### Typical Communication
- Daily collaboration with Developers during implementation and bug triage
- Acceptance and regression feedback to Product Managers
- Risk or release-readiness escalation to Project Managers

---

## Engineering Lead

### Role Summary
Engineering Leads provide technical direction, guide architecture and implementation trade-offs, and keep engineering execution aligned with delivery commitments. They translate product intent into a technically sound path forward.

### Responsibilities
- Define technical approach, system boundaries, and key engineering trade-offs
- Coach Developers on solution design, maintainability, and implementation risk
- Identify technical dependencies, architectural constraints, and platform impacts early
- Partner with the Project Manager on sequencing, resourcing constraints, and delivery risk
- Support the Product Manager in evaluating scope options against technical cost and complexity

### Goals
- Reduce technical ambiguity before and during execution
- Keep architecture decisions aligned with product and delivery goals
- Lower the risk of rework caused by unclear or fragile implementation choices

### Typical Communication
- Design reviews and implementation planning with Developers
- Scope and trade-off discussions with Product Managers
- Dependency, risk, and sequencing alignment with Project Managers

---

## Executive Sponsor / Business Stakeholder

### Role Summary
Executive Sponsors or key business stakeholders provide strategic context, approvals, and escalation support for meaningful project decisions. They ensure the project remains aligned to business goals and organizational priorities.

### Responsibilities
- Confirm business priority, expected outcomes, and success measures
- Provide timely input or approvals for major scope, funding, or milestone decisions
- Help unblock escalations that require cross-functional or leadership support
- Review milestone progress and risks with the Project Manager
- Align with the Product Manager on customer and business impact

### Goals
- Keep delivery aligned with strategic priorities
- Reduce delays caused by unclear decision ownership
- Ensure material risks receive timely visibility and support

### Typical Communication
- Milestone reviews and escalation updates with Project Managers
- Outcome alignment and prioritization discussions with Product Managers
- Periodic status reviews with the broader stakeholder group

---

## Customer Support / Operations

### Role Summary
Customer Support or Operations represents the customer-impact and operational-readiness perspective during planning, release, and post-release follow-up. This role helps the team anticipate downstream issues before they become incidents.

### Responsibilities
- Share recurring customer pain points, support themes, and operational constraints
- Review rollout plans, release notes, and support-readiness needs before launch
- Provide feedback on incident trends, usability gaps, and adoption blockers after release
- Coordinate with Project Managers on communication timing and downstream readiness
- Partner with Product Managers and Developers on supportability improvements

### Goals
- Improve readiness for customer-facing change
- Reduce avoidable support load after releases
- Turn operational feedback into actionable product and delivery improvements

### Typical Communication
- Release-readiness and launch coordination with Project Managers
- Customer-impact feedback with Product Managers
- Defect and supportability feedback loops with Developers and QA

---

## UX Research / Design

### Role Summary
UX Research / Design ensures solutions are understandable, usable, and aligned with real user behavior. This role brings customer evidence into product and delivery decisions before and after implementation.

### Responsibilities
- Run lightweight discovery and usability validation for new or changed workflows
- Translate user insights into requirements, acceptance refinements, and design constraints
- Partner with Product Managers to define user outcomes and measurable experience goals
- Collaborate with Developers and Engineering Leads on feasible interaction patterns
- Share usability risks or adoption concerns with Project Managers when they may affect scope or timelines

### Goals
- Reduce rework caused by late discovery of usability issues
- Improve adoption and task completion outcomes for end users
- Keep delivery decisions grounded in customer evidence

### Typical Communication
- Discovery and acceptance refinement with Product Managers
- Design feasibility and implementation alignment with Developers and Engineering Leads
- Timeline-impacting usability risk updates with Project Managers

---

## Security / Compliance

### Role Summary
Security / Compliance ensures delivery decisions satisfy organizational security standards, regulatory expectations, and risk controls. This role reduces late-stage blockers by making governance requirements explicit early.

### Responsibilities
- Identify security and compliance requirements that apply to project scope
- Review architecture and delivery plans for control gaps and policy risks
- Define required evidence, approvals, and checkpoints for release readiness
- Partner with Engineering Leads and Developers on secure design and mitigation strategies
- Escalate material security or compliance risks through Project Managers and Executive Sponsors when needed

### Goals
- Prevent security and compliance blockers near release milestones
- Reduce operational and regulatory risk exposure
- Increase confidence that releases meet control expectations

### Typical Communication
- Requirement and policy clarification with Product Managers and Project Managers
- Design and mitigation reviews with Engineering Leads and Developers
- Readiness sign-off and escalation coordination with Executive Sponsors

---

## Role Interaction Guide

- Project Managers align schedule, risks, and stakeholder communication across all roles; they are the primary coordination point when delivery trade-offs or escalations are needed.
- Product Managers define desired outcomes and acceptance expectations, then rely on QA / Testing, Engineering Leads, and Customer Support / Operations to validate quality, feasibility, and downstream impact.
- Developers work most closely with Engineering Leads and QA / Testing during execution, while also incorporating feedback from Product Managers and operational partners.
- Executive Sponsors or business stakeholders provide approvals and escalation support, but should use Project Managers and Product Managers as the main operational interfaces.
- UX Research / Design partners with Product Managers to shape requirements, with Engineering Leads and Developers to de-risk implementation choices, and with Project Managers when usability concerns affect milestones.
- Security / Compliance works with Engineering Leads and Developers on controls, with Project Managers on governance checkpoints, and with Executive Sponsors for high-impact risk escalations.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

