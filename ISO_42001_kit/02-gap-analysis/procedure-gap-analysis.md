# Internal Procedure: Phase 2 — Gap Analysis

> **Current as of:** March 2026 | ISO/IEC 42001:2023

> **Document type:** Internal Procedure — Not for client distribution

---

## 1. Purpose

This procedure defines how to execute Phase 2 of an ISO 42001 readiness engagement. Phase 2 assesses the client's current state against every requirement of ISO/IEC 42001:2023 and produces a prioritized gap analysis that drives Phase 3 remediation planning. Specifically, Phase 2:

- Evaluates the client's existing practices against all Clauses 4–10 of ISO/IEC 42001:2023
- Assesses applicability and current implementation status of all 39 Annex A controls
- Assigns maturity scores (0–5) to each clause group and control domain
- Classifies gaps by severity (Critical, Major, Minor, Observation)
- Produces a prioritized remediation roadmap that feeds directly into Phase 3

A junior consultant with ISO management system experience (ISO 27001, ISO 9001, or similar) but no prior ISO 42001 experience should be able to execute this procedure by following each step as written. The procedure is calibrated for SMB clients (40–200 employees) that **use** third-party AI systems and do not develop, train, or provide AI systems.

---

## 2. Scope

This procedure covers Phase 2 of any ISO 42001 readiness engagement for SMB AI-user clients. It begins after the Phase 1 Summary Report has been delivered and accepted, and ends with the delivery of the Gap Analysis Report and a Phase 3 kickoff meeting.

This procedure does not cover:
- AI development, model training, or AI provider obligations
- GRC platform configuration or tool-specific setup
- ISO 27001 integration procedures (integration opportunities are noted where relevant)
- Phase 3 remediation planning (covered in a separate procedure)

---

## 3. Roles

| Role | Responsibility in Phase 2 |
|---|---|
| **Lead Consultant** | Executes this procedure. Conducts all assessment interviews, reviews all evidence, scores all clauses and controls, produces all deliverables. |
| **Client Sponsor** | Provides access to personnel and documentation. Reviews and accepts the Gap Analysis Report. Participates in the Phase 2 closing presentation. |
| **Client IT Lead** | Primary technical contact for Clause 6 (Operation), Clause 7 (Support — documented information), and Annex A technical controls. Provides system documentation and access logs. |
| **Client Compliance/Risk Lead** | Primary contact for Clause 5 (Leadership), Clause 6 (Planning), and Clause 9 (Performance). If no dedicated role exists, the Client Sponsor fills this function. |
| **Department Heads** | Participate in targeted interviews for Clause 8 (Operation) and Annex A use-of-AI controls. Typically 30–45 minutes each. |

---

## 4. Inputs

| Input | Source | Required? | Notes |
|---|---|---|---|
| AI System Inventory | `01-discovery/template-ai-system-inventory.md` | **Yes** | Must be complete and accepted before assessment begins. Drives Annex A control applicability. |
| Stakeholder Register | `01-discovery/template-stakeholder-register.md` | **Yes** | Required for Clause 4.2 assessment. Identifies interested parties and their requirements. |
| Draft AIMS Scope Statement | Phase 1 deliverable | **Yes** | Required for Clause 4.3 assessment. Defines what is in and out of scope. |
| Phase 1 Summary Report | Phase 1 deliverable | **Yes** | Provides context on organizational maturity, existing management systems, and key risks identified. |
| Existing management system documentation | Client Sponsor | If available | ISO 27001 ISMS, ISO 9001 QMS, SOC 2 — may satisfy multiple Clause 4–10 requirements. |
| AI-related policies (existing) | Client Sponsor | If available | Acceptable use policies, data handling policies, vendor management policies. |
| Vendor contracts for AI systems | Client IT Lead or Legal | Preferred | Required for Clause 6.1.3 (risk treatment) and A.10.2 (supplier management) assessment. |
| Organizational chart | Client Sponsor | **Yes** | Required for Clause 5.3 (roles and responsibilities) assessment. |

---

## 5. Outputs

| Output | Description | Feeds Into |
|---|---|---|
| Completed Gap Analysis Workbook | `template-gap-analysis-workbook.md` — clause-by-clause and control-by-control maturity scores, evidence notes, and gap descriptions | Phase 3 Remediation Planning |
| Gap Analysis Report | `template-gap-analysis-report.md` — executive summary, findings by clause, Annex A control heatmap, and prioritized remediation roadmap | Client Sponsor review, Phase 3 kickoff |
| Remediation Priority Matrix | Ranked list of gaps by severity and dependency, with estimated remediation effort | Phase 3 project planning |
| Updated Statement of Applicability (draft) | Preliminary SoA based on Annex A assessment — finalized in Phase 3 | Phase 3 Remediation Planning |

---

## 6. Time Estimate

| Activity | Duration | Notes |
|---|---|---|
| Pre-Assessment Preparation | Day 1–2 | Internal; minimal client time required (document request only) |
| Document Review & Evidence Collection | Day 2–3 | Client provides documents; consultant reviews and maps to clauses |
| Clause 4–5 Assessment (Context & Leadership) | Day 3–4 | 90-minute interview + review |
| Clause 6 Assessment (Planning) | Day 4–5 | 120-minute interview — most complex clause group |
| Clause 7 Assessment (Support) | Day 5–6 | 90-minute interview + document review |
| Clause 8 Assessment (Operation) | Day 6–7 | 90-minute interview + department spot-checks |
| Clause 9–10 Assessment (Performance & Improvement) | Day 7–8 | 60-minute interview |
| Annex A Control Assessment | Day 6–8 | Overlaps with Clause 6–8 interviews; uses same evidence |
| Scoring & Gap Classification | Day 8–9 | Internal analysis; no client time required |
| Findings Analysis & Prioritization | Day 9 | Internal; consultant produces remediation priority matrix |
| Report Assembly | Day 9–10 | Internal; populate templates from workbook |
| Client Presentation & Phase 3 Scoping | Day 10 | 90-minute presentation with Client Sponsor |
| **Total elapsed time** | **2–3 weeks** | Depends on client responsiveness, number of AI systems, and existing management system maturity |

---

## 7. Step-by-Step Procedure

---

### Step 1: Pre-Assessment Preparation (Day 1–2)

**Objective:** Arrive at the first assessment interview fully prepared. Review all Phase 1 deliverables, prepare the gap analysis workbook, send the document request, and schedule all assessment interviews.

#### 1.1 Review Phase 1 Deliverables

Before any client contact, spend 2–3 hours reviewing the Phase 1 outputs. Complete the following checklist:

- [ ] **AI System Inventory:** Count total AI systems. Note which are High Risk, which process Confidential data, and which are unmanaged (shadow AI). These will receive the most scrutiny in Annex A assessment.
- [ ] **Stakeholder Register:** Identify which interested parties have specific requirements (regulatory, contractual, or ethical). These requirements become evidence criteria for Clause 4.2.
- [ ] **Draft AIMS Scope Statement:** Confirm scope boundaries. Note any exclusions and their justifications. Scope determines which clauses and controls are fully applicable.
- [ ] **Phase 1 Summary Report:** Review key findings and risks. Note any existing management systems (ISO 27001, ISO 9001, SOC 2) — these will significantly affect how you assess Clauses 7–10.
- [ ] **Existing management system documentation (if provided):** Skim for document control procedures, internal audit records, management review minutes, risk registers, and corrective action logs. These may satisfy multiple ISO 42001 requirements.

**Key questions to answer before the first interview:**
1. Does this client have any existing management system infrastructure to leverage?
2. Which AI systems carry the highest risk (High Risk + Confidential data)?
3. Are there any obvious gaps visible from Phase 1 (e.g., no AI policy, no risk assessment process)?
4. Which departments are most AI-intensive and will need targeted assessment?

#### 1.2 Prepare the Gap Analysis Workbook

Open `template-gap-analysis-workbook.md` and complete the following setup steps before any interviews:

- [ ] Enter client name, engagement date, and consultant name in the header
- [ ] Pre-populate the AI System Inventory tab with all systems from Phase 1
- [ ] Pre-populate the Stakeholder Register tab with all parties from Phase 1
- [ ] For each Annex A control, pre-fill the Applicability column based on the AI System Inventory:
  - Mark A.6.2.2, A.6.2.3 as NOT APPLICABLE (AI user organization)
  - Mark A.10.4 as NOT APPLICABLE unless Phase 1 flagged the client as providing AI to customers
  - Mark all other controls as APPLICABLE (fully or partially per `00-foundation/annex-a-reference.md`)
- [ ] Leave all maturity scores blank — these are filled during assessment, not before

**Do not pre-fill maturity scores based on assumptions.** Every score must be supported by evidence gathered during the assessment.

#### 1.3 Send Document Request to Client

Send the following request to the Client Sponsor within 24 hours of Phase 2 kickoff. Tailor the list based on what was already collected in Phase 1.

**Document Request Email — Copy/Adapt:**

> Subject: ISO 42001 Gap Analysis — Phase 2 Document Request
>
> [Client Sponsor Name],
>
> We're ready to begin Phase 2 of your ISO 42001 readiness engagement. To conduct a thorough gap analysis, I need to review the following documents before our assessment interviews. Please provide whatever exists — if a document doesn't exist yet, that's important information in itself.
>
> **Governance & Policy Documents:**
> 1. Any existing AI policy, AI acceptable use policy, or AI governance policy
> 2. Data handling or data classification policy
> 3. Information security policy (if separate from any ISMS documentation)
> 4. Vendor management or third-party risk policy
>
> **Risk & Planning Documents:**
> 5. Any existing risk register or risk assessment records (AI-related or general)
> 6. Any impact assessments conducted for AI tools (privacy impact assessments, algorithmic impact assessments)
> 7. Business continuity or disaster recovery plans that reference AI systems
>
> **Operational Documents:**
> 8. Procedures or guidelines for using AI tools (how employees are expected to use them)
> 9. Vendor contracts or terms of service for the top 5 AI systems in your inventory
> 10. Any AI system documentation provided by vendors (data processing agreements, model cards, system cards)
>
> **HR & Training Documents:**
> 11. Training records related to AI tools or data handling
> 12. Job descriptions for roles with AI-related responsibilities
> 13. Any onboarding materials that mention AI tool usage
>
> **Audit & Review Records:**
> 14. Internal audit reports from the past 12 months (any management system)
> 15. Management review meeting minutes from the past 12 months
> 16. Any corrective action records or incident logs related to AI tools
>
> **Please provide whatever exists.** A document that's incomplete or informal is still useful evidence. If a category has nothing, simply reply "none exists" for that item — that's the information I need.
>
> I'll follow up to schedule our assessment interviews once I receive the initial batch. Items 1–4 and 9–10 are the most time-sensitive.

