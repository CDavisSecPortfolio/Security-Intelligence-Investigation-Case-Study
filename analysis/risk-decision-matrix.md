# Investigation Risk & Decision Matrix

| Indicator | Evidence Strength | Potential Impact | Confidence | Decision |
|---|---|---|---|---|
| After-hours access | Medium | Medium | High | Correlate with baseline/business need |
| Bulk confidential-file access | High | High | High | Investigate scope and authorization |
| Removable-media mount | Medium | High | High event confidence; low transfer confidence | Preserve endpoint evidence |
| Archive creation | High | High | High | Examine contents, timestamps, hashes |
| Unsanctioned 1.8 GB cloud upload | Very High | Critical | High | Immediate coordinated escalation |
| No known business justification | Medium | High | Moderate | Validate with manager/HR/Legal |
| Public career-transition context | Low/Medium | Medium | Moderate | Context only; do not infer motive |

## Decision Threshold
Multiple independent indicators raise the case to **High Priority** because a confirmed outbound transfer of confidential information is combined with anomalous access and staging behavior.

## Alternative Hypotheses
- Legitimate remote work performed through an unapproved method.
- Accidental synchronization or user error.
- Shared/compromised credentials.
- Approved work activity not known to the manager interviewed.
- Deliberate unauthorized transfer.

Each hypothesis should be tested against technical evidence and authorized human-source information rather than assumed.
