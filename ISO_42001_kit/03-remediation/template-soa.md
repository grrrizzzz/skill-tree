# Statement of Applicability — ISO/IEC 42001:2023

> **Current as of:** March 2026 | ISO/IEC 42001:2023

---

<!-- ============================================================
HOW TO CUSTOMIZE THIS DOCUMENT — INTERNAL CONSULTANT USE ONLY
REMOVE THIS BLOCK BEFORE DELIVERING TO CLIENT
================================================================

PURPOSE OF THE SoA
The Statement of Applicability (SoA) is a mandatory AIMS document required by ISO/IEC 42001:2023
Clause 6.1.6. It is the first document a certification auditor will request. It demonstrates that
the organization has systematically evaluated all 39 Annex A controls, determined which apply to
its specific context, and justified any exclusions. Quality here is non-negotiable.

WHAT "APPLICABLE" MEANS
- YES: The control applies in full to this organization. The organization must implement it and
  produce evidence of implementation.
- PARTIAL: The control applies in a reduced or adapted scope. Document exactly which portions
  apply and which do not. Auditors will probe partial determinations — be specific.
- NO: The control does not apply. The justification must be airtight. For AI-user organizations,
  the standard exclusions are A.6.2.2 (Design/Development), A.6.2.3 (Training/Testing), and
  A.10.4 (Provision to Third Parties — confirm with client before excluding).

HOW APPLICABILITY IS DETERMINED
Applicability flows from the risk treatment process:
  1. Risk Assessment (Clause 6.1.2) → identifies risks from AI systems in scope
  2. Risk Treatment (Clause 6.1.3) → selects controls to treat those risks
  3. SoA (Clause 6.1.6) → documents which Annex A controls are selected and why

Controls are NOT selected arbitrarily. Each "Yes" or "Partial" should trace to a risk in the
Risk Assessment Register (AIMS-RISK-001) and a treatment decision in the Risk Treatment Plan.

HOW TO COMPLETE THIS TEMPLATE
1. Confirm the client's role: AI user only, or does the client also develop/train/provide AI?
   - If pure AI user: use the pre-populated applicability determinations in this template.
   - If client develops or provides AI: reclassify A.6.2.2, A.6.2.3, A.10.4 as applicable.
2. Update the Document Metadata table (Organization, Prepared By, Approved By, dates).
3. Review each "Partial" control with the client — confirm the scope limitation is accurate.
4. Populate the Implementation Status column as the engagement progresses.
5. Populate the Evidence Reference column when evidence exists (policy doc IDs, procedure names).
6. Populate the Risk Treatment Link column with the corresponding risk ID from AIMS-RISK-001.
7. Update Summary Statistics to reflect final applicability counts.
8. Obtain senior management sign-off before submitting to auditor.
9. DELETE THIS BLOCK before delivering to the client.

JUSTIFICATION QUALITY STANDARD
Every justification must answer: WHY is this control applicable/excluded for THIS organization?
Generic justifications ("applicable" or "N/A") will be challenged by auditors. Each justification
should reference the organization's role (AI user), the specific AI systems in scope, and the
specific reason the control does or does not apply.

EVIDENCE REFERENCE FORMAT
Use document IDs from the AIMS document register. Examples:
  AIMS-POL-001 = AI Policy
  AIMS-RISK-001 = Risk Assessment Register
  AIMS-INV-001 = AI System Inventory
  AIMS-PROC-XXX = Procedure documents
  AIMS-REC-XXX = Records

RISK TREATMENT LINK FORMAT
Reference the risk ID from the Risk Assessment Register. Example: RISK-007, RISK-012.
If a control is included for compliance reasons rather than a specific risk, note "Compliance — Clause 6.1.6".

============================================================ -->

---

## Document Metadata

| Field | Value |
|---|---|
| **Document ID** | AIMS-SOA-001 |
| **Version** | 1.0 |
| **Date** | [YYYY-MM-DD] |
| **Organization** | [Organization Name] |
| **Prepared By** | [Name, Role — ISO 42001 Consultant or AIMS Lead] |
| **Approved By** | [Name, Title — must be senior management, e.g., CEO, COO, or CTO] |
| **Next Review Date** | [YYYY-MM-DD — no later than 12 months from Date, or upon significant change] |
| **AIMS Scope Reference** | AIMS-SCOPE-001 |
| **Risk Assessment Reference** | AIMS-RISK-001 |
| **AI System Inventory Reference** | AIMS-INV-001 |

---

> **Legal Disclaimer:** This template does not constitute legal advice. The applicability determinations and justifications contained herein are provided as a starting point for organizations pursuing ISO/IEC 42001:2023 certification. Organizations should consult qualified legal counsel for questions about regulatory obligations, including EU AI Act classification, sector-specific AI regulations, and data protection requirements. Final applicability determinations must reflect the organization's specific context, AI systems in scope, and applicable legal requirements.

---

## Clause Traceability

This document fulfills the requirements of **ISO/IEC 42001:2023, Clause 6.1.6 — Statement of Applicability**, which requires the organization to produce a documented statement that:

- (a) Contains the necessary controls determined through the risk treatment process (Clause 6.1.3);
- (b) Contains justification for the inclusion of those controls;
- (c) Indicates whether the necessary controls are implemented or not; and
- (d) Contains justification for the exclusion of any Annex A controls.

This SoA covers all 39 controls in ISO/IEC 42001:2023 Annex A (domains A.2 through A.10).

---

## 1. Introduction

### 1.1 What This Document Is

This Statement of Applicability (SoA) is a required document of the organization's AI Management System (AIMS). It provides a complete, auditable record of how the organization has evaluated each of the 39 controls in ISO/IEC 42001:2023 Annex A, determined which controls apply to its specific context, and justified any exclusions.

The SoA is not a standalone document. It is the output of a structured process that begins with understanding the organization's context (Clause 4), identifying interested parties and their requirements (Clause 4.2), defining the AIMS scope (Clause 4.3), conducting a risk assessment (Clause 6.1.2), and selecting risk treatment options (Clause 6.1.3). The controls documented in this SoA were selected because they treat identified risks — not because they appear in the standard.

