# Nonconformity and Corrective Action Report (NCAR) Log

> **Current as of:** March 2026 | ISO/IEC 42001:2023

---

> **HOW TO CUSTOMIZE — Remove this block before client delivery**
>
> This template serves three purposes in one document: (1) a blank NCAR form for recording individual nonconformities, (2) a master register for tracking all open and closed NCARs, and (3) a focused AI incident response section. Clients use all three together.
>
> **Before delivery:**
> - Replace all `[bracketed placeholders]` with client-specific values
> - Populate the NCAR Register (Section 4) with any NCARs already identified during gap assessment or internal audit
> - Delete the five example entries in Section 4 or retain them as illustrative samples — your call, but label them clearly if you keep them
> - Confirm the escalation contacts in Section 5 match the client's actual org chart
> - The Continual Improvement Tracker (Section 6) starts empty; populate it with observations from the gap assessment that didn't rise to nonconformity level
> - The Summary Dashboard (Section 7) is a template for management review reporting — update the period and figures before each management review meeting

---

## Document Metadata

| Field | Value |
|---|---|
| **Document ID** | AIMS-NCAR-001 |
| **Version** | 1.0 |
| **Date** | [YYYY-MM-DD] |
| **Organization** | [Organization Name] |
| **Maintained By** | [AIMS Owner Name, Role] |
| **Next Review Date** | [YYYY-MM-DD — review at each management review cycle] |

---

> **Legal Disclaimer:** This template does not constitute legal advice and does not create a legal compliance obligation beyond what applicable law and regulation already impose. It is provided as a practical tool to support ISO/IEC 42001:2023 implementation. Organizations should seek qualified legal counsel for advice on regulatory obligations specific to their jurisdiction and industry.

---

## Clause Traceability

| ISO 42001 Clause | Requirement |
|---|---|
| **Clause 10.1** | Nonconformity and corrective action — organizations must react to nonconformities, take action to control and correct them, evaluate the need for corrective action to eliminate root causes, and retain documented information as evidence |
| **Clause 10.2** | Continual improvement — organizations must continually improve the suitability, adequacy, and effectiveness of the AIMS |
| **Clause 9.3** | Management review inputs — status of nonconformities and corrective actions is a required input to management review |

---

## Section 1: Purpose and Scope

### What This Document Does

This NCAR Log is the organization's central record for identifying, tracking, and resolving nonconformities in its AI Management System (AIMS). It covers the full lifecycle of a nonconformity: from initial identification through root cause analysis, corrective action, and verification of effectiveness.

Every nonconformity raised against the AIMS, whether by an internal auditor, an external certification auditor, management review, or any employee, is recorded here. The log feeds directly into management review (Clause 9.3) and provides the evidence base that demonstrates continual improvement (Clause 10.2).

### What Counts as a Nonconformity

A nonconformity is the non-fulfillment of a requirement. In an AIMS context, that means a failure to meet:

- A requirement of ISO/IEC 42001:2023 (any clause or applicable Annex A control)
- The organization's own documented policies, procedures, or objectives
- Legal, regulatory, or contractual requirements the organization has committed to

Not every gap or weakness is a nonconformity. An auditor's suggestion for improvement, a process that works but could work better, or a risk that is accepted and documented — none of these are nonconformities. They are opportunities for improvement and belong in the Continual Improvement Tracker (Section 6).

### Correction vs. Corrective Action

This distinction matters to auditors and it matters operationally.

**Correction** is the immediate fix. The symptom is addressed. If a required training record is missing, the correction is to complete the training and file the record. Correction stops the bleeding.

**Corrective action** is the root cause fix. It asks why the nonconformity happened and what will prevent it from happening again. If training records were missing because there's no process for tracking completion, the corrective action is to establish that process. Corrective action prevents recurrence.

ISO 42001 Clause 10.1 requires both. An NCAR that only documents the correction, without addressing root cause, will not satisfy an auditor.

### Who Can Raise an NCAR

Anyone. Nonconformities can be identified and raised by:

- Internal auditors during scheduled or ad hoc internal audits
- External auditors (certification body) during Stage 1 or Stage 2 audit
- Management during management review
- Any employee who identifies a failure to meet a requirement
- The AIMS Owner during routine monitoring
- Customers or suppliers who report a failure

