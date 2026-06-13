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

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

---

## Additional Personas

As projects scale and cross-team interactions increase, we recommend adding the following personas to improve clarity on responsibilities, handoffs, and decision ownership. Add this section after the existing persona descriptions.

1. Technical Lead / Architect
- Role summary: Senior engineer responsible for the technical vision and architecture decisions for a project or large feature area.
- Responsibilities: define system-level design, make technology trade-offs, review and approve major design decisions, mentor engineers, ensure scalability and maintainability.
- Interactions: works with Product Managers to align technical feasibility with product goals, partners with Project Managers on delivery timelines and technical risks, reviews PRs and design documents with Developers.

2. Engineering Manager
- Role summary: People and delivery manager for an engineering team, focusing on capacity, career growth, and cross-team coordination.
- Responsibilities: manage staffing and capacity, unblock team-level issues, conduct performance coaching, support prioritization of technical debt and career development.
- Interactions: coordinates with Project Managers for resourcing and capacity planning, works with Product Managers on prioritization trade-offs, supports Developers with career and performance guidance.

3. QA Lead / Test Engineer
- Role summary: Responsible for test strategy, quality gates, and validation across features and releases.
- Responsibilities: define test plans, coordinate manual and automated testing efforts, manage test environments, ensure acceptance criteria are verified.
- Interactions: collaborates with Developers on testability and CI, works with Project Managers to schedule QA efforts, provides release readiness sign-off.

4. UX Researcher / Designer
- Role summary: Ensures the product is usable, accessible, and aligned with user needs.
- Responsibilities: run research, create UX designs and prototypes, validate usability, define UX acceptance criteria.
- Interactions: partners with Product Managers on user goals and requirements, provides design feedback to Developers, participates in demos and acceptance reviews.

5. Site Reliability Engineer (SRE) / Platform Engineer
- Role summary: Responsible for reliability, observability, and the platform that supports deployments and production operations.
- Responsibilities: define SLOs, implement monitoring and alerting, own incident response runbooks, optimize deployment pipelines and runbook automation.
- Interactions: advises on operability during planning, works with Developers to implement instrumentation, coordinates with Project Managers on deployment windows and risk mitigations.

6. Security Engineer / Security Reviewer
- Role summary: Ensures security requirements are incorporated early and reviews changes for security risks.
- Responsibilities: threat modeling, security reviews, vulnerability scanning, recommend mitigations and acceptance criteria.
- Interactions: consulted during planning and design with Product Managers and Technical Leads, provides mandatory review checkpoints for releases.

7. Release Manager
- Role summary: Coordinates release activities across teams to ensure smooth deployments and communications.
- Responsibilities: own the release checklist, schedule deployment windows, coordinate rollback plans and stakeholder communications.
- Interactions: works with Project Managers, SRE, QA Lead, and Product Managers to validate readiness and execute release steps.

8. Data Analyst / Analytics Owner
- Role summary: Owns metrics, instrumentation, and data validation for project success metrics.
- Responsibilities: define measurement strategy, validate telemetry, produce dashboards and post-release analyses.
- Interactions: partners with Product Managers on success metrics, provides Developers with instrumentation requirements, informs retrospectives with data.

9. Business Analyst / Product Operations
- Role summary: Bridges business stakeholders and delivery teams by clarifying requirements, acceptance criteria, and data flows.
- Responsibilities: refine user stories, document workflows, coordinate stakeholder reviews, track business requirements.
- Interactions: closely supports Product Managers and Project Managers, assists Developers and QA with detailed scenarios.

10. Stakeholder Representative / Domain SME
- Role summary: A named representative from the stakeholder group who provides domain knowledge and timely decisions.
- Responsibilities: answer domain-specific questions, validate feature fit, provide approvals when needed.
- Interactions: engaged by Product Managers for clarifications and sign-offs, escalated to by Project Managers for scope or priority decisions.

Suggested placement: add a new section "Additional Personas" after the existing persona descriptions. Each persona entry follows the document style with Role Summary, Responsibilities, and Typical Interactions.
