# Gap Analysis Workbook — ISO/IEC 42001:2023 AI Management System Assessment

> **Current as of:** March 2026 | ISO/IEC 42001:2023

---

> **HOW TO CUSTOMIZE THIS WORKBOOK**
>
> This block is for internal consultant use. Remove it before delivering the workbook to the client.
>
> **Step 1 — Complete Document Metadata.** Replace all placeholders in the metadata table below. The Assessment Period must match the report.
>
> **Step 2 — Conduct the assessment.** Work through Part 1 (Normative Clauses) and Part 2 (Annex A Controls) in sequence. For each row:
> - Assign a Score (0–5) based on evidence gathered through document review, interviews, and observation.
> - Record what evidence you found (or note its absence) in the Evidence Found field.
> - Describe the gap in Gap Description. If no gap exists, write "None — requirement met."
> - Classify Gap Severity: Critical / Major / Minor / Observation / N/A.
> - Recommend a specific, actionable remediation step.
>
> **Step 3 — Handle N/A controls.** Three controls are pre-populated as NOT APPLICABLE for AI-user organizations (A.6.2.2, A.6.2.3, A.10.4). Review the N/A justification with the client during scoping. If the client provides AI to third parties, reclassify A.10.4 to FULLY APPLICABLE.
>
> **Step 4 — Complete Part 3 (Assessment Summary).** Calculate clause group and domain averages. Count gaps by severity. Write the certification readiness verdict.
>
> **Step 5 — Transfer findings to the report.** The Gap Analysis Report (`template-gap-analysis-report.md`) references workbook row IDs (e.g., W-4.1-01). Ensure every finding cited in the report traces to a row in this workbook.
>
> **Step 6 — Remove this instruction block.** Delete everything between the `> **HOW TO CUSTOMIZE` line and the closing `>` of this block before delivering to the client.
>
> **Scoring reminder:** 3.0 is the certification readiness threshold. Any requirement scoring below 3 requires a gap description and recommended action. Scores of 0 or 1 on mandatory requirements should be classified Critical or Major.
>
> **Terminology:** Use terms as defined in `00-foundation/glossary.md`. Key terms: AI Management System (AIMS), Statement of Applicability (SoA), AI System, AI User, Impact Assessment, Documented Information, Interested Parties.

---

## Document Metadata

| Field | Value |
|---|---|
| **Document ID** | AIMS-GAP-WB-001 |
| **Document Title** | Gap Analysis Workbook — ISO/IEC 42001:2023 AIMS Assessment |
| **Version** | [VERSION, e.g., 1.0] |
| **Date** | [WORKBOOK DATE] |
| **Client** | [CLIENT NAME] |
| **Prepared By** | [CONSULTANT NAME], Skill Tree AI |
| **Assessment Period** | [START DATE] to [END DATE] |
| **Document Classification** | Confidential — For [CLIENT NAME] Internal Use Only |

---

> **Legal Disclaimer:** This workbook documents the findings of a readiness assessment conducted against the requirements of ISO/IEC 42001:2023. It is intended to support [CLIENT NAME]'s preparation for certification and to identify areas for improvement in AI governance practices. This workbook does not constitute legal advice. Certification decisions are made solely by accredited certification bodies following their own audit processes. References to the EU AI Act and other regulatory frameworks are provided for context only; organizations should consult qualified legal counsel regarding their specific regulatory obligations. Scores and findings in this workbook reflect the state of [CLIENT NAME]'s AI governance practices as of the assessment date and are not a certification outcome.

---

## Purpose

This workbook is the primary working document for Phase 2 of the ISO/IEC 42001:2023 readiness engagement. It provides a structured, row-by-row assessment of every normative clause requirement (Clauses 4–10) and every applicable Annex A control, enabling a systematic evaluation of the organization's current AI governance maturity.

Each assessment row captures:
- The specific requirement being assessed
- Guidance on what evidence demonstrates conformity for AI-user organizations
- The maturity score assigned (0–5)
- Evidence found during the assessment
- Gap description and severity classification
- Recommended remediation action

The findings in this workbook feed directly into the Gap Analysis Report (`template-gap-analysis-report.md`). Workbook row IDs (e.g., W-4.1-01, W-A.6.2.11-01) are referenced throughout the report to trace findings to their source assessment data.

---

## Scoring Methodology

### Maturity Scale

| Score | Level | Description |
|---|---|---|
| **0** | Not Addressed | No evidence of the requirement being considered or addressed. No documentation, process, or activity exists. |
| **1** | Initial | Ad hoc or informal activity exists; not documented or consistently applied. Would not satisfy an auditor's evidence request. |
| **2** | Managed | Activity is documented and applied in some areas but not consistently across the organization. Partial evidence exists. |
| **3** | Defined | Documented, consistently applied, and understood across the organization. Evidence is available and would satisfy an auditor. **This is the certification readiness threshold.** |
| **4** | Measured | All criteria for Score 3 are met. Performance is monitored and measured; data is used to manage the activity. |
| **5** | Optimized | All criteria for Score 4 are met. Continuously improved based on measurement data and organizational learning. |

### Gap Severity Classification

| Severity | Definition |
|---|---|
| **Critical** | Absence of a mandatory requirement that would result in a major nonconformity during certification audit; blocks certification until resolved. |
| **Major** | Significant gap that presents material risk or would likely result in a minor nonconformity during audit; requires structured remediation. |
| **Minor** | Gap that needs attention but does not block certification; represents an opportunity to strengthen the AIMS. |
| **Observation** | Requirement is met at minimum level (score ≥ 3); improvement opportunity noted for long-term AIMS maturity. |
| **N/A** | Control is not applicable to this organization's context; exclusion is justified in the Statement of Applicability. |

---

## Related Documents

| Document | Purpose |
|---|---|
| `00-foundation/glossary.md` | Controlled vocabulary — use for all terminology |
| `00-foundation/annex-a-reference.md` | Authoritative source for all Annex A control IDs, titles, and AI-user applicability ratings |
| `02-gap-analysis/template-gap-analysis-report.md` | Report template that references this workbook's row IDs |
| `01-discovery/template-ai-system-inventory.md` | AI system inventory — identifies the systems being assessed |

---

# PART 1: NORMATIVE CLAUSES ASSESSMENT

*Assess all 28 sub-clauses of ISO/IEC 42001:2023 Clauses 4 through 10. Score each requirement on the 0–5 maturity scale. Requirements scoring below 3.0 require a gap description and recommended action.*

---

## Clause 4 — Context of the Organization

---

### W-4.1-01

| Field | Value |
|---|---|
| **Row ID** | W-4.1-01 |
| **Clause** | 4.1 — Understanding the organization and its context |
| **Requirement** | The organization must identify internal and external factors that are relevant to its purpose and that affect its ability to achieve the intended outcomes of its AI management system. This includes understanding the regulatory environment, market conditions, organizational culture, existing governance structures, and the nature of AI systems in use. |
| **Evidence to Look For** | AIMS context document or equivalent; strategic planning documents referencing AI; documented analysis of external factors (regulatory, competitive, technological); documented analysis of internal factors (culture, capabilities, existing governance); evidence that context analysis was conducted with AI specifically in mind, not just general business context. |
| **Score** | *2* |
| **Evidence Found** | *Organization has a documented business strategy and existing ISO 27001 context analysis. However, neither document addresses AI-specific context factors such as the regulatory environment for AI (EU AI Act), the organization's role as an AI user, or the specific risks and opportunities arising from third-party AI use. Context analysis exists but has not been extended to the AIMS.* |
| **Gap Description** | *Existing context documentation does not address AI-specific internal and external factors. The organization has not formally analyzed the AI regulatory environment, its role as an AI user, or the implications of third-party AI dependency for its AIMS context.* |
| **Gap Severity** | *Major* |
| **Recommended Action** | *Extend the existing context analysis to include AI-specific factors: (1) external — EU AI Act applicability, sector-specific AI regulations, vendor landscape, and societal expectations for AI governance; (2) internal — AI competency levels, existing governance structures applicable to AI, and organizational risk appetite for AI. Document in an AIMS Context Statement.* |

---

### W-4.2-01

| Field | Value |
|---|---|
| **Row ID** | W-4.2-01 |
| **Clause** | 4.2 — Understanding the needs and expectations of interested parties |
| **Requirement** | The organization must identify interested parties relevant to its AIMS and determine their requirements and expectations regarding AI governance. Interested parties include employees, customers, regulators, AI system providers, and any other parties affected by or affecting the organization's AI activities. |
| **Evidence to Look For** | Documented list of interested parties relevant to the AIMS; documented requirements and expectations for each party; evidence that AI-specific stakeholder needs have been considered (e.g., customer expectations for AI transparency, employee concerns about AI-assisted decisions, regulatory requirements); process for monitoring changes in interested party requirements. |
| **Score** | [0-5] |
| **Evidence Found** | [Assessment notes — describe what was found or note absence of evidence] |
| **Gap Description** | [Description of gap, if any. If no gap: "None — requirement met."] |
| **Gap Severity** | [Critical / Major / Minor / Observation / N/A] |
| **Recommended Action** | [Specific action to close the gap] |

---

### W-4.3-01

| Field | Value |
|---|---|
| **Row ID** | W-4.3-01 |
| **Clause** | 4.3 — Determining the scope of the AI management system |
| **Requirement** | The organization must determine the boundaries and applicability of the AIMS, considering the context established in 4.1 and 4.2. The scope must identify which organizational units, locations, AI systems, and activities are covered. The scope must be documented and available to interested parties. |
| **Evidence to Look For** | Documented AIMS scope statement; evidence that scope boundaries are clearly defined (what is included and excluded); reference to specific AI systems within scope; organizational units and locations covered; evidence that scope was determined considering context and interested party requirements; scope document is accessible to relevant parties. |
| **Score** | [0-5] |
| **Evidence Found** | [Assessment notes] |
| **Gap Description** | [Description of gap, if any] |
| **Gap Severity** | [Critical / Major / Minor / Observation / N/A] |
| **Recommended Action** | [Specific action to close the gap] |

---

### W-4.4-01

| Field | Value |
|---|---|
| **Row ID** | W-4.4-01 |
| **Clause** | 4.4 — AI management system |
| **Requirement** | The organization must establish, implement, maintain, and continually improve an AI management system, including the processes needed and their interactions. This is the overarching requirement that the AIMS exists as a functioning system, not merely a collection of documents. |
| **Evidence to Look For** | Evidence that an AIMS has been formally established (not just planned); documented processes and their interactions; evidence of implementation (records of AIMS activities); evidence of maintenance (review and update activities); evidence of continual improvement mechanisms; overall AIMS framework or architecture document. |
| **Score** | [0-5] |
| **Evidence Found** | [Assessment notes] |
| **Gap Description** | [Description of gap, if any] |
| **Gap Severity** | [Critical / Major / Minor / Observation / N/A] |
| **Recommended Action** | [Specific action to close the gap] |

