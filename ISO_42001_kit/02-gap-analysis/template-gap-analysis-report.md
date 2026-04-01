# Gap Analysis Report — ISO/IEC 42001:2023 AI Management System Readiness Assessment

> **Current as of:** March 2026 | ISO/IEC 42001:2023

---

> **HOW TO CUSTOMIZE THIS TEMPLATE**
>
> This block is for internal consultant use. Remove it before delivering the report to the client.
>
> **Step 1 — Replace all placeholders.** Search for `[` to find every placeholder. Replace each with client-specific content. Do not leave any placeholder in the final deliverable.
>
> **Step 2 — Complete Sections 5 and 6.** These sections contain `[TO BE COMPLETED]` markers for each clause group and Annex A domain. Fill in findings from the Gap Analysis Workbook (`template-gap-analysis-workbook.md`). Reference workbook row IDs (e.g., W-4.1-01) when citing specific findings.
>
> **Step 3 — Populate the Findings Summary table (Section 4).** The example rows are illustrative. Replace them with the actual findings from the workbook, sorted by severity.
>
> **Step 4 — Build the Remediation Roadmap (Section 7).** Sequence actions based on dependencies. Critical gaps blocking certification must appear first. Confirm timeline estimates with the client before finalizing.
>
> **Step 5 — Verify the Maturity Profile (Section 3).** Scores must match the workbook exactly. Double-check clause group averages before delivery.
>
> **Step 6 — Remove this instruction block.** Delete everything between the `> **HOW TO CUSTOMIZE` line and the closing `>` of this block before sending to the client.
>
> **Terminology note:** Use terms as defined in `00-foundation/glossary.md`. Key terms: AI Management System (AIMS), Statement of Applicability (SoA), AI System, AI User, Impact Assessment, Documented Information, Interested Parties.

---

## Document Metadata

| Field | Value |
|---|---|
| **Document Title** | Gap Analysis Report — ISO/IEC 42001:2023 AIMS Readiness Assessment |
| **Version** | [VERSION, e.g., 1.0] |
| **Date** | [REPORT DATE] |
| **Client** | [CLIENT NAME] |
| **Prepared By** | [CONSULTANT NAME], Skill Tree AI |
| **Assessment Period** | [START DATE] to [END DATE] |
| **Report Classification** | Confidential — For [CLIENT NAME] Internal Use Only |

---

> **Legal Disclaimer:** This report presents the findings of a readiness assessment conducted against the requirements of ISO/IEC 42001:2023. It is intended to support [CLIENT NAME]'s preparation for certification and to identify areas for improvement in AI governance practices. This report does not constitute legal advice. Certification decisions are made solely by accredited certification bodies following their own audit processes. References to the EU AI Act and other regulatory frameworks are provided for context only; organizations should consult qualified legal counsel regarding their specific regulatory obligations.

---

## Table of Contents