### 1.2 How Applicability Was Determined

Applicability determinations in this SoA follow a three-stage process:

**Stage 1 — Risk Assessment (AIMS-RISK-001):** The organization identified and assessed risks arising from its AI systems, including risks related to AI output quality, bias, data privacy, vendor dependency, and misuse. Each risk was evaluated for likelihood and impact.

**Stage 2 — Risk Treatment (Clause 6.1.3):** For each identified risk, the organization selected a treatment option: mitigate, accept, transfer, or avoid. Where mitigation was selected, specific Annex A controls were identified as the mechanism for risk reduction.

**Stage 3 — Control Selection and SoA (Clause 6.1.6):** Controls selected through the risk treatment process are marked as applicable in this SoA. Controls not selected are marked as not applicable, with justification. Controls that apply in a reduced scope are marked as partially applicable, with the applicable scope defined.

### 1.3 The Organization's Role as an AI User

The organization operates exclusively as an **AI user** — it uses AI systems developed, trained, and maintained by third-party vendors. The organization does not design, develop, or train AI models, and does not provide AI systems or AI-powered services to third parties.

This role has a direct and significant effect on Annex A applicability:

- **Controls targeting AI development activities** (A.6.2.2 — Design and Development; A.6.2.3 — Training and Testing) are **not applicable** because the organization does not perform these activities. These responsibilities rest with the AI vendors.
- **Controls targeting AI provision to third parties** (A.10.4) are **not applicable** in the default configuration of this template. *Consultants: confirm this determination with the client during scoping. If the client embeds AI outputs in services delivered to customers, reclassify A.10.4 as applicable.*
- **Controls targeting AI usage, governance, and vendor management** are **fully applicable** and represent the core of the organization's AIMS obligations.

The organization's AI systems in scope are documented in the AI System Inventory (AIMS-INV-001). All applicability determinations in this SoA are made with reference to those systems and the organization's role as their user.

### 1.4 Reference Documents

| Document | Document ID | Purpose |
|---|---|---|
| AI System Inventory | AIMS-INV-001 | Defines the AI systems in scope for the AIMS |
| Risk Assessment Register | AIMS-RISK-001 | Documents identified risks that drive control selection |
| Risk Treatment Plan | AIMS-RTP-001 | Documents treatment decisions and selected controls |
| AI Policy | AIMS-POL-001 | Establishes the organization's governing AI policy |
| AIMS Scope Document | AIMS-SCOPE-001 | Defines the boundaries of the AIMS |

---

## 2. Statement of Applicability — Control Table

The following table covers all 39 ISO/IEC 42001:2023 Annex A controls. Controls are grouped by domain (A.2 through A.10). For each control, the table records:

- **Applicable?** — Yes / Partial / No
- **Justification** — Why the control is included, partially included, or excluded
- **Implementation Status** — Not Started / In Progress / Implemented / Verified
- **Evidence Reference** — Document ID(s) that demonstrate implementation
- **Risk Treatment Link** — Risk ID(s) from AIMS-RISK-001 that this control treats

---

### Domain A.2 — Policies for AI

*Objective: Provide management direction and support for AI systems in accordance with business requirements, applicable laws, and responsible AI principles.*

| Control ID | Control Title | Applicable? | Justification for Inclusion / Exclusion | Implementation Status | Evidence Reference | Risk Treatment Link |
|---|---|---|---|---|---|---|
| **A.2.2** | AI Policy | **Yes** | The organization has established a formal AI Policy (AIMS-POL-001) governing responsible AI use across all in-scope AI systems. This control is fully applicable because every organization using AI — regardless of whether it builds or buys — requires a governing policy that establishes commitments to compliance, ethical principles, and a framework for AI objectives. The AI Policy is the foundational document of the AIMS. | Not Started | AIMS-POL-001 | Compliance — Clause 6.1.6 |
| **A.2.3** | Responsible AI Topics in AI Policy | **Yes** | The organization's AI Policy (AIMS-POL-001) addresses responsible AI principles including fairness, transparency, accountability, human oversight, privacy, safety, and societal impact. This control is fully applicable because the organization's use of third-party AI tools to process customer and employee data creates ethical obligations that must be reflected in policy. Usage decisions — not just development decisions — carry ethical and societal implications. | Not Started | AIMS-POL-001 | Compliance — Clause 6.1.6 |

---

### Domain A.3 — Internal Organization

*Objective: Establish accountability within the organization to support a responsible approach to AI.*

| Control ID | Control Title | Applicable? | Justification for Inclusion / Exclusion | Implementation Status | Evidence Reference | Risk Treatment Link |
|---|---|---|---|---|---|---|
| **A.3.2** | Roles and Responsibilities for AI | **Yes** | The organization has defined and allocated roles and responsibilities for AI-related activities, including AI system owners, risk owners, and AIMS management. This control is fully applicable because clear ownership is essential for AI-user organizations: someone must be accountable for AI tool selection decisions, usage oversight, vendor management, and risk escalation. Without defined roles, governance gaps are inevitable. | Not Started | AIMS-POL-001; AIMS-PROC-001 | [RISK-ID] |
| **A.3.3** | Reporting of AI Concerns | **Yes** | The organization has established a mechanism for personnel to report AI-related ethical, safety, or compliance concerns without fear of retaliation. This control is fully applicable because staff using third-party AI tools regularly encounter unexpected outputs, potential bias, or misuse scenarios that require a clear escalation path. A reporting mechanism is essential for early detection of AI-related incidents. | Not Started | AIMS-PROC-002 | [RISK-ID] |
| **A.3.4** | Impact of Organizational Changes | **Yes** | The organization assesses and manages AI implications when undergoing changes such as restructuring, vendor transitions, or technology migrations. This control is fully applicable because organizational changes directly affect AI tool governance: a team restructure may leave AI systems without an owner; a vendor switch may introduce new data flows and risks. Change management must include AI impact assessment. | Not Started | AIMS-PROC-003 | [RISK-ID] |

---

### Domain A.4 — Resources for AI Systems

*Objective: Ensure the organization identifies and provides all resources required for AI systems to understand and address associated risks.*

