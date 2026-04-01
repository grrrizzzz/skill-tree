# Internal Procedure: Phase 5 — Certification Audit Support

> **Current as of:** March 2026 | ISO/IEC 42001:2023

> **Document type:** Internal Procedure — Not for client distribution

---

## 1. Purpose

This procedure defines how to execute Phase 5 of an ISO 42001 readiness engagement. Phase 5 supports the client through the certification audit process and transitions them to independent AIMS maintenance by:

- Closing all Stage 1 audit findings before the Stage 2 audit begins
- Preparing the client and its staff for Stage 2 on-site audit activities
- Supporting the client during Stage 2 as an observer and evidence coordinator
- Managing any nonconformities raised during Stage 2 through to closure
- Facilitating the certification decision and communicating the outcome to client stakeholders
- Handing off AIMS ownership to the client with a complete maintenance package

A junior consultant with ISO management system experience but no prior ISO 42001 experience should be able to execute this procedure by following each step as written. This procedure assumes Phase 3 (Remediation) and Phase 4 (Pre-Audit Readiness) have been completed and the client has received a Stage 1 audit report from the certification body.

---

## 2. Scope

This procedure covers Phase 5 of any ISO 42001 readiness engagement for SMB clients (typically 40–200 employees) that use third-party AI systems. It begins after the Stage 1 audit report is received and ends with the delivery of the post-certification handoff package and surveillance audit preparation notes.

This procedure does not cover the certification body's internal review process, the certification committee's decision-making, or any activities related to AI development or model training.

---

## 3. Roles

| Role | Responsibility in Phase 5 |
|---|---|
| **Lead Consultant** | Executes this procedure. Manages Stage 1 finding closure, coordinates Stage 2 logistics, serves as observer during Stage 2, manages finding response documentation, delivers post-certification handoff package. |
| **Client Sponsor** | Executive point of contact. Authorizes corrective actions, communicates certification achievement to stakeholders, accepts AIMS ownership at handoff. Typically CEO, COO, or VP-level. |
| **AIMS Owner** | Day-to-day AIMS management contact. Primary auditee for Stage 2 interviews on AIMS governance, SoA, and management review. Accepts document control ownership at handoff. |
| **Client IT Lead** | Technical auditee for Stage 2. Provides evidence of AI system controls, access management, and monitoring procedures. |
| **Department Heads / Auditees** | Staff interviewed during Stage 2. Must be able to describe the AI policy, their AI-related responsibilities, and how they report AI incidents. |
| **Certification Body Auditor** | External party. Conducts Stage 2 audit. The consultant does not advocate to or argue with the auditor. |

---

## 4. Inputs

| Input | Source | Required? | Notes |
|---|---|---|---|
| Stage 1 audit report | Certification body | **Yes** | Contains all Stage 1 findings (Major NCs, Minor NCs, Observations) that must be addressed before Stage 2 |
| Stage 1 finding closure evidence | Client + Consultant | **Yes** | Documented evidence that each Stage 1 finding has been addressed |
| Pre-Audit Readiness Checklist (completed) | Phase 4 output | **Yes** | Confirms AIMS documentation is complete and operational |
| All Phase 3–4 deliverables | 03-remediation/, 04-pre-audit/ | **Yes** | Complete AIMS documentation set: policies, procedures, risk register, SoA, NCAR log, training records, management review record, internal audit report |
| Stage 2 audit schedule | Certification body | **Yes** | Dates, times, auditee list, and agenda from the certification body |
| Client organizational chart | Client Sponsor | **Yes** | Needed to identify all auditees and coordinate interview preparation |

---

## 5. Outputs

| Output | Description | Feeds Into |
|---|---|---|
| Stage 1 Finding Closure Package | Documented evidence for each Stage 1 finding, formatted for submission to the certification body | Stage 2 audit readiness |
| Stage 2 Audit Support Notes | Consultant's real-time notes from Stage 2: auditor questions, evidence presented, findings raised, client responses | Finding response documentation |
| Finding Response Documentation | Corrective action plans for each nonconformity raised at Stage 2, formatted per certification body requirements | Certification decision |
| Certification Decision Record | Written record of the certification outcome, certificate details, and any conditions | Client Sponsor, post-certification maintenance |
| Post-Certification Maintenance Plan | Calendar of required AIMS activities: surveillance audits, annual management review, document review cycle, NCAR process ownership | Client AIMS Owner |
| Surveillance Audit Preparation Notes | Guidance on what surveillance audits cover, how to prepare, and common findings | Client AIMS Owner |

---

## 6. Time Estimate

| Activity | Duration | Notes |
|---|---|---|
| Stage 1 Finding Closure | 1–3 weeks | Depends on number and severity of Stage 1 findings |
| Stage 2 Audit Preparation | 1 week before Stage 2 | Final readiness check, auditee coaching, logistics |
| Stage 2 Audit (on-site) | 1–3 days | Certification body determines duration based on scope and headcount |
| Stage 2 Finding Response | 1–2 weeks (if findings raised) | Major NCs require immediate corrective action planning |
| Certification Decision | 2–6 weeks post-Stage 2 | Certification body review and committee decision |
| Post-Certification Handoff | 1 week | Handoff package assembly and client walkthrough |
| **Total elapsed time** | **2–4 weeks** | Stage 2 audit + finding closure + certification decision. Finding closure and handoff may extend timeline if Major NCs are raised. |