There is no penalty for raising an NCAR. The AIMS depends on people surfacing problems. A culture where employees hesitate to raise nonconformities is itself a governance risk.

### How NCARs Feed Continual Improvement

The NCAR log is not just a compliance record. Patterns in the log reveal systemic weaknesses. If multiple NCARs trace back to the same root cause (inadequate training, unclear ownership, missing procedure), that pattern is an input to strategic improvement planning. Management review uses the NCAR summary (Section 7) to identify these patterns and direct resources accordingly.

---

## Section 2: NCAR Classification

Every NCAR is assigned one of four classifications at the time it is raised. Classification may be revised as investigation proceeds.

### Major Nonconformity

The absence of, or total breakdown of, a required AIMS element. A major nonconformity indicates that the management system is not functioning in a material area. Examples include: no documented AI policy, no impact assessment for a High Risk AI system, no internal audit conducted in the past 12 months.

**Certification impact:** A major nonconformity raised during Stage 2 audit must be resolved before the certification body will grant certification. It is not a disqualification, but it is a hard stop until closed.

### Minor Nonconformity

An isolated failure or lapse in an otherwise functioning AIMS element. The system exists and generally works, but a specific instance did not meet the requirement. Examples include: one employee's training record missing from an otherwise complete training program, a supplier assessment completed 45 days late in an otherwise active supplier management process.

**Certification impact:** Minor nonconformities do not block certification. The certification body will require a corrective action plan and will verify closure at the next surveillance audit.

### Observation

Not a nonconformity. An observation is an auditor's note that a process or control, while currently meeting requirements, shows a pattern or trend that could lead to a nonconformity if not addressed. Observations are recorded in the Continual Improvement Tracker (Section 6), not in the NCAR Register.

### AI Incident

An event where an AI system produced harmful, incorrect, or unexpected outputs with actual or potential impact on individuals, the organization, or third parties. AI incidents are a special category because they may require immediate response actions before root cause analysis is complete.

Every AI incident generates an NCAR at minimum Minor classification. Incidents with actual harm to individuals or significant organizational impact are classified Major. See Section 5 for the AI Incident Response process.

---

## Section 3: Individual NCAR Form

Use one copy of this form for each nonconformity. Assign a unique NCAR ID in the format `NCAR-YYYY-NNN` (e.g., NCAR-2026-001). File completed forms in the AIMS document repository and record the summary in the NCAR Register (Section 4).

---

**NCAR ID:** `NCAR-[YYYY]-[NNN]`

| Field | Value |
|---|---|
| **Date Raised** | [YYYY-MM-DD] |
| **Raised By** | [Name, Role] |
| **Source** | [Internal Audit / External Audit / Management Review / AI Incident / Self-Identified / Customer Complaint / Supplier Report] |
| **Classification** | [Major / Minor / AI Incident] |
| **ISO 42001 Clause / Control Reference** | [e.g., Clause 7.2 / A.6.2.10 / Clause 6.1.4] |

---

**Description of Nonconformity**

*What was found? What specific requirement was not met? Be precise: name the clause or control, describe the evidence reviewed, and state clearly what was missing or failed.*

[Describe the nonconformity here. Include: what was observed, what requirement it relates to, and what evidence was reviewed.]

---

**Immediate Correction**

*What was done right away to address the immediate problem? This is the symptom fix, not the root cause fix.*

[Describe the correction taken. Include: who took the action, what was done, and when it was completed.]

**Correction Completed Date:** [YYYY-MM-DD]

---

**Root Cause Analysis**

*Why did this happen? Use 5-Why analysis or a fishbone (Ishikawa) diagram to identify the underlying cause. Avoid stopping at the first obvious answer.*

**Method used:** [5-Why / Fishbone / Other]

[Document the root cause analysis here. For 5-Why: state the problem, then ask "why" five times, recording each answer. The fifth answer is typically the root cause. For fishbone: identify contributing factors across categories such as People, Process, Technology, and Policy.]

**Root Cause Identified:** [State the root cause in one or two sentences.]

---

**Corrective Action Plan**

*What will be done to eliminate the root cause and prevent recurrence? Be specific: name the action, the owner, and the target date.*