| Control ID | Control Title | Applicable? | Justification for Inclusion / Exclusion | Implementation Status | Evidence Reference | Risk Treatment Link |
|---|---|---|---|---|---|---|
| **A.4.2** | Resources Related to AI Systems | **Yes** | The organization identifies and documents all resources needed for AI activities, including human, technical, financial, and infrastructure resources. This control is fully applicable because AI-user organizations must budget for software licenses, integration effort, monitoring tools, and skilled personnel. Inadequate resourcing is a primary cause of AIMS failure — controls cannot be implemented without the resources to support them. | Not Started | AIMS-PROC-004 | [RISK-ID] |
| **A.4.3** | Competencies Related to AI Systems | **Yes** | The organization ensures personnel involved in AI activities have the required competencies, identifies skill gaps, provides training, and maintains competency records. This control is fully applicable because staff need specific competencies to evaluate AI outputs critically, understand model limitations, recognize bias, and use tools responsibly. Competency gaps in AI-user organizations are a direct risk to output quality and responsible use. | Not Started | AIMS-PROC-005; AIMS-REC-001 | [RISK-ID] |
| **A.4.4** | Awareness of Responsible Use of AI Systems | **Yes** | The organization ensures all personnel are aware of the AI policy, relevant risks, ethical considerations, and their responsibilities regarding AI systems. This control is fully applicable because every staff member who interacts with an AI tool — even casually — needs baseline awareness of responsible use, data handling obligations, and how to report concerns. Awareness is the first line of defense against AI misuse. | Not Started | AIMS-PROC-006; AIMS-REC-002 | [RISK-ID] |
| **A.4.5** | Consultation | **Yes** | The organization engages relevant stakeholders when making significant AI decisions that affect them, including decisions to adopt, modify, or retire AI tools. This control is fully applicable because AI adoption decisions affect employees whose workflows change, customers whose data is processed, and partners whose interactions are mediated by AI. Consultation ensures these impacts are understood before decisions are finalized. | Not Started | AIMS-PROC-007 | [RISK-ID] |
| **A.4.6** | Communication About the AI System | **Yes** | The organization communicates relevant information about AI systems to interested parties, including capabilities, limitations, and intended use. This control is fully applicable because transparency about AI tool usage is both an ethical obligation and an emerging regulatory requirement. Internal teams need to understand what AI tools can and cannot do; external stakeholders need to know when AI is involved in decisions that affect them. | Not Started | AIMS-PROC-008 | [RISK-ID] |

---

### Domain A.5 — Assessing Impacts of AI Systems

*Objective: Assess AI system impacts on individuals, groups, and society throughout the system lifecycle.*

| Control ID | Control Title | Applicable? | Justification for Inclusion / Exclusion | Implementation Status | Evidence Reference | Risk Treatment Link |
|---|---|---|---|---|---|---|
| **A.5.2** | AI System Risk Assessment | **Yes** | The organization identifies and assesses risks from AI systems across technical, organizational, ethical, and societal dimensions, and conducts initial and periodic reassessments. This control is fully applicable because even third-party AI introduces significant risks — biased outputs, data leakage, over-reliance, vendor failure — that must be formally assessed. The risk assessment is the foundation of the entire AIMS and feeds directly into this SoA. | Not Started | AIMS-RISK-001 | Compliance — Clause 6.1.2 |
| **A.5.3** | AI System Impact Assessment | **Yes** | The organization evaluates the impacts of AI systems on individuals and groups, including potential harms, discrimination, and privacy effects, and documents mitigations. This control is fully applicable because the organization uses AI tools to process customer and employee data and to support decisions that affect people. Impact assessment is required regardless of who built the AI — the organization is responsible for the consequences of how it uses these tools. | Not Started | AIMS-RISK-001; AIMS-REC-003 | [RISK-ID] |
| **A.5.4** | Impact of AI System Documentation | **Yes** | The organization documents impact assessment results, including impacts identified, mitigations applied, and residual risks, and keeps documentation current as systems change. This control is fully applicable because documented impact records are required for audit evidence and for demonstrating ongoing monitoring of third-party AI tools. Documentation also enables the organization to track whether mitigations remain effective as AI systems evolve. | Not Started | AIMS-REC-003 | [RISK-ID] |

---

### Domain A.6 — AI System Life Cycle

*Objective: Define criteria and requirements for each stage of the AI system life cycle to ensure responsible deployment and operation.*

