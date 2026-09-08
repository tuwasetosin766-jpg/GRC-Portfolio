# GRC Portfolio — Tosin Tuwase

**Governance, Risk & Compliance | Nigerian Data Protection Law | ISO 27001 | Microsoft Security**

——-

## About This Portfolio

This repository contains a set of practice GRC (Governance, Risk & Compliance) documents built to demonstrate applied knowledge of information security frameworks and Nigerian data protection law.

I am a Computer Science graduate (Second Class Upper, Federal University Lokoja) transitioning into a career in Cybersecurity with a focus on GRC and Compliance. I am currently pursuing Microsoft's SC-900 Security, Compliance & Identity certification, with a structured roadmap toward roles in compliance analysis, risk assessment, and AI governance.

These documents were built on my final-year Computer Science degree project — an Applicant Assistant Chatbot System — and structured against real regulatory frameworks to simulate what a junior GRC analyst would produce in a professional environment.

---

## Portfolio Documents

### 1. Data Privacy Impact Assessment (DPIA)
**File:** `DPIA_Applicant_Assistant_Chatbot.pdf`

A full DPIA prepared under the Nigeria Data Protection Act (NDPA) 2023 and the General Application and Implementation Directive (GAID) 2025.

**Covers:**
- DPIA trigger identification under Article 28 of the GAID 2025
- Full mapping of all eight NDPA Section 24 data protection principles
- Four identified privacy risks with impact ratings and NDPA violation references
- Technical mitigations including AES-256 encryption, TLS 1.3, RBAC, and automated data retention
- Structured against Schedule 4 of the NDPC's GAID — the regulator's own DPIA template

**Frameworks referenced:** NDPA 2023 · GAID 2025 · NDPC Schedule 4

---

### 2. Corporate Access Control and Password Security Policy
**File:** `Corporate_Access_Control_Policy.pdf`

A formal information security policy governing user identification, authentication, and access management across all corporate systems.

**Covers:**
- Least privilege and separation of duties principles
- Password complexity standards (14-character minimum, character variety, history enforcement)
- Multi-Factor Authentication (MFA) requirements including prohibition of SMS-based MFA due to SIM-swapping risk
- Account lockout and brute-force protection thresholds
- User account provisioning and de-provisioning lifecycle including 2-hour off-boarding window

**Frameworks referenced:** ISO/IEC 27001 Control A.9 · NDPA 2023 · NIST SP 800-63

---

### 3. Enterprise Risk Register
**File:** `Enterprise_Risk_Register.xlsx`

A structured risk register covering seven identified risks across the chatbot system environment, with inherent and residual risk ratings, mitigating controls, and cross-references to the DPIA and Access Control Policy.

**Covers:**
- Unauthorized database access (High → Low after controls)
- Data exfiltration via unencrypted channels (High → Low after controls)
- DDoS and service availability risk (High → Medium after controls)
- Phishing and credential compromise (Critical → Medium after controls)
- Unapproved AI tool usage and data leakage (High → Low after controls)
- Undeployed storage limitation purge mechanism (High — open risk)
- Missing data subject rights mechanism (Medium — open risk)

**Frameworks referenced:** ISO/IEC 27001 · NDPA 2023 · GAID 2025

---

## Frameworks and Regulations Applied

| Framework / Regulation | Application |
|---|---|
| Nigeria Data Protection Act (NDPA) 2023 | Primary regulatory basis for DPIA and data handling |
| GAID 2025 (NDPC Implementation Directive) | DPIA trigger, Schedule 4 template, Article 28 obligations |
| ISO/IEC 27001 | Access control policy structure (Control A.9) |
| NIST SP 800-63 | Password and authentication standards reference |
| Microsoft SC-900 Curriculum | Security, compliance, and identity concepts applied throughout |

---

## Certifications In Progress

- **Microsoft SC-900** — Security, Compliance & Identity Fundamentals *(In Progress — Microsoft Learn, all learning path assessments passed)*

**Planned certification roadmap:**
SC-900 → CompTIA Security+ → SC-400 → CISM → CRISC → AIGP (AI Governance Professional)

---

## Connect

- **LinkedIn:** [linkedin.com/in/tosin-tuwase](https://linkedin.com/in/tosin-tuwase)
- **Email:** tuwasetosin766@gmail.com
- **Location:** Lagos, Nigeria | Open to Remote Opportunities Globally

---

*These are practice documents built to demonstrate GRC knowledge and applied regulatory understanding. They do not represent a live enterprise deployment. All company references are fictional and used for portfolio purposes only.*
