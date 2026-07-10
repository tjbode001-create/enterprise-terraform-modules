# Operational Runbook

## Daily Checks

* Review monitoring dashboards
* Validate CI/CD pipeline health
* Check failed deployments
* Review security alerts
* Confirm backup and DR job status
* Review cloud cost anomalies

## Incident Response

1. Identify impacted service
2. Validate recent deployments or configuration changes
3. Check logs, metrics, traces, and events
4. Apply rollback or remediation playbook
5. Document root cause
6. Create preventive action item

## Change Management

All changes should be submitted through pull requests, reviewed by platform owners, scanned by security tools, and deployed through approved pipelines.
