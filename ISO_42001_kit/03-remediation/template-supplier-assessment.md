# Third-Party AI Supplier Assessment

> **Current as of:** March 2026 | ISO/IEC 42001:2023 | EU AI Act (Regulation 2024/1689)

---

<!--
╔══════════════════════════════════════════════════════════════════════════════╗
║  HOW TO CUSTOMIZE — Internal Consultant Use Only (Remove Before Delivery)  ║
╠══════════════════════════════════════════════════════════════════════════════╣
║                                                                            ║
║  WHEN TO COMPLETE                                                          ║
║  Complete one assessment for each AI vendor/supplier in the organization's ║
║  AI System Inventory (AIMS-INV-001). If a single vendor provides multiple  ║
║  AI systems, complete one assessment covering all systems from that vendor ║
║  unless the systems operate under materially different contracts or data    ║
║  processing terms — in that case, complete a separate assessment per       ║
║  contract.                                                                 ║
║                                                                            ║
║  WHO SHOULD COMPLETE IT                                                    ║
║  This assessment requires input from three roles:                          ║
║  • IT Lead — provides technical details on integrations, data flows,       ║
║    security configurations, and vendor contact information                 ║
║  • Procurement / Contract Owner — provides contract terms, commercial      ║
║    details, and manages vendor engagement for due diligence questions       ║
║  • Legal / Data Protection — reviews data processing terms, DPA status,    ║
║    GDPR compliance, and EU AI Act obligations                              ║
║                                                                            ║
║  The consultant facilitates the process and ensures completeness. For      ║
║  SMB clients without separate Procurement or Legal functions, the IT Lead  ║
║  and a senior manager can jointly complete the assessment with consultant  ║
║  guidance.                                                                 ║
║                                                                            ║
║  HOW TO HANDLE UNCOOPERATIVE VENDORS                                       ║
║  Some vendors — particularly smaller AI startups — will not answer due     ║
║  diligence questions. This is expected. Do NOT delay the AIMS              ║
║  implementation waiting for vendor responses.                              ║
║                                                                            ║
║  Process for non-responsive vendors:                                       ║
║  1. Send the vendor a written due diligence request (email is sufficient)  ║
║  2. Allow 15 business days for response                                    ║
║  3. Send one follow-up if no response received                             ║
║  4. If still no response after 25 business days total, classify the        ║
║     vendor as Tier 3 (Limited Transparency) or Tier 4 (No Transparency)   ║
║  5. Complete Section 4 (Limited Transparency Tier) and document            ║
║     compensating controls                                                  ║
║  6. Record the vendor's non-response as evidence — this IS the due        ║
║     diligence record                                                       ║
║                                                                            ║
║  PRIORITY ORDER                                                            ║
║  Assess vendors in this order:                                             ║
║  1. Vendors processing the most sensitive organizational data              ║
║  2. Vendors with the highest-risk AI use cases (per Risk Register)         ║
║  3. Vendors with the largest contract values                               ║
║  4. All remaining vendors                                                  ║
║                                                                            ║
║  CONTROL TRACEABILITY                                                      ║
║  This template implements the following ISO 42001 Annex A controls:        ║
║  • A.10.2 — Suppliers of AI System Components                             ║
║  • A.6.2.11 — Management of Third-Party AI System Components              ║
║  • A.10.3 — Shared ML Models (where applicable)                           ║
║                                                                            ║
║  Remove this entire comment block before delivering to the client.         ║
╚══════════════════════════════════════════════════════════════════════════════╝
-->

## Document Metadata

| Field | Value |
|---|---|
| **Document ID** | AIMS-SUP-[vendor]-001 |
| **Version** | 1.0 |
| **Date** | [YYYY-MM-DD] |
| **Vendor Name** | [Vendor Name] |
| **AI System(s) Assessed** | [List all AI systems from this vendor within AIMS scope] |
| **Organization** | [Organization Name] |
| **Prepared By** | [Name, Role] |
| **Reviewed By** | [Name, Role] |
| **Next Review Date** | [YYYY-MM-DD — no later than 12 months from Date] |

---

## Purpose

This document provides a structured assessment of a third-party AI vendor's governance, security, transparency, and contractual posture. It supports the organization's obligations under ISO/IEC 42001:2023 to manage AI components sourced from third parties (Annex A controls A.10.2, A.6.2.11, and A.10.3 where applicable).

Complete one assessment per AI vendor. Use this assessment alongside the AI System Inventory (AIMS-INV-001) and the Risk Assessment Register (AIMS-RISK-001) to maintain a complete picture of third-party AI risk.

### Control Traceability