1. [Executive Summary](#1-executive-summary)
2. [Assessment Scope](#2-assessment-scope)
3. [Overall Maturity Profile](#3-overall-maturity-profile)
4. [Findings Summary](#4-findings-summary)
5. [Detailed Findings by Clause](#5-detailed-findings-by-clause)
6. [Detailed Findings by Annex A Domain](#6-detailed-findings-by-annex-a-domain)
7. [Remediation Roadmap](#7-remediation-roadmap-high-level)
8. [Risk Assessment of Current State](#8-risk-assessment-of-current-state)
9. [Next Steps](#9-next-steps)
10. [Appendices](#10-appendices)
11. [Version History](#11-version-history)

---

## 1. Executive Summary

### Assessment Overview

[CLIENT NAME] engaged [CONSULTANT NAME] / Skill Tree AI to conduct a readiness assessment against the requirements of ISO/IEC 42001:2023, the international standard for AI Management Systems. The assessment was conducted during [ASSESSMENT PERIOD] and covered [CLIENT NAME]'s use of AI systems within the scope defined in Phase 1 of this engagement.

The assessment evaluated [NUMBER] normative clause requirements (Clauses 4 through 10) and [NUMBER] Annex A controls applicable to [CLIENT NAME]'s role as an AI user organization. Evidence was gathered through document review, structured interviews with [NUMBER] personnel across [NUMBER] organizational units, and observation of current AI governance practices.

### Overall Maturity

The overall AIMS maturity score for [CLIENT NAME] is **[SCORE]/5**, against a certification readiness threshold of 3.0. This score reflects the current state of AI governance practices and is not a certification outcome.

*Example of a completed summary for reference:*

> Acme Corp was assessed against all applicable requirements of ISO/IEC 42001:2023 during Q1 2026. The assessment covered 47 normative clause requirements and 28 applicable Annex A controls. The overall maturity score is 1.8/5, with 3 critical gaps, 4 major gaps, and 6 minor gaps identified. With focused remediation over approximately 12 to 16 weeks, Acme Corp is well-positioned to achieve certification readiness. The organization demonstrates genuine commitment to responsible AI use and has existing governance infrastructure (an information security management system and a functioning risk management process) that provides a strong foundation for AIMS implementation.

### Key Findings

| Severity | Count | Summary |
|---|---|---|
| **Critical** | [N] | Gaps that must be resolved before certification can proceed |
| **Major** | [N] | Significant gaps that present material risk and require structured remediation |
| **Minor** | [N] | Gaps that need attention but do not block certification |
| **Observation** | [N] | Areas meeting minimum requirements with opportunities for improvement |

### Strengths Identified

[CLIENT NAME] demonstrated the following existing capabilities that provide a foundation for AIMS implementation:

- [STRENGTH 1 — e.g., "Established information security governance through existing ISO 27001 certification, providing a mature document control and internal audit framework that can be extended to AIMS requirements."]
- [STRENGTH 2 — e.g., "Active executive sponsorship for AI governance, with [ROLE] demonstrating clear understanding of the organization's AI risk profile."]
- [STRENGTH 3 — e.g., "Existing vendor management process that can be adapted to address third-party AI supply chain requirements."]

### Recommendation Summary

The assessment findings indicate that [CLIENT NAME] requires structured remediation before certification readiness can be achieved. The recommended approach prioritizes resolution of critical gaps (particularly the establishment of an AI policy, a formal risk assessment methodology, and AI system impact assessments) before addressing major and minor gaps. A detailed remediation roadmap is provided in Section 7.

With the remediation actions described in this report, [CLIENT NAME] is well-positioned to achieve ISO/IEC 42001:2023 certification readiness within [ESTIMATED TIMEFRAME].

---

## 2. Assessment Scope

### AIMS Scope Statement

The following scope statement was established during Phase 1 of this engagement and governs the boundaries of this assessment:

> [INSERT AIMS SCOPE STATEMENT FROM PHASE 1 SCOPE DOCUMENT]
>
> *Example: "The AI Management System of [CLIENT NAME] covers the procurement, deployment, and operational use of third-party AI systems used to support [BUSINESS FUNCTIONS] within [ORGANIZATIONAL UNITS] at [LOCATIONS]. The scope excludes AI systems used solely for internal IT infrastructure management and AI development activities."*

### AI Systems Included

The following AI systems were within scope for this assessment. Full inventory details are documented in the AI System Inventory produced during Phase 1.

| System ID | AI System Description | Business Function | Risk Classification |
|---|---|---|---|
| [AI-001] | [Description — e.g., "AI-assisted customer service platform"] | [Function] | [High / Medium / Low] |
| [AI-002] | [Description] | [Function] | [High / Medium / Low] |
| [AI-003] | [Description] | [Function] | [High / Medium / Low] |
| *[Add rows as needed]* | | | |

### Organizational Units Assessed

The following organizational units were included in the assessment:

- [UNIT 1 — e.g., Operations]
- [UNIT 2 — e.g., Customer Experience]
- [UNIT 3 — e.g., Human Resources]
- [UNIT 4 — e.g., IT / Technology]
- [UNIT 5 — e.g., Legal / Compliance]

### Standards and Frameworks Referenced

This assessment was conducted primarily against ISO/IEC 42001:2023. The following additional frameworks were referenced for context where noted:

| Framework | Relevance |
|---|---|
| **ISO/IEC 42001:2023** | Primary assessment standard — AI Management Systems |
| **ISO/IEC 22989:2022** | AI concepts and terminology |
| **EU AI Act (Regulation 2024/1689)** | Regulatory context for AI deployer obligations; referenced in risk assessment (Section 8) |
| **NIST AI RMF 1.0** | Supplementary risk management framework; referenced where alignment adds value |
| **ISO/IEC 27001:2022** | Referenced where existing ISMS controls are relevant to AIMS requirements |

*Note: This assessment does not constitute a compliance assessment against the EU AI Act or any other regulatory framework. Regulatory references are provided for context only.*

### Assessment Methodology

**Evidence Collection:** Evidence was gathered through three methods: (1) document review of policies, procedures, and records provided by [CLIENT NAME]; (2) structured interviews with personnel identified in Appendix C; and (3) observation of current practices where applicable.

**Scoring Scale:** Each requirement was scored on the following five-point maturity scale:

| Score | Level | Description |
|---|---|---|
| **0** | Not Addressed | No evidence of the requirement being considered or addressed |
| **1** | Initial | Ad hoc or informal activity exists; not documented or consistently applied |
| **2** | Managed | Activity is documented and applied in some areas but not consistently across the organization |
| **3** | Defined | Documented, consistently applied, and understood across the organization — minimum for certification readiness |
| **4** | Measured | Performance is monitored and measured; data is used to manage the activity |
| **5** | Optimized | Continuously improved based on measurement data and organizational learning |

**Severity Classification:** Gaps were classified by severity as follows:

| Severity | Definition |
|---|---|
| **Critical** | Absence of a mandatory requirement that would result in a major nonconformity during certification audit; blocks certification until resolved |
| **Major** | Significant gap that presents material risk to the organization or would likely result in a minor nonconformity during audit |
| **Minor** | Gap that needs attention but does not block certification; represents an opportunity to strengthen the AIMS |
| **Observation** | Requirement is met at minimum level; improvement opportunity noted for long-term AIMS maturity |

**Limitations:** This assessment reflects the state of [CLIENT NAME]'s AI governance practices as of [ASSESSMENT DATE]. It is based on evidence made available during the assessment period. The assessment does not guarantee a specific outcome in a certification audit, as certification bodies conduct independent evaluations.

---

## 3. Overall Maturity Profile

### Maturity Scores by Clause Group

The following table presents the average maturity score for each ISO 42001 clause group, compared to the certification readiness threshold of 3.0.

| Clause | Title | Current Score | Target (Cert. Ready) | Gap | Status |
|---|---|---|---|---|---|
| **Clause 4** | Context of the Organization | [0.0] | 3.0 | [Δ] | [Below / At / Above] |
| **Clause 5** | Leadership | [0.0] | 3.0 | [Δ] | [Below / At / Above] |
| **Clause 6** | Planning | [0.0] | 3.0 | [Δ] | [Below / At / Above] |
| **Clause 7** | Support | [0.0] | 3.0 | [Δ] | [Below / At / Above] |
| **Clause 8** | Operation | [0.0] | 3.0 | [Δ] | [Below / At / Above] |
| **Clause 9** | Performance Evaluation | [0.0] | 3.0 | [Δ] | [Below / At / Above] |
| **Clause 10** | Improvement | [0.0] | 3.0 | [Δ] | [Below / At / Above] |
| **Overall Average** | | **[0.0]** | **3.0** | **[Δ]** | |

### Maturity Scores by Annex A Domain

| Domain | Title | Current Score | Target (Cert. Ready) | Gap | Status |
|---|---|---|---|---|---|
| **A.2** | Policies for AI | [0.0] | 3.0 | [Δ] | [Below / At / Above] |
| **A.3** | Internal organization | [0.0] | 3.0 | [Δ] | [Below / At / Above] |
| **A.4** | Resources for AI systems | [0.0] | 3.0 | [Δ] | [Below / At / Above] |
| **A.5** | Assessing impacts of AI systems | [0.0] | 3.0 | [Δ] | [Below / At / Above] |
| **A.6** | AI system life cycle | [0.0] | 3.0 | [Δ] | [Below / At / Above] |
| **A.7** | Data for AI systems | [0.0] | 3.0 | [Δ] | [Below / At / Above] |
| **A.8** | Information for interested parties | [0.0] | 3.0 | [Δ] | [Below / At / Above] |
| **A.9** | Use of AI systems | [0.0] | 3.0 | [Δ] | [Below / At / Above] |
| **A.10** | Third-party and customer relationships | [0.0] | 3.0 | [Δ] | [Below / At / Above] |

### Maturity Profile — Text Visualization

The following representation shows relative maturity across clause groups. Each bar represents the current score on a 0 to 5 scale. The `|` marker at position 3 indicates the certification readiness threshold.

```
Clause 4  [████░░░░░░] [SCORE]/5
Clause 5  [████░░░░░░] [SCORE]/5
Clause 6  [██░░░░░░░░] [SCORE]/5
Clause 7  [███░░░░░░░] [SCORE]/5
Clause 8  [███░░░░░░░] [SCORE]/5
Clause 9  [██░░░░░░░░] [SCORE]/5
Clause 10 [██░░░░░░░░] [SCORE]/5
           0    1    2  |3   4    5
                        ^ Certification threshold
```

*Replace the bar lengths and scores above with actual assessment results. Each `█` represents approximately 0.5 points.*

### Interpretation

A score of 3.0 (Defined) represents the minimum maturity level required for certification readiness. At this level, a requirement is documented, consistently applied, and understood across the organization. Scores below 3.0 indicate gaps that require remediation before a certification audit.

Scores of 1.0 to 1.9 (Initial) indicate that some informal activity exists but it is not documented or consistently applied. These areas typically require the most significant remediation effort.

Scores of 0 (Not Addressed) indicate that the requirement has not been considered. These areas require foundational work before other improvements can be built on them.

[CLIENT NAME]'s current profile shows [INTERPRETATION — e.g., "the strongest maturity in Clause 4 (Context), reflecting the organization's existing business context documentation, and the greatest gaps in Clause 6 (Planning), where formal AI risk assessment and impact assessment processes have not yet been established."]

---

## 4. Findings Summary

The following table presents all identified gaps, sorted by severity. Full details for each finding are provided in Sections 5 and 6. Workbook row IDs reference the corresponding entries in the Gap Analysis Workbook.

| ID | Clause / Control | Finding | Current Score | Target Score | Severity | Priority |
|---|---|---|---|---|---|---|
| **GAP-001** | Clause 5.2 — AI Policy | No formal AI policy exists. The organization has no documented statement of its approach to responsible AI use, objectives, or governance commitments. | 0 | 3 | **Critical** | P1 |
| **GAP-002** | Clause 6.1.2 — AI Risk Assessment | No AI risk assessment methodology has been established. AI-related risks are not formally identified, analyzed, or evaluated. | 0 | 3 | **Critical** | P1 |
| **GAP-003** | Clause 6.1.4 — AI System Impact Assessments | No AI system impact assessments have been performed for any in-scope AI system. The organization has not evaluated potential effects on individuals or society. | 0 | 3 | **Critical** | P1 |
| **GAP-004** | A.6.2.4 — AI System Inventory | AI system inventory is incomplete. Embedded AI features within existing business software have not been cataloged. The inventory covers only standalone AI tools. | 1 | 3 | **Major** | P2 |
| **GAP-005** | Clause 6.1.6 — Statement of Applicability | No Statement of Applicability (SoA) has been produced. The organization has not formally determined which Annex A controls are applicable and documented justifications for inclusions and exclusions. | 0 | 3 | **Major** | P2 |
| **GAP-006** | Clause 6.2 — AI Objectives | AI objectives have not been established. The organization has no documented, measurable targets for AIMS performance. | 1 | 3 | **Major** | P2 |
| **GAP-007** | Clause 7.2 — Competence | Training records do not include AI competency. Personnel using AI systems have not received documented training on responsible AI use, limitations, or organizational policies. | 1 | 3 | **Minor** | P3 |
| **GAP-008** | Clause 7.5 — Documented Information | Document control processes exist (from existing ISMS) but have not been formally extended to cover AI management system documentation. | 2 | 3 | **Observation** | P4 |
| *[GAP-009]* | *[Clause / Control]* | *[Finding description]* | *[Score]* | *[Score]* | *[Severity]* | *[Priority]* |
| *[Add rows from workbook]* | | | | | | |

**Severity definitions:** Critical = blocks certification; Major = significant risk, structured remediation required; Minor = needs attention, does not block certification; Observation = meets minimum, improvement opportunity noted.

---

## 5. Detailed Findings by Clause

### Clause 4 — Context of the Organization

**Summary:** [TO BE COMPLETED. Provide a 2 to 4 sentence summary of findings for this clause group. Example: "Clause 4 requirements are partially addressed. The organization has documented its business context and identified key interested parties informally, but these have not been formalized in AIMS-specific documentation. The scope of the AIMS has been defined during Phase 1 of this engagement and is documented in the Phase 1 Scope Document."]

**Specific Gaps:**

| Workbook Ref | Requirement | Finding | Score |
|---|---|---|---|
| [W-4.1-01] | 4.1 — Understanding the organization and its context | [TO BE COMPLETED] | [0-5] |
| [W-4.2-01] | 4.2 — Understanding interested parties | [TO BE COMPLETED] | [0-5] |
| [W-4.3-01] | 4.3 — Determining the scope | [TO BE COMPLETED] | [0-5] |
| [W-4.4-01] | 4.4 — AI management system | [TO BE COMPLETED] | [0-5] |

**Existing Strengths:** [TO BE COMPLETED — Always identify at least one positive. Example: "The organization has a well-documented business strategy and existing stakeholder engagement processes that provide a strong foundation for formalizing AIMS context documentation."]

---

### Clause 5 — Leadership

**Summary:** [TO BE COMPLETED — Example: "Leadership engagement with AI governance is present at an informal level but has not been formalized. No AI policy has been established (Critical gap), and roles and responsibilities for AI governance have not been formally assigned. Executive sponsorship exists and leadership has expressed commitment to the AIMS initiative."]

**Specific Gaps:**

| Workbook Ref | Requirement | Finding | Score |
|---|---|---|---|
| [W-5.1-01] | 5.1 — Leadership and commitment | [TO BE COMPLETED] | [0-5] |
| [W-5.2-01] | 5.2 — AI policy | [TO BE COMPLETED] | [0-5] |
| [W-5.3-01] | 5.3 — Organizational roles, responsibilities, and authorities | [TO BE COMPLETED] | [0-5] |

**Existing Strengths:** [TO BE COMPLETED]

---

### Clause 6 — Planning

**Summary:** [TO BE COMPLETED — Example: "Planning represents the most significant gap area in this assessment. No formal AI risk assessment methodology exists, no AI system impact assessments have been performed, no risk treatment plan has been documented, and no Statement of Applicability has been produced. These are foundational requirements that must be addressed before other AIMS elements can be properly built. AI objectives have not been established. This clause group requires the most substantial remediation effort."]

**Specific Gaps:**

| Workbook Ref | Requirement | Finding | Score |
|---|---|---|---|
| [W-6.1.1-01] | 6.1.1 — General (actions to address risks and opportunities) | [TO BE COMPLETED] | [0-5] |
| [W-6.1.2-01] | 6.1.2 — AI risk assessment | [TO BE COMPLETED] | [0-5] |
| [W-6.1.3-01] | 6.1.3 — AI risk treatment | [TO BE COMPLETED] | [0-5] |
| [W-6.1.4-01] | 6.1.4 — AI system impact assessment | [TO BE COMPLETED] | [0-5] |
| [W-6.1.5-01] | 6.1.5 — AI system impact treatment | [TO BE COMPLETED] | [0-5] |
| [W-6.1.6-01] | 6.1.6 — Statement of Applicability | [TO BE COMPLETED] | [0-5] |
| [W-6.2-01] | 6.2 — AI objectives and planning to achieve them | [TO BE COMPLETED] | [0-5] |

**Existing Strengths:** [TO BE COMPLETED]

---

### Clause 7 — Support

**Summary:** [TO BE COMPLETED — Example: "Support requirements are partially addressed. The organization has adequate resources and infrastructure for AI use, and general competency management processes exist. However, AI-specific competency requirements have not been defined, training records do not capture AI-related training, and awareness activities have not been extended to cover AI governance. Document control processes from the existing ISMS provide a foundation that can be extended to AIMS documentation."]

**Specific Gaps:**

| Workbook Ref | Requirement | Finding | Score |
|---|---|---|---|
| [W-7.1-01] | 7.1 — Resources | [TO BE COMPLETED] | [0-5] |
| [W-7.2-01] | 7.2 — Competence | [TO BE COMPLETED] | [0-5] |
| [W-7.3-01] | 7.3 — Awareness | [TO BE COMPLETED] | [0-5] |
| [W-7.4-01] | 7.4 — Communication | [TO BE COMPLETED] | [0-5] |
| [W-7.5-01] | 7.5 — Documented information | [TO BE COMPLETED] | [0-5] |

**Existing Strengths:** [TO BE COMPLETED]

---

### Clause 8 — Operation

**Summary:** [TO BE COMPLETED — Example: "Operational requirements are partially addressed. The organization has operational processes for deploying and using AI systems, but these have not been formalized in AIMS-specific procedures. Operational planning and control documentation is absent. Supplier and third-party AI management is informal, with no structured vendor assessment process for AI providers."]

**Specific Gaps:**

| Workbook Ref | Requirement | Finding | Score |
|---|---|---|---|
| [W-8.1-01] | 8.1 — Operational planning and control | [TO BE COMPLETED] | [0-5] |
| [W-8.2-01] | 8.2 — AI risk assessment (operational) | [TO BE COMPLETED] | [0-5] |
| [W-8.3-01] | 8.3 — AI risk treatment (operational) | [TO BE COMPLETED] | [0-5] |
| [W-8.4-01] | 8.4 — Documented AI system objectives | [TO BE COMPLETED] | [0-5] |

**Existing Strengths:** [TO BE COMPLETED]

---

### Clause 9 — Performance Evaluation

**Summary:** [TO BE COMPLETED — Example: "Performance evaluation processes for the AIMS have not been established. No monitoring or measurement of AI governance performance is occurring. Internal audit has not been conducted for AIMS requirements. Management review has not been extended to cover AI governance topics. These gaps are addressable through extension of existing ISMS performance evaluation processes."]

**Specific Gaps:**

| Workbook Ref | Requirement | Finding | Score |
|---|---|---|---|
| [W-9.1-01] | 9.1 — Monitoring, measurement, analysis, and evaluation | [TO BE COMPLETED] | [0-5] |
| [W-9.2-01] | 9.2 — Internal audit | [TO BE COMPLETED] | [0-5] |
| [W-9.3-01] | 9.3 — Management review | [TO BE COMPLETED] | [0-5] |

**Existing Strengths:** [TO BE COMPLETED]

---

### Clause 10 — Improvement

**Summary:** [TO BE COMPLETED — Example: "Improvement processes have not been formally established for the AIMS. The organization has a general corrective action process from its ISMS that can be extended. Continual improvement mechanisms specific to AI governance are absent."]

**Specific Gaps:**

| Workbook Ref | Requirement | Finding | Score |
|---|---|---|---|
| [W-10.1-01] | 10.1 — Nonconformity and corrective action | [TO BE COMPLETED] | [0-5] |
| [W-10.2-01] | 10.2 — Continual improvement | [TO BE COMPLETED] | [0-5] |

**Existing Strengths:** [TO BE COMPLETED]

---

## 6. Detailed Findings by Annex A Domain

*Note: Annex A controls are applicable only where determined by the organization's risk assessment and documented in the Statement of Applicability. The findings below reflect the assessment of controls that are provisionally applicable based on [CLIENT NAME]'s AI system inventory and organizational context. Final applicability determinations will be made during SoA development in Phase 3.*

---

### A.2 — Policies for AI

**Summary:** [TO BE COMPLETED — Example: "No AI-specific policies have been established. The organization lacks documented policies governing responsible AI use, acceptable use boundaries, and AI governance commitments. This is the foundational control domain and must be addressed first in the remediation sequence."]

**Key Gaps:** [TO BE COMPLETED]

**Existing Strengths:** [TO BE COMPLETED — e.g., "Existing information security policy provides a model and governance structure that can be extended to cover AI policy requirements."]

---

### A.3 — Internal Organization

**Summary:** [TO BE COMPLETED — Example: "AI governance roles and responsibilities have not been formally assigned. No individual or function has been designated as accountable for AIMS oversight. Informal ownership exists at the operational level but is not documented."]

**Key Gaps:** [TO BE COMPLETED]

**Existing Strengths:** [TO BE COMPLETED]

---

### A.4 — Resources for AI Systems

**Summary:** [TO BE COMPLETED — Example: "Resource management for AI systems is informal. The organization has not formally assessed the computational, data, or human resources required to operate AI systems responsibly within the AIMS framework."]

**Key Gaps:** [TO BE COMPLETED]

**Existing Strengths:** [TO BE COMPLETED]

---

### A.5 — Assessing Impacts of AI Systems

**Summary:** [TO BE COMPLETED — Example: "No structured impact assessment process exists for AI systems. The organization has not evaluated the potential effects of its AI systems on individuals, groups, or society. This is a critical gap given the nature of AI systems in scope, some of which interact directly with customers or influence decisions affecting individuals."]

**Key Gaps:** [TO BE COMPLETED]

**Existing Strengths:** [TO BE COMPLETED]

---

### A.6 — AI System Life Cycle

**Summary:** [TO BE COMPLETED — Example: "As an AI user organization, [CLIENT NAME]'s life cycle responsibilities are focused on procurement, deployment, and operational use rather than development. Controls related to AI system acquisition and vendor selection are partially addressed through existing procurement processes. Controls related to operational monitoring and decommissioning are not formally established."]

**Key Gaps:** [TO BE COMPLETED]

**Existing Strengths:** [TO BE COMPLETED]

---

### A.7 — Data for AI Systems

**Summary:** [TO BE COMPLETED — Example: "Data governance for AI systems is partially addressed through existing data protection and information security controls. However, AI-specific data quality, provenance, and input validation controls have not been established. The organization has not assessed the data inputs to its AI systems for quality or bias risks."]

**Key Gaps:** [TO BE COMPLETED]

**Existing Strengths:** [TO BE COMPLETED]

---

### A.8 — Information for Interested Parties

**Summary:** [TO BE COMPLETED — Example: "Transparency obligations to interested parties regarding AI system use have not been formally addressed. Customers and employees who interact with or are affected by AI systems have not been informed of AI use in a structured way. This gap may also have implications under applicable data protection regulations."]

**Key Gaps:** [TO BE COMPLETED]

**Existing Strengths:** [TO BE COMPLETED]

---

### A.9 — Use of AI Systems

**Summary:** [TO BE COMPLETED — Example: "Operational controls for responsible AI use are informal. Personnel use AI systems without documented guidance on acceptable use, limitations, or escalation procedures. No process exists for monitoring AI system outputs for quality or appropriateness."]

**Key Gaps:** [TO BE COMPLETED]

**Existing Strengths:** [TO BE COMPLETED]

---

### A.10 — Third-Party and Customer Relationships

**Summary:** [TO BE COMPLETED — Example: "Third-party AI management is the most significant Annex A gap area. All in-scope AI systems are provided by third-party vendors, yet no structured vendor assessment process exists for AI providers. Contractual terms with AI vendors have not been reviewed for AI governance requirements. The organization has limited visibility into how its AI providers manage model updates, data handling, and incident response."]

**Key Gaps:** [TO BE COMPLETED]

**Existing Strengths:** [TO BE COMPLETED — e.g., "Existing vendor management process and supplier agreements provide a starting point for extending third-party controls to AI providers."]

---

## 7. Remediation Roadmap (High-Level)

### Sequencing Principles

The remediation roadmap is sequenced to address dependencies between requirements. Foundational elements (AI policy, risk assessment methodology, and AI system inventory) must be established before dependent requirements (risk treatment, SoA, impact assessments) can be completed. Critical gaps are addressed first, followed by major gaps, then minor gaps and observations.

### Priority 1 — Critical Gaps (Weeks 1–[N])

These items must be resolved before a certification audit can proceed. They represent the absence of mandatory AIMS foundations.

| Priority | Requirement | Action Required | Estimated Effort | Dependencies | Target Completion |
|---|---|---|---|---|---|
| P1-01 | Clause 5.2 — AI Policy | Draft, review, and approve a formal AI policy covering responsible AI use commitments, governance objectives, and scope. | [e.g., 8-12 hrs internal + consultant review] | None (foundational) | [Week X] |
| P1-02 | Clause 6.1.2 — AI Risk Assessment Methodology | Establish a documented AI risk assessment methodology, including risk criteria, assessment process, and risk register template. | [e.g., 12-16 hrs internal + consultant facilitation] | AI policy (P1-01) | [Week X] |
| P1-03 | Clause 6.1.4 — AI System Impact Assessments | Conduct impact assessments for all in-scope AI systems using the established methodology. | [e.g., 4-8 hrs per AI system] | Risk methodology (P1-02), complete AI inventory (P2-01) | [Week X] |

### Priority 2 — Major Gaps (Weeks [N]–[N])

These items present significant risk and require structured remediation. They can be addressed in parallel with Priority 1 items where dependencies allow.

| Priority | Requirement | Action Required | Estimated Effort | Dependencies | Target Completion |
|---|---|---|---|---|---|
| P2-01 | A.6.2.4 — AI System Inventory | Complete the AI system inventory to include embedded AI features in existing business software. Conduct a structured review of all software platforms in use. | [e.g., 8-12 hrs internal] | None (can begin immediately) | [Week X] |
| P2-02 | Clause 6.1.6 — Statement of Applicability | Develop the SoA documenting applicable and excluded Annex A controls with justifications. | [e.g., 8-16 hrs internal + consultant facilitation] | Risk assessment (P1-02), risk treatment (P2-03) | [Week X] |
| P2-03 | Clause 6.1.3 — AI Risk Treatment Plan | Document risk treatment decisions for identified AI risks, including selected controls and residual risk acceptance. | [e.g., 8-12 hrs internal + consultant review] | Risk assessment (P1-02) | [Week X] |
| P2-04 | Clause 6.2 — AI Objectives | Establish documented, measurable AI management objectives aligned with the AI policy. | [e.g., 4-6 hrs internal] | AI policy (P1-01) | [Week X] |

### Priority 3 — Minor Gaps (Weeks [N]–[N])

These items need attention but do not block certification. They can be addressed after Priority 1 and 2 items are underway.

| Priority | Requirement | Action Required | Estimated Effort | Dependencies | Target Completion |
|---|---|---|---|---|---|
| P3-01 | Clause 7.2 — AI Competency | Define AI competency requirements for relevant roles. Update training records to capture AI-related training. Develop or source AI awareness training. | [e.g., 6-10 hrs internal] | AI policy (P1-01), roles defined | [Week X] |
| P3-02 | Clause 7.3 — AI Awareness | Develop and deliver AI governance awareness communication for all personnel using AI systems. | [e.g., 4-6 hrs internal] | AI policy (P1-01), competency framework (P3-01) | [Week X] |
| P3-03 | Clause 9.1 — Monitoring and Measurement | Define AIMS performance indicators and establish a monitoring process. | [e.g., 4-8 hrs internal] | AI objectives (P2-04) | [Week X] |

### Priority 4 — Observations (Ongoing)

These items meet minimum requirements. Improvement actions are recommended for long-term AIMS maturity but are not required for initial certification.

| Priority | Requirement | Action Required | Estimated Effort | Target Completion |
|---|---|---|---|---|
| P4-01 | Clause 7.5 — Documented Information | Formally extend existing document control procedures to cover AIMS documentation. | [e.g., 2-4 hrs internal] | [Ongoing] |
| *[Add as needed]* | | | | |

### Quick Wins

The following actions can be completed immediately with minimal effort and will demonstrate early progress:

1. **Designate an AIMS owner.** Assign a named individual as responsible for AIMS implementation. This requires a management decision, not documentation work.
2. **Complete the AI system inventory.** Extend the existing inventory to include embedded AI features. This can be accomplished through a structured review of software subscriptions.
3. **Extend document control to AIMS.** Add AIMS documentation to the existing document control register. This is a configuration change to an existing process.
4. **Schedule the first management review agenda item.** Add AI governance as a standing agenda item to the next scheduled management review meeting.

### Estimated Overall Timeline

| Phase | Activities | Estimated Duration |
|---|---|---|
| **Remediation Phase 1** | Critical gap resolution (policy, risk methodology, impact assessments) | [e.g., 4–6 weeks] |
| **Remediation Phase 2** | Major gap resolution (SoA, risk treatment, objectives, inventory completion) | [e.g., 4–6 weeks] |
| **Remediation Phase 3** | Minor gap resolution, documentation finalization, internal audit | [e.g., 3–4 weeks] |
| **Pre-Audit Review** | Final readiness check, mock audit, corrective action closure | [e.g., 2–3 weeks] |
| **Total Estimated Duration** | | **[e.g., 13–19 weeks]** |

*Timeline estimates assume [CLIENT NAME] can dedicate [N] hours per week of internal resource to remediation activities and that consultant support is available as scheduled. Actual timelines will vary based on resource availability and the complexity of findings.*

---

## 8. Risk Assessment of Current State

This section describes the risks [CLIENT NAME] faces today as a result of the identified gaps. These are not hypothetical future risks. They are present risks arising from the current absence of AI governance controls.

### Regulatory Risk

**EU AI Act Deployer Obligations**

The EU AI Act (Regulation 2024/1689) imposes obligations on organizations that deploy AI systems within the EU. The deployer obligations phase-in timeline includes requirements that may apply to [CLIENT NAME]'s AI systems. Organizations deploying AI systems classified as high-risk under the EU AI Act face obligations including fundamental rights impact assessments, human oversight requirements, and record-keeping obligations, with the August 2, 2026 deadline for certain provisions.

[CLIENT NAME] has not conducted a formal assessment of its AI systems against EU AI Act risk classifications. Without this assessment, the organization may be unaware of applicable obligations. Organizations should consult qualified legal counsel to determine their specific EU AI Act obligations.

*Note: This report does not constitute a legal assessment of EU AI Act compliance. The regulatory landscape is evolving and organizations should seek qualified legal advice regarding their specific obligations.*

**Data Protection Considerations**

AI systems that process personal data may trigger obligations under applicable data protection regulations. The absence of AI system impact assessments means [CLIENT NAME] has not formally evaluated whether its AI systems process personal data in ways that require data protection impact assessments or other regulatory actions. Organizations should consult legal counsel regarding data protection obligations related to AI system use.

### Operational Risk

**Ungoverned AI Use**

Without an AI policy, acceptable use guidelines, or competency requirements, personnel are using AI systems without documented guidance on appropriate use, limitations, or escalation procedures. This creates risk of:

- Inconsistent AI use practices across the organization, leading to variable output quality
- Use of AI systems for purposes outside vendor terms of service
- Inadvertent disclosure of confidential or personal information to AI systems
- Over-reliance on AI outputs without appropriate human oversight
- Inability to respond consistently to AI-related incidents

**Third-Party AI Risk**

All in-scope AI systems are provided by third-party vendors. Without structured vendor assessment and contractual controls, [CLIENT NAME] has limited assurance that its AI providers meet appropriate standards for data handling, model governance, and incident response. Changes to vendor AI models or terms of service may not be detected or assessed for impact.

**Incident Response Gap**

No AI-specific incident response process exists. If an AI system produces harmful, incorrect, or inappropriate outputs, the organization does not have a defined process for detection, escalation, containment, or remediation.

### Reputational Risk

Organizations that use AI systems without governance frameworks face reputational risk if AI-related incidents occur. The absence of documented AI governance may be perceived by customers, partners, and regulators as evidence of insufficient due diligence. As AI governance expectations increase, driven by regulatory developments and market standards, organizations without demonstrable AI governance frameworks may face competitive disadvantage.

---

## 9. Next Steps

### Recommended Phase 3 Engagement Scope

Based on the findings of this assessment, the recommended Phase 3 (Remediation) engagement includes the following activities:

1. **AI Policy development** — Drafting, review, and approval of the organization's AI policy
2. **AI risk assessment facilitation** — Establishing the risk assessment methodology and facilitating the initial risk assessment for all in-scope AI systems
3. **AI system impact assessment facilitation** — Conducting impact assessments for all in-scope AI systems
4. **Statement of Applicability development** — Developing the SoA with justifications for all applicable and excluded controls
5. **AIMS documentation build-out** — Developing required procedures, records templates, and supporting documentation
6. **Competency and awareness program** — Developing AI competency requirements and awareness materials
7. **Internal audit preparation** — Preparing for and facilitating the first AIMS internal audit
8. **Pre-certification readiness review** — Final gap check and mock audit preparation

*A detailed Phase 3 proposal will be provided separately.*

### Key Decisions Needed from Leadership

Before remediation can begin, [CLIENT NAME] leadership should make the following decisions:

1. **AIMS Owner designation** — Who is accountable for AIMS implementation and ongoing maintenance?
2. **Remediation resourcing** — What internal resource (hours per week) can be committed to remediation activities?
3. **Certification timeline** — What is the target date for certification readiness? This determines the remediation pace.
4. **Scope confirmation** — Are there any changes to the AIMS scope based on the findings of this assessment?
5. **Phase 3 engagement** — Confirm scope and timeline for Phase 3 consultant engagement.

### Timeline for Remediation Kickoff

| Milestone | Target Date |
|---|---|
| Leadership decisions confirmed | [DATE] |
| Phase 3 engagement confirmed | [DATE] |
| AIMS Owner designated | [DATE] |
| Remediation kickoff meeting | [DATE] |
| AI policy first draft | [DATE] |

### Preparation [CLIENT NAME] Can Begin Immediately

The following actions can be taken before Phase 3 formally begins, at no additional cost:

1. **Designate an AIMS Owner.** Make the management decision and communicate it internally.
2. **Complete the AI system inventory.** Conduct a structured review of all software subscriptions to identify embedded AI features not currently in the inventory.
3. **Collect existing documentation.** Gather all existing policies, procedures, and records that may be relevant to AIMS requirements (information security policies, risk management procedures, vendor contracts, training records).
4. **Brief leadership.** Share this report with relevant leadership and confirm their understanding of the critical gaps and remediation commitment required.
5. **Review vendor agreements.** Begin reviewing existing contracts with AI providers to understand current data handling and governance terms.

---

## 10. Appendices

### Appendix A — Assessment Methodology (Detailed Scoring Criteria)

The following criteria were used to assign maturity scores to each assessed requirement.

**Score 0 — Not Addressed**
- No evidence of the requirement being considered
- No documentation, process, or activity exists
- Personnel are unaware of the requirement

**Score 1 — Initial**
- Some informal activity exists that partially addresses the requirement
- Activity is ad hoc, undocumented, or dependent on individual knowledge
- Not consistently applied across the organization
- Would not satisfy an auditor's evidence request

**Score 2 — Managed**
- Activity is documented in some form
- Applied in some areas or by some personnel but not consistently
- Documentation may be incomplete or not formally approved
- Partial evidence exists but gaps remain

**Score 3 — Defined (Certification Readiness Threshold)**
- Requirement is fully documented in approved policies, procedures, or records
- Consistently applied across all relevant organizational units and personnel
- Personnel understand the requirement and their responsibilities
- Evidence is available and would satisfy an auditor's evidence request
- This is the minimum level required for certification readiness

**Score 4 — Measured**
- All criteria for Score 3 are met
- Performance against the requirement is monitored and measured
- Metrics or indicators are defined and tracked
- Data is used to manage and improve the activity

**Score 5 — Optimized**
- All criteria for Score 4 are met
- Continuous improvement is actively occurring based on measurement data
- The organization is a recognized leader in this practice area
- Lessons learned are systematically captured and applied

---

### Appendix B — Documents Reviewed

The following documents were reviewed as evidence during this assessment.

| Document | Version / Date | Provided By |
|---|---|---|
| [Document name — e.g., Information Security Policy] | [Version / Date] | [Name / Role] |
| [Document name — e.g., Vendor Management Procedure] | [Version / Date] | [Name / Role] |
| [Document name — e.g., AI System Inventory (draft)] | [Version / Date] | [Name / Role] |
| [Document name — e.g., Employee Handbook] | [Version / Date] | [Name / Role] |
| *[Add all documents reviewed]* | | |

*Note: Where a required document did not exist, this is reflected in the relevant finding.*

---

### Appendix C — Personnel Interviewed

The following personnel participated in assessment interviews.

| Name | Role / Title | Organizational Unit | Interview Date |
|---|---|---|---|
| [Name] | [Role] | [Unit] | [Date] |
| [Name] | [Role] | [Unit] | [Date] |
| [Name] | [Role] | [Unit] | [Date] |
| *[Add all interviewees]* | | | |

---

### Appendix D — Reference to Gap Analysis Workbook

The detailed assessment data underlying this report is documented in the Gap Analysis Workbook, a separate deliverable provided to [CLIENT NAME] as part of this engagement.

**Workbook reference:** `template-gap-analysis-workbook.md` (completed version titled: [CLIENT NAME] — Gap Analysis Workbook — [DATE])

The workbook contains:
- Individual scored assessments for every evaluated requirement
- Evidence notes and observations for each finding
- Workbook row IDs (e.g., W-4.1-01) referenced throughout this report
- Raw scores used to calculate clause group and Annex A domain averages in Section 3

The workbook is an internal working document. This report is the primary client-facing deliverable summarizing workbook findings.

---

## 11. Version History

| Version | Date | Author | Changes |
|---|---|---|---|
| 0.1 | [DATE] | [AUTHOR] | Initial draft for internal review |
| 0.2 | [DATE] | [AUTHOR] | Revised following internal review; findings updated |
| 1.0 | [DATE] | [AUTHOR] | Final version issued to client |
| *[Add rows as needed]* | | | |

---

*ISO 42001 Readiness Service Toolkit | 02-Gap Analysis | Confidential Client Deliverable*
*Prepared by [CONSULTANT NAME] / Skill Tree AI | [DATE]*
