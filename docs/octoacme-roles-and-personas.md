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

## New / Additional Personas

The following personas are being added to increase clarity around cross-cutting responsibilities, ownership, and handoffs.

### Technical Program Manager (TPM)
- Role summary: Coordinates complex technical programs, manages cross-team dependencies, and tracks milestones.
- Responsibilities:
  - Track and manage cross-team dependencies and integration points
  - Maintain program-level milestone roadmap and risk register
  - Facilitate technical design trade-offs and decision records
  - Drive cross-team planning and unblock escalations
- Interaction with existing roles:
  - Works closely with PM/PdM on prioritization and milestone planning
  - Coordinates with Developers and Project Managers on scheduling and delivery
  - Escalates architectural or priority decisions to Product Lead when needed

### Delivery Lead
- Role summary: Hands-on coordinator for sprint-level delivery across a small set of features or teams.
- Responsibilities:
  - Manage iteration scope and day-to-day delivery status
  - Coordinate QA, staging verification, and acceptance testing
  - Actively remove blockers and coordinate cross-functional resources
  - Ensure stories meet Definition of Done before close
- Interaction with existing roles:
  - Reports status to PM and coordinates with TPM for dependency visibility
  - Pairs with Developers and QA to complete stories

### Product Designer / UX Researcher
- Role summary: Owns user-facing design and research guidance for features.
- Responsibilities:
  - Provide design specs, wireframes, and accessibility checks
  - Conduct usability validation and research where needed
  - Create handoff artifacts for engineering and QA
- Interaction with existing roles:
  - Works with PdM to shape scope and acceptance criteria
  - Collaborates with Developers on implementation details and accessibility
  - Partners with QA to validate UX acceptance criteria

### SRE / On-call Lead
- Role summary: Ensures reliability, observability, and operational readiness.
- Responsibilities:
  - Define SLIs/SLOs and monitoring requirements
  - Create and maintain on-call runbooks and incident response playbooks
  - Validate operational readiness prior to major releases
  - Lead post-incident triage and remediation guidance
- Interaction with existing roles:
  - Collaborates with Developers on operability design and capacity planning
  - Works with Release Manager to validate deployment and rollback plans
  - Advises PM on reliability trade-offs and risk mitigation

### Release Manager
- Role summary: Coordinates release windows, deployment validation, and rollback plans.
- Responsibilities:
  - Schedule releases and coordinate stakeholders
  - Validate deployment checklists and pre-release criteria
  - Own release announcements and post-release verification
  - Maintain rollback and mitigation plans
- Interaction with existing roles:
  - Works with CI/CD owners, SRE, PM, and Stakeholder Representatives
  - Coordinates with Documentation Owner to publish release notes

### Data Analyst / Measurement Owner
- Role summary: Defines success metrics, instrumentation needs, and dashboarding for features.
- Responsibilities:
  - Define metrics and events required to measure success
  - Validate instrumentation quality and data pipelines
  - Create dashboards and run analysis for post-release evaluation
- Interaction with existing roles:
  - Partners with PdM on success criteria and metric definitions
  - Works with Developers to add instrumentation and telemetry
  - Reports findings to PM and stakeholders

### Security / Compliance Liaison
- Role summary: Ensures features meet security and compliance requirements.
- Responsibilities:
  - Perform threat modeling and security reviews
  - Coordinate security scans and remediation activities
  - Ensure compliance requirements are documented and met
- Interaction with existing roles:
  - Engages with Developers for security fixes
  - Works with PM to prioritize vulnerabilities
  - Notifies Security on-call for critical issues

### Documentation / Enablement Owner
- Role summary: Own product docs, internal runbooks, and user-facing guides for releases.
- Responsibilities:
  - Maintain and publish product documentation and runbooks
  - Coordinate training materials and enablement sessions
  - Ensure documentation is updated alongside releases
- Interaction with existing roles:
  - Works with Product Designer, PM, and Release Manager to produce accurate documentation
  - Coordinates with Support for knowledge base updates

---

## How to use these personas
- Add the responsible person's name or team for each persona in project charters and issue templates.
- Reference personas in checklists (e.g., Release Manager must sign off before production deployment).
- Use the Interaction sections to guide escalation and handoff processes.