---

## 7. Step-by-Step Procedure

---

### Step 1: Stage 1 Finding Closure (Pre-Stage 2, 1–3 Weeks)

**Objective:** Ensure every finding from the Stage 1 audit is addressed with documented evidence before Stage 2 begins. Certification bodies expect to see closure evidence at the start of Stage 2.

#### 1.1 Categorize All Stage 1 Findings

Obtain the Stage 1 audit report from the client. Create a finding closure tracker with one row per finding. Classify each finding using the certification body's terminology (typically Major Nonconformity, Minor Nonconformity, or Observation). Record:

- Finding reference number (from the audit report)
- Finding classification (Major NC / Minor NC / Observation)
- Clause or control referenced
- Auditor's description of the gap
- Closure deadline (if specified by the certification body)

> **Note:** Stage 1 findings are not the same as Stage 2 nonconformities. Stage 1 findings are identified during the documentation review and are expected to be closed before Stage 2. Stage 2 nonconformities are raised during the on-site implementation audit and follow a different closure process (see Step 4).

#### 1.2 Develop Closure Evidence for Each Finding

For each Stage 1 finding, identify the specific evidence that demonstrates closure. Use the following guidance by finding type:

**Missing or incomplete documented information:**
- Produce or finalize the required document
- Ensure it is approved, version-controlled, and accessible
- Record the document reference and approval date in the closure tracker

**Policy or procedure not implemented:**
- Confirm the procedure has been communicated to relevant staff
- Collect training records or acknowledgment records as evidence
- If the procedure requires a record (e.g., a completed risk assessment), produce the record

**Control not operational:**
- Confirm the control is active and functioning
- Collect at least one cycle of evidence (e.g., one completed NCAR, one management review record, one internal audit report)
- Document who owns the control and how it is monitored

**Observation (not a nonconformity):**
- Observations do not require formal closure evidence, but addressing them demonstrates maturity
- Record the client's response to each observation in the closure tracker
- If the client chooses not to address an observation, document the rationale

#### 1.3 Verify Closure with Client

Before assembling the closure package, verify each piece of evidence with the AIMS Owner:

- Confirm the document or record exists and is accessible
- Confirm the evidence directly addresses the auditor's finding (not a related but different document)
- Confirm the evidence is dated after the Stage 1 audit (pre-existing documents that were simply not provided at Stage 1 may not satisfy the auditor)

Walk through the closure tracker line by line with the AIMS Owner. Do not assume closure is complete until you have seen the evidence yourself.

#### 1.4 Assemble the Stage 1 Finding Closure Package

Compile all closure evidence into a single organized package. Format:

- Cover page: client name, Stage 1 audit date, Stage 2 audit date, total findings, closure status summary
- One section per finding: finding reference, auditor's description, closure evidence (document title, version, date), brief narrative explaining how the evidence addresses the finding
- Index of all supporting documents

Submit the closure package to the certification body per their instructions. Some certification bodies require submission in advance of Stage 2; others review it at the opening meeting. Confirm the submission process with the certification body before Stage 2 is scheduled.

#### 1.5 Decision Tree: Stage 1 Finding Cannot Be Closed Before Stage 2

If one or more Stage 1 findings cannot be closed before Stage 2, use the following decision tree:

```
Stage 1 Finding Cannot Be Closed Before Stage 2
│
├── Is the finding a Major Nonconformity?
│   ├── YES → Contact certification body immediately.
│   │         Request guidance on whether Stage 2 can proceed.
│   │         Most certification bodies will not proceed to Stage 2
│   │         with open Major NCs. Options:
│   │         (a) Delay Stage 2 until the Major NC is closed
│   │         (b) Request a partial Stage 2 if the finding is isolated
│   │         → Escalate to Client Sponsor. See Escalation Trigger E-1.
│   │
│   └── NO (Minor NC or Observation) →
│       ├── Can closure be demonstrated within 30 days of Stage 2?
│       │   ├── YES → Proceed to Stage 2. Disclose the open finding
│       │   │         to the auditor at the opening meeting.
│       │   │         Present a corrective action plan with timeline.
│       │   │
│       │   └── NO → Escalate to Client Sponsor.
│       │             Discuss whether to delay Stage 2 or proceed
│       │             with a documented corrective action plan.
│       │             Certification body may accept a plan in lieu
│       │             of closure evidence for Minor NCs.
```

> **Key principle:** Never conceal an open Stage 1 finding from the auditor. Disclose proactively at the opening meeting. Auditors respond better to transparency than to discovering undisclosed gaps during the audit.

---

### Step 2: Stage 2 Audit Preparation (1 Week Before Stage 2)

**Objective:** Ensure the client is operationally and psychologically ready for Stage 2. Stage 2 is an on-site implementation audit — auditors will interview staff, review records, and observe processes. Preparation is the single most effective way to prevent avoidable findings.

#### 2.1 Final Readiness Check

One week before Stage 2, conduct a final readiness check using the Pre-Audit Readiness Checklist from Phase 4. Verify that all items remain current:

- All required AIMS documents are approved, version-controlled, and accessible
- The NCAR log contains at least one completed entry (a real nonconformity, not a placeholder)
- The management review record is complete and signed
- The internal audit report is complete and signed
- Training records exist for all staff who use AI systems within scope
- The SoA is current and reflects the actual AIMS controls in operation
- The AI system inventory is current (no new AI tools added since Phase 4 that are not documented)

