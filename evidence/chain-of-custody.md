# Simulated Chain of Custody Log

**Case:** ND-2026-017  
**Purpose:** Demonstrate evidence accountability and integrity. No real evidence is represented.

| Evidence ID | Item | Source | Collected | Integrity / Handling | Custodian |
|---|---|---|---|---|---|
| EV-001 | Identity authentication export | Identity platform | 2026-09-15 09:12 CT | Export preserved read-only; SHA-256 recorded in case system | Investigator A |
| EV-002 | File-access audit export | File repository | 2026-09-15 09:18 CT | Original export preserved; working copy separated | Investigator A |
| EV-003 | DLP alert package | DLP platform | 2026-09-15 09:24 CT | Alert metadata and policy result preserved | Investigator A |
| EV-004 | Endpoint forensic image | ND-LT-447 | 2026-09-15 13:45 CT | Forensic image acquired; hash verified before analysis | Forensic Analyst B |
| EV-005 | Manager context memo | HR-approved context | 2026-09-15 14:20 CT | Signed case note; access restricted | Investigator A |

## Handling Rules
- Record every transfer of custody.
- Preserve originals and analyze verified copies when appropriate.
- Restrict evidence access to personnel with a legitimate investigative need.
- Document acquisition method, timestamps, integrity checks, and disposition.
- Coordinate retention and legal-hold requirements with authorized Legal personnel.