| Control ID | Control Title | Applicable? | Justification for Inclusion / Exclusion | Implementation Status | Evidence Reference | Risk Treatment Link |
|---|---|---|---|---|---|---|
| **A.6.2.2** | Design and Development of AI System | **No** | The organization does not design or develop AI systems. All AI capabilities in scope are procured from third-party vendors (e.g., Microsoft, Salesforce, OpenAI, and similar providers). Design and development responsibilities — including requirements definition, architecture decisions, and development standards — rest entirely with the AI vendors. This control is excluded because the organization acts exclusively as an AI user. *Note: If the organization develops custom AI features, fine-tunes models, or builds AI-powered products, reclassify this control as applicable.* | N/A — Excluded | N/A | N/A |
| **A.6.2.3** | Training and Testing AI Model | **No** | The organization does not train or test AI models. Model training, testing (functional, performance, bias, security, robustness), and validation are the responsibility of the AI vendors from whom the organization procures AI services. The organization relies on vendor-provided testing evidence and model cards where available. This control is excluded because the organization acts exclusively as an AI user. *Note: If the organization uses vendor fine-tuning capabilities or trains custom models, reclassify this control as applicable.* | N/A — Excluded | N/A | N/A |
| **A.6.2.4** | Verification and Validation of AI System | **Partial** | This control applies in the context of verifying and validating that a third-party AI tool meets the organization's requirements before adoption and on an ongoing basis — not in the context of building verification and validation processes for AI development. The organization conducts pre-adoption evaluation of AI tools (fitness for purpose, data handling, performance against use-case requirements) and periodic re-validation as tools evolve. The development-phase V&V activities described in the full control are not applicable. | Not Started | AIMS-PROC-009; AIMS-REC-004 | [RISK-ID] |
| **A.6.2.5** | Deployment of AI System | **Yes** | The organization plans and executes controlled deployment of AI tools to production, including rollout planning, user onboarding, configuration management, and initial monitoring. This control is fully applicable because deploying third-party AI tools within the organization requires the same discipline as any significant technology deployment: phased rollout, user training, configuration documentation, and monitoring from day one. | Not Started | AIMS-PROC-010 | [RISK-ID] |
| **A.6.2.6** | Operation and Monitoring of AI System | **Yes** | The organization ensures ongoing AI system performance through monitoring, performance tracking, and issue identification. This is a core control for AI-user organizations — monitoring third-party AI output quality, availability, accuracy, and performance is the primary mechanism for detecting when a tool is no longer performing as expected. This control is fully applicable and is one of the highest-priority controls for the organization's AIMS. | Not Started | AIMS-PROC-011; AIMS-REC-005 | [RISK-ID] |
| **A.6.2.7** | Retirement of AI System | **Partial** | This control applies to the decommissioning of third-party AI tools from the organization's environment, including data migration, access removal, contract termination, and user transition. It does not apply to the retirement of proprietary AI systems, as the organization does not own or operate any. The scope of this control is narrower for AI-user organizations but remains important: retiring an AI tool without proper data handling and access management creates residual risk. | Not Started | AIMS-PROC-012 | [RISK-ID] |
| **A.6.2.8** | Responsible AI System Integration | **Yes** | The organization integrates third-party AI systems responsibly into organizational processes and technical environments, including integration planning, testing, and validation of data flows. This control is fully applicable because integrating AI tools into business workflows, APIs, and decision processes requires careful planning to avoid unintended data exposure, process disruption, or over-reliance on AI outputs. Integration quality directly affects the reliability and safety of AI-assisted processes. | Not Started | AIMS-PROC-013 | [RISK-ID] |
| **A.6.2.9** | AI System Documentation | **Yes** | The organization maintains comprehensive documentation of each AI system in use, including purpose, capabilities, limitations, operating parameters, configuration details, data flows, and vendor SLA terms. This control is fully applicable because AI-user organizations must be able to demonstrate to auditors — and to themselves — exactly what AI tools are in use, how they are configured, what data they process, and what their known limitations are. The AI System Inventory (AIMS-INV-001) is the primary vehicle for this documentation. | Not Started | AIMS-INV-001; AIMS-PROC-014 | [RISK-ID] |
| **A.6.2.10** | Defined Use and Misuse of AI System | **Yes** | The organization defines and communicates intended uses and explicitly prohibited uses of AI systems to all users and stakeholders. This control is fully applicable and is critical for AI-user organizations: acceptable use policies must clearly define what staff can and cannot do with AI tools, including prohibitions on inputting sensitive data, using AI for prohibited purposes, or relying on AI outputs without appropriate human review. Misuse of AI tools is a primary risk for organizations that have not defined clear boundaries. | Not Started | AIMS-POL-001; AIMS-PROC-015 | [RISK-ID] |
| **A.6.2.11** | Management of Third-Party AI System Components | **Yes** | The organization manages AI components sourced from third parties through defined selection criteria, contractual requirements, ongoing assessment, and performance monitoring. This is the single most important control for AI-user organizations — it governs the entire third-party AI supply chain. Every AI tool in scope was procured from a vendor, and the organization's ability to manage the risks of those tools depends on robust vendor management practices. This control is fully applicable and is a primary focus of the AIMS. | Not Started | AIMS-PROC-016; AIMS-REC-006 | [RISK-ID] |

---

### Domain A.7 — Data for AI Systems

*Objective: Ensure the organization understands the role and impacts of data in AI systems and manages data appropriately.*

| Control ID | Control Title | Applicable? | Justification for Inclusion / Exclusion | Implementation Status | Evidence Reference | Risk Treatment Link |
|---|---|---|---|---|---|---|
| **A.7.2** | Data for Development and Enhancement of AI System | **Partial** | This control applies if the organization provides data for fine-tuning, customization, or enhancement of third-party AI tools (e.g., uploading organizational documents to train a custom AI assistant, or providing labeled data to a vendor for model improvement). It does not apply to core model development, which is the vendor's responsibility. *Consultants: confirm with the client whether any vendor relationships involve data contribution for model training or fine-tuning. If yes, this control applies in full.* | Not Started | [Confirm with client] | [RISK-ID] |
| **A.7.3** | Data Quality for ML and Data for AI System | **Yes** | The organization ensures data quality across accuracy, completeness, relevance, timeliness, and representativeness for AI system inputs. This control is fully applicable because the quality of data fed into third-party AI tools directly determines the quality of AI outputs — garbage in, garbage out. The organization is responsible for the data it provides to AI systems, even when it does not control the underlying model. Poor input data quality is a primary source of AI output errors and bias. | Not Started | AIMS-PROC-017 | [RISK-ID] |
| **A.7.4** | Data Preparation | **Partial** | This control applies when the organization prepares organizational data for input to AI tools, including structuring prompts, cleaning datasets, formatting data for API calls, and transforming data for AI consumption. The scope is narrower than for AI developers: the organization is not responsible for training data preparation, only for the preparation of data it actively provides to AI systems during operation. This is a meaningful obligation for organizations that regularly feed structured data into AI tools. | Not Started | AIMS-PROC-018 | [RISK-ID] |
| **A.7.5** | Data Acquisition and Collection | **Partial** | This control applies to data the organization collects and feeds into AI systems, including ensuring proper consent, privacy protections, and representativeness considerations for that data. It does not apply to training data acquisition, which is the vendor's responsibility. The organization must ensure that data it provides to AI tools was collected lawfully, with appropriate consent, and is representative of the population it is intended to describe. | Not Started | AIMS-PROC-019 | [RISK-ID] |
| **A.7.6** | Data Provenance | **Partial** | This control applies to tracking the origin, transformations, and lineage of organizational data used as AI inputs. The organization must be able to demonstrate where its AI input data came from, how it was processed before being provided to the AI system, and what transformations occurred. The vendor is responsible for training data provenance. This control is partially applicable because the organization's data provenance obligations are limited to the data it controls and provides to AI systems. | Not Started | AIMS-PROC-020; AIMS-REC-007 | [RISK-ID] |

