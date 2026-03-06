# GRC-Portfolio
Project — NimbusHR Inc."Not associated with any real company named NimbusHR."
Governance, Risk & Compliance Package | NIST CSF 2.0 Aligned
Prepared by: Donnie V Haynes
Status: In Progress (3-document package)
Frameworks: NIST Cybersecurity Framework 2.0 · ISO 27001 (reference)
Certifications: Google Cybersecurity Certificate ✅ · CompTIA Security+ (March 20th)

Project Overview

This project demonstrates a complete **GRC (Governance, Risk & Compliance) package** for a fictional SaaS company NimbusHR Inc., a cloud-based HR platform processing sensitive employee PII on AWS.

The goal of this project is to replicate the type of documentation a GRC analyst would produce when onboarding a new client or conducting an internal security assessment. All three deliverables were built using real industry frameworks and free, publicly available resources.

> **Why NimbusHR?** A SaaS company handling payroll data and SSNs on AWS represents a realistic, high-risk environment that maps directly to the kinds of clients GRC analysts work with in the real world.
>
> ## 📁 Package Contents

| # | Document | Framework Reference | Status |
|---|----------|-------------------|--------|
| 01 | [Risk Assessment](NimbusHR_Risk_Assessment_3.pdf) | NIST CSF 2.0 — GOVERN, IDENTIFY | ✅ Complete |
| 02 | Risk Register | NIST CSF 2.0 — IDENTIFY (ID.RA) | 🔄 In Progress |
| 03 | Information Security Policy | NIST CSF 2.0 — GOVERN (GV.PO) | 🔄 In Progress |

---

## 🔍 Document 1 — Risk Assessment

**File:** `NimbusHR_Risk_Assessment_3.pdf`

The Risk Assessment answers the question: *"What could go wrong, how likely is it, and how bad would it be?"*

### What's inside:
- **Executive Summary** with color-coded priority recommendations
- **Asset Inventory** of 11 key information assets (AWS infrastructure, web app, credentials, etc.)
- **Threat & Vulnerability Analysis** covering 4 threat actor categories and 6 vulnerability domains
- **8 Risk Findings** — each scored using a qualitative 5×5 Likelihood × Impact matrix
- **90-Day Remediation Roadmap** with specific free tooling recommendations
- **NIST CSF 2.0 subcategory mappings** for every finding (e.g., PR.AA-03, ID.RA-01)


### Risk findings summary:

| ID | Risk | Rating | Score |
|----|------|--------|-------|
| R-001 | No MFA on Admin Accounts | 🔴 CRITICAL | 25/25 |
| R-002 | Insufficient Encryption of PII at Rest | 🔴 CRITICAL | 20/25 |
| R-003 | No Incident Response Plan | 🟠 HIGH | 16/25 |
| R-004 | No Security Awareness Training | 🟠 HIGH | 16/25 |
| R-005 | No Patch Management Programme | 🟡 MEDIUM | 12/25 |
| R-006 | Excessive Privileges / No Access Reviews | 🟡 MEDIUM | 9/25 |
| R-007 | Insufficient Logging & Monitoring | 🟡 MEDIUM | 9/25 |
| R-008 | Unassessed Third-Party Vendor Risk | 🟢 LOW | 6/25 |

---
