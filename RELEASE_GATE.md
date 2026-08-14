# Candidate Release Gate

Release train: Aurora 7.4
Assurance owner: Release Engineering

The managed table below is the approval summary for this candidate. The surrounding release notes are maintained by the release team and must remain byte-for-byte unchanged.

<!-- BEGIN VERIFIED RELEASE GATES -->
| Check key | Result | Evidence |
| --- | --- | --- |
| artifact-signing | PASS | observed=signed |
| canary-health | PASS | observed=healthy |
| schema-compatibility | WAIVED | waiver=RISK-284 |
<!-- END VERIFIED RELEASE GATES -->

## Deployment notes

- Production promotion remains a separate human approval.
- Rollback artifacts must stay available through the observation window.
- Any new blocking evidence invalidates this summary.
