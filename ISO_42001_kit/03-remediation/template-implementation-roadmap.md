# AIMS Implementation Roadmap

> **Current as of:** March 2026 | ISO/IEC 42001:2023

---

> **HOW TO CUSTOMIZE (Remove this block before delivering to client)**
>
> This template is a working project management tool. It is not a compliance document. It's the plan that produces compliance documents.
>
> **Before your first client meeting:**
> 1. Replace all `[BRACKETED]` fields with client-specific information.
> 2. Adjust phase durations based on the gap analysis findings. A client with mostly minor gaps may compress to 12 weeks. A client with no AI policy and no risk process may need 20 weeks.
> 3. Populate the Action Plan table (Section 3) with the specific actions from the gap analysis report. Remove example rows that don't apply.
> 4. Set realistic start weeks based on when the client can actually begin. Week 1 is the week after the gap analysis debrief, not the week you deliver this document.
> 5. Assign owners by role, not by name where possible. Roles survive personnel changes; names don't.
> 6. The Milestone Tracker (Section 4) is what you review in every status call. Keep it current.
> 7. Resource estimates in Section 5 are conservative. Adjust based on what you learned during discovery.
>
> **Clause traceability:** This roadmap addresses ISO 42001 Clauses 6.2 (AI objectives and planning) and 8.1 (operational planning and control). The individual actions within it trace to their specific clauses in the Action Plan table.

---

## Document Metadata

| Field | Value |
|---|---|
| **Document ID** | AIMS-ROAD-001 |
| **Version** | 1.0 |
| **Date** | [YYYY-MM-DD] |
| **Organization** | [Organization Name] |
| **Prepared By** | [Name, Role] |
| **Approved By** | [Name, Role] |
| **Target Certification Date** | [YYYY-MM-DD] |
| **Next Review Date** | [YYYY-MM-DD — review at each phase gate] |

---

> **Legal Disclaimer:** This template does not constitute legal advice and does not create a legal, professional, or advisory relationship between the preparer and any other party. Organizations should seek qualified legal counsel for advice on regulatory obligations specific to their jurisdiction and industry. ISO 42001 certification does not guarantee compliance with any particular law or regulation.

---

## 1. Purpose

This roadmap translates the findings from the AIMS Gap Analysis Report into a sequenced action plan for achieving ISO 42001 certification readiness. It identifies what needs to be done, in what order, by when, and by whom.

The roadmap is organized into six phases. Each phase builds on the one before it. The critical path runs through four milestones: AI Policy approval, Risk Assessment completion, Statement of Applicability (SoA) approval, and Internal Audit completion. Nothing on the critical path can be skipped or significantly delayed without pushing the certification date.

This document is a living project management tool. It should be reviewed at every status meeting and updated when timelines shift, owners change, or new actions are identified.

**ISO 42001 Clause Traceability:**
- Clause 6.2 — AI objectives and planning to achieve them
- Clause 8.1 — Operational planning and control

---

## 2. Roadmap Overview

The table below summarizes the six phases, their duration, and the key deliverables each phase produces. Phases overlap where dependencies allow. Phase 3 begins before Phase 2 is complete, for example, because some controls implementation can start once the risk assessment is underway. The overlap is intentional and keeps the overall timeline manageable for SMB teams with limited bandwidth.

| Phase | Name | Duration | Key Deliverables | Status |
|---|---|---|---|---|
| **Phase 1** | Foundation | Weeks 1–2 | AIMS Owner designated, AI Policy approved, Acceptable Use Policy drafted, AIMS scope confirmed | [ ] Not Started |
| **Phase 2** | Risk and Impact Assessment | Weeks 2–6 | AI Risk Assessment Register, Impact Assessments (high-risk systems), Statement of Applicability draft | [ ] Not Started |
| **Phase 3** | Controls Implementation | Weeks 4–10 | Risk Treatment Plan, Supplier Assessments (priority vendors), AI Competency Framework, Training Program delivered | [ ] Not Started |
| **Phase 4** | Documentation and Records | Weeks 8–12 | All required AIMS documentation complete, document control established, records management in place | [ ] Not Started |
| **Phase 5** | Internal Audit and Review | Weeks 12–14 | Internal audit completed, management review conducted, corrective actions logged and assigned | [ ] Not Started |
| **Phase 6** | Pre-Certification Readiness | Weeks 14–16 | Mock audit completed, all critical findings closed, Stage 1 audit scheduled and prepared | [ ] Not Started |