| Annex A Control | Control Title | How This Template Addresses It |
|---|---|---|
| **A.10.2** | Suppliers of AI System Components | Sections 1–3 and 5: vendor selection criteria, contractual requirements, ongoing assessment, and performance monitoring |
| **A.6.2.11** | Management of Third-Party AI System Components | Sections 2 and 3: ongoing assessment of third-party AI components including governance, data handling, security, and contractual terms |
| **A.10.3** | Shared ML Models | Section 2.2: assessment of model transparency, provenance, and limitations for shared or pre-trained models |

> **Legal Disclaimer:** This template does not constitute legal advice. Organizations should consult qualified legal counsel for questions about regulatory obligations, including EU AI Act classification and compliance requirements. The assessment questions in this document are designed to support ISO 42001 conformity and do not replace regulatory legal analysis.

---

## Section 1: Vendor Overview

*Complete this section using contract records, vendor documentation, and IT system records.*

### 1.1 Vendor Identification

| Field | Value |
|---|---|
| **Vendor Legal Name** | [Full legal entity name] |
| **Trading Name (if different)** | [Trading/brand name] |
| **Headquarters Location** | [City, Country] |
| **Website** | [URL] |
| **Vendor's Role in AI Value Chain** | [ ] AI Developer / [ ] AI Provider / [ ] Both |

*Example: Microsoft Corporation | Redmond, WA, United States | microsoft.com | Both (AI Developer and AI Provider)*

### 1.2 AI Systems Provided

List all AI systems this vendor provides to the organization that are within AIMS scope:

| AI System Name | Description | Business Function | Inventory Reference |
|---|---|---|---|
| [System name] | [Brief description of AI capabilities used] | [Department/process using this system] | [AIMS-INV-001 entry ID] |
| [System name] | [Brief description] | [Department/process] | [Entry ID] |
| [System name] | [Brief description] | [Department/process] | [Entry ID] |

*Example:*

| AI System Name | Description | Business Function | Inventory Reference |
|---|---|---|---|
| *Microsoft 365 Copilot* | *Generative AI assistant embedded in Word, Excel, PowerPoint, Outlook, Teams — drafts content, summarizes documents, generates presentations, analyzes data* | *All departments* | *AIMS-INV-001, Entry 2* |

### 1.3 Commercial Relationship

| Field | Value |
|---|---|
| **Contract Type** | [ ] SaaS Subscription / [ ] API Access / [ ] Enterprise License / [ ] Platform License / [ ] Other: _______ |
| **Contract Start Date** | [YYYY-MM-DD] |
| **Contract End Date** | [YYYY-MM-DD] |
| **Renewal Date** | [YYYY-MM-DD] |
| **Auto-Renewal** | [ ] Yes / [ ] No |
| **Annual Contract Value (range)** | [ ] Under £10,000 / [ ] £10,000–£50,000 / [ ] £50,000–£150,000 / [ ] Over £150,000 |
| **Primary Vendor Contact** | [Name, Role, Email] |
| **Account Manager** | [Name, Email] |

*Example: SaaS Subscription | Microsoft 365 E5 with Copilot add-on | Annual contract value: £50,000–£150,000*

### 1.4 Vendor Certifications

| Certification | Status | Certificate Reference | Expiry Date |
|---|---|---|---|
| ISO 27001 | [ ] Certified / [ ] Not Certified / [ ] Unknown | [Reference number or URL] | [Date] |
| SOC 2 Type II | [ ] Certified / [ ] Not Certified / [ ] Unknown | [Reference] | [Date] |
| ISO 42001 | [ ] Certified / [ ] Not Certified / [ ] In Progress / [ ] Unknown | [Reference] | [Date] |
| SOC 3 | [ ] Certified / [ ] Not Certified / [ ] Unknown | [Reference] | [Date] |
| Other: _______ | [ ] Certified / [ ] Not Certified / [ ] Unknown | [Reference] | [Date] |

*Example: Microsoft holds ISO 27001, SOC 2 Type II, and SOC 3 certifications for Microsoft 365 services. ISO 42001 certification status: In Progress (as of March 2026). Certificate details available via the Microsoft Service Trust Portal (servicetrust.microsoft.com).*

---

## Section 2: AI Governance Assessment

*For each question, record the vendor's response, note any evidence provided, and assign an assessment rating. Use the following rating scale:*

| Rating | Definition |
|---|---|
| **Satisfactory** | Vendor provides a clear, documented response with supporting evidence |
| **Partial** | Vendor provides a response but evidence is incomplete or the practice is immature |
| **Unsatisfactory** | Vendor response reveals gaps, deficiencies, or practices that conflict with organizational requirements |
| **Unknown** | Vendor has not responded to this question or provided insufficient information to assess |

