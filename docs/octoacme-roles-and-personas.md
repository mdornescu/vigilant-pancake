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

### Interactions with Other Roles
- **Product Managers**: Clarify requirements and acceptance criteria; provide technical feasibility input and effort estimates
- **Project Managers**: Report progress and blockers; coordinate dependencies and timelines
- **QA Engineers**: Collaborate on testability and bug fixes; discuss edge cases during design reviews
- **UX Designers**: Implement designs with high fidelity; provide feedback on technical constraints and feasibility
- **DevOps Engineers**: Work on CI/CD improvements, containerization, and deployment automation
- **Business Analysts**: Seek clarification on business logic and edge cases; validate technical solutions meet business requirements
- **Customer Support Lead**: Investigate and fix customer-reported bugs; provide technical context for support documentation

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

### Interactions with Other Roles
- **Project Managers**: Align on roadmap priorities, timelines, and resource allocation; coordinate stakeholder communication
- **Developers**: Define clear acceptance criteria and success metrics; make trade-off decisions on scope and feasibility
- **QA Engineers**: Review test plans to ensure coverage of critical user flows; validate quality bar for releases
- **UX Designers**: Collaborate on feature definition and user research; validate design solutions meet customer needs
- **DevOps Engineers**: Discuss infrastructure requirements and cost implications; align on performance and scalability goals
- **Business Analysts**: Work together on requirements analysis and business value validation; prioritize based on business impact
- **Customer Support Lead**: Review customer feedback and feature requests; prioritize bug fixes and user experience improvements

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

### Interactions with Other Roles
- **Product Managers**: Coordinate on timelines, dependencies, and resource planning; escalate risks and blockers
- **Developers**: Track delivery progress and remove blockers; facilitate sprint planning and retrospectives
- **QA Engineers**: Coordinate testing schedules and quality gates; ensure testing is integrated into project timelines
- **UX Designers**: Track design deliverables and dependencies; ensure design reviews happen at appropriate project phases
- **DevOps Engineers**: Coordinate infrastructure timelines and deployment schedules; manage deployment windows and releases
- **Business Analysts**: Ensure requirements are documented and reviewed; track UAT and business validation activities
- **Customer Support Lead**: Coordinate release communications and support readiness; manage change impact to customers

---

## QA Engineers

### Role Summary
QA Engineers ensure software quality by designing test strategies, executing test plans, and validating that features meet acceptance criteria and quality standards before release.

### Responsibilities
- Create comprehensive test plans and test cases for new features
- Execute manual and automated testing across functional, integration, and end-to-end scenarios
- Identify, document, and track bugs through resolution
- Collaborate with Developers on testability and edge cases
- Validate acceptance criteria are met before sign-off
- Maintain test automation suites and contribute to CI/CD quality gates

### Goals
- Deliver high-quality, defect-free releases to production
- Reduce escape rate (bugs found in production)
- Improve test coverage and automation efficiency
- Ensure smooth user experience through comprehensive testing

### Typical Communication
- Daily standups to report testing progress and blockers
- Test plan reviews with Product Managers and Developers
- Bug triage meetings and status updates
- Sign-off documentation for release readiness

### Interactions with Other Roles
- **Product Managers**: Review acceptance criteria and feature specs to create test plans; validate user flows match expected behavior
- **Project Managers**: Report testing progress, flag quality risks, and coordinate testing timelines within release schedules
- **Developers**: Collaborate on bug fixes, provide reproducible steps, discuss testability during design reviews
- **UX Designers**: Test user flows and UI/UX consistency; provide feedback on usability issues discovered during testing
- **DevOps Engineers**: Coordinate on test environment setup and CI/CD integration for automated tests
- **Customer Support Lead**: Share insights on customer-reported issues to prioritize regression testing areas

---

## UX Designers

### Role Summary
UX Designers create user-centered designs that balance customer needs, business goals, and technical feasibility. They conduct user research, design interfaces, and validate solutions through prototyping and usability testing.

### Responsibilities
- Conduct user research to understand customer needs, pain points, and behaviors
- Create wireframes, mockups, and interactive prototypes
- Design intuitive user interfaces and experiences that meet accessibility standards
- Collaborate with Product Managers on feature requirements and user flows
- Conduct usability testing and iterate based on feedback
- Maintain design systems and component libraries
- Partner with Developers to ensure design implementation fidelity

### Goals
- Deliver intuitive, accessible, and delightful user experiences
- Validate design decisions through user research and testing
- Reduce user friction and improve task completion rates
- Maintain design consistency across the product

### Typical Communication
- Design reviews with Product Managers and stakeholders
- Handoff sessions with Developers including design specs and assets
- User research readouts and usability testing reports
- Weekly syncs with cross-functional team members

### Interactions with Other Roles
- **Product Managers**: Collaborate on feature definition, validate user needs through research, align on success metrics and user outcomes
- **Project Managers**: Communicate design timeline and dependencies; flag design risks that may impact delivery schedules
- **Developers**: Provide detailed design specifications, assets, and implementation guidance; review UI implementation for fidelity
- **QA Engineers**: Share expected user flows and edge cases; review QA feedback on usability and accessibility issues
- **Business Analysts**: Review user journey maps and process flows to ensure alignment with business requirements
- **Customer Support Lead**: Gather insights on user pain points and common support issues to inform design improvements