**Clause 4 Average Score:** [X.X] / 5.0

---

## Clause 5 — Leadership

---

### W-5.1-01

| Field | Value |
|---|---|
| **Row ID** | W-5.1-01 |
| **Clause** | 5.1 — Leadership and commitment |
| **Requirement** | Top management must demonstrate leadership and commitment to the AIMS by ensuring the AI policy and objectives are established and compatible with the organization's strategic direction, ensuring AIMS requirements are integrated into business processes, providing necessary resources, communicating the importance of AI governance, and promoting continual improvement. |
| **Evidence to Look For** | Evidence of top management involvement in AIMS decisions (meeting minutes, sign-offs, communications); AI governance as a standing agenda item in leadership meetings; management review records; evidence that resources have been allocated for AIMS implementation; leadership communications about AI governance to the organization; evidence that AI policy has been approved at the appropriate level. |
| **Score** | [0-5] |
| **Evidence Found** | [Assessment notes] |
| **Gap Description** | [Description of gap, if any] |
| **Gap Severity** | [Critical / Major / Minor / Observation / N/A] |
| **Recommended Action** | [Specific action to close the gap] |

---

### W-5.2-01

| Field | Value |
|---|---|
| **Row ID** | W-5.2-01 |
| **Clause** | 5.2 — AI policy |
| **Requirement** | Top management must establish an AI policy that is appropriate to the organization's purpose, provides a framework for setting AI objectives, includes commitments to satisfy applicable requirements and to continual improvement, and addresses responsible AI principles. The policy must be documented, communicated internally, and available to interested parties. |
| **Evidence to Look For** | Documented AI policy approved by top management; policy addresses responsible AI principles (fairness, transparency, accountability, safety); policy provides framework for AI objectives; policy is communicated to all relevant personnel; evidence of communication (training records, intranet publication, acknowledgment records); policy is available to external interested parties where appropriate; policy review date and version control. |
| **Score** | *0* |
| **Evidence Found** | *No AI policy exists. The organization has an Information Security Policy and an Acceptable Use Policy for IT systems, but neither addresses AI-specific governance, responsible AI principles, or the organization's commitments regarding AI use. No draft AI policy was identified.* |
| **Gap Description** | *No formal AI policy has been established. This is a mandatory AIMS requirement and a foundational document that all other AIMS elements depend on. Without an AI policy, the organization cannot demonstrate top management commitment to responsible AI governance, and downstream requirements (objectives, awareness, competency) cannot be properly anchored.* |
| **Gap Severity** | *Critical* |
| **Recommended Action** | *Develop and approve a formal AI policy as the first priority in the remediation sequence. The policy should: (1) state the organization's commitment to responsible AI use; (2) address fairness, transparency, accountability, and safety; (3) provide a framework for AI objectives; (4) reference applicable regulatory requirements; (5) be approved by top management and communicated to all personnel. Use the AI Policy template from Phase 3 materials.* |

---

### W-5.3-01

| Field | Value |
|---|---|
| **Row ID** | W-5.3-01 |
| **Clause** | 5.3 — Organizational roles, responsibilities, and authorities |
| **Requirement** | Top management must ensure that roles, responsibilities, and authorities relevant to the AIMS are assigned, communicated, and understood. This includes designating responsibility for ensuring the AIMS conforms to ISO 42001 requirements and reporting on AIMS performance to top management. |
| **Evidence to Look For** | Documented AIMS roles and responsibilities (in policy, procedure, or RACI matrix); named individual(s) responsible for AIMS conformity; evidence that responsibilities have been communicated (job descriptions, role charters, organizational announcements); evidence that the AIMS owner reports to top management; evidence that AI system owners have been designated for each in-scope AI system. |
| **Score** | [0-5] |
| **Evidence Found** | [Assessment notes] |
| **Gap Description** | [Description of gap, if any] |
| **Gap Severity** | [Critical / Major / Minor / Observation / N/A] |
| **Recommended Action** | [Specific action to close the gap] |

**Clause 5 Average Score:** [X.X] / 5.0

---

## Clause 6 — Planning

---

### W-6.1.1-01

| Field | Value |
|---|---|
| **Row ID** | W-6.1.1-01 |
| **Clause** | 6.1.1 — General (actions to address risks and opportunities) |
| **Requirement** | The organization must determine the risks and opportunities that need to be addressed to ensure the AIMS can achieve its intended outcomes, prevent or reduce undesired effects, and achieve continual improvement. The organization must plan actions to address these risks and opportunities and integrate those actions into AIMS processes. |
| **Evidence to Look For** | Documented risk and opportunity register for the AIMS; evidence that risks and opportunities were identified considering the context (4.1) and interested parties (4.2); documented plan for addressing identified risks and opportunities; evidence that planned actions have been integrated into AIMS processes; review and update records. |
| **Score** | [0-5] |
| **Evidence Found** | [Assessment notes] |
| **Gap Description** | [Description of gap, if any] |
| **Gap Severity** | [Critical / Major / Minor / Observation / N/A] |
| **Recommended Action** | [Specific action to close the gap] |

---

### W-6.1.2-01

| Field | Value |
|---|---|
| **Row ID** | W-6.1.2-01 |
| **Clause** | 6.1.2 — AI risk assessment |
| **Requirement** | The organization must establish, implement, and maintain an AI risk assessment process that defines risk acceptance criteria, identifies AI risks across technical, organizational, ethical, and societal dimensions, analyzes and evaluates those risks, and produces documented results. Risk assessments must be conducted at planned intervals and when significant changes occur. |
| **Evidence to Look For** | Documented AI risk assessment methodology; defined risk criteria (likelihood, impact scales, risk acceptance thresholds); completed risk assessments for each in-scope AI system; risk register with identified, analyzed, and evaluated risks; evidence of periodic reassessment; evidence that risk assessment considers AI-specific dimensions (bias, explainability, data quality, third-party dependency); documented results retained as evidence. |
| **Score** | *0* |
| **Evidence Found** | *No AI risk assessment methodology exists. The organization has a general IT risk register maintained under its ISMS, but it does not address AI-specific risks. No AI risk assessments have been conducted for any in-scope AI system. Personnel interviewed were unaware of any formal process for assessing AI-related risks.* |
| **Gap Description** | *No AI risk assessment process has been established. This is a foundational planning requirement. Without a risk assessment methodology, the organization cannot identify which risks require treatment, cannot determine which Annex A controls are applicable, and cannot produce the Statement of Applicability. All downstream planning requirements depend on this process being in place.* |
| **Gap Severity** | *Critical* |
| **Recommended Action** | *Establish a documented AI risk assessment methodology as a Priority 1 remediation action. The methodology should: (1) define risk criteria appropriate to AI risks (including bias, explainability, data quality, and third-party dependency dimensions); (2) specify the assessment process and frequency; (3) provide a risk register template; (4) be facilitated by the consultant for the initial assessment cycle covering all in-scope AI systems.* |

---

### W-6.1.3-01

| Field | Value |
|---|---|
| **Row ID** | W-6.1.3-01 |
| **Clause** | 6.1.3 — AI risk treatment |
| **Requirement** | The organization must select appropriate risk treatment options for identified AI risks, determine the controls necessary to implement those options, compare selected controls with Annex A controls, produce a risk treatment plan, and obtain risk owner approval. Residual risk must be assessed and accepted by authorized risk owners. |
| **Evidence to Look For** | Documented risk treatment plan; evidence that treatment options were selected for each identified risk (avoid, accept, transfer, mitigate); mapping of selected controls to Annex A controls; documented residual risk assessment; evidence of risk owner approval; Statement of Applicability (which is produced as part of this process); evidence that treatment actions have been implemented or are tracked. |
| **Score** | [0-5] |
| **Evidence Found** | [Assessment notes] |
| **Gap Description** | [Description of gap, if any] |
| **Gap Severity** | [Critical / Major / Minor / Observation / N/A] |
| **Recommended Action** | [Specific action to close the gap] |

---

### W-6.1.4-01

| Field | Value |
|---|---|
| **Row ID** | W-6.1.4-01 |
| **Clause** | 6.1.4 — AI system impact assessment |
| **Requirement** | The organization must establish, implement, and maintain a process to assess the impacts of AI systems on individuals, groups, and society. Impact assessments must be conducted for each in-scope AI system, considering both intended and unintended consequences, and must be documented. Assessments must be reviewed when AI systems or their context changes. |
| **Evidence to Look For** | Documented impact assessment methodology or procedure; completed impact assessments for each in-scope AI system; evidence that assessments consider effects on individuals (privacy, discrimination, autonomy), groups, and society; documented mitigations for identified impacts; evidence of periodic review; impact assessment records retained as documented information. |
| **Score** | [0-5] |
| **Evidence Found** | [Assessment notes] |
| **Gap Description** | [Description of gap, if any] |
| **Gap Severity** | [Critical / Major / Minor / Observation / N/A] |
| **Recommended Action** | [Specific action to close the gap] |

---

### W-6.1.5-01

| Field | Value |
|---|---|
| **Row ID** | W-6.1.5-01 |
| **Clause** | 6.1.5 — AI system impact treatment |
| **Requirement** | The organization must select and implement treatment options for identified AI system impacts, including mitigations, safeguards, and compensating controls. Treatment decisions must be documented, and residual impacts must be assessed and accepted by authorized decision-makers. |
| **Evidence to Look For** | Documented impact treatment plan; evidence that treatment options were selected for each identified impact; implemented mitigations and safeguards; evidence of residual impact assessment; evidence of authorized acceptance of residual impacts; linkage between impact treatment and Annex A controls (particularly A.5 domain controls); evidence that treatment actions are tracked and reviewed. |
| **Score** | [0-5] |
| **Evidence Found** | [Assessment notes] |
| **Gap Description** | [Description of gap, if any] |
| **Gap Severity** | [Critical / Major / Minor / Observation / N/A] |
| **Recommended Action** | [Specific action to close the gap] |

---

### W-6.1.6-01

