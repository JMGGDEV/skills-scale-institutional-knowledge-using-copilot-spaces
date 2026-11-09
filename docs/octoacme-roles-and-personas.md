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

## Engineering / Technical Leads

### Role Summary
Engineering or Technical Leads provide technical direction and ensure implementation decisions support the product outcome and delivery plan.

### Responsibilities
- Guide architecture, technical design, and engineering standards
- Identify technical risks, dependencies, and integration needs
- Support engineering estimates and sequencing decisions
- Review implementation approaches and promote maintainability
- Coordinate technical decisions across Developers and external engineering teams

### Interaction with Existing Roles
- Partner with the Product Manager on feasibility, scope, and technical trade-offs.
- Work with the Project Manager to surface technical dependencies, risks, and schedule impacts.
- Guide Developers while preserving their ownership of implementation work.
- Collaborate with QA/Testing on testability, quality risks, and technical acceptance criteria.
- Explain technical implications to Stakeholders in an accessible way.

### Typical Lifecycle Touchpoints
- Planning estimates, architecture decisions, technical risk reviews, design reviews, and release readiness.

---

## UX / Product Designers and Researchers

### Role Summary
UX or Product Designers and Researchers represent user needs and validate that proposed solutions are understandable, usable, and fit for purpose.

### Responsibilities
- Conduct user research and synthesize user needs
- Define workflows, interaction patterns, prototypes, and design guidance
- Validate concepts through usability testing and feedback
- Document experience decisions and accessibility considerations
- Contribute user-centered acceptance criteria

### Interaction with Existing Roles
- Collaborate with the Product Manager on user problems, outcomes, prioritization, and discovery.
- Work with Developers and Engineering/Technical Leads to adapt designs to feasible technical solutions.
- Partner with QA/Testing on usability, accessibility, and experience-focused validation.
- Coordinate with the Project Manager on discovery activities, dependencies, and milestone timing.
- Share research findings and design rationale with Stakeholders to support informed decisions.

### Typical Lifecycle Touchpoints
- Initiation, discovery, backlog refinement, design review, acceptance validation, and retrospective learning.

---

## Security and Privacy Leads

### Role Summary
Security and Privacy Leads identify security, privacy, and compliance needs and help the team reduce related risks throughout delivery.

### Responsibilities
- Define applicable security, privacy, and compliance requirements
- Identify threats, data risks, and control gaps
- Advise on mitigations and secure design practices
- Coordinate security reviews and readiness checks
- Confirm that security and privacy considerations are represented in acceptance criteria and release decisions

### Interaction with Existing Roles
- Work with the Product Manager to balance customer value, data use, and compliance obligations.
- Partner with the Project Manager to record, escalate, and track security risks and dependencies.
- Advise Developers and Engineering/Technical Leads on secure implementation and architecture.
- Coordinate with QA/Testing on security verification and evidence.
- Brief Stakeholders on material risks, residual risk, and release readiness.

### Typical Lifecycle Touchpoints
- Initiation risk assessment, planning, design review, threat modeling, testing, release approval, and incident follow-up.

---

## Data and Analytics Leads

### Role Summary
Data and Analytics Leads connect project outcomes to measurable signals and ensure that instrumentation and reporting support reliable decisions.

### Responsibilities
- Define success metrics, measurement plans, and reporting needs
- Specify event instrumentation and data quality expectations
- Identify gaps in telemetry and analytic dependencies
- Validate that data supports product and delivery decisions
- Communicate outcome trends and measurement limitations

### Interaction with Existing Roles
- Partner with the Product Manager to define measurable outcomes and interpret results.
- Work with the Project Manager to provide progress indicators and highlight metric-related risks.
- Collaborate with Developers and Engineering/Technical Leads on instrumentation design and implementation.
- Coordinate with QA/Testing to verify events, data quality, and reporting behavior.
- Help Stakeholders understand project impact and evidence-based trade-offs.

### Typical Lifecycle Touchpoints
- Initiation success metrics, planning measurement design, implementation instrumentation, release verification, and post-release review.

---

## Release, Operations, and Site Reliability Leads

### Role Summary
Release, Operations, or Site Reliability Leads ensure that changes can be deployed, observed, supported, and recovered safely.

### Responsibilities
- Define operational readiness and deployment requirements
- Coordinate environments, observability, capacity, and operational dependencies
- Maintain rollback and mitigation plans
- Validate smoke tests and post-deployment verification
- Monitor service health and feed operational learnings back into planning

### Interaction with Existing Roles
- Coordinate with the Project Manager on release timing, dependencies, risks, and escalation.
- Work with the Product Manager on rollout scope, customer impact, and operational trade-offs.
- Partner with Developers and Engineering/Technical Leads on deployment design, reliability, and observability.
- Collaborate with QA/Testing on environment readiness, smoke tests, and release verification.
- Keep Stakeholders informed about operational impact, rollout status, and incidents.

### Typical Lifecycle Touchpoints
- Release planning, environment preparation, readiness review, deployment, post-release verification, and incident retrospectives.

---

## Customer Support and Enablement Representatives

### Role Summary
Customer Support and Enablement Representatives bring customer-facing readiness into planning and help the organization support adoption after delivery.

### Responsibilities
- Identify support, training, documentation, and communication needs
- Prepare help content, enablement materials, and support guidance
- Surface recurring customer questions and adoption risks
- Coordinate readiness for launches and significant changes
- Feed customer feedback into backlog and retrospective discussions

### Interaction with Existing Roles
- Collaborate with the Product Manager on customer needs, adoption goals, and feedback-driven priorities.
- Work with the Project Manager on communication plans, milestones, launch coordination, and readiness tracking.
- Partner with Developers and QA/Testing to understand behavior, known issues, and support implications.
- Coordinate with Release/Operations Leads on rollout timing, incidents, and customer-facing status.
- Help Stakeholders assess adoption, customer impact, and follow-up actions.

### Typical Lifecycle Touchpoints
- Planning, acceptance readiness, release communications, launch support, feedback collection, and retrospective review.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Engage each persona when its decisions, risks, or handoffs affect the project lifecycle; the roles complement rather than replace the accountability of the existing Project Manager, Product Manager, Developers, QA/Testing, and Stakeholders.