#### 1.4 Schedule Assessment Interviews

Using the organizational chart from Phase 1, schedule the following sessions. Confirm attendees with the Client Sponsor before sending calendar invites.

| Session | Attendees | Duration | Timing | Clauses Covered |
|---|---|---|---|---|
| Context & Leadership Interview | Client Sponsor + Compliance/Risk Lead | 90 minutes | Day 3 | Clauses 4, 5 |
| Planning Interview | Client Sponsor + IT Lead + Compliance/Risk Lead | 120 minutes | Day 4–5 | Clause 6 |
| Support Interview | IT Lead + HR Lead (if available) | 90 minutes | Day 5–6 | Clause 7 |
| Operations Interview | IT Lead + 1–2 Department Heads | 90 minutes | Day 6–7 | Clause 8 |
| Performance & Improvement Interview | Client Sponsor + Compliance/Risk Lead | 60 minutes | Day 7–8 | Clauses 9, 10 |

**Scheduling notes:**
- The Planning Interview (Clause 6) is the most complex and should not be shortened. If the client is not available for 120 minutes, split into two 60-minute sessions.
- If the client has an existing ISO 27001 or ISO 9001 management system, the Support and Performance interviews may be shorter — many processes will already exist.
- Department Head spot-checks for Clause 8 can be conducted as 20-minute add-ons to existing department interviews rather than standalone sessions.

#### 1.5 Decision Tree: Leveraging Existing Management Systems

Before the first interview, determine the assessment approach based on Phase 1 findings:

```
Does the client have an existing certified management system?
│
├── YES — ISO 27001 (ISMS)
│   ├── Highest overlap with ISO 42001. Shared Clause 4–10 structure.
│   ├── ASSESS THESE AS LIKELY SATISFIED (verify evidence):
│   │   - Clause 4.1 (Context) — ISMS context analysis likely transferable
│   │   - Clause 4.2 (Interested parties) — ISMS stakeholder analysis likely transferable
│   │   - Clause 7.1 (Resources) — ISMS resource management likely transferable
│   │   - Clause 7.4 (Communication) — ISMS communication processes likely transferable
│   │   - Clause 7.5 (Documented information) — ISMS document control likely transferable
│   │   - Clause 9.2 (Internal audit) — ISMS audit program likely transferable
│   │   - Clause 9.3 (Management review) — ISMS review process likely transferable
│   │   - Clause 10.1 (Nonconformity) — ISMS corrective action likely transferable
│   ├── ASSESS THESE AS LIKELY GAPS (AI-specific, not covered by ISMS):
│   │   - Clause 4.3 (AIMS scope) — ISMS scope ≠ AIMS scope; needs AI-specific definition
│   │   - Clause 5.2 (AI policy) — Information security policy ≠ AI policy
│   │   - Clause 6.1.4 (AI impact assessment) — Not part of standard ISMS
│   │   - Clause 6.1.6 (SoA for AI) — ISMS SoA covers different controls
│   │   - All Annex A controls — AI-specific; not covered by ISO 27001 Annex A
│   └── Note in workbook: "Integrated management system approach — leverage ISMS infrastructure"
│
├── YES — ISO 9001 (QMS)
│   ├── Process management, document control, internal audit transferable.
│   ├── ASSESS THESE AS LIKELY SATISFIED (verify evidence):
│   │   - Clause 7.1 (Resources) — QMS resource management likely transferable
│   │   - Clause 7.5 (Documented information) — QMS document control likely transferable
│   │   - Clause 9.2 (Internal audit) — QMS audit program likely transferable
│   │   - Clause 9.3 (Management review) — QMS review process likely transferable
│   │   - Clause 10.1 (Nonconformity) — QMS corrective action likely transferable
│   ├── ASSESS THESE AS LIKELY GAPS:
│   │   - All AI-specific clauses (4.3, 5.2, 6.1.3–6.1.6, 6.2, 8.1–8.4)
│   │   - All Annex A controls
│   └── Note in workbook: "QMS infrastructure available — process management foundation exists"
│
├── YES — SOC 2
│   ├── Not an ISO management system but indicates audit maturity.
│   ├── ASSESS THESE AS POTENTIALLY SATISFIED (verify evidence):
│   │   - Clause 7.5 (Documented information) — SOC 2 requires extensive documentation
│   │   - A.10.2 (Supplier management) — SOC 2 vendor management may be reusable
│   │   - A.6.2.9 (AI system documentation) — SOC 2 system description may partially satisfy
│   ├── ASSESS THESE AS LIKELY GAPS:
│   │   - All ISO 42001-specific requirements (SOC 2 is not a management system standard)
│   │   - All Annex A controls (SOC 2 Trust Services Criteria ≠ ISO 42001 Annex A)
│   └── Note in workbook: "SOC 2 audit maturity — documentation culture exists; management system structure needed"
│
└── NO — No existing management system
    ├── All Clause 4–10 processes will need to be created
    ├── All Annex A controls will need to be implemented from scratch
    ├── Factor additional time into Phase 3 remediation estimate
    ├── Client will need management system fundamentals education
    └── Note in workbook: "Standalone AIMS build — no existing MS infrastructure"
```

#### 1.6 Post-Preparation Actions

- [ ] Phase 1 deliverables reviewed and key findings noted
- [ ] Gap analysis workbook set up with pre-populated applicability column
- [ ] Document request sent to Client Sponsor
- [ ] All assessment interviews scheduled and confirmed
- [ ] Existing management system approach determined and noted in workbook

---

### Step 2: Document Review & Evidence Collection (Day 2–3)

**Objective:** Review all documents provided by the client before the first interview. Map each document to the clause or control it evidences. Identify gaps where no documentation exists.

**Duration:** 3–4 hours of consultant review time. No client time required.

#### 2.1 Document Review Approach

For each document received, complete the following:

1. **Read the document** — do not skim. Note the date, author, approval status, and version.
2. **Map to clauses** — identify which ISO 42001 clauses or Annex A controls the document evidences.
3. **Assess adequacy** — does the document actually satisfy the requirement, or does it only partially address it?
4. **Note gaps** — what is missing from the document that the standard requires?
5. **Record in workbook** — enter the document name, date, and adequacy assessment in the Evidence column for each relevant clause.

**Evidence adequacy criteria:**
- **Adequate:** Document exists, is current (reviewed within 12 months), is approved by appropriate authority, and addresses the requirement substantively.
- **Partial:** Document exists but is outdated, unapproved, incomplete, or only tangentially addresses the requirement.
- **Absent:** No document exists for this requirement.

#### 2.2 Document Review Checklist by Clause Group

Use this checklist to systematically map received documents to requirements. Check each item as reviewed.

**Clause 4 — Context:**
- [ ] Any document describing the organization's internal and external context (strategic plans, SWOT analyses, board presentations) → Clause 4.1
- [ ] Any stakeholder analysis, interested party register, or customer/regulatory requirement list → Clause 4.2
- [ ] AIMS scope statement (from Phase 1) → Clause 4.3
- [ ] Any document describing how the AIMS fits into the organization's overall management approach → Clause 4.4

**Clause 5 — Leadership:**
- [ ] AI policy or AI governance policy → Clause 5.2
- [ ] Any executive communications about AI (memos, all-hands presentations, board minutes) → Clause 5.1 (leadership commitment evidence)
- [ ] Organizational chart showing AI-related roles → Clause 5.3
- [ ] Job descriptions for roles with AI responsibilities → Clause 5.3

**Clause 6 — Planning:**
- [ ] Risk register or risk assessment records → Clause 6.1.2
- [ ] Risk treatment plan → Clause 6.1.3
- [ ] Impact assessment records (privacy impact assessments, algorithmic impact assessments) → Clause 6.1.4
- [ ] Impact treatment plan → Clause 6.1.5
- [ ] Statement of Applicability (draft or final) → Clause 6.1.6
- [ ] AI objectives documentation → Clause 6.2

**Clause 7 — Support:**
- [ ] Budget records or resource allocation documents for AI activities → Clause 7.1
- [ ] Training records for AI-related competencies → Clause 7.2
- [ ] Awareness training materials (AI policy training, responsible use training) → Clause 7.3
- [ ] Communication plan or records of AI-related communications → Clause 7.4
- [ ] Document control procedure → Clause 7.5
- [ ] Document register or master list of controlled documents → Clause 7.5

**Clause 8 — Operation:**
- [ ] Operational procedures for AI tool use → Clause 8.1
- [ ] Operational risk assessment records (separate from planning-level risk assessment) → Clause 8.2
- [ ] Operational risk treatment records → Clause 8.3
- [ ] Operational impact assessment records → Clause 8.4

**Clause 9 — Performance:**
- [ ] KPIs or metrics for AI system performance → Clause 9.1
- [ ] Internal audit plan and audit reports → Clause 9.2
- [ ] Management review agenda and minutes → Clause 9.3

**Clause 10 — Improvement:**
- [ ] Nonconformity and corrective action records → Clause 10.1
- [ ] Continual improvement records or improvement log → Clause 10.2

**Annex A — Controls:**
- [ ] Vendor contracts for AI systems (data processing agreements, terms of service) → A.10.2, A.6.2.11
- [ ] Vendor assessment records or due diligence questionnaires → A.10.2
- [ ] AI system documentation (model cards, system cards, vendor-provided documentation) → A.6.2.9
- [ ] Acceptable use policy for AI tools → A.6.2.10
- [ ] Data quality procedures → A.7.3
- [ ] Human oversight procedures or escalation procedures → A.9.5
- [ ] Disclosure notices for AI interactions (customer-facing) → A.8.2

#### 2.3 Evidence Gap Log

For each clause or control where no document was received, log the gap in the workbook Evidence column as: **"No documentation provided — to be confirmed in interview."**