---

### 2.1 AI Policy and Governance

| # | Question | Response | Evidence Provided | Assessment | Notes |
|---|---|---|---|---|---|
| 2.1.1 | Does the vendor have a published AI policy or responsible AI principles? | [Response] | [ ] Public document / [ ] Provided on request / [ ] Not available | [ ] Satisfactory / [ ] Partial / [ ] Unsatisfactory / [ ] Unknown | [Notes] |
| 2.1.2 | Does the vendor have an AI ethics board or governance committee? | [Response] | [ ] Public disclosure / [ ] Provided on request / [ ] Not available | [ ] Satisfactory / [ ] Partial / [ ] Unsatisfactory / [ ] Unknown | [Notes] |
| 2.1.3 | Has the vendor published an AI transparency report? | [Response] | [ ] Public report / [ ] Provided on request / [ ] Not available | [ ] Satisfactory / [ ] Partial / [ ] Unsatisfactory / [ ] Unknown | [Notes] |
| 2.1.4 | Is the vendor pursuing or holding ISO 42001 certification? | [Response] | [ ] Certificate / [ ] Public statement / [ ] Not available | [ ] Satisfactory / [ ] Partial / [ ] Unsatisfactory / [ ] Unknown | [Notes] |

*Example (Microsoft):*

| # | Question | Response | Evidence Provided | Assessment | Notes |
|---|---|---|---|---|---|
| *2.1.1* | *Does the vendor have a published AI policy or responsible AI principles?* | *Yes — Microsoft publishes Responsible AI Principles covering fairness, reliability & safety, privacy & security, inclusiveness, transparency, and accountability* | *Public document: microsoft.com/ai/responsible-ai* | *Satisfactory* | *Principles published since 2018, regularly updated* |
| *2.1.2* | *Does the vendor have an AI ethics board or governance committee?* | *Yes — Office of Responsible AI (ORA) and AI, Ethics, and Effects in Engineering and Research (Aether) committee* | *Public disclosure in annual Responsible AI Transparency Report* | *Satisfactory* | *Governance structure includes both executive oversight and cross-functional working groups* |
| *2.1.3* | *Has the vendor published an AI transparency report?* | *Yes — annual Responsible AI Transparency Report* | *Public report* | *Satisfactory* | *Most recent report covers Copilot transparency features* |
| *2.1.4* | *Is the vendor pursuing or holding ISO 42001 certification?* | *In progress — Microsoft has announced alignment work toward ISO 42001* | *Public statement* | *Partial* | *Not yet certified as of assessment date; monitor for updates* |

---

### 2.2 Model Transparency

| # | Question | Response | Evidence Provided | Assessment | Notes |
|---|---|---|---|---|---|
| 2.2.1 | What AI model(s) power the services provided to our organization? | [Response — e.g., GPT-4, proprietary model, etc.] | [ ] Documentation / [ ] Model card / [ ] Not disclosed | [ ] Satisfactory / [ ] Partial / [ ] Unsatisfactory / [ ] Unknown | [Notes] |
| 2.2.2 | How does the vendor communicate model updates that may affect outputs? | [Response] | [ ] Change log / [ ] Email notification / [ ] Service dashboard / [ ] Not communicated | [ ] Satisfactory / [ ] Partial / [ ] Unsatisfactory / [ ] Unknown | [Notes] |
| 2.2.3 | What is the vendor's process for notifying customers of significant model changes? | [Response] | [ ] Documented process / [ ] Ad hoc / [ ] Not disclosed | [ ] Satisfactory / [ ] Partial / [ ] Unsatisfactory / [ ] Unknown | [Notes] |
| 2.2.4 | Does the vendor provide model cards or system cards describing model capabilities and limitations? | [Response] | [ ] Published model/system card / [ ] Provided on request / [ ] Not available | [ ] Satisfactory / [ ] Partial / [ ] Unsatisfactory / [ ] Unknown | [Notes] |

*Example (Microsoft):*

| # | Question | Response | Evidence Provided | Assessment | Notes |
|---|---|---|---|---|---|
| *2.2.1* | *What AI model(s) power the services provided?* | *Microsoft 365 Copilot is powered by OpenAI GPT-4 models, integrated through Microsoft's Azure OpenAI Service infrastructure* | *Documentation: Microsoft 365 Copilot technical documentation* | *Satisfactory* | *Model architecture publicly documented; specific version updates communicated via Message Center* |
| *2.2.2* | *How does the vendor communicate model updates?* | *Via Microsoft 365 Message Center, service health dashboard, and Microsoft 365 roadmap* | *Service dashboard* | *Satisfactory* | *Admins can configure notification preferences* |
| *2.2.3* | *Notification process for significant model changes?* | *Documented change management process — significant changes announced via Message Center with advance notice period* | *Documented process* | *Satisfactory* | *Advance notice typically 30+ days for major changes* |
| *2.2.4* | *Model cards or system cards available?* | *Yes — Microsoft publishes system cards for Copilot features describing capabilities, limitations, and responsible use guidance* | *Published system card* | *Satisfactory* | *System cards available in Microsoft Learn documentation* |

