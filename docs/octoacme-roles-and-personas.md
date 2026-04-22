# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

## When to use
- During initiation and planning to assign clear ownership for outcomes and decisions.
- During execution/release when escalation or handoff accountability is unclear.
- During onboarding to align new contributors on who does what and how roles collaborate.

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

## QA / Test Leads

### Role Summary
QA / Test Leads define and coordinate quality strategy so increments meet acceptance criteria and release standards.

### Responsibilities
- Define test strategy for features, integrations, and critical flows
- Align test plans with acceptance criteria and Definition of Done
- Track quality risks and coordinate remediation with delivery team
- Validate release readiness and sign off on test evidence

### Goals
- Prevent regressions and reduce escaped defects
- Make quality status visible before release decisions
- Improve confidence in each deployment

### Typical Communication
- Test plan and coverage updates in sprint ceremonies
- Release-readiness summaries with Product and PM
- Defect triage notes and quality risk escalations

---

## UX Designers

### Role Summary
UX Designers ensure solutions are usable, accessible, and aligned to customer needs.

### Responsibilities
- Define interaction patterns and user flows
- Validate assumptions with lightweight research/testing
- Provide design artifacts and acceptance details for implementation
- Partner with Product and Engineering on trade-offs

### Goals
- Reduce rework caused by unclear or unvalidated user experience
- Improve adoption and task completion for target users

### Typical Communication
- Design reviews with Product and Engineering
- Accessibility/usability findings shared during planning and demos

---

## Technical Writers

### Role Summary
Technical Writers keep user and operational documentation accurate and usable as the product evolves.

### Responsibilities
- Draft and maintain release notes and user guidance
- Document operational runbooks and known limitations
- Coordinate documentation updates with feature and release cycles

### Goals
- Ensure stakeholders and users can adopt changes without confusion
- Keep support-facing information current and discoverable

### Typical Communication
- Documentation change logs linked to pull requests
- Release-note reviews with Product, Support, and PM

---

## Support Engineers

### Role Summary
Support Engineers represent user-reported pain points and operational feedback in planning and release activities.

### Responsibilities
- Surface recurring customer issues and urgency signals
- Contribute troubleshooting and known-issue updates
- Validate release communications from a support-readiness perspective

### Goals
- Reduce resolution time and repeat incidents
- Improve prioritization using real-world user impact data

### Typical Communication
- Incident and escalation updates with PM/Product
- Support readiness input during release planning

---

## Security & Compliance Partners

### Role Summary
Security/Compliance partners ensure project decisions and releases meet required risk, privacy, and policy controls.

### Responsibilities
- Review high-risk changes and threat considerations
- Define required security controls and sign-off criteria
- Participate in security incident escalation and post-incident follow-up

### Goals
- Reduce security risk introduced by delivery changes
- Ensure compliance obligations are met on time

### Typical Communication
- Security review outcomes in planning/release checkpoints
- Incident response coordination with PM and Engineering

---

## Data / Analytics Partners

### Role Summary
Data/Analytics partners instrument outcomes so teams can validate impact and improve prioritization.

### Responsibilities
- Define metrics collection approach for success criteria
- Validate data quality for dashboards and reporting
- Support experiment analysis and retrospective insights

### Goals
- Improve confidence in product and process decisions
- Shorten feedback loops through trustworthy measurement

### Typical Communication
- KPI reviews with Product and PM
- Measurement updates in demos and retrospectives

---

## Role interaction model (who works with whom)
- **PM ↔ Product Manager:** priority, scope, risks, and stakeholder alignment.
- **Product Manager ↔ UX / Data:** clarify user needs, success metrics, and expected outcomes.
- **Engineering ↔ QA / Security:** implementation quality, threat controls, and release readiness.
- **PM ↔ Support / Technical Writer:** readiness communications, incident patterns, and customer-facing updates.
- **Sponsor/Stakeholders ↔ PM + Product:** go/no-go decisions, trade-offs, and escalation support.

## Accountability checkpoints (RACI-lite)
- **Initiation one-pager:** Responsible: Product Manager, Accountable: Sponsor, Consulted: PM/Engineering/UX, Informed: stakeholders.
- **Plan and backlog readiness:** Responsible: Delivery team + QA, Accountable: PM, Consulted: Product Manager, Informed: stakeholders.
- **Release go/no-go:** Responsible: Engineering + QA, Accountable: Product Manager, Consulted: PM/Support/Security, Informed: sponsor.
- **Retrospective follow-through:** Responsible: action owner, Accountable: PM, Consulted: Product/Engineering/QA, Informed: stakeholders.

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

## Related docs
- [Project Management Overview](./octoacme-project-management-overview.md)
- [Risk Management & Communication](./octoacme-risks-and-communication.md)
- [Templates & Checklists Pack](./octoacme-project-management-templates.md)