---

### Domain A.8 — Information for Interested Parties

*Objective: Ensure interested parties have the information needed to understand and assess AI system risks and make informed decisions.*

| Control ID | Control Title | Applicable? | Justification for Inclusion / Exclusion | Implementation Status | Evidence Reference | Risk Treatment Link |
|---|---|---|---|---|---|---|
| **A.8.2** | Informing Interested Parties About AI System Interaction | **Yes** | The organization notifies individuals when they are interacting with an AI system through appropriate disclosure mechanisms. This control is fully applicable because the organization uses AI tools in customer-facing and employee-facing contexts. Individuals have a right to know when they are interacting with AI — this is both an ethical obligation and an emerging regulatory requirement under frameworks including the EU AI Act. Disclosure must be clear, timely, and accessible. | Not Started | AIMS-PROC-021 | [RISK-ID] |
| **A.8.3** | Informing Interested Parties About AI Outcomes | **Yes** | The organization enables understanding of AI-driven decisions by communicating explanations of outcomes and key decision factors to affected individuals. This control is fully applicable because the organization uses AI tools that influence decisions affecting people — including hiring support, customer service, and operational decisions. When AI outputs influence consequential decisions, the organization must be able to explain the AI's role and the basis for the outcome. | Not Started | AIMS-PROC-022 | [RISK-ID] |
| **A.8.4** | Access to Information About AI System Interaction | **Yes** | The organization maintains and provides access to records of AI system interactions as required by law, contract, or organizational policy. This control is fully applicable because regulatory obligations (including data protection laws and sector-specific requirements) may require the organization to produce records of AI interactions on request. The organization must maintain interaction logs for in-scope AI systems and have a process for responding to access requests. | Not Started | AIMS-PROC-023; AIMS-REC-008 | [RISK-ID] |
| **A.8.5** | Enabling Appropriate Human Actions in Response to AI Outputs | **Yes** | The organization provides information that enables humans to make informed decisions when acting on AI outputs, including confidence levels, caveats, and known limitations. This control is fully applicable because staff acting on AI recommendations — whether in customer service, operations, or decision support — need sufficient context to exercise proper judgment. Presenting AI outputs without appropriate caveats creates over-reliance risk and undermines human oversight. | Not Started | AIMS-PROC-024 | [RISK-ID] |

---

### Domain A.9 — Use of AI Systems

*Objective: Ensure the organization uses AI systems responsibly and in accordance with its AI policy.*

| Control ID | Control Title | Applicable? | Justification for Inclusion / Exclusion | Implementation Status | Evidence Reference | Risk Treatment Link |
|---|---|---|---|---|---|---|
| **A.9.2** | Objectives for Responsible Use of AI System | **Yes** | The organization defines measurable objectives guiding the responsible use of AI systems across the organization. This control is fully applicable because AI-user organizations need clear, measurable targets for what responsible AI usage looks like in their operational context — not just aspirational statements. Objectives provide the basis for monitoring, management review, and continual improvement of the AIMS. | Not Started | AIMS-POL-001; AIMS-PROC-025 | Compliance — Clause 6.1.6 |
| **A.9.3** | Intended Use of AI System | **Yes** | The organization ensures AI systems are used within their intended parameters, provides user guidance, and monitors for scope creep where AI tools are repurposed beyond their validated use cases. This control is fully applicable because preventing "mission creep" — where staff use AI tools for purposes beyond their validated scope — is a primary AI-user responsibility. Each AI system in scope has a defined intended use documented in the AI System Inventory (AIMS-INV-001). | Not Started | AIMS-INV-001; AIMS-PROC-026 | [RISK-ID] |
| **A.9.4** | Processes for Responsible Use of AI System | **Yes** | The organization establishes operational processes for responsible AI use, including review procedures, escalation paths, and human checkpoints for AI-assisted decisions. This control is fully applicable because day-to-day operational processes — how staff interact with AI tools, how outputs are reviewed, how concerns are escalated — are the practical expression of the AI Policy. Without defined processes, the policy remains aspirational. | Not Started | AIMS-PROC-027 | [RISK-ID] |
| **A.9.5** | Human Oversight Aspects | **Yes** | The organization ensures appropriate human control over AI systems through override capability, defined intervention points, and documented oversight levels (human-in-the-loop, human-on-the-loop, or human-in-command) appropriate to each AI system's risk level. This control is fully applicable and is arguably the most critical control for AI-user organizations. The organization must define, for each AI system in scope, the level of human oversight required and the mechanisms by which humans can intervene, override, or reject AI outputs. | Not Started | AIMS-PROC-028; AIMS-REC-009 | [RISK-ID] |

---

### Domain A.10 — Third-Party and Customer Relationships

*Objective: Ensure responsibilities and risks are appropriately managed when third parties are involved in the AI value chain.*

| Control ID | Control Title | Applicable? | Justification for Inclusion / Exclusion | Implementation Status | Evidence Reference | Risk Treatment Link |
|---|---|---|---|---|---|---|
| **A.10.2** | Suppliers of AI System Components | **Yes** | The organization manages AI component suppliers through defined selection criteria, contractual requirements, ongoing assessment, and performance monitoring. This control is fully applicable and is a core control for AI-user organizations — it governs vendor selection, due diligence, contractual obligations (data processing agreements, SLAs, security requirements), and ongoing supplier monitoring. Every AI tool in scope was procured from a vendor, and the organization's risk exposure is directly tied to the quality of its vendor management practices. | Not Started | AIMS-PROC-016; AIMS-REC-006 | [RISK-ID] |
| **A.10.3** | Shared ML Models | **Partial** | This control applies when the organization uses publicly available or shared pre-trained models (e.g., open-source large language models, Hugging Face models, or community-maintained AI models). It requires assessing model provenance, suitability, limitations, and bias characteristics before use. This control is less relevant if the organization exclusively uses proprietary vendor APIs (e.g., OpenAI API, Microsoft Azure AI) where the vendor manages the underlying model. *Consultants: confirm whether the client uses any open-source or shared models. If yes, this control applies in full.* | Not Started | [Confirm with client] | [RISK-ID] |
| **A.10.4** | Provision of AI System to Third Parties | **No** | The organization does not provide AI systems or AI-powered services to third parties. The organization uses AI tools internally for its own operations and does not embed AI outputs in products or services delivered to customers. This control is excluded because the organization acts exclusively as an AI user, not as an AI provider. *Note: Confirm this determination with the client during scoping. If the client embeds AI outputs in services delivered to customers (e.g., AI-generated reports, AI-powered customer portals, AI-assisted recommendations provided to clients), reclassify this control as fully applicable.* | N/A — Excluded | N/A | N/A |