---

### 2.3 Data Handling

| # | Question | Response | Evidence Provided | Assessment | Notes |
|---|---|---|---|---|---|
| 2.3.1 | What data does the vendor collect from our organization's use of the AI system? | [Response] | [ ] Data flow documentation / [ ] Privacy policy / [ ] Not disclosed | [ ] Satisfactory / [ ] Partial / [ ] Unsatisfactory / [ ] Unknown | [Notes] |
| 2.3.2 | Is our data used to train or improve the vendor's AI models? | [ ] Yes / [ ] No / [ ] Opt-out available / [ ] Unknown | [ ] Contractual commitment / [ ] Published policy / [ ] Not disclosed | [ ] Satisfactory / [ ] Partial / [ ] Unsatisfactory / [ ] Unknown | [Notes] |
| 2.3.3 | Where is our data stored? (data residency/sovereignty) | [Response — region/country] | [ ] Data residency documentation / [ ] Contractual clause / [ ] Not disclosed | [ ] Satisfactory / [ ] Partial / [ ] Unsatisfactory / [ ] Unknown | [Notes] |
| 2.3.4 | What is the vendor's data retention and deletion policy? | [Response] | [ ] Published policy / [ ] Contractual clause / [ ] Not disclosed | [ ] Satisfactory / [ ] Partial / [ ] Unsatisfactory / [ ] Unknown | [Notes] |
| 2.3.5 | Does the vendor have a Data Processing Agreement (DPA) in place? | [ ] Yes — DPA executed / [ ] Yes — standard DPA available / [ ] No / [ ] Unknown | [ ] Executed DPA / [ ] Standard DPA reviewed / [ ] Not available | [ ] Satisfactory / [ ] Partial / [ ] Unsatisfactory / [ ] Unknown | [Notes] |
| 2.3.6 | What encryption standards are applied to our data? | [Response — encryption at rest, in transit, key management] | [ ] Security documentation / [ ] Certification report / [ ] Not disclosed | [ ] Satisfactory / [ ] Partial / [ ] Unsatisfactory / [ ] Unknown | [Notes] |

*Example (Microsoft):*

| # | Question | Response | Evidence Provided | Assessment | Notes |
|---|---|---|---|---|---|
| *2.3.1* | *What data is collected?* | *Copilot processes data within the Microsoft 365 tenant boundary — prompts, responses, and referenced documents. Telemetry data collected per Microsoft privacy statement* | *Data flow documentation in Microsoft 365 Copilot data residency documentation* | *Satisfactory* | *Data remains within tenant boundary; telemetry governed by privacy statement* |
| *2.3.2* | *Is our data used to train models?* | *No — Microsoft commits that Microsoft 365 Copilot does not use customer data to train foundation models* | *Contractual commitment in Microsoft Product Terms* | *Satisfactory* | *Explicit contractual commitment; verified in Product Terms (updated quarterly)* |
| *2.3.3* | *Where is our data stored?* | *Data residency follows Microsoft 365 tenant location — EU Data Boundary available for EU tenants* | *Data residency documentation and EU Data Boundary commitments* | *Satisfactory* | *Organization's tenant located in [UK/EU region — confirm]* |
| *2.3.4* | *Data retention and deletion policy?* | *Customer data deleted per Microsoft 365 retention policies configured by the organization; Copilot interaction data subject to published retention schedule* | *Published policy in Microsoft Product Terms* | *Satisfactory* | *Organization controls retention via Microsoft 365 compliance center* |
| *2.3.5* | *DPA in place?* | *Yes — Microsoft Online Services Data Processing Agreement (DPA) included in Microsoft Product Terms* | *Executed DPA (part of enterprise agreement)* | *Satisfactory* | *DPA covers GDPR requirements; reviewed and accepted at contract signing* |
| *2.3.6* | *Encryption standards?* | *AES-256 encryption at rest, TLS 1.2+ in transit, Microsoft-managed keys with customer-managed key option available* | *Security documentation and SOC 2 report* | *Satisfactory* | *Meets organizational encryption requirements* |

---

### 2.4 Security and Compliance

