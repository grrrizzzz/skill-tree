# Internal Procedure: Phase 4 — Pre-Audit Readiness

> **Current as of:** March 2026 | ISO/IEC 42001:2023

> **Document type:** Internal Procedure — Not for client distribution

---

## 1. Purpose

This procedure defines how to execute Phase 4 of an ISO 42001 readiness engagement. Phase 4 prepares the client's AI Management System (AIMS) for certification by:

- Verifying that all Phase 3 remediation deliverables are complete, approved, and implemented
- Conducting a formal internal audit of the AIMS against all applicable ISO 42001 clauses and Annex A controls
- Facilitating the management review required by Clause 9.3
- Closing all nonconformities identified during the internal audit before the Stage 1 certification audit
- Conducting a mock Stage 1 audit to simulate the certification body's document review
- Assembling the Stage 1 Audit Readiness Package and coaching the client through the Stage 1 process

A junior consultant with ISO management system experience but no prior ISO 42001 experience should be able to execute this procedure by following each step as written. Phase 4 is the final consultant-led phase before the certification body engages. The quality of work done here directly determines whether the client passes Stage 1 and proceeds to Stage 2.

---

## 2. Scope

This procedure covers Phase 4 of any ISO 42001 readiness engagement for SMB clients (typically 40–200 employees) that use third-party AI systems. It begins after Phase 3 deliverables have been submitted to the client and ends with the client's Stage 1 audit either completed or formally scheduled with the certification body.

This procedure does not cover Stage 2 audit support (covered in Phase 5), ongoing AIMS maintenance post-certification, or any activities where the client is acting as an AI developer or AI provider.

---

## 3. Roles

| Role | Responsibility in Phase 4 |
|---|---|
| **Lead Consultant** | Executes this procedure. Plans and facilitates the internal audit, facilitates the management review, conducts the mock audit, assembles the Stage 1 readiness package, and supports the client during Stage 1. |
| **Internal Auditor** | Conducts the internal audit. Must be independent of the AIMS implementation. May be the Lead Consultant (if not involved in Phase 3 implementation), a qualified colleague, or a trained client employee. See Step 2 for independence requirements. |
| **Client Sponsor** | Executive point of contact. Approves the internal audit plan, participates in the management review as top management, reviews and approves the Stage 1 readiness package. |
| **AIMS Owner** | Client-side AIMS coordinator. Primary auditee for most internal audit sessions. Responsible for corrective action implementation and evidence collection. |
| **Department Heads / Process Owners** | Auditees for their respective areas. Provide objective evidence during internal audit interviews. |
| **Certification Body Auditor** | External party. Conducts Stage 1 (document review) and Stage 2 (on-site audit). Not a consultant role — the consultant supports the client in preparing for and responding to the certification body. |

---

## 4. Inputs

| Input | Source | Required? | Notes |
|---|---|---|---|
| AI Policy | Phase 3 deliverable | **Yes** | Must be approved by top management before internal audit |
| Acceptable Use Policy (AUP) | Phase 3 deliverable | **Yes** | Must be approved and communicated to all staff |
| AI Risk Register | Phase 3 deliverable | **Yes** | Must reflect current risk assessment with treatment decisions |
| AI Impact Assessments | Phase 3 deliverable | **Yes** | Required for all AI systems classified as Medium or High risk |
| Statement of Applicability (SoA) | Phase 3 deliverable | **Yes** | Must be complete with all 39 controls assessed and justified |
| Risk Treatment Plan (RTP) | Phase 3 deliverable | **Yes** | Must document treatment decisions and implementation status |
| Supplier Assessments | Phase 3 deliverable | **Yes** | Required for all in-scope third-party AI providers |
| Training Records | Phase 3 deliverable | **Yes** | Evidence that all staff received AI awareness training |
| NCAR Log (Nonconformity and Corrective Action Report) | Phase 3 deliverable | **Yes** | Log of any nonconformities identified during Phase 3 |
| Implementation Roadmap | Phase 3 deliverable | **Yes** | Status of all remediation activities |
| AIMS Scope Statement | Phase 1 deliverable | **Yes** | Defines what is in scope for the internal audit |
| AI System Inventory | Phase 1 deliverable | **Yes** | Reference for audit coverage of all in-scope AI systems |
| Gap Analysis Report | Phase 2 deliverable | **Yes** | Baseline for measuring remediation completeness |
| Signed SOW | 07-business/ | **Yes** | Confirms Phase 4 is within engagement scope |

---

## 5. Outputs

| Output | Description | Feeds Into |
|---|---|---|
| Internal Audit Report | Formal report documenting audit scope, methodology, findings (Major NCs, Minor NCs, Observations), and conclusions | Management Review, Corrective Action Management, Stage 1 Readiness Package |
| Management Review Minutes | Documented record of the management review meeting including all required inputs, decisions made, and actions assigned | Stage 1 Readiness Package, AIMS records |
| Corrective Action Closure Evidence | Documented evidence that all nonconformities identified in the internal audit have been addressed (root cause analysis, corrective action, verification) | Stage 1 Readiness Package |
| Stage 1 Audit Readiness Package | Complete document index and evidence bundle prepared for the certification body's Stage 1 document review | Certification body Stage 1 audit |
| Mock Audit Report | Internal report summarizing findings from the mock Stage 1 audit simulation, including remaining gaps and recommendations | Stage 1 preparation, client coaching |

---

## 6. Time Estimate

| Activity | Duration | Notes |
|---|---|---|
| Phase 3 Completion Verification | Week 1, Days 1–3 | Internal review + client confirmation sessions |
| Internal Audit Planning | Week 1, Days 3–5 | Audit plan, checklist preparation, auditee notification |
| Internal Audit Execution | Weeks 2–3 | Opening meeting, interviews, document review, closing meeting |
| Internal Audit Report | Week 3 | Draft, client review, finalization |
| Corrective Action Management | Weeks 3–4 | Root cause analysis, corrective action plans, implementation |
| Management Review Facilitation | Week 4 | Preparation, meeting, minutes finalization |
| Mock Audit | Weeks 4–5 | Document review simulation, gap identification |
| Stage 1 Audit Preparation | Weeks 5–6 | Readiness package assembly, client coaching |
| Stage 1 Audit Support | Week 6 | Active support during Stage 1 audit |
| **Total elapsed time** | **4–6 weeks** | Depends on number of audit findings, corrective action complexity, and client responsiveness |

---

## 7. Step-by-Step Procedure

---

### Step 1: Phase 3 Completion Verification (Week 1, Days 1–3)

**Objective:** Confirm that all Phase 3 deliverables are complete, approved, and implemented before beginning the internal audit. Starting an internal audit against an incomplete AIMS wastes time and generates findings that are artifacts of incompleteness rather than genuine system weaknesses.

**Duration:** 2–3 days (internal review + client confirmation)

**Why this step matters:** The internal audit is an audit of the AIMS as implemented. If key documents are missing or unapproved, the audit will generate Major nonconformities that could have been avoided. Completing this verification step protects the client's timeline and the consultant's credibility.

#### 1.1 Phase 3 Deliverable Verification Checklist

Review each deliverable against the criteria below. For each item, confirm: (a) the document exists, (b) it is in its final approved version, and (c) it has been communicated or implemented as required.

**Governance Documents:**

- [ ] **AI Policy** — Final version exists; approved by top management (signature or equivalent); version-controlled; communicated to all staff
- [ ] **Acceptable Use Policy (AUP)** — Final version exists; approved; communicated to all staff; acknowledgment records exist (signed forms or training completion records)
- [ ] **AIMS Scope Statement** — Final version exists; approved by Client Sponsor; consistent with AI System Inventory

**Risk and Impact Documentation:**

- [ ] **AI Risk Register** — All in-scope AI systems assessed; risk levels assigned; treatment decisions documented; owner assigned for each risk; last review date recorded
- [ ] **AI Impact Assessments** — Completed for all Medium and High risk AI systems; findings documented; mitigations recorded; approved by AIMS Owner or Client Sponsor
- [ ] **Statement of Applicability (SoA)** — All 39 Annex A controls assessed; applicability decisions justified; approved by Client Sponsor; version-controlled
- [ ] **Risk Treatment Plan (RTP)** — Treatment options selected for all identified risks; implementation status tracked; residual risk documented

**Operational Controls:**

- [ ] **Supplier Assessments** — Completed for all in-scope third-party AI providers; assessment criteria documented; results recorded; review schedule established
- [ ] **AI System Documentation** — Documented information exists for each in-scope AI system (purpose, capabilities, limitations, data flows, operating parameters)
- [ ] **Defined Use and Misuse Documentation** — Intended uses and prohibited uses documented for each AI system; communicated to relevant staff

**People and Awareness:**

- [ ] **Training Records** — Evidence that all staff received AI awareness training; completion records by employee; training content version-controlled
- [ ] **Roles and Responsibilities** — AI-related roles defined and assigned; role descriptions documented; individuals aware of their responsibilities

**Operational Records:**

- [ ] **NCAR Log** — Nonconformity and Corrective Action Report log exists; any Phase 3 nonconformities recorded; status tracked
- [ ] **Implementation Roadmap** — All Phase 3 remediation activities tracked; completion status current; any open items documented with owner and target date

