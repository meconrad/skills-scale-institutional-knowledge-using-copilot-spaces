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

## Additional Personas (proposed)

The following personas are commonly involved in cross-functional projects and fill important, frequently overlooked responsibilities. Adding them to the main Personas document reduces ambiguity, clarifies handoffs, and makes it easier to know who to engage for non-functional concerns (security, releases, data, etc.).

### Delivery Lead
- Role summary: Owns day-to-day delivery for an initiative (schedule, dependencies, risks) and coordinates cross-team activities to ensure timely delivery.
- Responsibilities:
  - Maintain the project schedule and milestone plan
  - Coordinate cross-team dependencies and handoffs
  - Track and escalate risks and mitigation status
  - Drive weekly delivery syncs and follow-ups
- Interactions:
  - Works closely with PM and PdM to translate scope into deliverables
  - Coordinates with Technical Leads and Release Manager for deploy readiness
  - Escalates unresolved blockers to Product Lead
- When to engage: At planning, when dependencies span multiple teams, and during pre-release coordination.

### Technical Lead
- Role summary: Leads the technical implementation for an initiative, balancing delivery with long-term maintainability.
- Responsibilities:
  - Propose and document the technical approach
  - Make architecture decisions for the initiative
  - Mentor and review the work of developers
  - Identify technical risks and propose mitigations
- Interactions:
  - Collaborates with Architects, Developers, and QA to ensure implementation meets requirements
  - Reviews complex PRs and design documents
- When to engage: During design, implementation planning, and for high-risk technical decisions.

### Architect
- Role summary: Ensures system-level consistency and long-term architectural integrity across projects.
- Responsibilities:
  - Validate design proposals for systemic impact
  - Own cross-service integration patterns and interface contracts
  - Provide guidance on scalability, performance, and maintainability
- Interactions:
  - Advises Technical Leads and Product on trade-offs
  - Reviews integration plans with SRE and Security
- When to engage: When changes affect system boundaries, integrations, or long-term architecture.

### UX Researcher / Designer
- Role summary: Validates user needs and designs usable, accessible interfaces.
- Responsibilities:
  - Conduct user research and usability testing
  - Produce design specifications and prototypes
  - Ensure accessibility and consistency with design system
- Interactions:
  - Works with PdM to define user goals and acceptance criteria
  - Collaborates with Developers to translate designs into implementation
- When to engage: At discovery, before finalizing acceptance criteria, and during UI implementation.

### Analytics Engineer / Data Owner
- Role summary: Defines the measurement strategy and ensures data quality for product decisions.
- Responsibilities:
  - Define success metrics and instrumentation requirements
  - Implement tracking and maintain dashboards
  - Ensure data health and observability for experiments
- Interactions:
  - Works with PdM to align on measurable outcomes
  - Collaborates with Developers on instrumentation and with Analysts on dashboards
- When to engage: During planning when success metrics are defined and prior to launch to validate instrumentation.

### Release Manager
- Role summary: Coordinates release activities, ensuring deployments are planned, communicated, and reversible.
- Responsibilities:
  - Create and maintain release plans and cutover steps
  - Coordinate deployment windows and stakeholder communications
  - Verify rollback and mitigation plans
- Interactions:
  - Works with PM, SRE, and Support to schedule releases and validate runbooks
  - Triggers post-release verification and communicates status
- When to engage: During release planning and execution, especially for cross-team or user-impacting releases.

### Security Lead
- Role summary: Ensures security and compliance considerations are addressed throughout the project lifecycle.
- Responsibilities:
  - Perform security reviews and threat modelling
  - Ensure automated scans and manual checks are run and remediated
  - Advise on compliance requirements and data handling
- Interactions:
  - Engages during design and PR review for security-sensitive work
  - Escalates to Security on-call for critical vulnerabilities
- When to engage: For any feature handling sensitive data or affecting authentication/authorization.

### Support / Customer Advocacy Lead
- Role summary: Represents customer and support perspectives, ensuring product decisions account for real-world incidents and feedback.
- Responsibilities:
  - Surface customer-reported issues and prioritize fixes
  - Maintain communication channels with support teams
  - Provide input on usability and supportability concerns
- Interactions:
  - Works with PM to prioritize customer-impacting work
  - Collaborates with Developers for reproducing and resolving issues
- When to engage: When addressing customer-reported defects or when changes may impact support workflows.

### Site Reliability Engineer (SRE) / On-call Owner
- Role summary: Ensures the reliability and operability of production systems.
- Responsibilities:
  - Define runbooks and reliability targets
  - Participate in incident planning and postmortems
  - Validate deploy readiness and performance testing
- Interactions:
  - Works with Developers and Release Manager on deploy readiness and rollback procedures
  - Collaborates with Architects for capacity and scaling plans
- When to engage: During production rollouts, performance-sensitive changes, and incident response.

---

## How to use these personas
- Add a short note on the project README when a persona is required for the initiative (e.g., "Engage Security Lead for handling PII").
- Include persona engagement in the Definition of Ready for backlog items needing specialized input.
- Reference the "When to engage" notes in planning and pre-release checklists.