| # | Question | Response | Evidence Provided | Assessment | Notes |
|---|---|---|---|---|---|
| 2.4.1 | What security certifications does the vendor hold? (SOC 2 Type II, ISO 27001, etc.) | [Response] | [ ] Certificates / [ ] Audit reports / [ ] Not disclosed | [ ] Satisfactory / [ ] Partial / [ ] Unsatisfactory / [ ] Unknown | [Notes] |
| 2.4.2 | Has the vendor experienced any data breaches in the past 24 months? If yes, describe. | [Response] | [ ] Breach disclosure / [ ] Written attestation / [ ] Not disclosed | [ ] Satisfactory / [ ] Partial / [ ] Unsatisfactory / [ ] Unknown | [Notes] |
| 2.4.3 | What is the vendor's incident response process for AI-related incidents? | [Response] | [ ] Documented IR plan / [ ] Published process / [ ] Not disclosed | [ ] Satisfactory / [ ] Partial / [ ] Unsatisfactory / [ ] Unknown | [Notes] |
| 2.4.4 | Does the vendor comply with GDPR / applicable data protection regulations? | [Response] | [ ] Compliance documentation / [ ] DPA / [ ] Not disclosed | [ ] Satisfactory / [ ] Partial / [ ] Unsatisfactory / [ ] Unknown | [Notes] |

*Example (Microsoft): SOC 2 Type II, ISO 27001, ISO 27018 certified. No material AI-specific data breaches disclosed. Incident response process documented in Microsoft Security Response Center (MSRC) practices. GDPR compliance documented in DPA and Microsoft Trust Center.*

---

### 2.5 EU AI Act Compliance

*Complete this subsection where the AI system may fall within EU AI Act scope. If the organization does not operate within the EU or process data of EU persons, note as "Not applicable — outside EU AI Act territorial scope" and proceed to Section 2.6.*

| # | Question | Response | Evidence Provided | Assessment | Notes |
|---|---|---|---|---|---|
| 2.5.1 | Has the vendor assessed whether its AI systems are classified as high-risk under the EU AI Act? | [Response] | [ ] Risk classification documentation / [ ] Public statement / [ ] Not disclosed | [ ] Satisfactory / [ ] Partial / [ ] Unsatisfactory / [ ] Unknown | [Notes] |
| 2.5.2 | Does the vendor provide documentation to support deployer compliance obligations? | [Response] | [ ] Deployer documentation / [ ] Technical documentation / [ ] Not available | [ ] Satisfactory / [ ] Partial / [ ] Unsatisfactory / [ ] Unknown | [Notes] |
| 2.5.3 | Does the vendor maintain an EU AI Act conformity assessment or CE marking (for high-risk systems)? | [Response] | [ ] Conformity documentation / [ ] CE marking / [ ] Not applicable / [ ] Not disclosed | [ ] Satisfactory / [ ] Partial / [ ] Unsatisfactory / [ ] Unknown | [Notes] |

*Example (Microsoft): Microsoft has publicly committed to supporting customer compliance with the EU AI Act. Copilot features include transparency documentation. Conformity assessment processes for high-risk use cases are being developed in alignment with EU AI Act implementation timelines. As a general-purpose AI system provider, Microsoft is subject to obligations under Title V of the EU AI Act.*

---

### 2.6 Human Oversight and Control

| # | Question | Response | Evidence Provided | Assessment | Notes |
|---|---|---|---|---|---|
| 2.6.1 | What human oversight mechanisms does the vendor build into the AI system? | [Response] | [ ] Product documentation / [ ] Configuration guide / [ ] Not disclosed | [ ] Satisfactory / [ ] Partial / [ ] Unsatisfactory / [ ] Unknown | [Notes] |
| 2.6.2 | Can the organization disable or override AI features? | [ ] Yes — fully / [ ] Yes — partially / [ ] No / [ ] Unknown | [ ] Admin documentation / [ ] Configuration options / [ ] Not available | [ ] Satisfactory / [ ] Partial / [ ] Unsatisfactory / [ ] Unknown | [Notes] |
| 2.6.3 | Does the vendor provide audit logs of AI system activity? | [ ] Yes — comprehensive / [ ] Yes — limited / [ ] No / [ ] Unknown | [ ] Log documentation / [ ] Sample logs / [ ] Not available | [ ] Satisfactory / [ ] Partial / [ ] Unsatisfactory / [ ] Unknown | [Notes] |

*Example (Microsoft): Copilot outputs are presented as suggestions requiring user review and acceptance. Administrators can enable/disable Copilot per user, per application, and per sensitivity label via Microsoft 365 admin center. Copilot interaction logs available through Microsoft Purview Audit for compliance monitoring.*

---

### 2.7 Performance and Reliability