**Total estimated duration:** 16–20 weeks from gap analysis debrief to Stage 1 audit.

*Actual duration depends on resource availability, the number and severity of gaps identified, and vendor responsiveness during supplier assessments. Most SMB clients achieve certification readiness in 14–18 weeks when internal resources are available as planned.*

### 2.1 Phase Descriptions

**Phase 1: Foundation (Weeks 1–2)**

Phase 1 establishes the governance infrastructure that everything else depends on. The two non-negotiable outputs are a designated AIMS Owner and an approved AI Policy. Without an AIMS Owner, no one has authority to make decisions. Without an AI Policy, there is no documented commitment to anchor the rest of the management system.

The AI System Inventory also begins in Phase 1. It can run in parallel with policy drafting because it has no dependency on the policy. Starting the inventory immediately is one of the highest-value actions in the entire engagement. Many clients discover AI systems they didn't know were in scope, and those discoveries affect the risk assessment scope.

Phase 1 is typically the fastest phase. Most clients can complete it in two weeks if management is available for the policy approval decision.

**Phase 2: Risk and Impact Assessment (Weeks 2–6)**

Phase 2 is the analytical core of the AIMS. The risk assessment identifies what could go wrong with each AI system and how severe the consequences could be. The impact assessments go deeper on high-risk systems, asking specifically what harm could occur to people. The Statement of Applicability synthesizes both into a documented record of which Annex A controls apply and why.

This phase requires the most consultant involvement. The risk methodology needs to be calibrated to the client's context, and the impact assessments for high-risk systems often surface issues that require management attention before the SoA can be finalized.

Phase 2 is the most common source of timeline slippage. Risk assessment workshops take longer than expected, impact assessments require more stakeholder input than anticipated, and SoA decisions sometimes require multiple rounds of management review. Build buffer here.

**Phase 3: Controls Implementation (Weeks 4–10)**

Phase 3 translates the risk treatment decisions from Phase 2 into operational controls. The Risk Treatment Plan documents what the organization will do about each identified risk. Supplier assessments evaluate whether key AI vendors meet the organization's governance requirements. The competency framework and training program ensure that people using AI systems understand their obligations.

Phase 3 has the most parallel workstreams. Supplier assessments, training development, and document control can all proceed simultaneously once the risk assessment is underway. The AIMS Owner needs to coordinate these workstreams actively to prevent bottlenecks.

**Phase 4: Documentation and Records (Weeks 8–12)**

Phase 4 is about completeness and consistency. By Week 8, most of the substantive AIMS work is done. Phase 4 ensures that all required documented information exists, is approved, is version-controlled, and is accessible. It also establishes the records management practices that will generate ongoing audit evidence after certification.

A common mistake is treating Phase 4 as a documentation sprint at the end of the project. Documentation should be produced throughout the engagement, with Phase 4 serving as the final review and gap-closure phase, not the primary production phase.

**Phase 5: Internal Audit and Review (Weeks 12–14)**

The internal audit is a required AIMS activity and a critical pre-certification step. It tests whether the AIMS is actually operating as documented. The management review that follows gives senior leadership a formal opportunity to assess AIMS performance and make decisions about resources, objectives, and improvements.

Both activities generate records that the certification auditor will review. The internal audit report and management review minutes are among the most scrutinized documents in a Stage 2 audit. They need to be substantive, not perfunctory.

**Phase 6: Pre-Certification Readiness (Weeks 14–16)**

Phase 6 prepares the organization for the certification body's Stage 1 audit. The Stage 1 audit is a document review. The certification body assesses whether the AIMS documentation is complete and whether the organization is ready for the Stage 2 on-site audit. Stage 1 findings are typically documentation gaps or clarifications. They are not unusual and do not indicate failure.

The key output of Phase 6 is a complete, organized documentation package that the certification body can review efficiently. A document index that maps each ISO 42001 requirement to the relevant AIMS document is a practical tool that auditors appreciate.

### 2.2 Critical Path

The critical path is the sequence of actions where any delay directly delays the certification date. For most SMB AIMS implementations, the critical path is:

```
Designate AIMS Owner (ACT-001)
  → Draft and approve AI Policy (ACT-002)
    → Conduct AI Risk Assessment (ACT-005)
      → Develop Statement of Applicability (ACT-007)
        → Conduct Internal Audit (ACT-015)
          → Conduct Management Review (ACT-016)
            → Stage 1 Audit Preparation (ACT-018)
              → Stage 1 Audit (ACT-019)
```

