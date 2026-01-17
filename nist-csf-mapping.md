# NIST CSF Mapping (ISO 27001 + SOC 2)

This mapping links ISO 27001 Annex A and SOC 2 Trust Services Criteria to NIST CSF Functions and Categories.

## Summary
- Functions covered: Identify, Protect, Detect, Respond, Recover
- Source frameworks: ISO 27001:2022 Annex A, SOC 2 (Security, Availability, Confidentiality)

## Mapping Table
| Control ID | Control Name | Standard | NIST CSF Function | NIST CSF Category | Subcategory | Notes |
|---|---|---|---|---|---|---|
| A.5.1 | Policies for information security | ISO 27001 | Identify | ID.GV | ID.GV-1 | Policy framework documented and approved |
| CC1.1 | Integrity & ethical values | SOC 2 | Identify | ID.GV | ID.GV-2 | Governance and culture |
| A.5.9 | Inventory of information and other assets | ISO 27001 | Identify | ID.AM | ID.AM-1 | Asset inventory maintained |
| CC2.2 | Communication of security objectives | SOC 2 | Identify | ID.GV | ID.GV-3 | Security responsibilities communicated |
| A.5.15 | Access control | ISO 27001 | Protect | PR.AC | PR.AC-1 | Logical access controls enforced |
| CC6.1 | Logical access security | SOC 2 | Protect | PR.AC | PR.AC-3 | MFA and least privilege |
| A.5.30 | ICT readiness for business continuity | ISO 27001 | Protect | PR.IP | PR.IP-9 | Resilience planning |
| CC6.7 | Data transmission security | SOC 2 | Protect | PR.DS | PR.DS-2 | Encryption in transit |
| A.5.7 | Threat intelligence | ISO 27001 | Detect | DE.CM | DE.CM-1 | Continuous monitoring inputs |
| CC7.2 | Security monitoring | SOC 2 | Detect | DE.CM | DE.CM-7 | Logs reviewed and alerts configured |
| A.5.25 | Information security event reporting | ISO 27001 | Respond | RS.CO | RS.CO-2 | Incident reporting procedures |
| CC7.4 | Incident response | SOC 2 | Respond | RS.MI | RS.MI-1 | Response plans tested |
| A.5.29 | ICT readiness for recovery | ISO 27001 | Recover | RC.RP | RC.RP-1 | Recovery plans maintained |
| CC4.1 | Business continuity | SOC 2 | Recover | RC.RP | RC.RP-2 | Continuity strategy documented |