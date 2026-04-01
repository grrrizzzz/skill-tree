# Internal Procedure: Engagement Management

> **Current as of:** March 2026 | ISO/IEC 42001:2023
>
> **Classification:** Internal Use Only. Do not share with clients.

---

## 1. Purpose

This procedure tells you how to run an ISO 42001 readiness engagement from first inquiry through close-out. It's written so a junior consultant can follow it without guessing. If something isn't covered here, escalate to the Lead Consultant before proceeding.

The procedure covers the full five-phase engagement (Discovery, Gap Analysis, Remediation, Pre-Audit, Certification Support). For engagements scoped to fewer phases, apply only the relevant sections.

---

## 2. Scope

This procedure applies to all ISO 42001 readiness engagements delivered by this firm. It covers:

- Pre-engagement activities (inquiry through signed SOW)
- Kickoff
- Phase execution (all five phases)
- Ongoing engagement management
- Close-out

It does not cover post-certification surveillance engagements. Those are handled under a separate procedure.

---

## 3. Roles

| Role | Description |
|---|---|
| **Lead Consultant** | Owns the engagement. Responsible for quality of all deliverables, client relationship, and escalation decisions. Signs off on all client-facing documents before delivery. |
| **Supporting Consultant** | Assists with research, documentation drafting, and workshop facilitation under Lead Consultant direction. Does not communicate directly with the client sponsor without Lead Consultant approval. |
| **Client Sponsor** | The client's senior decision-maker for the engagement. Signs off on phase deliverables and the SOW. Participates in management review. |
| **Client PM** | The client's day-to-day project contact. Coordinates internal scheduling, document access, and stakeholder availability. Receives weekly status updates. |

---

## 4. Pre-Engagement

### 4.1 Inquiry Handling

When a new inquiry arrives:

1. Log it in the inquiry tracker within 24 hours. Record: date received, source (referral, website, event, etc.), contact name, organization name, and initial description of need.
2. Respond to the inquiry within 1 business day. Acknowledge receipt and propose a discovery call within the next 5 business days.
3. Before the discovery call, do a 15-minute background check on the organization: size, industry, any public AI tool usage, existing certifications (ISO 27001, ISO 9001), and any regulatory context (EU AI Act exposure, sector-specific AI rules).

### 4.2 Discovery Call

The discovery call has two purposes: qualify the opportunity and gather enough information to write a credible proposal. Aim for 45–60 minutes.

**Before the call:**
- Review your background research
- Confirm who will be on the call (title and role)
- Have the qualification questions below ready

**Discovery Call Qualification Questions**

Ask all of these. Take notes. The answers feed directly into the "Understanding Your Organization" section of the proposal.

1. What AI tools is your organization currently using? (Probe for tools that might not be top of mind: CRM AI features, email AI, HR tools, customer service bots.)
2. How many distinct AI systems would you estimate are in scope? (This drives effort estimation.)
3. What's driving this engagement right now? (Regulatory deadline, customer requirement, board directive, incident?)
4. Do you have a target date for certification or a specific deadline we need to work toward?
5. Does your organization hold any existing ISO certifications? (ISO 27001, ISO 9001, ISO 13485?) If yes, who manages them?
6. Who would be the internal project lead? How much time can they realistically commit per week?
7. Who would need to sign off on the engagement? Is that person on this call?
8. What does your current AI governance look like? (Probe: any written policies? Any AI inventory? Any risk assessments done?)
9. Are there any AI tools under evaluation or planned for deployment in the next 6–12 months?
10. Are there any organizational constraints we should know about? (Upcoming audits, restructuring, key personnel changes, budget cycles.)
11. What does success look like for you at the end of this engagement?
12. Have you spoken with other consultants about this? (Understand the competitive situation.)
13. What's your approximate budget range for this work? (If they won't say, offer a range and watch the reaction.)
14. Are there any parts of the organization or specific AI systems that would be politically sensitive to include in scope?
15. Is there anything about your organization's AI use that you think we should know before we put together a proposal?

