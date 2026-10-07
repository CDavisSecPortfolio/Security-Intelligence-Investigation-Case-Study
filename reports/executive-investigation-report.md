# Executive Investigation Report

**Classification: SIMULATED / PORTFOLIO USE ONLY**  
**Case:** ND-2026-017 — Suspected Insider Threat / Unauthorized Data Transfer

## Allegation
Security monitoring identified anomalous activity associated with Employee E-1047, an engineer authorized to access confidential design information. The activity included after-hours repository access, bulk file retrieval, removable-media interaction, and transfer to an unsanctioned cloud service.

## Objective
Establish facts, preserve evidence, assess whether activity was authorized, determine potential exposure of confidential information, and provide defensible recommendations.

## Scope
Simulated DLP alerts, authentication records, file-access events, endpoint/removable-media events, cloud-transfer telemetry, manager-provided context, and fictional OSINT artifacts.

## Method
1. Preserve evidence before disruptive changes when feasible.
2. Separate observed facts from inference.
3. Correlate independent sources before raising confidence.
4. Consider legitimate alternative explanations.
5. Escalate proportionally with Legal, HR, Security, and technical forensics.

## Findings
### F1 — Anomalous after-hours access — Substantiated
E-1047 authenticated outside the established work pattern and accessed a confidential engineering repository.

### F2 — Bulk access to confidential files — Substantiated
Simulated telemetry shows 186 confidential engineering files accessed within a compressed time window, materially above the fictional baseline.

### F3 — Removable-media activity — Substantiated
Endpoint telemetry records an approved corporate endpoint interacting with a removable-storage device during the investigative window. This indicator is significant but does not alone prove exfiltration.

### F4 — Unsanctioned cloud transfer — Substantiated
DLP telemetry identifies a 1.8 GB outbound transfer containing files labeled Confidential to a non-corporate cloud-storage destination.

### F5 — Business justification — Not established
The fictional manager context did not identify a project requirement supporting the bulk transfer to a personal cloud destination.

### F6 — Criminal intent / competitor receipt — Not established
The evidence supports unauthorized transfer and policy violation. It does **not** by itself prove criminal intent, sale of information, or receipt by a competitor.

## Assessment
**Severity:** High  
**Confidence:** High for unauthorized transfer; Low/Moderate for motive  
**Potential impact:** Loss of confidentiality, intellectual-property exposure, legal/regulatory consequences, competitive harm, and reputational risk.

## Immediate Recommendations
- Preserve endpoint, identity, DLP, file-access, cloud, and relevant communication records under approved retention/legal processes.
- Coordinate investigative actions with Legal and HR before interviewing the employee or changing employment status.
- Engage technical forensics to validate file hashes, endpoint artifacts, removable-media activity, and transfer scope.
- Apply risk-based access restrictions through authorized processes while preserving evidence.
- Identify the affected information owner and determine sensitivity/business impact.
- Document all investigative decisions, evidence transfers, and access.

## Long-Term Recommendations
- Strengthen DLP policies for personal cloud storage and bulk transfers.
- Apply least privilege and periodic entitlement review to sensitive repositories.
- Improve behavioral baselining for unusual file-access volume and after-hours activity.
- Establish removable-media controls based on business need.
- Integrate identity, endpoint, DLP, cloud, and HR-approved contextual signals into insider-risk workflows.
- Conduct recurring awareness training on confidential information and approved transfer methods.

## Investigative Limitation
This exercise uses fabricated evidence and does not perform attribution to a real individual. Conclusions are intentionally limited to what the simulated evidence supports.

## Leadership Conclusion
The evidence warrants a coordinated high-priority insider-risk response and technical forensic review. Leadership should treat the confidentiality exposure as substantiated while avoiding unsupported conclusions regarding motive or criminal conduct.
