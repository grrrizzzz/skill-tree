# Internal Procedure: Phase 3 — Remediation & Implementation Support

> **Current as of:** March 2026 | ISO/IEC 42001:2023

> **Document type:** Internal Procedure — Not for client distribution

---

## 1. Purpose

This procedure defines how to execute Phase 3 of an ISO 42001 readiness engagement. Phase 3 builds the client's AI Management System (AIMS) by translating gap analysis findings into documented, operational controls. Specifically, Phase 3:

- Converts gap analysis findings into a sequenced remediation plan with assigned owners and target dates
- Facilitates development of all required AIMS documentation: AI Policy, Acceptable Use Policy, Risk Assessment Register, Impact Assessments, Statement of Applicability, Risk Treatment Plan, and supporting records
- Guides the client through risk and impact assessment facilitation for each in-scope AI system
- Prepares the client for their first internal audit and the Phase 4 certification readiness review

A junior consultant with ISO management system experience but no prior ISO 42001 experience should be able to execute this procedure by following each step as written. Phase 3 is the longest and most client-intensive phase of the engagement. Expect significant variation in pace depending on client resource availability, gap severity, and management system maturity.

---

## 2. Scope

This procedure covers Phase 3 of any ISO 42001 readiness engagement for SMB clients (typically 40–200 employees) that use third-party AI systems. It begins after the Gap Analysis Report has been delivered and accepted by the Client Sponsor, and ends with the delivery of the Phase 3 Completion Package and handoff to Phase 4.

This procedure does not cover AI development, model training, or any activities where the client is acting as an AI developer or AI provider. It does not cover the internal audit itself (Phase 4) or the certification audit (Phase 5).

---

## 3. Roles

| Role | Responsibility in Phase 3 |
|---|---|
| **Lead Consultant** | Executes this procedure. Facilitates all working sessions, produces or co-produces all deliverables, manages timeline, tracks remediation progress, escalates blockers. |
| **Client Sponsor** | Executive point of contact. Approves AI Policy and Acceptable Use Policy. Provides residual risk acceptance decisions. Removes organizational blockers. Typically CEO, COO, or VP-level. |
| **Client AIMS Owner** | Day-to-day client counterpart. Coordinates internal stakeholder availability, manages document review cycles, maintains the remediation tracker. Typically a compliance, IT, or operations lead. |
| **Client IT Lead** | Technical input for AI system documentation, data flow confirmation, supplier contract review, and integration details. |
| **Department Heads / AI System Owners** | Provide operational context for risk and impact assessments. Assigned as owners for specific remediation items. Participate in working sessions relevant to their AI systems. |
| **Client Legal / HR** | Engaged for impact assessments involving people-affecting AI systems and for review of supplier contract gaps. |

---

## 4. Inputs

| Input | Source | Required? | Notes |
|---|---|---|---|
| Gap Analysis Report | `02-gap-analysis/template-gap-analysis-report.md` (completed) | **Yes** | Primary driver of remediation priorities. Must be accepted by Client Sponsor before Phase 3 begins. |
| Gap Analysis Workbook | `02-gap-analysis/template-gap-analysis-workbook.md` (completed) | **Yes** | Row-level findings used to build the remediation priority matrix in Step 1. |
| AI System Inventory | Phase 1 output | **Yes** | Defines which AI systems require risk assessment, impact assessment, and SoA coverage. |
| Stakeholder Register | Phase 1 output (`template-stakeholder-register.md` completed) | **Yes** | Identifies interested parties whose requirements shape policy content and impact assessment scope. |
| Draft AIMS Scope Statement | Phase 1 output | **Yes** | Defines the boundaries within which all Phase 3 documentation applies. Must be finalized before SoA work begins. |
| Existing management system documentation | Client Sponsor / IT Lead | If available | ISO 27001 ISMS, ISO 9001 QMS, or similar — leverage existing policies, procedures, and records infrastructure where possible. |
| Vendor/supplier contracts for in-scope AI systems | Client IT Lead or Legal | **Yes** | Required for supplier assessment in Step 8. Collect early — contract retrieval often takes longer than expected. |

---

## 5. Outputs

| Output | Description | Feeds Into |
|---|---|---|
| Remediation Priority Matrix | Sequenced list of all gap findings with owners, target dates, and dependencies | Tracks Phase 3 progress; referenced in Phase 4 handoff |
| AI Policy | Completed `template-ai-policy.md` — formal organizational AI policy approved by top management | SoA (A.2.2, A.2.3), Phase 4 internal audit |
| Acceptable Use Policy | Completed `template-acceptable-use-policy.md` — defines permitted and prohibited AI uses for all staff | SoA (A.6.2.10, A.9.3), Phase 4 internal audit |
| Risk Assessment Register | Completed `template-risk-assessment-register.md` — risk assessment for each in-scope AI system | SoA (A.5.2), Risk Treatment Plan, Phase 4 internal audit |
| Impact Assessment(s) | Completed `template-impact-assessment.md` — one per AI system meeting the impact assessment threshold | SoA (A.5.3, A.5.4), Phase 4 internal audit |
| Statement of Applicability | Completed `template-soa.md` — all 39 Annex A controls assessed with applicability determination and justification | Phase 4 internal audit; first document auditors request |
| Risk Treatment Plan | Completed `template-risk-treatment-plan.md` — maps risks to controls, documents treatment decisions, records residual risk acceptance | SoA, Phase 4 internal audit |
| Supplier Assessment(s) | Completed `template-supplier-assessment.md` — one per in-scope AI vendor | SoA (A.10.2, A.6.2.11), Phase 4 internal audit |
| Implementation Roadmap | Completed `template-implementation-roadmap.md` — sequenced plan for ongoing AIMS operation post-certification | Phase 4 handoff, client self-management |
| Training & Competence Records | Completed `template-training-competence-records.md` — evidence of AI awareness training and role-specific competency | SoA (A.4.3, A.4.4), Phase 4 internal audit |
| NCAR Log | Initialized `template-ncar-log.md` — Nonconformity and Corrective Action Report log | Phase 4 internal audit, ongoing AIMS operation |
| Phase 3 Completion Package | All above deliverables, quality-checked and organized for Phase 4 handoff | Phase 4 kickoff |

---

## 6. Time Estimate

| Activity | Duration | Notes |
|---|---|---|
| Remediation Planning | Week 1 | Internal analysis + client kickoff session |
| AI Policy Development | Week 1–2 | 1–2 working sessions with Client Sponsor |
| Acceptable Use Policy Development | Week 2 | 1 working session; often faster if AI Policy is complete |
| Risk Assessment Facilitation | Week 2–4 | One session per AI system or system cluster; most time-intensive activity |
| Impact Assessment Facilitation | Week 3–5 | Subset of AI systems; involves HR and/or Legal |
| Statement of Applicability Development | Week 4–6 | 2–3 working sessions; depends on risk assessment completion |
| Risk Treatment Plan Development | Week 5–7 | Follows SoA; requires residual risk acceptance from Client Sponsor |
| Third-Party Supplier Assessment | Week 5–8 | Depends on vendor responsiveness; start early |
| Supporting Documentation | Week 6–10 | Implementation roadmap, training records, NCAR log |
| Internal Audit Preparation | Week 10–14 | Brief client team; conduct readiness walkthrough |
| Phase 3 Completion Review | Week 14–16 | Quality check all deliverables; prepare Phase 4 handoff package |
| **Total elapsed time** | **8–16 weeks** | Depends on gap severity, number of AI systems, and client resource availability |

> **Note on timeline variability:** The 8-week lower bound assumes a client with fewer than 10 AI systems, moderate gaps, an existing management system (ISO 27001 or ISO 9001), and a dedicated AIMS Owner who can commit 4–6 hours per week. The 16-week upper bound reflects clients with 15+ AI systems, critical gaps across multiple domains, no existing management system, and limited internal resource availability. Set expectations with the Client Sponsor at Phase 3 kickoff.

---

## 7. Step-by-Step Procedure

---

### Step 1: Remediation Planning (Week 1)

**Objective:** Transform gap analysis findings into a sequenced, owned, time-bound remediation plan. Establish the working rhythm for Phase 3.

**Duration:** 2–3 hours internal preparation + 90-minute kickoff session with client

**Attendees (kickoff session):** Lead Consultant, Client Sponsor, Client AIMS Owner

#### 1.1 Build the Remediation Priority Matrix

Before the client kickoff session, review the completed Gap Analysis Workbook and build the Remediation Priority Matrix. This is an internal working document — not a client deliverable — but it drives all Phase 3 scheduling.

For each gap finding in the workbook, capture:

| Column | Content |
|---|---|
| Finding ID | Reference the workbook row ID (e.g., W-A.2.2-01) |
| Gap Description | Brief description of what is missing or insufficient |
| Severity | Critical / Major / Minor (from workbook) |
| Annex A Control(s) | Which controls the finding relates to |
| Remediation Action | What needs to be built or changed |
| Dependency | What must be completed before this item can start |
| Assigned Owner | Client role responsible for this item |
| Target Completion | Week number within Phase 3 |
| Status | Not Started / In Progress / Complete |

**Sequencing rule:** The critical path for AIMS documentation is:

```
AI Policy (A.2.2, A.2.3)
    ↓
Risk Assessment (A.5.2) + Impact Assessment (A.5.3, A.5.4)
    ↓
Statement of Applicability (Clause 6.1.6)
    ↓
Risk Treatment Plan (Clause 6.1.3)
    ↓
All other controls (A.3–A.10 as applicable)
```

Do not begin SoA work until the risk assessment is substantially complete. The SoA applicability determinations must reflect actual risk treatment decisions, not hypothetical ones.

#### 1.2 Decision Tree: Remediation Sequencing