| Field | Value |
|---|---|
| **Row ID** | W-6.1.6-01 |
| **Clause** | 6.1.6 — Statement of Applicability |
| **Requirement** | The organization must produce a Statement of Applicability (SoA) that documents all Annex A controls, states whether each control is applicable or not applicable, provides justification for inclusions and exclusions, and indicates the implementation status of applicable controls. The SoA is a required AIMS document. |
| **Evidence to Look For** | Documented SoA covering all 39 Annex A controls; justification for each inclusion and exclusion; implementation status for each applicable control; evidence that the SoA was produced based on the risk assessment and risk treatment process; evidence that the SoA is reviewed and updated when the risk profile changes; SoA approved by appropriate authority. |
| **Score** | [0-5] |
| **Evidence Found** | [Assessment notes] |
| **Gap Description** | [Description of gap, if any] |
| **Gap Severity** | [Critical / Major / Minor / Observation / N/A] |
| **Recommended Action** | [Specific action to close the gap] |

---

### W-6.2-01

| Field | Value |
|---|---|
| **Row ID** | W-6.2-01 |
| **Clause** | 6.2 — AI objectives and planning to achieve them |
| **Requirement** | The organization must establish AI objectives at relevant functions and levels. Objectives must be consistent with the AI policy, measurable, consider applicable requirements, be monitored, communicated, and updated as appropriate. The organization must determine what will be done, what resources are required, who is responsible, when objectives will be completed, and how results will be evaluated. |
| **Evidence to Look For** | Documented AI objectives (specific, measurable, time-bound); evidence that objectives are aligned with the AI policy; evidence that objectives have been communicated to relevant personnel; plans for achieving each objective (resources, responsibilities, timelines); monitoring records showing progress against objectives; evidence of objective review and update. |
| **Score** | [0-5] |
| **Evidence Found** | [Assessment notes] |
| **Gap Description** | [Description of gap, if any] |
| **Gap Severity** | [Critical / Major / Minor / Observation / N/A] |
| **Recommended Action** | [Specific action to close the gap] |

**Clause 6 Average Score:** [X.X] / 5.0

---

## Clause 7 — Support

---

### W-7.1-01

| Field | Value |
|---|---|
| **Row ID** | W-7.1-01 |
| **Clause** | 7.1 — Resources |
| **Requirement** | The organization must determine and provide the resources needed to establish, implement, maintain, and continually improve the AIMS. This includes human resources, infrastructure, technology, and financial resources necessary for AI governance activities. |
| **Evidence to Look For** | Evidence that resources have been allocated for AIMS implementation (budget, headcount, tools); evidence that resource adequacy has been assessed; documented resource plan or budget for AIMS activities; evidence that resource constraints have been identified and addressed; management decisions on resource allocation for AI governance. |
| **Score** | [0-5] |
| **Evidence Found** | [Assessment notes] |
| **Gap Description** | [Description of gap, if any] |
| **Gap Severity** | [Critical / Major / Minor / Observation / N/A] |
| **Recommended Action** | [Specific action to close the gap] |

---

### W-7.2-01

| Field | Value |
|---|---|
| **Row ID** | W-7.2-01 |
| **Clause** | 7.2 — Competence |
| **Requirement** | The organization must determine the competencies required for personnel whose work affects AI governance performance, ensure those personnel are competent through education, training, or experience, take action to acquire necessary competencies where gaps exist, and retain documented evidence of competence. |
| **Evidence to Look For** | Documented AI competency requirements for relevant roles; training records showing AI-related training completed; competency gap assessment; evidence of training programs or external qualifications for AI governance; records of competency evaluation; evidence that competency requirements are reviewed when AI systems or roles change. |
| **Score** | [0-5] |
| **Evidence Found** | [Assessment notes] |
| **Gap Description** | [Description of gap, if any] |
| **Gap Severity** | [Critical / Major / Minor / Observation / N/A] |
| **Recommended Action** | [Specific action to close the gap] |

---

### W-7.3-01

| Field | Value |
|---|---|
| **Row ID** | W-7.3-01 |
| **Clause** | 7.3 — Awareness |
| **Requirement** | Personnel working under the organization's control must be aware of the AI policy, their contribution to AIMS effectiveness, the implications of not conforming to AIMS requirements, and the benefits of improved AI governance performance. Awareness must be appropriate to each person's role and level of AI system interaction. |
| **Evidence to Look For** | Evidence of AI awareness communications (emails, intranet posts, briefings); AI awareness training records; evidence that all personnel using AI systems have received awareness information; awareness content covering the AI policy, responsible AI principles, and reporting obligations; evidence of awareness program review and refresh. |
| **Score** | [0-5] |
| **Evidence Found** | [Assessment notes] |
| **Gap Description** | [Description of gap, if any] |
| **Gap Severity** | [Critical / Major / Minor / Observation / N/A] |
| **Recommended Action** | [Specific action to close the gap] |

---

### W-7.4-01

| Field | Value |
|---|---|
| **Row ID** | W-7.4-01 |
| **Clause** | 7.4 — Communication |
| **Requirement** | The organization must determine the internal and external communications relevant to the AIMS, including what to communicate, when, to whom, and how. This covers both internal AI governance communications and external communications to interested parties about AI system use. |
| **Evidence to Look For** | Documented communication plan for AIMS-related communications; evidence of internal communications about AI governance (policy announcements, updates, incident notifications); evidence of external communications to interested parties (customer disclosures, regulatory notifications); communication records; process for managing incoming AI-related inquiries or concerns. |
| **Score** | [0-5] |
| **Evidence Found** | [Assessment notes] |
| **Gap Description** | [Description of gap, if any] |
| **Gap Severity** | [Critical / Major / Minor / Observation / N/A] |
| **Recommended Action** | [Specific action to close the gap] |

---

### W-7.5-01

| Field | Value |
|---|---|
| **Row ID** | W-7.5-01 |
| **Clause** | 7.5 — Documented information |
| **Requirement** | The organization must maintain documented information required by ISO 42001 and determined necessary for AIMS effectiveness. Documented information must be controlled to ensure it is available, suitable for use, adequately protected, and managed through its lifecycle (creation, update, distribution, access, retention, and disposal). |
| **Evidence to Look For** | Document control procedure covering AIMS documentation; document register or index of AIMS documents; evidence of version control on AIMS documents; evidence of review and approval processes; access controls on sensitive AIMS documents; retention schedule for AIMS records; evidence that document control has been extended to cover AI-specific documentation (not just general ISMS documents). |
| **Score** | [0-5] |
| **Evidence Found** | [Assessment notes] |
| **Gap Description** | [Description of gap, if any] |
| **Gap Severity** | [Critical / Major / Minor / Observation / N/A] |
| **Recommended Action** | [Specific action to close the gap] |

**Clause 7 Average Score:** [X.X] / 5.0

---

## Clause 8 — Operation

---

### W-8.1-01

| Field | Value |
|---|---|
| **Row ID** | W-8.1-01 |
| **Clause** | 8.1 — Operational planning and control |
| **Requirement** | The organization must plan, implement, control, and maintain the processes needed to meet AIMS requirements and implement the actions determined in Clause 6. This includes establishing criteria for processes, implementing control of processes in accordance with criteria, and retaining documented information to demonstrate that processes have been carried out as planned. |
| **Evidence to Look For** | Documented operational procedures for AI governance activities; evidence that procedures are implemented and followed; process records demonstrating conformity with planned activities; evidence of operational controls for AI system use (access controls, usage monitoring, output review procedures); evidence that outsourced processes affecting the AIMS are controlled. |
| **Score** | [0-5] |
| **Evidence Found** | [Assessment notes] |
| **Gap Description** | [Description of gap, if any] |
| **Gap Severity** | [Critical / Major / Minor / Observation / N/A] |
| **Recommended Action** | [Specific action to close the gap] |

---

### W-8.2-01

| Field | Value |
|---|---|
| **Row ID** | W-8.2-01 |
| **Clause** | 8.2 — AI risk assessment (operational) |
| **Requirement** | The organization must perform AI risk assessments at planned intervals and when significant changes are proposed or occur. Operational risk assessments must follow the methodology established in 6.1.2 and produce documented results that are retained as evidence. |
| **Evidence to Look For** | Records of AI risk assessments conducted during the operational period; evidence that assessments were triggered by planned intervals and change events; updated risk register reflecting current risk profile; evidence that assessment results were reviewed and acted upon; evidence that risk assessment frequency is appropriate to the organization's AI risk profile. |
| **Score** | [0-5] |
| **Evidence Found** | [Assessment notes] |
| **Gap Description** | [Description of gap, if any] |
| **Gap Severity** | [Critical / Major / Minor / Observation / N/A] |
| **Recommended Action** | [Specific action to close the gap] |

---

### W-8.3-01

| Field | Value |
|---|---|
| **Row ID** | W-8.3-01 |
| **Clause** | 8.3 — AI risk treatment (operational) |
| **Requirement** | The organization must implement the AI risk treatment plan established in 6.1.3 and retain documented information of the results of risk treatment. Evidence must demonstrate that treatment actions have been implemented and are effective. |
| **Evidence to Look For** | Evidence that risk treatment actions from the risk treatment plan have been implemented; records of control implementation; evidence of control effectiveness monitoring; updated risk treatment plan reflecting implementation status; evidence that residual risks are being monitored; records of risk owner acceptance of residual risks. |
| **Score** | [0-5] |
| **Evidence Found** | [Assessment notes] |
| **Gap Description** | [Description of gap, if any] |
| **Gap Severity** | [Critical / Major / Minor / Observation / N/A] |
| **Recommended Action** | [Specific action to close the gap] |

---

### W-8.4-01

| Field | Value |
|---|---|
| **Row ID** | W-8.4-01 |
| **Clause** | 8.4 — Documented AI system objectives |
| **Requirement** | The organization must document the objectives for each AI system within scope, including the intended purpose, performance expectations, and constraints. These documented objectives provide the baseline against which AI system performance is monitored and evaluated. |
| **Evidence to Look For** | Documented objectives for each in-scope AI system; evidence that objectives are specific and measurable; evidence that objectives are aligned with the AI policy and organizational AI objectives (6.2); evidence that AI system objectives are communicated to relevant personnel; evidence that objectives are reviewed when AI systems change. |
| **Score** | [0-5] |
| **Evidence Found** | [Assessment notes] |
| **Gap Description** | [Description of gap, if any] |
| **Gap Severity** | [Critical / Major / Minor / Observation / N/A] |
| **Recommended Action** | [Specific action to close the gap] |

**Clause 8 Average Score:** [X.X] / 5.0

---

## Clause 9 — Performance Evaluation

---

### W-9.1-01