Actions off the critical path (supplier assessments, training, document control) are still required for certification. They just don't directly determine the certification date if they complete on time. Monitor the critical path actions most closely in status meetings.

---

## 3. Detailed Action Plan

The table below lists all actions required to achieve certification readiness. Actions are sequenced by dependency, not by phase alone. Review the "Depends On" column before scheduling any action. Starting an action before its dependencies are complete wastes effort and produces documents that need rework.

**Priority definitions:**
- **Critical:** Must be complete before certification audit can proceed. Blocking the critical path.
- **High:** Required for certification. Can be addressed in parallel with critical items where dependencies allow.
- **Medium:** Required for certification but not on the critical path. Can be scheduled after critical and high items are underway.

**Status options:** Not Started / In Progress / Complete / Blocked

| Action ID | Phase | Action Description | ISO 42001 Reference | Priority | Owner (Role) | Depends On | Start Week | End Week | Status | Notes |
|---|---|---|---|---|---|---|---|---|---|---|
| ACT-001 | 1 | Designate AIMS Owner — assign a named individual with authority and accountability for AIMS implementation and maintenance | Clause 5.3 | Critical | CEO / COO | None | Week 1 | Week 1 | | Management decision required; no documentation needed to complete this action |
| ACT-002 | 1 | Draft and approve AI Policy — covering responsible AI use commitments, governance objectives, and AIMS scope | Clause 5.2, A.2.2 | Critical | AIMS Owner + Consultant | ACT-001 | Week 1 | Week 2 | | Policy must be approved by top management before it can be used as a foundation for other documents |
| ACT-003 | 1 | Draft Acceptable Use Policy — defining permitted and prohibited AI uses, employee obligations, and reporting requirements | A.6.2.10, A.9.3 | Critical | AIMS Owner | ACT-002 | Week 2 | Week 3 | | Can be drafted in parallel with ACT-004; requires AI Policy as parent document |
| ACT-004 | 1 | Complete AI System Inventory — document all in-scope AI systems including embedded AI features in existing SaaS platforms | A.6.2.9 | Critical | IT Lead | None | Week 1 | Week 2 | | Can begin immediately; use AIMS-INV-001 template; involve department heads for shadow AI discovery |
| ACT-005 | 2 | Conduct AI Risk Assessment — assess risks for all systems in the inventory using the documented risk methodology | Clause 6.1.2, A.5.2 | Critical | AIMS Owner + Consultant | ACT-002, ACT-004 | Week 2 | Week 4 | | Risk criteria must be defined before assessment begins; output is the Risk Assessment Register (AIMS-RISK-001) |
| ACT-006 | 2 | Conduct Impact Assessments for high-risk AI systems — evaluate potential effects on individuals, groups, and society | Clause 6.1.4, A.5.3 | Critical | AIMS Owner + Consultant | ACT-005 | Week 3 | Week 5 | | Prioritize systems classified as high or critical risk in ACT-005; use AIMS-IA-001 template |
| ACT-007 | 2 | Develop Statement of Applicability — document applicable and excluded Annex A controls with justifications | Clause 6.1.6 | Critical | AIMS Owner + Consultant | ACT-005, ACT-006 | Week 4 | Week 6 | | SoA is one of the first documents a certification auditor will request; requires risk assessment and impact assessment inputs |
| ACT-008 | 3 | Develop Risk Treatment Plan — document treatment decisions for identified risks, selected controls, and residual risk acceptance | Clause 6.1.3 | High | AIMS Owner | ACT-005, ACT-007 | Week 5 | Week 7 | | Treatment options: avoid, accept, transfer, or mitigate; selected controls must align with SoA |
| ACT-009 | 3 | Conduct Supplier Assessments for priority AI vendors — evaluate vendor AI governance, data handling, and contractual controls | A.10.2 | High | IT Lead + Procurement | ACT-004 | Week 4 | Week 8 | | Prioritize vendors processing personal data or supporting high-risk AI systems; use AIMS-SUPP-001 template |
| ACT-010 | 1 | Establish document control for AIMS — extend existing document control procedures to cover all AIMS documentation | Clause 7.5 | Medium | AIMS Owner | ACT-002 | Week 2 | Week 4 | | For most SMBs this means adding AIMS documents to an existing register, not building a new system |
| ACT-011 | 3 | Define AI competency requirements — identify required knowledge and skills for roles involved in AI use and governance | Clause 7.2, A.4.3 | Medium | HR + AIMS Owner | ACT-002 | Week 4 | Week 6 | | Output is a competency matrix by role; feeds into training program design (ACT-012) |
| ACT-012 | 3 | Deliver AI awareness training — provide all personnel using AI systems with training on responsible use, risks, and obligations | Clause 7.3, A.4.4 | Medium | AIMS Owner + HR | ACT-011 | Week 6 | Week 8 | | Training records are audit evidence; retain attendance records and completion confirmations |
| ACT-013 | 3 | Establish NCAR process — implement a documented process for logging, investigating, and closing nonconformities and corrective actions | Clause 10.1 | Medium | AIMS Owner | ACT-002 | Week 6 | Week 8 | | A simple log and investigation form is sufficient for SMBs; the process must be documented and followed |
| ACT-014 | 4 | Establish monitoring and measurement — define AIMS performance indicators and a process for collecting and reviewing them | Clause 9.1 | Medium | AIMS Owner | ACT-007 | Week 8 | Week 10 | | Indicators should connect to AI objectives (Clause 6.2); examples: number of AI incidents, training completion rate, supplier assessment completion |
| ACT-015 | 5 | Conduct internal audit — perform a systematic review of AIMS conformance against ISO 42001 requirements | Clause 9.2 | High | Internal Auditor | All prior actions | Week 12 | Week 13 | | Auditor must be independent of the areas being audited; consultant can conduct if internal resource is not available |
| ACT-016 | 5 | Conduct management review — top management reviews AIMS performance, audit results, and strategic alignment | Clause 9.3 | High | Senior Management | ACT-015 | Week 13 | Week 14 | | Requires documented agenda, inputs, and recorded outputs (decisions and actions); one-page meeting record is sufficient |
| ACT-017 | 5 | Close corrective actions from internal audit — investigate root causes and implement corrective actions for all nonconformities raised | Clause 10.1 | High | AIMS Owner | ACT-015 | Week 13 | Week 15 | | Major nonconformities must be closed before Stage 2 audit; minor nonconformities need a credible action plan |
| ACT-018 | 6 | Stage 1 audit preparation — compile and organize all AIMS documentation for certification body document review | Clause 9.2 | High | AIMS Owner + Consultant | ACT-016 | Week 14 | Week 16 | | Prepare a document index; confirm all required documented information is complete and approved |
| ACT-019 | 6 | Stage 1 audit (document review) — certification body conducts off-site review of AIMS documentation | External | High | Certification Body | ACT-018 | Week 16 | Week 16 | | Certification body schedules this; ensure all documents are accessible in the agreed format |
| ACT-020 | 6 | Close Stage 1 findings — address any observations or nonconformities raised by the certification body during Stage 1 | Clause 10.1 | High | AIMS Owner | ACT-019 | Week 17 | Week 18 | | Stage 1 findings are typically documentation gaps; most can be resolved within 1–2 weeks |