| # | Question | Response | Evidence Provided | Assessment | Notes |
|---|---|---|---|---|---|
| 2.7.1 | What SLA does the vendor provide for AI system availability? | [Response — uptime %, response time guarantees] | [ ] Published SLA / [ ] Contractual SLA / [ ] Not disclosed | [ ] Satisfactory / [ ] Partial / [ ] Unsatisfactory / [ ] Unknown | [Notes] |
| 2.7.2 | How does the vendor monitor and report on AI system performance? | [Response] | [ ] Status page / [ ] Performance reports / [ ] Not disclosed | [ ] Satisfactory / [ ] Partial / [ ] Unsatisfactory / [ ] Unknown | [Notes] |
| 2.7.3 | What is the vendor's process for handling AI system errors or unexpected outputs? | [Response] | [ ] Documented process / [ ] Support channel / [ ] Not disclosed | [ ] Satisfactory / [ ] Partial / [ ] Unsatisfactory / [ ] Unknown | [Notes] |

*Example (Microsoft): Microsoft 365 SLA provides 99.9% uptime guarantee with financial credits for non-compliance. Performance monitored via Microsoft 365 Service Health Dashboard (status.office.com). AI-specific issues reported through standard Microsoft support channels with AI-specific escalation paths for enterprise customers.*

---

## Section 3: Contractual Assessment

*Review the current contract, DPA, and terms of service against AI-specific requirements. This section identifies contractual gaps that should be addressed at the next contract renewal.*

| # | Contractual Element | Status | Details | Gap Identified |
|---|---|---|---|---|
| 3.1 | Does the current contract include AI-specific data processing terms? | [ ] Yes / [ ] No / [ ] Partial | [Details] | [ ] Yes / [ ] No |
| 3.2 | Does the contract address model updates and change notification? | [ ] Yes / [ ] No | [Details] | [ ] Yes / [ ] No |
| 3.3 | Does the contract include incident notification obligations? | [ ] Yes / [ ] No | [Details] | [ ] Yes / [ ] No |
| 3.4 | Does the contract address data deletion upon termination? | [ ] Yes / [ ] No | [Details] | [ ] Yes / [ ] No |
| 3.5 | Does the contract address data training opt-out? | [ ] Yes / [ ] No / [ ] N/A | [Details] | [ ] Yes / [ ] No |
| 3.6 | Does the contract reference the vendor's AI governance commitments? | [ ] Yes / [ ] No | [Details] | [ ] Yes / [ ] No |
| 3.7 | Does the contract include right-to-audit or compliance reporting provisions? | [ ] Yes / [ ] No | [Details] | [ ] Yes / [ ] No |

### Contractual Gaps Identified

| # | Gap Description | Risk Level | Recommended Amendment |
|---|---|---|---|
| 1 | [Description of missing contractual element] | [ ] High / [ ] Medium / [ ] Low | [Recommended language or action] |
| 2 | [Description] | [ ] High / [ ] Medium / [ ] Low | [Recommendation] |
| 3 | [Description] | [ ] High / [ ] Medium / [ ] Low | [Recommendation] |

### Recommended Contract Amendments

*List specific amendments to pursue at the next contract renewal or renegotiation:*

1. [Amendment description — e.g., "Add AI-specific data processing addendum addressing model training opt-out"]
2. [Amendment description]
3. [Amendment description]

*Example (Microsoft): Microsoft 365 enterprise agreement with Copilot add-on includes AI-specific terms in the Microsoft Product Terms (updated quarterly). DPA covers data processing. Model update notifications provided via Message Center. Data deletion on termination addressed in standard terms. Minor gap identified: contract does not explicitly reference ISO 42001 alignment — recommend raising at next enterprise agreement renewal.*

---

## Section 4: Limited Transparency Tier

*This section is critical for vendors who will not or cannot answer due diligence questions. Complete the Transparency Classification for every vendor. For Tier 3 and Tier 4 vendors, complete the full section including compensating controls and decision framework.*

### 4.1 Transparency Classification

Assess the vendor's overall willingness and ability to provide due diligence information:

| Tier | Classification | Definition | Criteria |
|---|---|---|---|
| **Tier 1** | **Full Transparency** | Vendor responds to all due diligence questions with documented evidence | All Section 2 questions answered; supporting evidence provided for material responses; vendor engages proactively with assessment process |
| **Tier 2** | **Partial Transparency** | Vendor responds to most questions; some gaps remain | Majority of Section 2 questions answered; evidence provided for some but not all responses; gaps are non-material or relate to commercially sensitive information the vendor explains |
| **Tier 3** | **Limited Transparency** | Vendor declines to answer material questions or provides only marketing materials | Vendor responds with marketing content rather than substantive answers; declines to answer data handling or security questions; does not provide certifications or audit reports; or fails to respond within 25 business days |
| **Tier 4** | **No Transparency** | Vendor refuses all due diligence engagement | Vendor explicitly declines due diligence, does not respond to any outreach, or provides no information beyond what is publicly available on its website |