| Field | Value |
|---|---|
| **Row ID** | W-9.1-01 |
| **Clause** | 9.1 — Monitoring, measurement, analysis, and evaluation |
| **Requirement** | The organization must determine what needs to be monitored and measured regarding AIMS performance, the methods for monitoring and measurement, when monitoring and measurement will be performed and analyzed, and who will perform these activities. Results must be documented and evaluated. |
| **Evidence to Look For** | Documented AIMS performance indicators or metrics; monitoring records showing regular measurement activity; evidence of analysis and evaluation of monitoring results; evidence that monitoring covers AI system performance, control effectiveness, and AIMS objectives; reports or dashboards showing AIMS performance data; evidence that monitoring results are used to drive improvement. |
| **Score** | [0-5] |
| **Evidence Found** | [Assessment notes] |
| **Gap Description** | [Description of gap, if any] |
| **Gap Severity** | [Critical / Major / Minor / Observation / N/A] |
| **Recommended Action** | [Specific action to close the gap] |

---

### W-9.2-01

| Field | Value |
|---|---|
| **Row ID** | W-9.2-01 |
| **Clause** | 9.2 — Internal audit |
| **Requirement** | The organization must conduct internal audits at planned intervals to provide information on whether the AIMS conforms to ISO 42001 requirements and the organization's own requirements, and whether the AIMS is effectively implemented and maintained. An audit program must be established, auditors must be objective and impartial, and audit results must be reported to management. |
| **Evidence to Look For** | Documented internal audit program for the AIMS; evidence of at least one completed AIMS internal audit; audit plan and scope documentation; audit records and findings; evidence of auditor competence and impartiality; evidence that audit results were reported to management; evidence that nonconformities identified in audit were addressed through corrective action. |
| **Score** | [0-5] |
| **Evidence Found** | [Assessment notes] |
| **Gap Description** | [Description of gap, if any] |
| **Gap Severity** | [Critical / Major / Minor / Observation / N/A] |
| **Recommended Action** | [Specific action to close the gap] |

---

### W-9.3-01

| Field | Value |
|---|---|
| **Row ID** | W-9.3-01 |
| **Clause** | 9.3 — Management review |
| **Requirement** | Top management must review the AIMS at planned intervals to ensure its continuing suitability, adequacy, and effectiveness. Management review inputs must include audit results, performance data, nonconformities, and changes in context. Outputs must include decisions on continual improvement opportunities and any changes needed to the AIMS. |
| **Evidence to Look For** | Management review meeting records (minutes or equivalent); evidence that review inputs were considered (audit results, performance data, nonconformities, interested party feedback, risk changes); documented review outputs (decisions, actions, improvement opportunities); evidence that management review is conducted at appropriate intervals; evidence that action items from management review are tracked and completed. |
| **Score** | [0-5] |
| **Evidence Found** | [Assessment notes] |
| **Gap Description** | [Description of gap, if any] |
| **Gap Severity** | [Critical / Major / Minor / Observation / N/A] |
| **Recommended Action** | [Specific action to close the gap] |

**Clause 9 Average Score:** [X.X] / 5.0

---

## Clause 10 — Improvement

---

### W-10.1-01

| Field | Value |
|---|---|
| **Row ID** | W-10.1-01 |
| **Clause** | 10.1 — Nonconformity and corrective action |
| **Requirement** | When a nonconformity occurs, the organization must react to it, evaluate the need for corrective action to eliminate the root cause, implement corrective action where needed, review the effectiveness of corrective action taken, and update risks and opportunities if necessary. Nonconformities and corrective actions must be documented. |
| **Evidence to Look For** | Documented nonconformity and corrective action procedure; records of nonconformities identified and addressed; evidence of root cause analysis for nonconformities; evidence of corrective action implementation and effectiveness review; nonconformity register or log; evidence that the corrective action process covers AI-specific nonconformities (not just general ISMS nonconformities). |
| **Score** | [0-5] |
| **Evidence Found** | [Assessment notes] |
| **Gap Description** | [Description of gap, if any] |
| **Gap Severity** | [Critical / Major / Minor / Observation / N/A] |
| **Recommended Action** | [Specific action to close the gap] |

---

### W-10.2-01

| Field | Value |
|---|---|
| **Row ID** | W-10.2-01 |
| **Clause** | 10.2 — Continual improvement |
| **Requirement** | The organization must continually improve the suitability, adequacy, and effectiveness of the AIMS. This requires systematic identification of improvement opportunities, implementation of improvements, and evidence that the AIMS is evolving over time rather than remaining static. |
| **Evidence to Look For** | Evidence of a continual improvement process for the AIMS; improvement opportunities identified from management review, audit results, monitoring data, and incident analysis; evidence that improvements have been implemented; improvement log or register; evidence that improvement activities are tracked and their effectiveness evaluated; evidence that the AIMS has evolved in response to changing AI risks and organizational context. |
| **Score** | [0-5] |
| **Evidence Found** | [Assessment notes] |
| **Gap Description** | [Description of gap, if any] |
| **Gap Severity** | [Critical / Major / Minor / Observation / N/A] |
| **Recommended Action** | [Specific action to close the gap] |

**Clause 10 Average Score:** [X.X] / 5.0

---

# PART 2: ANNEX A CONTROL ASSESSMENT

*Assess all 39 Annex A controls using the A.2–A.10 numbering scheme. For each control, confirm the AI-User Applicability rating from `00-foundation/annex-a-reference.md`. Controls rated NOT APPLICABLE are pre-populated with N/A justification — confirm with client during scoping before finalizing.*

---

## Domain A.2 — Policies for AI

*Objective: Provide management direction and support for AI systems in accordance with business requirements, applicable laws, and responsible AI principles.*

---

### W-A.2.2-01

| Field | Value |
|---|---|
| **Row ID** | W-A.2.2-01 |
| **Control** | A.2.2 — AI Policy |
| **AI-User Applicability** | FULLY APPLICABLE |
| **Requirement Summary** | Define and document a formal AI policy establishing the organization's approach to responsible AI, including commitments to compliance, ethical principles, and a framework for AI objectives. |
| **Evidence to Look For** | Documented AI policy; policy approved by top management; policy addresses responsible AI principles; policy provides framework for AI objectives; evidence of communication to all personnel; version control and review date. |
| **Score** | [0-5] |
| **Evidence Found** | [Assessment notes] |
| **Gap Description** | [Description of gap, if any] |
| **Gap Severity** | [Critical / Major / Minor / Observation / N/A] |
| **Recommended Action** | [Specific action to close the gap] |

---

### W-A.2.3-01

| Field | Value |
|---|---|
| **Row ID** | W-A.2.3-01 |
| **Control** | A.2.3 — Responsible AI Topics in AI Policy |
| **AI-User Applicability** | FULLY APPLICABLE |
| **Requirement Summary** | Address specific responsible AI considerations in the AI policy, including fairness, transparency, accountability, human oversight, privacy, safety, and societal impact. |
| **Evidence to Look For** | AI policy explicitly addresses fairness (non-discrimination), transparency (explainability), accountability (ownership of AI decisions), human oversight (intervention mechanisms), privacy (data protection in AI use), safety (harm prevention), and societal impact; evidence that responsible AI topics are operationalized in procedures, not just stated in policy. |
| **Score** | [0-5] |
| **Evidence Found** | [Assessment notes] |
| **Gap Description** | [Description of gap, if any] |
| **Gap Severity** | [Critical / Major / Minor / Observation / N/A] |
| **Recommended Action** | [Specific action to close the gap] |

**Domain A.2 Average Score:** [X.X] / 5.0

---

## Domain A.3 — Internal Organization

*Objective: Establish accountability within the organization to support a responsible approach to AI.*

---

### W-A.3.2-01

| Field | Value |
|---|---|
| **Row ID** | W-A.3.2-01 |
| **Control** | A.3.2 — Roles and Responsibilities for AI |
| **AI-User Applicability** | FULLY APPLICABLE |
| **Requirement Summary** | Define and allocate roles and responsibilities for AI-related activities, including AI system owners, data stewards, risk owners, and AIMS management. |
| **Evidence to Look For** | Documented AI governance roles (AIMS owner, AI system owners, risk owners, data stewards); role descriptions or RACI matrix; evidence that roles have been assigned to named individuals; evidence that role holders understand their responsibilities; evidence that roles are reviewed when organizational structure changes. |
| **Score** | [0-5] |
| **Evidence Found** | [Assessment notes] |
| **Gap Description** | [Description of gap, if any] |
| **Gap Severity** | [Critical / Major / Minor / Observation / N/A] |
| **Recommended Action** | [Specific action to close the gap] |

---

### W-A.3.3-01

| Field | Value |
|---|---|
| **Row ID** | W-A.3.3-01 |
| **Control** | A.3.3 — Reporting of AI Concerns |
| **AI-User Applicability** | FULLY APPLICABLE |
| **Requirement Summary** | Establish a mechanism for personnel to report AI-related ethical, safety, or compliance concerns without fear of retaliation. |
| **Evidence to Look For** | Documented AI concern reporting mechanism (dedicated channel, process, or extension of existing whistleblower/ethics hotline); evidence that the mechanism is communicated to all personnel; evidence of non-retaliation commitment; records of concerns received and addressed; evidence that the mechanism is accessible and known to staff using AI systems. |
| **Score** | [0-5] |
| **Evidence Found** | [Assessment notes] |
| **Gap Description** | [Description of gap, if any] |
| **Gap Severity** | [Critical / Major / Minor / Observation / N/A] |
| **Recommended Action** | [Specific action to close the gap] |

---

### W-A.3.4-01

| Field | Value |
|---|---|
| **Row ID** | W-A.3.4-01 |
| **Control** | A.3.4 — Impact of Organizational Changes |
| **AI-User Applicability** | FULLY APPLICABLE |
| **Requirement Summary** | Assess and manage AI implications when the organization undergoes changes such as restructuring, mergers, or technology transitions. |
| **Evidence to Look For** | Change management procedure that includes AI governance considerations; evidence that AI impact was assessed during recent organizational changes; evidence that AI system ownership and responsibilities are updated when organizational changes occur; evidence that vendor transitions or AI tool changes trigger a formal assessment process. |
| **Score** | [0-5] |
| **Evidence Found** | [Assessment notes] |
| **Gap Description** | [Description of gap, if any] |
| **Gap Severity** | [Critical / Major / Minor / Observation / N/A] |
| **Recommended Action** | [Specific action to close the gap] |

**Domain A.3 Average Score:** [X.X] / 5.0

---

## Domain A.4 — Resources for AI Systems