### 3.1 Action Plan Notes

A few points on using this table effectively:

**Ownership.** Each action has a single primary owner. That person is accountable for the action completing on time, even if others contribute. If an action has no clear owner, it will not get done. Assign owners before the kickoff meeting, not during it.

**Dependencies.** The "Depends On" column is not advisory. An action that depends on another action cannot produce a useful output until its dependency is complete. Starting ACT-005 (Risk Assessment) before ACT-004 (AI System Inventory) is complete means the risk assessment will be incomplete and will need to be redone when new systems are discovered.

**Status updates.** Update the Status column weekly. "Not Started" items that should be "In Progress" by their start week are early warning signs. Catch them before they become schedule problems.

**Adding actions.** The gap analysis report will identify specific actions not listed here. Add them with the next available ACT-ID. Assign a phase, owner, dependencies, and timeline before adding to the table.

---

## 4. Milestone Tracker

Key milestones mark the completion of significant phases or deliverables. These are the checkpoints to review in leadership status meetings. Update the Actual Date column as each milestone is reached.

To set target dates, count forward from the project start date using the week numbers in the Action Plan. For example, if Week 1 begins on [Project Start Date], then a milestone targeted for Week 6 falls on [Project Start Date + 5 weeks].

| Milestone | Target Date | Actual Date | Status |
|---|---|---|---|
| AIMS Owner designated | [YYYY-MM-DD] | | [ ] Not Reached |
| AI Policy approved by management | [YYYY-MM-DD] | | [ ] Not Reached |
| AI System Inventory complete | [YYYY-MM-DD] | | [ ] Not Reached |
| Risk Assessment complete | [YYYY-MM-DD] | | [ ] Not Reached |
| Impact Assessments complete (high-risk systems) | [YYYY-MM-DD] | | [ ] Not Reached |
| Statement of Applicability approved | [YYYY-MM-DD] | | [ ] Not Reached |
| All critical gaps closed | [YYYY-MM-DD] | | [ ] Not Reached |
| AI awareness training delivered to all staff | [YYYY-MM-DD] | | [ ] Not Reached |
| Internal audit complete | [YYYY-MM-DD] | | [ ] Not Reached |
| Management review complete | [YYYY-MM-DD] | | [ ] Not Reached |
| All internal audit corrective actions closed | [YYYY-MM-DD] | | [ ] Not Reached |
| Stage 1 audit complete | [YYYY-MM-DD] | | [ ] Not Reached |
| Stage 1 findings closed | [YYYY-MM-DD] | | [ ] Not Reached |
| Stage 2 audit complete (certification granted) | [YYYY-MM-DD] | | [ ] Not Reached |