If any item is not current, address it immediately. Do not proceed to Stage 2 with known gaps that can be closed in the available time.

#### 2.2 Brief the Client on the Stage 2 Process

Schedule a 60-minute briefing with the Client Sponsor and AIMS Owner. Cover the following:

**What Stage 2 is:**
- An on-site audit conducted by the certification body auditor(s)
- Typically 1–3 days depending on scope and organization size
- Auditors will interview staff, request documents and records, and observe how the AIMS operates in practice
- The auditor is evaluating whether the AIMS is implemented and effective, not just documented

**What Stage 2 is not:**
- A test that can be "passed" by saying the right things
- An adversarial process — auditors are evaluating conformance, not looking for reasons to deny certification
- A repeat of Stage 1 — auditors will not re-review documentation in detail; they will focus on implementation evidence

**What happens after Stage 2:**
- The auditor prepares a Stage 2 audit report
- The certification body's review committee makes the certification decision
- If no Major NCs are raised, certification is typically granted within 2–6 weeks
- If findings are raised, the client has an opportunity to respond before the decision is made

#### 2.3 Coach Auditees on How to Respond to Auditor Questions

This is the most important preparation activity. Identify all staff who will be interviewed during Stage 2 (typically: AIMS Owner, IT Lead, department heads, and a sample of AI system users). Schedule 30-minute coaching sessions with each auditee or group.

**Core coaching principles — communicate these explicitly:**

**Answer what is asked. Nothing more.**
> "If the auditor asks 'How do you report an AI incident?', describe the process. Do not volunteer that the process was only implemented last month, or that you've never actually used it, or that you're not sure it works. Answer the question asked."

**Show evidence confidently.**
> "When the auditor asks to see a document or record, retrieve it calmly and hand it over. Do not apologize for its format or explain its history. If you cannot find something, say 'Let me get that for you' and ask the consultant for assistance."

**Do not guess.**
> "If you don't know the answer to a question, say 'I don't know, but I can find out.' Do not speculate or make up an answer. Incorrect answers are worse than 'I don't know.'"

**Do not argue with the auditor.**
> "If the auditor says something you disagree with, do not argue. Say 'I understand' and let the consultant handle any clarification needed. The consultant will address concerns through the appropriate channel."

**Common Stage 2 auditor questions — prepare auditees for these specifically:**

| Auditor Question | What the Auditee Should Be Able to Answer |
|---|---|
| "Can you describe your organization's AI policy?" | The policy's key commitments: responsible use, risk management, compliance. Not a word-for-word recitation — a genuine understanding. |
| "What AI systems do you use in your role?" | The specific tools they use, what they use them for, and whether those tools are in the AI system inventory. |
| "How do you know what's acceptable use of AI in your role?" | Reference to the AI acceptable use policy, training they received, and where to find the policy. |
| "What would you do if you noticed an AI system producing unexpected or harmful outputs?" | The incident reporting process: who to notify, how to report, what happens next. |
| "Has your team had any AI-related incidents or near-misses?" | Honest answer. If yes, describe what happened and how it was handled. If no, say no. |
| "How does management review the performance of the AIMS?" | Reference to the management review process: frequency, who attends, what inputs are reviewed, what decisions are made. |
| "Who is responsible for maintaining the AI system inventory?" | The AIMS Owner's name and role. |

> **Coaching note:** The most common Stage 2 failure is staff who cannot describe the AI policy in their own words. Run a brief verbal drill with each auditee: ask them to explain the AI policy as if speaking to a new employee. If they cannot do this, schedule additional preparation time.

#### 2.4 Confirm Logistics

One week before Stage 2, confirm the following with the certification body and the Client Sponsor:

- **Audit schedule:** Confirm dates, start times, and which auditees are scheduled for which time slots
- **Room setup:** Confirm a private room is available for auditor interviews. The room should have a table, chairs, power outlets, and Wi-Fi access. Remove any sensitive materials unrelated to the AIMS.
- **Document access:** Confirm all AIMS documents are accessible from the audit room (printed copies or shared drive access). Do not rely on a single person's laptop.
- **Auditee availability:** Confirm all scheduled auditees are available and have not scheduled conflicting meetings or travel
- **Consultant logistics:** Confirm the consultant's role (observer), seating arrangement (consultant sits to the side, not at the main table), and communication protocol with the AIMS Owner during the audit

---

### Step 3: Stage 2 Audit Day Support

**Objective:** Support the client through the Stage 2 audit as an informed observer. The consultant's role is to facilitate, not to advocate. The auditor must be able to evaluate the client's AIMS independently.

#### 3.1 Consultant Role During Stage 2

The consultant's role during Stage 2 is strictly defined:

**The consultant IS:**
- An observer who takes detailed notes
- A resource for evidence retrieval (finding documents the client cannot locate quickly)
- A debrief partner for the client at the end of each day
- A point of contact for logistical questions from the auditor (room, schedule, document access)

**The consultant IS NOT:**
- An advocate who argues the client's case to the auditor
- A spokesperson who answers auditor questions on behalf of the client
- An interpreter who rephrases the auditor's questions to make them easier
- A coach who signals to auditees how to answer during the interview