*Objective: Ensure the organization identifies and provides all resources required for AI systems to understand and address associated risks.*

---

### W-A.4.2-01

| Field | Value |
|---|---|
| **Row ID** | W-A.4.2-01 |
| **Control** | A.4.2 — Resources Related to AI Systems |
| **AI-User Applicability** | FULLY APPLICABLE |
| **Requirement Summary** | Identify and document all resources needed for AI activities, including human, technical, financial, and infrastructure resources at each lifecycle stage. |
| **Evidence to Look For** | Documented resource inventory for AI activities; evidence that resource needs have been assessed for each in-scope AI system; budget allocation for AI governance activities; evidence that resource adequacy is reviewed periodically; evidence that resource gaps have been identified and addressed. |
| **Score** | [0-5] |
| **Evidence Found** | [Assessment notes] |
| **Gap Description** | [Description of gap, if any] |
| **Gap Severity** | [Critical / Major / Minor / Observation / N/A] |
| **Recommended Action** | [Specific action to close the gap] |

---

### W-A.4.3-01

| Field | Value |
|---|---|
| **Row ID** | W-A.4.3-01 |
| **Control** | A.4.3 — Competencies Related to AI Systems |
| **AI-User Applicability** | FULLY APPLICABLE |
| **Requirement Summary** | Ensure personnel involved in AI activities have the required competencies; identify skill gaps, provide training, and maintain competency records. |
| **Evidence to Look For** | Documented AI competency framework; competency gap assessment results; training records for AI-related competencies; evidence of training programs (internal or external); competency evaluation records; evidence that competency requirements are updated when AI systems or roles change. |
| **Score** | [0-5] |
| **Evidence Found** | [Assessment notes] |
| **Gap Description** | [Description of gap, if any] |
| **Gap Severity** | [Critical / Major / Minor / Observation / N/A] |
| **Recommended Action** | [Specific action to close the gap] |

---

### W-A.4.4-01

| Field | Value |
|---|---|
| **Row ID** | W-A.4.4-01 |
| **Control** | A.4.4 — Awareness of Responsible Use of AI Systems |
| **AI-User Applicability** | FULLY APPLICABLE |
| **Requirement Summary** | Ensure personnel are aware of the AI policy, relevant risks, ethical considerations, and their own responsibilities regarding AI systems. |
| **Evidence to Look For** | AI awareness training program; training completion records; awareness content covering AI policy, responsible AI principles, data handling obligations, and reporting mechanisms; evidence that awareness is tailored to different roles and levels of AI interaction; evidence of periodic awareness refresh. |
| **Score** | [0-5] |
| **Evidence Found** | [Assessment notes] |
| **Gap Description** | [Description of gap, if any] |
| **Gap Severity** | [Critical / Major / Minor / Observation / N/A] |
| **Recommended Action** | [Specific action to close the gap] |

---

### W-A.4.5-01

| Field | Value |
|---|---|
| **Row ID** | W-A.4.5-01 |
| **Control** | A.4.5 — Consultation |
| **AI-User Applicability** | FULLY APPLICABLE |
| **Requirement Summary** | Engage relevant stakeholders when making significant AI decisions that affect them. |
| **Evidence to Look For** | Evidence of stakeholder consultation before adopting new AI systems; records of consultation activities (meetings, surveys, feedback sessions); evidence that consultation outcomes influenced AI governance decisions; evidence that affected employees were consulted before AI tools were deployed in their workflows; evidence of customer or partner consultation where AI use affects them. |
| **Score** | [0-5] |
| **Evidence Found** | [Assessment notes] |
| **Gap Description** | [Description of gap, if any] |
| **Gap Severity** | [Critical / Major / Minor / Observation / N/A] |
| **Recommended Action** | [Specific action to close the gap] |

---

### W-A.4.6-01

| Field | Value |
|---|---|
| **Row ID** | W-A.4.6-01 |
| **Control** | A.4.6 — Communication About the AI System |
| **AI-User Applicability** | FULLY APPLICABLE |
| **Requirement Summary** | Communicate relevant information about AI systems to interested parties, including capabilities, limitations, and intended use. |
| **Evidence to Look For** | Evidence of communications to internal teams about AI system capabilities and limitations; evidence of external communications to customers or partners about AI use; AI system documentation accessible to relevant personnel; evidence that communications are updated when AI systems change; evidence that limitations and constraints are communicated alongside capabilities. |
| **Score** | [0-5] |
| **Evidence Found** | [Assessment notes] |
| **Gap Description** | [Description of gap, if any] |
| **Gap Severity** | [Critical / Major / Minor / Observation / N/A] |
| **Recommended Action** | [Specific action to close the gap] |

**Domain A.4 Average Score:** [X.X] / 5.0

---

## Domain A.5 — Assessing Impacts of AI Systems

*Objective: Assess AI system impacts on individuals, groups, and society throughout the system lifecycle.*

---

### W-A.5.2-01

| Field | Value |
|---|---|
| **Row ID** | W-A.5.2-01 |
| **Control** | A.5.2 — AI System Risk Assessment |
| **AI-User Applicability** | FULLY APPLICABLE |
| **Requirement Summary** | Identify and assess risks from AI systems across technical, organizational, ethical, and societal dimensions; conduct initial and periodic reassessments. |
| **Evidence to Look For** | Completed AI risk assessments for each in-scope AI system; risk assessment methodology documentation; risk register with AI-specific risks identified; evidence that assessments cover technical risks (system failure, data quality), organizational risks (over-reliance, misuse), ethical risks (bias, discrimination), and societal risks; evidence of periodic reassessment. |
| **Score** | [0-5] |
| **Evidence Found** | [Assessment notes] |
| **Gap Description** | [Description of gap, if any] |
| **Gap Severity** | [Critical / Major / Minor / Observation / N/A] |
| **Recommended Action** | [Specific action to close the gap] |

---

### W-A.5.3-01

| Field | Value |
|---|---|
| **Row ID** | W-A.5.3-01 |
| **Control** | A.5.3 — AI System Impact Assessment |
| **AI-User Applicability** | FULLY APPLICABLE |
| **Requirement Summary** | Evaluate the impacts of AI systems on individuals and groups, including potential harms, discrimination, and privacy effects; document mitigations. |
| **Evidence to Look For** | Completed impact assessments for each in-scope AI system; impact assessment methodology; evidence that assessments consider effects on individuals (privacy, autonomy, discrimination), groups (disparate impact), and society; documented mitigations for identified impacts; evidence of periodic review; impact assessment records retained as documented information. |
| **Score** | [0-5] |
| **Evidence Found** | [Assessment notes] |
| **Gap Description** | [Description of gap, if any] |
| **Gap Severity** | [Critical / Major / Minor / Observation / N/A] |
| **Recommended Action** | [Specific action to close the gap] |

---

### W-A.5.4-01

| Field | Value |
|---|---|
| **Row ID** | W-A.5.4-01 |
| **Control** | A.5.4 — Impact of AI System Documentation |
| **AI-User Applicability** | FULLY APPLICABLE |
| **Requirement Summary** | Document impact assessment results, including impacts identified, mitigations applied, and residual risks; keep documentation current as systems change. |
| **Evidence to Look For** | Documented impact assessment records for each in-scope AI system; evidence that records include identified impacts, applied mitigations, and residual risks; evidence that documentation is updated when AI systems or their context changes; evidence that impact documentation is retained and accessible for audit; version control on impact assessment records. |
| **Score** | [0-5] |
| **Evidence Found** | [Assessment notes] |
| **Gap Description** | [Description of gap, if any] |
| **Gap Severity** | [Critical / Major / Minor / Observation / N/A] |
| **Recommended Action** | [Specific action to close the gap] |

**Domain A.5 Average Score:** [X.X] / 5.0

---

## Domain A.6 — AI System Life Cycle

*Objective: Define criteria and requirements for each stage of the AI system life cycle to ensure responsible deployment and operation.*

---

### W-A.6.2.2-01

| Field | Value |
|---|---|
| **Row ID** | W-A.6.2.2-01 |
| **Control** | A.6.2.2 — Design and Development of AI System |
| **AI-User Applicability** | NOT APPLICABLE |
| **Requirement Summary** | Apply responsible design and development practices including requirements definition, design decisions, and development standards. |
| **Evidence to Look For** | N/A — Control excluded from scope. |
| **Score** | N/A |
| **Evidence Found** | N/A |
| **Gap Description** | *Not applicable. The organization does not design or develop AI systems. All in-scope AI systems are procured from third-party providers. This control targets AI developers and is excluded from the AIMS scope. Exclusion must be documented in the Statement of Applicability with this justification.* |
| **Gap Severity** | N/A |
| **Recommended Action** | Document exclusion in the Statement of Applicability. Confirm with client that no AI development activities are occurring within scope. If the client uses vendor fine-tuning capabilities or builds custom models on foundation models, reassess applicability. |

---

### W-A.6.2.3-01

| Field | Value |
|---|---|
| **Row ID** | W-A.6.2.3-01 |
| **Control** | A.6.2.3 — Training and Testing AI Model |
| **AI-User Applicability** | NOT APPLICABLE |
| **Requirement Summary** | Ensure AI models are properly trained, tested, and validated before deployment. |
| **Evidence to Look For** | N/A — Control excluded from scope. |
| **Score** | N/A |
| **Evidence Found** | N/A |
| **Gap Description** | *Not applicable. The organization does not train or test AI models. Model training and testing is the responsibility of the AI provider. The organization relies on provider testing and validation evidence, which is addressed through the third-party management controls (A.10.2). Exclusion must be documented in the Statement of Applicability.* |
| **Gap Severity** | N/A |
| **Recommended Action** | Document exclusion in the Statement of Applicability. When reviewing vendor agreements (A.10.2), request evidence of the provider's model testing and validation practices as part of supplier due diligence. |

---

### W-A.6.2.4-01

| Field | Value |
|---|---|
| **Row ID** | W-A.6.2.4-01 |
| **Control** | A.6.2.4 — Verification and Validation of AI System |
| **AI-User Applicability** | PARTIALLY APPLICABLE |
| **Requirement Summary** | Confirm that the AI system meets specified requirements (verification) and fulfills its intended purpose (validation). For AI users, this applies in the context of validating that a third-party AI tool meets organizational requirements before adoption — not building full V&V processes. |
| **Evidence to Look For** | Evidence of pre-adoption evaluation of AI tools against organizational requirements; documented acceptance criteria for AI system adoption; evidence that AI tools were tested or piloted before full deployment; evidence that validation is repeated when vendors release significant updates; records of validation activities. |
| **Score** | [0-5] |
| **Evidence Found** | [Assessment notes] |
| **Gap Description** | [Description of gap, if any] |
| **Gap Severity** | [Critical / Major / Minor / Observation / N/A] |
| **Recommended Action** | [Specific action to close the gap] |