Do not assume a gap is confirmed until the interview. The client may have relevant practices that are not yet documented, or may have forgotten to include a document in their initial submission.

---

### Step 3: Clause-by-Clause Assessment — Clauses 4–10 (Day 3–8)

**Objective:** Conduct structured interviews for each clause group, gather evidence, and assign maturity scores. This is the core of the gap analysis.

**General interview guidance:**
- Open each session by explaining the purpose: "We're assessing your current practices against ISO 42001 requirements. I'll ask about what you do today — not what you plan to do. There are no wrong answers."
- Take notes in real time. Do not rely on memory.
- When a client describes a practice, ask: "Is that documented anywhere?" and "Can you show me an example?"
- If a client says "we do that informally," score it at Level 1 (Initial) or Level 2 (Managed) — not Level 3 (Defined), which requires documented processes.
- After each session, update the workbook within 24 hours while the interview is fresh.

---

#### 3.1 Clause 4 — Context of the Organization

**Interview session:** Combined with Clause 5 (Context & Leadership Interview)
**Duration:** First 30 minutes of the 90-minute session
**Attendees:** Client Sponsor + Compliance/Risk Lead

**Interview Script — Clause 4:**

*Section A: Clause 4.1 — Understanding the Organization and Its Context (10 minutes)*

1. "Walk me through the key external factors that affect how your organization uses AI — things like regulatory requirements, customer expectations, competitive pressures, or industry trends."
2. "What internal factors shape your approach to AI? For example, your culture around technology adoption, your risk appetite, your existing governance structures."
3. "Has your organization formally documented these internal and external factors anywhere — in a strategic plan, a risk register, or a board presentation?"
4. "Are there any regulatory requirements that specifically govern how you use AI? For example, sector-specific rules in healthcare, finance, or employment?"

*Section B: Clause 4.2 — Interested Parties (10 minutes)*

5. "Looking at the Stakeholder Register we built in Phase 1 — are there any groups we missed? Any parties who have requirements or expectations about how you use AI?"
6. "For your most important interested parties — customers, regulators, employees — what specific requirements do they have about your AI use? Are those requirements documented anywhere?"
7. "Have any interested parties communicated concerns or requirements about AI to you in the past 12 months? How did you respond?"

*Section C: Clause 4.3 — AIMS Scope (5 minutes)*

8. "Looking at the Draft AIMS Scope Statement from Phase 1 — has anything changed since we defined it? Any new AI systems, new business units, or new locations that should be included?"
9. "Is the scope statement approved by leadership? Has it been communicated to relevant staff?"

*Section D: Clause 4.4 — AIMS Establishment (5 minutes)*

10. "Do you have a documented plan or framework for how your AI management system will be structured — what processes it will include, how it will be maintained?"

**Evidence to look for — Clause 4:**
- Written context analysis (any format — strategic plan, SWOT, board presentation)
- Stakeholder register or interested party list with documented requirements
- Signed AIMS scope statement
- Any document describing the AIMS structure or framework

**Common findings for AI-user SMBs — Clause 4:**
- *Maturity 0–1:* No formal context analysis exists. Stakeholders identified informally. Scope not documented.
- *Maturity 2:* Context discussed at leadership level but not formally documented. Stakeholder list exists but requirements not mapped. Scope statement drafted but not approved.
- *Maturity 3 (certification threshold):* Context analysis documented and reviewed annually. Stakeholder register complete with requirements mapped to AIMS activities. Scope statement approved and communicated.

**Post-interview actions — Clause 4:**
- [ ] Score each sub-clause (4.1, 4.2, 4.3, 4.4) using the maturity scale in Step 5
- [ ] Record evidence references in workbook
- [ ] Note any gaps for the Gap Analysis Report

---

#### 3.2 Clause 5 — Leadership

**Interview session:** Combined with Clause 4 (Context & Leadership Interview)
**Duration:** Second 60 minutes of the 90-minute session
**Attendees:** Client Sponsor + Compliance/Risk Lead

**Interview Script — Clause 5:**

*Section A: Clause 5.1 — Leadership and Commitment (20 minutes)*

1. "How does senior leadership demonstrate commitment to responsible AI use? Is there a visible champion at the executive level?"
2. "Has leadership formally approved an AI policy or AI governance framework? If yes, can you show me the approval record?"
3. "Does leadership allocate specific budget or resources for AI governance activities — training, risk assessment, compliance monitoring?"
4. "How does leadership communicate the importance of responsible AI to the rest of the organization? Town halls, written communications, policy rollouts?"
5. "Has leadership ever intervened to stop or modify an AI tool adoption based on risk or ethical concerns? Can you describe an example?"
6. "Is AI governance on the agenda for leadership meetings? How often is it discussed at the executive or board level?"

*Section B: Clause 5.2 — AI Policy (20 minutes)*

7. "Do you have a documented AI policy? If yes, please share it. If no, do you have any policy that addresses AI use — even partially, like an acceptable use policy or data handling policy?"
8. "If an AI policy exists: When was it last reviewed and updated? Who approved it? How was it communicated to employees?"
9. "Does your AI policy (or equivalent) address: the organization's commitment to responsible AI, specific principles (fairness, transparency, accountability, human oversight), and a framework for AI objectives?"
10. "Are employees required to acknowledge the AI policy? Is there a record of that acknowledgment?"

*Section C: Clause 5.3 — Roles, Responsibilities, and Authorities (20 minutes)*

11. "Who is responsible for AI governance in your organization? Is there a named role — an AI lead, a data governance officer, a compliance manager?"
12. "For each AI system in your inventory, is there a named owner — someone accountable for how that system is used and what risks it creates?"
13. "Who has the authority to approve the adoption of a new AI tool? Is that process documented?"
14. "Who is responsible for conducting risk assessments for AI systems? For impact assessments?"
15. "If an employee has a concern about an AI tool — a biased output, a data exposure, an ethical issue — who do they report it to? Is that escalation path documented?"

**Evidence to look for — Clause 5:**
- AI policy document (approved, dated, version-controlled)
- Leadership communications about AI (emails, presentations, meeting minutes)
- Budget records showing AI governance investment
- Organizational chart with AI-related roles highlighted
- Job descriptions for AI-related roles
- Policy acknowledgment records (training completion, signed acknowledgments)
- AI tool approval process documentation

**Common findings for AI-user SMBs — Clause 5:**
- *Maturity 0–1:* No AI policy exists. No named AI governance role. Leadership has not formally addressed AI governance.
- *Maturity 2:* AI policy drafted but not approved or communicated. AI governance responsibility assigned informally to IT or compliance. Leadership aware of AI risks but not formally committed.
- *Maturity 3 (certification threshold):* AI policy approved by leadership, communicated to all staff, and reviewed annually. Named AI governance role with documented responsibilities. Leadership commitment evidenced by budget allocation and regular agenda items.

> **Integration note (ISO 27001 clients):** If the client has an ISO 27001 ISMS, their information security policy structure, document approval process, and role assignment framework can be extended to cover AI. The AI policy can be a standalone document or an addendum to the information security policy. Either approach is acceptable for ISO 42001 certification.

**Post-interview actions — Clause 5:**
- [ ] Score each sub-clause (5.1, 5.2, 5.3) using the maturity scale in Step 5
- [ ] Record evidence references in workbook
- [ ] Flag any Critical gaps (no AI policy, no leadership commitment) — see Escalation Trigger E-4

---

#### 3.3 Clause 6 — Planning

**Interview session:** Planning Interview (standalone)
**Duration:** 120 minutes
**Attendees:** Client Sponsor + IT Lead + Compliance/Risk Lead

**This is the most critical clause group for ISO 42001 certification.** Clause 6 contains the risk assessment, impact assessment, risk treatment, and Statement of Applicability requirements that are unique to ISO 42001 and cannot be satisfied by existing management system documentation without significant AI-specific additions. Allocate the full 120 minutes and do not rush.

**Interview Script — Clause 6:**

*Section A: Clause 6.1.1 — Actions to Address Risks and Opportunities (10 minutes)*

1. "Does your organization have a formal process for identifying risks and opportunities related to your AI systems? Is it documented?"
2. "How do you determine which risks need to be addressed and which can be accepted? Is there a risk appetite or risk tolerance statement?"
3. "How often do you review your AI-related risks? Is there a trigger for ad-hoc reviews — for example, when a new AI system is adopted or when an incident occurs?"

*Section B: Clause 6.1.2 — AI System Risk Assessment (25 minutes)*

4. "Walk me through how you would assess the risk of a new AI tool before adopting it. What factors do you consider?"
5. "Do you have a documented risk assessment methodology? Does it define risk criteria — likelihood, impact, risk levels?"
6. "Have you conducted a formal risk assessment for any of the AI systems currently in your inventory? If yes, can you show me the records?"
7. "What types of risks do you consider for AI systems? Technical risks (system failure, inaccurate outputs), organizational risks (over-reliance, skill gaps), ethical risks (bias, discrimination), and legal/regulatory risks?"
8. "Who conducts the risk assessment? Is there a defined process for who participates and what their roles are?"
9. "How do you document risk assessment results? Is there a standard format or template?"

*Section C: Clause 6.1.3 — AI System Risk Treatment (20 minutes)*

10. "For risks that are identified, how do you decide what to do about them? Do you have a defined set of treatment options — avoid, accept, transfer, mitigate?"
11. "Do you have a risk treatment plan that documents the controls selected for each risk, who is responsible, and the target completion date?"
12. "How do you verify that risk treatment controls are actually implemented? Is there a follow-up process?"
13. "For third-party AI systems, how do you address risks that you can't control directly — for example, risks related to the vendor's model quality or data handling practices?"
14. "Do your vendor contracts for AI systems include any risk-related provisions — data processing agreements, liability clauses, audit rights?"

*Section D: Clause 6.1.4 — AI System Impact Assessment (25 minutes)*

*Note: This is often the biggest gap for AI-user SMBs. Many clients have never conducted a formal impact assessment. Spend extra time here.*