**This vendor's Transparency Tier:** [ ] Tier 1 / [ ] Tier 2 / [ ] Tier 3 / [ ] Tier 4

**Justification:** [Explain why this tier was assigned, referencing specific evidence or non-responses]

---

### 4.2 Tier 3 and Tier 4: Risk Escalation

*Complete this subsection only for Tier 3 and Tier 4 vendors.*

> **Mandatory action:** Any vendor classified as Tier 3 or Tier 4 must be documented as **High Risk** in the Risk Assessment Register (AIMS-RISK-001), regardless of other risk factors. The inability to verify a vendor's AI governance practices is itself a material risk.

| Field | Value |
|---|---|
| **Risk Register Entry ID** | [AIMS-RISK-001 entry reference] |
| **Risk Category** | Third-Party AI — Limited Vendor Transparency |
| **Risk Rating Override** | HIGH (mandatory for Tier 3/4 vendors) |
| **Date Escalated** | [YYYY-MM-DD] |
| **Escalated To** | [Name, Role — must be senior management for Tier 4] |

---

### 4.3 Tier 3 and Tier 4: Compensating Controls

*When vendor cooperation is unavailable, the organization must implement compensating controls to manage the risk of using the vendor's AI system without full visibility into its governance practices.*

| # | Compensating Control | Description | Implemented | Owner |
|---|---|---|---|---|
| 4.3.1 | **Usage Restrictions** | Restrict the use of the AI system to non-sensitive data and lower-risk business processes only. Define which data classifications are prohibited as inputs. | [ ] Yes / [ ] Planned / [ ] N/A | [Name, Role] |
| 4.3.2 | **Data Minimization** | Minimize the volume and sensitivity of organizational data provided to the AI system. Do not share confidential, personal, or regulated data unless contractually protected. | [ ] Yes / [ ] Planned / [ ] N/A | [Name, Role] |
| 4.3.3 | **Enhanced Monitoring** | Implement additional monitoring of the AI system's outputs and behavior, including regular spot-checks for accuracy, bias, or unexpected behavior changes. | [ ] Yes / [ ] Planned / [ ] N/A | [Name, Role] |
| 4.3.4 | **Contractual Protections** | Ensure the contract includes maximum available protections: data processing terms, deletion on termination, incident notification, liability provisions. | [ ] Yes / [ ] Planned / [ ] N/A | [Name, Role] |
| 4.3.5 | **Output Verification** | Require human review and verification of all AI outputs before use in business decisions. No AI output from a Tier 3/4 vendor should be used without human validation. | [ ] Yes / [ ] Planned / [ ] N/A | [Name, Role] |
| 4.3.6 | **Alternative Vendor Assessment** | Evaluate alternative vendors who offer greater transparency. Include transparency posture as a weighted criterion in vendor selection. | [ ] Yes / [ ] Planned / [ ] N/A | [Name, Role] |

### Additional compensating controls (if applicable):

| # | Control Description | Implemented | Owner |
|---|---|---|---|
| 4.3.7 | [Description] | [ ] Yes / [ ] Planned | [Name, Role] |
| 4.3.8 | [Description] | [ ] Yes / [ ] Planned | [Name, Role] |

---

### 4.4 Tier 3 and Tier 4: Decision Framework

*Based on the transparency tier, compensating controls assessment, and organizational risk appetite, select the appropriate course of action:*

| Decision | When Appropriate | Required Approver |
|---|---|---|
| **Continue use with compensating controls** | Tier 3 vendor where the AI system provides significant business value; all compensating controls in Section 4.3 are implemented and monitored; no suitable transparent alternative exists at comparable cost | IT Lead + Senior Management |
| **Restrict use** | Tier 3 or Tier 4 vendor where continued use is necessary but risk must be actively reduced; restrict to specific use cases, specific users, or non-sensitive data only | IT Lead + Senior Management |
| **Discontinue use** | Tier 4 vendor where compensating controls are insufficient to manage risk; viable alternative vendors exist; or the AI system processes sensitive data without adequate contractual protection | Senior Management |

**Decision for this vendor:** [ ] Continue with compensating controls / [ ] Restrict use / [ ] Discontinue use

**Justification:** [Explain the decision, referencing compensating controls and business need]

**Restrictions (if "Restrict use" selected):**

- Permitted use cases: [List]
- Permitted users/departments: [List]
- Prohibited data classifications: [List]
- Review frequency: [Monthly / Quarterly]