```
What is the client's most critical gap?
│
├── NO AI POLICY EXISTS (Critical gap — A.2.2)
│   → Start here. Everything else references the policy.
│   → Schedule AI Policy working session in Week 1.
│   → Do not begin risk assessment until policy scope is agreed.
│
├── NO RISK ASSESSMENT PROCESS (Critical gap — A.5.2)
│   → Second priority after policy.
│   → Risk assessment results feed the SoA and Risk Treatment Plan.
│   → Schedule risk assessment sessions in Weeks 2–4.
│
├── NO IMPACT ASSESSMENTS (Critical gap — A.5.3)
│   → Run parallel with risk assessment where possible.
│   → Requires HR/Legal involvement — schedule early.
│
├── INCOMPLETE OR MISSING SoA (Critical gap — Clause 6.1.6)
│   → Cannot complete SoA until risk assessment is done.
│   → Block time in Weeks 4–6 for SoA working sessions.
│
├── SUPPLIER MANAGEMENT GAPS (Major gap — A.10.2)
│   → Start supplier contract collection in Week 1 (takes time).
│   → Assessment sessions can run in Weeks 5–8.
│
└── DOCUMENTATION GAPS ONLY (Minor gaps)
    → Address in Weeks 6–10 after core documents are complete.
    → These are the fastest items to close.
```

#### 1.3 Decision Tree: Leveraging Existing Management System

If the client has an existing ISO 27001 ISMS or ISO 9001 QMS, significant Phase 3 effort can be reduced by extending existing infrastructure rather than building from scratch.

```
Does the client have an existing certified management system?
│
├── YES — ISO 27001 (ISMS)
│   ├── Document control → Extend existing document control procedure to cover AIMS documents
│   ├── Internal audit → Extend existing internal audit program to include AIMS scope
│   ├── Management review → Add AIMS agenda items to existing management review
│   ├── Corrective action → Use existing NCAR process; add AI-specific categories
│   ├── Risk assessment → Adapt existing risk methodology for AI-specific risks
│   │   (Note: AI risk assessment has different dimensions — bias, over-reliance,
│   │   vendor lock-in — that may not be in the existing ISMS risk register)
│   ├── Supplier management → Extend existing supplier assessment to cover AI vendors
│   └── Awareness training → Add AI-specific module to existing security awareness program
│
├── YES — ISO 9001 (QMS)
│   ├── Document control → Extend existing document control to AIMS documents
│   ├── Internal audit → Extend existing audit program to AIMS scope
│   ├── Management review → Add AIMS agenda items
│   ├── Corrective action → Use existing NCR process; add AI-specific categories
│   ├── Risk-based thinking → Foundation exists; AI risk assessment is more structured
│   └── Note: ISO 9001 has less overlap with AI-specific controls (A.5–A.10)
│       than ISO 27001. More new content will be required.
│
└── NO — Building from scratch
    → All Clause 4–10 processes must be created
    → Add 2–4 weeks to Phase 3 estimate
    → Client will need management system fundamentals education
    → Prioritize: document control, corrective action, internal audit process
    → These are prerequisites for a functioning AIMS, not optional
```

> **Callout — Integration Tip:** When extending an existing management system, always document the integration explicitly. The SoA should note which controls are addressed through the existing ISMS/QMS and which are AIMS-specific. Auditors appreciate clarity about integrated vs. standalone management systems.

#### 1.4 Decision Tree: Client Resource Constraints

```
Is the client able to dedicate adequate time to Phase 3?
│
├── YES — AIMS Owner available 4–6 hours/week, sponsor available for approvals
│   → Proceed with standard timeline
│
├── PARTIAL — AIMS Owner available but limited (2–3 hours/week)
│   → Extend timeline by 30–50%
│   → Prioritize working sessions over async document review
│   → Reduce session frequency; increase session length
│   → Flag risk to Client Sponsor: timeline extension may affect certification target
│
├── MINIMAL — No dedicated AIMS Owner; sponsor is primary contact
│   → Significant risk to timeline and quality
│   → Escalate immediately (see Escalation Trigger E-1)
│   → Consider whether Phase 3 scope needs to be reduced
│   → Consultant may need to draft more content for client review
│   → Document all decisions made without full client input
│
└── CRISIS — Key personnel unavailable due to organizational disruption
    → Pause Phase 3 activities
    → Notify Client Sponsor in writing
    → Document pause date and reason
    → Resume only when minimum resource availability is confirmed
    → See Escalation Trigger E-2
```

#### 1.5 Phase 3 Kickoff Session

Conduct a 90-minute kickoff session with the Client Sponsor and AIMS Owner. Cover:

1. **Review gap analysis findings** (15 minutes): Walk through the severity summary from the Gap Analysis Report. Confirm the client understands what Critical, Major, and Minor gaps mean for certification readiness.

2. **Present the remediation sequence** (20 minutes): Walk through the critical path. Explain why policy must come before risk assessment, and why risk assessment must come before the SoA. Clients often want to jump to the SoA — redirect them.

3. **Assign client owners** (20 minutes): For each remediation item, assign a named client owner. The owner is responsible for providing input, reviewing drafts, and obtaining approvals within their function. The consultant facilitates; the client owns.

4. **Confirm working session schedule** (15 minutes): Book all Phase 3 working sessions now. Clients who don't commit to dates in Week 1 consistently fall behind schedule.

5. **Confirm document collection** (10 minutes): Identify any documents needed for Phase 3 that haven't been collected yet (vendor contracts, existing policies, HR training records). Assign collection to the AIMS Owner with a deadline.

6. **Agree on communication cadence** (10 minutes): Weekly status email from consultant to AIMS Owner. Bi-weekly check-in call. Escalation path if blockers arise.

#### 1.6 Post-Kickoff Actions

- [ ] Finalize Remediation Priority Matrix with client-assigned owners and agreed target dates
- [ ] Send kickoff summary email to Client Sponsor and AIMS Owner within 24 hours
- [ ] Confirm all working session bookings
- [ ] Begin vendor contract collection (do not wait — this is always the longest lead-time item)
- [ ] Identify any existing policies that may be extended rather than replaced

---

### Step 2: AI Policy Development (Week 1–2)

**Objective:** Facilitate development of the client's formal AI Policy — the foundational AIMS document that establishes organizational commitments to responsible AI. Addresses controls A.2.2 and A.2.3.

**Duration:** 2 working sessions (60–90 minutes each) + document drafting and review cycle

**Attendees:** Lead Consultant, Client Sponsor, Client AIMS Owner (Legal if available)

**Template:** `template-ai-policy.md`

#### 2.1 Decision Tree: Build vs. Extend

```
Does the client have an existing IT, security, or acceptable use policy?
│
├── YES — Existing policy covers some AI-relevant content
│   ├── Is AI mentioned explicitly?
│   │   ├── YES → Assess whether existing AI language meets A.2.2 and A.2.3 requirements
│   │   │   - If yes: Extend with AIMS-specific additions (scope, objectives, roles)
│   │   │   - If no: Use existing policy as a base; rewrite AI sections substantially
│   │   └── NO → Add AI Policy as a standalone document that references the existing policy
│   │       - Avoids disrupting existing approved policy
│   │       - Easier to get approved quickly
│   │       - Note in SoA: "AI Policy supplements [existing policy name]"
│   │
│   └── Is the existing policy actively maintained and recently reviewed?
│       ├── YES → Extend it (faster approval path)
│       └── NO → Create standalone AI Policy; flag existing policy for future consolidation
│
└── NO — No existing policy
    → Build from scratch using template-ai-policy.md
    → Expect 2–3 working sessions and 1–2 review cycles
    → Client Sponsor must approve final version
```

#### 2.2 Interview Script — AI Policy Content Session

Use this script in the first AI Policy working session. The goal is to gather the content needed to populate the policy template. Do not draft the policy during this session — capture answers and draft afterward.

**Opening (2 minutes):**
"The AI Policy is the cornerstone of your AIMS. It tells your employees, customers, and auditors what your organization believes about responsible AI and how you've committed to governing it. We're going to work through the key decisions together, and I'll draft the policy based on what we agree on today."

**Section A: Policy Scope and Purpose (15 minutes)**

1. "Which parts of the organization does this policy apply to? All employees? Contractors? Specific departments?"
2. "Does this policy cover all AI systems in your inventory, or are there any you'd like to treat differently?"
3. "What is the primary purpose of your AI use — efficiency, customer service, decision support, something else? This shapes how we frame the policy objectives."
4. "Are there any AI uses you want to explicitly prohibit at the policy level — not just in the acceptable use policy, but as a matter of organizational principle?"

**Section B: Responsible AI Commitments (20 minutes)**

5. "ISO 42001 requires your policy to address responsible AI principles. Let me walk through each one and get your input on how it applies to your organization."
   - **Fairness:** "Do you have any AI systems that make or influence decisions about people — hiring, customer treatment, pricing? How do you want to commit to fairness in those contexts?"
   - **Transparency:** "How transparent do you want to be with customers and employees about your AI use? Do you want to commit to disclosing when AI is involved in interactions or decisions?"
   - **Accountability:** "Who is ultimately accountable for AI-related decisions in your organization? How do you want to express that in the policy?"
   - **Human oversight:** "What level of human review do you want to require before acting on AI outputs? Is this different for high-stakes decisions vs. routine tasks?"
   - **Privacy:** "How do you want to commit to protecting personal data that flows through AI systems?"
   - **Safety:** "Are there any AI uses where safety is a concern — physical safety, financial safety, or safety of vulnerable individuals?"

6. "Are there any responsible AI principles that are particularly important to your leadership or your customers that we should emphasize?"

**Section C: Roles and Governance (15 minutes)**

7. "Who will be named as the AIMS Owner in the policy — the person responsible for maintaining the AI management system?"
8. "Who approves new AI tools before they're adopted? Is this a single person or a committee?"
9. "Who is responsible for reviewing the AI Policy annually and recommending updates?"
10. "Does your organization have a board or advisory committee that should be referenced in the policy?"

**Section D: Objectives and Review (10 minutes)**