15. "Have you ever formally assessed the potential impact of your AI systems on individuals — employees, customers, or other people affected by AI-driven decisions?"
16. "For AI systems that inform decisions about people — hiring, customer service, pricing, performance evaluation — have you considered what could go wrong? What if the AI output is biased or incorrect?"
17. "Do you have a process for conducting impact assessments before deploying a new AI system? What does that process look like?"
18. "Have you conducted any privacy impact assessments or data protection impact assessments for AI systems that process personal data?"
19. "How do you document impact assessment results? Is there a standard format?"
20. "Who is responsible for conducting impact assessments? Do they have the skills to identify potential harms — including subtle harms like algorithmic bias?"

*Section E: Clause 6.1.5 — AI System Impact Treatment (10 minutes)*

21. "When an impact assessment identifies a potential harm, what do you do about it? Is there a defined process for selecting and implementing mitigations?"
22. "Do you have documented impact treatment plans for any of your AI systems?"
23. "How do you verify that impact mitigations are effective? Is there a monitoring or review process?"

*Section F: Clause 6.1.6 — Statement of Applicability (10 minutes)*

24. "Are you familiar with the Statement of Applicability requirement in ISO 42001? Have you started developing one?"
25. "Have you reviewed the 39 Annex A controls and determined which ones apply to your organization?"
26. "For controls you've determined are not applicable — particularly the development-focused controls — have you documented the justification for exclusion?"

*Section G: Clause 6.2 — AI Objectives (10 minutes)*

27. "Has your organization defined specific objectives for responsible AI use? For example, targets for AI system accuracy, human oversight coverage, or training completion rates?"
28. "Are these objectives documented, measurable, and communicated to relevant staff?"
29. "How do you track progress against AI objectives? Is there a monitoring process?"
30. "Are AI objectives reviewed and updated as part of management review?"

**Evidence to look for — Clause 6:**
- Risk assessment methodology document (defines criteria, process, roles)
- Completed risk assessments for AI systems (any format)
- Risk register with AI-specific entries
- Risk treatment plan with assigned owners and target dates
- Vendor contracts with data processing agreements and risk provisions
- Impact assessment records (privacy impact assessments, algorithmic impact assessments, or equivalent)
- Impact treatment plans
- Draft or final Statement of Applicability
- AI objectives documentation (measurable targets)

**Common findings for AI-user SMBs — Clause 6:**
- *Maturity 0:* No risk assessment process. No impact assessments. No SoA. No AI objectives. (Most common for first-time AIMS clients.)
- *Maturity 1:* Risks discussed informally. No documented methodology. No impact assessments. SoA not started.
- *Maturity 2:* Risk register exists but not AI-specific. Some vendor due diligence conducted. No formal impact assessments. SoA in draft.
- *Maturity 3 (certification threshold):* Documented AI risk assessment methodology. Risk assessments completed for all in-scope AI systems. Impact assessments completed for high-risk systems. Risk treatment plan with assigned owners. SoA approved. AI objectives defined and measurable.

**Decision Tree — Clause 6 Gap Severity:**

```
Does a documented AI risk assessment methodology exist?
│
├── NO → Critical Gap (Clause 6.1.2)
│   - No certification possible without this
│   - Remediation: Create AI risk assessment procedure (Phase 3, Week 1)
│
└── YES
    ├── Have risk assessments been conducted for all in-scope AI systems?
    │   ├── NO → Major Gap (Clause 6.1.2)
    │   │   - Methodology exists but not applied
    │   │   - Remediation: Conduct assessments using existing methodology
    │   └── YES → Proceed to impact assessment check
    │
    └── Have impact assessments been conducted for high-risk AI systems?
        ├── NO → Major Gap (Clause 6.1.4)
        │   - Impact assessment is a distinct requirement from risk assessment
        │   - Remediation: Conduct impact assessments (Phase 3, Week 2–3)
        └── YES → Check documentation quality
            ├── Documented and approved? → Score 3+
            └── Informal only? → Score 2 (Major Gap — needs formalization)
```

**Post-interview actions — Clause 6:**
- [ ] Score each sub-clause (6.1.1 through 6.1.6, 6.2) using the maturity scale in Step 5
- [ ] Record evidence references in workbook
- [ ] Flag any Critical gaps (no risk assessment process, no impact assessment process)
- [ ] Note which AI systems still need risk assessments and impact assessments

---

#### 3.4 Clause 7 — Support

**Interview session:** Support Interview
**Duration:** 90 minutes
**Attendees:** IT Lead + HR Lead (if available)

**Interview Script — Clause 7:**

*Section A: Clause 7.1 — Resources (15 minutes)*

1. "What resources does your organization allocate specifically for AI governance activities? This includes budget, staff time, tools, and infrastructure."
2. "Is there a dedicated budget line for AI governance, compliance, or risk management? Or is it absorbed into general IT or operations budgets?"
3. "Do you have sufficient staff with the skills to manage AI governance activities — risk assessment, vendor management, policy maintenance?"
4. "Are there any resource constraints that currently limit your ability to govern AI responsibly?"

*Section B: Clause 7.2 — Competence (20 minutes)*

5. "What competencies do you require for roles involved in AI governance? Are these documented in job descriptions or competency frameworks?"
6. "How do you assess whether staff have the required competencies for AI-related roles? Is there a skills assessment or certification requirement?"
7. "What training have staff received related to AI systems — responsible use, data handling, risk identification?"
8. "Are training records maintained? Can you show me records of AI-related training completed in the past 12 months?"
9. "How do you identify and address competency gaps? Is there a training needs analysis process?"

*Section C: Clause 7.3 — Awareness (15 minutes)*

10. "Are all employees aware of the organization's AI policy and their responsibilities under it?"
11. "How is AI awareness communicated to staff — training sessions, onboarding materials, policy acknowledgments, team meetings?"
12. "Do employees understand the risks of using AI tools irresponsibly — for example, entering sensitive data into unauthorized AI tools?"
13. "Have there been any AI-related incidents that were caused by lack of awareness? How were they addressed?"

*Section D: Clause 7.4 — Communication (15 minutes)*

14. "How does the organization communicate about AI governance internally — to employees, management, and the board?"
15. "How does the organization communicate about AI use externally — to customers, partners, or regulators?"
16. "Is there a defined communication plan for AI governance? Does it specify what is communicated, to whom, when, and by whom?"
17. "When a significant change occurs — a new AI system is adopted, a vendor changes their terms, an incident occurs — how is that communicated to relevant parties?"

*Section E: Clause 7.5 — Documented Information (25 minutes)*

18. "How do you manage documents related to AI governance? Is there a document control procedure?"
19. "Are AI governance documents version-controlled, approved before use, and reviewed periodically?"
20. "Where are AI governance documents stored? Are they accessible to the people who need them?"
21. "How do you manage records — evidence that activities were performed? For example, training records, risk assessment records, audit records?"
22. "Is there a master list or register of controlled documents? How do you ensure outdated versions are not in use?"

**Evidence to look for — Clause 7:**
- Budget records or resource allocation documents
- Job descriptions with AI-related competency requirements
- Training records (completion dates, topics covered)
- Awareness training materials
- Policy acknowledgment records
- Communication plan or records of AI-related communications
- Document control procedure
- Document register or master list
- Records management procedure

**Common findings for AI-user SMBs — Clause 7:**
- *Maturity 0–1:* No formal resource allocation. No competency requirements defined. No awareness training. No document control procedure.
- *Maturity 2:* Some training conducted but not recorded. Documents exist but not version-controlled. Communication happens ad hoc.
- *Maturity 3 (certification threshold):* Competency requirements documented. Training records maintained. Awareness training completed by all staff. Document control procedure in place with version control and approval records.

> **Integration note (ISO 27001/9001 clients):** Clause 7 is the most transferable from existing management systems. If the client has ISO 27001 or ISO 9001, their document control procedure, training records system, and communication processes almost certainly satisfy Clause 7 requirements. The primary gap will be AI-specific content (AI policy, AI training materials) rather than the management system infrastructure.

**Post-interview actions — Clause 7:**
- [ ] Score each sub-clause (7.1 through 7.5) using the maturity scale in Step 5
- [ ] Record evidence references in workbook
- [ ] Note any training records that need to be collected as evidence

---

#### 3.5 Clause 8 — Operation

**Interview session:** Operations Interview
**Duration:** 90 minutes
**Attendees:** IT Lead + 1–2 Department Heads

**Interview Script — Clause 8:**

*Section A: Clause 8.1 — Operational Planning and Control (20 minutes)*

1. "How do you plan and control the operational use of AI systems? Is there a defined process for how AI tools are deployed, monitored, and managed day-to-day?"
2. "When a new AI system is adopted, what steps do you go through before it goes live? Is there a deployment checklist or approval process?"
3. "How do you ensure that AI systems are used within their intended parameters — that employees aren't using AI tools for purposes they weren't designed for?"
4. "Are there documented procedures for how employees should use specific AI tools? For example, guidelines for what data can be entered, how outputs should be reviewed, or when to escalate concerns?"
5. "How do you handle changes to AI systems — vendor updates, new features, configuration changes? Is there a change management process?"

*Section B: Clause 8.2 — AI System Operational Risk Assessment (20 minutes)*

6. "Beyond the planning-level risk assessment we discussed earlier, do you conduct operational risk assessments — assessments of how AI systems are actually performing in practice?"
7. "How do you monitor AI system outputs for quality, accuracy, and consistency? Is there a defined monitoring process?"
8. "When an AI system produces an unexpected or concerning output, what happens? Is there a defined escalation process?"
9. "Do you track incidents related to AI systems — incorrect outputs, data exposures, misuse by employees? Is there an incident log?"

*Section C: Clause 8.3 — AI System Operational Risk Treatment (15 minutes)*

10. "When operational monitoring identifies a risk or issue with an AI system, how do you respond? Is there a defined treatment process?"
11. "Have you ever suspended or restricted use of an AI system because of a risk identified during operation? What was the process?"
12. "How do you verify that operational risk treatments are effective? Is there a follow-up review?"

*Section D: Clause 8.4 — AI System Operational Impact Assessment (20 minutes)*

13. "Do you conduct ongoing assessments of how your AI systems are actually impacting people — employees, customers, or others — during operation?"
14. "For AI systems that inform decisions about people, how do you monitor for unintended consequences — bias, discrimination, or unfair treatment?"
15. "If an AI system's impact changes over time — for example, if a vendor updates their model and outputs change — how do you detect and respond to that?"
16. "Do you have a process for reviewing AI system impacts periodically, not just at initial deployment?"