> **Tier 4 Escalation Requirement:** For any vendor classified as Tier 4, the decision to continue use, restrict, or discontinue must be escalated to and approved by senior management. The escalation and decision must be documented as evidence for internal audit.

---

## Section 5: Overall Assessment

### 5.1 Assessment Summary

| Field | Value |
|---|---|
| **Vendor Name** | [Vendor Name] |
| **Transparency Tier** | [ ] Tier 1 / [ ] Tier 2 / [ ] Tier 3 / [ ] Tier 4 |
| **Overall Risk Rating** | [ ] Low / [ ] Medium / [ ] High / [ ] Critical |
| **Recommendation** | [ ] Approve / [ ] Approve with Conditions / [ ] Restrict / [ ] Discontinue |

### 5.2 Risk Rating Guidance

Use the following guidance to determine the overall risk rating. The highest applicable rating applies:

| Rating | Criteria |
|---|---|
| **Low** | Tier 1 transparency; vendor holds relevant security certifications; DPA in place; data handling practices meet organizational requirements; no material contractual gaps |
| **Medium** | Tier 2 transparency; vendor holds some certifications; DPA in place; minor contractual gaps identified; vendor responsive to due diligence but some evidence gaps |
| **High** | Tier 3 transparency; OR material contractual gaps; OR vendor lacks relevant certifications; OR data handling practices raise concerns; OR vendor processes sensitive data without adequate protections |
| **Critical** | Tier 4 transparency; OR vendor has experienced a material data breach affecting AI services; OR vendor cannot demonstrate GDPR/data protection compliance; OR AI system processes high-risk data (per EU AI Act) without adequate governance |

### 5.3 Conditions and Required Actions

**Conditions for continued use (if "Approve with Conditions" selected):**

| # | Condition | Deadline | Owner |
|---|---|---|---|
| 1 | [Condition — e.g., "Execute updated DPA with AI-specific terms"] | [YYYY-MM-DD] | [Name, Role] |
| 2 | [Condition] | [Date] | [Name, Role] |
| 3 | [Condition] | [Date] | [Name, Role] |

**Required actions before next review:**

| # | Action | Deadline | Owner | Status |
|---|---|---|---|---|
| 1 | [Action — e.g., "Request updated SOC 2 report covering AI services"] | [YYYY-MM-DD] | [Name, Role] | [ ] Open / [ ] Complete |
| 2 | [Action] | [Date] | [Name, Role] | [ ] Open / [ ] Complete |
| 3 | [Action] | [Date] | [Name, Role] | [ ] Open / [ ] Complete |

### 5.4 Next Review

| Field | Value |
|---|---|
| **Next Review Date** | [YYYY-MM-DD — no later than 12 months from assessment date; 6 months for High/Critical risk vendors] |
| **Review Trigger Events** | Material contract change, vendor breach notification, significant model update, organizational change affecting AI usage, or change in vendor transparency posture |
| **Review Owner** | [Name, Role] |

*Example (Microsoft): Transparency Tier 1 — Full Transparency. Overall Risk Rating: Low. Recommendation: Approve. Microsoft provides comprehensive due diligence documentation, holds relevant certifications, has DPA in place, and commits to not using customer data for model training. Next review in 12 months or upon significant Copilot feature changes.*

---

## Section 6: Approval

*This assessment must be reviewed and approved before it constitutes a formal vendor risk assessment record for AIMS purposes.*

### Assessor Sign-Off

| Field | Value |
|---|---|
| **Assessor Name** | [Name] |
| **Role** | [Role] |
| **Date** | [YYYY-MM-DD] |
| **Signature** | _________________________ |

### IT Lead Sign-Off

| Field | Value |
|---|---|
| **IT Lead Name** | [Name] |
| **Role** | [Role] |
| **Date** | [YYYY-MM-DD] |
| **Signature** | _________________________ |

### Senior Management Approval

*Required for all vendors rated High Risk or Critical, and for all Tier 4 vendors regardless of risk rating.*

| Field | Value |
|---|---|
| **Senior Manager Name** | [Name] |
| **Role** | [Role] |
| **Date** | [YYYY-MM-DD] |
| **Decision** | [ ] Approved / [ ] Approved with Conditions / [ ] Rejected |
| **Comments** | [Comments] |
| **Signature** | _________________________ |

---

## Version History

| Version | Date | Author | Changes |
|---|---|---|---|
| 1.0 | [YYYY-MM-DD] | [Name] | Initial assessment |
| | | | |
| | | | |

---

*ISO 42001 Readiness Service Toolkit | 03-Remediation | Confidential Client Deliverable*
