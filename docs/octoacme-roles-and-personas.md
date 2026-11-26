# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. Roles may be combined or shared on smaller projects, but each responsibility and decision should have a clearly identified owner.

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

## UX / Design Leads

### Role Summary
UX/Design Leads shape usable, accessible experiences that address user needs and support product outcomes.

### Responsibilities
- Conduct or coordinate user research and translate findings into design requirements
- Create and validate user flows, prototypes, and interaction designs
- Incorporate accessibility and usability considerations
- Document design decisions and support design consistency

### Decision Authority
Own day-to-day design recommendations and artifacts; resolve product-priority trade-offs with the Product Manager and escalate unresolved scope decisions to the appropriate product decision-maker.

### How They Work with Existing Roles
- Partner with Product Managers to connect user needs, product goals, and acceptance criteria
- Collaborate with Developers and Technical Leads to assess feasibility and refine designs
- Coordinate with QA/Quality Leads to make usability and accessibility verifiable
- Keep Project Managers informed of design dependencies and review timing

---

## Technical Leads / Architects

### Role Summary
Technical Leads or Architects guide the technical approach and help ensure the solution is coherent, maintainable, and feasible.

### Responsibilities
- Define or facilitate architecture and technical design decisions
- Identify technical risks, integration points, and dependencies
- Establish engineering standards and guide implementation choices
- Support estimates and break down complex technical work

### Decision Authority
Own technical design decisions within agreed product, security, and operational constraints; surface significant trade-offs or risks to Product Managers and Project Managers for coordination and escalation.

### How They Work with Existing Roles
- Guide Developers through design reviews, implementation, and technical problem-solving
- Work with Product Managers to explain technical options and consequences for scope or outcomes
- Partner with Project Managers to identify dependencies, sequencing, and delivery risks
- Consult Security/Privacy and Operations/SRE roles on applicable design and readiness requirements

---

## QA / Quality Leads

### Role Summary
QA/Quality Leads coordinate the quality strategy so that delivered work meets acceptance criteria and is fit for use.

### Responsibilities
- Define test approach, coverage, and quality checkpoints with the team
- Identify test data, environments, and automation needs
- Coordinate exploratory, integration, and end-to-end testing as appropriate
- Report quality risks and help track defects through resolution

### Decision Authority
Recommend whether quality evidence meets agreed acceptance and release criteria; unresolved release-risk decisions go to the designated product and release decision-makers.

### How They Work with Existing Roles
- Collaborate with Product Managers to make acceptance criteria testable
- Work with Developers to build testability into implementation and maintain automated tests
- Coordinate validation timing and defect visibility with Project Managers
- Partner with UX/Design Leads on usability and accessibility validation

---

## Security / Privacy Leads

### Role Summary
Security/Privacy Leads advise teams on protecting systems and data and on meeting applicable security and privacy requirements.

### Responsibilities
- Identify security and privacy risks, requirements, and controls relevant to the project
- Advise on secure design, data handling, and privacy considerations
- Coordinate or recommend appropriate reviews and assessments
- Track findings and communicate unresolved risks through established escalation paths

### Decision Authority
Provide security and privacy guidance and identify required controls; decisions to accept residual risk or exceptions belong to the organization’s designated authority, not this role alone.

### How They Work with Existing Roles
- Advise Developers and Technical Leads on secure implementation and design choices
- Work with Product Managers to clarify data use and user-facing implications
- Coordinate security reviews and risk escalations with Project Managers
- Liaise with Security/on-call or governance functions according to the applicable incident and review processes

---

## Operations / Site Reliability Engineering (SRE)

### Role Summary
Operations/SRE roles help ensure services can be deployed, monitored, supported, and recovered reliably.

### Responsibilities
- Define or advise on operational readiness, monitoring, alerting, and runbooks
- Assess reliability, capacity, and support needs
- Plan deployment, rollback, and recovery considerations with delivery teams
- Share production feedback and operational risks with the project

### Decision Authority
Own operational guidance and readiness recommendations within the team’s service ownership model; escalate material reliability or production risks to the designated operational decision-maker.

### How They Work with Existing Roles
- Partner with Developers and Technical Leads to build operability and observability into solutions
- Coordinate release readiness and deployment dependencies with Project Managers
- Work with Product Managers to communicate reliability trade-offs affecting outcomes
- Align with QA/Quality Leads on environments and post-deployment verification

---

## Business Sponsors / Stakeholder Representatives

### Role Summary
A Business Sponsor provides strategic direction, sponsorship, and timely decisions on business outcomes, priority, and resources. Stakeholder Representatives provide the needs and feedback of the groups they represent.

### Responsibilities
- Confirm strategic alignment and expected business outcomes
- Make or obtain timely decisions on priority, scope, and major trade-offs within their authority
- Help secure appropriate sponsorship, resources, and stakeholder participation
- Communicate impacts, concerns, and adoption needs from represented groups

### Decision Authority
The Sponsor owns decisions explicitly delegated to the sponsor, such as strategic direction or funding; Product Managers retain day-to-day product prioritization unless authority is otherwise agreed. Representatives advise and communicate stakeholder needs but do not assume sponsor approval authority by default.

### How They Work with Existing Roles
- Align with Product Managers on outcomes, priorities, and significant product trade-offs
- Work with Project Managers on governance, escalations, decisions, and stakeholder updates
- Provide Developers and Technical Leads with timely business context through the product and project leads
- Engage QA/Quality, UX/Design, Security/Privacy, and Operations/SRE roles when decisions affect their domain

---

## Applying These Personas

- Assign roles according to project size, complexity, and risk. On smaller projects, one person may cover multiple roles, but document who owns each responsibility and decision.
- Involve specialist roles when the work has relevant design, quality, technical, security, privacy, or operational needs; not every project requires a dedicated person for every role.
- Clarify decision authority and escalation paths at kickoff, especially where roles overlap or a decision has material scope, risk, or release impact.
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise. Each persona can also be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
