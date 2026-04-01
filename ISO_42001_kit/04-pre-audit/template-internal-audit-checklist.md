# Internal Audit Program and Checklist — ISO/IEC 42001:2023

> **Current as of:** March 2026 | ISO/IEC 42001:2023

---

> **HOW TO CUSTOMIZE — REMOVE THIS BLOCK BEFORE CLIENT DELIVERY**
>
> This template combines five audit documents into one deliverable: (1) Annual Audit Program, (2) Per-Audit Plan, (3) Clause-by-Clause Checklist, (4) Finding Form, and (5) Audit Report Template. Deliver the full package to the client; they will populate each section as audits are planned and executed.
>
> **Before delivery:**
> - Replace all `[bracketed placeholders]` with client-specific values
> - Confirm the client's AI system inventory is complete — the checklist references specific AI systems by name in several places; add system names where indicated
> - Confirm the client's SoA is finalized — the Annex A checklist section should reflect only applicable controls per the client's SoA; mark N/A for excluded controls with the SoA exclusion justification
> - For SMBs without a dedicated internal auditor: recommend using a department head from a non-AI-using function (e.g., Finance or Legal) as lead auditor, supplemented by external consultant support for the first audit cycle
> - The most common first-audit findings are: (a) SoA not complete or missing justifications, (b) training records absent or informal, (c) impact assessments not conducted for all High Risk systems, (d) management review not formally documented. Flag these areas for extra attention during audit preparation.
> - Audit frequency: minimum annual per Clause 9.2. Trigger-based audits (significant AI system change, incident, new high-risk AI system) should be added to the program as they arise.
> - Clause traceability: this entire document implements ISO/IEC 42001:2023 Clause 9.2 (Internal Audit).

---

## Document Metadata

| Field | Value |
|---|---|
| **Document ID** | AIMS-AUDIT-001 |
| **Version** | 1.0 |
| **Date** | [YYYY-MM-DD] |
| **Organization** | [Organization Name] |
| **Audit Program Owner** | [Name — AIMS Owner / Management Representative] |
| **Next Review Date** | [YYYY-MM-DD — no later than 12 months from Date] |
| **ISO Standard** | ISO/IEC 42001:2023 |
| **Clause Reference** | Clause 9.2 — Internal Audit |

---

> **Legal Disclaimer:** This template does not constitute legal advice and does not guarantee certification outcomes. ISO/IEC 42001:2023 certification decisions are made solely by accredited certification bodies. Organizations should seek qualified legal counsel for regulatory compliance questions and engage an accredited certification body for formal conformity assessment. This template is provided as a practical implementation aid for organizations building an AI Management System (AIMS).

---

## Table of Contents