11. "What are 2–3 measurable objectives you want to set for responsible AI use in the next 12 months? Examples: complete risk assessments for all AI systems, achieve 100% staff AI awareness training completion, reduce shadow AI incidents to zero."
12. "How often do you want to formally review the AI Policy? Annually is standard; some clients prefer semi-annually in the first year."

#### 2.3 AI Policy Drafting Guidance

After the content session, draft the AI Policy using `template-ai-policy.md`. The policy must address all A.2.3 responsible AI topics. Use this checklist to verify completeness before sending for client review:

- [ ] **Scope:** Clearly states which organizational units, employees, and AI systems the policy covers
- [ ] **Purpose:** States why the organization has an AI policy and what it is designed to achieve
- [ ] **Responsible AI commitments:** Addresses fairness, transparency, accountability, human oversight, privacy, and safety — all six topics required by A.2.3
- [ ] **AI objectives:** Includes at least 2 measurable objectives for responsible AI use
- [ ] **Roles:** Names the AIMS Owner and defines top management's commitment
- [ ] **Compliance:** References ISO/IEC 42001:2023 and any applicable regulatory frameworks
- [ ] **Review cycle:** States how often the policy will be reviewed and by whom
- [ ] **Approval:** Includes signature block for Client Sponsor approval

#### 2.4 Approval Process Guidance

The AI Policy must be approved by top management (Client Sponsor or equivalent). Walk the client through this process:

1. **Draft review:** Send draft to Client Sponsor and AIMS Owner. Allow 5 business days for review.
2. **Revision cycle:** Incorporate feedback. Limit to 2 revision cycles — if more are needed, schedule a working session to resolve disagreements directly.
3. **Formal approval:** Client Sponsor signs the policy. Date the approval. Store the signed version as a controlled document.
4. **Communication:** Once approved, the policy must be communicated to all employees. This is an A.4.4 requirement. Coordinate with the AIMS Owner on communication method (all-staff email, intranet posting, team meeting).

#### 2.5 Post-Session Actions

- [ ] Draft AI Policy within 3 business days of content session
- [ ] Send draft to Client Sponsor and AIMS Owner for review
- [ ] Track review cycle; follow up if no response within 5 business days
- [ ] Once approved, confirm communication plan with AIMS Owner
- [ ] Update Remediation Priority Matrix: mark A.2.2 and A.2.3 as complete upon approval

---

### Step 3: Acceptable Use Policy Development (Week 2)

**Objective:** Facilitate development of the Acceptable Use Policy (AUP) — the operational document that tells employees specifically what they can and cannot do with AI tools. Addresses control A.6.2.10 and supports A.9.3.

**Duration:** 1 working session (60–90 minutes) + drafting and review cycle

**Attendees:** Lead Consultant, Client AIMS Owner, HR representative (recommended), IT Lead

**Template:** `template-acceptable-use-policy.md`

#### 3.1 What the AUP Must Cover

The Acceptable Use Policy is distinct from the AI Policy. The AI Policy states organizational commitments and principles. The AUP tells individual employees what to do and not do. It must be specific enough that an employee can read it and know whether a specific action is permitted.

The AUP must address:

| Section | Content Required |
|---|---|
| **Permitted uses** | Specific AI tools approved for use; approved use cases per tool; any conditions on use (e.g., "Copilot may be used for drafting internal documents but not for generating client-facing content without human review") |
| **Prohibited uses** | Explicit list of prohibited actions — entering customer PII into non-approved AI tools, using personal AI accounts for work purposes, using AI to make final hiring decisions without human review, using AI to generate content that will be presented as entirely human-authored without disclosure |
| **Data handling rules** | What categories of data may and may not be entered into AI tools; how to handle AI-generated content that contains sensitive information; data retention rules for AI interaction logs |
| **Reporting obligations** | How employees report unexpected AI outputs, suspected AI misuse, or AI-related incidents; who to contact; what information to include in a report |
| **Consequences** | What happens if an employee violates the AUP — disciplinary process, escalation path |
| **Scope** | Who the policy applies to (employees, contractors, temporary staff) |
| **Review and updates** | How employees will be notified of AUP changes |

#### 3.2 Working Session Script

**Opening (2 minutes):**
"The Acceptable Use Policy is what your employees will actually read and follow day-to-day. We want it to be specific enough to be useful, but not so long that no one reads it. Let's work through the key decisions."

**Section A: Approved Tools (15 minutes)**

1. "Looking at your AI System Inventory, which tools do you want to formally approve for employee use? Are there any you want to restrict to specific departments or roles?"
2. "Are there any AI tools currently in use that you want to prohibit going forward? How will you communicate that to affected employees?"
3. "What is the process for an employee to request approval for a new AI tool? Who approves it?"

**Section B: Data Handling Rules (20 minutes)**

4. "What categories of data are employees absolutely prohibited from entering into AI tools? Walk me through your data classification — what's most sensitive?"
5. "Are there AI tools where you're comfortable with employees entering customer data? What conditions apply?"
6. "What should an employee do if they accidentally enter sensitive data into an AI tool?"
7. "Do you want to require employees to review AI-generated content before using it? For all content, or only certain types?"

**Section C: Prohibited Uses (15 minutes)**

8. "Are there any AI use cases you want to explicitly prohibit — not just restrict, but ban outright?"
   - *Common prohibitions for SMB clients: using AI to make final hiring decisions, using AI to generate legal or financial advice without professional review, using personal AI accounts for work, sharing proprietary information with AI tools not covered by a data processing agreement*
9. "Are there any AI uses that would violate your existing policies (data protection, confidentiality, code of conduct) that we should cross-reference?"

**Section D: Reporting and Consequences (10 minutes)**

10. "If an employee sees an AI tool produce a biased, incorrect, or harmful output, who should they report it to? What information should they capture?"
11. "What are the consequences for violating the AUP? Does this align with your existing disciplinary process?"

#### 3.3 Staff Communication Guidance

Once the AUP is approved, it must be communicated to all employees. Provide the following guidance to the AIMS Owner:

- **Communication method:** All-staff email with the AUP attached, plus posting on the intranet or shared drive. For organizations with fewer than 50 employees, a brief all-hands meeting is more effective.
- **Acknowledgment:** Require employees to acknowledge receipt. A simple email reply or a checkbox in the HR system is sufficient. Keep acknowledgment records — auditors may ask for evidence that the AUP was communicated.
- **Training integration:** The AUP should be covered in the AI awareness training (Step 9). New employees should receive the AUP as part of onboarding.
- **Timing:** Communicate the AUP within 2 weeks of approval. Do not wait until all Phase 3 documents are complete.

#### 3.4 Post-Session Actions

- [ ] Draft AUP within 3 business days of working session
- [ ] Send draft to AIMS Owner and HR for review
- [ ] Confirm approval process with Client Sponsor (AUP typically approved by AIMS Owner or HR, not necessarily Client Sponsor)
- [ ] Confirm communication plan and acknowledgment method
- [ ] Update Remediation Priority Matrix: mark A.6.2.10 as in progress

---

### Step 4: AI Risk Assessment Facilitation (Week 2–4)

**Objective:** Facilitate a formal risk assessment for each in-scope AI system. Produce a completed Risk Assessment Register that identifies, scores, and documents risks for all AI systems. Addresses control A.5.2.

**Duration:** 60–90 minutes per AI system or system cluster + internal analysis time

**Attendees:** Lead Consultant, Client AIMS Owner, AI System Owner (the person responsible for each system), IT Lead (for technical risk context)

**Template:** `template-risk-assessment-register.md`

#### 4.1 Risk Assessment Facilitation Approach

Do not attempt to assess all AI systems in a single session. Group AI systems by department or function and run one session per group. For clients with fewer than 8 AI systems, a single 2-hour session may be sufficient.

**Session structure:**
- 10 minutes: Explain the risk assessment methodology (likelihood × impact scoring)
- 50–70 minutes: Walk through each AI system using the interview script below
- 10 minutes: Confirm scores and next steps

#### 4.2 Interview Script — Risk Assessment Facilitation

Use this script for each AI system. Adapt the questions based on the system's role and risk classification from the AI System Inventory.

**Opening (2 minutes):**
"We're going to assess the risks associated with [AI System Name]. I'll ask you questions about how the system is used, what could go wrong, and how likely and serious those problems would be. There are no wrong answers — we're trying to capture the real risks, not the theoretical ones."

**Section A: System Context (10 minutes)**

1. "How does your team use [AI System Name] day-to-day? Walk me through a typical use case."
2. "What decisions does this system inform or make? Are those decisions reviewed by a human before action is taken?"
3. "What data goes into this system? Who has access to the outputs?"
4. "How dependent is your team on this system? If it were unavailable for a week, what would happen?"

**Section B: Risk Identification (25 minutes)**

For each of the following risk categories, ask: "Has this happened, or could it happen with [AI System Name]?"

| Risk Category | Prompt Questions |
|---|---|
| **Data leakage / privacy** | "Could sensitive data entered into this system be exposed to the vendor, other users, or the public? Has the vendor confirmed how your data is used for model training?" |
| **Bias / unfair outcomes** | "Could this system produce outputs that are unfair to certain groups of people — based on gender, age, ethnicity, or other characteristics? Does your team check for this?" |
| **Over-reliance / automation bias** | "Is there a risk that your team accepts AI outputs without sufficient critical review? Have you seen cases where the AI was wrong but the output was used anyway?" |
| **Vendor lock-in** | "How difficult would it be to switch to a different AI vendor? Are your processes or data formats tied to this specific vendor?" |
| **Regulatory non-compliance** | "Could using this system create compliance issues — GDPR, CCPA, sector-specific regulations, or employment law?" |
| **Inaccurate outputs** | "How often does this system produce incorrect, outdated, or misleading outputs? What is the impact when it does?" |
| **Unauthorized use** | "Could employees use this system in ways that weren't intended or approved? Is there any monitoring in place?" |
| **Vendor failure / service disruption** | "What happens if the vendor has an outage, changes their pricing, or discontinues the product?" |
| **Reputational risk** | "Could AI-generated content or decisions associated with this system damage your organization's reputation if they became public?" |

