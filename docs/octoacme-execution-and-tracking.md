# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups (15 min) — focus on progress, blockers, dependencies
- Weekly delivery sync — show progress, updates, and flagged risks
- Demo/Review at the end of each sprint or milestone

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Pull Request workflow:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Run automated tests and linting in CI before requesting review
  - Require at least one approval before merging (or team-defined policy)

### Cross-Functional Workflow Enhancements

To ensure smooth handoffs and collaboration between roles:

#### Design Review & Handoff
- UX Designer presents designs in review sessions before development starts
- Developers flag technical constraints or feasibility concerns during design review
- Design handoff includes specifications, assets, and walkthrough session
- Final UI implementation reviewed by UX Designer before QA handoff
- Use design review checklist from [Cross-Functional Checklist](octoacme-cross-functional-checklist.md)

#### Requirements Clarity
- Business Analyst documents requirements and business logic before development
- Acceptance criteria must be clear, testable, and reviewed by BA and Product Manager
- Developer questions on business logic routed through BA or Product Manager
- UAT coordinated by BA with business stakeholders

#### Infrastructure & Deployment Coordination
- DevOps Engineer involved early when infrastructure changes are needed
- Deployment runbooks created or updated for each release
- Staging environment maintained by DevOps for pre-production validation
- Monitoring and alerting reviewed before each major release
- DevOps handoff checklist completed before production deployment

#### QA Integration
- QA Engineer involved in planning to define test strategy
- Test environments and test data prepared before development completes
- QA begins testing as soon as features reach "In Review" or dedicated QA column
- Developers collaborate on bug reproduction and fixes
- QA sign-off required before moving to "Done" or "Ready for Release"

#### Support Readiness Integration
- Customer Support Lead notified of upcoming features during planning
- Support documentation drafted as features near completion
- Support training scheduled 1-2 weeks before release
- Known issues and workarounds documented by QA and Developers for support team
- Support handoff checklist completed before release announcement


## Quality & Testing
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI
- Manual QA for feature acceptance when needed

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)

## Blocker Escalation
- Level 1: Team-level triage in daily standup
- Level 2: PM escalates to Product Lead and dependent teams
- Level 3: Sponsor-level escalation for business-impacting issues

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint
- [ ] Regular demos scheduled
- [ ] Risk register updated weekly
- [ ] Cross-functional handoff checkpoints scheduled
- [ ] Design reviews scheduled with UX Designer
- [ ] QA test environments prepared and maintained
- [ ] DevOps monitoring dashboards accessible to team
- [ ] Support documentation tracked alongside feature work
- [ ] Regular cross-role sync meetings held