**Evidence to look for — Clause 8:**
- AI deployment procedures or checklists
- Acceptable use guidelines for specific AI tools
- Change management records for AI systems
- AI system monitoring records (performance logs, output quality reviews)
- Incident log or incident records related to AI systems
- Operational risk assessment records
- Operational impact assessment records

**Common findings for AI-user SMBs — Clause 8:**
- *Maturity 0–1:* No operational procedures for AI use. No monitoring. No incident log. AI systems deployed without formal process.
- *Maturity 2:* Some informal monitoring. Incidents handled ad hoc. Deployment process exists but not documented.
- *Maturity 3 (certification threshold):* Documented deployment procedures. Monitoring process defined and executed. Incident log maintained. Operational risk and impact assessments conducted periodically.

**Post-interview actions — Clause 8:**
- [ ] Score each sub-clause (8.1 through 8.4) using the maturity scale in Step 5
- [ ] Record evidence references in workbook
- [ ] Note any AI systems with no operational monitoring — flag as Major Gap

---

#### 3.6 Clause 9 — Performance Evaluation

**Interview session:** Performance & Improvement Interview
**Duration:** First 35 minutes of the 60-minute session
**Attendees:** Client Sponsor + Compliance/Risk Lead

**Interview Script — Clause 9:**

*Section A: Clause 9.1 — Monitoring, Measurement, Analysis, and Evaluation (15 minutes)*

1. "How do you measure the performance of your AI management system? What metrics or KPIs do you track?"
2. "How do you know if your AI governance activities are effective? Is there a defined evaluation process?"
3. "How often do you review AI system performance data? Who is responsible for this review?"
4. "Do you track metrics related to responsible AI use — for example, training completion rates, incident counts, risk assessment completion rates, or vendor assessment scores?"

*Section B: Clause 9.2 — Internal Audit (10 minutes)*

5. "Do you conduct internal audits of your AI management system? If yes, how often and who conducts them?"
6. "Is there a documented internal audit program — a schedule, scope, and methodology for audits?"
7. "Are audit findings documented and tracked to closure? Can you show me recent audit records?"
8. "Are internal auditors independent of the activities they audit?"

*Section C: Clause 9.3 — Management Review (10 minutes)*

9. "Does senior management formally review the AI management system on a periodic basis?"
10. "What inputs does management review consider — audit results, performance metrics, nonconformities, changes in context?"
11. "Are management review outputs documented — decisions made, actions assigned, resources allocated?"
12. "Can you show me minutes or records from a recent management review that addressed AI governance?"

**Evidence to look for — Clause 9:**
- KPI or metrics dashboard for AI governance
- Internal audit program (schedule, scope, methodology)
- Internal audit reports
- Management review agenda and minutes
- Action items from management review with assigned owners

**Common findings for AI-user SMBs — Clause 9:**
- *Maturity 0–1:* No internal audit program. No management review of AI governance. No performance metrics.
- *Maturity 2:* Management review occurs but AI governance not on the agenda. Some metrics tracked informally.
- *Maturity 3 (certification threshold):* Internal audit program documented and executed. Management review includes AI governance agenda items with documented outputs. Performance metrics defined and tracked.

> **Integration note (ISO 27001/9001 clients):** If the client has an existing internal audit program and management review process, these almost certainly satisfy Clause 9 requirements. The primary gap will be ensuring AI governance is included in the audit scope and management review agenda.

**Post-interview actions — Clause 9:**
- [ ] Score each sub-clause (9.1, 9.2, 9.3) using the maturity scale in Step 5
- [ ] Record evidence references in workbook

---

#### 3.7 Clause 10 — Improvement

**Interview session:** Performance & Improvement Interview
**Duration:** Second 25 minutes of the 60-minute session
**Attendees:** Client Sponsor + Compliance/Risk Lead

**Interview Script — Clause 10:**

*Section A: Clause 10.1 — Nonconformity and Corrective Action (15 minutes)*

1. "When something goes wrong with an AI system — an incorrect output, a policy violation, a data exposure — what is the process for responding?"
2. "Do you have a formal nonconformity and corrective action process? Is it documented?"
3. "When a nonconformity is identified, do you investigate the root cause — not just fix the immediate problem, but understand why it happened?"
4. "Are corrective actions tracked to closure? Is there a record of what was done and whether it was effective?"
5. "Have there been any AI-related nonconformities or incidents in the past 12 months? How were they handled?"

*Section B: Clause 10.2 — Continual Improvement (10 minutes)*

6. "How does your organization systematically improve its AI governance over time? Is there a defined improvement process?"
7. "What inputs drive improvement decisions — audit findings, management review outputs, incident analysis, stakeholder feedback?"
8. "Can you give me an example of an improvement that was made to your AI governance practices in the past 12 months?"
9. "Is there a documented improvement log or improvement plan?"

**Evidence to look for — Clause 10:**
- Nonconformity and corrective action records
- Root cause analysis records
- Corrective action tracking log
- Improvement log or improvement plan
- Evidence of improvements implemented (before/after comparisons)

**Common findings for AI-user SMBs — Clause 10:**
- *Maturity 0–1:* No formal corrective action process. Incidents handled ad hoc. No improvement tracking.
- *Maturity 2:* Incidents documented but root cause analysis not conducted. Improvements made but not tracked.
- *Maturity 3 (certification threshold):* Documented corrective action process with root cause analysis. Corrective actions tracked to closure. Improvement log maintained and reviewed at management review.

> **Integration note (ISO 27001/9001 clients):** Corrective action and continual improvement processes from existing management systems are directly transferable. Verify that AI-related nonconformities are captured in the existing process.

**Post-interview actions — Clause 10:**
- [ ] Score each sub-clause (10.1, 10.2) using the maturity scale in Step 5
- [ ] Record evidence references in workbook
- [ ] Complete all clause scoring before moving to Step 4

---

### Step 4: Annex A Control Assessment (Day 6–8, Overlapping Step 3)

**Objective:** Assess the implementation status of all 39 Annex A controls. Use evidence gathered during clause interviews and document review. Conduct targeted follow-up questions where evidence is insufficient.

**Approach:** Annex A assessment runs in parallel with Clause 6–8 interviews. Most Annex A evidence is gathered during the Planning and Operations interviews. Do not schedule separate Annex A interviews — integrate Annex A questions into existing sessions.

#### 4.1 Assessment Approach by Domain

For each Annex A domain, the following guidance describes what to assess for AI-user organizations and what evidence to look for.

---

**A.2 — Policies for AI (A.2.2, A.2.3)**

*What to assess:* Does a formal AI policy exist? Does it address responsible AI principles (fairness, transparency, accountability, human oversight, privacy, safety)?

*Evidence to look for:*
- AI policy document (approved, dated, version-controlled)
- Policy acknowledgment records
- Evidence that the policy addresses all responsible AI topics (A.2.3)

*Assessment questions (add to Clause 5 interview):*
- "Does your AI policy specifically address fairness and non-discrimination in AI outputs?"
- "Does it address transparency — how you communicate about AI use to affected parties?"
- "Does it address human oversight — when and how humans review AI outputs?"

*Common gap:* Policy exists but does not address all responsible AI topics in A.2.3. Score A.2.2 at 3 but A.2.3 at 1–2.

---

**A.3 — Internal Organization (A.3.2, A.3.3, A.3.4)**

*What to assess:* Are AI roles and responsibilities formally defined? Is there a mechanism for reporting AI concerns? Are AI implications assessed when organizational changes occur?

*Evidence to look for:*
- Job descriptions with AI responsibilities
- Organizational chart with AI roles highlighted
- Reporting mechanism for AI concerns (hotline, email, designated contact)
- Change management records that include AI impact assessment

*Assessment questions (add to Clause 5 interview):*
- "Is there a named AI system owner for each AI tool in your inventory?"
- "How can employees report concerns about AI tools — bias, accuracy, ethical issues?"
- "When your organization undergoes changes — new hires, restructuring, vendor changes — is the AI impact formally assessed?"

*Common gap:* A.3.3 (reporting mechanism) is frequently absent. Employees have no formal channel to report AI concerns.

---

**A.4 — Resources for AI Systems (A.4.2, A.4.3, A.4.4, A.4.5, A.4.6)**

*What to assess:* Are resources identified and allocated? Are competencies defined and assessed? Is awareness training conducted? Are stakeholders consulted on significant AI decisions? Is information about AI systems communicated to interested parties?

*Evidence to look for:*
- Resource allocation records
- Competency requirements documentation
- Training records
- Awareness training materials
- Consultation records (e.g., employee input on AI tool adoption)
- Communication records (e.g., customer notices about AI use)

*Assessment questions (add to Clause 7 interview):*
- "When you adopt a new AI tool, do you consult affected employees before rollout?"
- "Do you communicate to customers or partners when AI is used in your interactions with them?"

*Common gap:* A.4.5 (consultation) and A.4.6 (communication) are frequently absent. Organizations adopt AI tools without consulting affected employees or communicating to customers.

---

**A.5 — Assessing Impacts of AI Systems (A.5.2, A.5.3, A.5.4)**

*What to assess:* Have AI system risk assessments been conducted? Have impact assessments been conducted for AI systems affecting individuals? Are impact assessment results documented?

*Evidence to look for:*
- Risk assessment records for each in-scope AI system
- Impact assessment records (especially for HR, customer service, and decision-support AI)
- Impact assessment documentation (A.5.4)

*Assessment questions (add to Clause 6 interview):*
- "For your AI systems that affect hiring, customer treatment, or employee evaluation — have you formally assessed the potential for biased or discriminatory outcomes?"
- "Are impact assessment results documented in a standard format?"

*Common gap:* A.5.3 (impact assessment) is the most common Critical gap for AI-user SMBs. Most have never conducted a formal impact assessment.

---

**A.6 — AI System Life Cycle (A.6.2.2 through A.6.2.11)**

*Not Applicable controls — document and move on:*
- **A.6.2.2 (Design and Development):** NOT APPLICABLE. Organization does not design or develop AI systems. Record justification: "Organization is an AI user, not an AI developer. Design and development responsibilities rest with third-party AI providers."
- **A.6.2.3 (Training and Testing):** NOT APPLICABLE. Organization does not train or test AI models. Record justification: "Organization does not train AI models. Model training and testing is conducted by third-party AI providers."