**Section C: Risk Scoring (15 minutes)**

For each identified risk, assign:

- **Likelihood:** 1 (Rare) / 2 (Unlikely) / 3 (Possible) / 4 (Likely) / 5 (Almost Certain)
- **Impact:** 1 (Negligible) / 2 (Minor) / 3 (Moderate) / 4 (Major) / 5 (Catastrophic)
- **Risk Score:** Likelihood × Impact (1–25)
- **Risk Level:** Low (1–6) / Medium (7–14) / High (15–25)

**Scoring guidance for SMB AI users:**

| Risk Level | Score | Typical Treatment |
|---|---|---|
| **High** | 15–25 | Immediate mitigation required; must appear in Risk Treatment Plan with specific controls |
| **Medium** | 7–14 | Mitigation planned; controls documented in Risk Treatment Plan |
| **Low** | 1–6 | Accept or monitor; document acceptance rationale |

#### 4.3 Common AI Risks for SMB AI Users

Use this reference list to prompt risk identification when clients struggle to identify risks. These are the most common risks for organizations using third-party AI tools.

**Data and Privacy Risks:**
- Customer PII entered into AI tools without adequate data processing agreements
- Employee data processed by AI tools without employee awareness or consent
- AI vendor uses customer data for model training without explicit opt-out
- AI-generated outputs contain hallucinated personal information about real individuals

**Operational Risks:**
- Over-reliance on AI outputs without human verification (automation bias)
- AI system unavailability disrupts business processes that have become dependent on it
- AI outputs are inconsistent or degrade over time as the underlying model changes
- Employees use AI tools outside their intended scope (mission creep)

**Compliance and Legal Risks:**
- AI-assisted hiring decisions create employment discrimination liability
- AI-generated content violates copyright or intellectual property rights
- AI tool usage violates sector-specific regulations (healthcare, finance, education)
- Lack of disclosure when AI is used in customer-facing interactions

**Vendor and Supply Chain Risks:**
- Vendor changes pricing, terms, or data handling practices without adequate notice
- Vendor experiences a data breach affecting client data
- Vendor discontinues the AI product or feature
- Vendor's AI model has known biases that affect the organization's use case

**Reputational Risks:**
- AI-generated content is factually incorrect and published externally
- AI-assisted decisions affecting customers are perceived as unfair or discriminatory
- Shadow AI use by employees creates data exposure that becomes public

#### 4.4 Post-Session Actions

- [ ] Complete Risk Assessment Register entries for all AI systems assessed in the session
- [ ] Confirm risk scores with the AI System Owner within 48 hours
- [ ] Flag any High-risk findings to Client Sponsor immediately
- [ ] Identify which risks require impact assessment (see Step 5 decision tree)
- [ ] Update Remediation Priority Matrix

---

### Step 5: AI System Impact Assessment Facilitation (Week 3–5)

**Objective:** Facilitate impact assessments for AI systems that meet the impact assessment threshold. Produce completed Impact Assessment documents for each qualifying system. Addresses controls A.5.3 and A.5.4.

**Duration:** 90–120 minutes per AI system requiring assessment

**Attendees:** Lead Consultant, Client AIMS Owner, AI System Owner, HR representative (for people-affecting AI), Legal (for regulatory implications)

**Template:** `template-impact-assessment.md`

#### 5.1 Decision Tree: Which AI Systems Require Impact Assessment

```
Does the AI system affect individuals (employees, customers, or other people)?
│
├── YES
│   ├── Is the system classified as High Risk in the Risk Assessment Register?
│   │   ├── YES → IMPACT ASSESSMENT REQUIRED
│   │   │   Examples: AI-assisted hiring, customer credit scoring, performance evaluation AI,
│   │   │   AI-driven customer eligibility determinations
│   │   │
│   │   └── NO (Medium or Low Risk)
│   │       ├── Does the system make or significantly influence decisions about individuals?
│   │       │   ├── YES → IMPACT ASSESSMENT REQUIRED
│   │       │   │   Examples: AI lead scoring that determines sales outreach priority,
│   │       │   │   AI sentiment analysis used to flag employee concerns
│   │       │   └── NO → Impact assessment recommended but not required
│   │       │       Document rationale for not conducting assessment
│   │
│   └── Does the system process personal data (PII, health data, financial data)?
│       ├── YES → IMPACT ASSESSMENT STRONGLY RECOMMENDED
│       │   Note: If GDPR applies, a DPIA may also be required — flag for Legal
│       └── NO → Impact assessment at consultant's discretion based on context
│
└── NO — System does not affect individuals
    → Impact assessment not required
    → Document this determination in the Risk Assessment Register
    → Example: AI tool used only for internal data analysis with no individual-level outputs
```

**Minimum threshold:** All AI systems classified as High Risk in the Risk Assessment Register require an impact assessment. All AI systems that make or influence decisions about individuals require an impact assessment, regardless of risk classification.

#### 5.2 Who to Involve

| AI System Type | Required Participants |
|---|---|
| AI used in hiring, performance evaluation, or workforce management | HR representative + Legal (employment law implications) |
| AI used in customer-facing decisions (eligibility, pricing, service) | Customer-facing team lead + Legal (consumer protection implications) |
| AI processing health or financial data | Legal + Compliance (sector-specific regulatory implications) |
| AI used in marketing or communications | Marketing lead + Legal (advertising standards, disclosure obligations) |
| All impact assessments | Client AIMS Owner + AI System Owner |

#### 5.3 Interview Script — Impact Assessment Facilitation

**Opening (3 minutes):**
"An impact assessment asks a specific question: what could this AI system do to people? Not just what could go wrong technically, but what are the real-world effects on individuals if the system produces incorrect, biased, or harmful outputs? We're going to work through this systematically."

**Section A: Affected Individuals (15 minutes)**

1. "Who are the individuals affected by this AI system? Employees? Customers? Job applicants? Members of the public?"
2. "How many individuals are affected? Is this a small group or a large population?"
3. "Are any of the affected individuals in a vulnerable position — job applicants, people seeking services they depend on, individuals with limited ability to contest decisions?"
4. "Do affected individuals know that AI is involved in decisions or processes that affect them?"

**Section B: Potential Harms (25 minutes)**

5. "What is the worst realistic outcome if this AI system produces an incorrect or biased output? Walk me through a specific scenario."
6. "Could this system produce outputs that discriminate against individuals based on protected characteristics — age, gender, ethnicity, disability, religion?"
7. "Could this system produce outputs that violate individuals' privacy — exposing personal information, making inferences about sensitive attributes?"
8. "Could this system produce outputs that affect individuals' economic situation — employment, credit, pricing, access to services?"
9. "Could this system produce outputs that affect individuals' physical safety or wellbeing?"
10. "Are there groups of individuals who are more likely to be harmed by this system than others?"

**Section C: Existing Safeguards (15 minutes)**

11. "What human review exists before AI outputs affect individuals? Is a human required to approve AI recommendations before action is taken?"
12. "Can affected individuals contest or appeal decisions that were influenced by this AI system?"
13. "Are there any technical controls in place to detect or prevent biased outputs?"
14. "Has the vendor provided any documentation about bias testing, fairness metrics, or impact assessment for this system?"

**Section D: Mitigation Decisions (20 minutes)**

15. "Based on what we've discussed, what mitigations do you want to put in place to reduce the risk of harm to individuals?"
    - *Common mitigations: mandatory human review before action, disclosure to affected individuals, regular bias audits, opt-out mechanisms, appeal processes*
16. "Are there any uses of this system that you want to prohibit based on this assessment?"
17. "What residual risk remains after mitigations are applied? Is that level of residual risk acceptable to the organization?"

#### 5.4 Post-Session Actions

- [ ] Complete Impact Assessment document for each assessed system
- [ ] Confirm mitigation decisions with AI System Owner and Legal (if involved)
- [ ] Update Risk Assessment Register with impact assessment findings
- [ ] Flag any unacceptable residual risks to Client Sponsor
- [ ] Update Remediation Priority Matrix: mark A.5.3 and A.5.4 as in progress

---

### Step 6: Statement of Applicability Development (Week 4–6)

**Objective:** Facilitate completion of the Statement of Applicability — the document that records which of the 39 Annex A controls apply to the organization, with justification for each determination. Addresses Clause 6.1.6.

**Duration:** 2–3 working sessions (90 minutes each) + internal drafting time

**Attendees:** Lead Consultant, Client AIMS Owner (Client Sponsor for final review and approval)

**Template:** `template-soa.md`

> **Critical note:** The SoA is the first document a certification auditor will request. It must be complete, internally consistent, and linked to the risk treatment decisions made in Steps 4–5. Do not rush this step.

#### 6.1 Pre-Session Preparation

Before the first SoA working session, prepare the following:

- [ ] Completed Risk Assessment Register (Step 4 must be substantially complete)
- [ ] Completed Impact Assessments (Step 5 must be complete for all qualifying systems)
- [ ] AI System Inventory with Annex A control mapping from Phase 1
- [ ] Annex A control reference (`00-foundation/annex-a-reference.md`) — open during the session
- [ ] Draft SoA with all 39 controls pre-populated with applicability determinations based on the AI-user context (use the applicability column from the Annex A reference as the starting point)

#### 6.2 Applicability Determination Process

For each of the 39 Annex A controls, determine:

**Step 1: Is the control applicable to an AI-user organization?**
Use the applicability ratings in `00-foundation/annex-a-reference.md` as the baseline:
- FULLY APPLICABLE: 29 controls
- PARTIALLY APPLICABLE: 7 controls
- NOT APPLICABLE: 3 controls (A.6.2.2, A.6.2.3, A.10.4 — unless client embeds AI in services)

