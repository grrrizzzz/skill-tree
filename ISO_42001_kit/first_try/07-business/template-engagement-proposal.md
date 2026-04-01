# ISO/IEC 42001:2023 — AI Management System Readiness Assessment Proposal

> **Current as of:** March 2026 | ISO/IEC 42001:2023 | EU AI Act (Regulation 2024/1689) | NIST AI RMF 1.0

---

> **TEMPLATE INSTRUCTIONS — READ BEFORE USING**
>
> This document is a proposal template for ISO 42001 readiness engagements. It is designed for organizations that **use** third-party AI systems (ChatGPT, Microsoft Copilot, Salesforce Einstein, and similar tools) and need a structured AI Management System (AIMS) to govern that use.
>
> **How to customize this template:**
>
> 1. **Replace all `[PLACEHOLDER]` variables** with client-specific information. Every placeholder is listed in brackets and describes what goes there. Do not leave any placeholders in the final document sent to the client.
> 2. **Expand the "Understanding Your Organization" section** using notes from your discovery call. This is the section that makes the proposal feel tailored rather than generic. Spend time here.
> 3. **Select the appropriate service option** in the Investment section (Option A, B, or C) and remove or gray out the others if you're recommending a specific path.
> 4. **Fill in the Investment section fee ranges** based on your assessment of scope complexity, number of AI systems, and organizational size. Market reference: gap analysis engagements typically run $5K–$15K; full implementation $20K–$35K for SMBs.
> 5. **Update the Qualifications section** with your firm's specific credentials, certifications, and relevant case experience.
> 6. **Review the Scope section** and remove any line items that don't apply to this client's situation. The template lists the full range of possible scope items.
> 7. **Delete this instruction block** before sending to the client. Everything above this line is for internal use only.
>
> **Terminology note:** This template uses vocabulary from the ISO 42001 Readiness Service Toolkit glossary. Key terms: *AI system* (the engineered system), *AI tool* (the user-facing product like Copilot or ChatGPT), *AI user* (the client's role — they use, not build, AI), *AIMS* (AI Management System), *SoA* (Statement of Applicability). Consistent terminology matters; auditors notice when documentation uses the same terms differently across documents.
>
> **Conversion:** Export to Word or PDF using Pandoc before client delivery. See `00-foundation/README.md` for conversion instructions.

---

## Document Information

| Field | Value |
|---|---|
| **Document Title** | ISO/IEC 42001:2023 AI Management System Readiness Assessment Proposal |
| **Version** | [VERSION NUMBER, e.g., 1.0] |
| **Date** | [PROPOSAL DATE] |
| **Prepared For** | [CLIENT ORGANIZATION NAME] |
| **Attention** | [CLIENT CONTACT NAME], [TITLE] |
| **Prepared By** | [CONSULTANT NAME / FIRM NAME] |
| **Valid Until** | [EXPIRY DATE, typically 30–60 days from proposal date] |
| **Confidentiality** | Confidential — prepared exclusively for [CLIENT ORGANIZATION NAME]. Not for distribution. |

---

## Executive Summary

[CLIENT ORGANIZATION NAME] is using AI tools across its operations. That's not unusual. What is changing is the regulatory and governance environment around that use.

The EU AI Act (Regulation 2024/1689) takes effect for deployers on August 2, 2026. Organizations that deploy AI systems in the EU, or that process data belonging to EU residents, will face documented obligations around risk assessment, transparency, human oversight, and incident reporting. These are not aspirational guidelines. They are legal requirements with enforcement mechanisms.

ISO/IEC 42001:2023 is the international standard for AI Management Systems. It gives organizations a structured, auditable framework for governing AI use responsibly. Achieving certification against this standard does three things at once: it builds the internal governance infrastructure your organization needs, it provides documented evidence of due diligence for regulators and customers, and it maps directly to the EU AI Act's deployer obligations, so the work you do for certification isn't duplicated when compliance deadlines arrive.

[CLIENT ORGANIZATION NAME] currently uses approximately [NUMBER OF AI SYSTEMS] AI systems across [NUMBER OF BUSINESS FUNCTIONS] business functions. Based on our initial conversation, the primary governance gaps are [BRIEF SUMMARY OF KEY GAPS — e.g., "the absence of a formal AI inventory, no documented risk assessment process for third-party AI tools, and no defined accountability structure for AI-related decisions"]. These are addressable gaps. They are also the gaps most likely to attract auditor attention and regulatory scrutiny.

This proposal outlines a [PHASE 1-5 / PHASE 1-2] engagement to [establish a certified AI Management System / conduct a gap analysis and readiness assessment] for [CLIENT ORGANIZATION NAME]. The engagement is scoped specifically for an organization in your position: an AI user, not an AI developer, working with commercially available third-party tools rather than building models from scratch. That distinction matters for scoping, and it means a significant portion of ISO 42001's development-focused controls will be formally excluded from your AIMS, keeping the compliance burden proportionate to your actual risk profile.

---

## Understanding Your Organization

*This section is completed based on the discovery conversation and any materials the client has shared. It demonstrates that the proposal reflects the client's specific situation, not a generic template. Replace all bracketed content with actual client context.*

Based on our discussion on [DATE OF INITIAL CONVERSATION], we understand that [CLIENT ORGANIZATION NAME] is a [BRIEF DESCRIPTION, e.g., "mid-sized professional services firm with approximately 200 employees operating across three office locations"]. Your organization uses AI tools primarily in [PRIMARY USE AREAS, e.g., "customer-facing communications, internal knowledge management, and sales pipeline analysis"].

**AI tools currently in use:** [LIST THE SPECIFIC TOOLS IDENTIFIED, e.g., Microsoft Copilot (Microsoft 365 integration), Salesforce Einstein (CRM and lead scoring), ChatGPT Enterprise (content drafting and research)]. You have indicated that [ADDITIONAL CONTEXT, e.g., "two additional tools are under evaluation for deployment in the next six months"].

**Current governance state:** [CLIENT ORGANIZATION NAME] [DESCRIBE CURRENT STATE, e.g., "has no formal AI governance documentation in place. Individual teams have adopted AI tools independently, and there is no centralized inventory of which systems are in use or what data they process. Acceptable use guidance exists informally but has not been documented or communicated consistently"].

**Key drivers for this engagement:** [LIST THE CLIENT'S STATED MOTIVATIONS, e.g., "a customer contract requirement for documented AI governance, proactive preparation for EU AI Act compliance, and a board-level directive to formalize AI risk management before the end of the fiscal year"].

**Relevant existing frameworks:** [NOTE ANY EXISTING MANAGEMENT SYSTEMS OR COMPLIANCE PROGRAMS, e.g., "Your organization holds ISO 27001 certification. The AIMS we build will be designed to integrate with your existing ISMS structure, sharing documentation controls and management review processes where possible to minimize duplication"].

**Constraints and considerations:** [NOTE ANY CONSTRAINTS IDENTIFIED, e.g., "The engagement needs to complete before [DATE] to align with a customer audit. Internal resource availability is limited to approximately [X] hours per week from the designated project lead"].

---

## Proposed Scope

The following scope defines the boundaries of the AI Management System this engagement will establish. The scope document produced in Phase 1 will formalize these boundaries and become a required AIMS document.

**Organizational scope:** All AI-related activities conducted by [CLIENT ORGANIZATION NAME] at [LOCATION(S)], including activities performed by employees, contractors, and third parties acting on behalf of the organization.

**AI system scope:** All AI systems used by [CLIENT ORGANIZATION NAME] within the defined organizational boundary, as identified and documented during Phase 1 discovery. This includes third-party AI tools accessed through commercial subscriptions, APIs, or embedded product features.

**This engagement includes:**

- Establishment of an AI Management System (AIMS) framework aligned to ISO/IEC 42001:2023
- AI system inventory and classification (identifying all AI tools in use, their business functions, data inputs, and risk profiles)
- Gap analysis against all applicable ISO 42001 clauses (Clauses 4 through 10) and Annex A controls
- Risk assessment methodology development and initial AI risk register
- Policy and procedure development (AI use policy, acceptable use guidelines, vendor assessment procedure, incident response procedure, and others as required)
- Statement of Applicability (SoA) documenting which Annex A controls apply to your organization and why
- Internal audit process establishment and first internal audit
- Management review preparation and facilitation
- Pre-audit readiness review and remediation of any remaining gaps
- Certification body selection guidance and Stage 1 / Stage 2 audit support

**This engagement does not include:**

- Legal advice or regulatory compliance opinions
- Post-certification surveillance audit support (available as a separate engagement)
- IT security assessments or penetration testing
- AI system development, configuration, or vendor contract negotiation
- Certification body fees (billed directly by the certification body to [CLIENT ORGANIZATION NAME])

---

## Service Phases

### Phase 1: Discovery and Scoping

**Duration:** 1–2 weeks

**Objective:** Establish a complete, accurate picture of [CLIENT ORGANIZATION NAME]'s AI use, organizational context, and interested parties. Define the AIMS scope.

This phase is the foundation of the engagement. The quality of everything that follows depends on how thoroughly we understand your organization's AI footprint and governance context. We conduct structured discovery workshops with key stakeholders, review existing documentation, and produce a formal AI system inventory.

**Activities:**
- Stakeholder identification and mapping (employees, customers, regulators, AI providers, and other interested parties)
- AI system inventory workshop: identifying all AI tools in use, their business purpose, data inputs, and the organizational functions that depend on them
- Context of the organization assessment (internal and external factors affecting the AIMS)
- AIMS scope definition and documentation
- Initial identification of applicable legal, regulatory, and contractual requirements

**Deliverables:**
- AI System Inventory (documented register of all in-scope AI systems)
- Stakeholder Register
- AIMS Scope Document (draft, for client review and sign-off)
- Phase 1 Summary Report

---

### Phase 2: Gap Analysis

**Duration:** 2–3 weeks

**Objective:** Assess [CLIENT ORGANIZATION NAME]'s current state against every applicable ISO 42001 requirement and produce a prioritized gap register.

We evaluate your organization clause by clause against ISO 42001 (Clauses 4–10) and control by control against Annex A. For each requirement, we document the current state, identify the gap, assess its severity, and recommend a remediation approach. The output is a gap register that drives Phase 3.

**Activities:**
- Clause-by-clause assessment of ISO 42001 requirements (leadership, planning, support, operations, performance evaluation, improvement)
- Annex A control evaluation: identifying which controls apply to an AI user organization and assessing current compliance for each applicable control
- Interviews with process owners and AI tool users
- Review of existing policies, procedures, and records relevant to AI governance
- Gap severity classification (major gap, minor gap, observation)

**Deliverables:**
- Gap Analysis Workbook (clause-by-clause and control-by-control findings)
- Gap Analysis Report (executive summary, prioritized findings, recommended remediation sequence)
- Preliminary Statement of Applicability (draft, identifying applicable and excluded controls with justification)

*Note: For clients selecting Option B (Gap Analysis Only), the engagement concludes at the end of Phase 2 with a final Gap Analysis Report and a remediation roadmap the client can execute independently or with future support.*

---

### Phase 3: Remediation and Implementation

**Duration:** 4–8 weeks

**Objective:** Build the AIMS. Close the gaps identified in Phase 2 by developing the policies, procedures, records, and governance structures ISO 42001 requires.

This is the largest phase of the engagement. We work alongside your team to develop documentation that reflects how your organization actually operates, not generic templates that don't fit your context. The goal is an AIMS that your people will use and maintain, not a documentation set that exists only for the auditor.

**Activities:**
- Policy development: AI use policy, acceptable use guidelines, AI provider assessment policy, and others identified in the gap register
- Procedure development: AI system onboarding procedure, risk assessment procedure, incident identification and response procedure, corrective action procedure, and others as required
- Risk assessment: applying the risk methodology to each in-scope AI system, producing the initial AI risk register
- Risk treatment planning: selecting and documenting controls for identified risks
- Statement of Applicability (SoA) finalization: documenting all applicable Annex A controls, exclusions, and justifications
- Roles and responsibilities documentation: defining accountability for AI governance within the organization
- Awareness and training: developing and delivering AI governance awareness content for relevant staff
- Documented information controls: establishing version control, review cycles, and access controls for AIMS documentation

**Deliverables:**
- Complete AIMS Policy Set
- AIMS Procedure Set
- AI Risk Register
- Risk Treatment Plan
- Statement of Applicability (final)
- Roles and Responsibilities Matrix
- Training completion records
- Documented Information Register

---

### Phase 4: Pre-Audit Readiness Review

**Duration:** 2–3 weeks

**Objective:** Stress-test the AIMS before the certification body arrives. Identify and close any remaining gaps.

We conduct a structured internal audit of the AIMS, simulating the approach a certification auditor would take. We review documentation for completeness and consistency, test whether records exist to support documented procedures, and identify any areas where the AIMS says one thing but the evidence shows another. We also facilitate the first formal management review.

**Activities:**
- Internal audit planning and execution (covering all in-scope clauses and applicable Annex A controls)
- Evidence review: confirming that records exist to support each documented procedure and control
- Nonconformity identification and corrective action initiation for any findings
- Management review facilitation: preparing the agenda, inputs, and outputs required by Clause 9.3
- Readiness checklist completion: a structured assessment of certification readiness across all AIMS elements
- Auditor question simulation: preparing key personnel for the types of questions a Stage 1 and Stage 2 auditor will ask

**Deliverables:**
- Internal Audit Report
- Corrective Action Register (for any findings from the internal audit)
- Management Review Record
- Certification Readiness Checklist
- Pre-Audit Briefing Document (for client personnel who will participate in the certification audit)

---

### Phase 5: Certification Audit Support

**Duration:** 2–4 weeks

**Objective:** Support [CLIENT ORGANIZATION NAME] through Stage 1 and Stage 2 certification audits and through any post-audit nonconformity response.

We support the client through the certification process itself. This includes helping select an appropriate accredited certification body, preparing Stage 1 documentation submissions, attending Stage 1 and Stage 2 audits in an advisory capacity, and supporting the preparation of nonconformity responses if findings are raised.

**Activities:**
- Certification body selection: identifying accredited CBs with ISO 42001 competence, comparing scope and pricing, and supporting the application process
- Stage 1 preparation: ensuring all required documented information is complete and accessible for the document review
- Stage 1 attendance and debrief: attending the Stage 1 audit in an advisory capacity, reviewing any findings, and confirming readiness for Stage 2
- Stage 2 preparation: addressing any Stage 1 findings, confirming evidence availability, and briefing audit participants
- Stage 2 attendance and debrief: attending the Stage 2 audit in an advisory capacity
- Nonconformity response support: if the auditor raises nonconformities, supporting the preparation of root cause analysis and corrective action plans within the certification body's required timeframe

**Deliverables:**
- Certification Body Selection Summary
- Stage 1 Submission Package
- Stage 1 Findings Response (if applicable)
- Stage 2 Preparation Checklist
- Nonconformity Response Documentation (if applicable)

---

## Timeline

The table below shows indicative durations for each phase. Actual timelines depend on client resource availability, the number of AI systems in scope, and the complexity of gaps identified in Phase 2.

| Phase | Description | Duration | Key Milestone |
|---|---|---|---|
| **Phase 1** | Discovery and Scoping | 1–2 weeks | Signed AIMS Scope Document |
| **Phase 2** | Gap Analysis | 2–3 weeks | Gap Analysis Report delivered |
| **Phase 3** | Remediation and Implementation | 4–8 weeks | Complete AIMS documentation set |
| **Phase 4** | Pre-Audit Readiness Review | 2–3 weeks | Readiness Checklist signed off |
| **Phase 5** | Certification Audit Support | 2–4 weeks | Certification decision |
| **Total (Phases 1–5)** | Full Implementation | **11–20 weeks** | ISO 42001 certification |
| **Total (Phases 1–2)** | Gap Analysis Only | **3–5 weeks** | Gap Analysis Report and roadmap |

**Estimated start date:** [PROPOSED START DATE]

**Target certification date (Option A):** [TARGET DATE, calculated from start date + 20 weeks maximum]

*Timeline assumes [CLIENT ORGANIZATION NAME] can provide a designated project lead with approximately [X] hours per week of availability, and that key stakeholders are accessible for workshops and interviews during Phase 1 and Phase 2.*

---

## Investment

### Option A: Full Implementation (Phases 1–5)

Complete engagement from initial discovery through certification audit support. Delivers a certified AI Management System.

**Investment:** [FEE RANGE]

---

### Option B: Gap Analysis Only (Phases 1–2)

Discovery, scoping, and a comprehensive gap analysis. Delivers a clear picture of where you stand today and a prioritized roadmap for achieving certification. Suitable for organizations that want to understand the scope of work before committing to full implementation, or that have internal resources to execute remediation independently.

**Investment:** [FEE RANGE]

---

### Option C: Custom Scope

If your organization's needs don't fit neatly into Option A or Option B, we can scope an engagement around your specific situation. Examples include a Phase 3–5 engagement for organizations that have already completed a gap analysis, or a Phase 1–4 engagement for organizations that prefer to manage the certification body relationship directly.

**Investment:** To be discussed based on agreed scope.

---

### What's Included

- All consultant time for activities and deliverables described in the Service Phases section
- All client-facing deliverables listed under each phase
- Up to [NUMBER] hours of email and call support between scheduled working sessions
- One round of revisions on each deliverable based on client feedback

### What's Not Included

- Certification body fees (billed directly by the CB to [CLIENT ORGANIZATION NAME]; typically [REFERENCE RANGE] for SMB organizations)
- Travel expenses, if on-site work is required (billed at cost with prior approval)
- Legal advice or regulatory compliance opinions
- Work outside the agreed scope (available at [HOURLY RATE] with prior written agreement)

### Payment Terms

[PAYMENT TERMS PLACEHOLDER — e.g., "50% upon engagement commencement, 50% upon delivery of final Phase deliverables" or "Monthly invoicing in arrears based on work completed" or other terms per firm policy]

All fees are in [CURRENCY]. Invoices are due within [PAYMENT PERIOD] days of issue.

---

## Our Qualifications

[FIRM NAME] brings a combination of ISO management system implementation experience and AI domain knowledge that is directly relevant to this engagement.

**ISO management system experience:** [DESCRIBE RELEVANT EXPERIENCE, e.g., "We have supported more than [NUMBER] organizations through ISO management system implementations, including ISO 13485 (medical devices quality management), ISO 27001 (information security), and ISO 9001 (quality management). This experience means we understand how management systems work in practice, not just on paper, and how to build documentation that satisfies auditors without creating unnecessary operational burden."]

**AI domain knowledge:** [DESCRIBE AI EXPERTISE, e.g., "Our team has direct experience with the AI tools your organization uses, including [RELEVANT TOOLS]. We understand how these systems process data, what governance controls are available at the vendor level, and where the residual risks sit with the deploying organization. This knowledge shapes how we approach the AI inventory, risk assessment, and vendor assessment components of the engagement."]

**ISO 42001 specific experience:** [DESCRIBE ISO 42001 EXPERIENCE, e.g., "We have been working with ISO/IEC 42001:2023 since its publication and have [DESCRIBE RELEVANT ENGAGEMENTS OR TRAINING]. We maintain current knowledge of certification body interpretations and auditor expectations as the standard matures."]

**Relevant credentials:** [LIST RELEVANT CERTIFICATIONS, TRAINING, OR PROFESSIONAL MEMBERSHIPS]

---

## Cross-Framework Value

One engagement, multiple frameworks addressed.

ISO 42001 certification doesn't exist in isolation. For most organizations, it sits alongside EU AI Act obligations and, for US-facing operations, NIST AI RMF alignment. The work done to achieve ISO 42001 certification maps directly to requirements in both frameworks, which means the investment in this engagement delivers compliance value beyond the certificate itself.

**EU AI Act (Regulation 2024/1689):** The Act's deployer obligations, effective August 2, 2026, require organizations that deploy AI systems to conduct risk assessments, maintain documentation, implement human oversight measures, and report incidents. These requirements align closely with ISO 42001 Clauses 6, 8, and 9, and with Annex A controls covering risk management and operational governance. An organization with a functioning AIMS will have the documented evidence to demonstrate EU AI Act compliance without building a parallel compliance program.

**NIST AI Risk Management Framework 1.0:** The NIST AI RMF organizes AI risk management around four functions: Govern, Map, Measure, and Manage. ISO 42001's clause structure maps to all four functions. Organizations with US federal customers or contractors, or those that have adopted NIST frameworks for cybersecurity, will find that ISO 42001 certification provides a natural extension of their existing risk management approach.

The cross-framework mapping work is built into this engagement. The gap analysis in Phase 2 will identify not only ISO 42001 gaps but also the corresponding EU AI Act and NIST AI RMF implications, so [CLIENT ORGANIZATION NAME] has a complete picture of its multi-framework position from the start.

---

## Next Steps

If this proposal reflects your organization's needs, the next step is a brief scoping call to confirm the engagement parameters and agree on a start date.

**To proceed:**

1. Review this proposal and note any questions or scope adjustments
2. Contact [CONSULTANT NAME] at [EMAIL ADDRESS] or [PHONE NUMBER] to schedule a 30-minute scoping call
3. Upon agreement, we will issue a Statement of Work and engagement letter for signature

**Proposal valid until:** [EXPIRY DATE]

We're ready to start as soon as [PROPOSED START DATE]. Given the EU AI Act deployer deadline of August 2, 2026, organizations beginning a full implementation engagement in [CURRENT QUARTER] are well-positioned to achieve certification before that deadline.

---

## Terms and Conditions

[TERMS AND CONDITIONS PLACEHOLDER — Insert your firm's standard engagement terms here. At minimum, address the following: scope change process, intellectual property ownership of deliverables, confidentiality obligations, limitation of liability, dispute resolution, termination provisions, and governing law. Have these reviewed by qualified legal counsel before use.]

---

## Legal Disclaimer

This proposal does not constitute legal advice. Regulatory compliance determinations, including obligations under the EU AI Act or other applicable law, require qualified legal counsel. ISO 42001 certification decisions are made by accredited certification bodies, not by consultants. Achieving certification depends on the organization meeting the standard's requirements as assessed by the certification body; no consultant can guarantee a certification outcome.

---

## Version History

| Version | Date | Author | Changes |
|---|---|---|---|
| 1.0 | [DATE] | [AUTHOR] | Initial version |
| | | | |

---

*ISO 42001 Readiness Service Toolkit | 07-Business | Client-Facing Template*