*Partially applicable controls — assess reduced scope:*
- **A.6.2.4 (Verification and Validation):** Assess whether the organization validates that third-party AI tools meet their requirements before adoption. Evidence: vendor evaluation records, pilot testing records.
- **A.6.2.7 (Retirement):** Assess whether the organization has a process for decommissioning AI tools — data migration, access removal, contract termination. Evidence: offboarding procedures, contract termination records.

*Fully applicable controls — assess in full:*
- **A.6.2.5 (Deployment):** Is there a controlled deployment process for new AI tools? Evidence: deployment checklists, rollout plans.
- **A.6.2.6 (Operation and Monitoring):** Is there ongoing monitoring of AI system performance? Evidence: monitoring records, performance reviews.
- **A.6.2.8 (Integration):** Are AI systems integrated responsibly into business processes? Evidence: integration documentation, testing records.
- **A.6.2.9 (Documentation):** Is each AI system documented — purpose, capabilities, limitations, data flows? Evidence: AI system inventory, vendor documentation.
- **A.6.2.10 (Defined Use and Misuse):** Are acceptable and prohibited uses of AI tools defined and communicated? Evidence: acceptable use policy, training materials.
- **A.6.2.11 (Third-Party Components):** Are third-party AI providers managed — selection criteria, ongoing assessment, performance monitoring? Evidence: vendor assessment records, contracts, periodic reviews.

*Assessment questions (add to Clause 8 interview):*
- "Before adopting a new AI tool, do you evaluate whether it meets your requirements? What does that evaluation look like?"
- "Do you have documented procedures for what employees can and cannot do with each AI tool?"
- "How do you monitor whether AI tools are performing as expected over time?"
- "When you stop using an AI tool, what is the process for removing access and handling any data?"

*Common gap:* A.6.2.11 (third-party component management) is frequently at Maturity 1–2. Vendors are selected informally, contracts lack AI-specific provisions, and ongoing monitoring is absent.

---

**A.7 — Data for AI Systems (A.7.2 through A.7.6)**

*Partially applicable controls — assess reduced scope:*
- **A.7.2 (Data for Development):** Assess only if the client provides data for vendor fine-tuning or customization. If not, record: "PARTIALLY APPLICABLE — not currently applicable as organization does not provide data for AI model development or customization."
- **A.7.4 (Data Preparation):** Assess whether the organization prepares data before entering it into AI tools (e.g., anonymizing customer data before using it in AI prompts). Evidence: data preparation procedures, prompt engineering guidelines.
- **A.7.5 (Data Acquisition):** Assess whether the organization collects data responsibly for use as AI inputs. Evidence: data collection procedures, consent records.
- **A.7.6 (Data Provenance):** Assess whether the organization tracks the origin and handling of data used as AI inputs. Evidence: data lineage records, data flow documentation.

*Fully applicable controls — assess in full:*
- **A.7.3 (Data Quality):** Are there controls to ensure data quality before it enters AI systems? Evidence: data quality procedures, data validation records.

*Assessment questions (add to Clause 8 interview):*
- "Before entering data into AI tools, do you check it for quality — accuracy, completeness, relevance?"
- "Do you have guidelines for what data can be entered into AI tools and in what format?"
- "Do you track where the data you use as AI inputs comes from?"

*Common gap:* A.7.3 (data quality) is frequently absent. Organizations enter data into AI tools without any quality checks, leading to unreliable outputs.

---

**A.8 — Information for Interested Parties (A.8.2 through A.8.5)**

*What to assess:* Do affected parties know when they're interacting with AI? Can they understand AI-driven decisions? Can they access records of AI interactions? Do staff have enough information to act appropriately on AI outputs?

*Evidence to look for:*
- Customer-facing AI disclosure notices (website, chatbot, email)
- Employee notices about AI use in HR processes
- Explanation mechanisms for AI-driven decisions (e.g., how lead scores are calculated)
- AI interaction logs accessible to affected parties
- Guidelines for staff on how to interpret and act on AI outputs

*Assessment questions (add to Clause 8 interview):*
- "When customers interact with an AI chatbot or receive AI-generated communications, are they informed that AI is involved?"
- "If an AI system influences a decision about a customer or employee, can that person understand why the decision was made?"
- "Do employees who act on AI recommendations have enough information to exercise their own judgment — confidence scores, caveats, limitations?"

*Common gap:* A.8.2 (disclosure of AI interaction) is frequently absent for customer-facing AI. A.8.5 (enabling human action) is frequently absent — staff act on AI outputs without understanding their limitations.

---

**A.9 — Use of AI Systems (A.9.2 through A.9.5)**

*What to assess:* Are there defined objectives for responsible AI use? Are AI systems used within their intended parameters? Are there operational processes for responsible use? Is there appropriate human oversight?

*Evidence to look for:*
- Documented AI objectives (measurable targets)
- Intended use documentation for each AI system
- Operational procedures for responsible AI use
- Human oversight procedures (when and how humans review AI outputs)
- Override capability documentation (can humans override AI decisions?)

*Assessment questions (add to Clause 8 interview):*
- "For each AI system, is there documentation of what it's intended to be used for — and what it's not intended for?"
- "Are there processes that require human review of AI outputs before action is taken? For which systems?"
- "Can employees override AI recommendations? Is there a process for doing so?"
- "What happens when an AI system produces an output that seems wrong or unexpected?"

*Common gap:* A.9.5 (human oversight) is frequently at Maturity 1–2. Human review happens informally but is not documented as a required process step.

---

**A.10 — Third-Party and Customer Relationships (A.10.2, A.10.3, A.10.4)**

*Not Applicable controls — document and move on:*
- **A.10.4 (Provision of AI to Third Parties):** NOT APPLICABLE for standard AI-user clients. Record justification: "Organization does not provide AI systems or AI-powered services to third parties." *Exception: If Phase 1 flagged the client as embedding AI outputs in services delivered to customers, reclassify to FULLY APPLICABLE — see Escalation Trigger E-6.*

*Partially applicable controls — assess reduced scope:*
- **A.10.3 (Shared ML Models):** Assess only if the client uses open-source or shared pre-trained models (e.g., running a local LLM). If exclusively using proprietary vendor APIs, record: "PARTIALLY APPLICABLE — not currently applicable as organization uses only proprietary vendor AI APIs, not shared or open-source models."

*Fully applicable controls — assess in full:*
- **A.10.2 (Suppliers):** Are AI vendors managed through formal supplier management — selection criteria, contractual requirements, ongoing assessment, performance monitoring? Evidence: vendor selection records, contracts with AI-specific provisions, vendor assessment records, periodic vendor reviews.

*Assessment questions (add to Clause 6 interview):*
- "How do you select AI vendors? Is there a formal evaluation process with defined criteria?"
- "Do your contracts with AI vendors include provisions about data handling, security, and performance?"
- "Do you periodically review your AI vendors' performance and compliance? How often?"
- "Have you reviewed your AI vendors' terms of service or data processing agreements in the past 12 months?"

*Common gap:* A.10.2 (supplier management) is the most common Major Gap for AI-user SMBs. Vendors are selected informally, contracts are accepted without review, and ongoing monitoring is absent.

#### 4.2 Annex A Assessment Summary Checklist

After completing all Annex A assessments, verify:

- [ ] All 39 controls have been assessed (scored or marked N/A)
- [ ] A.6.2.2, A.6.2.3, and A.10.4 are marked NOT APPLICABLE with justification text recorded
- [ ] All partially applicable controls have a scope note explaining what applies and what doesn't
- [ ] Every score is supported by at least one evidence reference
- [ ] No control is scored at 3 or above without documented evidence

---

### Step 5: Scoring & Gap Classification (Day 8–9)

**Objective:** Apply maturity scores to all clauses and controls, classify gaps by severity, and calculate domain averages. This step is internal — no client time required.

#### 5.1 Maturity Scoring Scale

Apply the following scale to every clause sub-requirement and every Annex A control. Use the full scale — do not default to 2 when evidence is ambiguous. When in doubt, score lower and note the uncertainty.

| Score | Level | Definition | Certification Implication |
|---|---|---|---|
| **0** | Not Addressed | No evidence of any activity related to this requirement. The requirement has not been considered. | Cannot certify. Critical remediation required. |
| **1** | Initial | Some awareness of the requirement exists. Activities occur informally or reactively, but there is no documented process and no consistent execution. | Cannot certify. Major remediation required. |
| **2** | Managed | Activities are planned and executed but not formally documented. Results are inconsistent. Practices depend on individual knowledge rather than defined processes. | Cannot certify. Significant remediation required. |
| **3** | Defined | Documented processes exist, are approved by appropriate authority, are communicated to relevant staff, and are consistently followed. Evidence of execution is available. **This is the minimum threshold for certification readiness.** | Certification possible. Minor improvements may be needed. |
| **4** | Measured | Processes are defined (Level 3) AND performance is measured against defined metrics. Results are analyzed and used to drive improvement decisions. | Exceeds certification requirements. |
| **5** | Optimized | Processes are measured (Level 4) AND continuously improved based on performance data, benchmarking, and innovation. Best-in-class practices. | Exceeds certification requirements. |

**Scoring rules:**
- Score based on evidence, not intent. "We plan to do this" = Score 0 or 1.
- Score based on consistent practice, not isolated examples. One risk assessment conducted once = Score 1, not Score 3.
- Score the weakest link. If a process is documented but not followed, score based on actual practice (Score 1–2), not the documentation (Score 3).
- For partially applicable controls, score only the applicable portion.
- For not applicable controls, enter "N/A" — do not score.

#### 5.2 Gap Severity Classification

After scoring, classify each gap (any score below 3) by severity. Use the following criteria:

| Severity | Criteria | Certification Impact | Remediation Priority |
|---|---|---|---|
| **Critical** | Score 0 on a mandatory clause requirement OR a fundamental process is entirely absent (no risk assessment methodology, no AI policy, no internal audit program) | Certification impossible without remediation | Phase 3, Week 1 |
| **Major** | Score 1 on any clause requirement OR Score 2 on a high-importance requirement (Clause 6 planning, Annex A core controls) | Certification unlikely without remediation | Phase 3, Weeks 1–3 |
| **Minor** | Score 2 on a lower-importance requirement OR Score 3 with documentation gaps | Certification possible but auditor may raise observation | Phase 3, Weeks 3–6 |
| **Observation** | Score 3 but with improvement opportunities noted OR Score 4 with optimization potential | No certification impact | Phase 3 or post-certification |