**Step 2: Does the client's specific context change the applicability?**
- If the client has no AI systems in a particular domain, some controls may be partially applicable rather than fully applicable
- If the client embeds AI outputs in services delivered to customers, A.10.4 reclassifies from NOT APPLICABLE to FULLY APPLICABLE
- If the client uses any fine-tuning or custom model capabilities, A.6.2.2 and A.6.2.3 may reclassify to PARTIALLY APPLICABLE

**Step 3: Is the control currently implemented?**
- Implemented: Evidence exists that the control is in place and operating
- Partially implemented: Some elements are in place; gaps remain
- Not implemented: Control is applicable but not yet in place (remediation required)

**Step 4: Link to risk treatment decisions**
- For each applicable control, note which risks from the Risk Assessment Register it addresses
- This linkage demonstrates that the SoA reflects actual risk treatment decisions, not a generic checklist

#### 6.3 Walking Through All 39 Controls

Use the following domain-by-domain guide during SoA working sessions. For each control, confirm the applicability determination and draft the justification.

**A.2 — Policies for AI (2 controls)**

| Control | Applicability | Justification Guidance |
|---|---|---|
| A.2.2 AI Policy | FULLY APPLICABLE | "The organization has adopted a formal AI Policy [reference document name and approval date] establishing its approach to responsible AI use." |
| A.2.3 Responsible AI Topics in AI Policy | FULLY APPLICABLE | "The AI Policy addresses all six responsible AI topics required by A.2.3: fairness, transparency, accountability, human oversight, privacy, and safety." |

**A.3 — Internal Organization (3 controls)**

| Control | Applicability | Justification Guidance |
|---|---|---|
| A.3.2 Roles and Responsibilities | FULLY APPLICABLE | "Roles and responsibilities for AI governance are defined in the AI Policy and the AIMS Roles and Responsibilities document [reference]." |
| A.3.3 Reporting of AI Concerns | FULLY APPLICABLE | "A reporting mechanism for AI concerns is established through [describe mechanism — e.g., AIMS Owner contact, incident reporting form]." |
| A.3.4 Impact of Organizational Changes | FULLY APPLICABLE | "The organization's change management process includes assessment of AI implications for significant organizational changes." |

**A.4 — Resources for AI Systems (5 controls)**

| Control | Applicability | Justification Guidance |
|---|---|---|
| A.4.2 Resources | FULLY APPLICABLE | "Resources for AI activities are identified and allocated through the annual planning process." |
| A.4.3 Competencies | FULLY APPLICABLE | "Competency requirements for AI-related roles are defined; training records are maintained [reference template-training-competence-records.md]." |
| A.4.4 Awareness | FULLY APPLICABLE | "All employees have completed AI awareness training [reference training records]. The AI Policy and AUP have been communicated to all staff." |
| A.4.5 Consultation | FULLY APPLICABLE | "Stakeholder consultation processes are documented in the Stakeholder Register [reference]." |
| A.4.6 Communication | FULLY APPLICABLE | "Communication about AI systems to interested parties is addressed through [describe mechanism]." |

**A.5 — Assessing Impacts (3 controls)**

| Control | Applicability | Justification Guidance |
|---|---|---|
| A.5.2 Risk Assessment | FULLY APPLICABLE | "Risk assessments have been conducted for all in-scope AI systems [reference Risk Assessment Register]. Reassessment is scheduled [frequency]." |
| A.5.3 Impact Assessment | FULLY APPLICABLE | "Impact assessments have been conducted for all AI systems meeting the impact assessment threshold [reference Impact Assessment documents]." |
| A.5.4 Impact Documentation | FULLY APPLICABLE | "Impact assessment results are documented and maintained as controlled documents [reference]." |

**A.6 — AI System Life Cycle (10 controls)**

| Control | Applicability | Justification Guidance |
|---|---|---|
| A.6.2.2 Design and Development | NOT APPLICABLE | "The organization does not design or develop AI systems. All AI systems in scope are third-party products. Responsibility for design and development lies with the AI provider." |
| A.6.2.3 Training and Testing | NOT APPLICABLE | "The organization does not train or test AI models. All AI systems in scope use pre-trained models provided by third-party vendors." |
| A.6.2.4 Verification and Validation | PARTIALLY APPLICABLE | "The organization validates that third-party AI tools meet organizational requirements before adoption. Formal V&V of the underlying model is the vendor's responsibility." |
| A.6.2.5 Deployment | FULLY APPLICABLE | "Deployment of third-party AI tools follows the organization's AI tool adoption process [reference]." |
| A.6.2.6 Operation and Monitoring | FULLY APPLICABLE | "AI system performance is monitored through [describe monitoring approach]. Issues are reported through the NCAR process." |
| A.6.2.7 Retirement | PARTIALLY APPLICABLE | "The organization manages the retirement of third-party AI tools, including data migration, access removal, and contract termination." |
| A.6.2.8 Integration | FULLY APPLICABLE | "Integration of AI tools into organizational processes is managed through the AI tool adoption process [reference]." |
| A.6.2.9 Documentation | FULLY APPLICABLE | "Documentation for each in-scope AI system is maintained in the AI System Inventory [reference]." |
| A.6.2.10 Defined Use and Misuse | FULLY APPLICABLE | "Permitted and prohibited uses of AI systems are defined in the Acceptable Use Policy [reference]." |
| A.6.2.11 Third-Party Components | FULLY APPLICABLE | "Third-party AI systems are managed through the supplier assessment process [reference Supplier Assessment documents]." |

**A.7 — Data for AI Systems (5 controls)**

| Control | Applicability | Justification Guidance |
|---|---|---|
| A.7.2 Data for Development | PARTIALLY APPLICABLE | "Applicable only to the extent the organization provides data for customization of third-party AI tools. [Describe scope or state 'Not currently applicable — no fine-tuning in use.']" |
| A.7.3 Data Quality | FULLY APPLICABLE | "Data quality requirements for AI system inputs are addressed in the Acceptable Use Policy and AI system documentation." |
| A.7.4 Data Preparation | PARTIALLY APPLICABLE | "Applicable to the preparation of organizational data for input to AI tools. Data preparation guidelines are included in the Acceptable Use Policy." |
| A.7.5 Data Acquisition | PARTIALLY APPLICABLE | "Applicable to data the organization collects and feeds into AI systems. Data acquisition practices are governed by the organization's data protection policy [reference]." |
| A.7.6 Data Provenance | PARTIALLY APPLICABLE | "The organization tracks the provenance of organizational data used as AI inputs. Training data provenance is the vendor's responsibility." |

**A.8 — Information for Interested Parties (4 controls)**

| Control | Applicability | Justification Guidance |
|---|---|---|
| A.8.2 Informing About AI Interaction | FULLY APPLICABLE | "Disclosure mechanisms for AI interaction are defined in [reference — e.g., customer-facing disclosure statement, employee communication]." |
| A.8.3 Informing About AI Outcomes | FULLY APPLICABLE | "Processes for communicating AI-influenced decisions to affected individuals are defined in [reference]." |
| A.8.4 Access to Interaction Information | FULLY APPLICABLE | "Records of AI system interactions are maintained and accessible per [reference — e.g., data subject access request process]." |
| A.8.5 Enabling Human Actions | FULLY APPLICABLE | "Human oversight processes ensure staff have sufficient context to exercise judgment on AI outputs [reference — e.g., human oversight section of AUP or operational procedures]." |

**A.9 — Use of AI Systems (4 controls)**

| Control | Applicability | Justification Guidance |
|---|---|---|
| A.9.2 Objectives for Responsible Use | FULLY APPLICABLE | "Responsible AI use objectives are defined in the AI Policy [reference] and reviewed annually." |
| A.9.3 Intended Use | FULLY APPLICABLE | "Intended use parameters for each AI system are documented in the AI System Inventory and enforced through the Acceptable Use Policy." |
| A.9.4 Responsible Use Processes | FULLY APPLICABLE | "Operational processes for responsible AI use are defined in [reference — e.g., operational procedures, AUP, human oversight guidelines]." |
| A.9.5 Human Oversight | FULLY APPLICABLE | "Human oversight requirements are defined per AI system in the Risk Assessment Register and operationalized through [reference — e.g., review workflows, approval requirements]." |

**A.10 — Third-Party and Customer Relationships (3 controls)**

| Control | Applicability | Justification Guidance |
|---|---|---|
| A.10.2 Suppliers | FULLY APPLICABLE | "AI system suppliers are managed through the supplier assessment process [reference Supplier Assessment documents]. Supplier assessments are conducted [frequency]." |
| A.10.3 Shared ML Models | PARTIALLY APPLICABLE | "Applicable to the extent the organization uses shared or pre-trained models accessed through vendor APIs. Assessment of model suitability is included in the supplier assessment process." |
| A.10.4 Provision to Third Parties | NOT APPLICABLE | "The organization does not provide AI systems or AI-powered services to third parties. *[If applicable: Reclassify to FULLY APPLICABLE and document provision controls.]*" |

#### 6.4 SoA Quality Checklist

Before finalizing the SoA, verify:

- [ ] All 39 Annex A controls are addressed — no controls are missing
- [ ] Every NOT APPLICABLE determination has a written justification
- [ ] Every PARTIALLY APPLICABLE determination specifies which portions apply
- [ ] All FULLY APPLICABLE controls have an implementation status (Implemented / Partial / Not Implemented)
- [ ] Controls marked "Not Implemented" appear in the Risk Treatment Plan or Remediation Priority Matrix
- [ ] The SoA is linked to the Risk Assessment Register — risk treatment decisions are reflected in applicability determinations
- [ ] A.6.2.2, A.6.2.3, and A.10.4 are marked NOT APPLICABLE with correct justifications (unless client context requires reclassification)
- [ ] Client Sponsor has reviewed and approved the SoA

