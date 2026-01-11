# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans
- Release notes drafted
- Rollback / mitigation plan documented
- Smoke tests prepared
- **Cross-functional sign-offs obtained** (QA, UX, DevOps, Product Manager)
- **Support team trained and ready**
- **Customer communication plan finalized**

## Deployment Checklist
- [ ] Deployment window scheduled (if needed)
- [ ] Backup or snapshot (if applicable)
- [ ] Deploy to staging and run smoke tests
- [ ] Deploy to production (automated pipeline preferred)
- [ ] Run post-deploy verifications
- [ ] Announce release to stakeholders and support
- [ ] **Support team notified with release notes and known issues**
- [ ] **Customer communication sent (if customer-facing changes)**
- [ ] **Monitoring dashboards reviewed with DevOps**
- [ ] **Support escalation procedures updated**

### Cross-Functional Release Coordination

For successful releases, coordinate with all relevant roles:

#### DevOps Coordination
- DevOps Engineer executes or oversees deployment automation
- Infrastructure changes applied and validated in staging first
- Monitoring alerts configured before production deployment
- Rollback procedure reviewed and ready to execute if needed
- Post-deployment health checks automated and monitored
- Deployment communication channels open (Slack, Teams, etc.)

#### Support Team Handoff
- Customer Support Lead ensures team is trained on new features
- Support documentation published to knowledge base
- Known issues and workarounds documented and accessible
- Support team has access to logs and monitoring for troubleshooting
- Escalation path to engineering clearly defined
- First 24-48 hours: engineering and support coordinate closely on any issues

#### Customer Communication
- Product Manager and Customer Support Lead coordinate on customer-facing announcements
- Communication tailored to customer segments (all users, specific plans, beta users, etc.)
- Timing aligned with deployment to avoid confusion
- Feedback channels monitored actively post-release

#### Quality Validation
- QA Engineer verifies smoke tests pass in production
- Critical user flows tested post-deployment
- Performance metrics compared to baseline
- Any discrepancies immediately escalated

For a complete release readiness assessment, use the [Release Readiness Checklist](octoacme-cross-functional-checklist.md#release-readiness-checklist).

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call
  - Rollback to last known-good release if necessary
  - Triage root cause and capture action items

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