**After the call:**
- Update the inquiry tracker with key findings
- Note any red flags (unrealistic timeline, budget mismatch, scope that's too complex for the team, client who seems to want a rubber stamp rather than real governance)
- Decide within 24 hours whether to proceed with a proposal. If not proceeding, notify the contact promptly and professionally.

### 4.3 Proposal Preparation Checklist

Before sending the proposal, confirm all of the following:

- [ ] "Understanding Your Organization" section reflects actual discovery call notes, not generic placeholder text
- [ ] AI tools identified in the call are listed specifically
- [ ] Scope section reflects the client's actual situation (remove inapplicable items)
- [ ] Timeline is realistic given the client's stated constraints and resource availability
- [ ] Investment section has actual fee figures, not blank placeholders
- [ ] Qualifications section reflects current firm credentials
- [ ] Legal disclaimer is present
- [ ] Proposal has been reviewed by Lead Consultant before sending
- [ ] Proposal is exported to PDF or Word (not sent as raw Markdown)
- [ ] Proposal is sent with a brief cover email that references the discovery call and sets a follow-up date

### 4.4 SOW Finalization

When the client accepts the proposal:

1. Open `template-sow.md` and complete every `[PLACEHOLDER]` field. Search for `[` to find them all.
2. Confirm the phase scope matches what was agreed. If the client is purchasing Phases 1–2 only, remove Phases 3–5 from the SOW.
3. Confirm the fee figures match the accepted proposal exactly.
4. Confirm the schedule dates are realistic. Build in buffer for client review cycles (assume 5 business days per deliverable).
5. Have the SOW reviewed by the Lead Consultant and, if required by firm policy, by legal counsel.
6. Send the SOW to the Client Sponsor for signature. Use a cover email that explains what they're signing and what happens next.
7. Do not begin any billable work until the SOW is signed by both parties.
8. File the signed SOW in the client folder immediately upon receipt.

---

## 5. Kickoff

### 5.1 Kickoff Meeting Agenda

Schedule the kickoff within 5 business days of SOW signature. Duration: 60–90 minutes. Attendees: Lead Consultant, Client Sponsor, Client PM, and any key stakeholders who will be involved in Phase 1 workshops.

**Agenda:**

| Time | Topic | Owner |
|---|---|---|
| 0:00–0:10 | Introductions and meeting objectives | Lead Consultant |
| 0:10–0:25 | Engagement overview: what we're doing, why, and what success looks like | Lead Consultant |
| 0:25–0:40 | Phase 1 plan: workshop schedule, who needs to be involved, what to prepare | Lead Consultant |
| 0:40–0:55 | Client obligations review: access, documentation, management time | Lead Consultant |
| 0:55–1:05 | Communication plan: status updates, escalation, decision-making | Lead Consultant |
| 1:05–1:20 | Document request list review (see 5.2) | Lead Consultant + Client PM |
| 1:20–1:30 | Questions and next steps | Both |

**After the kickoff:**
- Send a meeting summary with agreed actions and owners within 24 hours
- Create the project folder structure (see 5.3)
- Send the document request list formally via email

### 5.2 Document Request List

Send this list to the Client PM within 24 hours of the kickoff. Request documents within 5 business days.

**Organizational context:**
- [ ] Organizational chart (current)
- [ ] List of office locations and any remote work arrangements
- [ ] Any existing management system documentation (ISO 27001, ISO 9001, etc.)
- [ ] Board or management committee terms of reference (if available)

**AI systems:**
- [ ] Any existing AI tool inventory or software asset register
- [ ] Contracts and terms of service with AI system vendors
- [ ] Any vendor data processing agreements related to AI tools
- [ ] Any internal guidance or policies related to AI tool use (even informal ones)

**Risk and compliance:**
- [ ] Any existing risk registers or risk assessment documentation
- [ ] Any previous audit reports (internal or external) related to AI or data governance
- [ ] Any regulatory correspondence related to AI or data protection
- [ ] Any customer contracts that reference AI governance requirements

**HR and training:**
- [ ] Job descriptions for roles that use or oversee AI tools
- [ ] Any existing training records related to AI or data handling

If the client can't provide a document, note it. Absence of documentation is itself a gap finding.

### 5.3 Project Setup

After kickoff, set up the following before Phase 1 work begins:

- [ ] Client folder created with standard structure: `/[CLIENT NAME]/01-discovery/`, `/02-gap-analysis/`, `/03-remediation/`, `/04-pre-audit/`, `/05-certification/`, `/admin/`
- [ ] Project plan created with phase milestones and key dates
- [ ] Weekly status update template prepared (see Section 6.1)
- [ ] Risk and issue log created (see Section 6.2)
- [ ] Workshop schedule confirmed with Client PM for Phase 1

---

## 6. Phase Execution

### 6.1 Phase 1: Discovery and Scoping

**Entry criteria:**
- SOW signed
- Kickoff complete
- Document request list sent
- Workshop schedule confirmed

**Estimated hours:** 16–24 hours (Lead Consultant), 4–8 hours (Supporting Consultant if applicable)

**Key activities and how to do them:**

**AI System Inventory Workshop**

Run this as a structured workshop, not a free-form conversation. Duration: 2–3 hours. Attendees: Client PM plus representatives from each business function that uses AI tools.

Before the workshop, prepare a blank inventory template with columns: Tool Name, Vendor, Business Function, Primary Users, Data Inputs (what data does the tool process?), Data Outputs (what does it produce?), Business Purpose, Estimated Usage Frequency, and Initial Risk Classification (High/Medium/Low).

During the workshop, go function by function. Ask: "What AI tools does your team use?" Then probe: "Does your CRM have any AI features? Does your email client have AI writing assistance? Does your HR system use AI for any decisions?" Many clients undercount their AI footprint on the first pass.

After the workshop, send the draft inventory to the Client PM for review. Ask them to circulate it to function heads for additions or corrections. Allow 3 business days for feedback.

**Stakeholder Mapping**

Work through the following categories with the Client PM:
- Internal: employees who use AI tools, employees whose work is affected by AI outputs, management, IT
- External: customers (especially those whose data AI tools process), AI system vendors/providers, regulators, industry bodies, shareholders

For each stakeholder group, document: who they are, how they're affected by the organization's AI use, and what their expectations or requirements are.

**Context Assessment**

Review the documents collected and conduct a 60-minute interview with the Client Sponsor. Cover:
- Internal factors: organizational culture toward AI, existing governance maturity, resource constraints, strategic direction
- External factors: regulatory environment (EU AI Act exposure, sector-specific rules), customer requirements, competitive landscape, technology trends

**AIMS Scope Definition**

Draft the scope document after the inventory and context work is complete. The scope must specify:
- Organizational units covered (all departments? specific functions?)
- Locations covered
- AI systems covered (reference the inventory)
- Activities covered (use, procurement, oversight of AI systems)

For AI user organizations, the scope will typically exclude AI development and training activities. Document this exclusion explicitly.

**Deliverable QA checklist (Phase 1):**
- [ ] AI System Inventory: all tools identified in workshops are listed; each row has a risk classification; no blank required fields
- [ ] Stakeholder Register: covers all four stakeholder categories; each entry has a documented relevance to the AIMS
- [ ] AIMS Scope Document: specifies organizational units, locations, AI systems, and activities; exclusions are documented; language is clear enough for an auditor to understand what's in and out
- [ ] Phase 1 Summary Report: summarizes key findings; flags any early risk observations; is readable by a non-technical client sponsor

**Client sign-off:** The Client Sponsor must sign the AIMS Scope Document before Phase 2 begins. Send it with a cover note explaining that this document becomes a required AIMS record and will be reviewed by the certification auditor.

**Exit criteria:**
- AIMS Scope Document signed by Client Sponsor
- Phase 1 Summary Report delivered and acknowledged
- No unresolved factual disputes about the AI inventory

---

### 6.2 Phase 2: Gap Analysis

**Entry criteria:**
- AIMS Scope Document signed
- Phase 1 Summary Report acknowledged
- Client has provided all available documentation from the request list

**Estimated hours:** 24–40 hours (Lead Consultant), 8–16 hours (Supporting Consultant if applicable)

**Key activities and how to do them:**

**Clause-by-Clause Assessment**

Work through ISO 42001 Clauses 4–10 systematically. For each clause:
1. Review any relevant documentation the client has provided
2. Conduct a structured interview with the relevant process owner (30–60 minutes)
3. Document: current state (what exists), gap (what's missing or insufficient), severity (major/minor/observation), and recommended remediation

Use the Gap Analysis Workbook template. Do not skip clauses. Even if a clause seems obviously compliant, document the evidence.

**Severity definitions:**
- **Major gap:** The requirement is not met. There is no documentation, no process, or no evidence of the activity. This will be a nonconformity if not addressed before certification.
- **Minor gap:** The requirement is partially met. Something exists but it's incomplete, inconsistent, or not formally documented. This may be a nonconformity or an observation depending on the auditor.
- **Observation:** The requirement is met but there's an improvement opportunity. Not a compliance failure.

**Annex A Control Evaluation**

For each Annex A control:
1. Determine applicability: does this control apply to an AI user organization? Many development-focused controls (e.g., controls related to training data, model development) will not apply. Document the justification for exclusion.
2. For applicable controls, assess current compliance using the same major/minor/observation scale.
3. Record findings in the Gap Analysis Workbook.

**Preliminary SoA**

Draft the preliminary SoA as you work through Annex A. For each control, record: applicable (yes/no), justification for inclusion or exclusion, and current implementation status. The preliminary SoA is a working document at this stage; it will be finalized in Phase 3.

**Deliverable QA checklist (Phase 2):**
- [ ] Gap Analysis Workbook: all clauses (4–10) assessed; all Annex A controls addressed; no blank severity fields; each gap has a recommended remediation action
- [ ] Gap Analysis Report: executive summary is readable by a non-technical sponsor; findings are prioritized (address major gaps first); remediation sequence is logical and accounts for dependencies
- [ ] Preliminary SoA: all Annex A controls listed; applicability decisions are documented with justification; exclusions reference the AI user role where relevant

**Client sign-off:** The Gap Analysis Report requires acknowledgment (not formal sign-off) from the Client Sponsor. Send it with a cover note explaining that the findings drive Phase 3 scope. Ask the client to confirm the findings reflect their actual situation and to raise any factual corrections within 5 business days.

**Exit criteria:**
- Gap Analysis Report acknowledged by Client Sponsor
- No unresolved factual disputes about findings
- Client has confirmed readiness to proceed to Phase 3 (or engagement concludes here for Phase 1–2 scope)

---

### 6.3 Phase 3: Remediation and Implementation

**Entry criteria:**
- Gap Analysis Report acknowledged
- Client has confirmed Phase 3 scope (which gaps to address, in what sequence)
- Client has confirmed resource availability for document review cycles

**Estimated hours:** 40–80 hours (Lead Consultant), 16–32 hours (Supporting Consultant if applicable)

**Key activities and how to do them:**

**Documentation Development Sequence**

Build AIMS documentation in this order. Each layer depends on the one before it.

1. **Roles and Responsibilities Matrix** — Define who owns what before writing any policies. Policies that assign responsibilities to undefined roles create audit findings.
2. **AI Use Policy** — The top-level policy statement. Sets the organization's commitment to responsible AI use. Requires management sign-off.
3. **Acceptable Use Guidelines** — Operational guidance for staff. What they can and can't do with AI tools. Derived from the AI Use Policy.
4. **AI Provider Assessment Procedure** — How the organization evaluates and monitors third-party AI vendors. Feeds into the risk register.
5. **Risk Assessment Procedure** — The methodology for assessing AI system risks. Must be documented before conducting the risk assessment.
6. **AI Risk Register** — Apply the risk assessment procedure to each in-scope AI system. This is a record, not a policy.
7. **Risk Treatment Plan** — Document how identified risks will be treated. Feeds into the SoA.
8. **SoA (final)** — Finalize after the risk treatment plan is complete. The SoA reflects which controls are implemented to treat which risks.
9. **Incident Identification and Response Procedure** — How the organization identifies, reports, and responds to AI-related incidents.
10. **Corrective Action Procedure** — How the organization handles nonconformities and drives continual improvement.
11. **Documented Information Register** — List all AIMS documents and records with version, owner, and review cycle.
12. **Internal Audit Procedure** — Required before Phase 4. Defines how internal audits are planned and conducted.
13. **Management Review Procedure** — Required before Phase 4. Defines the management review process, inputs, and outputs.

**Document Review Cycles**

For each document:
1. Draft the document
2. Send to the relevant process owner for review (allow 3 business days)
3. Incorporate feedback and send to the Client Sponsor for approval (allow 3 business days)
4. Finalize and add to the Documented Information Register

Do not skip the process owner review step. Documents that process owners haven't reviewed tend to describe processes that don't match reality.

**Risk Assessment**

Apply the risk assessment procedure to each AI system in the inventory. For each system, assess:
- Likelihood of harm (to individuals, groups, or the organization)
- Severity of potential harm
- Existing controls that reduce likelihood or severity
- Residual risk after existing controls

Record findings in the AI Risk Register. Flag any high-residual-risk systems for priority treatment.

**Awareness Training**

Develop a brief (30–45 minute) awareness session covering:
- What the AIMS is and why it exists
- The organization's AI use policy and acceptable use guidelines
- How to identify and report AI-related incidents
- Who to contact with questions

Deliver the session to all relevant staff. Record attendance. The training records are a required AIMS document.

**Deliverable QA checklist (Phase 3):**
- [ ] All policies: approved by management; version controlled; in the Documented Information Register
- [ ] All procedures: reviewed by relevant process owners; version controlled; in the Documented Information Register
- [ ] AI Risk Register: all in-scope AI systems assessed; risk ratings documented; treatment decisions recorded
- [ ] Risk Treatment Plan: all high and medium risks have documented treatment actions with owners and target dates
- [ ] SoA (final): all Annex A controls addressed; applicable controls reference the risk treatment plan; exclusions are justified; signed by management
- [ ] Training records: attendance documented for all required staff; training content version controlled

**Client sign-off:** The SoA requires formal sign-off from management (not just the Client PM). This is a required AIMS record. The Client Sponsor must sign it.

**Exit criteria:**
- All deliverables reviewed and accepted by client
- SoA signed by management
- Training records complete
- Documented Information Register reflects all AIMS documents

---

### 6.4 Phase 4: Pre-Audit Readiness Review

**Entry criteria:**
- All Phase 3 deliverables accepted
- SoA signed
- Training records complete
- Client has confirmed availability for internal audit activities and management review

**Estimated hours:** 16–24 hours (Lead Consultant), 4–8 hours (Supporting Consultant if applicable)

**Key activities and how to do them:**

**Internal Audit Planning**

Prepare an internal audit plan covering:
- Audit scope (all in-scope clauses and applicable Annex A controls)
- Audit schedule (which areas will be audited on which dates)
- Auditors (Lead Consultant as lead auditor; note that the auditor must be independent of the area being audited)
- Evidence to be reviewed for each clause/control

Send the audit plan to the Client PM at least 5 business days before the audit begins.

**Internal Audit Execution**

Conduct the audit by reviewing documentation and interviewing process owners. For each clause and control:
1. Review the documented procedure or policy
2. Ask the process owner to walk you through how they actually perform the activity
3. Request evidence (records) that the activity has been performed
4. Note any gaps between what the documentation says and what actually happens

Document findings as: conformity (requirement met with evidence), minor nonconformity (partial compliance), major nonconformity (requirement not met), or observation (improvement opportunity).

**Corrective Action Initiation**

For each nonconformity:
1. Document the finding in the Corrective Action Register: finding description, clause/control reference, severity, assigned owner, target closure date
2. Brief the Client PM on findings within 24 hours of completing the audit
3. Work with the client to develop corrective actions for each finding
4. Confirm that major nonconformities are closed (or have credible closure plans) before proceeding to Phase 5

**Management Review Facilitation**

Prepare the management review agenda and inputs at least 5 business days before the meeting. Required inputs per ISO 42001 Clause 9.3:
- Status of actions from previous management reviews (if any)
- Changes in external and internal issues relevant to the AIMS
- Information on AIMS performance (audit results, nonconformities, monitoring results)
- Adequacy of resources
- Effectiveness of actions taken to address risks and opportunities
- Opportunities for continual improvement

Facilitate the meeting. Record decisions and actions. The management review record must be signed by the most senior attendee.

**Auditor Question Simulation**

Run a 60-minute session with the Client Sponsor and Client PM. Walk through the types of questions a Stage 1 and Stage 2 auditor will ask. Focus on:
- "Show me your AIMS scope document and explain what's in and out of scope."
- "Walk me through how you identified your interested parties."
- "Show me your SoA and explain why [specific control] is excluded."
- "Walk me through your risk assessment process for [specific AI system]."
- "Show me evidence that [specific procedure] has been followed."
- "What would you do if [specific AI incident scenario] occurred?"

Note any areas where the client struggles to answer confidently. Address those gaps before Stage 1.

**Deliverable QA checklist (Phase 4):**
- [ ] Internal Audit Report: all in-scope clauses and controls covered; findings documented with evidence references; severity classifications applied consistently
- [ ] Corrective Action Register: all nonconformities have assigned owners and target dates; major nonconformities have closure evidence or credible plans
- [ ] Management Review Record: covers all required Clause 9.3 inputs; decisions and actions documented; signed by top management
- [ ] Certification Readiness Checklist: all items addressed; any open items have documented plans
- [ ] Pre-Audit Briefing Document: covers Stage 1 and Stage 2 process; includes likely auditor questions; references evidence locations

**Client sign-off:** The Management Review Record requires sign-off from top management. This is a required AIMS record.

**Exit criteria:**
- Internal audit complete
- All major nonconformities closed or have documented remediation plans with credible timelines
- Management review record signed
- Client management has confirmed readiness to proceed to certification

---

### 6.5 Phase 5: Certification Audit Support

**Entry criteria:**
- Phase 4 complete
- Client management has confirmed readiness
- Certification body selected and application submitted

**Estimated hours:** 16–32 hours (Lead Consultant)

**Key activities and how to do them:**

**Certification Body Selection**

Research accredited CBs with ISO 42001 competence. At the time of writing, ISO 42001 is a relatively new standard and not all CBs have developed competence. Check accreditation body websites for current lists.

Prepare a comparison covering: accreditation status, ISO 42001 experience, geographic coverage, estimated fees, and availability. Present the comparison to the Client Sponsor with a recommendation.

Once the client selects a CB, support the application process: completing application forms, preparing the scope statement for the CB, and confirming audit dates.

**Stage 1 Preparation**

Stage 1 is a document review. The CB will review the AIMS documentation to confirm it's complete and suitable for Stage 2. Prepare a Stage 1 Submission Package:
- AIMS Scope Document
- Statement of Applicability
- All required policies and procedures
- AI Risk Register and Risk Treatment Plan
- Internal Audit Report and Corrective Action Register
- Management Review Record
- Documented Information Register

Organize the package so the auditor can navigate it easily. Include a cover sheet that maps each required document to its location in the package.

**Stage 1 Attendance**

Attend Stage 1 in an advisory capacity. Do not answer questions on behalf of the client. Your role is to observe, take notes, and debrief the client after the session.

After Stage 1, review any findings with the client. Determine whether each finding is a nonconformity that must be addressed before Stage 2, or an observation that can be addressed after certification.

**Stage 2 Preparation**

Address any Stage 1 findings. Confirm that all evidence is in place and accessible. Brief all personnel who will be interviewed during Stage 2 on what to expect.

**Stage 2 Attendance**

Attend Stage 2 in an advisory capacity. Take detailed notes on auditor questions and client responses. Note any areas where the auditor seems unsatisfied with an answer.

After Stage 2, debrief the client on findings. If nonconformities are raised, begin working on responses immediately. CB timelines for nonconformity responses are typically 30–90 days.

**Nonconformity Response Support**

For each nonconformity:
1. Conduct a root cause analysis with the relevant process owner
2. Document the root cause, the correction (immediate fix), and the corrective action (systemic fix to prevent recurrence)
3. Prepare the response in the format required by the CB
4. Submit within the CB's required timeframe

**Deliverable QA checklist (Phase 5):**
- [ ] Certification Body Selection Summary: covers all relevant CBs; recommendation is justified
- [ ] Stage 1 Submission Package: complete; organized; all required documents present
- [ ] Stage 1 Findings Response (if applicable): addresses all Stage 1 findings; accepted by CB before Stage 2
- [ ] Stage 2 Preparation Checklist: all items complete; personnel briefed
- [ ] Nonconformity Response Documentation (if applicable): root cause analysis complete; corrective actions documented; submitted within CB timeframe

**Exit criteria:**
- Stage 2 audit complete
- Any nonconformities have documented responses submitted to the CB
- Certification decision received (or timeline confirmed if decision is pending)

---

## 7. Ongoing Engagement Management

### 7.1 Weekly Status Update

Send a written status update to the Client PM every [DAY OF WEEK]. Use this template:

---

**Weekly Status Update — [CLIENT NAME] — Week of [DATE]**

**Overall status:** [Green / Amber / Red]

**Work completed this week:**
- [Item]
- [Item]

**Work planned for next week:**
- [Item]
- [Item]

**Decisions needed from client:**
- [Decision needed, by when, and why it's time-sensitive]

**Risks and issues:**
- [Risk or issue, impact, and proposed mitigation]

**Upcoming milestones:**
- [Milestone, target date, status]

---

Green = on track. Amber = at risk but manageable. Red = off track, requires escalation or scope/schedule discussion.

Never send a Red status without a phone call to the Client PM first.

### 7.2 Risk and Issue Tracking

Maintain a risk and issue log throughout the engagement. Update it weekly.

**Risk log columns:** Risk ID, Description, Likelihood (High/Medium/Low), Impact (High/Medium/Low), Risk Rating (H x I), Mitigation Action, Owner, Status.

**Issue log columns:** Issue ID, Description, Date Raised, Impact, Resolution Action, Owner, Target Date, Status.

**Common risks to track from day one:**
- Client resource availability (the most common cause of delays)
- Scope creep (client requests that expand beyond the SOW)
- AI inventory completeness (new tools discovered late in the engagement)
- Management engagement (sponsor becomes unavailable or disengaged)
- Certification body availability (limited CB capacity for ISO 42001)

### 7.3 Scope Change Management

When a client requests work outside the SOW scope:

1. Do not agree to perform the work verbally. Say: "That sounds like it might be outside our current scope. Let me check and get back to you."
2. Review the SOW. If the work is clearly out of scope, prepare a Change Order.
3. A Change Order must include: description of the additional work, timeline impact, and additional fee.
4. Send the Change Order to the Client Sponsor (not just the Client PM) for approval.
5. Do not begin out-of-scope work until the Change Order is signed.
6. If the client disputes whether the work is in scope, escalate to the Lead Consultant immediately.

### 7.4 Client Escalation Procedure

Use this procedure when the engagement is at risk due to client-side issues.

**Level 1: Client PM conversation**

Use when: minor delays, missed document submissions, scheduling difficulties.

Action: Raise the issue directly with the Client PM. Document the conversation in the issue log. Set a clear resolution date.

**Level 2: Client Sponsor email**

Use when: Level 1 hasn't resolved the issue within 5 business days, or the issue is significant enough to affect a phase milestone.

Action: Send a written summary to the Client Sponsor (copy the Client PM). State the issue, the impact on the engagement, and what you need from the client to resolve it. Request a response within 2 business days.

**Level 3: Formal notice**

Use when: Level 2 hasn't resolved the issue, or the engagement is at risk of failing to meet its objectives due to client non-performance.

Action: Send a formal written notice to the Client Sponsor referencing the relevant SOW obligations (Section 7 of the SOW). State that continued non-performance may require a schedule extension, additional fees, or engagement suspension. Consult with the Lead Consultant before sending.

**Level 4: Engagement suspension or termination**

Use when: The client is unable or unwilling to meet their SOW obligations and the engagement cannot proceed.

Action: Consult with the Lead Consultant and, if appropriate, legal counsel. Follow the termination provisions in the SOW.

---

## 8. Decision Trees

### 8.1 Client Unresponsive

```
Client has not responded to a request within the agreed timeframe
│
├── Has it been less than 3 business days?
│   └── YES → Wait. Send a polite follow-up on day 3.
│
└── Has it been 3+ business days?
    │
    ├── Is this a minor request (scheduling, document access)?
    │   └── YES → Follow up with Client PM. Log in issue tracker.
    │               If no response in 2 more days → escalate to Level 2.
    │
    └── Is this a critical request (deliverable sign-off, phase gate)?
        │
        ├── Has the delay affected a milestone?
        │   └── YES → Escalate to Level 2 immediately.
        │               Update project plan to reflect delay.
        │               Notify client in writing that timeline is affected.
        │
        └── Has the delay NOT yet affected a milestone?
            └── Escalate to Level 1. Set a 2-day resolution deadline.
                If unresolved → escalate to Level 2.
```

### 8.2 Scope Change Requested

```
Client requests work or a deliverable not described in the SOW
│
├── Is the request clearly within the SOW scope?
│   └── YES → Proceed. No change order needed.
│               Document the request and your decision in the issue log.
│
└── Is the request outside or ambiguous relative to SOW scope?
    │
    ├── Is the additional work minor (< 2 hours, no deliverable impact)?
    │   └── Consider absorbing it as goodwill, but:
    │       - Document it in the issue log
    │       - Note it in the weekly status update
    │       - If similar requests recur, raise a Change Order
    │
    └── Is the additional work significant (> 2 hours, or adds a deliverable)?
        │
        ├── Prepare a Change Order (description, timeline impact, fee)
        │
        ├── Send to Client Sponsor for approval
        │
        ├── Client approves?
        │   └── YES → Proceed. File signed Change Order.
        │               Update project plan and fee tracker.
        │
        └── Client declines?
            └── Do not perform the work.
                Document the declined request in the issue log.
                If client continues to request the work, escalate to Lead Consultant.
```

---

## 9. Close-Out

### 9.1 Deliverable Handover Checklist

Before closing the engagement, confirm all of the following:

**Documentation:**
- [ ] All deliverables listed in the SOW have been delivered and accepted
- [ ] All deliverables are in their final versions (no drafts in the client folder)
- [ ] All deliverables are accessible to the client in the agreed format
- [ ] The Documented Information Register is complete and up to date

**Records:**
- [ ] All client sign-offs are on file (AIMS Scope Document, SoA, Management Review Record)
- [ ] All Change Orders are on file
- [ ] All weekly status updates are archived
- [ ] The risk and issue log is closed out (all open items resolved or formally accepted)

**Access:**
- [ ] Any shared project workspaces or document repositories have been transferred to the client
- [ ] Consultant access to client systems has been revoked (if applicable)

**Financial:**
- [ ] All invoices have been issued
- [ ] All invoices have been paid (or payment is confirmed)
- [ ] Any outstanding expenses have been submitted and approved

### 9.2 Client Satisfaction Survey

Send a brief satisfaction survey to the Client Sponsor within 5 business days of engagement close. Keep it short: 5–7 questions, mix of rating scale and open text.

Suggested questions:
1. How would you rate the overall quality of the deliverables? (1–5)
2. How would you rate the Lead Consultant's communication throughout the engagement? (1–5)
3. Did the engagement meet your objectives? (Yes / Partially / No)
4. Was the engagement completed within the agreed timeline? (Yes / Mostly / No)
5. How likely are you to recommend our services to a colleague? (1–10)
6. What worked well in this engagement?
7. What could we have done better?

Review responses within 48 hours. If any rating is 3 or below, follow up with a phone call.

### 9.3 Lessons Learned

Within 2 weeks of engagement close, conduct a 30-minute internal lessons learned session with the engagement team. Document:

- What went well (keep doing this)
- What didn't go well (stop doing this or do it differently)
- What surprised us (update the procedure or templates to account for it)
- Any new risks or issues that should be added to the standard risk log
- Any template improvements identified during the engagement

File the lessons learned document in the internal knowledge base. Update this procedure if any lessons warrant a process change.

### 9.4 Follow-On Opportunity Identification

At close-out, assess whether there are natural follow-on opportunities:

- **Surveillance support:** Does the client need help maintaining their AIMS and preparing for surveillance audits? (Separate engagement.)
- **Scope expansion:** Are there AI systems or organizational units that were out of scope for this engagement but could be included in a future one?
- **Cross-framework work:** Does the client have EU AI Act compliance gaps that weren't addressed in this engagement?
- **Training:** Does the client need ongoing staff training as their AI tool usage evolves?

Document any identified opportunities and discuss with the Lead Consultant. If appropriate, raise them with the Client Sponsor in the close-out conversation.

---

## 10. Time Estimates by Phase

The following estimates are for a typical SMB engagement (5–15 AI systems in scope, 50–500 employees, no existing ISO management system). Adjust up for larger organizations, more complex AI footprints, or significant existing documentation gaps.

| Phase | Lead Consultant Hours | Supporting Consultant Hours | Total Hours |
|---|---|---|---|
| Pre-Engagement (discovery call through signed SOW) | 4–8 | 0–2 | 4–10 |
| Kickoff | 2–4 | 0–2 | 2–6 |
| Phase 1: Discovery and Scoping | 16–24 | 4–8 | 20–32 |
| Phase 2: Gap Analysis | 24–40 | 8–16 | 32–56 |
| Phase 3: Remediation and Implementation | 40–80 | 16–32 | 56–112 |
| Phase 4: Pre-Audit Readiness Review | 16–24 | 4–8 | 20–32 |
| Phase 5: Certification Audit Support | 16–32 | 0–4 | 16–36 |
| Ongoing Management (status updates, risk/issue tracking) | 1–2/week | 0 | Varies |
| Close-Out | 4–6 | 0–2 | 4–8 |
| **Total (Phases 1–5, excluding pre-engagement and close-out)** | **114–204** | **32–70** | **146–274** |
| **Total (Phases 1–2 only)** | **40–64** | **12–24** | **52–88** |

**Notes:**
- Hours at the high end of each range apply when: the client has no existing governance documentation, the AI inventory is large or complex, client responsiveness is slow, or significant corrective action is required after the internal audit.
- Phase 3 is the most variable phase. A client with existing ISO 27001 documentation will require significantly less effort than one starting from scratch.
- Phase 5 hours depend heavily on whether nonconformities are raised during Stage 1 or Stage 2. Budget for the high end if the client's AIMS is not mature.

---

*ISO 42001 Readiness Service Toolkit | 07-Business | Internal Use Only*