#### 6.5 Post-Session Actions

- [ ] Complete SoA draft after each working session
- [ ] Send draft to Client AIMS Owner for review between sessions
- [ ] Finalize SoA after all 39 controls are addressed
- [ ] Obtain Client Sponsor approval signature
- [ ] Update Remediation Priority Matrix: mark Clause 6.1.6 as complete upon approval

---

### Step 7: Risk Treatment Plan Development (Week 5–7)

**Objective:** Develop the Risk Treatment Plan — the document that maps identified risks to treatment decisions and selected controls. Addresses Clause 6.1.3.

**Duration:** 1–2 working sessions (60–90 minutes each) + drafting time

**Attendees:** Lead Consultant, Client AIMS Owner, Client Sponsor (for residual risk acceptance)

**Template:** `template-risk-treatment-plan.md`

#### 7.1 Risk Treatment Options

For each risk identified in the Risk Assessment Register, the organization must select a treatment option:

| Treatment Option | Definition | When to Use |
|---|---|---|
| **Mitigate** | Implement controls to reduce likelihood or impact | Most common option; appropriate for Medium and High risks where controls are feasible |
| **Accept** | Acknowledge the risk and decide not to take further action | Appropriate for Low risks or where cost of mitigation exceeds benefit |
| **Transfer** | Shift the risk to a third party (e.g., through contractual terms, insurance) | Appropriate for vendor-related risks that can be addressed through contract terms |
| **Avoid** | Eliminate the risk by discontinuing the activity | Appropriate for High risks where no acceptable mitigation exists; may mean discontinuing use of an AI system |

#### 7.2 Mapping Risks to Controls

For each risk requiring mitigation, identify the Annex A controls that address it. Use the following mapping as a guide:

| Risk Type | Primary Controls |
|---|---|
| Data leakage / privacy | A.6.2.10 (AUP), A.7.3 (data quality), A.10.2 (supplier contracts) |
| Bias / unfair outcomes | A.5.3 (impact assessment), A.9.5 (human oversight), A.8.3 (informing about outcomes) |
| Over-reliance / automation bias | A.9.5 (human oversight), A.8.5 (enabling human action), A.9.4 (responsible use processes) |
| Vendor lock-in | A.10.2 (supplier management), A.6.2.7 (retirement planning) |
| Regulatory non-compliance | A.5.2 (risk assessment), A.5.3 (impact assessment), A.10.2 (supplier contracts) |
| Inaccurate outputs | A.6.2.6 (monitoring), A.9.5 (human oversight), A.7.3 (data quality) |
| Unauthorized use | A.6.2.10 (AUP), A.4.4 (awareness training), A.3.3 (reporting mechanism) |
| Vendor failure | A.10.2 (supplier management), A.6.2.7 (retirement planning) |

#### 7.3 Residual Risk Acceptance

After treatment decisions are made, calculate the residual risk score (post-treatment likelihood × post-treatment impact). The Client Sponsor must formally accept all residual risks.

**Residual risk acceptance process:**
1. Present residual risk summary to Client Sponsor
2. For each High residual risk (score 15–25 after treatment), explain why the risk cannot be reduced further
3. Obtain written acceptance from Client Sponsor (signature on Risk Treatment Plan or separate acceptance record)
4. Document the acceptance date and the person who accepted

> **Note:** If the Client Sponsor is unwilling to accept a residual risk, additional controls must be identified or the AI system use must be restricted/discontinued. Do not proceed with a residual risk that has not been formally accepted.

#### 7.4 Post-Session Actions

- [ ] Complete Risk Treatment Plan with all risks, treatment decisions, and control mappings
- [ ] Obtain residual risk acceptance from Client Sponsor
- [ ] Confirm that all controls selected in the Risk Treatment Plan are reflected in the SoA
- [ ] Update Remediation Priority Matrix

---

### Step 8: Third-Party Supplier Assessment (Week 5–8)

**Objective:** Facilitate supplier assessments for all in-scope AI vendors. Produce completed Supplier Assessment documents that evaluate vendor AI governance, data handling, and contractual protections. Addresses controls A.10.2 and A.6.2.11.

**Duration:** 60–90 minutes per vendor assessment session + document review time

**Attendees:** Lead Consultant, Client AIMS Owner, Client IT Lead, Legal (for contract gap review)

**Template:** `template-supplier-assessment.md`

#### 8.1 Prioritization

Not all vendors require the same depth of assessment. Prioritize based on:

| Priority | Criteria | Assessment Depth |
|---|---|---|
| **High** | Vendor processes sensitive data (PII, financial, health); AI system is High Risk; vendor has significant operational dependency | Full assessment; contract review; vendor questionnaire |
| **Medium** | Vendor processes internal data; AI system is Medium Risk | Standard assessment; contract review |
| **Low** | Vendor processes only public or non-sensitive data; AI system is Low Risk | Abbreviated assessment; documentation review only |

#### 8.2 Supplier Assessment Facilitation

For each vendor, gather the following information. Some will come from vendor documentation; some will require direct vendor inquiry.

**Section A: Vendor AI Governance**

1. Does the vendor have a published AI policy or responsible AI framework? (Request URL or document)
2. Does the vendor conduct bias testing or fairness assessments on their AI models?
3. Does the vendor have an AI ethics board or governance committee?
4. Has the vendor published any transparency reports or model cards for the AI systems you use?
5. Does the vendor hold any AI-related certifications (ISO 42001, NIST AI RMF alignment, EU AI Act compliance documentation)?

**Section B: Data Handling**

6. How does the vendor use customer data? Is it used for model training? Can the organization opt out?
7. Where is data processed and stored? Does it leave the organization's jurisdiction?
8. What data retention and deletion policies does the vendor apply to customer data?
9. Does the vendor have a data processing agreement (DPA) in place? Does it cover AI-specific data handling?
10. Has the vendor experienced any data breaches in the past 24 months? How were they handled?

**Section C: Contractual Review**

Review the vendor contract against the following requirements. Flag gaps for Legal review.

| Requirement | Present in Contract? | Gap Action |
|---|---|---|
| Data processing agreement (DPA) | Yes / No / Partial | If no: Request DPA from vendor |
| Data use restrictions (no training on customer data without consent) | Yes / No / Partial | If no: Request contract amendment or addendum |
| Data deletion on contract termination | Yes / No / Partial | If no: Request contract amendment |
| Breach notification obligations | Yes / No / Partial | If no: Request contract amendment |
| Audit rights (right to audit vendor AI practices) | Yes / No / Partial | If no: Request contract amendment or accept risk |
| SLA for AI system availability | Yes / No / Partial | If no: Document as accepted risk |
| Liability for AI-related harms | Yes / No / Partial | If no: Flag for Legal review |

#### 8.3 Handling "Limited Transparency" Vendors

Many major AI vendors (OpenAI, Microsoft, Google, Salesforce) provide limited transparency into their AI model internals. This is a common challenge for SMB clients. Use the following approach:

```
Vendor provides limited transparency into AI model internals?
│
├── YES
│   ├── Does the vendor publish a responsible AI framework or AI principles?
│   │   ├── YES → Document the framework reference in the Supplier Assessment
│   │   │   Note: Published principles are not the same as verified practices,
│   │   │   but they demonstrate vendor commitment and provide audit evidence
│   │   └── NO → Document the gap; assess whether the risk is acceptable
│   │
│   ├── Does the vendor have a DPA that covers AI-specific data handling?
│   │   ├── YES → Document the DPA reference; review key provisions
│   │   └── NO → This is a contractual gap; escalate to Legal
│   │
│   └── Is the vendor subject to external regulatory oversight (EU AI Act, etc.)?
│       ├── YES → Note regulatory compliance as a mitigating factor
│       └── NO → Document as a risk; consider whether usage should be restricted
│
└── NO — Vendor provides good transparency
    → Proceed with standard assessment
    → Document evidence of transparency (model cards, audit reports, certifications)
```

**Practical guidance for major vendors:**
- **Microsoft (Copilot, Azure AI):** Reference Microsoft's Responsible AI Standard and Azure AI transparency documentation. Review Microsoft DPA for data handling terms.
- **OpenAI (ChatGPT, API):** Review OpenAI's usage policies and enterprise data handling terms. Enterprise accounts have stronger data protection than consumer accounts.
- **Google (Gemini, Workspace AI):** Reference Google's AI Principles and Workspace data processing terms.
- **Salesforce (Einstein):** Reference Salesforce's Trusted AI Principles and review Einstein data handling documentation.

#### 8.4 Contractual Gap Identification

After reviewing all vendor contracts, compile a Contractual Gap Summary for the Client AIMS Owner and Legal. For each gap:

1. Identify the specific contractual provision that is missing or insufficient
2. Assess the risk created by the gap (High / Medium / Low)
3. Recommend the remediation action (request amendment, accept risk, restrict usage)
4. Assign an owner and target date for resolution

> **Note:** Not all contractual gaps can be closed. Major vendors often have non-negotiable standard terms. In these cases, document the gap, the risk, and the organization's decision to accept the risk. This documentation is itself an AIMS control — it demonstrates that the risk was identified and consciously accepted.

#### 8.5 Post-Session Actions

- [ ] Complete Supplier Assessment document for each vendor
- [ ] Compile Contractual Gap Summary
- [ ] Send gap summary to Legal for review
- [ ] Track contract amendment requests and responses
- [ ] Update Remediation Priority Matrix: mark A.10.2 and A.6.2.11 as in progress

---

### Step 9: Supporting Documentation (Week 6–10)

**Objective:** Complete all remaining AIMS documentation: Implementation Roadmap, Training & Competence Records, and NCAR Log. Establish document control for all AIMS documentation.

**Duration:** Varies by document; most can be completed with 1 working session + drafting

**Attendees:** Lead Consultant, Client AIMS Owner (HR for training records)

#### 9.1 Implementation Roadmap

**Template:** `template-implementation-roadmap.md`