| Action | Owner | Target Date | Status |
|---|---|---|---|
| [Action 1] | [Name] | [YYYY-MM-DD] | [Not Started / In Progress / Complete] |
| [Action 2] | [Name] | [YYYY-MM-DD] | [Not Started / In Progress / Complete] |
| [Action 3] | [Name] | [YYYY-MM-DD] | [Not Started / In Progress / Complete] |

**Responsible Owner (overall):** [Name, Role]

**Target Completion Date:** [YYYY-MM-DD]

---

**Verification**

*How will the organization confirm that the corrective action was effective? Describe the verification method before the action is taken, not after.*

**Verification Method:** [e.g., Re-audit of the affected area; review of updated records; confirmation from affected employees; repeat testing of the control]

**Actual Completion Date:** [YYYY-MM-DD]

**Effectiveness Verified By:** [Name, Role]

**Verification Date:** [YYYY-MM-DD]

**Verification Notes:** [What evidence confirmed effectiveness?]

---

**Status:** [Open / In Progress / Closed / Verified Effective]

---

## Section 4: NCAR Register

This table is the master log of all NCARs. Update it whenever a new NCAR is raised or an existing NCAR changes status. The register is a required input to management review.

| NCAR ID | Date Raised | Source | Classification | Clause / Control | Brief Description | Owner | Target Date | Status | Closed Date |
|---|---|---|---|---|---|---|---|---|---|
| NCAR-2026-001 | 2026-01-15 | Internal Audit | Minor | Clause 7.2 | AI competency requirements not defined for IT Lead role; no documented competency criteria against which to assess current capability | HR Manager | 2026-02-28 | Closed | 2026-02-21 |
| NCAR-2026-002 | 2026-02-03 | Management Review | Minor | A.6.2.10 | Acceptable Use Policy not communicated to 3 employees hired after policy publication date; no onboarding process step for AIMS policy acknowledgment | HR Manager | 2026-03-14 | In Progress | |
| NCAR-2026-003 | 2026-02-17 | AI Incident | Major | A.9.5 | Customer service AI chatbot provided incorrect pricing information to 12 customers without human review step; no human-in-the-loop control in place for customer-facing AI outputs | Operations Manager | 2026-03-21 | Open | |
| NCAR-2026-004 | 2026-02-24 | Self-Identified | Minor | A.10.2 | Supplier assessment for [Vendor X] overdue by 45 days; no automated reminder or calendar trigger in supplier review process | IT Lead | 2026-03-31 | In Progress | |
| NCAR-2026-005 | 2026-03-01 | External Audit | Major | Clause 6.1.4 | Impact assessment not completed for HR AI screening tool despite High Risk classification assigned during inventory; no documented justification for delay | AIMS Owner | 2026-03-28 | Open | |

*The five entries above are illustrative examples. Replace with actual NCARs for [Organization Name].*

---

## Section 5: AI Incident Response

### What Constitutes an AI Incident

An AI incident is an event where an AI system within the AIMS scope produced outputs or behaviors that caused, or had the potential to cause, harm. This includes:

