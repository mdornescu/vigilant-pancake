# OctoAcme Project Management Guide

Welcome to OctoAcme! This guide provides an overview of how we run projects, our key processes, and the roles involved. Whether you're a new team member or need a quick refresher, this document will help you understand our approach to delivering customer value through iterative, well-coordinated teamwork.

## Our Approach and Key Workflows

OctoAcme follows a structured project lifecycle that emphasizes customer-first thinking, iterative delivery, and clear ownership. Every project moves through five phases:

- [**Initiation**](octoacme-project-initiation.md): Validate the problem and create a project one-pager with success metrics
- [**Planning**](octoacme-project-planning.md): Break work into actionable increments with clear acceptance criteria
- [**Execution**](octoacme-execution-and-tracking.md): Daily standups, weekly syncs, and continuous progress tracking via project boards
- [**Release**](octoacme-release-and-deployment.md): Deploy with proper smoke tests and rollback plans
- [**Retrospective**](octoacme-retrospective-and-continuous-improvement.md): Capture learnings and actionable improvements

Our execution model uses GitHub Projects with standard workflow columns (Backlog → Ready → In Progress → In Review → QA → Done) and emphasizes:

- Small pull requests (<= 400 lines when possible)
- Automated testing and linting in CI
- At least one approval before merging

Quality assurance is embedded throughout the development process:

- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows
- Security scanning in CI
- Manual QA for feature acceptance

We measure success through velocity, burndown charts, and the success metrics defined in each project's one-pager.

## Roles, Personas, and Team Rhythms

Our cross-functional teams include clearly defined [**roles**](octoacme-roles-and-personas.md):

- **Project Managers (PM)**: Coordinate delivery, manage schedules and risks, and maintain project documentation
- **Product Managers (PdM)**: Define what to build, prioritize the backlog, and measure outcomes
- **Developers**: Implement features, write tests, and participate in code reviews
- **QA Engineers**: Design test strategies, validate quality, and ensure acceptance criteria are met
- **UX Designers**: Create user-centered designs through research, prototyping, and usability testing
- **DevOps Engineers**: Build and maintain infrastructure, CI/CD pipelines, and deployment automation
- **Business Analysts**: Gather requirements, analyze processes, and bridge business and technical teams
- **Customer Support Lead**: Manage support team, gather customer feedback, and ensure support readiness for releases
- **Stakeholders**: Provide inputs and approvals

For detailed role descriptions and how these personas interact, see [Roles & Personas](octoacme-roles-and-personas.md).

To ensure smooth cross-functional collaboration, we provide [reusable checklists](octoacme-cross-functional-checklist.md) for handoffs and release readiness.

Communication follows predictable cadences to keep everyone aligned:

- **Daily standups**: 15 minutes, focusing on progress and blockers
- **Twice-weekly delivery team syncs**: Show progress, updates, and flagged risks
- **Weekly PM + PdM alignment**: Coordinate on priorities and roadmap
- **Monthly stakeholder updates**: Keep leadership informed of progress
- **Demo/review sessions**: End of each sprint or milestone

Each project maintains a single source of truth in its project README or release doc. Weekly status updates follow a standard template covering progress, next steps, risks/blockers, and decisions needed.

## Communication and Stakeholder Engagement

Effective [**communication and risk management**](octoacme-risks-and-communication.md) are critical to our success. We identify stakeholder groups early (engineering, sales, support, etc.) and tailor communication to their needs, providing regular updates at weekly or milestone-based intervals.

Our risk management approach involves maintaining a risk register that tracks ID, description, impact, likelihood, owner, mitigation plan, and status. Risks are identified during planning and ongoing execution, assessed for impact and likelihood, mitigated through actions and contingency plans, and monitored at weekly syncs.

Escalation paths are clear: team-level triage occurs in daily standups, the PM escalates to the Product Lead and dependent teams as needed, and sponsor-level escalation handles business-impacting issues. For incidents, we follow a structured communication approach including triage summary, actions being taken, expected timeline, and scheduling a blameless post-incident retrospective.

## Getting Started and Continuous Improvement

For more details on any aspect of our process, explore the complete documentation set:

- [Project Management Overview](octoacme-project-management-overview.md) — Principles and high-level lifecycle
- [Project Initiation](octoacme-project-initiation.md) — How we validate and start new work
- [Project Planning](octoacme-project-planning.md) — Turning ideas into actionable backlogs
- [Execution & Tracking](octoacme-execution-and-tracking.md) — Day-to-day workflows and quality practices
- [Release & Deployment](octoacme-release-and-deployment.md) — Standardized release processes
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — Learning and iteration
- [Roles & Personas](octoacme-roles-and-personas.md) — Detailed role descriptions
- [Risk Management & Communication](octoacme-risks-and-communication.md) — Stakeholder engagement strategies
- [Cross-Functional Checklists](octoacme-cross-functional-checklist.md) — Handoff and release readiness templates

We believe in psychological safety, data-informed decisions, and continuous improvement. After each sprint, release, or milestone, we run retrospectives to capture what went well, what could be improved, and 2-3 top action items with clear owners and timelines. These improvements are tracked in our backlog and reviewed in weekly PM syncs, creating a culture of measurable, iterative enhancement.
