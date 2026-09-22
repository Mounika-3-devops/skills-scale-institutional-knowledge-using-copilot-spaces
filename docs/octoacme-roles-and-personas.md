# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. Role assignments should be adapted to the project, with ownership and handoffs made explicit during planning.

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

## Executive Sponsors

### Role Summary
Executive Sponsors provide strategic direction and organizational support. They confirm that the initiative remains aligned with business priorities and help resolve issues that exceed the delivery team's authority.

### Responsibilities
- Confirm strategic alignment, priority, and expected business outcomes
- Approve major scope, funding, timeline, or priority decisions
- Remove organizational barriers and support cross-team coordination
- Participate in milestone decisions and sponsor-level escalations

### Interactions with Existing Roles
- Partner with the Product Manager to validate the business case and desired outcomes
- Work with the Project Manager on governance, escalations, and major decisions
- Provide direction to delivery leads without taking over day-to-day execution

---

## Engineering Managers / Delivery Leads

### Role Summary
Engineering Managers or Delivery Leads coordinate technical execution and team capacity. They translate delivery commitments into an achievable engineering approach while supporting developers and technical quality.

### Responsibilities
- Plan engineering capacity and sequence technical work
- Coordinate technical dependencies, architecture decisions, and delivery risks
- Support developers with prioritization, coaching, and removal of technical blockers
- Provide engineering estimates and readiness information for planning and release decisions

### Interactions with Existing Roles
- Work with the Project Manager on schedules, dependencies, risks, and delivery status
- Partner with the Product Manager to balance customer value, scope, and technical constraints
- Guide Developers during implementation and design reviews
- Coordinate with the QA Lead, Security/Compliance Lead, and Support/Operations Lead on readiness

---

## QA Leads / Test Managers

### Role Summary
QA Leads or Test Managers establish the quality approach and coordinate validation across the project lifecycle. They ensure acceptance criteria are testable and that release decisions are supported by evidence.

### Responsibilities
- Define the test strategy, coverage expectations, and quality gates
- Coordinate integration, end-to-end, regression, and manual testing where applicable
- Track defects and communicate quality risks and release readiness
- Confirm that acceptance criteria and the Definition of Done are validated

### Interactions with Existing Roles
- Work with the Product Manager to clarify acceptance criteria
- Partner with Developers and the Engineering Manager/Delivery Lead on testability, automation, and defect resolution
- Provide the Project Manager with quality status, risks, and release recommendations
- Coordinate with Security/Compliance and Support/Operations before production release

---

## Security / Compliance Leads

### Role Summary
Security or Compliance Leads identify and manage security, privacy, regulatory, and policy requirements that affect delivery. They provide guidance early enough for the team to address risks before release.

### Responsibilities
- Identify applicable security, privacy, and compliance requirements
- Review designs, implementation plans, and release evidence for relevant risks
- Define required security testing, approvals, and mitigations
- Escalate unresolved high-impact risks through the agreed risk and incident paths

### Interactions with Existing Roles
- Work with the Product Manager to understand data, customer, and regulatory needs
- Advise Developers and the Engineering Manager/Delivery Lead on secure design and remediation
- Coordinate with the Project Manager to record risks, owners, mitigations, and decisions
- Partner with QA and Support/Operations on release checks and operational controls

---

## Support / Operations Leads

### Role Summary
Support or Operations Leads prepare the service and its support organization for release and ongoing operation. They ensure that operational ownership, monitoring, and customer support needs are addressed before launch.

### Responsibilities
- Define operational readiness requirements, monitoring, alerts, and service ownership
- Prepare runbooks, support documentation, and incident handoff procedures
- Validate deployment, rollback, backup, and recovery considerations
- Coordinate post-release monitoring and communicate production issues

### Interactions with Existing Roles
- Work with the Project Manager to track operational dependencies and release readiness
- Partner with Developers and the Engineering Manager/Delivery Lead on observability and deployment design
- Coordinate with the QA Lead on smoke tests and verification plans
- Provide the Product Manager and stakeholders with service impact and support-readiness information

---

## Stakeholder Representatives

### Role Summary
Stakeholder Representatives provide domain expertise, user context, business validation, and feedback from affected groups. They help the team make informed decisions without replacing the accountable product or delivery owner.

### Responsibilities
- Contribute domain requirements, constraints, and user needs
- Review proposed scope and validate outcomes at agreed milestones
- Provide timely feedback, decisions, and approval input within their authority
- Communicate project impacts to the groups they represent

### Interactions with Existing Roles
- Work with the Product Manager to refine priorities, requirements, and success measures
- Provide the Project Manager with decisions, risks, dependencies, and communication needs
- Collaborate with Developers and QA on examples, acceptance criteria, and validation
- Receive regular status updates and escalation requests through the agreed communication cadence

---

## Lifecycle Accountability and Handoffs

The following lightweight accountability model clarifies how the personas collaborate. The accountable owner may vary by project, but the handoffs should be explicitly recorded in the project plan.

| Lifecycle phase | Primary accountability | Key collaborators and handoffs |
| --- | --- | --- |
| Initiation | Product Manager and Executive Sponsor | Project Manager coordinates the one-pager; Stakeholder Representatives provide context; Engineering Manager/Delivery Lead identifies feasibility and risks |
| Planning | Project Manager and Product Manager | Engineering Manager/Delivery Lead estimates capacity and dependencies; QA Lead defines the test approach; Security/Compliance and Support/Operations identify readiness needs |
| Execution | Engineering Manager/Delivery Lead and Developers | Project Manager tracks progress and blockers; Product Manager clarifies scope; QA validates increments; Security/Compliance manages security risks |
| Release | Project Manager and Product Manager | QA confirms quality evidence; Support/Operations confirms service readiness; Security/Compliance confirms required controls; Executive Sponsor supports major go/no-go decisions |
| Retrospective and improvement | Project Manager and delivery team | Product Manager, Developers, QA, and supporting personas review outcomes, agree action owners, and track improvements |

When ownership is unclear, the Project Manager should record the decision or dependency, identify an owner, and escalate through the documented path. Role assignments should be revisited when project scope, team composition, or delivery risk changes.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Use the lifecycle accountability model to make ownership, handoffs, and escalation expectations explicit in project artifacts.
