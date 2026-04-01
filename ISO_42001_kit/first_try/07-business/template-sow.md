# Statement of Work — ISO/IEC 42001:2023 AI Management System Readiness

> **Current as of:** March 2026 | ISO/IEC 42001:2023

---

> **HOW TO CUSTOMIZE THIS TEMPLATE — READ BEFORE USING**
>
> This Statement of Work formalizes the engagement described in the proposal. It is a binding contract document. Do not send it to a client until your firm's legal counsel has reviewed the terms.
>
> **Customization steps:**
>
> 1. **Replace every `[PLACEHOLDER]` field** with the correct value. Search the document for `[` to find them all. Do not leave any placeholder in the final version.
> 2. **Select the correct phase scope.** If the client is purchasing Phases 1–2 only, delete Phases 3–5 from Section 4 and adjust the schedule, fees, and RACI accordingly.
> 3. **Adjust the deliverable list** in Section 4 to match exactly what was agreed in the proposal. Remove any deliverables that are not in scope.
> 4. **Fill in the fee structure** in Section 11 based on the agreed investment from the proposal. Do not leave fee fields blank.
> 5. **Confirm the schedule dates** in Section 8 are realistic given the agreed start date and client resource availability.
> 6. **Delete this instruction block** before sending to the client.
>
> **Terminology note:** Terms used in this document follow the ISO 42001 Readiness Service Toolkit glossary. Key terms: *AI system* (the engineered system), *AI tool* (the user-facing product), *AI user* (the client's role), *AIMS* (AI Management System), *SoA* (Statement of Applicability). Consistent terminology matters; auditors notice discrepancies across documents.
>
> **Conversion:** Export to Word or PDF using Pandoc before client delivery. See `00-foundation/README.md` for conversion instructions.

---

## Document Information

| Field | Value |
|---|---|
| **Document Title** | Statement of Work — ISO/IEC 42001:2023 AI Management System Readiness |
| **SOW Reference** | [SOW-YYYY-NNN, e.g., SOW-2026-001] |
| **Version** | [VERSION NUMBER, e.g., 1.0] |
| **Effective Date** | [DATE BOTH PARTIES SIGN] |
| **Prepared By** | [CONSULTANT NAME / FIRM NAME] |
| **Prepared For** | [CLIENT ORGANIZATION NAME] |
| **Related Proposal** | [PROPOSAL REFERENCE NUMBER AND DATE] |
| **Confidentiality** | Confidential — prepared exclusively for [CLIENT ORGANIZATION NAME]. Not for distribution. |

---

## 1. Parties

**Service Provider**

| Field | Value |
|---|---|
| **Legal Name** | [FIRM LEGAL NAME] |
| **Trading Name (if different)** | [TRADING NAME] |
| **Registered Address** | [ADDRESS] |
| **Primary Contact** | [LEAD CONSULTANT NAME], [TITLE] |
| **Email** | [EMAIL ADDRESS] |
| **Phone** | [PHONE NUMBER] |

**Client**

| Field | Value |
|---|---|
| **Legal Name** | [CLIENT LEGAL NAME] |
| **Trading Name (if different)** | [TRADING NAME] |
| **Registered Address** | [ADDRESS] |
| **Primary Contact** | [CLIENT SPONSOR NAME], [TITLE] |
| **Project Manager** | [CLIENT PM NAME], [TITLE] |
| **Email** | [EMAIL ADDRESS] |
| **Phone** | [PHONE NUMBER] |

This Statement of Work is entered into by the parties identified above and is governed by the terms set out herein. Where this SOW conflicts with any prior proposal or correspondence, this SOW takes precedence.

---

## 2. Engagement Overview

This engagement provides ISO/IEC 42001:2023 AI Management System readiness services to [CLIENT ORGANIZATION NAME] as described in Proposal [PROPOSAL REFERENCE], dated [PROPOSAL DATE].

[CLIENT ORGANIZATION NAME] is an AI user organization: it uses third-party AI systems for business purposes but does not develop or train AI models. This distinction shapes the entire engagement. A significant portion of ISO 42001's development-focused Annex A controls will be formally excluded from the AIMS scope, keeping the compliance burden proportionate to the organization's actual risk profile.

The engagement covers [SELECTED PHASES, e.g., "all five service phases from Discovery through Certification Audit Support" or "Phases 1 and 2 (Discovery and Gap Analysis)"]. The objective is [ENGAGEMENT OBJECTIVE, e.g., "to establish a certified AI Management System that demonstrates responsible AI governance to customers, regulators, and other interested parties" or "to produce a comprehensive gap analysis and prioritized remediation roadmap"].

**Engagement start date:** [START DATE]

**Target completion date:** [TARGET COMPLETION DATE]

---

## 3. Out of Scope

The following are explicitly excluded from this engagement. Any request to perform out-of-scope work will be handled through the change management process in Section 12.

| Exclusion | Notes |
|---|---|
| AI system development, configuration, or fine-tuning | The client's AI tools are vendor-provided. Configuration of those tools is the client's or vendor's responsibility. |
| Legal advice or regulatory compliance opinions | Regulatory determinations require qualified legal counsel. This engagement produces governance documentation, not legal opinions. |
| Certification body fees | CB fees are billed directly by the certification body to the client. |
| Post-certification surveillance audit support | Available as a separate engagement upon request. |
| Tool-specific technical configuration | Guidance on configuring specific AI products (e.g., Microsoft Copilot data governance settings) is outside scope. |
| Industry-specific regulatory compliance | Sector-specific requirements (e.g., financial services AI regulations, healthcare AI rules) require specialist advice. |
| IT security assessments or penetration testing | AIMS implementation does not include technical security testing. |
| Vendor contract negotiation | Reviewing or negotiating contracts with AI providers is outside scope. |

---

## 4. Scope of Services

### Phase 1: Discovery and Scoping

**Objective:** Establish a complete, accurate picture of [CLIENT ORGANIZATION NAME]'s AI use, organizational context, and interested parties. Define the AIMS scope.

**Entry criteria:** Signed SOW. Client has designated a project lead and confirmed stakeholder availability for workshops.

**Duration:** 1–2 weeks

**Activities:**

- Stakeholder identification and mapping: documenting all interested parties (employees, customers, regulators, AI providers, and others) who can affect or be affected by the organization's AI use
- AI system inventory workshop: identifying all AI tools in use, their business purpose, data inputs, and the organizational functions that depend on them
- Context of the organization assessment: documenting internal factors (culture, governance structures, existing capabilities) and external factors (regulatory requirements, market conditions, supplier relationships) that affect the AIMS
- AIMS scope definition: establishing the organizational boundaries, locations, and AI systems covered by the management system
- Initial identification of applicable legal, regulatory, and contractual requirements

**Deliverables:**

| Deliverable | Description | Acceptance Criteria |
|---|---|---|
| AI System Inventory | Documented register of all in-scope AI systems, including tool name, vendor, business function, data inputs, and risk classification | Client confirms all known AI tools are captured; no material omissions |
| Stakeholder Register | Documented list of interested parties with their relevance to the AIMS | Client sponsor reviews and confirms completeness |
| AIMS Scope Document | Formal document defining the boundaries and applicability of the management system, per ISO 42001 Clause 4.3 | Client sponsor signs off; document is suitable for submission to certification body |
| Phase 1 Summary Report | Summary of discovery findings, context assessment, and any early risk observations | Client acknowledges receipt and raises any factual corrections within 5 business days |

**Exit criteria:** Client sponsor has signed the AIMS Scope Document. Phase 1 Summary Report delivered and acknowledged.

---

### Phase 2: Gap Analysis

**Objective:** Assess [CLIENT ORGANIZATION NAME]'s current state against every applicable ISO 42001 requirement and produce a prioritized gap register.

**Entry criteria:** Signed AIMS Scope Document from Phase 1. Client has made relevant documentation available (existing policies, procedures, records).

**Duration:** 2–3 weeks

**Activities:**

- Clause-by-clause assessment of ISO 42001 requirements (Clauses 4 through 10): leadership, planning, support, operations, performance evaluation, and improvement
- Annex A control evaluation: identifying which controls apply to an AI user organization and assessing current compliance for each applicable control
- Interviews with process owners and AI tool users
- Review of existing policies, procedures, and records relevant to AI governance
- Gap severity classification: major gap (requirement not met, significant remediation required), minor gap (partial compliance, targeted remediation required), or observation (improvement opportunity, not a compliance failure)
- Preliminary SoA development: identifying applicable and excluded controls with initial justification

**Deliverables:**

| Deliverable | Description | Acceptance Criteria |
|---|---|---|
| Gap Analysis Workbook | Clause-by-clause and control-by-control findings, including current state, gap description, severity, and recommended remediation approach | All applicable clauses and controls assessed; no blank rows |
| Gap Analysis Report | Executive summary, prioritized findings, and recommended remediation sequence | Client sponsor reviews and confirms findings reflect the organization's actual state; factual corrections raised within 5 business days |
| Preliminary Statement of Applicability | Draft SoA identifying applicable and excluded Annex A controls with initial justification | Covers all Annex A controls; exclusions are justified by reference to the AI user role |

**Exit criteria:** Gap Analysis Report delivered and acknowledged. Client has reviewed findings and confirmed accuracy.

*Note: For engagements scoped to Phases 1–2 only, the engagement concludes here. The Gap Analysis Report and a remediation roadmap are the final deliverables.*

---

### Phase 3: Remediation and Implementation

**Objective:** Build the AIMS. Close the gaps identified in Phase 2 by developing the policies, procedures, records, and governance structures ISO 42001 requires.

**Entry criteria:** Gap Analysis Report acknowledged. Client has confirmed resource availability for document review and approval cycles.

**Duration:** 4–8 weeks

**Activities:**

- Policy development: AI use policy, acceptable use guidelines, AI provider assessment policy, and others identified in the gap register
- Procedure development: AI system onboarding procedure, risk assessment procedure, incident identification and response procedure, corrective action procedure, and others as required by the gap register
- Risk assessment: applying the risk methodology to each in-scope AI system, producing the initial AI risk register
- Risk treatment planning: selecting and documenting controls for identified risks, feeding into the SoA
- SoA finalization: documenting all applicable Annex A controls, exclusions, and justifications
- Roles and responsibilities documentation: defining accountability for AI governance within the organization
- Awareness and training: developing and delivering AI governance awareness content for relevant staff
- Documented information controls: establishing version control, review cycles, and access controls for AIMS documentation

**Deliverables:**

| Deliverable | Description | Acceptance Criteria |
|---|---|---|
| AIMS Policy Set | Complete set of required policies, including AI use policy and acceptable use guidelines | Covers all policy requirements identified in the gap register; reviewed and approved by client management |
| AIMS Procedure Set | Complete set of required procedures, including risk assessment, incident response, and corrective action procedures | Covers all procedure requirements identified in the gap register; reviewed by relevant process owners |
| AI Risk Register | Documented assessment of risks associated with each in-scope AI system | All in-scope AI systems assessed; risk ratings and treatment decisions documented |
| Risk Treatment Plan | Documented plan for addressing identified risks, including selected controls and implementation owners | Aligned with SoA; treatment decisions approved by client management |
| Statement of Applicability (final) | Final SoA documenting all applicable and excluded Annex A controls with justification | All controls addressed; exclusions justified; signed by client management |
| Roles and Responsibilities Matrix | Document defining AI governance accountability within the organization | Reviewed and accepted by client management |
| Training Completion Records | Evidence that relevant staff have received AI governance awareness training | Records cover all staff identified as requiring training |
| Documented Information Register | Register of all AIMS documents and records, with version, owner, and review cycle | All AIMS documents listed; version control applied |

**Exit criteria:** All deliverables reviewed and accepted by client. SoA signed by client management. Training records complete.

---

### Phase 4: Pre-Audit Readiness Review

**Objective:** Stress-test the AIMS before the certification body arrives. Identify and close any remaining gaps.

**Entry criteria:** Phase 3 complete. All AIMS documentation finalized and approved. Client has confirmed availability for internal audit activities and management review.

**Duration:** 2–3 weeks

**Activities:**

- Internal audit planning and execution: covering all in-scope clauses and applicable Annex A controls, simulating the approach a certification auditor would take
- Evidence review: confirming that records exist to support each documented procedure and control
- Nonconformity identification and corrective action initiation for any findings
- Management review facilitation: preparing the agenda, inputs, and outputs required by ISO 42001 Clause 9.3
- Readiness checklist completion: a structured assessment of certification readiness across all AIMS elements
- Auditor question simulation: preparing key personnel for the types of questions a Stage 1 and Stage 2 auditor will ask

**Deliverables:**

| Deliverable | Description | Acceptance Criteria |
|---|---|---|
| Internal Audit Report | Findings from the internal audit, including any nonconformities and observations | All in-scope clauses and controls covered; findings documented with evidence references |
| Corrective Action Register | Documented corrective actions for any nonconformities identified during the internal audit | All nonconformities have assigned owners and target closure dates |
| Management Review Record | Formal record of the management review meeting, including inputs reviewed and decisions made | Meets ISO 42001 Clause 9.3 requirements; signed by top management |
| Certification Readiness Checklist | Structured assessment of readiness across all AIMS elements | All checklist items addressed; any open items have documented remediation plans |
| Pre-Audit Briefing Document | Guidance for client personnel who will participate in the certification audit | Covers Stage 1 and Stage 2 process, likely auditor questions, and evidence locations |

**Exit criteria:** Internal audit complete. All major nonconformities closed or have documented remediation plans. Management review record signed. Client management confirms readiness to proceed to certification.

---

### Phase 5: Certification Audit Support

**Objective:** Support [CLIENT ORGANIZATION NAME] through Stage 1 and Stage 2 certification audits and through any post-audit nonconformity response.

**Entry criteria:** Phase 4 complete. Certification body selected and audit dates confirmed.

**Duration:** 2–4 weeks

**Activities:**

- Certification body selection: identifying accredited CBs with ISO 42001 competence, comparing scope and pricing, and supporting the application process
- Stage 1 preparation: ensuring all required documented information is complete and accessible for the document review
- Stage 1 attendance and debrief: attending the Stage 1 audit in an advisory capacity, reviewing any findings, and confirming readiness for Stage 2
- Stage 2 preparation: addressing any Stage 1 findings, confirming evidence availability, and briefing audit participants
- Stage 2 attendance and debrief: attending the Stage 2 audit in an advisory capacity
- Nonconformity response support: if the auditor raises nonconformities, supporting the preparation of root cause analysis and corrective action plans within the certification body's required timeframe

**Deliverables:**

| Deliverable | Description | Acceptance Criteria |
|---|---|---|
| Certification Body Selection Summary | Comparison of accredited CBs with recommendation | Client selects preferred CB and confirms |
| Stage 1 Submission Package | All required documented information prepared for Stage 1 document review | Complete and accessible; no missing required documents |
| Stage 1 Findings Response | Response to any findings raised during Stage 1 (if applicable) | Addresses all Stage 1 findings; accepted by certification body |
| Stage 2 Preparation Checklist | Confirmation that all evidence is in place and personnel are briefed for Stage 2 | All checklist items complete before Stage 2 date |
| Nonconformity Response Documentation | Root cause analysis and corrective action plans for any nonconformities raised during Stage 2 (if applicable) | Submitted within certification body's required timeframe; accepted by CB |

**Exit criteria:** Stage 2 audit complete. Any nonconformities have documented responses submitted to the certification body. Certification decision received.

---

## 5. Deliverable Summary

The following table lists all deliverables across the engagement. Deliverables marked with an asterisk (*) require formal client sign-off before the engagement proceeds to the next phase.

| Phase | Deliverable |
|---|---|
| 1 | AI System Inventory |
| 1 | Stakeholder Register |
| 1 | AIMS Scope Document * |
| 1 | Phase 1 Summary Report |
| 2 | Gap Analysis Workbook |
| 2 | Gap Analysis Report |
| 2 | Preliminary Statement of Applicability |
| 3 | AIMS Policy Set |
| 3 | AIMS Procedure Set |
| 3 | AI Risk Register |
| 3 | Risk Treatment Plan |
| 3 | Statement of Applicability (final) * |
| 3 | Roles and Responsibilities Matrix |
| 3 | Training Completion Records |
| 3 | Documented Information Register |
| 4 | Internal Audit Report |
| 4 | Corrective Action Register |
| 4 | Management Review Record * |
| 4 | Certification Readiness Checklist |
| 4 | Pre-Audit Briefing Document |
| 5 | Certification Body Selection Summary |
| 5 | Stage 1 Submission Package |
| 5 | Stage 1 Findings Response (if applicable) |
| 5 | Stage 2 Preparation Checklist |
| 5 | Nonconformity Response Documentation (if applicable) |

---

## 6. Roles and Responsibilities

The following matrix defines accountability for key engagement activities. Roles: **R** = Responsible (does the work), **A** = Accountable (owns the outcome), **C** = Consulted (provides input), **I** = Informed (receives updates).

| Activity | Lead Consultant | Client Sponsor | Client PM | Client Subject Matter Experts |
|---|---|---|---|---|
| Engagement planning and scheduling | R/A | C | C | I |
| Stakeholder identification | R | A | C | C |
| AI system inventory workshops | R | A | C | R |
| Context of the organization assessment | R | A | C | C |
| AIMS scope definition | R | A | C | C |
| Gap analysis interviews | R | A | C | R |
| Gap analysis documentation | R/A | C | I | I |
| Policy and procedure drafting | R/A | C | I | C |
| Policy and procedure review and approval | C | A | R | C |
| Risk assessment | R | A | C | C |
| Risk treatment decisions | C | A | R | C |
| SoA finalization | R | A | C | C |
| Staff awareness training delivery | R/A | C | C | I |
| Internal audit execution | R/A | C | C | C |
| Management review facilitation | R | A | C | I |
| Management review sign-off | I | A/R | I | I |
| Certification body selection | R | A | C | I |
| Stage 1 and Stage 2 audit attendance | R | A | R | C |
| Nonconformity response preparation | R | A | C | C |
| Weekly status reporting | R/A | I | C | I |

---

## 7. Client Obligations

The engagement's success depends on the client's active participation. The following obligations are conditions of this SOW. Failure to meet these obligations may affect timelines and is subject to the change management process in Section 12.

**Personnel access.** [CLIENT ORGANIZATION NAME] will make the following personnel available for workshops, interviews, and review activities:

- A designated project lead with approximately [X] hours per week of availability throughout the engagement
- The client sponsor (or delegate) for phase sign-off activities and management review
- Process owners and AI tool users for Phase 1 and Phase 2 workshops and interviews, as scheduled with reasonable advance notice

**Documentation access.** [CLIENT ORGANIZATION NAME] will provide access to:

- Existing policies, procedures, and records relevant to AI governance
- Contracts and terms of service with AI system vendors
- Any existing risk assessments, audit reports, or compliance documentation
- Organizational charts and role descriptions relevant to AI governance accountability

**Management time.** Senior management will participate in:

- The Phase 1 kickoff meeting
- Phase 2 gap analysis debrief
- Phase 3 policy and procedure review and approval
- Phase 4 management review (required by ISO 42001 Clause 9.3)
- Phase 5 certification audit (Stage 1 and Stage 2)

**Timely review and feedback.** [CLIENT ORGANIZATION NAME] will review deliverables and provide feedback or sign-off within [5] business days of delivery, unless otherwise agreed. Delays in review that affect the project schedule will be documented and may require schedule adjustment.

**Accurate information.** [CLIENT ORGANIZATION NAME] will provide accurate and complete information about its AI systems, governance practices, and organizational context. The quality of deliverables depends on the accuracy of information provided.

---

## 8. Project Schedule

The following milestone table reflects the agreed engagement timeline. All dates are subject to the client meeting the obligations in Section 7.

| Milestone | Target Date | Owner |
|---|---|---|
| SOW signed by both parties | [DATE] | Both parties |
| Kickoff meeting | [DATE] | Lead Consultant |
| Phase 1 workshops complete | [DATE] | Lead Consultant |
| AIMS Scope Document delivered | [DATE] | Lead Consultant |
| AIMS Scope Document signed off | [DATE] | Client Sponsor |
| Phase 2 interviews complete | [DATE] | Lead Consultant |
| Gap Analysis Report delivered | [DATE] | Lead Consultant |
| Gap Analysis Report acknowledged | [DATE] | Client Sponsor |
| Phase 3 documentation drafts delivered | [DATE] | Lead Consultant |
| Phase 3 documentation approved | [DATE] | Client Sponsor |
| SoA signed | [DATE] | Client Sponsor |
| Phase 4 internal audit complete | [DATE] | Lead Consultant |
| Management review complete | [DATE] | Client Sponsor |
| Certification body application submitted | [DATE] | Client PM |
| Stage 1 audit | [DATE] | Certification Body |
| Stage 2 audit | [DATE] | Certification Body |
| Certification decision | [DATE] | Certification Body |

**Note:** Certification body scheduling is outside the control of either party. Stage 1 and Stage 2 dates are indicative and will be confirmed once the certification body is engaged.

---

## 9. Communication Plan

**Weekly status updates.** The Lead Consultant will provide a written status update every [DAY OF WEEK]. The update will cover work completed in the prior week, work planned for the coming week, any risks or issues, and any decisions or actions required from the client.

**Status calls.** [FREQUENCY, e.g., "Bi-weekly"] status calls will be held between the Lead Consultant and the Client PM. Duration: [30/60] minutes.

**Phase reviews.** At the end of each phase, the Lead Consultant will present findings and deliverables to the Client Sponsor. These sessions are scheduled in advance and require the Client Sponsor's attendance.

**Issue escalation.** Issues that cannot be resolved between the Lead Consultant and the Client PM will be escalated to the Client Sponsor within [2] business days. See Section 12 for scope change escalation.

**Primary communication channel:** [EMAIL / PROJECT MANAGEMENT TOOL]. All formal communications, deliverable submissions, and sign-off requests will be sent via [EMAIL] to the contacts identified in Section 1.

---

## 10. Intellectual Property

All deliverables produced under this SOW become the property of [CLIENT ORGANIZATION NAME] upon receipt of full payment for the phase in which they were produced.

The Service Provider retains ownership of any pre-existing methodologies, frameworks, templates, and tools used in producing the deliverables. The client receives a perpetual, non-exclusive license to use those elements as incorporated into the deliverables.

The Service Provider may reference the engagement in general terms (e.g., "we have supported organizations in [INDUSTRY] through ISO 42001 implementation") without disclosing the client's identity or any confidential information.

---

## 11. Fees and Payment

### Fee Structure

| Phase | Description | Fee |
|---|---|---|
| Phase 1 | Discovery and Scoping | [FEE] |
| Phase 2 | Gap Analysis | [FEE] |
| Phase 3 | Remediation and Implementation | [FEE] |
| Phase 4 | Pre-Audit Readiness Review | [FEE] |
| Phase 5 | Certification Audit Support | [FEE] |
| **Total** | **Full Engagement (Phases 1–5)** | **[TOTAL FEE]** |

*For engagements scoped to Phases 1–2 only, the total fee is [FEE].*

### What's Included

- All consultant time for activities and deliverables described in Section 4
- Up to [NUMBER] hours of email and call support between scheduled working sessions
- One round of revisions on each deliverable based on client feedback

### What's Not Included

- Certification body fees (billed directly by the CB to [CLIENT ORGANIZATION NAME])
- Travel expenses, if on-site work is required (billed at cost with prior written approval)
- Work outside the agreed scope (available at [HOURLY RATE] per hour with prior written agreement per Section 12)

### Payment Terms

[PAYMENT TERMS PLACEHOLDER, e.g., "50% of the total engagement fee is due upon execution of this SOW. The remaining 50% is due upon delivery of the final phase deliverables." Or: "Fees are invoiced monthly in arrears based on phases completed or substantially in progress."]

All fees are in [CURRENCY]. Invoices are due within [PAYMENT PERIOD] days of issue. Late payments accrue interest at [RATE]% per month after the due date.

---

## 12. Change Management

### What Constitutes a Scope Change

A scope change is any request to perform work not described in Section 4, add deliverables not listed in Section 5, extend the engagement timeline beyond the dates in Section 8 due to client-caused delays, or increase the number of AI systems in scope beyond those identified in Phase 1.

### Scope Change Process

1. Either party may identify a potential scope change and raise it in writing to the other party's primary contact.
2. The Lead Consultant will assess the impact on timeline and fees within [3] business days and provide a written Change Order describing the additional work, timeline impact, and additional fee.
3. The Client Sponsor must approve the Change Order in writing before any out-of-scope work begins.
4. Approved Change Orders become amendments to this SOW and are subject to the same payment terms.

Work performed without an approved Change Order is at the Service Provider's discretion and does not create an obligation for additional payment.

---

## 13. Confidentiality

Each party agrees to hold the other party's confidential information in strict confidence and not to disclose it to any third party without prior written consent, except as required by law or regulation.

**Confidential information** includes: the terms of this SOW, all deliverables produced under it, all information about the client's AI systems and governance practices, and any other information designated as confidential by the disclosing party.

**Exceptions:** Confidentiality obligations do not apply to information that is or becomes publicly available through no fault of the receiving party, was already known to the receiving party before disclosure, or is independently developed by the receiving party without reference to the confidential information.

This confidentiality obligation survives termination of this SOW for a period of [3] years.

---

## 14. Termination

**Termination for convenience.** Either party may terminate this SOW with [30] days' written notice. Upon termination, the client will pay for all work completed and deliverables produced up to the termination date, calculated on a pro-rata basis against the phase fees in Section 11.

**Termination for cause.** Either party may terminate this SOW immediately upon written notice if the other party materially breaches this SOW and fails to cure the breach within [15] business days of receiving written notice of the breach.

**Effect of termination.** Upon termination, the Service Provider will deliver all completed deliverables and work in progress to the client. The client will pay all outstanding invoices within [30] days of the termination date.

---

## 15. Limitation of Liability

The Service Provider's total liability under this SOW, whether in contract, tort, or otherwise, will not exceed the total fees paid by the client under this SOW in the [12] months preceding the event giving rise to the claim.

Neither party will be liable for indirect, consequential, incidental, or punitive damages, even if advised of the possibility of such damages.

---

## 16. Governing Law

This SOW is governed by the laws of [JURISDICTION]. Any disputes arising under this SOW will be resolved in the courts of [JURISDICTION], or through [ALTERNATIVE DISPUTE RESOLUTION MECHANISM, e.g., binding arbitration] if both parties agree.

---

## 17. Signatures

By signing below, both parties agree to the terms of this Statement of Work.

**Service Provider**

| Field | Value |
|---|---|
| **Authorized Signatory Name** | [NAME] |
| **Title** | [TITLE] |
| **Signature** | _________________________ |
| **Date** | [DATE] |

**Client**

| Field | Value |
|---|---|
| **Authorized Signatory Name** | [NAME] |
| **Title** | [TITLE] |
| **Signature** | _________________________ |
| **Date** | [DATE] |

---

## Legal Disclaimer

This SOW does not constitute legal advice. Regulatory compliance determinations, including obligations under the EU AI Act or other applicable law, require qualified legal counsel. ISO 42001 certification decisions are made by accredited certification bodies, not by consultants. Achieving certification depends on the organization meeting the standard's requirements as assessed by the certification body; no consultant can guarantee a certification outcome.

---

## Version History

| Version | Date | Author | Changes |
|---|---|---|---|
| 1.0 | [DATE] | [AUTHOR] | Initial version |
| | | | |

---

*ISO 42001 Readiness Service Toolkit | 07-Business | Client-Facing Template*