1. [Part 1: Annual Audit Program](#part-1-annual-audit-program)
2. [Part 2: Audit Plan (Per Audit)](#part-2-audit-plan-per-audit)
3. [Part 3: Audit Checklist — Clause by Clause](#part-3-audit-checklist--clause-by-clause)
4. [Part 4: Audit Finding Form](#part-4-audit-finding-form)
5. [Part 5: Audit Report Template](#part-5-audit-report-template)
6. [Version History](#version-history)

---

## Part 1: Annual Audit Program

### 1.1 Purpose

The Annual Audit Program establishes the organization's planned internal audit activities for the AIMS over a 12-month period. It ensures that all AIMS clauses (4–10) and all applicable Annex A controls are audited at least once per year, that audit resources are allocated in advance, and that audit results feed into the management review process as required by ISO/IEC 42001:2023 Clause 9.3.

The audit program is a living document. It is updated when trigger-based audits are added, when planned audits are rescheduled, or when scope changes occur.

### 1.2 Audit Frequency

| Audit Type | Minimum Frequency | Trigger |
|---|---|---|
| **Full AIMS Audit** | Annual (once per 12-month cycle) | Calendar-based; required for certification maintenance |
| **Focused Audit — New AI System** | Within 90 days of deployment | Any new AI system added to the AIMS scope |
| **Focused Audit — Significant Change** | Within 60 days of change | Material change to an existing in-scope AI system (new use case, new data inputs, vendor change) |
| **Focused Audit — Incident** | Within 30 days of incident closure | AI-related incident classified as High severity or involving a data breach |
| **Focused Audit — Regulatory Change** | Within 90 days of effective date | New or amended regulation materially affecting AI governance obligations |

### 1.3 Audit Scope

The annual audit program covers:

- **AIMS Clauses:** All normative clauses of ISO/IEC 42001:2023 (Clauses 4 through 10)
- **Annex A Controls:** All controls marked as Applicable in the organization's Statement of Applicability (AIMS-SOA-001)
- **Organizational Units:** All departments and functions within the AIMS scope boundary as defined in the AIMS Scope Statement (AIMS-SCOPE-001)
- **AI Systems:** All AI systems listed in the AI System Inventory (AIMS-INV-001) with status "Active" or "Pilot"
- **Documented Information:** All AIMS policies, procedures, records, and registers required by ISO/IEC 42001:2023

### 1.4 Auditor Independence Requirement

**Auditors must not audit their own work.** This is a fundamental requirement of ISO/IEC 42001:2023 Clause 9.2 and a basic principle of audit integrity.

| Situation | Requirement |
|---|---|
| Internal auditor is also the AIMS Owner | Assign a different auditor for Clause 5 (Leadership) and Clause 6 (Planning) sections |
| Internal auditor works in IT and manages AI tools | Assign a different auditor for Clause 8 (Operation) and Annex A.6 (AI System Life Cycle) sections |
| No independent internal auditor available | Engage an external consultant or qualified third party to conduct the audit or specific audit sections |
| Small organization (fewer than 20 employees) | Document the independence rationale; consider using a board member, external advisor, or peer organization auditor |

**Auditor Qualification Minimum:** Lead auditors should have completed ISO management system auditor training (ISO 19011 principles) and have familiarity with AI governance concepts. ISO 42001-specific training is strongly recommended but not required if the auditor has ISO 27001 or ISO 9001 audit experience and reviews this checklist thoroughly before the audit.

### 1.5 Annual Audit Schedule

Complete this table at the start of each audit year. Update Status as audits progress.

| Audit ID | Audit Scope | Planned Date | Lead Auditor | Auditees | Status |
|---|---|---|---|---|---|
| AUD-[YYYY]-001 | Full AIMS — Clauses 4–10 + All Applicable Annex A Controls | [YYYY-MM-DD] | [Name] | [Department Heads, AIMS Owner] | Planned |
| AUD-[YYYY]-002 | Focused — [AI System Name] New Deployment | [YYYY-MM-DD] | [Name] | [IT Lead, System Owner] | Planned |
| AUD-[YYYY]-003 | [Add trigger-based audits as they arise] | [YYYY-MM-DD] | [Name] | [TBD] | Planned |

### 1.6 Audit Program Review

The Audit Program Owner reviews this program:
- **Annually** — before the start of each new audit cycle, to confirm scope, schedule, and auditor assignments
- **After each completed audit** — to incorporate lessons learned and update the schedule if needed
- **After any trigger event** — to add a focused audit to the schedule

---

## Part 2: Audit Plan (Per Audit)

*Complete one Audit Plan for each audit listed in the Annual Audit Schedule. The Audit Plan is shared with auditees at least 2 weeks before the audit date.*

### Audit Plan — [Audit ID: AUD-[YYYY]-XXX]

| Field | Detail |
|---|---|
| **Audit ID** | AUD-[YYYY]-XXX |
| **Audit Title** | [e.g., Annual AIMS Internal Audit — FY2026] |
| **Audit Scope** | [e.g., Full AIMS — ISO/IEC 42001:2023 Clauses 4–10 and all applicable Annex A controls as listed in AIMS-SOA-001] |
| **Audit Objectives** | 1. Determine whether the AIMS conforms to the requirements of ISO/IEC 42001:2023. 2. Determine whether the AIMS is effectively implemented and maintained. 3. Identify opportunities for improvement. |
| **Audit Criteria** | ISO/IEC 42001:2023 (normative requirements); Organization's AIMS documentation set (policies, procedures, registers); Applicable legal and regulatory requirements |
| **Audit Methods** | Interview (I) / Document Review (DR) / Observation (OB) — method specified per checklist item |
| **Audit Date(s)** | [YYYY-MM-DD] to [YYYY-MM-DD] |
| **Lead Auditor** | [Name, Role] |
| **Supporting Auditor(s)** | [Name, Role — if applicable] |
| **Observer(s)** | [Name, Role — e.g., Certification Body Observer, if applicable] |
| **Auditees** | [List names and roles of all personnel to be interviewed] |
| **Opening Meeting** | [Date, Time, Location/Video Link] |
| **Closing Meeting** | [Date, Time, Location/Video Link] |
| **Report Due Date** | [YYYY-MM-DD — typically within 10 business days of closing meeting] |

### 2.1 Audit Schedule (Day-by-Day)

| Date/Time | Activity | Auditor | Auditee(s) | Location |
|---|---|---|---|---|
| [Date] 09:00 | Opening Meeting — Introductions, scope confirmation, logistics | Lead Auditor | All auditees | [Room/Link] |
| [Date] 09:30 | Clause 4 & 5 — Context and Leadership | Lead Auditor | AIMS Owner, CEO/Executive Sponsor | [Room/Link] |
| [Date] 11:00 | Clause 6 — Planning (Risk Assessment, SoA, Objectives) | Lead Auditor | AIMS Owner, Risk Owner | [Room/Link] |
| [Date] 13:00 | Clause 7 — Support (Competence, Training, Documentation) | Lead Auditor | HR Lead, AIMS Owner | [Room/Link] |
| [Date] 14:30 | Clause 8 — Operation (AI System Controls, Acceptable Use) | Lead Auditor | IT Lead, Department Heads | [Room/Link] |
| [Date+1] 09:00 | Clause 9 — Performance Evaluation (Monitoring, Audit Records, Mgmt Review) | Lead Auditor | AIMS Owner | [Room/Link] |
| [Date+1] 10:30 | Clause 10 — Improvement (NCARs, Corrective Actions) | Lead Auditor | AIMS Owner | [Room/Link] |
| [Date+1] 11:30 | Annex A Controls — Spot-check of applicable controls | Lead Auditor | IT Lead, Department Heads | [Room/Link] |
| [Date+1] 14:00 | Auditor working session — Finding consolidation, report drafting | Lead Auditor | (No auditees) | [Room/Link] |
| [Date+1] 15:30 | Closing Meeting — Preliminary findings presentation | Lead Auditor | All auditees | [Room/Link] |

### 2.2 Documents to Request Before the Audit

Request the following documents from the AIMS Owner at least 5 business days before the audit:

| Document | Document ID | Purpose |
|---|---|---|
| AIMS Scope Statement | AIMS-SCOPE-001 | Confirm audit boundary |
| AI Policy | AIMS-POL-001 | Clause 5 and A.2 audit |
| AI System Inventory | AIMS-INV-001 | Confirm in-scope systems |
| Statement of Applicability | AIMS-SOA-001 | Confirm applicable controls |
| Risk Assessment Register | AIMS-RISK-001 | Clause 6 and A.5 audit |
| Risk Treatment Plan | AIMS-RTP-001 | Clause 6 audit |
| Impact Assessment records | AIMS-IA-[XXX] | A.5 audit |
| Training records | [HR system or document] | Clause 7 and A.4 audit |
| Acceptable Use Policy | AIMS-AUP-001 | Clause 8 and A.9 audit |
| Monitoring/KPI reports | [As available] | Clause 9 audit |
| Previous audit report | AUD-[YYYY-1]-001 | Clause 10 — follow-up on prior findings |
| NCAR log | AIMS-NCAR-LOG | Clause 10 audit |
| Management review minutes | [Meeting records] | Clause 9.3 audit |
| Supplier assessment records | [Vendor files] | A.10 audit |

---

## Part 3: Audit Checklist — Clause by Clause

### How to Use This Checklist

- Complete one row per audit question during the audit
- **Finding codes:** C = Conforming | MiNC = Minor Nonconformity | MaNC = Major Nonconformity | OBS = Observation (opportunity for improvement, no nonconformity) | N/A = Not Applicable
- A **Minor Nonconformity** is a single lapse or isolated failure that does not indicate a systemic breakdown
- A **Major Nonconformity** is a systemic failure, complete absence of a required element, or a situation that would prevent the AIMS from achieving its intended outcomes
- Record objective evidence (document references, interviewee statements, observations) in the Evidence/Notes field
- If a question is not applicable to this audit's scope, mark N/A and note the reason

---

### Clause 4 — Context of the Organization

*Requirement: The organization shall determine external and internal issues relevant to its purpose and that affect its ability to achieve the intended outcomes of its AIMS (Clause 4.1). The organization shall determine interested parties and their requirements (Clause 4.2). The organization shall determine the scope of the AIMS (Clause 4.3). The organization shall establish, implement, maintain, and continually improve the AIMS (Clause 4.4).*

| # | Audit Question | Method | Evidence to Request | Finding | Notes / Objective Evidence |
|---|---|---|---|---|---|
| 4.1 | Has the organization documented its internal and external context relevant to AI use, including regulatory environment, organizational culture, and technology landscape? | DR | Context analysis document or equivalent section in AIMS documentation | C / MiNC / MaNC / OBS / N/A | |
| 4.2 | Can the organization demonstrate it has identified all relevant interested parties (employees, customers, regulators, suppliers) and their specific requirements or expectations regarding AI? | I + DR | Interested parties register or equivalent; evidence that requirements have been captured and reviewed | C / MiNC / MaNC / OBS / N/A | |
| 4.3 | Is the AIMS scope documented, approved, and available? Does it clearly define the organizational units, locations, AI systems, and activities covered? | DR | AIMS Scope Statement (AIMS-SCOPE-001); confirm it is version-controlled and approved | C / MiNC / MaNC / OBS / N/A | |
| 4.4 | Is there evidence that the AIMS has been established, implemented, and is being maintained? Are the required AIMS documents in place and current? | DR + I | AIMS documentation set; document register; version history of key documents | C / MiNC / MaNC / OBS / N/A | |
| 4.5 | Does the AIMS scope exclude any organizational units or AI systems? If so, is the exclusion justified and documented? | DR | Scope Statement exclusion rationale; confirm excluded systems are not in the AI System Inventory as Active | C / MiNC / MaNC / OBS / N/A | |

---

### Clause 5 — Leadership

*Requirement: Top management shall demonstrate leadership and commitment to the AIMS (Clause 5.1), establish an AI Policy (Clause 5.2), and ensure roles, responsibilities, and authorities are assigned (Clause 5.3).*

| # | Audit Question | Method | Evidence to Request | Finding | Notes / Objective Evidence |
|---|---|---|---|---|---|
| 5.1 | Can top management demonstrate commitment to the AIMS? Is there evidence of resource allocation, active participation in management review, and communication of AI governance importance? | I | Management review minutes; budget records for AIMS activities; communications from leadership on AI governance | C / MiNC / MaNC / OBS / N/A | |
| 5.2 | Is there an approved AI Policy signed by top management? Does it include the organization's commitment to responsible AI, the AIMS scope, and a framework for AI objectives? | DR | AI Policy (AIMS-POL-001); confirm approval signature, date, and version number | C / MiNC / MaNC / OBS / N/A | |
| 5.3 | Does the AI Policy address responsible AI topics including fairness, transparency, accountability, human oversight, privacy, safety, and societal impact? | DR | AI Policy — review content against responsible AI requirements (A.2.3) | C / MiNC / MaNC / OBS / N/A | |
| 5.4 | Are AI governance roles and responsibilities formally assigned? Is there a documented AIMS Owner / Management Representative with defined authority? | DR + I | Role assignment document, org chart, or AIMS procedure; interview AIMS Owner to confirm understanding of responsibilities | C / MiNC / MaNC / OBS / N/A | |
| 5.5 | Are AI system owners assigned for each in-scope AI system? Do they understand their responsibilities for risk management and operational oversight of their assigned systems? | I + DR | AI System Inventory (AIMS-INV-001) — confirm Owner field is populated; interview at least one AI system owner | C / MiNC / MaNC / OBS / N/A | |

---

### Clause 6 — Planning

*Requirement: The organization shall address risks and opportunities (Clause 6.1), conduct AI risk assessments (Clause 6.1.2), conduct AI impact assessments (Clause 6.1.4), determine applicable Annex A controls and produce a Statement of Applicability (Clause 6.1.6), develop a Risk Treatment Plan (Clause 6.1.3), and establish AI objectives (Clause 6.2).*

*Note: Clause 6 is typically the most finding-rich clause in first-cycle audits. Allocate additional audit time here.*

| # | Audit Question | Method | Evidence to Request | Finding | Notes / Objective Evidence |
|---|---|---|---|---|---|
| 6.1 | Is there a documented AI risk assessment methodology? Does it define risk criteria, risk acceptance thresholds, and the process for identifying, analyzing, and evaluating AI risks? | DR | Risk Assessment Register (AIMS-RISK-001) — methodology section; confirm criteria are defined before risk assessment results | C / MiNC / MaNC / OBS / N/A | |
| 6.2 | Has a risk assessment been conducted for all AI systems listed as Active or Pilot in the AI System Inventory? Are risk assessments current (reviewed within the past 12 months or after significant change)? | DR | Completed Risk Assessment Register; cross-reference with AI System Inventory to confirm all systems are covered | C / MiNC / MaNC / OBS / N/A | |
| 6.3 | Have impact assessments been conducted for all AI systems classified as High Risk or Medium Risk in the risk assessment? Are impact assessments documented with identified impacts, mitigations, and residual risks? | DR | Completed Impact Assessment forms (AIMS-IA-[XXX]); cross-reference with Risk Assessment Register for all High/Medium Risk systems | C / MiNC / MaNC / OBS / N/A | |
| 6.4 | Is there a Statement of Applicability (SoA) covering all 39 Annex A controls? Does it clearly indicate each control as Applicable or Not Applicable? | DR | Statement of Applicability (AIMS-SOA-001); confirm all 39 controls are listed | C / MiNC / MaNC / OBS / N/A | |
| 6.5 | Does the SoA include documented justifications for all inclusions and exclusions? Are exclusion justifications specific and defensible (not generic)? | DR | SoA — review justification column for each excluded control; flag any justification that is blank or generic | C / MiNC / MaNC / OBS / N/A | |
| 6.6 | Is there a Risk Treatment Plan documenting treatment decisions for all identified risks above the acceptance threshold? Does it identify the treatment option (mitigate/accept/transfer/avoid), the responsible owner, and the target completion date? | DR | Risk Treatment Plan (AIMS-RTP-001); confirm all High and Medium risks have documented treatment decisions | C / MiNC / MaNC / OBS / N/A | |
| 6.7 | Are AI objectives documented? Are they measurable, consistent with the AI Policy, and assigned to responsible owners with target dates? | DR | AI objectives — may be in the AI Policy, a separate objectives document, or the management review record | C / MiNC / MaNC / OBS / N/A | |
| 6.8 | Is there a documented plan for achieving AI objectives, including what will be done, what resources are required, who is responsible, and when it will be completed? | DR + I | AI objectives plan or equivalent; interview AIMS Owner on progress against objectives | C / MiNC / MaNC / OBS / N/A | |

---

### Clause 7 — Support

*Requirement: The organization shall determine and provide necessary resources (Clause 7.1), ensure competence (Clause 7.2), promote awareness (Clause 7.3), determine communication needs (Clause 7.4), and control documented information (Clause 7.5).*

| # | Audit Question | Method | Evidence to Request | Finding | Notes / Objective Evidence |
|---|---|---|---|---|---|
| 7.1 | Are AI competency requirements defined for all roles involved in AI governance, operation, and oversight? Is there a competency framework or role description that specifies required knowledge and skills? | DR | Competency framework, job descriptions, or AIMS procedure defining competency requirements by role | C / MiNC / MaNC / OBS / N/A | |
| 7.2 | Are training records maintained for all AI-related training? Do records confirm that all personnel with AI governance responsibilities have completed required training? | DR | Training records (HR system or training log); cross-reference with competency requirements and personnel list | C / MiNC / MaNC / OBS / N/A | |
| 7.3 | Has AI governance awareness been communicated to all personnel who use AI systems within the AIMS scope? Can staff demonstrate awareness of the AI Policy and their responsibilities? | I + DR | Training records; communication records (emails, intranet posts, meeting minutes); interview 2–3 staff members who use AI tools | C / MiNC / MaNC / OBS / N/A | |
| 7.4 | Has the organization determined what AI-related information needs to be communicated, to whom, when, and through what channels? Is there a communication plan or equivalent? | DR | Communication plan or equivalent; evidence of communications sent (e.g., AI Policy distribution record) | C / MiNC / MaNC / OBS / N/A | |
| 7.5 | Is AIMS documentation controlled per the document control procedure? Are documents version-controlled, approved before use, and protected from unauthorized modification? | DR | Document register; version history of key AIMS documents; confirm current versions are accessible to relevant personnel | C / MiNC / MaNC / OBS / N/A | |
| 7.6 | Are AIMS records retained for the required period and protected from loss, damage, or unauthorized access? | DR | Records retention schedule or equivalent; spot-check retention of audit records, training records, and risk assessment records | C / MiNC / MaNC / OBS / N/A | |

---

### Clause 8 — Operation

*Requirement: The organization shall plan, implement, and control the processes needed to meet AIMS requirements (Clause 8.1), conduct and update risk assessments when changes occur (Clause 8.2), and implement the risk treatment plan (Clause 8.3).*

| # | Audit Question | Method | Evidence to Request | Finding | Notes / Objective Evidence |
|---|---|---|---|---|---|
| 8.1 | Are operational processes for AI use documented and implemented? Is there an Acceptable Use Policy (AUP) that defines permitted and prohibited uses of AI systems? | DR + OB | Acceptable Use Policy (AIMS-AUP-001); operational procedures for AI use; observe actual AI tool usage if possible | C / MiNC / MaNC / OBS / N/A | |
| 8.2 | Are controls from the Risk Treatment Plan implemented and operating effectively? Select 2–3 controls from the RTP and verify implementation evidence. | DR + OB | Risk Treatment Plan; implementation evidence for selected controls (e.g., access controls, monitoring logs, vendor contracts) | C / MiNC / MaNC / OBS / N/A | |
| 8.3 | Is the risk assessment reviewed and updated when AI systems change (new system, new use case, vendor change, significant incident)? Is there evidence of triggered risk reassessments? | DR | Risk Assessment Register — review revision history; cross-reference with AI System Inventory change log | C / MiNC / MaNC / OBS / N/A | |
| 8.4 | Are impact assessments reviewed and updated when AI system use changes materially? Is there a process for triggering impact assessment reviews? | DR | Impact Assessment records — review revision history; confirm process for triggering reviews is documented | C / MiNC / MaNC / OBS / N/A | |
| 8.5 | Are outsourced processes that affect AIMS conformity identified and controlled? Are vendor contracts for AI systems reviewed for AI governance requirements? | DR | Vendor contracts for in-scope AI systems; supplier assessment records; confirm AI-specific contractual requirements are present | C / MiNC / MaNC / OBS / N/A | |

---

### Clause 9 — Performance Evaluation

*Requirement: The organization shall monitor, measure, analyze, and evaluate AIMS performance (Clause 9.1), conduct internal audits (Clause 9.2), and conduct management reviews (Clause 9.3).*

| # | Audit Question | Method | Evidence to Request | Finding | Notes / Objective Evidence |
|---|---|---|---|---|---|
| 9.1 | Are AIMS performance indicators defined and monitored? Is there evidence that monitoring results are analyzed and used to evaluate AIMS effectiveness? | DR | Monitoring records; KPI reports; AI objectives progress reports | C / MiNC / MaNC / OBS / N/A | |
| 9.2 | Has an internal audit been conducted per the audit program within the past 12 months? Was the audit conducted by an independent auditor? | DR | Previous audit report; audit program; confirm auditor independence | C / MiNC / MaNC / OBS / N/A | |
| 9.3 | Were audit findings from the previous audit cycle addressed? Is there evidence of corrective actions taken and verified for effectiveness? | DR | Previous audit report; NCAR log; closed NCARs with verification records | C / MiNC / MaNC / OBS / N/A | |
| 9.4 | Has a management review been conducted within the past 12 months with the required inputs (audit results, nonconformities, performance data, changes in context, AI objectives progress)? | DR | Management review minutes; confirm required inputs were presented and decisions/actions were recorded | C / MiNC / MaNC / OBS / N/A | |
| 9.5 | Did the management review produce documented outputs including decisions on AIMS changes, resource needs, and improvement opportunities? | DR | Management review minutes — review outputs section; confirm action items are assigned and tracked | C / MiNC / MaNC / OBS / N/A | |

---

### Clause 10 — Improvement

*Requirement: The organization shall react to nonconformities, take corrective action, and continually improve the AIMS (Clauses 10.1 and 10.2).*

| # | Audit Question | Method | Evidence to Request | Finding | Notes / Objective Evidence |
|---|---|---|---|---|---|
| 10.1 | Is there a documented process for identifying, recording, and managing nonconformities? Does the process require root cause analysis and corrective action? | DR | NCAR procedure or equivalent; NCAR log (AIMS-NCAR-LOG) | C / MiNC / MaNC / OBS / N/A | |
| 10.2 | Are corrective actions implemented and verified for effectiveness? Are closed NCARs supported by evidence of root cause elimination, not just symptom correction? | DR | Closed NCARs — review root cause analysis and verification evidence for at least 3 closed items | C / MiNC / MaNC / OBS / N/A | |
| 10.3 | Is there evidence of continual improvement in the AIMS beyond corrective action? Are improvement opportunities identified through monitoring, audit, and management review being acted upon? | I + DR | Management review outputs; improvement log or equivalent; interview AIMS Owner on improvement initiatives | C / MiNC / MaNC / OBS / N/A | |
| 10.4 | Are nonconformities communicated to relevant stakeholders as appropriate? Is there a process for escalating significant nonconformities to top management? | I + DR | NCAR log; escalation records; interview AIMS Owner on escalation process | C / MiNC / MaNC / OBS / N/A | |

---

### Annex A Controls — Domain by Domain

*Audit only the controls marked as Applicable in the organization's Statement of Applicability (AIMS-SOA-001). For each control marked Not Applicable in the SoA, mark the corresponding checklist item N/A and note the SoA exclusion justification.*

*For each applicable control, the auditor should: (1) confirm the control is implemented, (2) verify implementation evidence, and (3) assess effectiveness.*

---

#### A.2 — Policies for AI (2 Controls)

*Objective: Provide management direction and support for AI systems in accordance with business requirements, applicable laws, and responsible AI principles.*

| Control | Audit Question | Method | Evidence to Request | Finding | Notes / Objective Evidence |
|---|---|---|---|---|---|
| **A.2.2** AI Policy | Is the AI Policy current (reviewed within 12 months or after significant change), approved by top management, and communicated to all relevant personnel? | DR | AI Policy — confirm version, approval date, approval signature, and distribution record | C / MiNC / MaNC / OBS / N/A | |
| **A.2.2** AI Policy | Does the AI Policy establish the organization's approach to responsible AI, define the AIMS scope, and provide a framework for AI objectives? | DR | AI Policy — review content for required elements | C / MiNC / MaNC / OBS / N/A | |
| **A.2.3** Responsible AI Topics | Does the AI Policy explicitly address fairness, transparency, accountability, human oversight, privacy, safety, and societal impact? | DR | AI Policy — review responsible AI section; confirm all seven topics are addressed | C / MiNC / MaNC / OBS / N/A | |

---

#### A.3 — Internal Organization (3 Controls)

*Objective: Establish accountability within the organization to support a responsible approach to AI.*

| Control | Audit Question | Method | Evidence to Request | Finding | Notes / Objective Evidence |
|---|---|---|---|---|---|
| **A.3.2** Roles and Responsibilities | Are AI governance roles formally defined and assigned? Do role descriptions include AI system owners, data stewards, risk owners, and AIMS management? | DR + I | Role assignment document; org chart; interview AIMS Owner and at least one AI system owner to confirm understanding | C / MiNC / MaNC / OBS / N/A | |
| **A.3.3** Reporting of AI Concerns | Is there a documented mechanism for personnel to report AI-related ethical, safety, or compliance concerns? Is the mechanism communicated to all staff? | DR + I | Reporting procedure or equivalent; communication records; interview 2 staff members on awareness of reporting channel | C / MiNC / MaNC / OBS / N/A | |
| **A.3.4** Impact of Organizational Changes | Is there a process for assessing AI implications when the organization undergoes significant changes (restructuring, vendor changes, technology transitions)? | DR | Change management procedure or equivalent; evidence of AI impact assessment triggered by a recent organizational change (if applicable) | C / MiNC / MaNC / OBS / N/A | |

---

#### A.4 — Resources for AI Systems (5 Controls)

*Objective: Ensure the organization identifies and provides all resources required for AI systems.*

| Control | Audit Question | Method | Evidence to Request | Finding | Notes / Objective Evidence |
|---|---|---|---|---|---|
| **A.4.2** Resources | Are resources required for AI activities identified and documented? Does the organization have adequate human, technical, and financial resources to operate the AIMS? | DR + I | Resource plan or equivalent; budget records; interview AIMS Owner on resource adequacy | C / MiNC / MaNC / OBS / N/A | |
| **A.4.3** Competencies | Are competency requirements defined for all AI-related roles? Is there evidence that skill gaps have been identified and addressed through training or hiring? | DR | Competency framework; training records; gap analysis (if conducted) | C / MiNC / MaNC / OBS / N/A | |
| **A.4.4** Awareness | Are all personnel who use AI systems aware of the AI Policy, relevant risks, and their responsibilities? Can staff articulate what responsible AI use means in their role? | I | Interview 3–5 staff members who use AI tools; ask about AI Policy awareness, reporting obligations, and prohibited uses | C / MiNC / MaNC / OBS / N/A | |
| **A.4.5** Consultation | Is there evidence that relevant stakeholders are consulted when significant AI decisions are made (e.g., adopting a new AI system, changing AI use cases)? | DR + I | Meeting records; consultation records; interview AIMS Owner on consultation process | C / MiNC / MaNC / OBS / N/A | |
| **A.4.6** Communication | Is relevant information about AI systems communicated to interested parties? Do communications include AI capabilities, limitations, and intended use? | DR | Communication records; AI system documentation shared with stakeholders; customer-facing disclosures (if applicable) | C / MiNC / MaNC / OBS / N/A | |

---

#### A.5 — Assessing Impacts of AI Systems (3 Controls)

*Objective: Assess AI system impacts on individuals, groups, and society throughout the system lifecycle.*

| Control | Audit Question | Method | Evidence to Request | Finding | Notes / Objective Evidence |
|---|---|---|---|---|---|
| **A.5.2** AI System Risk Assessment | Has a formal risk assessment been conducted for each in-scope AI system? Does the assessment cover technical, organizational, ethical, and societal risk dimensions? | DR | Risk Assessment Register (AIMS-RISK-001); confirm all Active/Pilot AI systems are assessed | C / MiNC / MaNC / OBS / N/A | |
| **A.5.3** AI System Impact Assessment | Have impact assessments been conducted for AI systems that affect individuals or groups? Do assessments identify potential harms, discrimination risks, and privacy effects? | DR | Impact Assessment forms (AIMS-IA-[XXX]); confirm assessments are complete for all High and Medium Risk systems | C / MiNC / MaNC / OBS / N/A | |
| **A.5.4** Impact Assessment Documentation | Are impact assessment results documented with identified impacts, mitigations applied, and residual risks? Are impact assessments updated when AI system use changes? | DR | Impact Assessment forms — review completeness; check revision history for updates triggered by system changes | C / MiNC / MaNC / OBS / N/A | |

---

#### A.6 — AI System Life Cycle (10 Controls)

*Objective: Define criteria and requirements for each stage of the AI system life cycle.*

*Note: Controls A.6.2.2 (Design and Development) and A.6.2.3 (Training and Testing) are typically Not Applicable for AI-user organizations. Confirm against the SoA before auditing.*

| Control | Audit Question | Method | Evidence to Request | Finding | Notes / Objective Evidence |
|---|---|---|---|---|---|
| **A.6.2.2** Design and Development | [Confirm SoA applicability — typically N/A for AI users] | — | SoA exclusion justification | N/A (confirm) | |
| **A.6.2.3** Training and Testing | [Confirm SoA applicability — typically N/A for AI users] | — | SoA exclusion justification | N/A (confirm) | |
| **A.6.2.4** Verification and Validation | Is there evidence that third-party AI tools were validated against organizational requirements before adoption? Is there a pre-adoption assessment process? | DR | Pre-adoption assessment records; vendor evaluation documentation; pilot test results | C / MiNC / MaNC / OBS / N/A | |
| **A.6.2.5** Deployment | Is there a controlled deployment process for new AI systems? Does deployment include user onboarding, access control setup, and initial monitoring? | DR + I | Deployment records for recently adopted AI systems; onboarding materials; access control records | C / MiNC / MaNC / OBS / N/A | |
| **A.6.2.6** Operation and Monitoring | Are in-scope AI systems monitored for performance, output quality, and anomalies? Is there a process for identifying and escalating AI system issues? | DR + OB | Monitoring logs or reports; incident records; escalation procedure | C / MiNC / MaNC / OBS / N/A | |
| **A.6.2.7** Retirement | Is there a process for responsibly decommissioning AI systems, including data handling, access removal, and contract termination? | DR | Retirement procedure or equivalent; evidence of a completed retirement (if applicable) | C / MiNC / MaNC / OBS / N/A | |
| **A.6.2.8** Responsible Integration | Are AI systems integrated into organizational processes responsibly? Is there evidence of integration planning, testing, and validation before go-live? | DR + I | Integration planning records; test results; interview IT Lead on integration process | C / MiNC / MaNC / OBS / N/A | |
| **A.6.2.9** AI System Documentation | Is comprehensive documentation maintained for each in-scope AI system, including purpose, capabilities, limitations, operating parameters, and vendor SLA details? | DR | AI System Inventory (AIMS-INV-001); system-specific documentation; vendor documentation | C / MiNC / MaNC / OBS / N/A | |
| **A.6.2.10** Defined Use and Misuse | Are intended uses and explicitly prohibited uses of AI systems defined and communicated to all users? Is there an Acceptable Use Policy that covers all in-scope AI systems? | DR + I | Acceptable Use Policy (AIMS-AUP-001); confirm all in-scope systems are covered; interview staff on awareness of prohibited uses | C / MiNC / MaNC / OBS / N/A | |
| **A.6.2.11** Third-Party AI Management | Are third-party AI system components managed through defined selection criteria, contractual requirements, and ongoing performance monitoring? | DR | Supplier assessment records; vendor contracts; ongoing monitoring evidence | C / MiNC / MaNC / OBS / N/A | |

---

#### A.7 — Data for AI Systems (5 Controls)

*Objective: Ensure the organization understands the role and impacts of data in AI systems and manages data appropriately.*

*Note: Several A.7 controls are Partially Applicable for AI-user organizations. Confirm applicability against the SoA for each control.*

| Control | Audit Question | Method | Evidence to Request | Finding | Notes / Objective Evidence |
|---|---|---|---|---|---|
| **A.7.2** Data for Development | [Confirm SoA applicability — applies only if organization provides data for AI fine-tuning or customization] | DR | SoA applicability determination; if applicable: data management records for fine-tuning data | C / MiNC / MaNC / OBS / N/A | |
| **A.7.3** Data Quality | Are data quality requirements defined for data inputs to AI systems? Is there evidence that input data quality is monitored and maintained? | DR + I | Data quality requirements documentation; data quality monitoring records; interview IT Lead or data owner | C / MiNC / MaNC / OBS / N/A | |
| **A.7.4** Data Preparation | Is organizational data properly prepared before input to AI systems (cleaning, formatting, privacy screening)? Is there a data preparation procedure? | DR | Data preparation procedure or equivalent; evidence of data preparation activities | C / MiNC / MaNC / OBS / N/A | |
| **A.7.5** Data Acquisition and Collection | Is data collected for AI use acquired responsibly, with appropriate consent and privacy protections? | DR | Data collection procedures; privacy notices; consent records (if applicable) | C / MiNC / MaNC / OBS / N/A | |
| **A.7.6** Data Provenance | Is the origin and lineage of organizational data used as AI inputs tracked and documented? | DR | Data provenance records or equivalent; data flow diagrams | C / MiNC / MaNC / OBS / N/A | |

---

#### A.8 — Information for Interested Parties (4 Controls)

*Objective: Ensure interested parties have the information needed to understand and assess AI system risks.*

| Control | Audit Question | Method | Evidence to Request | Finding | Notes / Objective Evidence |
|---|---|---|---|---|---|
| **A.8.2** Informing About AI Interaction | Are individuals notified when they are interacting with an AI system? Are disclosure mechanisms in place (e.g., chatbot labels, AI-generated content notices)? | DR + OB | Disclosure notices; customer-facing communications; observe AI-powered interfaces for disclosure labels | C / MiNC / MaNC / OBS / N/A | |
| **A.8.3** Informing About AI Outcomes | When AI outputs influence decisions affecting individuals (hiring, pricing, service), is there a mechanism to communicate the AI's role and key decision factors? | DR + I | Decision communication templates; AI outcome explanation records; interview relevant department head | C / MiNC / MaNC / OBS / N/A | |
| **A.8.4** Access to Interaction Records | Are records of AI system interactions maintained and accessible as required by law, contract, or policy? Is there a process for responding to access requests? | DR | Interaction log retention policy; access request procedure; sample interaction records | C / MiNC / MaNC / OBS / N/A | |
| **A.8.5** Enabling Human Action | Do staff acting on AI recommendations receive sufficient context (confidence levels, caveats, limitations) to exercise informed judgment? | I + DR | AI output documentation; user guidance materials; interview staff who act on AI recommendations | C / MiNC / MaNC / OBS / N/A | |

---

#### A.9 — Use of AI Systems (4 Controls)

*Objective: Ensure the organization uses AI systems responsibly and in accordance with its AI Policy.*

| Control | Audit Question | Method | Evidence to Request | Finding | Notes / Objective Evidence |
|---|---|---|---|---|---|
| **A.9.2** Objectives for Responsible Use | Are measurable objectives for responsible AI use defined and monitored? Do objectives address fairness, transparency, and accountability in AI use? | DR | AI objectives documentation; monitoring records showing progress against objectives | C / MiNC / MaNC / OBS / N/A | |
| **A.9.3** Intended Use | Are AI systems used within their intended parameters? Is there evidence that scope creep (using AI tools for unvalidated purposes) is monitored and controlled? | I + DR | Acceptable Use Policy; monitoring records; interview department heads on AI tool usage patterns | C / MiNC / MaNC / OBS / N/A | |
| **A.9.4** Processes for Responsible Use | Are operational processes for responsible AI use established, including review procedures, escalation paths, and human checkpoints? | DR + OB | Operational procedures; escalation records; observe AI-assisted workflows for human review checkpoints | C / MiNC / MaNC / OBS / N/A | |
| **A.9.5** Human Oversight | Is appropriate human oversight of AI systems implemented? Are override capabilities, intervention points, and oversight levels (human-in-the-loop, human-on-the-loop, human-in-command) defined for each AI system? | DR + I | Human oversight procedure; AI System Inventory — oversight level field; interview staff on override capability awareness | C / MiNC / MaNC / OBS / N/A | |

---

#### A.10 — Third-Party and Customer Relationships (3 Controls)

*Objective: Ensure responsibilities and risks are appropriately managed when third parties are involved in the AI value chain.*

*Note: Control A.10.4 (Provision of AI to Third Parties) is typically Not Applicable for AI-user organizations. Confirm against the SoA.*

| Control | Audit Question | Method | Evidence to Request | Finding | Notes / Objective Evidence |
|---|---|---|---|---|---|
| **A.10.2** Suppliers of AI Components | Are AI component suppliers managed through defined selection criteria, contractual requirements, and ongoing performance monitoring? Is there a supplier assessment for each AI vendor? | DR | Supplier assessment records; vendor contracts; ongoing monitoring evidence; confirm all AI vendors in the inventory have assessments | C / MiNC / MaNC / OBS / N/A | |
| **A.10.3** Shared ML Models | [Confirm SoA applicability — applies if organization uses open-source or shared pre-trained models] If applicable: Are shared models assessed for provenance, suitability, limitations, and bias characteristics before use? | DR | SoA applicability determination; if applicable: model assessment records for shared/open-source models in use | C / MiNC / MaNC / OBS / N/A | |
| **A.10.4** Provision to Third Parties | [Confirm SoA applicability — typically N/A for AI users who do not provide AI to others] | — | SoA exclusion justification; confirm client does not embed AI outputs in services delivered to customers | N/A (confirm) | |

---

## Part 4: Audit Finding Form

*Complete one Finding Form for each nonconformity or observation identified during the audit. Attach to the Audit Report. Conforming items do not require a Finding Form.*

---

### Finding Form — [Finding ID: AUD-[YYYY]-XXX-F[##]]

| Field | Detail |
|---|---|
| **Finding ID** | AUD-[YYYY]-XXX-F[##] (e.g., AUD-2026-001-F01) |
| **Audit ID** | AUD-[YYYY]-XXX |
| **Date Identified** | [YYYY-MM-DD] |
| **Auditor** | [Name] |
| **Clause / Control** | [e.g., Clause 6.1.4 / A.5.3 — AI System Impact Assessment] |
| **Finding Type** | ☐ Major Nonconformity ☐ Minor Nonconformity ☐ Observation |

#### Finding Description

*State the finding clearly and factually. Describe what was found, not what should have been found. Avoid opinion or interpretation.*

> [Example: The organization has not conducted an impact assessment for AI System "Salesforce Einstein Lead Scoring," which is classified as High Risk in the Risk Assessment Register (AIMS-RISK-001, Row 4). The SoA (AIMS-SOA-001) marks control A.5.3 as Applicable. No impact assessment document exists for this system.]

#### Objective Evidence

*List the specific documents reviewed, statements made, or observations made that support the finding. Be precise — reference document IDs, version numbers, and page/section numbers where possible.*

> [Example: AI System Inventory (AIMS-INV-001, v1.2, Row 4) — Salesforce Einstein Lead Scoring, Risk Level: High. Risk Assessment Register (AIMS-RISK-001, v1.1, Row 4) — confirms High Risk classification. Impact Assessment folder — no document found for this system. AIMS Owner confirmed in interview (2026-03-15) that impact assessment has not been initiated for this system.]

#### ISO 42001 Requirement

*State the specific requirement that has not been met.*

> [Example: ISO/IEC 42001:2023 Clause 6.1.4 requires the organization to conduct an AI system impact assessment. Annex A control A.5.3 requires evaluation of impacts on individuals and groups, including potential harms, discrimination, and privacy effects.]

#### Proposed Corrective Action (Auditee to Complete)

| Field | Detail |
|---|---|
| **Root Cause** | [To be completed by auditee — what caused this nonconformity?] |
| **Immediate Correction** | [To be completed by auditee — what will be done to fix the specific instance?] |
| **Corrective Action** | [To be completed by auditee — what will be done to prevent recurrence?] |
| **Responsible Owner** | [Name, Role] |
| **Target Completion Date** | [YYYY-MM-DD] |
| **Verification Method** | [How will the auditor verify that the corrective action is effective?] |

#### Finding Closure

| Field | Detail |
|---|---|
| **Closure Date** | [YYYY-MM-DD] |
| **Verification Evidence** | [Document references or observations confirming corrective action effectiveness] |
| **Closed By** | [Auditor Name] |
| **Status** | ☐ Open ☐ Closed — Effective ☐ Closed — Partially Effective (re-open) |

---

*Copy this Finding Form for each additional finding. Number sequentially: F01, F02, F03...*

---

## Part 5: Audit Report Template

*The Audit Report is the formal output of the internal audit. It is submitted to the AIMS Owner and top management, and retained as a required AIMS record. It serves as a key input to the management review (Clause 9.3).*

---

# AIMS Internal Audit Report

**[Organization Name]**
**Audit ID:** AUD-[YYYY]-XXX
**Report Date:** [YYYY-MM-DD]
**Report Status:** ☐ Draft ☐ Final

---

### Section 1: Audit Summary

| Field | Detail |
|---|---|
| **Audit Title** | [e.g., Annual AIMS Internal Audit — FY2026] |
| **Audit Scope** | [e.g., ISO/IEC 42001:2023 Clauses 4–10 and all applicable Annex A controls per AIMS-SOA-001 v[X.X]] |
| **Audit Objectives** | 1. Determine AIMS conformity with ISO/IEC 42001:2023. 2. Determine AIMS effective implementation and maintenance. 3. Identify improvement opportunities. |
| **Audit Criteria** | ISO/IEC 42001:2023; AIMS documentation set; applicable legal and regulatory requirements |
| **Audit Dates** | [YYYY-MM-DD] to [YYYY-MM-DD] |
| **Lead Auditor** | [Name, Role] |
| **Supporting Auditor(s)** | [Name, Role — if applicable] |
| **Auditees** | [List all personnel interviewed, with name and role] |
| **Audit Methods Used** | Document Review, Interview, Observation |

---

### Section 2: Overall Conformity Assessment

*The auditor's overall assessment of AIMS conformity based on audit findings.*

| Assessment | Description | Select |
|---|---|---|
| **Conforming** | No major nonconformities identified. AIMS is effectively implemented and maintained. Minor nonconformities and observations noted for improvement. | ☐ |
| **Conditionally Conforming** | Minor nonconformities identified. AIMS is substantially implemented but requires corrective action in specific areas. Certification readiness is achievable with targeted remediation. | ☐ |
| **Not Conforming** | One or more major nonconformities identified. AIMS has significant gaps that must be resolved before certification audit. | ☐ |

**Overall Assessment Narrative:**

> [Provide a 2–4 sentence summary of the overall AIMS conformity status. Example: "The organization has established a substantially conforming AIMS with clear leadership commitment and a well-documented AI Policy. The primary gap identified is the incomplete impact assessment program — three of five High Risk AI systems lack completed impact assessments. Corrective action in this area is required before the Stage 2 certification audit. All other clauses demonstrated conformity with minor observations noted for improvement."]

---

### Section 3: Findings Summary

#### 3.1 Findings by Severity

| Finding Type | Count |
|---|---|
| Major Nonconformities | [#] |
| Minor Nonconformities | [#] |
| Observations | [#] |
| **Total Findings** | **[#]** |

#### 3.2 Findings by Clause / Control

| Finding ID | Clause / Control | Finding Type | Brief Description | Status |
|---|---|---|---|---|
| AUD-[YYYY]-XXX-F01 | [e.g., Clause 6.1.4 / A.5.3] | [Major NC / Minor NC / OBS] | [One-sentence description] | Open |
| AUD-[YYYY]-XXX-F02 | [e.g., Clause 7.2 / A.4.3] | [Major NC / Minor NC / OBS] | [One-sentence description] | Open |
| AUD-[YYYY]-XXX-F03 | [e.g., A.9.5] | [Major NC / Minor NC / OBS] | [One-sentence description] | Open |
| [Add rows as needed] | | | | |

---

### Section 4: Detailed Findings

*Include one subsection per finding. Reference the corresponding Finding Form (Part 4) for full detail.*

#### Finding AUD-[YYYY]-XXX-F01 — [Brief Title]

- **Clause / Control:** [e.g., Clause 6.1.4 / A.5.3 — AI System Impact Assessment]
- **Finding Type:** [Major Nonconformity / Minor Nonconformity / Observation]
- **Description:** [Full finding description — copy from Finding Form]
- **Objective Evidence:** [Evidence summary — copy from Finding Form]
- **Required Action:** [Corrective action required — reference Finding Form for detail]
- **Target Date:** [YYYY-MM-DD]

#### Finding AUD-[YYYY]-XXX-F02 — [Brief Title]

- **Clause / Control:** [Clause / Control reference]
- **Finding Type:** [Finding type]
- **Description:** [Finding description]
- **Objective Evidence:** [Evidence summary]
- **Required Action:** [Required action]
- **Target Date:** [YYYY-MM-DD]

*[Add sections for each additional finding]*

---

### Section 5: Positive Observations

*Document what the organization is doing well. Positive observations are not findings — they are evidence of effective AIMS implementation that should be recognized and maintained.*

| Area | Positive Observation |
|---|---|
| [e.g., Leadership Commitment] | [e.g., Top management demonstrated strong awareness of AI governance obligations and could articulate the organization's AI Policy commitments without prompting.] |
| [e.g., AI System Inventory] | [e.g., The AI System Inventory is comprehensive, current, and well-maintained. All Active systems have assigned owners and current risk classifications.] |
| [e.g., Acceptable Use Policy] | [e.g., The Acceptable Use Policy is clear, specific, and staff demonstrated strong awareness of prohibited AI uses during interviews.] |
| [Add rows as needed] | |

---

### Section 6: Certification Readiness Assessment

*This section provides the auditor's assessment of the organization's readiness for the ISO/IEC 42001:2023 Stage 2 certification audit. It is advisory only — certification decisions are made by the accredited certification body.*

| Readiness Indicator | Status | Notes |
|---|---|---|
| All AIMS clauses (4–10) audited and assessed | ☐ Yes ☐ No | |
| No major nonconformities outstanding | ☐ Yes ☐ No | |
| All minor nonconformities have corrective action plans | ☐ Yes ☐ No | |
| SoA complete with justifications for all 39 controls | ☐ Yes ☐ No | |
| Impact assessments complete for all High Risk AI systems | ☐ Yes ☐ No | |
| Management review conducted within past 12 months | ☐ Yes ☐ No | |
| Training records complete for all AI governance roles | ☐ Yes ☐ No | |
| Previous audit findings closed or in progress | ☐ Yes ☐ No | |

**Certification Readiness Narrative:**

> [Provide the auditor's overall assessment of certification readiness. Be specific about what must be resolved before Stage 2 and what is already in good shape. Example: "The organization is approximately 80% ready for Stage 2 certification. The primary pre-certification actions are: (1) complete impact assessments for the three High Risk AI systems identified in Finding F01, and (2) formalize training records for the IT team as identified in Finding F02. All other AIMS elements are substantially conforming. With targeted remediation over the next 60 days, the organization should be well-positioned for Stage 2."]

---

### Section 7: Recommended Actions

| Priority | Action | Owner | Target Date |
|---|---|---|---|
| High | [e.g., Complete impact assessments for all High Risk AI systems] | [AIMS Owner] | [YYYY-MM-DD] |
| High | [e.g., Formalize training records for IT team] | [HR Lead] | [YYYY-MM-DD] |
| Medium | [e.g., Update SoA justifications for partially applicable controls] | [AIMS Owner] | [YYYY-MM-DD] |
| Low | [e.g., Consider adding KPI dashboard for AI monitoring metrics] | [IT Lead] | [YYYY-MM-DD] |

---

### Section 8: Auditor Sign-Off

| Field | Detail |
|---|---|
| **Lead Auditor Name** | [Name] |
| **Lead Auditor Signature** | _________________________ |
| **Date** | [YYYY-MM-DD] |
| **Supporting Auditor Name** | [Name — if applicable] |
| **Supporting Auditor Signature** | _________________________ |
| **Date** | [YYYY-MM-DD] |

**Distribution:**
- AIMS Owner / Management Representative
- Top Management / Executive Sponsor
- Audit file (retained as AIMS record per document retention schedule)

**Retention:** This report shall be retained for a minimum of [3 years / per organizational retention policy] as required AIMS documented information per ISO/IEC 42001:2023 Clause 9.2.

---

*By signing above, the Lead Auditor confirms that this report accurately reflects the audit findings and that the audit was conducted in accordance with the Audit Plan (AUD-[YYYY]-XXX) and ISO 19011 audit principles.*

---

## Version History

| Version | Date | Author | Changes |
|---|---|---|---|
| 1.0 | [YYYY-MM-DD] | [Author Name] | Initial release |

---

*ISO 42001 Readiness Service Toolkit | 04-Pre-Audit | Confidential Client Deliverable*