The Implementation Roadmap is a forward-looking document that shows how the client will operate and maintain their AIMS after certification. It is not a Phase 3 project plan — it is a post-certification operational plan.

The roadmap must address:

| Activity | Frequency | Owner |
|---|---|---|
| AI Policy review | Annual | AIMS Owner |
| Acceptable Use Policy review | Annual | AIMS Owner + HR |
| Risk Assessment review (all AI systems) | Annual + upon significant change | AIMS Owner |
| Impact Assessment review | Annual + upon significant change | AIMS Owner |
| SoA review | Annual | AIMS Owner |
| Supplier assessment review | Annual per vendor | AIMS Owner + IT Lead |
| Internal audit | Annual | Internal Auditor (or external) |
| Management review | Annual (minimum) | Client Sponsor |
| AI awareness training | Annual for all staff; upon onboarding for new staff | HR + AIMS Owner |
| NCAR log review | Quarterly | AIMS Owner |
| AI System Inventory update | Upon adoption or retirement of any AI system | AIMS Owner + IT Lead |

**Guidance for the client:** The Implementation Roadmap is the document that prevents AIMS decay after certification. Clients who don't have a roadmap tend to let their AIMS documentation go stale, which creates nonconformities at surveillance audits. Help the client build this into their existing operational calendar.

#### 9.2 Training & Competence Records

**Template:** `template-training-competence-records.md`

ISO 42001 requires evidence that personnel have the competencies needed for their AI-related roles (A.4.3) and that all staff are aware of the AI Policy, relevant risks, and their responsibilities (A.4.4).

**Minimum training requirements for SMB AI users:**

| Audience | Training Content | Evidence Required |
|---|---|---|
| All employees | AI Policy overview, Acceptable Use Policy, how to report AI concerns, data handling rules for AI tools | Attendance record or acknowledgment record |
| AIMS Owner | AIMS management, internal audit basics, risk assessment methodology, SoA maintenance | Training completion record; may be satisfied by this engagement |
| AI System Owners | Risk assessment for their specific systems, monitoring requirements, incident reporting | Working session attendance records from Phase 3 |
| IT Lead | Supplier assessment process, AI system documentation requirements, monitoring tools | Working session attendance records from Phase 3 |
| HR (if AI used in people decisions) | Impact assessment requirements, employment law implications of AI in HR | Impact assessment working session attendance |

**Practical guidance:** For most SMB clients, the Phase 3 working sessions themselves constitute significant training for the AIMS Owner, AI System Owners, and IT Lead. Document attendance at all Phase 3 working sessions as training records. Supplement with a brief all-staff awareness session (30–45 minutes) covering the AI Policy and AUP.

**All-staff awareness session outline:**
1. What is our AI Management System and why does it matter? (5 minutes)
2. Our AI Policy — what we've committed to (10 minutes)
3. Our Acceptable Use Policy — what you can and can't do (15 minutes)
4. How to report AI concerns (5 minutes)
5. Q&A (10 minutes)

#### 9.3 NCAR Log Setup

**Template:** `template-ncar-log.md`

The NCAR (Nonconformity and Corrective Action Report) Log is the mechanism for tracking nonconformities and corrective actions. It is required by Clause 10.1 and is a common audit focus point.

**Setting up the NCAR Log:**

1. Initialize the log with the template structure
2. Populate with any nonconformities identified during Phase 3 (gaps that were identified but not yet closed)
3. Assign an owner and target date for each open item
4. Establish the review cadence (quarterly review by AIMS Owner is standard for SMBs)

**What goes in the NCAR Log:**
- Nonconformities identified during internal audit
- Nonconformities identified during Phase 3 remediation that were not closed before Phase 4
- AI incidents or near-misses that reveal a gap in AIMS controls
- Corrective actions taken in response to nonconformities

**What does NOT go in the NCAR Log:**
- Routine improvement suggestions (these go in the management review outputs)
- Risk treatment actions (these go in the Risk Treatment Plan)
- Supplier contract gaps (these go in the Contractual Gap Summary)

#### 9.4 Document Control for AIMS Documentation

All AIMS documents must be controlled. For SMB clients, a simple document control approach is sufficient. Provide the following guidance to the AIMS Owner:

**Minimum document control requirements:**

| Requirement | Simple Implementation |
|---|---|
| Document identification | Each document has a unique name and version number (e.g., "AI-POL-001 v1.0") |
| Version control | Date and version number on every document; previous versions archived |
| Approval records | Signed approval page or email approval record for each document |
| Access control | Documents stored in a location accessible to relevant staff; restricted where appropriate |
| Review schedule | Review date noted on each document; AIMS Owner tracks review schedule |
| Distribution | Record of who has received each document (for policies communicated to staff) |

**Recommended storage:** A shared drive folder structure is sufficient for most SMB clients. A dedicated AIMS folder with subfolders for each document category (Policies, Procedures, Records, Templates) is adequate. A GRC platform is not required.

---

### Step 10: Internal Audit Preparation (Week 10–14)

**Objective:** Prepare the client for their first internal audit. Ensure the client understands what internal audit means for an AIMS, who conducts it, and what evidence is required. Handoff to Phase 4.

**Duration:** 1 briefing session (60 minutes) + readiness walkthrough (90–120 minutes)

**Attendees:** Lead Consultant, Client AIMS Owner, Client Sponsor (for briefing session)

#### 10.1 Internal Audit Briefing

Conduct a 60-minute briefing session with the Client Sponsor and AIMS Owner. Cover:

**What is an internal audit?**
"An internal audit is a systematic review of your AIMS to verify that it is operating as documented and meeting ISO 42001 requirements. It is conducted by or on behalf of your organization — not by the certification body. Think of it as a dress rehearsal for the certification audit."

