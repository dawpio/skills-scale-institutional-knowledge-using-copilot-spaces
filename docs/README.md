# OctoAcme Project Management Processes

OctoAcme uses a lightweight, end-to-end project lifecycle to keep delivery iterative and outcomes measurable. Work moves through five phases: Initiation (clarify problem, goals, metrics, stakeholders, and initial risks), Planning (build a prioritized backlog with estimates and acceptance criteria), Execution (ship in small increments with visible tracking), Release (deploy with verification and rollback readiness), and Close & Retrospective (capture learnings and turn them into follow-up actions). Core artifacts such as the project one-pager, backlog, risk register, release notes, and retrospective action items act as the shared source of truth.

Roles and personas are intentionally clear so accountability stays explicit while collaboration remains cross-functional. Project Managers coordinate delivery cadence, dependencies, risk management, and stakeholder communication. Product Managers define outcomes, prioritize roadmap and backlog items, and track business impact. Developers design and implement features, contribute to estimation, and maintain test and documentation quality, while QA/testing validates acceptance criteria and release readiness with stakeholders providing direction, approvals, and feedback.

Communication follows a predictable cadence with clear escalation paths. Teams run regular standups, weekly delivery and PM/PdM syncs, and sprint or milestone demos to keep progress and blockers transparent. Stakeholders receive routine status updates and rely on a single project status source (such as a README or release document). When blockers or incidents emerge, escalation progresses from team triage to PM and product coordination, then to sponsor-level support for business-critical impact, with urgent handling for security events.

Quality assurance is embedded throughout delivery rather than deferred to the end. Execution emphasizes small, reviewable pull requests linked to issues and acceptance criteria, automated CI checks for tests and linting, required approvals, and security scans. Testing combines unit, integration, and critical-flow smoke coverage, with manual QA where needed for feature acceptance. Release quality is reinforced by pre-release checks, staging and production verification, stakeholder release communication, and retrospectives that convert lessons learned into tracked continuous improvement work.

## When to use this index
- Start here when onboarding to OctoAcme delivery practices.
- Use this page to move between lifecycle phases, role guidance, and reusable templates/checklists.
- Keep this file updated whenever a process document is added or renamed under `docs/`.

## Process documentation map

### Lifecycle docs (run in order)
1. [Project Management Overview](./octoacme-project-management-overview.md)
2. [Project Initiation Guide](./octoacme-project-initiation.md)
3. [Project Planning](./octoacme-project-planning.md)
4. [Execution & Tracking](./octoacme-execution-and-tracking.md)
5. [Release & Deployment Guide](./octoacme-release-and-deployment.md)
6. [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)

### Cross-cutting docs
- [Risk Management & Communication](./octoacme-risks-and-communication.md)
- [Roles and Personas](./octoacme-roles-and-personas.md)
- [Templates & Checklists Pack](./octoacme-project-management-templates.md)

## Role accountability quick view
- **Project Manager (PM):** delivery cadence, dependency/risk management, escalation ownership.
- **Product Manager (PdM):** outcome definition, prioritization, acceptance criteria quality.
- **Delivery Team (Engineering + QA):** implementation quality, verification, release readiness.
- **Stakeholders/Sponsor:** alignment, decisions, and business-priority confirmation.
- **Extended roles (UX, Tech Writer, Support, Security, Data):** domain accountability and handoff quality.