**Supporting Processes:**

- [ ] **Document Control Process** — Procedure for creating, reviewing, approving, and retiring AIMS documents exists; version control applied consistently
- [ ] **Internal Audit Procedure** — Procedure for conducting internal audits exists (may be this document or a client-owned procedure)
- [ ] **Corrective Action Procedure** — Procedure for identifying, recording, analyzing, and closing nonconformities exists
- [ ] **Management Review Procedure** — Procedure or agenda template for management review exists

#### 1.2 Decision Tree: Missing or Incomplete Deliverables

```
Is a Phase 3 deliverable missing or incomplete?
│
├── YES — Determine criticality:
│   │
│   ├── CRITICAL DOCUMENT (AI Policy, SoA, Risk Register, Internal Audit Procedure)
│   │   │
│   │   ├── Missing entirely → STOP. Do not begin internal audit.
│   │   │   - Notify Client Sponsor immediately
│   │   │   - Identify root cause: Phase 3 scope gap, client delay, or resource issue
│   │   │   - Estimate time to complete the missing document
│   │   │   - Adjust Phase 4 timeline accordingly
│   │   │   - Document the delay and its cause in engagement notes
│   │   │
│   │   └── Exists but not approved → PAUSE internal audit for this area.
│   │       - Escalate to Client Sponsor for approval within 48 hours
│   │       - If approval cannot be obtained in 48 hours, see Escalation Trigger E-4
│   │       - Do not audit a document that is still in draft — findings will be invalid
│   │
│   ├── IMPORTANT DOCUMENT (Impact Assessments, Supplier Assessments, Training Records)
│   │   │
│   │   ├── Missing for some AI systems → Proceed with audit but flag as finding.
│   │   │   - Document which systems lack the required documentation
│   │   │   - This will generate a Minor or Major NC in the internal audit
│   │   │   - Ensure corrective action is planned before Stage 1 audit
│   │   │
│   │   └── Missing entirely → Treat as Critical Document (see above)
│   │
│   └── SUPPORTING DOCUMENT (Implementation Roadmap, NCAR Log)
│       - Proceed with audit
│       - Note the gap in the internal audit report
│       - Assign corrective action with target date before Stage 1
│
└── NO — All deliverables complete and approved → Proceed to Step 2
```

#### 1.3 Verification Meeting with AIMS Owner

Schedule a 60-minute verification meeting with the AIMS Owner (and Client Sponsor if available) to:

1. Walk through the checklist above together — do not rely solely on document review
2. Confirm that documents are not just filed but actually implemented (e.g., staff have actually received training, not just that training materials exist)
3. Identify any items the client believes are complete but that require consultant review before the audit
4. Agree on the internal audit start date and confirm auditee availability

**Post-meeting actions:**
- [ ] Document verification results in engagement notes
- [ ] Log any incomplete items with owner and target completion date
- [ ] Confirm internal audit start date with Client Sponsor
- [ ] Proceed to Step 2 only when all Critical Documents are complete and approved

---

### Step 2: Internal Audit Planning (Week 1, Days 3–5)

**Objective:** Plan a rigorous, well-scoped internal audit that covers all applicable ISO 42001 clauses and Annex A controls. A well-planned audit produces findings that are credible, actionable, and defensible to the certification body.

**Duration:** 2 days (planning and preparation)

#### 2.1 Internal Audit Scope

The internal audit must cover:

- **All ISO 42001 clauses:** Clauses 4 through 10 (Context, Leadership, Planning, Support, Operation, Performance Evaluation, Improvement)
- **All applicable Annex A controls:** All controls marked FULLY APPLICABLE or PARTIALLY APPLICABLE in the client's SoA
- **All in-scope AI systems:** Every AI system listed in the AI System Inventory within the AIMS scope
- **All in-scope organizational units:** Every department or business unit within the AIMS scope boundary

**What the internal audit does NOT cover:**
- Annex A controls marked NOT APPLICABLE in the SoA (A.6.2.2, A.6.2.3, A.10.4 for AI-user organizations) — but the auditor should verify that the exclusion justifications are adequate
- AI systems explicitly excluded from the AIMS scope — but the auditor should verify that exclusion justifications are documented

#### 2.2 Internal Auditor Selection

**The most important rule in internal audit planning:** The internal auditor must be independent of the activities being audited. This means the person who implemented the AIMS cannot audit their own work.

**Decision Tree: Who Can Serve as Internal Auditor?**

```
Who implemented the AIMS (Phase 3 remediation)?
│
├── LEAD CONSULTANT implemented Phase 3
│   │
│   ├── Can the Lead Consultant audit Phase 4? → NO, if they wrote the documents.
│   │   The auditor cannot audit their own work. This is a fundamental independence
│   │   requirement of ISO 42001 Clause 9.2.
│   │
│   └── Options for independent auditor:
│       ├── OPTION A: Colleague from consulting firm (preferred)
│       │   - Must have ISO 42001 or equivalent management system audit experience
│       │   - Must not have been involved in Phase 3 implementation
│       │   - Brief them on the client's AIMS scope and context before the audit
│       │   - Lead Consultant can support logistics but must not lead audit sessions
│       │
│       ├── OPTION B: Qualified client employee (acceptable if trained)
│       │   - Must not have been involved in implementing the documents being audited
│       │   - Must have completed ISO internal auditor training (ISO 19011 awareness minimum)
│       │   - Lead Consultant can coach the client auditor but must not conduct the audit
│       │   - Document the client auditor's qualifications in the audit plan
│       │
│       └── OPTION C: External auditor (acceptable, adds cost)
│           - Hire a qualified external auditor for the internal audit
│           - Appropriate when: no qualified internal resource exists, client wants
│             maximum independence, or engagement scope includes audit support
│           - Ensure the external auditor understands ISO 42001 specifically
│
├── CLIENT EMPLOYEE implemented Phase 3
│   │
│   ├── Can the Lead Consultant audit? → YES, if the consultant did not write the documents.
│   │   - Lead Consultant is independent of the client's implementation activities
│   │   - This is the most common arrangement for SMB engagements
│   │   - Document the independence basis in the audit plan
│   │
│   └── Can a different client employee audit? → YES, with conditions.
│       - Must not have been involved in implementing the specific documents being audited
│       - For small organizations, this may be difficult — use the Lead Consultant instead
│
└── MIXED (consultant and client both implemented Phase 3)
    - Identify which documents each party implemented
    - Assign audit coverage to the party that did NOT implement each area
    - Document the split in the audit plan
    - This is complex — consider using an external auditor for simplicity
```

**What to do if no qualified independent auditor exists:**

This is a common challenge for SMB clients. If the only person with ISO audit knowledge is the same person who implemented the AIMS, escalate to Escalation Trigger E-2. Options include:
1. Train a client employee in ISO internal auditing (minimum 1-day course) — adds 1–2 weeks to timeline
2. Engage a colleague from the consulting firm
3. Engage an external auditor
4. Document the limitation and proceed with the best available option — the certification body will assess independence during Stage 2

#### 2.3 Prepare the Internal Audit Plan

The audit plan is a required document (Clause 9.2 requires a documented audit program). Prepare the following:

**Internal Audit Plan — Required Elements:**

| Element | Content |
|---|---|
| **Audit objectives** | Determine conformity of the AIMS with ISO 42001 requirements and the organization's own AIMS requirements; assess AIMS effectiveness |
| **Audit scope** | All ISO 42001 clauses (4–10) and all applicable Annex A controls within the AIMS scope boundary |
| **Audit criteria** | ISO/IEC 42001:2023; client's AI Policy, AUP, procedures, and documented information |
| **Audit methods** | Document review, interviews, observation of processes |
| **Audit schedule** | Dates, times, and locations for each audit session |
| **Auditees** | Names and roles of individuals to be interviewed |
| **Auditor(s)** | Name(s) and independence basis |
| **Reporting** | Format, distribution, and timeline for audit report |

**Audit Schedule Template:**

| Session | Clause/Control Coverage | Auditee | Duration | Date |
|---|---|---|---|---|
| Opening Meeting | All | Client Sponsor, AIMS Owner, Department Heads | 30 min | Day 1 |
| Context & Leadership | Clauses 4, 5; A.2, A.3 | Client Sponsor, AIMS Owner | 90 min | Day 1 |
| Planning & Risk | Clause 6; A.5 | AIMS Owner | 90 min | Day 1 |
| Support & Awareness | Clause 7; A.4 | AIMS Owner, HR Lead | 60 min | Day 2 |
| Operations — AI Systems | Clause 8; A.6, A.7, A.9 | AIMS Owner, IT Lead | 120 min | Day 2 |
| Supplier Management | A.10 | AIMS Owner, IT Lead or Procurement | 60 min | Day 2 |
| Interested Parties & Disclosure | A.8 | AIMS Owner, relevant Department Heads | 60 min | Day 3 |
| Performance Evaluation | Clause 9 | AIMS Owner | 60 min | Day 3 |
| Improvement | Clause 10 | AIMS Owner | 45 min | Day 3 |
| Closing Meeting | All | Client Sponsor, AIMS Owner, Department Heads | 45 min | Day 3 |

#### 2.4 Notify Auditees