---

## 5. Resource Requirements

The estimates below reflect typical SMB engagements. Adjust based on the client's actual gap profile and the number of AI systems in scope. Hours are per week during the phases where each role is most active.

Resource availability is the single most common reason AIMS implementations run over schedule. The estimates here are realistic minimums, not aspirational targets. If the AIMS Owner cannot commit 8 hours per week during active phases, the timeline needs to extend accordingly. It is better to set a realistic certification date at the start than to miss an aggressive one mid-engagement.

| Role | Active Phases | Estimated Hours/Week | Total Estimated Hours | Notes |
|---|---|---|---|---|
| **AIMS Owner** | All phases | 8–12 hrs/week | 120–180 hrs total | Highest sustained commitment; this role drives the entire implementation |
| **IT Lead** | Phases 1, 2, 3 | 4–6 hrs/week | 40–60 hrs total | Concentrated in inventory (Phase 1) and supplier assessments (Phase 3) |
| **HR** | Phase 3 | 2–4 hrs/week | 10–20 hrs total | Competency framework and training coordination |
| **Senior Management** | Phases 1, 5, 6 | 1–2 hrs/week | 8–12 hrs total | Policy approvals, management review, and certification decisions |
| **Department Heads** | Phase 1 | 1–2 hrs/week | 4–8 hrs total | AI inventory input and shadow AI discovery |
| **Internal Auditor** | Phase 5 | 8–12 hrs/week during audit | 16–24 hrs total | Can be the consultant if no qualified internal resource is available |
| **External Consultant** | All phases | Per SOW | Per SOW | Facilitation, documentation review, audit preparation, and Stage 1 support |

**Total internal resource commitment (excluding consultant):** approximately 200–300 hours across the full implementation. For a 16-week engagement, this averages 12–19 hours per week across all internal roles combined.

*These estimates assume a single-site SMB with 3–8 AI systems in scope. Organizations with more AI systems, multiple locations, or complex supplier relationships should expect higher resource requirements.*

### 5.1 Making the Case for Internal Resource Commitment

Clients sometimes push back on the resource estimates, particularly for the AIMS Owner role. The framing that tends to work: ISO 42001 certification is not a project the consultant does for the client. It is a project the client does with consultant support. The certification body is certifying the client's management system, not the consultant's work product. The AIMS Owner needs to understand, own, and be able to explain every element of the AIMS. That requires genuine engagement, not just review and sign-off.

For clients who genuinely cannot free up an AIMS Owner at the required commitment level, two options exist: extend the timeline to reduce the weekly hours required, or bring in a fractional AIMS Owner resource to supplement internal capacity. Both are preferable to proceeding with an under-resourced implementation that produces a management system the client doesn't understand and can't maintain.

---

## 6. Risks to Roadmap

The following risks could delay the implementation timeline or reduce the quality of AIMS outputs. Review this table at each phase gate and update likelihood and status as the engagement progresses.

Likelihood and impact ratings use a simple three-point scale: Low / Medium / High. Update these ratings as the engagement progresses. A risk that was Low likelihood at kickoff may become Medium by Week 6 if early warning signs appear.

