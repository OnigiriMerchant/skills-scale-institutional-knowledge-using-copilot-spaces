# Release Checklist

Owner: Release Manager (assigned per release)

Pre-release (before deploying to staging)
- [ ] Confirm all PRs merged that are part of the release and have required approvals
- [ ] CI passing and security scans green
- [ ] Smoke tests defined and automated where possible
- [ ] Rollback plan documented and tested at a high level
- [ ] Stakeholders notified of planned window and impact
- [ ] Documentation and release notes drafted and linked
- [ ] Measurement owner confirms instrumentation and dashboards are ready
- [ ] SRE has validated capacity, SLIs/SLOs, and monitoring for the release

Staging validation
- [ ] Deploy to staging and run smoke tests
- [ ] Run manual QA for critical flows if relevant
- [ ] Verify logs, metrics, and alerts are firing as expected
- [ ] Confirm rollback procedure can be executed

Production deployment
- [ ] Schedule deploy in calendar (owner: Release Manager)
- [ ] Run the deployment and monitor health checks
- [ ] Verify post-deploy smoke tests
- [ ] Communicate successful deployment to stakeholders

Post-release
- [ ] Validate metrics and dashboards for expected signals
- [ ] Monitor for regressions and incidents for defined window
- [ ] Run a short post-release review and capture action items
- [ ] Update runbooks or docs based on findings