**Decision Tree — Gap Severity Classification:**

```
Gap identified (score below 3)?
│
├── Score = 0 (Not Addressed)?
│   ├── Is this a mandatory clause requirement (Clauses 4–10)?
│   │   └── YES → CRITICAL GAP
│   │       - Certification impossible without this
│   │       - Flag for immediate escalation if >5 Critical gaps (see E-5)
│   └── Is this an Annex A control?
│       ├── Fully Applicable → CRITICAL GAP
│       └── Partially Applicable → MAJOR GAP
│
├── Score = 1 (Initial)?
│   ├── Is this Clause 6 (Planning) or Clause 5 (Leadership)?
│   │   └── YES → MAJOR GAP (these are foundational)
│   └── Is this any other clause or control?
│       └── YES → MAJOR GAP
│
├── Score = 2 (Managed)?
│   ├── Is this Clause 6.1.2 (Risk Assessment), 6.1.4 (Impact Assessment), or 5.2 (AI Policy)?
│   │   └── YES → MAJOR GAP (documentation required for certification)
│   └── Is this any other clause or control?
│       └── YES → MINOR GAP (formalization needed)
│
└── Score = 3 (Defined) with issues noted?
    └── YES → OBSERVATION (improvement opportunity, not a gap)
```

#### 5.3 Calculating Domain Averages

After scoring all clauses and controls, calculate the following averages for the Gap Analysis Report:

1. **Clause average:** Average score across all sub-clauses within each clause group (4, 5, 6, 7, 8, 9, 10)
2. **Annex A domain average:** Average score across all applicable controls within each Annex A domain (A.2 through A.10)
3. **Overall AIMS maturity score:** Average of all clause and control scores (excluding N/A controls)

**Interpreting overall scores:**
- 0.0–1.0: Early stage. Significant build required. Certification 12–18 months away.
- 1.1–2.0: Foundation exists. Substantial formalization required. Certification 9–12 months away.
- 2.1–2.9: Approaching readiness. Targeted remediation required. Certification 6–9 months away.
- 3.0+: Certification ready. Minor improvements and evidence collection required. Certification 3–6 months away.

#### 5.4 Scoring Verification Checklist

Before finalizing scores, verify:

- [ ] Every clause sub-requirement has a score (0–5) or is marked N/A
- [ ] Every Annex A control has a score (0–5) or is marked N/A
- [ ] Every score below 3 has a gap description in the workbook
- [ ] Every gap description includes: what is missing, what evidence was reviewed, and what remediation is needed
- [ ] A.6.2.2, A.6.2.3, and A.10.4 are marked N/A with justification text
- [ ] Domain averages are calculated and recorded
- [ ] Overall AIMS maturity score is calculated

---

### Step 6: Findings Analysis & Prioritization (Day 9)

**Objective:** Analyze the scored gaps, identify dependency chains between gaps, and produce a prioritized remediation sequence. This step is internal — no client time required.

#### 6.1 Dependency Chain Analysis

Before prioritizing gaps, identify dependencies between them. Some gaps cannot be remediated until other gaps are closed first. Common dependency chains for AI-user SMBs:

**Chain 1: Policy → Everything**
- AI Policy (A.2.2, Clause 5.2) must exist before awareness training (A.4.4, Clause 7.3) can be conducted
- AI Policy must exist before acceptable use guidelines (A.6.2.10) can be written
- AI Policy must exist before the SoA (Clause 6.1.6) can be finalized
- *Implication:* If AI Policy is a Critical or Major Gap, it must be the first remediation item.

**Chain 2: Risk Assessment → Risk Treatment → SoA**
- Risk assessment methodology (Clause 6.1.2) must be defined before risk assessments can be conducted
- Risk assessments must be completed before risk treatment plans (Clause 6.1.3) can be developed
- Risk treatment plans must be completed before the SoA (Clause 6.1.6) can be finalized
- *Implication:* Clause 6 remediation must proceed in sequence: methodology → assessments → treatment → SoA.

**Chain 3: Impact Assessment → Impact Treatment → Disclosure**
- Impact assessment methodology (Clause 6.1.4) must be defined before impact assessments can be conducted
- Impact assessments must be completed before impact treatment plans (Clause 6.1.5) can be developed
- Impact assessments must be completed before disclosure obligations (A.8.2, A.8.3) can be fully addressed
- *Implication:* Impact assessment remediation must precede disclosure remediation.

**Chain 4: Roles → Processes → Records**
- Roles and responsibilities (A.3.2, Clause 5.3) must be defined before processes can be assigned to owners
- Processes must be defined before records can be generated
- Records must exist before internal audit (Clause 9.2) can be conducted
- *Implication:* Role definition must precede process development, which must precede audit.

**Chain 5: Vendor Contracts → Supplier Management**
- Vendor contracts must be reviewed and updated (A.10.2) before supplier management processes can be fully implemented
- Vendor assessment criteria must be defined before assessments can be conducted
- *Implication:* Contract review is a prerequisite for A.10.2 remediation.

#### 6.2 Prioritization Framework

Prioritize remediation items using the following framework. Assign each gap to a priority tier:

| Priority | Criteria | Phase 3 Timing |
|---|---|---|
| **P1 — Foundation** | Critical gaps + dependency chain anchors (AI Policy, Risk Assessment Methodology, Roles & Responsibilities) | Phase 3, Weeks 1–2 |
| **P2 — Core Processes** | Major gaps in Clause 6 (Planning) and Annex A core controls (A.5.2, A.5.3, A.6.2.10, A.6.2.11, A.9.5, A.10.2) | Phase 3, Weeks 2–4 |
| **P3 — Operational Controls** | Major gaps in Clause 7–8 and Annex A operational controls | Phase 3, Weeks 3–5 |
| **P4 — Performance & Improvement** | Major gaps in Clause 9–10 | Phase 3, Weeks 4–6 |
| **P5 — Minor Gaps** | Minor gaps and observations | Phase 3, Weeks 5–8 or post-certification |

#### 6.3 Remediation Effort Estimation

For each gap, estimate remediation effort using the following benchmarks. These are rough estimates for SMB clients — adjust based on client complexity.

| Gap Type | Typical Effort | Notes |
|---|---|---|
| Create AI policy from scratch | 8–12 hours | Includes drafting, review, approval, and communication |
| Develop risk assessment methodology | 4–6 hours | Includes procedure, criteria, and template |
| Conduct risk assessments for 5–10 AI systems | 2–3 hours per system | Includes assessment, documentation, and review |
| Conduct impact assessments for 3–5 high-risk systems | 3–4 hours per system | More complex than risk assessment |
| Develop acceptable use guidelines | 4–6 hours | Per AI system or as a general policy |
| Establish vendor management process | 6–8 hours | Includes procedure, assessment template, and initial assessments |
| Develop internal audit program | 4–6 hours | Includes schedule, methodology, and checklist |
| Establish document control procedure | 3–4 hours | If not already in place |
| Develop training materials | 6–10 hours | Depends on scope and format |
| Conduct awareness training | 1–2 hours per session | Plus scheduling and tracking |

#### 6.4 Remediation Priority Matrix — Format

Produce the Remediation Priority Matrix in the following format. One row per gap.

| # | Gap Description | Clause/Control | Severity | Score | Priority | Estimated Effort | Dependencies | Phase 3 Week |
|---|---|---|---|---|---|---|---|---|
| 1 | No AI policy exists | Clause 5.2, A.2.2, A.2.3 | Critical | 0 | P1 | 10 hours | None | Week 1 |
| 2 | No risk assessment methodology | Clause 6.1.2 | Critical | 0 | P1 | 5 hours | None | Week 1 |
| 3 | No impact assessments conducted | Clause 6.1.4, A.5.3 | Critical | 0 | P2 | 12 hours | Gap #2 | Week 2–3 |
| ... | ... | ... | ... | ... | ... | ... | ... | ... |

---

### Step 7: Report Assembly (Day 9–10)

**Objective:** Populate `template-gap-analysis-report.md` from the completed workbook. Produce a client-ready report that presents findings clearly and sets up Phase 3.

#### 7.1 Report Assembly Checklist

Complete the following sections of the Gap Analysis Report in order:

**Section 1 — Executive Summary:**
- [ ] State the overall AIMS maturity score and what it means
- [ ] List the top 3–5 findings (most significant gaps)
- [ ] State the certification readiness timeline estimate
- [ ] Summarize the recommended remediation approach

**Section 2 — Assessment Scope and Methodology:**
- [ ] Confirm the AIMS scope assessed (reference the Draft AIMS Scope Statement)
- [ ] List the assessment activities conducted (interviews, document review, dates)
- [ ] List the personnel interviewed
- [ ] State the maturity scoring scale used