---

### W-A.6.2.5-01

| Field | Value |
|---|---|
| **Row ID** | W-A.6.2.5-01 |
| **Control** | A.6.2.5 — Deployment of AI System |
| **AI-User Applicability** | FULLY APPLICABLE |
| **Requirement Summary** | Plan and execute controlled deployment of AI systems to production, including rollout planning, user onboarding, and monitoring. |
| **Evidence to Look For** | Documented deployment plan or procedure for AI system rollout; evidence of controlled deployment (phased rollout, pilot testing); user onboarding records; evidence of deployment monitoring; evidence that deployment activities are documented; evidence that deployment plans are reviewed before significant AI system changes. |
| **Score** | [0-5] |
| **Evidence Found** | [Assessment notes] |
| **Gap Description** | [Description of gap, if any] |
| **Gap Severity** | [Critical / Major / Minor / Observation / N/A] |
| **Recommended Action** | [Specific action to close the gap] |

---

### W-A.6.2.6-01

| Field | Value |
|---|---|
| **Row ID** | W-A.6.2.6-01 |
| **Control** | A.6.2.6 — Operation and Monitoring of AI System |
| **AI-User Applicability** | FULLY APPLICABLE |
| **Requirement Summary** | Ensure ongoing AI system performance through monitoring, performance tracking, and issue identification. |
| **Evidence to Look For** | Documented monitoring procedure for AI systems; evidence of regular monitoring activity (logs, reports, dashboards); evidence that monitoring covers output quality, availability, and performance; evidence that issues identified through monitoring are escalated and addressed; evidence that monitoring frequency is appropriate to the risk level of each AI system. |
| **Score** | [0-5] |
| **Evidence Found** | [Assessment notes] |
| **Gap Description** | [Description of gap, if any] |
| **Gap Severity** | [Critical / Major / Minor / Observation / N/A] |
| **Recommended Action** | [Specific action to close the gap] |

---

### W-A.6.2.7-01

| Field | Value |
|---|---|
| **Row ID** | W-A.6.2.7-01 |
| **Control** | A.6.2.7 — Retirement of AI System |
| **AI-User Applicability** | PARTIALLY APPLICABLE |
| **Requirement Summary** | Plan and execute responsible decommissioning of AI systems, including data handling, user transition, and documentation. For AI users, this applies to decommissioning use of third-party AI tools (data migration, access removal, contract termination). |
| **Evidence to Look For** | Documented procedure for retiring AI tools; evidence that data handling is addressed when retiring AI systems (data retrieval, deletion, portability); evidence that user access is removed upon retirement; evidence that contract termination procedures address AI-specific considerations; records of any AI system retirements conducted. |
| **Score** | [0-5] |
| **Evidence Found** | [Assessment notes] |
| **Gap Description** | [Description of gap, if any] |
| **Gap Severity** | [Critical / Major / Minor / Observation / N/A] |
| **Recommended Action** | [Specific action to close the gap] |

---

### W-A.6.2.8-01

| Field | Value |
|---|---|
| **Row ID** | W-A.6.2.8-01 |
| **Control** | A.6.2.8 — Responsible AI System Integration |
| **AI-User Applicability** | FULLY APPLICABLE |
| **Requirement Summary** | Integrate AI systems responsibly into organizational processes and technical environments, including integration planning, testing, and validation. |
| **Evidence to Look For** | Evidence of integration planning before connecting AI systems to organizational processes or data; evidence of integration testing; evidence that integration risks were assessed before deployment; documentation of data flows between AI systems and organizational systems; evidence that integrations are reviewed when AI systems or organizational processes change. |
| **Score** | [0-5] |
| **Evidence Found** | [Assessment notes] |
| **Gap Description** | [Description of gap, if any] |
| **Gap Severity** | [Critical / Major / Minor / Observation / N/A] |
| **Recommended Action** | [Specific action to close the gap] |

---

### W-A.6.2.9-01

| Field | Value |
|---|---|
| **Row ID** | W-A.6.2.9-01 |
| **Control** | A.6.2.9 — AI System Documentation |
| **AI-User Applicability** | FULLY APPLICABLE |
| **Requirement Summary** | Maintain comprehensive documentation of AI systems including purpose, capabilities, limitations, operating parameters, and known constraints. |
| **Evidence to Look For** | Documented AI system records for each in-scope system (purpose, capabilities, limitations, data flows, vendor details, configuration); evidence that documentation is kept current; evidence that documentation is accessible to relevant personnel; AI system inventory as a foundation for this documentation; evidence that vendor-provided documentation is retained and referenced. |
| **Score** | [0-5] |
| **Evidence Found** | [Assessment notes] |
| **Gap Description** | [Description of gap, if any] |
| **Gap Severity** | [Critical / Major / Minor / Observation / N/A] |
| **Recommended Action** | [Specific action to close the gap] |

---

### W-A.6.2.10-01

| Field | Value |
|---|---|
| **Row ID** | W-A.6.2.10-01 |
| **Control** | A.6.2.10 — Defined Use and Misuse of AI System |
| **AI-User Applicability** | FULLY APPLICABLE |
| **Requirement Summary** | Define and communicate intended uses and explicitly prohibited uses of AI systems to all users and stakeholders. |
| **Evidence to Look For** | Documented acceptable use policy or guidelines for AI systems; evidence that intended uses are defined for each AI system; evidence that prohibited uses are explicitly stated; evidence that acceptable use guidelines are communicated to all personnel using AI systems; evidence that guidelines are updated when AI systems or their context changes; evidence of acknowledgment or training on acceptable use. |
| **Score** | [0-5] |
| **Evidence Found** | [Assessment notes] |
| **Gap Description** | [Description of gap, if any] |
| **Gap Severity** | [Critical / Major / Minor / Observation / N/A] |
| **Recommended Action** | [Specific action to close the gap] |

---

### W-A.6.2.11-01

| Field | Value |
|---|---|
| **Row ID** | W-A.6.2.11-01 |
| **Control** | A.6.2.11 — Management of Third-Party AI System Components |
| **AI-User Applicability** | FULLY APPLICABLE |
| **Requirement Summary** | Manage AI components sourced from third parties, including selection criteria, ongoing assessment, and performance monitoring. This is the single most important control for AI-user organizations — it governs the entire third-party AI supply chain. |
| **Evidence to Look For** | Documented vendor assessment process for AI providers; selection criteria for AI vendors (security, data handling, governance, model transparency); evidence of vendor due diligence conducted before adoption; ongoing vendor monitoring records; contractual terms addressing AI governance requirements; evidence that vendor performance is reviewed periodically; process for managing vendor changes (model updates, terms of service changes). |
| **Score** | *1* |
| **Evidence Found** | *The organization has a general vendor management process used for IT procurement. However, this process does not include AI-specific selection criteria, does not require vendors to demonstrate AI governance practices, and does not address model update management or AI-specific contractual terms. Vendor contracts with AI providers were reviewed and found to contain standard SaaS terms without AI governance provisions. No structured ongoing monitoring of AI vendor performance exists.* |
| **Gap Description** | *Third-party AI management is ad hoc. The organization has not established AI-specific vendor selection criteria, has not conducted structured due diligence on AI providers, and has not incorporated AI governance requirements into vendor contracts. Given that all in-scope AI systems are third-party provided, this gap represents a significant risk to the organization's ability to govern its AI use.* |
| **Gap Severity** | *Major* |
| **Recommended Action** | *Develop an AI vendor assessment framework that includes: (1) AI-specific selection criteria (data handling, model governance, incident response, transparency); (2) due diligence questionnaire for AI providers; (3) contractual requirements for AI governance (data processing terms, model change notification, audit rights); (4) ongoing monitoring process (periodic vendor reviews, monitoring of vendor communications about model changes). Apply to all existing AI vendors and incorporate into procurement process for future AI tool adoption.* |

**Domain A.6 Average Score:** [X.X] / 5.0

---

## Domain A.7 — Data for AI Systems

*Objective: Ensure the organization understands the role and impacts of data in AI systems and manages data appropriately.*

---

### W-A.7.2-01

| Field | Value |
|---|---|
| **Row ID** | W-A.7.2-01 |
| **Control** | A.7.2 — Data for Development and Enhancement of AI System |
| **AI-User Applicability** | PARTIALLY APPLICABLE |
| **Requirement Summary** | Define and implement data management processes related to AI system development, including data selection, acquisition, and preparation. For AI users, this applies only if the organization provides data for fine-tuning or customization of third-party AI; does not apply to core model development. |
| **Evidence to Look For** | Evidence of whether the organization provides data to AI vendors for fine-tuning or customization; if yes: documented data management process for data provided to vendors; data quality standards for vendor-provided data; data governance controls for data shared with AI providers; contractual terms governing vendor use of organizational data for model improvement. |
| **Score** | [0-5] |
| **Evidence Found** | [Assessment notes — note whether fine-tuning/customization is in scope] |
| **Gap Description** | [Description of gap, if any. If fine-tuning is not in scope, note partial applicability scope.] |
| **Gap Severity** | [Critical / Major / Minor / Observation / N/A] |
| **Recommended Action** | [Specific action to close the gap] |

---

### W-A.7.3-01

| Field | Value |
|---|---|
| **Row ID** | W-A.7.3-01 |
| **Control** | A.7.3 — Data Quality for ML and Data for AI System |
| **AI-User Applicability** | FULLY APPLICABLE |
| **Requirement Summary** | Ensure data quality across accuracy, completeness, relevance, timeliness, and representativeness for AI system inputs. |
| **Evidence to Look For** | Documented data quality standards for data fed into AI systems; evidence of data quality checks before data is used as AI input; evidence that data quality issues are identified and addressed; evidence that data quality is monitored on an ongoing basis; evidence that data quality considerations are included in AI system risk assessments. |
| **Score** | [0-5] |
| **Evidence Found** | [Assessment notes] |
| **Gap Description** | [Description of gap, if any] |
| **Gap Severity** | [Critical / Major / Minor / Observation / N/A] |
| **Recommended Action** | [Specific action to close the gap] |

---

### W-A.7.4-01

