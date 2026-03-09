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
| 01 | [Risk Assessment](01-risk-assessment/NimbusHR_Risk_Assessment_3.pdf.pdf | NIST CSF 2.0 — GOVERN, IDENTIFY | ✅ Complete |
| 02 | [Risk Register](./02-risk-register/NimbusHR_Risk_Register.xlsx) | NIST CSF 2.0 — IDENTIFY (ID.RA) | ✅ Complete |
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


##  Methodology & Frameworks

### NIST Cybersecurity Framework 2.0
All documents in this package align to the NIST CSF 2.0, which organises cybersecurity activities into six functions:

```
GOVERN → IDENTIFY → PROTECT → DETECT → RESPOND → RECOVER
```

This GRC package primarily addresses **GOVERN** (policies, roles, oversight) and **IDENTIFY** (asset management, risk assessment) — the foundation that all other security activities are built on.

**Free resource:** [https://www.nist.gov/cyberframework](https://www.nist.gov/cyberframework)


### Risk Scoring
Risks are scored using a **qualitative 5×5 matrix**:
- **Likelihood** (1–5): How probable is this threat materialising?
- **Impact** (1–5): How severe would the business damage be?
- **Risk Score** = Likelihood × Impact (max 25)

| Score Range | Rating | Action Required |
|-------------|--------|----------------|
| 20–25 | 🔴 CRITICAL | Immediate remediation |
| 12–19 | 🟠 HIGH | Remediate within 30–60 days |
| 6–11 | 🟡 MEDIUM | Remediate within 90 days |
| 1–5 | 🟢 LOW | Monitor and review annually |

---


## 🗂️ About the Fictional Company

**NimbusHR Inc.**  
Cloud-based HR SaaS platform · 40 employees · 200 small business clients  
Infrastructure: AWS (EC2, S3, RDS) · No dedicated security team  
Data handled: SSNs, salary data, onboarding documents, employee PII

*NimbusHR is entirely fictional and was created for portfolio demonstration purposes only.*

---

## 📚 Free Resources Used

All resources referenced in this project are publicly available at no cost:

- **NIST CSF 2.0** — [nist.gov/cyberframework](https://www.nist.gov/cyberframework)
- **MITRE ATT&CK** — [attack.mitre.org](https://attack.mitre.org)
- **CISA Known Exploited Vulnerabilities** — [cisa.gov/known-exploited-vulnerabilities-catalog](https://www.cisa.gov/known-exploited-vulnerabilities-catalog)
- **AWS Security Best Practices** — [docs.aws.amazon.com/security](https://docs.aws.amazon.com/security)
- **OpenVAS (free vulnerability scanner)** — [openvas.org](https://www.openvas.org)

---

## 🚀 What I Would Do Next (Real-World Extension)

If this were a real engagement, the next steps after delivering this package would be:

1. **Gap Analysis** — Map current controls against NIST CSF 2.0 targets to produce a maturity score
2. **Control Implementation Tracking** — Use the Risk Register to assign owners and track remediation to closure
3. **SOC 2 Readiness Assessment** — NimbusHR's client contracts likely require SOC 2 Type II; this package forms the foundation
4. **Tabletop Exercise** — Design and facilitate an IR tabletop scenario based on the top risks identified
5. **Vendor Risk Programme** — Build out a full third-party risk management (TPRM) workflow

---

## 👤 About Me

I'm transitioning deeper into cybersecurity with a focus on **Incident Response → GRC → Consulting**. I hold the Google Cybersecurity Certificate and am currently studying for CompTIA Security+.

This portfolio project was built entirely using free, publicly available frameworks to demonstrate practical GRC skills without requiring enterprise tooling.

📫 Connect with me on [LinkedIn](https://www.linkedin.com/in/dvhii/) | 🌐 [More projects](#)

---

*All company names, data, and scenarios in this repository are fictional and created for educational and portfolio purposes only.*