**Who conducts the internal audit?**
"The internal auditor must be independent of the activities being audited. For most SMB clients, this means either:
- A staff member from a different function (e.g., the Finance Manager auditing the IT function's AI practices)
- An external party (e.g., a consultant or a peer organization)
- The Lead Consultant can conduct the first internal audit as part of Phase 4, if the client does not have an internal auditor"

**What does the internal auditor look at?**
"The internal auditor reviews your AIMS documentation and interviews staff to verify that:
- Documented policies and procedures are being followed in practice
- Required records are being maintained
- Nonconformities are being identified and addressed
- The AIMS is achieving its objectives"

**What happens if nonconformities are found?**
"Nonconformities found during internal audit are not failures — they are the system working as intended. The internal audit is designed to find gaps before the certification auditor does. Each nonconformity is logged in the NCAR Log and addressed through a corrective action."

#### 10.2 Readiness Walkthrough

Conduct a 90–120 minute readiness walkthrough with the AIMS Owner. This is an informal pre-audit review — not a formal audit. The goal is to identify any remaining gaps before Phase 4.

**Walkthrough checklist:**

**Documentation completeness:**
- [ ] AI Policy — approved, dated, communicated to all staff
- [ ] Acceptable Use Policy — approved, dated, communicated to all staff, acknowledgments recorded
- [ ] Risk Assessment Register — complete for all in-scope AI systems, reviewed and approved
- [ ] Impact Assessments — complete for all qualifying AI systems
- [ ] Statement of Applicability — all 39 controls addressed, approved by Client Sponsor
- [ ] Risk Treatment Plan — all risks addressed, residual risks accepted
- [ ] Supplier Assessments — complete for all in-scope vendors
- [ ] Implementation Roadmap — complete and realistic
- [ ] Training & Competence Records — all required training documented
- [ ] NCAR Log — initialized, any open items assigned

**Evidence availability:**
- [ ] Can the AIMS Owner locate any document within 2 minutes? (Auditors will ask for specific documents)
- [ ] Are approval records (signatures, email approvals) stored with the documents they approve?
- [ ] Are training attendance records stored and accessible?
- [ ] Are supplier assessment records stored with vendor contracts?

**Operational evidence:**
- [ ] Is there evidence that the AI Policy has been communicated (e.g., all-staff email, meeting record)?
- [ ] Is there evidence that the AUP has been communicated and acknowledged?
- [ ] Is there evidence that risk assessments were conducted (meeting notes, completed templates)?
- [ ] Is there evidence that supplier assessments were conducted?

**Common audit questions — prepare the AIMS Owner:**
- "Show me your AI Policy. When was it last reviewed? Who approved it?"
- "Walk me through how you assess risks for a new AI system."
- "What happens if an employee wants to use a new AI tool?"
- "Show me the impact assessment for [specific AI system]."
- "What would you do if an AI system produced a biased or harmful output?"
- "Show me your Statement of Applicability. Why is A.6.2.2 marked Not Applicable?"

#### 10.3 Handoff to Phase 4

Prepare the Phase 4 handoff package:

- [ ] All Phase 3 deliverables finalized and stored in the engagement folder
- [ ] Remediation Priority Matrix updated — all items marked Complete or documented as open
- [ ] Any open items documented with owner, target date, and risk assessment
- [ ] Phase 4 scope confirmed: internal audit coverage, audit criteria, audit schedule
- [ ] Internal auditor identified and briefed
- [ ] Phase 4 kickoff meeting scheduled

---

### Step 11: Phase 3 Completion Review (Week 14–16)

**Objective:** Perform a final quality check on all Phase 3 deliverables. Verify that all critical gaps identified in the Gap Analysis Report have been closed. Prepare the Phase 3 Completion Package for handoff to Phase 4.

**Duration:** Internal review (2–3 hours) + client review session (60 minutes)

**Attendees:** Lead Consultant (internal review), then Client Sponsor and AIMS Owner (client review session)

#### 11.1 Deliverable Quality Checklist

**AI Policy:**
- [ ] Addresses all six A.2.3 responsible AI topics (fairness, transparency, accountability, human oversight, privacy, safety)
- [ ] Includes measurable AI objectives
- [ ] Approved by Client Sponsor with signature and date
- [ ] Communicated to all employees; acknowledgment records exist
- [ ] Version controlled and stored as a controlled document

**Acceptable Use Policy:**
- [ ] Covers all required sections (permitted uses, prohibited uses, data handling, reporting, consequences)
- [ ] Specific enough that an employee can determine whether a specific action is permitted
- [ ] Approved and communicated; acknowledgment records exist
- [ ] Cross-referenced in the SoA under A.6.2.10

**Risk Assessment Register:**
- [ ] All in-scope AI systems assessed
- [ ] All risks scored with likelihood and impact
- [ ] Risk levels assigned (High / Medium / Low)
- [ ] No AI system has an unaddressed High risk without a documented treatment decision

**Impact Assessments:**
- [ ] All AI systems meeting the impact assessment threshold have a completed assessment
- [ ] All assessments identify affected individuals, potential harms, and mitigations
- [ ] Residual risks documented and accepted
- [ ] HR and/or Legal reviewed assessments for people-affecting AI systems

**Statement of Applicability:**
- [ ] All 39 Annex A controls addressed — no gaps
- [ ] A.6.2.2, A.6.2.3, and A.10.4 marked NOT APPLICABLE with correct justifications
- [ ] All FULLY APPLICABLE controls have an implementation status
- [ ] Controls marked "Not Implemented" have a remediation plan
- [ ] Linked to Risk Assessment Register and Risk Treatment Plan
- [ ] Approved by Client Sponsor

**Risk Treatment Plan:**
- [ ] All risks from the Risk Assessment Register have a treatment decision
- [ ] All mitigation controls are mapped to Annex A controls
- [ ] Residual risks formally accepted by Client Sponsor
- [ ] Consistent with the SoA

**Supplier Assessments:**
- [ ] All in-scope vendors assessed
- [ ] Contractual gaps identified and addressed (or accepted with documented rationale)
- [ ] High-priority vendors assessed at appropriate depth

**Supporting Documentation:**
- [ ] Implementation Roadmap complete and realistic
- [ ] Training & Competence Records complete for all required audiences
- [ ] NCAR Log initialized with any open items assigned

#### 11.2 SoA Completeness Verification

The SoA is the most critical document for certification. Perform a final verification:

1. Count the controls in the SoA: must be exactly 39
2. Verify that every control has an applicability determination (Fully / Partially / Not Applicable)
3. Verify that every NOT APPLICABLE control has a written justification
4. Verify that every FULLY APPLICABLE control has an implementation status
5. Verify that the SoA version number and approval date are current
6. Cross-check: every control marked "Not Implemented" in the SoA should appear in the NCAR Log or Remediation Priority Matrix

#### 11.3 Critical Gap Closure Verification

Return to the Gap Analysis Report. For each Critical gap identified in Phase 2:

- [ ] Confirm the gap has been closed (remediation action completed)
- [ ] Confirm evidence exists that the gap is closed (completed document, training record, etc.)
- [ ] If any Critical gap remains open, document the reason and the plan to close it before Phase 4

> **Note:** A Critical gap that remains open at the end of Phase 3 is a significant risk to certification. Escalate to Client Sponsor immediately. Do not proceed to Phase 4 with unresolved Critical gaps unless the Client Sponsor has explicitly accepted the risk and a closure plan is in place.

#### 11.4 Phase 4 Handoff Package

Compile the Phase 4 Handoff Package. This package is the complete set of AIMS documentation that the internal auditor will review in Phase 4.

**Package contents:**
1. Phase 3 Completion Summary (1-page summary of what was built, what remains open, and Phase 4 readiness assessment)
2. All Phase 3 deliverables (listed in Section 5 of this procedure)
3. Updated Remediation Priority Matrix (final status of all items)
4. Open items log (any items not completed in Phase 3, with owner and target date)
5. Phase 4 internal audit scope and schedule

**Delivery:** Deliver the Phase 4 Handoff Package to the Client Sponsor and AIMS Owner in a structured review session. Walk through the completion summary. Confirm Phase 4 kickoff date.

---

## 8. Referenced Documents

| Document | Location | Usage |
|---|---|---|
| Controlled Vocabulary | `00-foundation/glossary.md` | Term definitions used throughout this procedure |
| Annex A Control Reference | `00-foundation/annex-a-reference.md` | Control IDs, applicability ratings, and justification guidance referenced in Step 6 |
| Gap Analysis Report Template | `02-gap-analysis/template-gap-analysis-report.md` | Primary input to Phase 3; drives remediation priorities |
| Gap Analysis Workbook | `02-gap-analysis/template-gap-analysis-workbook.md` | Row-level findings used to build the Remediation Priority Matrix |
| AI Policy Template | `03-remediation/template-ai-policy.md` | Completed in Step 2 |
| Acceptable Use Policy Template | `03-remediation/template-acceptable-use-policy.md` | Completed in Step 3 |
| Risk Assessment Register Template | `03-remediation/template-risk-assessment-register.md` | Completed in Step 4 |
| Impact Assessment Template | `03-remediation/template-impact-assessment.md` | Completed in Step 5 |
| Statement of Applicability Template | `03-remediation/template-soa.md` | Completed in Step 6 |
| Risk Treatment Plan Template | `03-remediation/template-risk-treatment-plan.md` | Completed in Step 7 |
| Supplier Assessment Template | `03-remediation/template-supplier-assessment.md` | Completed in Step 8 |
| Implementation Roadmap Template | `03-remediation/template-implementation-roadmap.md` | Completed in Step 9 |
| Training & Competence Records Template | `03-remediation/template-training-competence-records.md` | Completed in Step 9 |
| NCAR Log Template | `03-remediation/template-ncar-log.md` | Initialized in Step 9 |
| Stakeholder Register Template | `01-discovery/template-stakeholder-register.md` | Input to Phase 3; referenced in SoA and policy development |
| Traceability Matrix | `00-foundation/traceability-matrix.md` | Maps Phase 3 outputs to ISO 42001 clause requirements |

---

## 9. Escalation Triggers

Monitor for the following conditions throughout Phase 3. When triggered, take the specified action.

| ID | Trigger Condition | Action |
|---|---|---|
| **E-1** | Client leadership disengages mid-remediation — Client Sponsor becomes unavailable, stops responding, or delegates all decisions to a junior staff member without authority | Stop billable work immediately. Send a written notice to the Client Sponsor documenting the engagement pause and its cause. Do not continue producing deliverables that require executive input or approval. Request a re-engagement meeting within 5 business days. If no response within 10 business days, escalate to your firm's engagement manager. Document all communications. |
| **E-2** | Critical gap cannot be closed within engagement scope — A gap identified in the Gap Analysis Report as Critical cannot be remediated because it requires organizational change, budget, or vendor action outside the consultant's control | Document the gap, the reason it cannot be closed, and the risk it creates for certification. Present options to the Client Sponsor: (a) extend the engagement scope to address the gap, (b) accept the risk and proceed to Phase 4 with the gap documented, or (c) delay Phase 4 until the gap is closed. Do not proceed to Phase 4 without a documented decision from the Client Sponsor. |
| **E-3** | Client wants to skip impact assessments — Client Sponsor or AIMS Owner argues that impact assessments are unnecessary, too time-consuming, or not applicable to their AI systems | Do not agree to skip impact assessments for AI systems that meet the threshold (High Risk or affecting individuals). Explain that A.5.3 is a FULLY APPLICABLE control and that missing impact assessments are a common cause of certification failure. If the client insists, document the disagreement in writing, note the risk to certification, and obtain written confirmation from the Client Sponsor that they are choosing to proceed without impact assessments. Flag this as a Major gap in the Phase 3 Completion Summary. |
| **E-4** | Scope expansion discovered during Phase 3 — New AI systems are discovered that were not in the Phase 1 inventory, or the client's AI use has expanded significantly since Phase 1 | Assess the impact on Phase 3 timeline and deliverables. If the new systems are material (High Risk or significantly affect the SoA), update the AI System Inventory, conduct risk and impact assessments for the new systems, and update the SoA. Notify the Client Sponsor of the scope expansion and its timeline implications. If the expansion is significant, issue a change order before proceeding. |
| **E-5** | Client's AI vendor refuses to provide AI governance information — A key vendor declines to answer supplier assessment questions, provide a DPA, or share any information about their AI practices | Document the vendor's refusal in the Supplier Assessment. Assess the risk created by the lack of transparency. Present options to the Client Sponsor: (a) restrict or discontinue use of the vendor's AI features, (b) accept the risk with documented rationale, or (c) seek contractual protections through the vendor's standard terms. Note that a vendor's refusal to provide basic AI governance information is itself a risk indicator. Flag for Legal review. |
| **E-6** | Client's SoA is challenged by the certification body during pre-audit review — The certification body raises concerns about the SoA before the Stage 1 audit | Review the specific concerns raised. If the concerns relate to applicability determinations (e.g., the certification body believes a control marked NOT APPLICABLE should be PARTIALLY APPLICABLE), assess whether the determination is defensible. Prepare a written justification for each challenged determination. If the determination cannot be defended, update the SoA and implement the required control before Stage 1. |
| **E-7** | Client discovers a significant AI incident during Phase 3 — An AI system produces a harmful output, a data breach involving AI tools occurs, or an employee misuse incident is discovered | Activate the NCAR process immediately. Document the incident in the NCAR Log. Assess whether the incident reveals a gap in AIMS controls that must be addressed before Phase 4. Brief the Client Sponsor. If the incident involves personal data, assess whether data breach notification obligations apply (GDPR, CCPA, etc.) and flag for Legal. Use the incident as a real-world test of the AIMS controls being built — it demonstrates why the AIMS matters. |

---

## 10. Revision History

| Version | Date | Author | Changes |
|---|---|---|---|
| 1.0 | March 2026 | [Author] | Initial release |

---

*ISO 42001 Readiness Service Toolkit | 03-Remediation | Internal Use*