| Risk | Likelihood | Impact | Mitigation |
|---|---|---|---|
| **Key personnel unavailability** — AIMS Owner or IT Lead is pulled into other priorities, reducing time available for AIMS work | Medium | High | Establish a backup contact for each critical role at project kickoff; build buffer weeks into the schedule for Phases 2 and 3 |
| **Vendor non-cooperation with supplier assessments** — AI vendors decline to complete questionnaires or provide insufficient responses | Medium | Medium | Begin supplier outreach early (Week 4); use contractual leverage where available; document non-responses as a risk in the Risk Assessment Register |
| **Scope expansion** — additional AI systems are discovered during inventory or internal audit that were not identified during gap analysis | Medium | Medium | Treat newly discovered systems as a normal part of the process; assess and classify them promptly; adjust the risk assessment and SoA if needed |
| **Leadership disengagement** — senior management approves the project but does not actively participate in reviews and decisions | Low | High | Set expectations at kickoff that management review and policy approvals require active participation, not just sign-off; schedule these sessions in advance |
| **Documentation backlog** — internal team falls behind on producing required documented information, creating a bottleneck before the internal audit | Medium | High | Review documentation status weekly from Week 6 onward; identify gaps early enough to address them before Phase 5 |
| **Certification body scheduling delays** — preferred certification body cannot schedule Stage 1 audit within the target window | Low | Medium | Contact the certification body to discuss scheduling no later than Week 10; do not wait until documentation is complete to initiate contact |
| **Corrective action volume from internal audit** — internal audit raises more nonconformities than expected, requiring more time to close | Low | High | Build two weeks of buffer between the internal audit completion and the Stage 1 audit date; do not schedule Stage 1 before the internal audit is complete |

### 6.1 Escalation Protocol

When a risk materializes and threatens the timeline, escalate promptly. The escalation path is:

1. **AIMS Owner** identifies the issue and assesses impact on the schedule.
2. **Consultant** and AIMS Owner agree on a revised timeline or mitigation approach.
3. **Senior Management** is informed if the certification date needs to move or if additional resources are required.

Do not absorb schedule slippage silently. A two-week delay identified in Week 4 is manageable. The same delay identified in Week 12 may require rescheduling the Stage 1 audit.

---

## 7. Document Index Reference

The table below maps each major AIMS document to its document ID and the phase in which it is produced. Use this as a checklist when preparing for the Stage 1 audit. Every document listed as required must exist, be approved, and be version-controlled before the Stage 1 audit proceeds.

| Document | Document ID | Phase Produced | Required for Stage 1 |
|---|---|---|---|
| AIMS Scope Statement | AIMS-SCOPE-001 | Phase 1 | Yes |
| AI Policy | AIMS-POL-001 | Phase 1 | Yes |
| Acceptable Use Policy | AIMS-AUP-001 | Phase 1 | Yes |
| AI System Inventory | AIMS-INV-001 | Phase 1 | Yes |
| AI Risk Assessment Register | AIMS-RISK-001 | Phase 2 | Yes |
| Impact Assessment(s) | AIMS-IA-001 (per system) | Phase 2 | Yes (for high-risk systems) |
| Statement of Applicability | AIMS-SOA-001 | Phase 2 | Yes |
| Risk Treatment Plan | AIMS-RTP-001 | Phase 3 | Yes |
| Supplier Assessment Records | AIMS-SUPP-001 (per vendor) | Phase 3 | Yes (for priority vendors) |
| AI Competency Framework | AIMS-COMP-001 | Phase 3 | Yes |
| Training Records | AIMS-TRAIN-001 | Phase 3 | Yes |
| NCAR Log and Process | AIMS-NCAR-001 | Phase 3 | Yes |
| Monitoring and Measurement Procedure | AIMS-MON-001 | Phase 4 | Yes |
| Document Control Procedure | AIMS-DOC-001 | Phase 4 | Yes |
| Internal Audit Plan and Report | AIMS-AUD-001 | Phase 5 | Yes |
| Management Review Minutes | AIMS-MR-001 | Phase 5 | Yes |
| Corrective Action Records | AIMS-CA-001 | Phase 5 | Yes |

*Document IDs follow the AIMS-[TYPE]-[NUMBER] convention. Adjust to match the client's existing document numbering system if one is already in use.*

---

## 8. Version History

| Version | Date | Author | Changes |
|---|---|---|---|
| 1.0 | [YYYY-MM-DD] | [Name] | Initial version |
| | | | |

---

*ISO 42001 Readiness Service Toolkit | 03-Remediation | Confidential Client Deliverable*