**Section 3 — Clause-by-Clause Findings:**
For each clause group (4–10):
- [ ] State the clause average score
- [ ] List each sub-clause score
- [ ] Describe the key finding for each sub-clause (what exists, what's missing)
- [ ] List the evidence reviewed
- [ ] State the gap severity (Critical/Major/Minor/Observation)

**Section 4 — Annex A Control Assessment:**
- [ ] Include the Annex A control heatmap (color-coded by score: red=0–1, amber=2, green=3+, grey=N/A)
- [ ] For each domain, summarize the key findings
- [ ] List all N/A controls with justification

**Section 5 — Remediation Priority Matrix:**
- [ ] Include the full Remediation Priority Matrix from Step 6.4
- [ ] Group by priority tier (P1 through P5)
- [ ] Include estimated effort and dependencies

**Section 6 — Certification Readiness Assessment:**
- [ ] State the estimated timeline to certification readiness
- [ ] Identify the critical path items (what must be done first)
- [ ] Note any risks to the timeline (client resource constraints, complex gaps)

**Section 7 — Next Steps:**
- [ ] Phase 3 scope and approach
- [ ] Immediate actions before Phase 3 begins (if any)
- [ ] Phase 3 kickoff date

#### 7.2 Report Quality Checklist

Before delivering the report to the client, verify:

- [ ] All scores in the report match the workbook — no transcription errors
- [ ] All gap descriptions are factual and evidence-based — no speculation
- [ ] Tone is advisory and constructive — findings are presented as opportunities, not failures
- [ ] No internal-only language appears in the report (no references to escalation triggers, internal procedures, or fee discussions)
- [ ] Terminology matches the controlled vocabulary — use "AI system" in formal text, "AI tool" in conversational context
- [ ] All Annex A control IDs use the A.2–A.10 numbering scheme
- [ ] The report is readable by a non-technical executive — avoid jargon without explanation
- [ ] The Remediation Priority Matrix is actionable — each item has a clear owner, effort estimate, and timeline

#### 7.3 Sensitive Findings Guidance

Some findings require careful handling in the report:

**Shadow AI findings:** If Phase 1 identified unmanaged AI tools, reference them in the gap analysis as evidence of gaps in A.6.2.10 (defined use and misuse) and A.10.2 (supplier management). Do not name individual employees who were found using unauthorized tools.

**Leadership commitment gaps:** If Clause 5 scores are low, frame findings as "the organization has an opportunity to formalize leadership commitment" rather than "leadership is not committed to AI governance." The client sponsor is reading this report.

**Vendor contract gaps:** If vendor contracts lack AI-specific provisions, frame as "vendor agreements should be reviewed and updated to include AI governance provisions" — not as a legal compliance failure.

**High-risk AI systems:** If the assessment reveals AI systems with significant impact potential (e.g., AI-assisted hiring with no impact assessment), flag these clearly but frame remediation as achievable: "Conducting an impact assessment for [system] is a Phase 3 Week 2 priority and is achievable within the engagement timeline."

---

### Step 8: Client Presentation & Phase 3 Scoping (Day 10)

**Objective:** Present the Gap Analysis Report to the Client Sponsor, manage reactions to findings, and agree on the Phase 3 scope and approach.

**Duration:** 90 minutes

**Attendees:** Lead Consultant, Client Sponsor, Compliance/Risk Lead (and IT Lead if available)

#### 8.1 Presentation Structure

Structure the 90-minute session as follows:

| Time | Content |
|---|---|
| 0–5 min | Opening: purpose of the session, agenda overview |
| 5–15 min | Overall findings: maturity score, certification timeline, top 3 findings |
| 15–40 min | Clause-by-clause walkthrough: key findings per clause group (not every sub-clause — focus on Critical and Major gaps) |
| 40–55 min | Annex A highlights: domain averages, key control gaps, N/A justifications |
| 55–70 min | Remediation Priority Matrix: walk through P1 and P2 items, explain dependencies |
| 70–80 min | Phase 3 scope discussion: what Phase 3 will cover, timeline, resource requirements |
| 80–90 min | Q&A and next steps |

#### 8.2 Managing Client Reactions to Findings

**Reaction: "We're worse than I expected."**
Response: "This is very common for organizations at this stage. The gap analysis is designed to surface what needs to be built — and the good news is that we now have a clear, prioritized roadmap. Most of the gaps we've identified are addressable within the Phase 3 timeline."

**Reaction: "We're better than I expected — do we really need all this?"**
Response: "The gaps we've identified are requirements of the standard, not optional enhancements. The certification auditor will assess each of these areas. The good news is that your existing practices give us a strong foundation to build on."

**Reaction: "Some of these findings seem wrong — we do have that process."**
Response: "I'd like to understand more about that. Can you walk me through the process and show me where it's documented? If there's evidence I didn't see during the assessment, we can update the score." *Do not argue. If the client provides credible evidence, update the score. If the evidence doesn't meet the scoring criteria, explain why.*

**Reaction: "This is going to take too long / cost too much."**
Response: "Let's look at the critical path. The P1 and P2 items are what you need for certification — the P3–P5 items can be phased. We can discuss a Phase 3 scope that focuses on certification readiness first and builds toward optimization over time."

**Reaction: "Can we just document what we already do and call it done?"**
Response: "Documentation is part of the answer, but not all of it. For some gaps — like the risk assessment methodology and impact assessments — the process itself needs to be created, not just documented. For others — like document control — you may already have the practice and just need to formalize it. Let's go through the P1 items and distinguish between 'create' and 'document.'"

#### 8.3 Phase 3 Scoping Discussion

During the presentation, agree on the following Phase 3 parameters:

- [ ] **Phase 3 scope:** Which gaps will be addressed in Phase 3? (Recommend: all Critical and Major gaps at minimum)
- [ ] **Phase 3 timeline:** Target completion date for certification readiness
- [ ] **Client resource commitment:** Who from the client team will own each remediation item?
- [ ] **Consultant involvement:** Which remediation items will the consultant lead vs. support vs. review?
- [ ] **Certification body:** Has the client selected a certification body? If not, Phase 3 should include certification body selection.
- [ ] **Stage 1 audit target date:** When does the client want to schedule the Stage 1 (documentation review) audit?

#### 8.4 Post-Presentation Actions

- [ ] Send the final Gap Analysis Report to the Client Sponsor within 24 hours of the presentation
- [ ] Send the Remediation Priority Matrix as a standalone document for Phase 3 planning
- [ ] Schedule Phase 3 kickoff meeting
- [ ] Update the engagement folder with all Phase 2 deliverables
- [ ] Document any scope changes or new information surfaced during the presentation
- [ ] Check for any escalation triggers triggered during Phase 2 (see Section 9)

---

## 8. Referenced Documents

| Document | Location | Usage |
|---|---|---|
| Controlled Vocabulary | `00-foundation/glossary.md` | Term definitions used throughout this procedure |
| Annex A Control Reference | `00-foundation/annex-a-reference.md` | Control IDs, applicability ratings, and descriptions referenced in Steps 4–5 |
| Traceability Matrix | `00-foundation/traceability-matrix.md` | Maps clause requirements to Annex A controls and Phase 3 remediation items |
| AI System Inventory Template | `01-discovery/template-ai-system-inventory.md` | Phase 1 output; primary input to Annex A assessment |
| Stakeholder Register Template | `01-discovery/template-stakeholder-register.md` | Phase 1 output; primary input to Clause 4.2 assessment |
| Gap Analysis Workbook Template | `02-gap-analysis/template-gap-analysis-workbook.md` | Primary working document for Phase 2; completed during Steps 3–5 |
| Gap Analysis Report Template | `02-gap-analysis/template-gap-analysis-report.md` | Client-facing deliverable; populated in Step 7 |
| Phase 1 Discovery Procedure | `01-discovery/procedure-discovery-scoping.md` | Predecessor procedure; provides context for Phase 2 inputs |

---

## 9. Escalation Triggers

Monitor for the following conditions throughout Phase 2. When triggered, take the specified action before proceeding.

| ID | Trigger Condition | Action |
|---|---|---|
| **E-1** | Client scores all zeros (Score 0) across an entire clause group | Do not accept without verification. A complete absence of any activity is unusual even for immature organizations. Return to the interview and probe more specifically: "Is there anyone in the organization who thinks about [topic]? Has it ever been discussed?" If confirmed, document as Critical Gap and flag in the report. If the client has no awareness of the requirement at all, include a brief educational note in the report explaining what the clause requires and why it matters. |
| **E-2** | Client refuses to provide evidence or grant interview access for a clause group | Notify Client Sponsor immediately. Explain that the gap analysis cannot be completed without access to relevant personnel and documentation. If access is not granted within 48 hours, document the limitation in the Gap Analysis Report: "Assessment of [clause] was limited due to unavailability of [evidence/personnel]. Findings in this area are based on available information only and may not reflect the full current state." Adjust the engagement timeline accordingly. |
| **E-3** | AI systems discovered during Phase 2 that were not in the Phase 1 inventory | Stop and assess scope impact. If the newly discovered systems are within the agreed AIMS scope, add them to the AI System Inventory and include them in the Annex A assessment. If they represent a significant expansion (more than 3 new systems, or a new category of AI use), notify the Client Sponsor and discuss whether the Phase 2 scope needs to be adjusted. Document the discovery in the Gap Analysis Report. |
| **E-4** | Critical gaps in leadership commitment (Clause 5 scores all 0–1) | This is a significant risk to the engagement. Without leadership commitment, remediation in Phase 3 will be difficult to execute. Brief the Client Sponsor privately before the formal presentation. Frame the finding as: "For Phase 3 to succeed, we need visible leadership commitment — a named executive sponsor, an approved AI policy, and budget allocation. Without these, the certification timeline is at risk." If the Client Sponsor is the source of the commitment gap, escalate to your firm's senior consultant or engagement manager. |
| **E-5** | More than 5 Critical gaps identified across the assessment | The engagement complexity may exceed the original SOW. Assess whether the Phase 3 scope and timeline in the SOW are still realistic. If not, prepare a scope change discussion for the Phase 2 closing presentation. Present the finding factually: "We've identified [#] Critical gaps that each require significant remediation effort. The original Phase 3 timeline assumed [X] weeks. Based on these findings, we recommend [revised timeline] to ensure certification readiness." Do not proceed to Phase 3 without client agreement on the revised scope. |
| **E-6** | Client embeds AI outputs in services delivered to their customers | Annex A.10.4 (Provision of AI System to Third Parties) reclassifies from NOT APPLICABLE to FULLY APPLICABLE. Update the Annex A assessment to include A.10.4. Add assessment questions: "What documentation do you provide to customers about the AI capabilities in your service? How do you communicate AI limitations? What support do you provide if AI outputs cause issues for customers?" Update the SoA draft accordingly. |
| **E-7** | Client is using AI for high-stakes decisions about individuals with no human oversight | Flag immediately as a Critical Gap in A.9.5 (Human Oversight) and A.5.3 (Impact Assessment). Examples: AI-assisted hiring with no human review of AI recommendations, AI-driven credit or eligibility decisions with no appeal process, AI performance evaluation with no manager review. Recommend interim controls before Phase 3 begins: "While we develop the formal AIMS controls, we recommend immediately implementing a human review step for [specific AI use] to reduce risk exposure." Document the recommendation in the Gap Analysis Report. |

---

## 10. Revision History

| Version | Date | Author | Changes |
|---|---|---|---|
| 1.0 | March 2026 | [Author] | Initial release |

---

*ISO 42001 Readiness Service Toolkit | 02-Gap Analysis | Internal Use*