---

## DevOps Engineers

### Role Summary
DevOps Engineers build and maintain infrastructure, CI/CD pipelines, and deployment automation. They enable reliable, secure, and efficient software delivery while ensuring system observability and performance.

### Responsibilities
- Design, implement, and maintain CI/CD pipelines for automated builds, tests, and deployments
- Manage cloud infrastructure, containerization, and orchestration platforms
- Implement monitoring, logging, and alerting systems for production observability
- Ensure security best practices in infrastructure and deployment processes
- Automate infrastructure provisioning and configuration management
- Optimize system performance, scalability, and cost efficiency
- Support incident response and root cause analysis for infrastructure issues

### Goals
- Achieve reliable, fast, and automated deployments with minimal manual intervention
- Maintain high system availability and performance
- Reduce deployment risk through automation and testing
- Ensure infrastructure security and compliance

### Typical Communication
- Infrastructure design reviews with Developers and Project Managers
- Deployment coordination during release windows
- Incident response communications and postmortems
- Infrastructure planning meetings for capacity and scaling

### Interactions with Other Roles
- **Product Managers**: Understand feature requirements that impact infrastructure needs; provide feedback on technical feasibility and costs
- **Project Managers**: Communicate infrastructure timelines, dependencies, and deployment schedules; flag infrastructure risks early
- **Developers**: Collaborate on CI/CD pipeline improvements, containerization strategies, and deployment automation; support local development environments
- **QA Engineers**: Provide test environments and coordinate test data management; integrate automated tests into CI/CD pipelines
- **Business Analysts**: Align on compliance, security, and operational requirements for infrastructure planning
- **Customer Support Lead**: Provide observability tools and access for troubleshooting production issues; communicate during incident response

---

## Business Analysts

### Role Summary
Business Analysts bridge the gap between business stakeholders and technical teams. They gather requirements, analyze business processes, and ensure solutions align with business objectives and user needs.

### Responsibilities
- Gather and document business requirements from stakeholders
- Analyze current business processes and identify improvement opportunities
- Create process flows, user stories, and functional specifications
- Facilitate requirements workshops and stakeholder interviews
- Validate that delivered solutions meet business objectives
- Perform gap analysis and impact assessment for changes
- Support user acceptance testing (UAT) and business validation

### Goals
- Ensure solutions deliver measurable business value
- Bridge communication between business and technical teams
- Reduce rework through clear, complete requirements
- Validate business processes are optimized and efficient

### Typical Communication
- Requirements gathering sessions with stakeholders
- Business process documentation and workflow diagrams
- User acceptance criteria and test scenarios
- Regular status updates on requirements and validation progress

### Interactions with Other Roles
- **Product Managers**: Collaborate on roadmap priorities and feature definitions; provide business context and requirements analysis
- **Project Managers**: Support project planning with detailed requirements; flag business risks and dependencies
- **Developers**: Translate business requirements into technical specifications; clarify business logic and edge cases
- **QA Engineers**: Define business validation criteria and support UAT planning; review test scenarios for business accuracy
- **UX Designers**: Provide business process context for user flows; validate designs meet business requirements
- **Customer Support Lead**: Gather customer feedback and support trends to inform requirements; coordinate on change management and user communication

---

## Customer Support Lead

### Role Summary
Customer Support Lead manages the support team and ensures customers receive timely, effective assistance. They bridge customer feedback to product teams and prepare support teams for new releases.

### Responsibilities
- Lead and coach customer support team members
- Triage and resolve escalated customer issues
- Gather, analyze, and communicate customer feedback and pain points to product teams
- Create and maintain support documentation, FAQs, and knowledge bases
- Coordinate support readiness for new feature releases
- Monitor support metrics (response time, resolution time, customer satisfaction)
- Identify trends in support tickets to inform product improvements

### Goals
- Deliver excellent customer support experiences
- Reduce customer churn through proactive issue resolution
- Minimize support ticket volume through self-service resources
- Ensure smooth feature launches with prepared support teams

### Typical Communication
- Customer escalation communications and resolution updates
- Support readiness briefings before releases
- Customer feedback reports to Product and Engineering
- Weekly metrics reviews and trend analysis

### Interactions with Other Roles
- **Product Managers**: Share customer insights, feature requests, and pain points; provide feedback on feature usability and adoption
- **Project Managers**: Coordinate on release timelines to ensure support readiness; flag customer impact risks
- **Developers**: Report bugs with detailed customer scenarios; request clarification on feature behavior for support documentation
- **QA Engineers**: Share real-world customer use cases for test coverage; coordinate on reproducing customer-reported issues
- **UX Designers**: Provide feedback on user experience issues discovered through support interactions; suggest UI improvements
- **Business Analysts**: Provide customer data and trends for requirements analysis; validate business processes against customer needs
- **DevOps Engineers**: Coordinate on customer-impacting incidents; request access to logs and monitoring for troubleshooting

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