---

## 3. Summary Statistics

| Metric | Count |
|---|---|
| **Total Annex A Controls** | **39** |
| **Applicable (Yes)** | **29** |
| **Partially Applicable (Partial)** | **7** |
| **Not Applicable — Excluded (No)** | **3** |

### Applicability by Domain

| Domain | Total Controls | Yes | Partial | No |
|---|---|---|---|---|
| A.2 — Policies for AI | 2 | 2 | 0 | 0 |
| A.3 — Internal Organization | 3 | 3 | 0 | 0 |
| A.4 — Resources for AI Systems | 5 | 5 | 0 | 0 |
| A.5 — Assessing Impacts of AI Systems | 3 | 3 | 0 | 0 |
| A.6 — AI System Life Cycle | 10 | 6 | 2 | 2 |
| A.7 — Data for AI Systems | 5 | 1 | 4 | 0 |
| A.8 — Information for Interested Parties | 4 | 4 | 0 | 0 |
| A.9 — Use of AI Systems | 4 | 4 | 0 | 0 |
| A.10 — Third-Party and Customer Relationships | 3 | 1 | 1 | 1 |
| **Total** | **39** | **29** | **7** | **3** |

### Implementation Status Summary

*To be updated as the engagement progresses.*

| Status | Count |
|---|---|
| Not Started | 36 |
| In Progress | 0 |
| Implemented | 0 |
| Verified | 0 |
| N/A (Excluded) | 3 |
| **Total** | **39** |

---

## 4. Exclusion Justification Register

This section provides the full justification for each control excluded from the organization's AIMS. Exclusion justifications must be specific, accurate, and defensible to a certification auditor. Generic exclusions ("not applicable to our business") are insufficient.

---

### A.6.2.2 — Design and Development of AI System

**Applicability Determination:** Not Applicable — Excluded

**Full Justification:**

The organization does not design or develop AI systems. All AI capabilities within the AIMS scope are procured from third-party vendors through commercial product subscriptions, SaaS agreements, or API access arrangements. The organization has no AI development team, no model architecture responsibilities, and no involvement in the technical design of the AI systems it uses.

The control requires organizations to apply responsible design and development practices including requirements definition, design decisions, and development standards. These activities are performed entirely by the AI vendors (e.g., Microsoft, Salesforce, OpenAI, and similar providers) and are governed by those vendors' own development practices, which the organization evaluates through vendor due diligence (A.10.2).

The organization's obligations with respect to AI system design are limited to: (a) specifying its requirements when selecting AI tools (addressed under A.6.2.4 — Verification and Validation), and (b) assessing vendor development practices as part of supplier management (addressed under A.10.2 — Suppliers of AI System Components).

**Exclusion Condition:** This exclusion is valid only while the organization acts exclusively as an AI user. If the organization begins designing or developing AI systems — including building custom models, fine-tuning foundation models, or developing AI-powered products — this control must be reclassified as applicable.

---

### A.6.2.3 — Training and Testing AI Model

**Applicability Determination:** Not Applicable — Excluded

**Full Justification:**

The organization does not train or test AI models. Model training, testing (functional, performance, bias, security, and robustness testing), and pre-deployment validation are the responsibility of the AI vendors from whom the organization procures AI services. The organization has no access to model weights, training infrastructure, or training datasets.

The control requires organizations to ensure AI models are properly trained, tested, and validated before deployment. For the organization's in-scope AI systems, this responsibility rests with the vendors. The organization relies on vendor-provided evidence of testing (model cards, security assessments, third-party audits, and compliance certifications) as part of its vendor due diligence process (A.10.2).

The organization's obligations with respect to AI model testing are limited to: (a) requesting and reviewing vendor testing evidence during supplier assessment, and (b) validating that AI tools perform as expected in the organization's specific use context (addressed under A.6.2.4 — Verification and Validation).

**Exclusion Condition:** This exclusion is valid only while the organization acts exclusively as an AI user. If the organization begins training AI models — including using vendor fine-tuning capabilities with organizational data — this control must be reclassified as applicable for those activities.

---

### A.10.4 — Provision of AI System to Third Parties

**Applicability Determination:** Not Applicable — Excluded

**Full Justification:**

The organization does not provide AI systems or AI-powered services to third parties. The organization uses AI tools exclusively for internal operations and does not embed AI outputs in products, reports, or services delivered to customers or other external parties. The organization is an AI user, not an AI provider.

The control requires organizations that provide AI systems or AI-powered services to third parties to ensure responsible provision, including documentation, support, and communication of limitations. Because the organization does not perform this activity, the control does not apply.

**Critical Scoping Note:** This exclusion must be confirmed with the client during the scoping phase of the engagement. The exclusion is invalid if the client:
- Delivers AI-generated reports, analyses, or recommendations to customers as part of a service offering
- Operates a customer-facing portal or product that incorporates AI-powered features
- Provides AI-assisted outputs (e.g., AI-generated content, AI-powered scoring, AI-driven recommendations) to external parties as part of a commercial relationship
- Resells or white-labels AI capabilities to customers

If any of the above conditions apply, reclassify A.10.4 as **Fully Applicable** and implement the corresponding controls.

---

## 5. Approval

This Statement of Applicability has been reviewed and approved by senior management. The approval below confirms that:

1. The organization's senior management has reviewed and accepted the applicability determinations in this document.
2. The exclusions documented in Section 4 accurately reflect the organization's role and activities.
3. The organization commits to implementing the applicable controls and maintaining this SoA as a living document.
4. This SoA will be reviewed at least annually and updated whenever significant changes occur to the organization's AI systems, risk profile, or business activities.

| Role | Name | Signature | Date |
|---|---|---|---|
| **Approving Authority** (Senior Management) | [Name] | __________________ | [YYYY-MM-DD] |
| **AIMS Lead / Prepared By** | [Name] | __________________ | [YYYY-MM-DD] |
| **ISO 42001 Consultant** | [Name] | __________________ | [YYYY-MM-DD] |

> **Note:** The Approving Authority must be a member of senior management with authority over the organization's AI governance. Appropriate titles include Chief Executive Officer, Chief Operating Officer, Chief Technology Officer, or equivalent. Delegation to a non-senior-management role is not acceptable for this approval.

---

## 6. Control Implementation Guidance Notes

This section provides supplementary guidance for implementing the highest-priority controls for AI-user organizations. These notes are intended for the AIMS Lead and consultant team. They do not replace the full control requirements but highlight the most common implementation gaps observed during ISO 42001 engagements.

---

### A.6.2.11 — Management of Third-Party AI System Components (Priority: Critical)

This is the single most consequential control for AI-user organizations. Every AI risk the organization faces flows through its vendor relationships. Implementation requires:

**Vendor Selection Criteria:** Document the criteria used to evaluate AI vendors before adoption. Minimum criteria should include: data processing agreement availability, security certifications (SOC 2 Type II, ISO 27001), model transparency (model cards, bias testing evidence), incident response SLAs, and data residency commitments.

**Contractual Requirements:** Ensure all AI vendor contracts include: data processing agreements (DPAs) compliant with applicable privacy law, provisions for audit rights or third-party audit reports, SLA commitments for availability and performance, data deletion obligations upon contract termination, and notification requirements for material changes to the AI system.

**Ongoing Assessment:** Establish a periodic vendor review cycle (minimum annual) that reassesses vendor performance, reviews updated security certifications, evaluates changes to the AI system that may affect the organization's risk profile, and confirms continued compliance with contractual requirements.

**Evidence to Collect:** Signed DPAs for all in-scope AI vendors; vendor security certifications; completed vendor assessment questionnaires; records of periodic vendor reviews; escalation records for vendor performance issues.

---

### A.9.5 — Human Oversight Aspects (Priority: Critical)

Human oversight is the primary mechanism by which the organization maintains control over AI-assisted processes. Implementation requires defining, for each AI system in scope, the appropriate oversight level:

| Oversight Level | Definition | When to Apply |
|---|---|---|
| **Human-in-the-Loop** | A human reviews and approves every AI output before it takes effect | High-stakes decisions (hiring, credit, medical, legal); high-risk AI systems |
| **Human-on-the-Loop** | AI acts autonomously but a human monitors and can intervene | Medium-risk processes; AI outputs that are reversible |
| **Human-in-Command** | Humans set parameters and can override or shut down the AI system | Lower-risk, high-volume processes; AI outputs that are easily corrected |

**Evidence to Collect:** Documented oversight level for each AI system in AIMS-INV-001; process documentation showing human review checkpoints; records of human overrides or interventions; training records confirming staff understand their oversight responsibilities.

---

### A.5.2 — AI System Risk Assessment (Priority: High)

The risk assessment is the foundation of the AIMS. For AI-user organizations, the risk assessment must address risks that are specific to the use of third-party AI, including:

- **Output quality risk:** AI produces inaccurate, biased, or misleading outputs that affect decisions
- **Data privacy risk:** Sensitive data is inadvertently shared with AI vendors or exposed through AI outputs
- **Vendor dependency risk:** Over-reliance on a single AI vendor creates business continuity exposure
- **Misuse risk:** Staff use AI tools for purposes beyond their validated scope
- **Transparency risk:** AI-driven decisions cannot be explained to affected individuals
- **Regulatory risk:** AI tool usage creates compliance exposure under applicable laws (GDPR, EU AI Act, sector regulations)

**Evidence to Collect:** Completed Risk Assessment Register (AIMS-RISK-001) with all identified risks, likelihood/impact ratings, and treatment decisions; records of risk assessment review meetings; evidence that risk assessment was updated following significant changes.

---

### A.8.2 — Informing Interested Parties About AI System Interaction (Priority: High)

AI disclosure obligations are increasing across jurisdictions. Implementation requires:

**Internal Disclosure:** Ensure employees know when AI tools are being used in processes that affect them (e.g., AI-assisted performance review, AI-powered scheduling). Document disclosure mechanisms in relevant HR and operational procedures.

**External Disclosure:** Ensure customers and partners know when they are interacting with AI-powered systems (e.g., AI chatbots, AI-generated communications, AI-assisted service delivery). Disclosure must be clear, prominent, and provided before or at the point of AI interaction — not buried in terms and conditions.

**Regulatory Alignment:** Review disclosure requirements under applicable law. The EU AI Act imposes specific disclosure obligations for certain AI system categories. Sector-specific regulations (financial services, healthcare, employment) may impose additional requirements.

**Evidence to Collect:** Disclosure language used in customer-facing communications; screenshots or records of AI disclosure mechanisms; legal review of disclosure adequacy; records of disclosure updates following regulatory changes.

---

### A.6.2.6 — Operation and Monitoring of AI System (Priority: High)

Ongoing monitoring is how the organization detects when AI tools are no longer performing as expected. Implementation requires:

**Performance Metrics:** Define measurable performance indicators for each AI system in scope. Examples: output accuracy rate, user satisfaction scores, error/hallucination rate, response time, availability uptime.

**Monitoring Frequency:** Establish monitoring cadence appropriate to the risk level of each AI system. High-risk systems (those influencing consequential decisions) require more frequent monitoring than low-risk systems.

**Drift Detection:** AI model performance can degrade over time as the underlying model is updated by the vendor or as the organization's data patterns change. Establish a process for detecting performance drift and escalating when performance falls below defined thresholds.

**Incident Response:** Define what constitutes an AI-related incident (e.g., significant output quality degradation, data exposure, system unavailability) and establish an escalation and response process.