| Field | Value |
|---|---|
| **Row ID** | W-A.7.4-01 |
| **Control** | A.7.4 — Data Preparation |
| **AI-User Applicability** | PARTIALLY APPLICABLE |
| **Requirement Summary** | Properly prepare data for AI use, including cleaning, labeling, transformation, and format conversion. For AI users, this applies when preparing organizational data for input to AI tools (e.g., structuring prompts, cleaning datasets). |
| **Evidence to Look For** | Evidence of data preparation procedures for data used as AI inputs; evidence that data is cleaned and validated before use in AI systems; evidence that prompt engineering or data structuring practices are documented; evidence that data preparation activities are consistent and repeatable; evidence that data preparation is reviewed when AI systems or data sources change. |
| **Score** | [0-5] |
| **Evidence Found** | [Assessment notes] |
| **Gap Description** | [Description of gap, if any] |
| **Gap Severity** | [Critical / Major / Minor / Observation / N/A] |
| **Recommended Action** | [Specific action to close the gap] |

---

### W-A.7.5-01

| Field | Value |
|---|---|
| **Row ID** | W-A.7.5-01 |
| **Control** | A.7.5 — Data Acquisition and Collection |
| **AI-User Applicability** | PARTIALLY APPLICABLE |
| **Requirement Summary** | Ensure responsible data sourcing with proper consent, privacy protections, and representativeness considerations. For AI users, this applies to data the organization collects and feeds into AI systems. |
| **Evidence to Look For** | Evidence that data collection for AI use complies with applicable data protection requirements; evidence of consent mechanisms where required; evidence that data sources are assessed for representativeness and potential bias; evidence that data acquisition practices are documented; evidence that data protection impact assessments cover AI-related data collection. |
| **Score** | [0-5] |
| **Evidence Found** | [Assessment notes] |
| **Gap Description** | [Description of gap, if any] |
| **Gap Severity** | [Critical / Major / Minor / Observation / N/A] |
| **Recommended Action** | [Specific action to close the gap] |

---

### W-A.7.6-01

| Field | Value |
|---|---|
| **Row ID** | W-A.7.6-01 |
| **Control** | A.7.6 — Data Provenance |
| **AI-User Applicability** | PARTIALLY APPLICABLE |
| **Requirement Summary** | Track and document data origin, transformations, and lineage for data used in AI systems. For AI users, this applies to tracking the provenance of organizational data used as AI inputs. |
| **Evidence to Look For** | Evidence that data sources for AI inputs are documented; evidence that data transformations applied before AI use are recorded; evidence that data lineage can be traced for AI-related data; evidence that data provenance information is used in AI risk assessments; evidence that provenance tracking is updated when data sources or transformations change. |
| **Score** | [0-5] |
| **Evidence Found** | [Assessment notes] |
| **Gap Description** | [Description of gap, if any] |
| **Gap Severity** | [Critical / Major / Minor / Observation / N/A] |
| **Recommended Action** | [Specific action to close the gap] |

**Domain A.7 Average Score:** [X.X] / 5.0

---

## Domain A.8 — Information for Interested Parties

*Objective: Ensure interested parties have the information needed to understand and assess AI system risks and make informed decisions.*

---

### W-A.8.2-01

| Field | Value |
|---|---|
| **Row ID** | W-A.8.2-01 |
| **Control** | A.8.2 — Informing Interested Parties About AI System Interaction |
| **AI-User Applicability** | FULLY APPLICABLE |
| **Requirement Summary** | Notify individuals when they are interacting with an AI system through appropriate disclosure mechanisms. |
| **Evidence to Look For** | Evidence of AI disclosure mechanisms (notices, labels, disclosures in interfaces); evidence that customers are informed when interacting with AI-powered tools; evidence that employees are informed when AI systems are used in processes affecting them; evidence that disclosures are clear and accessible; evidence that disclosure practices are reviewed when AI systems change. |
| **Score** | [0-5] |
| **Evidence Found** | [Assessment notes] |
| **Gap Description** | [Description of gap, if any] |
| **Gap Severity** | [Critical / Major / Minor / Observation / N/A] |
| **Recommended Action** | [Specific action to close the gap] |

---

### W-A.8.3-01

| Field | Value |
|---|---|
| **Row ID** | W-A.8.3-01 |
| **Control** | A.8.3 — Informing Interested Parties About AI Outcomes |
| **AI-User Applicability** | FULLY APPLICABLE |
| **Requirement Summary** | Enable understanding of AI-driven decisions by communicating explanations of outcomes and key decision factors. |
| **Evidence to Look For** | Evidence that AI-driven decisions affecting individuals are explained; evidence that explanation mechanisms are in place (human review, explanation statements, appeal processes); evidence that the organization can explain the role of AI in decisions when requested; evidence that explanation practices are documented and consistently applied. |
| **Score** | [0-5] |
| **Evidence Found** | [Assessment notes] |
| **Gap Description** | [Description of gap, if any] |
| **Gap Severity** | [Critical / Major / Minor / Observation / N/A] |
| **Recommended Action** | [Specific action to close the gap] |

---

### W-A.8.4-01

| Field | Value |
|---|---|
| **Row ID** | W-A.8.4-01 |
| **Control** | A.8.4 — Access to Information About AI System Interaction |
| **AI-User Applicability** | FULLY APPLICABLE |
| **Requirement Summary** | Provide access to records of AI system interactions as required by law, contract, or organizational policy. |
| **Evidence to Look For** | Evidence that AI interaction logs are maintained; evidence that access to interaction records is provided when required; evidence that retention periods for AI interaction records are defined; evidence that access request processes are in place; evidence that log completeness and integrity are maintained. |
| **Score** | [0-5] |
| **Evidence Found** | [Assessment notes] |
| **Gap Description** | [Description of gap, if any] |
| **Gap Severity** | [Critical / Major / Minor / Observation / N/A] |
| **Recommended Action** | [Specific action to close the gap] |

---

### W-A.8.5-01

| Field | Value |
|---|---|
| **Row ID** | W-A.8.5-01 |
| **Control** | A.8.5 — Enabling Appropriate Human Actions in Response to AI Outputs |
| **AI-User Applicability** | FULLY APPLICABLE |
| **Requirement Summary** | Provide information that enables humans to make informed decisions when acting on AI outputs, including confidence levels and limitations. |
| **Evidence to Look For** | Evidence that AI outputs are presented with appropriate context (confidence indicators, caveats, limitations); evidence that personnel are trained to critically evaluate AI outputs; evidence that decision-making processes involving AI outputs include human review checkpoints; evidence that escalation procedures exist when AI outputs are uncertain or high-stakes; evidence that human override capability is maintained. |
| **Score** | [0-5] |
| **Evidence Found** | [Assessment notes] |
| **Gap Description** | [Description of gap, if any] |
| **Gap Severity** | [Critical / Major / Minor / Observation / N/A] |
| **Recommended Action** | [Specific action to close the gap] |

**Domain A.8 Average Score:** [X.X] / 5.0

---

## Domain A.9 — Use of AI Systems

*Objective: Ensure the organization uses AI systems responsibly and in accordance with its AI policy.*

---

### W-A.9.2-01

| Field | Value |
|---|---|
| **Row ID** | W-A.9.2-01 |
| **Control** | A.9.2 — Objectives for Responsible Use of AI System |
| **AI-User Applicability** | FULLY APPLICABLE |
| **Requirement Summary** | Define measurable objectives guiding the responsible use of AI systems across the organization. |
| **Evidence to Look For** | Documented responsible use objectives for AI systems; evidence that objectives are measurable and time-bound; evidence that objectives are aligned with the AI policy; evidence that objectives are communicated to relevant personnel; evidence that progress against objectives is monitored and reported. |
| **Score** | [0-5] |
| **Evidence Found** | [Assessment notes] |
| **Gap Description** | [Description of gap, if any] |
| **Gap Severity** | [Critical / Major / Minor / Observation / N/A] |
| **Recommended Action** | [Specific action to close the gap] |

---

### W-A.9.3-01

| Field | Value |
|---|---|
| **Row ID** | W-A.9.3-01 |
| **Control** | A.9.3 — Intended Use of AI System |
| **AI-User Applicability** | FULLY APPLICABLE |
| **Requirement Summary** | Ensure AI systems are used within their intended parameters; provide user guidance and monitor for scope creep. |
| **Evidence to Look For** | Documented intended use parameters for each AI system; evidence that users are informed of intended use boundaries; evidence that use cases are reviewed against intended parameters; evidence of monitoring for use outside intended parameters; evidence that scope creep (using AI for unvalidated purposes) is identified and addressed. |
| **Score** | [0-5] |
| **Evidence Found** | [Assessment notes] |
| **Gap Description** | [Description of gap, if any] |
| **Gap Severity** | [Critical / Major / Minor / Observation / N/A] |
| **Recommended Action** | [Specific action to close the gap] |

---

### W-A.9.4-01

| Field | Value |
|---|---|
| **Row ID** | W-A.9.4-01 |
| **Control** | A.9.4 — Processes for Responsible Use of AI System |
| **AI-User Applicability** | FULLY APPLICABLE |
| **Requirement Summary** | Establish operational processes for responsible AI use, including review procedures, escalation paths, and human checkpoints. |
| **Evidence to Look For** | Documented operational procedures for AI use; evidence of review workflows for AI outputs before action is taken; escalation procedures for AI-related issues; human checkpoint requirements in AI-assisted processes; evidence that procedures are followed in practice; evidence that procedures are reviewed and updated when AI systems or processes change. |
| **Score** | [0-5] |
| **Evidence Found** | [Assessment notes] |
| **Gap Description** | [Description of gap, if any] |
| **Gap Severity** | [Critical / Major / Minor / Observation / N/A] |
| **Recommended Action** | [Specific action to close the gap] |

---

### W-A.9.5-01

| Field | Value |
|---|---|
| **Row ID** | W-A.9.5-01 |
| **Control** | A.9.5 — Human Oversight Aspects |
| **AI-User Applicability** | FULLY APPLICABLE |
| **Requirement Summary** | Ensure appropriate human control over AI systems through override capability, intervention points, and defined oversight levels (human-in-the-loop, human-on-the-loop, or human-in-command). |
| **Evidence to Look For** | Documented human oversight requirements for each AI system; evidence that oversight level (human-in-the-loop, human-on-the-loop, human-in-command) is defined and appropriate to the risk level; evidence that override capability exists and is exercised; evidence that personnel understand their oversight responsibilities; evidence that oversight effectiveness is monitored; evidence that oversight requirements are reviewed when AI systems change. |
| **Score** | [0-5] |
| **Evidence Found** | [Assessment notes] |
| **Gap Description** | [Description of gap, if any] |
| **Gap Severity** | [Critical / Major / Minor / Observation / N/A] |
| **Recommended Action** | [Specific action to close the gap] |