> **Critical rule:** Do not speak during auditor interviews unless the auditor directly addresses you. If the auditor asks you a question, answer factually and briefly. If the client is struggling to answer a question, do not intervene. Let the auditee respond. You can address gaps in the end-of-day debrief.

#### 3.2 Opening Meeting Protocol

The Stage 2 audit begins with an opening meeting. Attend and take notes. The opening meeting typically covers:

- Introductions (auditor, client team, consultant)
- Confirmation of audit scope and objectives
- Review of the audit agenda and schedule
- Confirmation of the audit criteria (ISO/IEC 42001:2023)
- Logistics (breaks, document access, communication)
- Opportunity for the client to raise any preliminary matters

**At the opening meeting, the consultant should:**
- Introduce themselves as the client's ISO 42001 readiness consultant and observer
- Present the Stage 1 finding closure package if not previously submitted
- Disclose any open Stage 1 findings (see Step 1.5)
- Confirm the audit schedule is workable for the client team

**Do not:**
- Attempt to re-scope the audit at the opening meeting
- Raise concerns about the audit process in front of the client team
- Volunteer information about gaps or weaknesses in the AIMS

#### 3.3 Note-Taking During Stage 2

Take detailed notes throughout Stage 2. Record:

- Each auditor question (verbatim where possible)
- The auditee's response
- Any documents or records the auditor requested
- Any documents or records the auditor reviewed
- Any preliminary findings or concerns the auditor raised
- The auditor's body language and tone (useful for debrief)

Use a structured note template: timestamp, auditor question, auditee response, evidence presented, auditor reaction, consultant notes. These notes are the basis for the finding response documentation if nonconformities are raised.

#### 3.4 Evidence Retrieval Support

If the auditor requests a document or record that the auditee cannot locate quickly, the consultant may assist. Protocol:

1. The auditee says: "Let me get that for you" and looks to the consultant
2. The consultant retrieves the document from the shared drive or printed set
3. The consultant hands the document to the auditee, who presents it to the auditor
4. The consultant does not explain or contextualize the document unless asked

If the requested document does not exist or cannot be found within 5 minutes, the auditee should say: "I don't have that available right now. Can I provide it to you by [time]?" Do not fabricate or substitute a different document.

#### 3.5 Handling Unexpected Findings During Stage 2

If the auditor raises a finding or concern during the audit (not at the closing meeting), use the following protocol:

1. **Do not react visibly.** Take a note. Do not express surprise, disagreement, or concern in front of the auditor.
2. **Do not argue.** If the auditee begins to argue with the auditor, do not join in. After the interview, debrief with the auditee privately.
3. **Clarify, don't dispute.** If the auditor's finding appears to be based on a misunderstanding, the AIMS Owner may politely ask: "Could you help me understand what evidence would satisfy this requirement?" This is clarification, not argument.
4. **Note the finding precisely.** Record the auditor's exact language. This language will appear in the audit report and must be addressed in the finding response.

#### 3.6 Handling Auditor Requests for Documents Not in the Readiness Package

If the auditor requests a document that was not included in the readiness package:

- If the document exists: retrieve it and present it (see Step 3.4)
- If the document does not exist: the auditee should say "We don't have a document for that" — do not claim it exists elsewhere or is "in progress"
- If the document requirement is unclear: the AIMS Owner may ask the auditor to clarify which clause or control the request relates to

> **Note:** Auditors sometimes request documents that are not required by ISO 42001. If the auditor requests something that appears to be outside the standard's requirements, note it carefully. Address it in the end-of-day debrief, not during the interview.

#### 3.7 End-of-Day Debrief

At the end of each audit day, conduct a 30-minute debrief with the Client Sponsor and AIMS Owner. Cover:

- Summary of the day's activities (which clauses and controls were reviewed)
- Any preliminary findings or concerns raised by the auditor
- Auditee performance: who handled questions well, who struggled
- Documents or records that were requested but not available — plan to locate or produce them before the next day
- Adjustments to the next day's preparation (additional coaching for specific auditees, document retrieval)

Keep the debrief factual and constructive. Do not speculate about the certification outcome based on the day's events.

#### 3.8 Closing Meeting Protocol

The Stage 2 audit ends with a closing meeting. Attend and take detailed notes. The closing meeting typically covers:

- Summary of the audit activities
- Preliminary findings (Major NCs, Minor NCs, Observations) — note these verbatim
- Confirmation of the next steps (audit report timeline, finding response process)
- Opportunity for the client to ask questions

**At the closing meeting:**
- The AIMS Owner may ask clarifying questions about findings (not argue them)
- The consultant may ask about the finding response process and timeline
- Do not commit to corrective actions on the spot — wait for the written audit report

After the closing meeting, conduct an immediate debrief with the Client Sponsor and AIMS Owner. Explain the finding classification system (Major NC / Minor NC / Observation) and what each means for the certification timeline. Manage expectations: findings at Stage 2 are common and do not automatically mean certification is denied.

---

### Step 4: Stage 2 Finding Response (If Findings Raised)

**Objective:** Develop and submit corrective action plans for any nonconformities raised at Stage 2. The quality of the finding response directly affects the certification decision.

#### 4.1 Classify Stage 2 Findings

When the Stage 2 audit report is received, classify each finding:

