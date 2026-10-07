# Incident & Evidence Timeline

> All timestamps and events are fictional.

| Time (CT) | Source | Event | Investigative Significance |
|---|---|---|---|
| 2026-09-14 21:48 | Identity | E-1047 authenticates from corporate endpoint ND-LT-447 after normal work hours | Baseline deviation; requires context |
| 2026-09-14 21:55 | File Audit | Confidential engineering repository accessed | Sensitive-data access begins |
| 2026-09-14 22:02 | File Audit | Rapid sequence of design-file reads begins | Potential bulk collection |
| 2026-09-14 22:17 | Endpoint | USB storage device mounted | Possible staging/transfer vector |
| 2026-09-14 22:23 | DLP | Bulk access threshold triggered at 186 files | Corroborates anomalous volume |
| 2026-09-14 22:31 | Endpoint | Archive file `design_review_2026.zip` created | Possible staging indicator |
| 2026-09-14 22:36 | Cloud/DLP | 1.8 GB upload to unsanctioned personal cloud destination | Strong data-loss indicator |
| 2026-09-14 22:37 | DLP | Confidential-data policy alert generated | Security control detects transfer |
| 2026-09-15 08:20 | Manager Context | No known project requirement for personal cloud transfer | Legitimate explanation not established |
| 2026-09-15 09:05 | Security | Investigation ND-2026-017 opened; preservation initiated | Formal investigative response |
| 2026-09-15 10:10 | Security/Legal | Escalation for coordinated review | Cross-functional governance |
| 2026-09-15 11:30 | Forensics | Endpoint image/hash preservation requested | Protects technical evidence integrity |

## Correlation Assessment
The sequence is more significant than any single event. After-hours access, unusual volume, archive creation, removable-media interaction, and an unsanctioned cloud upload occur within one session and are corroborated by independent simulated telemetry sources.