- Harmful, discriminatory, or materially incorrect outputs delivered to customers, employees, or third parties
- Exposure of personal or confidential data through an AI tool (e.g., sensitive data entered into a public AI service, AI tool returning another user's data)
- An AI-assisted decision that caused demonstrable harm to an individual (e.g., incorrect AI-generated recommendation acted upon without human review)
- A vendor AI system breach or service failure that affected the organization's AI-dependent processes
- An AI system operating outside its approved use case or scope

Near-misses count. If an AI system produced a harmful output that was caught before it reached anyone, that is still an incident. Document it. The near-miss is evidence that a control gap exists.

### Immediate Response Steps (First 24 Hours)

**1. Contain**
Stop or suspend the AI system's output if the harm is ongoing. If the system cannot be suspended without significant operational impact, escalate immediately to the AIMS Owner and document the decision to continue operation.

**2. Assess**
Determine the scope: How many people were affected? What data was involved? What outputs were produced? Is the harm ongoing or contained? Assign an initial severity level (High / Medium / Low) based on actual or potential impact.

**3. Notify (Internal)**
Notify the AIMS Owner within 4 hours of identification. The AIMS Owner notifies senior management within the same business day if severity is High or if personal data is involved. See escalation criteria below.

**4. Document**
Open an NCAR immediately. Every AI incident generates an NCAR. Use the NCAR form in Section 3. Classification is at minimum Minor; incidents with actual harm to individuals or significant organizational impact are classified Major.

**5. Preserve Evidence**
Retain logs, outputs, screenshots, and any other evidence of the incident before remediation steps alter the system state. Evidence preservation takes priority over cleanup.

### NCAR Creation for AI Incidents

Every AI incident generates an NCAR. There are no exceptions. The NCAR ID is assigned at the time the incident is documented and becomes the primary reference for all subsequent investigation and corrective action.

If the incident is still being assessed when the NCAR is opened, record what is known and update the form as investigation proceeds. An incomplete NCAR opened promptly is better than a complete NCAR opened late.

### Escalation Criteria

| Condition | Action | Timing |
|---|---|---|
| Any AI incident identified | Notify AIMS Owner | Within 4 hours |
| High severity incident OR personal data involved | AIMS Owner notifies senior management | Same business day |
| Personal data of individuals exposed or at risk | Assess notification obligation to affected individuals; consult legal counsel | Within 24 hours of identification |
| Incident may trigger regulatory reporting obligation (e.g., data breach under applicable privacy law) | Consult legal counsel; notify relevant regulator if required | Per applicable regulatory timeline |
| Incident involves a vendor AI system | Notify vendor per contract terms; document vendor response | Within 24 hours |

### Post-Incident Review

**Root cause analysis:** Complete within 5 business days of incident identification. Document in the NCAR form (Section 3). The root cause analysis must address why the incident occurred, not just what happened.

**Corrective action plan:** Complete within 10 business days of incident identification. The plan must address the root cause identified, not just the immediate symptom. Assign a named owner and target completion date for each action.

**Lessons learned:** At the next management review following the incident, present a summary of the incident, root cause, corrective actions taken, and any systemic changes made to prevent recurrence. This is a required management review input under Clause 9.3.

---

## Section 6: Continual Improvement Tracker

This table records improvement opportunities that do not rise to the level of a nonconformity. Sources include auditor observations, management review outputs, employee suggestions, and benchmarking against industry practice. Items here are not NCARs and do not require root cause analysis, but they do require an owner and a target date.

| Opportunity ID | Source | Description | Potential Benefit | Owner | Status | Target Date |
|---|---|---|---|---|---|---|
| CI-2026-001 | [Source] | [Description of the improvement opportunity] | [What will improve if this is implemented] | [Owner] | [Not Started / In Progress / Complete] | [YYYY-MM-DD] |
| CI-2026-002 | | | | | | |
| CI-2026-003 | | | | | | |

*Add rows as opportunities are identified. Review this tracker at each management review.*

---

## Section 7: NCAR Summary Dashboard

This section is completed by the AIMS Owner before each management review meeting. It provides the summary view that management needs to assess AIMS performance and direct resources.

**Reporting Period:** [YYYY-MM-DD to YYYY-MM-DD]

### NCARs Raised This Period

| Metric | Count |
|---|---|
| Total NCARs raised | |
| NCARs closed this period | |
| NCARs remaining open | |
| NCARs overdue (past target date, not closed) | |

### By Classification

| Classification | Raised This Period | Open | Closed |
|---|---|---|---|
| Major | | | |
| Minor | | | |
| AI Incident | | | |
| **Total** | | | |

### By Source

| Source | Count |
|---|---|
| Internal Audit | |
| External Audit | |
| Management Review | |
| AI Incident | |
| Self-Identified | |
| Customer Complaint | |
| Supplier Report | |

### Overdue NCARs

| NCAR ID | Classification | Brief Description | Owner | Original Target Date | Days Overdue |
|---|---|---|---|---|---|
| | | | | | |

*If no NCARs are overdue, state: "No NCARs overdue as of [date]."*

### Average Time to Close

**Average days from raised to closed (this period):** [X days]

**Average days from raised to closed (all time):** [X days]

### Management Review Notes

*Record any decisions or actions arising from management's review of this dashboard.*

[Management review notes and actions here.]

---

## Version History

| Version | Date | Author | Summary of Changes |
|---|---|---|---|
| 1.0 | [YYYY-MM-DD] | [Name] | Initial release |

---

*ISO 42001 Readiness Service Toolkit | 03-Remediation | Confidential Client Deliverable*