**Major Nonconformity:** A finding that indicates a significant failure to meet a requirement of ISO 42001, or a situation where the AIMS is absent, not implemented, or systematically ineffective. Major NCs must typically be closed before certification is granted. The certification body will specify the closure deadline (typically 90 days from the audit date).

**Minor Nonconformity:** A finding that indicates a single lapse or isolated failure to meet a requirement. The AIMS is generally in place but has a specific gap. Minor NCs must be closed within the certification cycle (typically 12 months), often verified at the first surveillance audit.

**Observation:** A finding that does not constitute a nonconformity but indicates an area for improvement. Observations do not require formal corrective action but should be addressed to demonstrate continual improvement.

> **Important:** Do not accept finding classifications without reviewing them against the audit report language. Occasionally, auditors classify findings differently than the evidence warrants. If you believe a Major NC should be classified as a Minor NC (or vice versa), address this through the finding response process — not by arguing with the auditor.

#### 4.2 Develop Corrective Action Plans

For each nonconformity (Major or Minor), develop a corrective action plan using the following structure:

**Finding reference:** [Certification body's reference number]
**Finding description:** [Auditor's exact language from the audit report]
**Clause/control:** [ISO 42001 clause or Annex A control referenced]
**Root cause analysis:** [Why did this gap exist? Not what happened, but why the system failed to prevent it]
**Immediate correction:** [What was done to fix the specific instance — the symptom]
**Corrective action:** [What was done to address the root cause — preventing recurrence]
**Evidence of closure:** [Documents, records, or other evidence demonstrating the corrective action is complete]
**Responsible party:** [Name and role of the person accountable for closure]
**Target closure date:** [Must be within the certification body's deadline]

> **Root cause guidance:** The most common root cause errors are (1) describing the symptom as the cause ("the document was missing because it wasn't created") and (2) proposing a correction as the corrective action ("we will create the document"). Push the client to identify the systemic reason the gap existed: inadequate process ownership, insufficient training, unclear responsibility, or missing procedure.

#### 4.3 Timelines for Finding Closure

| Finding Type | Typical Closure Deadline | Verification Method |
|---|---|---|
| Major Nonconformity | 90 days from Stage 2 audit date | Certification body review of closure evidence; may require follow-up visit |
| Minor Nonconformity | 12 months (verified at first surveillance audit) | Surveillance audit review |
| Observation | No formal deadline | Addressed at discretion; reviewed at surveillance audit |

> **Note:** Timelines vary by certification body. Always confirm the specific deadlines in the Stage 2 audit report. Some certification bodies allow 60 days for Major NCs; others allow up to 6 months.

#### 4.4 Prepare Finding Response Documentation

Compile all corrective action plans into a finding response package. Format:

- Cover page: client name, Stage 2 audit date, audit report reference, total findings by classification, submission date
- One section per finding: corrective action plan (per Step 4.2 structure) plus supporting evidence
- Summary table: finding reference, classification, root cause summary, corrective action summary, closure date, status

Submit the finding response package to the certification body per their instructions. Confirm receipt and ask for acknowledgment that the response is complete.

#### 4.5 Decision Tree: Major Nonconformity Raised at Stage 2

```
Major Nonconformity Raised at Stage 2
│
├── Can the Major NC be closed within 90 days?
│   ├── YES → Develop corrective action plan immediately.
│   │         Submit finding response within 2 weeks of receiving
│   │         the audit report. Implement corrective action.
│   │         Submit closure evidence before the 90-day deadline.
│   │         Certification body will review and make decision.
│   │         → Proceed to Step 5 (Certification Decision Support)
│   │
│   └── NO → Escalate to Client Sponsor immediately.
│             See Escalation Trigger E-1.
│             Options:
│             (a) Request deadline extension from certification body
│                 (some bodies allow extensions for documented reasons)
│             (b) Accept certification delay — re-audit after closure
│             (c) If the Major NC reflects a fundamental AIMS gap,
│                 assess whether Phase 3 remediation needs to be
│                 revisited before re-audit
│
├── Does the client want to dispute the Major NC classification?
│   ├── YES → See Escalation Trigger E-2.
│   │         Review the audit report language carefully.
│   │         If there is a genuine basis for dispute (auditor
│   │         misapplied the standard), prepare a written response
│   │         citing the specific clause and the evidence that
│   │         demonstrates conformance.
│   │         Submit through the certification body's formal
│   │         objection process — not verbally to the auditor.
│   │
│   └── NO → Proceed with corrective action plan.
│
└── Are multiple Major NCs raised?
    ├── YES → Prioritize by risk and closure complexity.
    │         Address the most systemic findings first.
    │         Consider whether the AIMS has a fundamental gap
    │         that requires re-scoping or re-remediation.
    │         Escalate to Client Sponsor.
    │
    └── NO → Proceed with single corrective action plan.
```

#### 4.6 Decision Tree: Certification Denied

```
Certification Denied
│
├── Reason: Major NC not closed within deadline
│   ├── Was the deadline extension requested?
│   │   ├── YES, denied → Assess root cause of closure failure.
│   │   │                  Develop revised corrective action plan.
│   │   │                  Request re-audit date from certification body.
│   │   │                  Timeline: typically 3–6 months to re-audit.
│   │   │
│   │   └── NO → Request extension now (may be too late).
│   │             If extension denied, proceed to re-audit path.
│   │
│   └── Was the corrective action plan accepted by the CB?
│       ├── NO → Review CB feedback. Revise and resubmit.
│       └── YES, but evidence insufficient → Strengthen evidence.
│                                             Resubmit with additional documentation.
│
├── Reason: Fundamental AIMS gap identified
│   ├── Assess whether the gap was present during Phase 3–4
│   │   and was missed, or whether it emerged post-Phase 4.
│   ├── If missed during Phase 3–4: conduct root cause analysis
│   │   of the consulting engagement. Remediate at no additional
│   │   cost to the client if the gap was within scope.
│   └── Develop a targeted remediation plan.
│       Re-audit after remediation is complete.
│
└── Reason: Client disputes the denial
    ├── Review the certification body's appeals process.
    │   Most accredited certification bodies have a formal
    │   appeals procedure under their accreditation requirements.
    ├── Prepare a written appeal citing:
    │   (a) The specific finding(s) being appealed
    │   (b) The evidence that demonstrates conformance
    │   (c) The clause(s) of ISO 42001 that support the client's position
    └── Submit the appeal within the certification body's deadline.
        Appeals are typically reviewed by a different auditor or
        a certification committee member not involved in the original audit.
```

---

### Step 5: Certification Decision Support

**Objective:** Guide the client through the post-Stage 2 period, manage expectations about the certification timeline, and communicate the certification outcome effectively.

#### 5.1 What Happens After Stage 2

After the Stage 2 audit closes, the following sequence occurs:

1. **Auditor prepares Stage 2 audit report** (typically 1–2 weeks after the audit)
2. **Client receives audit report** and has an opportunity to review findings
3. **Client submits finding response** (if findings were raised) — see Step 4
4. **Certification body's technical reviewer** reviews the audit report and finding response
5. **Certification committee** makes the certification decision
6. **Certificate issued** (if approved) or **client notified of denial** (if not approved)

Total timeline from Stage 2 audit to certificate issuance: typically **2–6 weeks** if no Major NCs are raised. If Major NCs are raised, the timeline extends to include the corrective action closure period (up to 90 days) plus the certification body's review time.

#### 5.2 Maintaining Client Engagement During the Wait

The period between Stage 2 and the certification decision is often the most difficult for clients. They have completed the audit and are waiting for an outcome they cannot control. Manage this period proactively:

- Send a weekly status update to the Client Sponsor (even if there is nothing new to report)
- Confirm with the certification body that the audit report is on schedule
- If the finding response has been submitted, confirm receipt and ask for an estimated review timeline
- Begin preparing the post-certification handoff package during this period (see Step 6) — do not wait for the certificate

#### 5.3 Communicating Certification Achievement

When the certificate is issued, the consultant should:

1. **Notify the Client Sponsor immediately** by phone or video call — do not deliver this news by email alone
2. **Confirm the certificate details:** certificate number, scope statement, issue date, expiry date (typically 3 years), surveillance audit dates
3. **Provide a brief communication template** for the client to announce certification to their stakeholders:

**Internal announcement template:**
> "We are pleased to announce that [Organization Name] has achieved ISO/IEC 42001:2023 certification for [scope statement]. This certification demonstrates our commitment to responsible AI governance and our investment in managing AI-related risks systematically. Our AI Management System will be maintained through ongoing surveillance audits and annual reviews. Questions about our AIMS can be directed to [AIMS Owner Name]."

**External announcement guidance:**
- The client may announce certification publicly, but must accurately represent the scope
- The client may use the certification body's certification mark per the certification body's trademark guidelines — confirm these guidelines with the certification body
- The client should not claim ISO 42001 certification for activities outside the certified scope

#### 5.4 Certificate Details to Record

Record the following in the Certification Decision Record:

| Field | Value |
|---|---|
| Certificate number | [From certification body] |
| Certification body name | [Name and accreditation body] |
| Certification standard | ISO/IEC 42001:2023 |
| Certified scope | [Exact scope statement from certificate] |
| Issue date | [Date] |
| Expiry date | [Date — typically 3 years from issue] |
| First surveillance audit date | [Typically 6–12 months from issue] |
| Second surveillance audit date | [Typically 12–18 months from issue] |
| Recertification audit date | [Typically 3 years from issue] |
| Stage 2 findings summary | [Number of Major NCs, Minor NCs, Observations] |
| Finding closure status | [All closed / Minor NCs open — to be verified at surveillance] |

---

### Step 6: Post-Certification Handoff

**Objective:** Transfer AIMS ownership from consultant-led to client-led. The client must be able to maintain their AIMS independently after this handoff. A client who cannot maintain their AIMS without ongoing consultant support has not achieved the goal of the engagement.

#### 6.1 Handoff Package Contents

Assemble the following into a single organized handoff package. Deliver it to the AIMS Owner with a walkthrough session (minimum 2 hours):

**AIMS Documentation Set:**
- AI policy (approved, current version)
- AIMS scope statement (approved, current version)
- Statement of Applicability (approved, current version)
- AI system inventory (current as of certification date)
- Risk register and risk treatment plan (current as of certification date)
- All operational procedures (AI acceptable use, incident reporting, vendor assessment, etc.)
- All required records (management review record, internal audit report, NCAR log, training records)

**Maintenance Calendar:**
- Surveillance audit dates (from certificate — see Step 5.4)
- Annual management review date (recommend scheduling within 12 months of certification)
- Document review cycle (recommend annual review of all AIMS documents)
- AI system inventory review cycle (recommend quarterly — AI tools change frequently)
- NCAR process review (confirm the NCAR process is operational and ownership is clear)

**Process Ownership Register:**
- AIMS Owner: responsible for overall AIMS maintenance, document control, management review coordination
- IT Lead: responsible for AI system inventory maintenance, vendor assessment process
- HR/Training Lead: responsible for AI training records and onboarding process
- Department Heads: responsible for reporting AI incidents and maintaining departmental compliance

**Surveillance Audit Preparation Guide:**
- What surveillance audits cover (see Step 7)
- How to prepare (see Step 7)
- Contact information for the certification body
- How to request a surveillance audit date change if needed

#### 6.2 AIMS Owner Handoff Walkthrough

Conduct a 2-hour walkthrough session with the AIMS Owner. Cover:

1. **Document control:** Where all AIMS documents are stored, how to update them, version control process, approval process
2. **NCAR process:** How to open an NCAR, how to conduct root cause analysis, how to close an NCAR, how to report NCAR status at management review
3. **Management review:** How to schedule and run the annual management review, what inputs are required, what outputs must be recorded
4. **Internal audit:** How to plan and conduct the annual internal audit, how to record findings, how to report results
5. **AI system inventory:** How to add new AI systems, how to assess new systems for risk, how to update the SoA when new systems are added
6. **Surveillance audit preparation:** What to expect, how to prepare (see Step 7)

Provide the AIMS Owner with a one-page "AIMS Maintenance Cheat Sheet" summarizing the key recurring activities and their frequencies.

#### 6.3 Recertification Cycle

ISO 42001 certification is valid for 3 years, subject to successful surveillance audits. The recertification cycle:

- **Year 1:** First surveillance audit (typically 6–12 months after certification)
- **Year 2:** Second surveillance audit (typically 18–24 months after certification)
- **Year 3:** Recertification audit (full re-audit before certificate expiry)

Advise the client to begin recertification preparation 6 months before the certificate expiry date. The recertification audit is similar to Stage 2 but typically shorter, as the certification body has an established understanding of the client's AIMS.

> **Note:** If the client fails a surveillance audit (i.e., Major NCs are raised and not closed), the certification body may suspend or withdraw certification. Help the client understand that certification maintenance requires ongoing commitment, not just a one-time effort.

---

### Step 7: Surveillance Audit Preparation

**Objective:** Prepare the client for surveillance audits, which occur at approximately 6 and 12 months after certification. Surveillance audits are a common source of certification suspension for clients who treat certification as a finish line rather than an ongoing commitment.

#### 7.1 What Surveillance Audits Cover

Surveillance audits are shorter than Stage 2 (typically half a day to one day) and focus on:

- **Changes since certification:** New AI systems added to scope, changes to the AIMS scope, organizational changes affecting the AIMS
- **Continual improvement:** Evidence that the AIMS is improving, not just maintained — management review outputs, NCAR closures, internal audit findings and responses
- **Open findings from Stage 2:** Minor NCs that were not closed before certification must be closed by the first surveillance audit
- **Specific clauses selected by the auditor:** The certification body typically selects 2–4 clauses to audit in depth at each surveillance audit, rotating through the standard over the 3-year cycle
- **AIMS effectiveness:** Are the controls working? Is the AI policy understood by staff? Is the NCAR process generating real corrective actions?

#### 7.2 How to Prepare for Surveillance Audits

Advise the AIMS Owner to begin surveillance audit preparation 4–6 weeks before the scheduled date:

1. **Update the AI system inventory:** Confirm all AI systems currently in use are documented. Remove systems that are no longer in use. Add any new systems and assess their risk.
2. **Review open NCARs:** Ensure all open NCARs have current status and are on track for closure. Close any NCARs that are complete.
3. **Confirm management review is current:** The most recent management review should be within 12 months of the surveillance audit date. If not, schedule one immediately.
4. **Confirm internal audit is current:** The most recent internal audit should be within 12 months of the surveillance audit date. If not, conduct one.
5. **Review training records:** Confirm training records are current for all staff who use AI systems within scope. Update records for any new hires or role changes.
6. **Brief auditees:** Conduct a brief refresher coaching session with key auditees (AIMS Owner, IT Lead, department heads). Review the coaching principles from Step 2.3.
7. **Prepare a changes summary:** Document all significant changes to the AIMS since the last audit (new AI systems, policy updates, organizational changes, significant NCARs). Present this proactively at the surveillance audit opening meeting.

#### 7.3 Common Surveillance Audit Findings

The following findings are most common at surveillance audits for SMB AI user organizations. Advise the AIMS Owner to specifically check these areas before each surveillance audit:

| Common Finding | Root Cause | Prevention |
|---|---|---|
| AI system inventory not current | New AI tools adopted without AIMS review | Establish a process for IT/procurement to notify the AIMS Owner before new AI tools are deployed |
| NCAR process not operational | No real nonconformities recorded since certification | Remind the AIMS Owner that NCARs should be opened for real gaps, not just audit findings. Internal audit findings are a natural source of NCARs. |
| Management review not conducted | AIMS Owner deprioritized it after certification | Schedule the management review date at the handoff session and put it in the AIMS Owner's calendar |
| Training records not current | New hires not onboarded to AI policy | Add AI policy training to the HR onboarding checklist |
| Minor NCs from Stage 2 not closed | Corrective actions not completed | Track Minor NC closure in the NCAR log and review status monthly |
| Staff cannot describe AI policy | Policy not reinforced after initial training | Include AI policy in annual all-hands briefing or team meetings |

---

## 8. Referenced Documents

| Document | Location | Purpose |
|---|---|---|
| Pre-Audit Readiness Checklist | 04-pre-audit/ | Final readiness verification before Stage 2 |
| NCAR Template | 03-remediation/ | Corrective action plan format for Stage 2 findings |
| Statement of Applicability | Client AIMS documentation | Key document for Stage 2 auditor review |
| AI System Inventory | Client AIMS documentation | Key document for Stage 2 auditor review |
| Management Review Record | Client AIMS documentation | Evidence of AIMS operational effectiveness |
| Internal Audit Report | Client AIMS documentation | Evidence of AIMS self-assessment |
| Training Records | Client AIMS documentation | Evidence of staff competence |
| Glossary | 00-foundation/glossary.md | Controlled vocabulary for all AIMS documentation |
| Phase 4 Procedure | 04-pre-audit/ | Pre-Stage 2 readiness activities |
| Phase 3 Procedure | 03-remediation/ | AIMS remediation activities |

---

## 9. Escalation Triggers

The following conditions require immediate escalation to the Client Sponsor and, where indicated, to the engagement principal.

### E-1: Major Nonconformity That Cannot Be Closed Within 90 Days

**Trigger:** A Major NC is raised at Stage 2 and the client cannot implement the required corrective action within the certification body's deadline (typically 90 days).

**Why it matters:** Failure to close a Major NC within the deadline typically results in certification denial. This is a significant engagement risk and a client relationship risk.

**Action:**
1. Notify the Client Sponsor within 24 hours of identifying the closure risk
2. Contact the certification body to request a deadline extension — document the request and the response
3. Assess whether the Major NC reflects a gap in Phase 3–4 remediation that the consulting engagement should have caught
4. Develop a revised corrective action plan with a realistic timeline
5. If the deadline cannot be extended and closure is not achievable, prepare the client for a certification delay and a re-audit path
6. Escalate to the engagement principal if the gap may constitute a consulting delivery failure

### E-2: Client Wants to Dispute an Auditor Finding

**Trigger:** The client believes an auditor finding is incorrect, unfair, or based on a misapplication of the standard, and wants to formally dispute it.

**Why it matters:** Disputes handled incorrectly can damage the client's relationship with the certification body and delay certification. Disputes handled correctly can result in finding reclassification or withdrawal.

**Action:**
1. Review the audit report language and the relevant ISO 42001 clause carefully
2. Assess whether there is a genuine basis for dispute (auditor misapplied the standard, evidence was not considered, finding is factually incorrect) versus client disagreement with a valid finding
3. If there is a genuine basis: prepare a written response citing the specific clause, the evidence, and the basis for dispute. Submit through the certification body's formal objection process.
4. If there is no genuine basis: advise the client to accept the finding and develop a corrective action plan. Explain that disputing valid findings damages credibility with the certification body.
5. Do not argue with the auditor directly. All disputes go through the certification body's formal process.

### E-3: Certification Body Requests Additional Evidence Not in the Package

**Trigger:** After Stage 2, the certification body's technical reviewer requests additional evidence or documentation that was not included in the readiness package or finding response.

**Why it matters:** Requests for additional evidence can delay the certification decision. Failure to respond promptly can result in the certification body closing the file.

**Action:**
1. Confirm the specific evidence requested and the deadline for submission
2. Assess whether the evidence exists (it was simply not included) or needs to be created
3. If it exists: compile and submit within the deadline
4. If it needs to be created: assess whether this represents a genuine AIMS gap (which may require a corrective action) or a documentation gap (which can be addressed by producing the required record)
5. If the request appears to be outside the requirements of ISO 42001, prepare a written response explaining why the requested evidence is not required by the standard. Submit through the certification body's formal process.
6. Notify the Client Sponsor of the request and the response plan

### E-4: Client Leadership Disengages After Stage 2

**Trigger:** The Client Sponsor or AIMS Owner becomes unresponsive, deprioritizes AIMS activities, or signals that they consider the engagement complete after Stage 2 — before the certification decision is made or before the post-certification handoff is complete.

**Why it matters:** Client disengagement after Stage 2 is a common pattern. It creates risk in two ways: (1) finding response documentation may not be completed on time, jeopardizing certification; (2) the AIMS may not be maintained after certification, leading to surveillance audit failure.

**Action:**
1. Contact the Client Sponsor directly (phone or video call — not email) to re-establish engagement
2. Explain the specific risks of disengagement: finding response deadlines, certification decision timeline, surveillance audit requirements
3. If the Client Sponsor is unavailable, identify an alternative executive contact
4. Document all attempts to re-engage the client
5. If the client remains disengaged and finding response deadlines are at risk, notify the engagement principal
6. At the handoff session, explicitly address the surveillance audit schedule and the consequences of AIMS maintenance failure — make the ongoing commitment concrete and calendar-based

---

## 10. Revision History

| Version | Date | Author | Changes |
|---|---|---|---|
| 1.0 | March 2026 | Internal | Initial release |

---

*ISO 42001 Readiness Service Toolkit | 05-Certification | Internal Use*