**Domain A.9 Average Score:** [X.X] / 5.0

---

## Domain A.10 — Third-Party and Customer Relationships

*Objective: Ensure responsibilities and risks are appropriately managed when third parties are involved in the AI value chain.*

---

### W-A.10.2-01

| Field | Value |
|---|---|
| **Row ID** | W-A.10.2-01 |
| **Control** | A.10.2 — Suppliers of AI System Components |
| **AI-User Applicability** | FULLY APPLICABLE |
| **Requirement Summary** | Manage AI component suppliers through selection criteria, contractual requirements, ongoing assessment, and performance monitoring. |
| **Evidence to Look For** | Documented AI supplier management procedure; AI-specific vendor selection criteria; evidence of due diligence conducted on AI suppliers; contractual terms addressing AI governance (data handling, model change notification, incident response, audit rights); ongoing supplier performance monitoring records; evidence that supplier assessments are conducted periodically; process for managing supplier changes. |
| **Score** | [0-5] |
| **Evidence Found** | [Assessment notes] |
| **Gap Description** | [Description of gap, if any] |
| **Gap Severity** | [Critical / Major / Minor / Observation / N/A] |
| **Recommended Action** | [Specific action to close the gap] |

---

### W-A.10.3-01

| Field | Value |
|---|---|
| **Row ID** | W-A.10.3-01 |
| **Control** | A.10.3 — Shared ML Models |
| **AI-User Applicability** | PARTIALLY APPLICABLE |
| **Requirement Summary** | Manage the use of shared or pre-trained models, including assessing model provenance, suitability, limitations, and bias characteristics. Applies when using publicly available or shared pre-trained models (e.g., open-source LLMs); less relevant if exclusively using proprietary vendor APIs. |
| **Evidence to Look For** | Evidence of whether the organization uses open-source or shared pre-trained models; if yes: documented assessment of model provenance and suitability; evidence that model limitations and bias characteristics have been evaluated; evidence that shared model use is governed by the same controls as proprietary AI tools; evidence that model updates are monitored and assessed. |
| **Score** | [0-5] |
| **Evidence Found** | [Assessment notes — note whether shared/open-source models are in use] |
| **Gap Description** | [Description of gap, if any. If no shared models are in use, note partial applicability scope.] |
| **Gap Severity** | [Critical / Major / Minor / Observation / N/A] |
| **Recommended Action** | [Specific action to close the gap] |

---

### W-A.10.4-01

| Field | Value |
|---|---|
| **Row ID** | W-A.10.4-01 |
| **Control** | A.10.4 — Provision of AI System to Third Parties |
| **AI-User Applicability** | NOT APPLICABLE |
| **Requirement Summary** | Ensure responsible provision of AI systems or AI-powered services to customers, including documentation, support, and communication of limitations. |
| **Evidence to Look For** | N/A — Control excluded from scope. |
| **Score** | N/A |
| **Evidence Found** | N/A |
| **Gap Description** | *Not applicable. The organization does not provide AI systems or AI-powered services to third parties. This control targets organizations that embed AI outputs in services delivered to customers. Exclusion must be documented in the Statement of Applicability with this justification. **Important:** Confirm with client during scoping — if the client embeds AI outputs in products or services delivered to customers, reclassify this control to FULLY APPLICABLE.* |
| **Gap Severity** | N/A |
| **Recommended Action** | Document exclusion in the Statement of Applicability. Confirm with client that no AI-powered services are provided to third parties. If the client's products or services incorporate AI outputs delivered to customers, reassess applicability and reclassify accordingly. |

**Domain A.10 Average Score:** [X.X] / 5.0

---

# PART 3: ASSESSMENT SUMMARY

*Complete this section after all Part 1 and Part 2 rows have been scored. Calculate averages, count gaps by severity, and write the certification readiness verdict.*

---

## Overall Maturity Score

| Metric | Score |
|---|---|
| **Overall AIMS Maturity Score** | [X.X] / 5.0 |
| **Certification Readiness Threshold** | 3.0 / 5.0 |
| **Gap to Threshold** | [Δ] |
| **Certification Readiness Status** | [Below Threshold / At Threshold / Above Threshold] |

---

## Clause Group Averages

| Clause | Title | Sub-Clauses Assessed | Average Score | Gap to 3.0 | Status |
|---|---|---|---|---|---|
| **Clause 4** | Context of the Organization | 4 | [X.X] | [Δ] | [Below / At / Above] |
| **Clause 5** | Leadership | 3 | [X.X] | [Δ] | [Below / At / Above] |
| **Clause 6** | Planning | 7 | [X.X] | [Δ] | [Below / At / Above] |
| **Clause 7** | Support | 5 | [X.X] | [Δ] | [Below / At / Above] |
| **Clause 8** | Operation | 4 | [X.X] | [Δ] | [Below / At / Above] |
| **Clause 9** | Performance Evaluation | 3 | [X.X] | [Δ] | [Below / At / Above] |
| **Clause 10** | Improvement | 2 | [X.X] | [Δ] | [Below / At / Above] |
| **Overall Normative Average** | | **28** | **[X.X]** | **[Δ]** | |

---

## Annex A Domain Averages

| Domain | Title | Controls Assessed | Average Score | Gap to 3.0 | Status |
|---|---|---|---|---|---|
| **A.2** | Policies for AI | 2 | [X.X] | [Δ] | [Below / At / Above] |
| **A.3** | Internal Organization | 3 | [X.X] | [Δ] | [Below / At / Above] |
| **A.4** | Resources for AI Systems | 5 | [X.X] | [Δ] | [Below / At / Above] |
| **A.5** | Assessing Impacts of AI Systems | 3 | [X.X] | [Δ] | [Below / At / Above] |
| **A.6** | AI System Life Cycle | 8 (excl. 2 N/A) | [X.X] | [Δ] | [Below / At / Above] |
| **A.7** | Data for AI Systems | 5 | [X.X] | [Δ] | [Below / At / Above] |
| **A.8** | Information for Interested Parties | 4 | [X.X] | [Δ] | [Below / At / Above] |
| **A.9** | Use of AI Systems | 4 | [X.X] | [Δ] | [Below / At / Above] |
| **A.10** | Third-Party and Customer Relationships | 2 (excl. 1 N/A) | [X.X] | [Δ] | [Below / At / Above] |
| **Overall Annex A Average** | | **36 (excl. 3 N/A)** | **[X.X]** | **[Δ]** | |

*Note: N/A controls (A.6.2.2, A.6.2.3, A.10.4) are excluded from domain and overall averages.*

---

## Gap Count by Severity

| Severity | Normative Clauses | Annex A Controls | Total |
|---|---|---|---|
| **Critical** | [N] | [N] | [N] |
| **Major** | [N] | [N] | [N] |
| **Minor** | [N] | [N] | [N] |
| **Observation** | [N] | [N] | [N] |
| **N/A** | 0 | 3 | 3 |
| **Total Gaps (excl. N/A)** | [N] | [N] | [N] |

---

## Certification Readiness Verdict

**Overall Score:** [X.X] / 5.0 against a certification readiness threshold of 3.0.

[Write 3–5 sentences interpreting the overall score. Address: (1) whether the organization is above or below the threshold; (2) which clause groups or domains are strongest; (3) which areas require the most significant remediation; (4) an overall assessment of certification readiness timeline. Example below:]

*Example: The overall AIMS maturity score of 1.4/5.0 is significantly below the certification readiness threshold of 3.0. The organization demonstrates the strongest maturity in Clause 4 (Context) at 2.0/5.0, reflecting existing business context documentation that can be extended to the AIMS. The most significant gaps are in Clause 6 (Planning) at 0.3/5.0, where foundational requirements including AI risk assessment, impact assessment, and the Statement of Applicability have not been established. With focused remediation over an estimated 14–18 weeks, the organization is well-positioned to achieve certification readiness, given its existing governance infrastructure and demonstrated leadership commitment to the AIMS initiative.*

---

## Key Findings Summary

### Top Critical Gaps

| Rank | Row ID | Requirement | Score | Recommended Priority |
|---|---|---|---|---|
| 1 | [W-X.X-01] | [Requirement title] | [0-5] | P1 |
| 2 | [W-X.X-01] | [Requirement title] | [0-5] | P1 |
| 3 | [W-X.X-01] | [Requirement title] | [0-5] | P1 |

### Top Major Gaps

| Rank | Row ID | Requirement | Score | Recommended Priority |
|---|---|---|---|---|
| 1 | [W-X.X-01] | [Requirement title] | [0-5] | P2 |
| 2 | [W-X.X-01] | [Requirement title] | [0-5] | P2 |
| 3 | [W-X.X-01] | [Requirement title] | [0-5] | P2 |

### Identified Strengths

[List 2–4 existing capabilities that provide a foundation for AIMS implementation. Always identify genuine strengths — they anchor the remediation narrative and demonstrate that the assessment is balanced.]

- [STRENGTH 1 — e.g., "Existing ISO 27001 certification provides a mature document control, internal audit, and management review framework that can be extended to AIMS requirements with minimal additional effort."]
- [STRENGTH 2 — e.g., "Active executive sponsorship for AI governance, with clear understanding of the organization's AI risk profile at the leadership level."]
- [STRENGTH 3 — e.g., "Existing vendor management process provides a foundation for extending third-party controls to AI providers."]

---

## Workbook Sign-Off

| Field | Value |
|---|---|
| **Workbook Completed By** | [CONSULTANT NAME], Skill Tree AI |
| **Completion Date** | [DATE] |
| **Reviewed By** | [REVIEWER NAME] |
| **Review Date** | [DATE] |
| **Client Acknowledgment** | [CLIENT NAME / ROLE] |
| **Acknowledgment Date** | [DATE] |

*This workbook is a working document. Scores and findings reflect the state of [CLIENT NAME]'s AI governance practices as of the assessment date. This workbook does not constitute a certification audit or guarantee a specific certification outcome.*

---

## Version History

| Version | Date | Author | Changes |
|---|---|---|---|
| 0.1 | [DATE] | [AUTHOR] | Initial draft — assessment in progress |
| 0.2 | [DATE] | [AUTHOR] | Assessment complete; findings reviewed internally |
| 1.0 | [DATE] | [AUTHOR] | Final version issued to client with Gap Analysis Report |
| *[Add rows as needed]* | | | |

---

*ISO 42001 Readiness Service Toolkit | 02-Gap Analysis | Confidential Client Deliverable*