Send the following notification to all auditees at least 5 business days before the audit begins:

**Auditee Notification — Copy/Adapt:**

> Subject: ISO 42001 Internal Audit — [Date Range] — Your Participation Required
>
> [Auditee Name],
>
> As part of our ISO 42001 readiness program, we are conducting an internal audit of our AI Management System from [start date] to [end date].
>
> You are scheduled to participate in the following session:
> - **Date/Time:** [Date and time]
> - **Location/Format:** [In-person location or video call link]
> - **Topics:** [Brief description of audit area — e.g., "AI system operations and monitoring"]
> - **Duration:** [Duration]
>
> The purpose of the internal audit is to verify that our AIMS is working as intended and to identify any areas for improvement before our certification audit. This is not a performance review of individuals — it is an assessment of our management system.
>
> To prepare, please have access to any documentation, records, or systems relevant to your area. The auditor may ask to see evidence of how processes are carried out in practice.
>
> Please confirm your availability by [date]. If you have a conflict, contact [AIMS Owner] immediately so we can reschedule.

#### 2.5 Prepare Audit Checklists

Prepare audit checklists using `template-internal-audit-checklist.md` as the base. Customize for the client's specific AIMS scope, AI systems, and SoA. The checklist should include:

- The specific clause or control being audited
- The audit question or evidence request
- Space to record the evidence reviewed
- Space to record the finding (Conforming / Minor NC / Major NC / Observation)
- Space for auditor notes

**Post-planning actions:**
- [ ] Audit plan approved by Client Sponsor
- [ ] Auditee notifications sent and confirmations received
- [ ] Audit checklists prepared and reviewed
- [ ] Audit logistics confirmed (rooms, video links, document access)

---

### Step 3: Internal Audit Execution (Weeks 2–3)

**Objective:** Conduct the internal audit systematically, gathering objective evidence to determine whether the AIMS conforms to ISO 42001 requirements and is effectively implemented.

**Duration:** 3–5 audit days spread over 2 weeks (allows time for document review between sessions)

#### 3.1 Opening Meeting

The opening meeting sets the tone for the entire audit. Conduct it with all key participants present (Client Sponsor, AIMS Owner, Department Heads).

**Opening Meeting Agenda (30 minutes):**

1. **Introductions** (5 min) — Introduce the auditor(s) and confirm attendees
2. **Audit objectives and scope** (5 min) — Explain what will be audited and why
3. **Audit process** (5 min) — Explain how the audit will be conducted: document review, interviews, observation; findings will be classified; a closing meeting will summarize results
4. **Confidentiality** (2 min) — Audit findings are internal; the report will be distributed to [named recipients] only
5. **Logistics** (3 min) — Confirm schedule, locations, document access arrangements
6. **Questions** (10 min) — Address any questions from auditees

**Key message to communicate:** "The purpose of this audit is to help the organization identify and fix issues before the certification body does. Finding nonconformities now is a good outcome — it means we can address them on our timeline, not the auditor's."

#### 3.2 Audit Methods

Use all three methods for each audit area. Do not rely on document review alone.

**Method 1: Document Review**
- Request and review the documented information relevant to each clause/control
- Verify documents are: current (version-controlled), approved (signed or equivalent), and consistent with each other
- Check that documents reference the correct Annex A control IDs (A.2–A.10 scheme)
- Look for internal consistency: does the SoA match the Risk Register? Does the AI Policy reference the AUP?

**Method 2: Interviews**
- Interview the auditee responsible for each area
- Use the interview scripts in Section 3.3 as a starting point
- Ask open-ended questions — "How does this work in practice?" not "Do you do X?"
- Follow up on answers that seem rehearsed or inconsistent with documents
- Ask to see evidence: "Can you show me an example of that?"

**Method 3: Observation**
- Where possible, observe processes in action
- For AI systems: ask the auditee to demonstrate the tool and show how it is used
- For monitoring processes: ask to see the monitoring logs or dashboards
- For training: ask to see the training platform or records in the system

#### 3.3 Interview Scripts by Clause

Use these scripts as starting points. Adapt based on the client's specific AIMS and AI systems. Always follow up on answers that reveal gaps.

---

**Clause 5 — Leadership Interview Script**

*Auditee: Client Sponsor (CEO, COO, or equivalent top management)*

*Objective: Verify that top management demonstrates leadership and commitment to the AIMS, not just nominal approval.*

**Opening:** "I'd like to understand how leadership engages with the AI Management System. I'll ask about your role, how AI governance fits into the organization's strategy, and how you stay informed about AI-related risks."

1. "Can you describe your role in the AI Management System? What decisions do you make personally regarding AI governance?"
   - *Looking for:* Active engagement, not just document signing. Top management should be able to describe their AIMS responsibilities.

2. "How did you decide on the AI Policy commitments? Were there specific principles or values that drove those choices?"
   - *Looking for:* Evidence that the policy reflects genuine organizational values, not just boilerplate. If the sponsor cannot explain the policy's commitments, it may not be genuinely owned by leadership.

3. "How do you stay informed about AI-related risks in the organization? What information do you receive, and how often?"
   - *Looking for:* A defined reporting mechanism. Top management should receive regular updates on AI risk status, not just at management review.

4. "What resources have you committed to the AIMS? Can you give me examples of decisions you've made to support AI governance?"
   - *Looking for:* Concrete examples — budget allocation, staff time, tool procurement, policy enforcement decisions.

5. "What would you do if you learned that an employee was using an AI tool in a way that violated the Acceptable Use Policy?"
   - *Looking for:* A clear escalation path and willingness to enforce the policy. Vague answers suggest the AUP is not genuinely enforced.

6. "When was the last time AI governance was discussed at a leadership or board level? What was discussed?"
   - *Looking for:* Evidence of ongoing leadership engagement, not just a one-time policy approval.

7. "Can you show me the AI Policy and explain the key commitments it makes?"
   - *Looking for:* The sponsor should be able to locate the document and explain its contents. If they cannot, this is a finding.

*Evidence to request:*
- Signed AI Policy (with approval date and version)
- Any board or leadership meeting minutes referencing AI governance
- Evidence of resource allocation decisions (budget approvals, role assignments)

---

**Clause 6 — Planning Interview Script**

*Auditee: AIMS Owner (primary); may also involve IT Lead or Risk Owner*

*Objective: Verify that the organization has systematically identified AI-related risks and impacts, made treatment decisions, and documented the results in the SoA and Risk Treatment Plan.*

**Opening:** "I'd like to walk through how the organization identifies and manages AI-related risks. I'll ask about the risk assessment process, the impact assessments, and how treatment decisions were made."

1. "Walk me through how the AI risk assessment was conducted. Who was involved, what methodology was used, and how were risks identified?"
   - *Looking for:* A documented, repeatable process. The AIMS Owner should be able to describe the methodology, not just point to the output document.

2. "How did you decide which AI systems required an impact assessment? Can you show me the criteria?"
   - *Looking for:* A documented threshold or criteria (e.g., all Medium and High risk systems). Ad hoc decisions without documented criteria are a finding.

3. "Pick one AI system from the Risk Register and walk me through the risk assessment for that system. How was the risk level determined?"
   - *Looking for:* Consistent application of the risk methodology. The AIMS Owner should be able to explain the reasoning behind the risk rating.

4. "For the same system, what treatment option was selected and why? What controls were implemented?"
   - *Looking for:* A clear link between the risk assessment, the treatment decision, and the implemented controls. The SoA should reflect the treatment decisions.

5. "How does the SoA connect to the Risk Register? Can you show me how a specific risk maps to an Annex A control in the SoA?"
   - *Looking for:* Traceability between risk assessment and control selection. If the AIMS Owner cannot demonstrate this link, the SoA may be incomplete.

6. "When will the risk assessment be reviewed next? What would trigger an unscheduled review?"
   - *Looking for:* A defined review schedule and trigger criteria (e.g., new AI system adopted, significant change in use, incident).

7. "Are there any AI systems that were assessed as High risk? What additional controls were applied?"
   - *Looking for:* Proportionate treatment of high-risk systems. High-risk systems should have more rigorous controls than low-risk systems.

*Evidence to request:*
- AI Risk Register (current version, with approval date)
- AI Impact Assessments for Medium and High risk systems
- Statement of Applicability (current version, with approval)
- Risk Treatment Plan (with implementation status)

---

**Clause 8 — Operation Interview Script**

*Auditee: AIMS Owner and IT Lead (joint session); may also involve Department Heads for specific AI systems*

*Objective: Verify that AI systems are operated in accordance with the AIMS, that controls are implemented in practice, and that monitoring is occurring.*

**Opening:** "I'd like to understand how AI systems are managed day-to-day. I'll ask about how new AI tools are approved, how existing tools are monitored, and how the organization ensures staff use AI responsibly."

1. "If an employee wanted to start using a new AI tool today, what would happen? Walk me through the process from request to approval."
   - *Looking for:* A documented approval process with defined criteria. If the answer is "they'd just start using it," this is a Major NC.

2. "Can you show me an example of a recent AI tool adoption? What documentation was produced?"
   - *Looking for:* Evidence that the process is actually followed, not just documented. Request the approval record, risk assessment, and any deployment documentation.