**Evidence to Collect:** Monitoring logs for in-scope AI systems; performance metric records; incident reports and resolution records; records of monitoring reviews; evidence of escalation when thresholds were breached.

---

## 7. Appendix — Control Quick-Reference Index

The following index provides a rapid lookup of all 39 controls by ID, title, and applicability determination. Use this index when cross-referencing the SoA against audit checklists, gap analysis workbooks, or risk treatment plans.

| Control ID | Control Title | Domain | Applicable? |
|---|---|---|---|
| A.2.2 | AI Policy | Policies for AI | Yes |
| A.2.3 | Responsible AI Topics in AI Policy | Policies for AI | Yes |
| A.3.2 | Roles and Responsibilities for AI | Internal Organization | Yes |
| A.3.3 | Reporting of AI Concerns | Internal Organization | Yes |
| A.3.4 | Impact of Organizational Changes | Internal Organization | Yes |
| A.4.2 | Resources Related to AI Systems | Resources for AI Systems | Yes |
| A.4.3 | Competencies Related to AI Systems | Resources for AI Systems | Yes |
| A.4.4 | Awareness of Responsible Use of AI Systems | Resources for AI Systems | Yes |
| A.4.5 | Consultation | Resources for AI Systems | Yes |
| A.4.6 | Communication About the AI System | Resources for AI Systems | Yes |
| A.5.2 | AI System Risk Assessment | Assessing Impacts | Yes |
| A.5.3 | AI System Impact Assessment | Assessing Impacts | Yes |
| A.5.4 | Impact of AI System Documentation | Assessing Impacts | Yes |
| A.6.2.2 | Design and Development of AI System | AI System Life Cycle | **No** |
| A.6.2.3 | Training and Testing AI Model | AI System Life Cycle | **No** |
| A.6.2.4 | Verification and Validation of AI System | AI System Life Cycle | Partial |
| A.6.2.5 | Deployment of AI System | AI System Life Cycle | Yes |
| A.6.2.6 | Operation and Monitoring of AI System | AI System Life Cycle | Yes |
| A.6.2.7 | Retirement of AI System | AI System Life Cycle | Partial |
| A.6.2.8 | Responsible AI System Integration | AI System Life Cycle | Yes |
| A.6.2.9 | AI System Documentation | AI System Life Cycle | Yes |
| A.6.2.10 | Defined Use and Misuse of AI System | AI System Life Cycle | Yes |
| A.6.2.11 | Management of Third-Party AI System Components | AI System Life Cycle | Yes |
| A.7.2 | Data for Development and Enhancement of AI System | Data for AI Systems | Partial |
| A.7.3 | Data Quality for ML and Data for AI System | Data for AI Systems | Yes |
| A.7.4 | Data Preparation | Data for AI Systems | Partial |
| A.7.5 | Data Acquisition and Collection | Data for AI Systems | Partial |
| A.7.6 | Data Provenance | Data for AI Systems | Partial |
| A.8.2 | Informing Interested Parties About AI System Interaction | Information for Interested Parties | Yes |
| A.8.3 | Informing Interested Parties About AI Outcomes | Information for Interested Parties | Yes |
| A.8.4 | Access to Information About AI System Interaction | Information for Interested Parties | Yes |
| A.8.5 | Enabling Appropriate Human Actions in Response to AI Outputs | Information for Interested Parties | Yes |
| A.9.2 | Objectives for Responsible Use of AI System | Use of AI Systems | Yes |
| A.9.3 | Intended Use of AI System | Use of AI Systems | Yes |
| A.9.4 | Processes for Responsible Use of AI System | Use of AI Systems | Yes |
| A.9.5 | Human Oversight Aspects | Use of AI Systems | Yes |
| A.10.2 | Suppliers of AI System Components | Third-Party Relationships | Yes |
| A.10.3 | Shared ML Models | Third-Party Relationships | Partial |
| A.10.4 | Provision of AI System to Third Parties | Third-Party Relationships | **No** |

**Totals:** Yes: 29 | Partial: 7 | No: 3 | Total: 39

---

## 8. Appendix — SoA Maintenance Checklist

Use this checklist to ensure the SoA remains current and audit-ready between certification cycles.

### Annual Review Checklist

- [ ] Review all 39 controls — confirm applicability determinations remain accurate
- [ ] Update Implementation Status for all applicable controls
- [ ] Confirm all Evidence References point to current, valid documents
- [ ] Review Risk Treatment Links — confirm referenced risks are still active in AIMS-RISK-001
- [ ] Review Exclusion Justification Register — confirm excluded controls remain non-applicable
- [ ] Confirm A.10.4 exclusion with client — has the organization begun providing AI to third parties?
- [ ] Confirm A.7.2 partial scope — has the organization begun contributing data for model training?
- [ ] Confirm A.10.3 partial scope — has the organization adopted any open-source or shared models?
- [ ] Update Document Metadata (Version, Date, Next Review Date)
- [ ] Obtain senior management re-approval
- [ ] File signed approval record

### Trigger-Based Review Checklist

Complete when any of the following occur:

- [ ] **New AI system adopted** — assess applicability of all controls for the new system; update Evidence References
- [ ] **AI system retired** — confirm retirement controls (A.6.2.7) were applied; update inventory
- [ ] **Vendor change** — reassess A.10.2, A.10.3, A.6.2.11 for the new vendor relationship
- [ ] **Organizational restructure** — reassess A.3.2, A.3.4, A.4.2 for role and resource changes
- [ ] **Regulatory change** — reassess A.8.2, A.8.3, A.8.4 for new disclosure obligations
- [ ] **AI-related incident** — reassess controls relevant to the incident; update risk assessment
- [ ] **Scope change** — full SoA review required if AIMS scope changes

---

## 9. Version History

| Version | Date | Author | Summary of Changes |
|---|---|---|---|
| 1.0 | [YYYY-MM-DD] | [Name] | Initial version — baseline SoA for ISO 42001 certification engagement |
| | | | |
| | | | |

---

*ISO 42001 Readiness Service Toolkit | 03-Remediation | Confidential Client Deliverable*