3. "How do you monitor whether AI tools are being used within their intended parameters? What would alert you if a tool was being misused?"
   - *Looking for:* A defined monitoring mechanism. This could be usage logs, periodic reviews, or incident reporting. "We trust our staff" is not a monitoring control.

4. "Pick one AI system from the inventory. Can you show me its documentation — purpose, capabilities, limitations, data flows?"
   - *Looking for:* Documented information per A.6.2.9. The documentation should be current and accessible.

5. "How do you manage your AI suppliers? When did you last review your key AI vendor relationships?"
   - *Looking for:* Evidence of supplier assessment per A.10.2. The AIMS Owner should be able to show supplier assessment records and describe the review process.

6. "What happens when an AI tool produces an incorrect or unexpected output? Can you give me an example of how that was handled?"
   - *Looking for:* A defined incident or concern reporting process per A.3.3. If no incidents have ever been reported, probe whether the reporting mechanism is actually known to staff.

7. "How do you ensure staff know what they can and cannot do with AI tools? Can you show me the Acceptable Use Policy and how it was communicated?"
   - *Looking for:* The AUP, evidence of communication (training records, email distribution, acknowledgment forms), and evidence that staff can actually locate and understand the policy.

8. "For AI systems that interact with customers or make decisions affecting individuals, how do you ensure appropriate disclosure and human oversight?"
   - *Looking for:* Evidence of A.8.2 (disclosure) and A.9.5 (human oversight) implementation. Ask to see specific examples.

*Evidence to request:*
- AI tool adoption/approval records
- AI System documentation for 2–3 systems (selected by auditor)
- Supplier assessment records
- AUP with communication evidence
- Training completion records
- Any incident or concern reports

---

#### 3.4 What Constitutes Objective Evidence

Objective evidence is information that can be verified — it is not an assertion or a promise. The auditor must base all findings on objective evidence.

**Acceptable objective evidence:**
- Signed, dated documents (policies, procedures, approvals)
- Records with timestamps (training completion logs, meeting minutes, audit logs)
- System screenshots showing configuration or usage
- Email records showing communication or approval
- Physical observation of a process being performed
- Verbal explanation that is consistent with documented procedures and can be corroborated

**Not acceptable as objective evidence:**
- "We do that" without supporting documentation
- Undated or unsigned documents
- Documents that are clearly in draft form
- Verbal assurances that contradict documented procedures
- Plans for future implementation ("we're going to do that")

**When evidence is unavailable:** If an auditee cannot produce evidence for a required activity, this is a finding. Record it as such. Do not accept promises of future evidence — the audit assesses the current state.

#### 3.5 Finding Classification

Every audit finding must be classified. Use the following decision tree:

```
Does the finding represent a failure to meet a requirement?
│
├── YES — Is the requirement from ISO 42001 (Clauses 4–10 or applicable Annex A controls)?
│   │
│   ├── YES — Is the failure systematic or significant?
│   │   │
│   │   ├── YES → MAJOR NONCONFORMITY
│   │   │   Criteria for Major NC:
│   │   │   - Complete absence of a required process or document
│   │   │   - Systematic failure to implement a required control across multiple instances
│   │   │   - Failure that could directly undermine the integrity of the AIMS
│   │   │   - Failure that would prevent the organization from achieving its AIMS objectives
│   │   │   Examples:
│   │   │   - No internal audit has been conducted
│   │   │   - AI Policy has not been approved by top management
│   │   │   - SoA is incomplete (controls not assessed)
│   │   │   - No management review has been conducted
│   │   │   - No training records exist for any staff
│   │   │   Impact: Must be closed before Stage 1 audit can proceed
│   │   │
│   │   └── NO → MINOR NONCONFORMITY
│   │       Criteria for Minor NC:
│   │       - Isolated failure to implement a required control
│   │       - Required document exists but has a specific gap or error
│   │       - Process exists but is not consistently followed
│   │       - Single instance of non-compliance with a documented procedure
│   │       Examples:
│   │       - Impact assessment missing for one Medium-risk AI system
│   │       - Supplier assessment completed but not reviewed on schedule
│   │       - Training records incomplete for 2 of 45 employees
│   │       - AI system documentation missing the "limitations" section
│   │       Impact: Should be closed before Stage 1 audit; must be closed before Stage 2
│   │
│   └── NO — Is the requirement from the organization's own AIMS documents?
│       ├── YES → MINOR NONCONFORMITY (failure to follow own procedures)
│       └── NO → Reassess — may be an Observation
│
└── NO — Does the finding represent a potential improvement opportunity or risk?
    │
    ├── YES → OBSERVATION
    │   Criteria for Observation:
    │   - Not a nonconformity but worth noting for improvement
    │   - A process that meets requirements but could be more effective
    │   - A risk that is not yet a nonconformity but could become one
    │   - A best practice that is not yet implemented
    │   Examples:
    │   - Risk Register is complete but uses inconsistent risk scoring methodology
    │   - Supplier assessments are conducted but findings are not tracked over time
    │   - AI Policy is approved but not easily accessible to all staff
    │   Impact: No corrective action required; client may choose to address
    │
    └── NO → CONFORMING — Document as evidence of conformity
```

#### 3.6 Common Findings in First AIMS Internal Audits

Be alert for these findings, which appear frequently in first-time ISO 42001 internal audits for SMB clients:

| Finding | Typical Classification | Root Cause |
|---|---|---|
| AI Policy approved but not communicated to all staff | Minor NC | Implementation gap — document created but rollout not completed |
| SoA approved but justifications are generic/boilerplate | Minor NC | SoA was completed quickly without genuine analysis |
| Risk Register exists but risk owners have not been notified of their responsibilities | Minor NC | Roles assigned on paper but not operationalized |
| Impact assessments completed but not reviewed/approved by management | Minor NC | Process gap — assessments treated as consultant deliverables, not AIMS records |
| Training records exist but do not cover all in-scope staff | Minor NC | Training rollout incomplete |
| No mechanism for staff to report AI concerns (A.3.3) | Major NC | Control not implemented — often overlooked in Phase 3 |
| Supplier assessments completed but no review schedule established | Minor NC | One-time activity not embedded in ongoing AIMS operations |
| Management review not yet conducted | Major NC | Phase 3 did not include management review facilitation |
| NCAR log exists but no process for how nonconformities are identified and escalated | Minor NC | Log created but process not documented |
| AI system documentation missing for shadow AI tools that were brought into scope | Minor NC | Inventory updated but documentation not completed for all systems |

#### 3.7 Closing Meeting

The closing meeting presents the audit findings to the client before the formal report is issued. This is the client's first opportunity to understand the results.

**Closing Meeting Agenda (45 minutes):**

1. **Thank auditees** (2 min) — Acknowledge cooperation and time
2. **Audit scope confirmation** (3 min) — Confirm what was audited
3. **Positive findings** (5 min) — Acknowledge areas of strong conformity — this is important for morale and credibility
4. **Findings summary** (20 min) — Present each finding: classification, clause/control, description, evidence basis
5. **Next steps** (10 min) — Explain the corrective action process, timeline, and Stage 1 implications
6. **Questions** (5 min)

**Key messages for the closing meeting:**
- "These findings are normal for a first internal audit. Finding them now is the purpose of this exercise."
- "Major nonconformities must be closed before Stage 1. Minor nonconformities should be closed before Stage 1 but must be closed before Stage 2."
- "The certification body will conduct their own audit. Our job is to make sure there are no surprises."

**Post-audit actions:**
- [ ] Document all findings with evidence references
- [ ] Classify each finding (Major NC / Minor NC / Observation)
- [ ] Confirm findings with auditees (no surprises in the report)
- [ ] Begin drafting the Internal Audit Report (Step 4)

---

### Step 4: Internal Audit Report (Week 3)

**Objective:** Produce a formal Internal Audit Report that documents the audit process, findings, and conclusions. This report is a required AIMS record and will be reviewed by the certification body.

**Duration:** 2–3 days (drafting, client review, finalization)

#### 4.1 Required Sections of the Internal Audit Report

The Internal Audit Report must contain the following sections:

**Section 1: Audit Overview**
- Audit objectives
- Audit scope (clauses, controls, organizational units, AI systems)
- Audit criteria (ISO 42001, client's own AIMS documents)
- Audit dates and locations
- Auditor name(s) and independence basis
- Auditees (names and roles)

**Section 2: Audit Methodology**
- Methods used (document review, interviews, observation)
- Sampling approach (if not all instances were reviewed)
- Any limitations on the audit (areas not accessible, documents unavailable)

**Section 3: Summary of Findings**
- Total number of findings by classification (Major NCs, Minor NCs, Observations)
- Overall audit conclusion: Does the AIMS conform to ISO 42001 requirements?
- Key strengths identified
- Key areas for improvement

**Section 4: Detailed Findings**

For each finding, document:

| Field | Content |
|---|---|
| **Finding ID** | Sequential number (e.g., F-001) |
| **Classification** | Major NC / Minor NC / Observation |
| **Clause/Control** | ISO 42001 clause or Annex A control ID |
| **Requirement** | The specific requirement that was not met |
| **Finding Description** | What was found (factual, evidence-based) |
| **Objective Evidence** | The specific evidence that supports the finding |
| **Auditor** | Name of auditor who identified the finding |

**Section 5: Corrective Action Requirements**
- List of all Major and Minor NCs requiring corrective action
- Target closure dates (Major NCs: before Stage 1; Minor NCs: before Stage 2)
- Corrective action owner assignments

**Section 6: Audit Conclusion**
- Overall conformity assessment
- Recommendation regarding Stage 1 audit readiness (with conditions if applicable)
- Next steps

#### 4.2 Writing Findings Effectively

Findings must be factual, specific, and evidence-based. Avoid vague language.

**Poor finding (do not write this):**
> "The organization does not adequately manage AI risks."

**Good finding (write this):**
> "Finding F-003 (Minor NC): Clause 6.1.4 / A.5.3 — AI System Impact Assessment
> Requirement: The organization shall evaluate the impacts of AI systems on individuals and groups.
> Finding: Impact assessments have not been completed for two AI systems classified as Medium risk in the AI Risk Register: HubSpot Lead Scoring (added to inventory 15 January 2026) and Zoom AI Companion (added 3 February 2026). Impact assessments exist for all other Medium and High risk systems.
> Objective Evidence: AI Risk Register v1.2 (dated 28 February 2026) lists HubSpot Lead Scoring and Zoom AI Companion as Medium risk. Impact Assessment folder contains 7 completed assessments; neither HubSpot Lead Scoring nor Zoom AI Companion is included. Confirmed with AIMS Owner during interview on 12 March 2026."

#### 4.3 Communicating Findings to Management Without Causing Panic

The Internal Audit Report will be reviewed by the Client Sponsor. Frame findings appropriately:

**Do:**
- Lead with the overall conclusion and positive findings before presenting nonconformities
- Contextualize findings: "This is a common finding in first AIMS internal audits"
- Be specific about what needs to be done and by when
- Distinguish between what must be fixed before Stage 1 vs. Stage 2
- Emphasize that finding these issues now is the purpose of the internal audit

**Do not:**
- Use language that implies the certification is at risk unless it genuinely is
- Present findings as failures of individuals rather than system gaps
- Overstate the severity of Minor NCs
- Understate the severity of Major NCs — the client needs to understand the urgency

**Distinction between audit findings and certification readiness:**

An internal audit finding is not the same as a certification failure. The internal audit is conducted by the organization itself to identify and fix issues before the certification body arrives. The certification body will conduct their own independent audit. The goal of the internal audit is to ensure that when the certification body audits, they find a conforming AIMS.

A client with 3 Minor NCs from the internal audit, all of which are closed before Stage 1, is in a strong position for certification. A client with 0 internal audit findings who skipped the internal audit entirely is in a weak position — the certification body will find the issues instead.

#### 4.4 Report Distribution and Approval

- Draft report → AIMS Owner for factual accuracy review (48 hours)
- Revised draft → Client Sponsor for review and acceptance
- Final report → Distributed to: Client Sponsor, AIMS Owner, and any other recipients specified in the audit plan
- File the final report in the AIMS records system (this is documented information per Clause 9.2)

**Post-report actions:**
- [ ] Internal Audit Report finalized and approved
- [ ] All findings logged in the NCAR Log
- [ ] Corrective action owners notified
- [ ] Proceed to Step 5

---

### Step 5: Corrective Action Management (Weeks 3–4)

**Objective:** Ensure that every nonconformity identified in the internal audit is addressed through a documented corrective action process that eliminates the root cause and prevents recurrence.

**Duration:** 1–2 weeks (varies by number and complexity of findings)

**Critical timeline rule:** All Major NCs must be closed before the Stage 1 audit. Minor NCs should be closed before Stage 1 but must be closed before Stage 2. Do not proceed to Stage 1 with open Major NCs — see Escalation Trigger E-1.

#### 5.1 Corrective Action Process

For each Major NC and Minor NC from the internal audit, execute the following process:

**Step 5.1.1: Record the Nonconformity**

Open a new entry in the NCAR Log with:
- Finding ID (from Internal Audit Report)
- Classification (Major NC / Minor NC)
- Clause/control reference
- Finding description (copy from audit report)
- Date identified
- Owner assigned

**Step 5.1.2: Root Cause Analysis**

The corrective action must address the root cause, not just the symptom. Use the following approach:

*For each nonconformity, ask "Why?" at least three times:*

**Example:**
- Finding: Impact assessment missing for HubSpot Lead Scoring
- Why? → The AIMS Owner did not know it needed an impact assessment
- Why? → The criteria for which systems require impact assessments were not clearly communicated
- Why? → The impact assessment procedure does not include a clear trigger/threshold definition
- Root cause: The impact assessment procedure lacks a documented threshold for when assessments are required

*Common root causes in first AIMS implementations:*

| Root Cause Category | Description | Typical Corrective Action |
|---|---|---|
| **Process gap** | A required process was not defined or documented | Define and document the process; train relevant staff |
| **Communication gap** | Process exists but was not communicated to those responsible | Communicate the process; update training; verify understanding |
| **Implementation gap** | Process was defined and communicated but not followed | Investigate why; address barriers; verify implementation |
| **Resource gap** | Process could not be followed due to lack of time, tools, or skills | Allocate resources; adjust scope or timeline |
| **Scope gap** | The process was applied to some but not all required instances | Extend the process to all required instances; update procedure |

**Step 5.1.3: Corrective Action Plan**

Document the corrective action plan in the NCAR Log:
- Corrective action description (what will be done)
- Owner (who is responsible)
- Target completion date
- Verification method (how will closure be confirmed)

**Step 5.1.4: Implementation**

The corrective action owner implements the planned action. The consultant's role is to:
- Provide guidance on what constitutes adequate corrective action
- Review draft documents or records produced as part of the corrective action
- Confirm that the corrective action addresses the root cause, not just the symptom

**Step 5.1.5: Verification and Closure**

Before closing a corrective action:
- [ ] The corrective action has been implemented as planned
- [ ] Objective evidence of implementation exists (document, record, screenshot)
- [ ] The root cause has been addressed (not just the symptom)
- [ ] The evidence is sufficient to satisfy a certification auditor

Update the NCAR Log:
- Actual completion date
- Evidence reference (document name, version, date)
- Verification notes
- Status: CLOSED

#### 5.2 Timeline Management

Track corrective action status against the Stage 1 audit date. Use the following tracking approach:

| Finding ID | Classification | Owner | Target Date | Status | Evidence |
|---|---|---|---|---|---|
| F-001 | Major NC | AIMS Owner | [Date — before Stage 1] | Open / In Progress / Closed | [Reference] |
| F-002 | Minor NC | IT Lead | [Date — before Stage 1] | Open / In Progress / Closed | [Reference] |
| F-003 | Minor NC | HR Lead | [Date — before Stage 2] | Open / In Progress / Closed | [Reference] |

**Weekly check-in:** During Weeks 3–4, conduct a brief weekly check-in with the AIMS Owner to review corrective action status. Escalate any items at risk of missing their target date.

#### 5.3 What Constitutes Adequate Corrective Action Evidence

The certification body will review corrective action evidence during Stage 2. Evidence must demonstrate that:

1. The nonconformity was recorded (NCAR Log entry)
2. The root cause was analyzed (documented root cause analysis)
3. A corrective action was planned (corrective action plan in NCAR Log)
4. The corrective action was implemented (objective evidence of implementation)
5. The effectiveness of the corrective action was verified (verification notes)

**Evidence examples by finding type:**

| Finding Type | Adequate Evidence |
|---|---|
| Missing document | Completed, approved document with version and date |
| Unapproved document | Approval signature/record with date |
| Staff not trained | Training completion records for previously untrained staff |
| Process not followed | Updated procedure + evidence of new process being followed |
| Supplier assessment missing | Completed supplier assessment with date |

**Post-corrective action actions:**
- [ ] All Major NCs closed with evidence before Stage 1 date
- [ ] All Minor NCs closed or in progress with documented plans
- [ ] NCAR Log updated with closure evidence for all closed items
- [ ] Corrective action summary prepared for management review (Step 6)

---

### Step 6: Management Review Facilitation (Week 4)

**Objective:** Facilitate the management review required by Clause 9.3. The management review is a required AIMS activity and a common focus point for certification auditors. It must be documented and must cover all required inputs.

**Duration:** 2–3 hours for the review meeting; 1 day for preparation and documentation

**Critical requirement:** The management review must be conducted by top management (Client Sponsor or equivalent). The consultant facilitates but does not conduct the review. The review must be documented — a meeting record is required AIMS documented information.

#### 6.1 Management Review Preparation

Prepare the following before the management review meeting:

**Input Package — Assemble and distribute to participants at least 3 business days before the meeting:**

1. **Internal audit results** — Summary of findings from Step 4 (Major NCs, Minor NCs, Observations, overall conclusion)
2. **Corrective action status** — Summary of NCAR Log status (open, in progress, closed items)
3. **AI risk and opportunity status** — Summary of current risk register status; any new risks identified since last review
4. **AIMS performance data** — Any metrics collected on AIMS effectiveness (training completion rates, supplier assessment completion, incident reports)
5. **Interested party feedback** — Any feedback from customers, employees, regulators, or other interested parties regarding AI governance
6. **Changes affecting the AIMS** — Any organizational changes, new AI systems adopted, regulatory changes, or vendor changes since the AIMS was established
7. **Previous management review actions** — Status of any actions from previous management reviews (for first review, this section will be N/A)
8. **Opportunities for improvement** — Observations from the internal audit; any improvement opportunities identified during Phase 4

Use `template-management-review.md` as the agenda and documentation template.

#### 6.2 Required Inputs per Clause 9.3

Verify that the management review input package addresses all Clause 9.3 required inputs:

- [ ] Status of actions from previous management reviews (Clause 9.3.2a) — N/A for first review; document as such
- [ ] Changes in external and internal issues relevant to the AIMS (Clause 9.3.2b)
- [ ] Information on AIMS performance and effectiveness, including trends in nonconformities and corrective actions (Clause 9.3.2c)
- [ ] Monitoring and measurement results (Clause 9.3.2d)
- [ ] Audit results (Clause 9.3.2e)
- [ ] Fulfillment of AI objectives (Clause 9.3.2f)
- [ ] Performance of external providers (Clause 9.3.2g)
- [ ] Adequacy of resources (Clause 9.3.2h)
- [ ] Effectiveness of actions taken to address risks and opportunities (Clause 9.3.2i)
- [ ] Opportunities for continual improvement (Clause 9.3.2j)

#### 6.3 How to Facilitate the Management Review

The consultant's role is to facilitate, not to present. Top management must engage with the inputs and make decisions — the review cannot be a consultant presentation that management passively observes.

**Facilitation approach:**

1. **Open the meeting** — Confirm attendees, confirm the agenda, explain the purpose (this is a required AIMS activity; the outputs will be documented and reviewed by the certification body)

2. **Walk through each input** — For each required input, present the summary and ask management to discuss:
   - "What does this tell us about how the AIMS is performing?"
   - "Are there any concerns or actions needed?"
   - "Are the resources allocated to the AIMS adequate?"

3. **Drive to decisions** — The management review must produce documented outputs (see Section 6.4). For each agenda item, ensure a decision or action is recorded.

4. **Avoid consultant-led conclusions** — If management is passive, prompt them: "Based on the internal audit results, what is your assessment of the AIMS's effectiveness?" Do not answer for them.

5. **Close the meeting** — Summarize decisions and actions; confirm owners and target dates; confirm the next management review date

**Common facilitation challenges:**

| Challenge | Response |
|---|---|
| Management wants to delegate the review to the AIMS Owner | Explain that Clause 9.3 requires top management to conduct the review. The AIMS Owner can present inputs, but decisions must be made by top management. |
| Management has not read the input package | Briefly summarize each input during the meeting. Note in the minutes that the input package was distributed [date] and reviewed during the meeting. |
| Management wants to skip the review and just sign the minutes | This is not acceptable. The review must be a genuine discussion. If management is resistant, see Escalation Trigger E-3. |
| Management raises concerns about the AIMS that were not in the input package | Document these concerns in the minutes. They may generate new corrective actions or improvement opportunities. |

#### 6.4 Required Outputs of the Management Review

The management review must produce documented outputs addressing:

- [ ] **Conclusions on AIMS suitability, adequacy, and effectiveness** — Top management's overall assessment of whether the AIMS is fit for purpose
- [ ] **Decisions on continual improvement opportunities** — Specific improvement actions identified, with owners and target dates
- [ ] **Decisions on resource needs** — Any decisions to allocate additional resources (budget, staff time, tools) to the AIMS
- [ ] **Decisions on changes to the AIMS** — Any decisions to change the scope, policies, objectives, or processes of the AIMS
- [ ] **Actions required** — Specific actions assigned to named individuals with target dates

**Management Review Minutes — Required Structure:**

```
Management Review Minutes
Date: [Date]
Attendees: [Names and roles]
Facilitator: [Name]

1. Purpose and Agenda Confirmation
2. Review of Previous Actions (N/A for first review)
3. Internal Audit Results — Summary and Discussion
   Decision/Action: [Record here]
4. Corrective Action Status — Summary and Discussion
   Decision/Action: [Record here]
5. Risk and Opportunity Status — Summary and Discussion
   Decision/Action: [Record here]
6. AIMS Performance Data — Summary and Discussion
   Decision/Action: [Record here]
7. Interested Party Feedback — Summary and Discussion
   Decision/Action: [Record here]
8. Changes Affecting the AIMS — Summary and Discussion
   Decision/Action: [Record here]
9. Resource Adequacy — Discussion
   Decision/Action: [Record here]
10. Opportunities for Improvement — Discussion
    Decision/Action: [Record here]
11. Overall AIMS Assessment
    Conclusion: [Top management's conclusion on AIMS suitability, adequacy, and effectiveness]
12. Actions Summary
    [Table: Action | Owner | Target Date]
13. Next Management Review Date: [Date]

Approved by: [Client Sponsor signature]
Date: [Date]
```

**Post-management review actions:**
- [ ] Management Review Minutes finalized and approved by Client Sponsor
- [ ] All actions from the review logged with owners and target dates
- [ ] Minutes filed as AIMS documented information
- [ ] Any new corrective actions added to the NCAR Log
- [ ] Proceed to Step 7

---

### Step 7: Mock Audit (Weeks 4–5)

**Objective:** Simulate the certification body's Stage 1 document review to identify any remaining gaps before the actual Stage 1 audit. The mock audit gives the client a realistic preview of what the certification body will request and how they will assess the AIMS.

**Duration:** 1–2 days (document review simulation + debrief)

**Important distinction:** The mock audit simulates Stage 1 (document review), not Stage 2 (on-site audit). Stage 1 is primarily a desk review — the certification body checks that all required documents exist, are adequate, and demonstrate that the AIMS is ready for Stage 2. Stage 2 (on-site audit) is covered in Phase 5.

#### 7.1 What the Certification Body Will Request at Stage 1

The certification body's Stage 1 audit typically involves:

1. **Document index review** — The auditor will request a list of all AIMS documented information and verify that required documents exist
2. **Key document review** — The auditor will read and assess the adequacy of key documents (AI Policy, SoA, Scope Statement, Risk Register, Internal Audit Report, Management Review Minutes)
3. **Scope adequacy assessment** — The auditor will verify that the AIMS scope is appropriate and that the scope statement is clear
4. **SoA completeness check** — The auditor will verify that all 39 Annex A controls are addressed and that exclusion justifications are adequate
5. **Internal audit and management review verification** — The auditor will confirm that both activities have been conducted and documented
6. **Stage 2 readiness assessment** — The auditor will determine whether the AIMS is sufficiently developed to proceed to Stage 2

**Common Stage 1 findings (what the certification body typically flags):**

| Finding | Why It Happens | How to Avoid It |
|---|---|---|
| SoA incomplete — controls not assessed or justifications inadequate | SoA was completed quickly without genuine analysis | Review every control in the SoA; ensure justifications are specific to the organization |
| AI Policy not approved by top management | Policy was drafted but approval step was missed | Verify approval signature and date before Stage 1 |
| Internal audit not conducted | Client skipped the internal audit | Never skip the internal audit — it is a Stage 1 requirement |
| Management review not documented | Review was conducted informally without minutes | Ensure minutes are complete and approved before Stage 1 |
| Scope statement ambiguous | Scope was defined broadly without clear boundaries | Review scope statement for clarity; an auditor should be able to determine what's in and out |
| Risk Register not linked to SoA | Risk assessment and control selection were done independently | Verify traceability between Risk Register treatment decisions and SoA control selections |
| No evidence of corrective action process | NCAR Log exists but no process for how NCs are identified | Ensure the corrective action procedure is documented and the NCAR Log has at least one entry |

#### 7.2 Mock Audit Execution

Conduct the mock audit as a structured document review. The Lead Consultant plays the role of the certification body auditor.

**Mock Audit Session 1: Document Index Review (60 minutes)**

Request the AIMS Owner to present the complete document index. For each required document, verify:
- [ ] Document exists
- [ ] Document is the current approved version
- [ ] Document is accessible (not buried in a folder no one can find)
- [ ] Document is version-controlled (version number, date, approval)

**Required AIMS Documents Checklist:**

| Document | Required By | Status |
|---|---|---|
| AIMS Scope Statement | Clause 4.3 | |
| AI Policy | Clause 5.2 / A.2.2 | |
| Acceptable Use Policy | A.6.2.10 | |
| AI Objectives | Clause 6.2 | |
| AI Risk Register | Clause 6.1.2 | |
| AI Impact Assessments | Clause 6.1.4 / A.5.3 | |
| Statement of Applicability | Clause 6.1.6 | |
| Risk Treatment Plan | Clause 6.1.3 | |
| AI System Inventory / Documentation | A.6.2.9 | |
| Roles and Responsibilities | Clause 5.3 / A.3.2 | |
| Competency Records | Clause 7.2 / A.4.3 | |
| Training Records | Clause 7.3 / A.4.4 | |
| Supplier Assessments | A.10.2 | |
| Internal Audit Plan | Clause 9.2 | |
| Internal Audit Report | Clause 9.2 | |
| Management Review Minutes | Clause 9.3 | |
| NCAR Log | Clause 10.1 | |
| Corrective Action Records | Clause 10.1 | |
| Document Control Procedure | Clause 7.5 | |

**Mock Audit Session 2: Key Document Deep Review (90 minutes)**

Review the following documents in detail, assessing adequacy as a certification auditor would:

1. **AI Policy** — Does it address all required elements? Is it approved? Does it reference responsible AI principles (A.2.3)?
2. **Statement of Applicability** — Are all 39 controls assessed? Are exclusion justifications specific and credible? Is it approved?
3. **AI Risk Register** — Are all in-scope AI systems assessed? Is the methodology documented? Are treatment decisions linked to the SoA?
4. **Internal Audit Report** — Was the audit conducted by an independent auditor? Does it cover all required clauses? Are findings documented with objective evidence?
5. **Management Review Minutes** — Were all required inputs addressed? Are decisions and actions documented? Is it approved by top management?

**Mock Audit Session 3: Gap Identification and Debrief (60 minutes)**

Present findings from the mock audit to the AIMS Owner and Client Sponsor:
- Documents that are missing or incomplete
- Documents that exist but have adequacy concerns
- Areas where the AIMS is strong
- Recommended actions before Stage 1

#### 7.3 Preparing the Client for Auditor Interaction Style

Certification body auditors vary in style, but most Stage 1 audits follow a predictable pattern. Prepare the client for:

**What to expect:**
- The auditor will request documents in advance (typically 2–4 weeks before Stage 1)
- Stage 1 is primarily a desk review — the auditor may not visit the client's premises
- The auditor will ask clarifying questions about documents; these are not trick questions
- The auditor will issue a Stage 1 report with findings and a recommendation on Stage 2 readiness

**How to respond to auditor requests:**
- Respond promptly to document requests (within the timeframe specified)
- Provide documents in the format requested (PDF is standard)
- Do not provide more documents than requested — answer the question asked
- If a document is not yet finalized, say so — do not provide a draft as if it were final

**How to handle auditor questions:**
- Answer the question asked, concisely
- If you don't know the answer, say "I'll need to check and get back to you" — do not guess
- If the auditor identifies a concern, listen carefully before responding
- Do not argue with the auditor — note the concern and address it

**Post-mock audit actions:**
- [ ] Mock Audit Report prepared (findings, recommendations, remaining gaps)
- [ ] Remaining gaps assigned to owners with target dates before Stage 1
- [ ] Client briefed on Stage 1 process and auditor interaction
- [ ] Proceed to Step 8

---

### Step 8: Stage 1 Audit Preparation (Weeks 5–6)

**Objective:** Assemble the complete Stage 1 Audit Readiness Package, brief the client on the Stage 1 process, and ensure the client is fully prepared to respond to the certification body's document requests.

**Duration:** 1–2 weeks (package assembly, client coaching, final verification)

#### 8.1 Stage 1 Readiness Gate — Go/No-Go Decision

Before proceeding to Stage 1, conduct a formal readiness assessment. Use the following decision tree:

```
Stage 1 Readiness Gate
│
├── CRITICAL REQUIREMENTS (all must be YES to proceed)
│   │
│   ├── Is the AI Policy approved by top management? → YES / NO
│   ├── Is the SoA complete (all 39 controls assessed and justified)? → YES / NO
│   ├── Has the internal audit been conducted and documented? → YES / NO
│   ├── Has the management review been conducted and documented? → YES / NO
│   ├── Are all Major NCs from the internal audit closed with evidence? → YES / NO
│   └── Is the AIMS Scope Statement approved and unambiguous? → YES / NO
│
│   If ANY critical requirement is NO → DO NOT PROCEED TO STAGE 1
│   - Identify the gap and assign a corrective action with an urgent target date
│   - Notify Client Sponsor of the delay and its cause
│   - Reschedule Stage 1 audit if necessary
│   - See Escalation Trigger E-1 if Major NCs cannot be closed in time
│
├── IMPORTANT REQUIREMENTS (should be YES; document any NOs)
│   │
│   ├── Are all Minor NCs from the internal audit closed or have documented plans? → YES / NO
│   ├── Are all in-scope AI systems documented (A.6.2.9)? → YES / NO
│   ├── Are supplier assessments complete for all key AI providers? → YES / NO
│   ├── Are training records complete for all in-scope staff? → YES / NO
│   └── Is the document index complete and organized? → YES / NO
│
│   If any important requirement is NO → Document the gap and prepare an explanation
│   for the certification body. Stage 1 can proceed but the gap should be addressed
│   before Stage 2.
│
└── ALL CRITICAL REQUIREMENTS MET → PROCEED TO STAGE 1
    - Assemble Stage 1 Readiness Package (Section 8.2)
    - Brief client on Stage 1 process (Section 8.3)
    - Confirm Stage 1 date with certification body
```

#### 8.2 Assemble the Stage 1 Audit Readiness Package

The Stage 1 Readiness Package is the complete set of documents the client will provide to the certification body. Use `template-pre-audit-checklist.md` as the assembly guide.

**Package Contents:**

**Section A: AIMS Foundation Documents**
- AIMS Scope Statement (current approved version)
- AI Policy (current approved version)
- Statement of Applicability (current approved version)
- AI Objectives (current approved version)

**Section B: Risk and Impact Documentation**
- AI Risk Register (current approved version)
- AI Impact Assessments (all completed assessments)
- Risk Treatment Plan (current approved version)

**Section C: Operational Controls**
- AI System Inventory / Documentation (all in-scope systems)
- Acceptable Use Policy (current approved version)
- Supplier Assessments (all completed assessments)
- Roles and Responsibilities documentation

**Section D: People and Awareness**
- Training Records (all in-scope staff)
- Competency Records (where applicable)

**Section E: Performance Evaluation Records**
- Internal Audit Plan
- Internal Audit Report (final approved version)
- Management Review Minutes (final approved version)
- NCAR Log (current, showing all findings and closure status)
- Corrective Action Records (evidence of closure for all Major NCs)

**Section F: Supporting Procedures**
- Document Control Procedure
- Internal Audit Procedure
- Corrective Action Procedure
- Management Review Procedure (or agenda template)

**Document Index:**

Prepare a master document index listing every document in the package:

| # | Document Title | Version | Date | Approval | Location in Package |
|---|---|---|---|---|---|
| 1 | AIMS Scope Statement | v1.1 | [Date] | [Approver] | Section A |
| 2 | AI Policy | v1.2 | [Date] | [Approver] | Section A |
| ... | ... | ... | ... | ... | ... |

#### 8.3 Brief the Client on the Stage 1 Process

Conduct a 60-minute briefing session with the Client Sponsor and AIMS Owner covering:

**What Stage 1 is:**
- A document review conducted by the certification body
- The auditor assesses whether the AIMS is sufficiently developed to proceed to Stage 2
- Stage 1 is typically conducted remotely (document submission + video call)
- Duration: typically 1–2 days of auditor time

**What Stage 1 is not:**
- An on-site audit (that is Stage 2)
- A pass/fail test — Stage 1 findings can be addressed before Stage 2
- A surprise — the auditor will follow a structured process based on the standard

**What happens after Stage 1:**
- The certification body issues a Stage 1 report
- The report will include: findings (if any), a recommendation on Stage 2 readiness, and a proposed Stage 2 date
- If Stage 1 findings are raised, the client must address them before Stage 2
- If Stage 1 is passed, Stage 2 is scheduled (typically 4–8 weeks later)

**The client's role during Stage 1:**
- Respond to document requests promptly and completely
- Be available for clarifying questions (typically via email or video call)
- Do not provide documents that are not yet finalized
- Contact the consultant immediately if the auditor raises a concern

#### 8.4 Coach the Client on Responding to Auditor Requests

**Document request response protocol:**
1. Acknowledge the request within 24 hours
2. Provide the requested documents within the timeframe specified (typically 5–10 business days)
3. Provide documents in PDF format unless otherwise specified
4. Use the document index to locate documents quickly
5. If a requested document does not exist, say so — do not substitute a different document

**Handling auditor questions:**
- Read the question carefully before responding
- Answer the specific question asked — do not provide additional context unless asked
- If the question is about a process, describe how the process works in practice
- If the question is about a document, reference the specific document and section
- If you are unsure, say "I'll need to check and get back to you by [date]"

**If the auditor identifies a concern:**
- Do not argue or become defensive
- Ask for clarification: "Can you help me understand what specific requirement you're assessing against?"
- Note the concern and discuss with the consultant before responding
- Do not make commitments to the auditor without consulting the consultant first

#### 8.5 Common Stage 1 Findings and How to Avoid Them

| Stage 1 Finding | Prevention |
|---|---|
| SoA exclusion justifications are generic | Review each NOT APPLICABLE control and write a specific justification referencing the organization's context (e.g., "A.6.2.2 is not applicable because [Organization] does not design or develop AI systems; all AI systems in scope are third-party products accessed via commercial subscription") |
| AI Policy does not address all required responsible AI topics (A.2.3) | Review the AI Policy against A.2.3 requirements: fairness, transparency, accountability, human oversight, privacy, safety, societal impact — all must be addressed |
| Internal audit report does not demonstrate auditor independence | Ensure the audit plan documents the auditor's independence basis; the auditor's name and role must be clearly stated |
| Management review minutes do not address all required inputs | Use the Clause 9.3 checklist (Section 6.2) to verify all inputs are addressed in the minutes |
| Risk Register does not link to SoA | Add a column to the Risk Register showing which Annex A controls address each risk; verify consistency with the SoA |
| AIMS objectives are not measurable | Review AI Objectives against Clause 6.2 requirements: objectives must be measurable, have a target, have an owner, and have a timeline |

**Post-preparation actions:**
- [ ] Stage 1 Readiness Package assembled and reviewed
- [ ] Document index complete and accurate
- [ ] Client briefed on Stage 1 process
- [ ] Stage 1 date confirmed with certification body
- [ ] Consultant availability confirmed for Stage 1 support (Step 9)

---

### Step 9: Stage 1 Audit Support (Week 6)

**Objective:** Support the client during the Stage 1 audit, help manage auditor interactions, and prepare for any Stage 1 findings and the transition to Stage 2 planning.

**Duration:** 1–3 days (varies by certification body and audit scope)

#### 9.1 Consultant Role During Stage 1

The consultant's role during Stage 1 is to support the client, not to conduct the audit or speak on the client's behalf. The certification body is auditing the client's AIMS — the client must demonstrate ownership.

**What the consultant does during Stage 1:**
- Remains available (on-call or on-site) throughout the Stage 1 audit
- Reviews auditor questions before the client responds (if time permits)
- Helps the client locate documents quickly
- Advises the client on how to respond to auditor concerns
- Takes notes on auditor questions and concerns for follow-up

**What the consultant does NOT do during Stage 1:**
- Answer auditor questions on behalf of the client
- Argue with the auditor about findings
- Provide documents that were not in the Stage 1 Readiness Package without client approval
- Make commitments to the auditor on the client's behalf

#### 9.2 Handling Auditor Questions During Stage 1

When the auditor asks a question:

1. **Pause before responding** — Do not answer immediately. Take a moment to understand what is being asked.
2. **Identify the relevant document** — Most Stage 1 questions can be answered by pointing to a specific document. Use the document index.
3. **Answer specifically** — Reference the document, section, and version. "Our AI Policy, version 1.2, approved [date], addresses this in Section 3."
4. **If the answer is not in a document** — Describe the process and offer to provide supporting evidence. "Our process for [X] is described in [procedure]. I can provide an example of [evidence] if that would be helpful."
5. **If you don't know** — "I'll need to check and get back to you. Can I respond by [time/date]?"

#### 9.3 What to Do If Stage 1 Findings Are Raised

Stage 1 findings are not uncommon, even for well-prepared clients. They do not automatically prevent Stage 2 from proceeding.

**Types of Stage 1 findings:**

| Finding Type | Impact | Response |
|---|---|---|
| **Observation** | No action required; may be addressed before Stage 2 | Note the observation; decide whether to address before Stage 2 |
| **Minor finding** | Must be addressed before Stage 2; does not prevent Stage 2 scheduling | Develop a corrective action plan; provide to certification body before Stage 2 |
| **Major finding** | Must be resolved before Stage 2 can proceed | Develop and implement corrective action; provide evidence to certification body for review before Stage 2 is scheduled |
| **Stage 2 not recommended** | Stage 2 cannot proceed until significant gaps are addressed | Assess the scope of gaps; develop a remediation plan; request a follow-up Stage 1 review |

**If Stage 1 findings are raised:**
1. Do not react defensively during the audit — note the finding and thank the auditor
2. After the audit session, review the finding with the consultant
3. Determine whether the finding is valid (most are) or whether there is a misunderstanding
4. If there is a misunderstanding, prepare a written clarification with supporting evidence
5. If the finding is valid, develop a corrective action plan and timeline
6. Communicate the corrective action plan to the certification body in writing

#### 9.4 Transition to Stage 2 Planning

After Stage 1 is complete:

1. **Review the Stage 1 report** — Read the certification body's Stage 1 report carefully. Note all findings, observations, and the Stage 2 recommendation.
2. **Address Stage 1 findings** — Implement corrective actions for any Stage 1 findings before Stage 2.
3. **Confirm Stage 2 date** — Work with the certification body to confirm the Stage 2 date. Typical lead time is 4–8 weeks after Stage 1.
4. **Brief the client on Stage 2** — Stage 2 is an on-site audit. The certification body will interview staff, observe processes, and verify that the AIMS is implemented in practice. This is covered in Phase 5.
5. **Handoff to Phase 5** — Prepare the Phase 5 handoff package: Stage 1 report, open findings, Stage 2 date, and any areas requiring additional preparation.

**Post-Stage 1 actions:**
- [ ] Stage 1 report received and reviewed
- [ ] Stage 1 findings documented and corrective actions planned
- [ ] Stage 2 date confirmed
- [ ] Phase 5 handoff package prepared
- [ ] Client briefed on Stage 2 process

---

## 8. Referenced Documents

| Document | Location | Usage |
|---|---|---|
| Controlled Vocabulary | `00-foundation/glossary.md` | Term definitions used throughout this procedure |
| Annex A Control Reference | `00-foundation/annex-a-reference.md` | Control IDs and applicability ratings referenced throughout |
| Internal Audit Checklist Template | `04-pre-audit/template-internal-audit-checklist.md` | Used in Step 2.5 to prepare audit checklists |
| Management Review Template | `04-pre-audit/template-management-review.md` | Used in Step 6 to prepare and document the management review |
| Pre-Audit Checklist Template | `04-pre-audit/template-pre-audit-checklist.md` | Used in Step 8.2 to assemble the Stage 1 Readiness Package |
| NCAR Log Template | `03-remediation/template-ncar-log.md` | Used in Step 5 to track nonconformities and corrective actions |
| Phase 1 Procedure | `01-discovery/procedure-discovery-scoping.md` | Reference for Phase 1 outputs that feed into Phase 4 |
| Traceability Matrix | `00-foundation/traceability-matrix.md` | Maps Phase 4 outputs to ISO 42001 clause requirements |

---

## 9. Escalation Triggers

Monitor for the following conditions throughout Phase 4. When triggered, take the specified action.

| ID | Trigger Condition | Action |
|---|---|---|
| **E-1** | Client has unclosed Major NCs at the Stage 1 audit date | Do not proceed to Stage 1. Notify Client Sponsor immediately. Assess whether the Major NC can be closed within 5 business days (emergency closure). If yes, request a brief postponement of Stage 1 from the certification body. If no, reschedule Stage 1 to allow adequate time for corrective action. Document the delay and its cause. Note: proceeding to Stage 1 with open Major NCs will result in Stage 1 failure and damage the client relationship. |
| **E-2** | No qualified independent internal auditor is available | Escalate to senior consultant immediately. Options: (a) engage a qualified colleague from the consulting firm to conduct the audit; (b) train a client employee in ISO internal auditing (adds 1–2 weeks); (c) engage an external auditor. Do not allow the AIMS implementer to audit their own work — this is a fundamental independence violation that the certification body will identify. Document the resolution in the audit plan. |
| **E-3** | Management review has not been completed by Week 4 | Escalate to Client Sponsor immediately. The management review is a Stage 1 requirement — the certification body will request the minutes. If the Client Sponsor is unavailable, request an emergency 60-minute session. If the review cannot be completed before Stage 1, Stage 1 must be postponed. Do not proceed to Stage 1 without documented management review minutes. |
| **E-4** | Critical AIMS documents (AI Policy, SoA, Scope Statement) are not approved by top management at the start of Phase 4 | Pause Phase 4 activities for the affected area. Notify Client Sponsor that document approval is blocking the internal audit. Provide a 48-hour deadline for approval. If approval is not obtained within 48 hours, escalate to senior consultant and assess whether the Phase 4 timeline needs to be extended. Document the delay. |
| **E-5** | Client wants to skip the internal audit | Refuse. Explain clearly: (a) the internal audit is required by ISO 42001 Clause 9.2; (b) the certification body will ask for the internal audit report at Stage 1; (c) if no internal audit has been conducted, Stage 1 will fail; (d) the purpose of the internal audit is to find and fix issues before the certification body does — skipping it means the certification body finds the issues instead. If the client insists, document the refusal in writing and escalate to senior consultant. |
| **E-6** | Internal audit identifies a previously unknown Major NC that cannot be closed before Stage 1 | Assess the severity and scope of the finding. If the finding represents a fundamental gap in the AIMS (e.g., a required process does not exist), Stage 1 must be postponed. Develop a corrective action plan with the client. Notify the certification body of the postponement. Do not attempt to conceal the finding or proceed to Stage 1 hoping the certification body will not identify it. |
| **E-7** | Certification body raises a Stage 1 finding that the consultant believes is incorrect | Do not argue with the auditor during the audit. After the session, review the finding carefully with the client. If the finding appears to be based on a misunderstanding, prepare a written clarification with supporting evidence and submit it to the certification body through the appropriate channel. If the finding is valid, develop a corrective action plan. In either case, respond professionally and promptly. |

---

## 10. Revision History

| Version | Date | Author | Changes |
|---|---|---|---|
| 1.0 | March 2026 | [Author] | Initial release |

---

*ISO 42001 Readiness Service Toolkit | 04-Pre-Audit | Internal Use*
