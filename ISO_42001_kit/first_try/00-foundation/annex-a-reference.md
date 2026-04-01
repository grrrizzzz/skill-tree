# ISO/IEC 42001:2023 — Annex A Control Reference

> **Current as of:** March 2026 | ISO/IEC 42001:2023

---

## Purpose

This is the **authoritative control reference** for the ISO 42001 consulting toolkit. The Statement of Applicability (SoA) template, gap analysis workbook, audit checklists, and cross-framework mapping all reference the control IDs defined in this document. Any control ID cited elsewhere in the toolkit traces back to this reference sheet.

Do not modify control IDs without updating all dependent templates.

---

## How to Use This Reference

| If you are working on... | Then use this reference to... |
|---|---|
| **SoA Template** | Look up each control ID to confirm its title, domain, and applicability before populating the SoA |
| **Gap Analysis Workbook** | Verify that every assessed control maps to a valid Annex A control listed here |
| **Audit Checklists** | Confirm control scope and description when preparing audit evidence |
| **Cross-Framework Mapping** | Trace ISO 42001 control IDs to their exact definitions for mapping to ISO 27001, NIST AI RMF, or EU AI Act |

**Applicability Column Meaning:**

- **FULLY APPLICABLE** — The control applies in its entirety to organizations that use third-party AI systems. Implement as stated.
- **PARTIALLY APPLICABLE** — The control applies in a reduced or adapted scope for AI-user organizations. Document the applicable portions in your SoA.
- **NOT APPLICABLE** — The control targets AI developers/providers and does not apply to organizations that only use AI. Justify exclusion in the SoA.

---

## Numbering Verification Note

The control numbering in this document uses the **A.2 through A.10 scheme** from the published ISO/IEC 42001:2023 standard. This was cross-verified against multiple authoritative sources:

| Source | Scheme Confirmed | URL |
|---|---|---|
| **Bastion Tech** — ISO 42001 Annex A Complete Guide | A.2–A.10, 39 controls | bastion.tech/learn/iso42001/annex-a-controls |
| **Gabriel Consultant** — Annex Control Objectives and Controls | A.2–A.10, 9 domains | gabriel.hk/iso-42001-annex-control-objectives-and-controls/ |
| **ISMS.online** — ISO 42001 Annex B Implementation Guidance | A.2–A.10 (Annex B maps to Annex A) | isms.online/iso-42001/annex-b/ |

> **Warning:** Some secondary sources (blog posts, training materials) use an **A.5–A.13 numbering scheme**. That scheme reflects an earlier draft or alternative interpretation and is **not used in this toolkit**. If you encounter A.5–A.13 numbered controls, they do not map 1:1 to the IDs in this document.

---

## Control Listing — All 39 Controls

### A.2 — Policies for AI (2 controls)

*Objective: Provide management direction and support for AI systems in accordance with business requirements, applicable laws, and responsible AI principles.*

| Control ID | Control Title | Description | AI-User Applicability | Rationale |
|---|---|---|---|---|
| **A.2.2** | AI Policy | Define and document a formal AI policy that establishes the organization's approach to responsible AI, including commitments to compliance, ethical principles, and a framework for AI objectives. | **FULLY APPLICABLE** | Every organization using AI needs a governing policy, regardless of whether it builds or buys AI. |
| **A.2.3** | Responsible AI Topics in AI Policy | Address specific responsible AI considerations in the AI policy, including fairness, transparency, accountability, human oversight, privacy, safety, and societal impact. | **FULLY APPLICABLE** | Responsible AI principles apply equally to AI users; usage decisions carry ethical and societal implications. |

---

### A.3 — Internal Organization (3 controls)

*Objective: Establish accountability within the organization to support a responsible approach to AI.*

| Control ID | Control Title | Description | AI-User Applicability | Rationale |
|---|---|---|---|---|
| **A.3.2** | Roles and Responsibilities for AI | Define and allocate roles and responsibilities for AI-related activities, including AI system owners, data stewards, risk owners, and AIMS management. | **FULLY APPLICABLE** | AI users must assign clear ownership for AI tool selection, usage oversight, and risk management. |
| **A.3.3** | Reporting of AI Concerns | Establish a mechanism for personnel to report AI-related ethical, safety, or compliance concerns without fear of retaliation. | **FULLY APPLICABLE** | Staff using third-party AI must have a channel to flag unexpected outputs, bias, or misuse. |
| **A.3.4** | Impact of Organizational Changes | Assess and manage AI implications when the organization undergoes changes such as restructuring, mergers, or technology transitions. | **FULLY APPLICABLE** | Organizational changes (e.g., vendor switches, team restructures) directly affect AI tool governance and continuity. |

---

### A.4 — Resources for AI Systems (5 controls)

*Objective: Ensure the organization identifies and provides all resources required for AI systems to understand and address associated risks.*

| Control ID | Control Title | Description | AI-User Applicability | Rationale |
|---|---|---|---|---|
| **A.4.2** | Resources Related to AI Systems | Identify and document all resources needed for AI activities, including human, technical, financial, and infrastructure resources at each lifecycle stage. | **FULLY APPLICABLE** | AI users must budget for licenses, integration effort, monitoring tools, and skilled personnel. |
| **A.4.3** | Competencies Related to AI Systems | Ensure personnel involved in AI activities have the required competencies; identify skill gaps, provide training, and maintain competency records. | **FULLY APPLICABLE** | Staff need competencies to evaluate AI outputs, understand limitations, and use tools responsibly. |
| **A.4.4** | Awareness of Responsible Use of AI Systems | Ensure personnel are aware of the AI policy, relevant risks, ethical considerations, and their own responsibilities regarding AI systems. | **FULLY APPLICABLE** | All staff interacting with AI tools need awareness training on responsible use, data handling, and reporting obligations. |
| **A.4.5** | Consultation | Engage relevant stakeholders when making significant AI decisions that affect them. | **FULLY APPLICABLE** | Decisions to adopt or change AI tools affect employees, customers, and partners — consultation is essential. |
| **A.4.6** | Communication About the AI System | Communicate relevant information about AI systems to interested parties, including capabilities, limitations, and intended use. | **FULLY APPLICABLE** | AI users must communicate to internal teams and external stakeholders how AI tools are being used and what their limitations are. |

---

### A.5 — Assessing Impacts of AI Systems (3 controls)

*Objective: Assess AI system impacts on individuals, groups, and society throughout the system lifecycle.*

| Control ID | Control Title | Description | AI-User Applicability | Rationale |
|---|---|---|---|---|
| **A.5.2** | AI System Risk Assessment | Identify and assess risks from AI systems across technical, organizational, ethical, and societal dimensions; conduct initial and periodic reassessments. | **FULLY APPLICABLE** | Even third-party AI introduces risks (bias in outputs, data leakage, over-reliance) that must be formally assessed. |
| **A.5.3** | AI System Impact Assessment | Evaluate the impacts of AI systems on individuals and groups, including potential harms, discrimination, and privacy effects; document mitigations. | **FULLY APPLICABLE** | Using AI to process customer data or make decisions requires impact assessment regardless of who built the AI. |
| **A.5.4** | Impact of AI System Documentation | Document impact assessment results, including impacts identified, mitigations applied, and residual risks; keep documentation current as systems change. | **FULLY APPLICABLE** | Documented impact records are required for audit evidence and ongoing monitoring of third-party AI tools. |

---

### A.6 — AI System Life Cycle (10 controls)

*Objective: Define criteria and requirements for each stage of the AI system life cycle to ensure responsible development, deployment, and operation.*

| Control ID | Control Title | Description | AI-User Applicability | Rationale |
|---|---|---|---|---|
| **A.6.2.2** | Design and Development of AI System | Apply responsible design and development practices including requirements definition, design decisions, and development standards. | **NOT APPLICABLE** | Organization does not design or develop AI systems; this responsibility lies with the AI provider. |
| **A.6.2.3** | Training and Testing AI Model | Ensure AI models are properly trained, tested (functional, performance, bias, security, robustness), and validated before deployment. | **NOT APPLICABLE** | Organization does not train or test AI models; relies on provider testing and validation evidence. |
| **A.6.2.4** | Verification and Validation of AI System | Confirm that the AI system meets specified requirements (verification) and fulfills its intended purpose (validation). | **PARTIALLY APPLICABLE** | Applies in the context of validating that a third-party AI tool meets organizational requirements before adoption — not building V&V processes. |
| **A.6.2.5** | Deployment of AI System | Plan and execute controlled deployment of AI systems to production, including rollout planning and monitoring. | **FULLY APPLICABLE** | Deploying/rolling out third-party AI tools within the organization requires deployment planning, user onboarding, and monitoring. |
| **A.6.2.6** | Operation and Monitoring of AI System | Ensure ongoing AI system performance through monitoring, performance tracking, drift detection, and issue identification. | **FULLY APPLICABLE** | Core control for AI users — monitoring third-party AI output quality, availability, and performance is essential. |
| **A.6.2.7** | Retirement of AI System | Plan and execute responsible decommissioning of AI systems, including data handling, user transition, and documentation. | **PARTIALLY APPLICABLE** | Applies to decommissioning use of third-party AI tools (data migration, access removal, contract termination), not retiring proprietary systems. |
| **A.6.2.8** | Responsible AI System Integration | Integrate AI systems responsibly into organizational processes and technical environments, including integration planning, testing, and validation. | **FULLY APPLICABLE** | Integrating third-party AI into business workflows, APIs, and decision processes requires careful planning and testing. |
| **A.6.2.9** | AI System Documentation | Maintain comprehensive documentation of AI systems including purpose, capabilities, limitations, operating parameters, and known constraints. | **FULLY APPLICABLE** | AI users must maintain documentation of each AI tool in use: purpose, configuration, data flows, limitations, and vendor SLA details. |
| **A.6.2.10** | Defined Use and Misuse of AI System | Define and communicate intended uses and explicitly prohibited uses of AI systems to all users and stakeholders. | **FULLY APPLICABLE** | Critical for AI users — acceptable use policies must define what staff can and cannot do with AI tools. |
| **A.6.2.11** | Management of Third-Party AI System Components | Manage AI components sourced from third parties, including selection criteria, ongoing assessment, and performance monitoring. | **FULLY APPLICABLE** | This is the single most important control for AI-user organizations — governs the entire third-party AI supply chain. |

---

### A.7 — Data for AI Systems (5 controls)

*Objective: Ensure the organization understands the role and impacts of data in AI systems and manages data appropriately.*

| Control ID | Control Title | Description | AI-User Applicability | Rationale |
|---|---|---|---|---|
| **A.7.2** | Data for Development and Enhancement of AI System | Define and implement data management processes related to AI system development, including data selection, acquisition, and preparation. | **PARTIALLY APPLICABLE** | Applies if the organization provides data for fine-tuning or customization of third-party AI; does not apply to core model development. |
| **A.7.3** | Data Quality for ML and Data for AI System | Ensure data quality across accuracy, completeness, relevance, timeliness, and representativeness for AI system inputs. | **FULLY APPLICABLE** | Data quality of inputs fed into third-party AI directly affects output reliability — garbage in, garbage out. |
| **A.7.4** | Data Preparation | Properly prepare data for AI use, including cleaning, labeling, transformation, and format conversion. | **PARTIALLY APPLICABLE** | Applies when preparing organizational data for input to AI tools (e.g., structuring prompts, cleaning datasets); scope is narrower than for AI developers. |
| **A.7.5** | Data Acquisition and Collection | Ensure responsible data sourcing with proper consent, privacy protections, and representativeness considerations. | **PARTIALLY APPLICABLE** | Applies to data the organization collects and feeds into AI systems; the provider handles training data acquisition. |
| **A.7.6** | Data Provenance | Track and document data origin, transformations, and lineage for data used in AI systems. | **PARTIALLY APPLICABLE** | Applies to tracking the provenance of organizational data used as AI inputs; provider is responsible for training data provenance. |

---

### A.8 — Information for Interested Parties (4 controls)

*Objective: Ensure interested parties have the information needed to understand and assess AI system risks and make informed decisions.*

| Control ID | Control Title | Description | AI-User Applicability | Rationale |
|---|---|---|---|---|
| **A.8.2** | Informing Interested Parties About AI System Interaction | Notify individuals when they are interacting with an AI system through appropriate disclosure mechanisms. | **FULLY APPLICABLE** | Organizations must disclose to customers, employees, and partners when they are interacting with AI-powered tools or outputs. |
| **A.8.3** | Informing Interested Parties About AI Outcomes | Enable understanding of AI-driven decisions by communicating explanations of outcomes and key decision factors. | **FULLY APPLICABLE** | When AI outputs influence decisions affecting people (hiring, service, pricing), the organization must explain the AI's role. |
| **A.8.4** | Access to Information About AI System Interaction | Provide access to records of AI system interactions as required by law, contract, or organizational policy. | **FULLY APPLICABLE** | Organizations must maintain and provide access to logs of AI interactions, especially where regulatory or contractual obligations exist. |
| **A.8.5** | Enabling Appropriate Human Actions in Response to AI Outputs | Provide information that enables humans to make informed decisions when acting on AI outputs, including confidence levels and limitations. | **FULLY APPLICABLE** | Staff acting on AI recommendations need sufficient context (confidence scores, caveats) to exercise proper judgment. |

---

### A.9 — Use of AI Systems (4 controls)

*Objective: Ensure the organization uses AI systems responsibly and in accordance with its AI policy.*

| Control ID | Control Title | Description | AI-User Applicability | Rationale |
|---|---|---|---|---|
| **A.9.2** | Objectives for Responsible Use of AI System | Define measurable objectives guiding the responsible use of AI systems across the organization. | **FULLY APPLICABLE** | AI users need clear objectives for what responsible AI usage looks like in their operational context. |
| **A.9.3** | Intended Use of AI System | Ensure AI systems are used within their intended parameters; provide user guidance and monitor for scope creep. | **FULLY APPLICABLE** | Preventing "mission creep" where AI tools are repurposed beyond their validated use cases is a primary AI-user responsibility. |
| **A.9.4** | Processes for Responsible Use of AI System | Establish operational processes for responsible AI use, including review procedures, escalation paths, and human checkpoints. | **FULLY APPLICABLE** | Day-to-day operational processes (review workflows, escalation procedures, periodic reviews) are core AI-user controls. |
| **A.9.5** | Human Oversight Aspects | Ensure appropriate human control over AI systems through override capability, intervention points, and defined oversight levels (human-in-the-loop, human-on-the-loop, or human-in-command). | **FULLY APPLICABLE** | Human oversight is arguably the most critical control for AI users — defines when and how humans intervene in AI-assisted processes. |

---

### A.10 — Third-Party and Customer Relationships (3 controls)

*Objective: Ensure responsibilities and risks are appropriately managed when third parties are involved in the AI value chain.*

| Control ID | Control Title | Description | AI-User Applicability | Rationale |
|---|---|---|---|---|
| **A.10.2** | Suppliers of AI System Components | Manage AI component suppliers through selection criteria, contractual requirements, ongoing assessment, and performance monitoring. | **FULLY APPLICABLE** | Core control for AI users — governs vendor selection, due diligence, contractual obligations, and ongoing supplier monitoring. |
| **A.10.3** | Shared ML Models | Manage the use of shared or pre-trained models, including assessing model provenance, suitability, limitations, and bias characteristics. | **PARTIALLY APPLICABLE** | Applies when using publicly available or shared pre-trained models (e.g., open-source LLMs); less relevant if exclusively using proprietary vendor APIs. |
| **A.10.4** | Provision of AI System to Third Parties | Ensure responsible provision of AI systems or AI-powered services to customers, including documentation, support, and communication of limitations. | **NOT APPLICABLE** | Organization does not provide AI systems or AI-powered services to third parties. *Note: Confirm with client during scoping — reclassify to FULLY APPLICABLE if the client embeds AI outputs in services delivered to their customers.* |

---

## Summary Statistics

| Metric | Count |
|---|---|
| **Total Annex A Controls** | **39** |
| Fully Applicable for AI Users | **29** |
| Partially Applicable | **7** |
| Not Applicable | **3** |

### Breakdown by Domain

| Domain | Controls | Fully | Partial | N/A |
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

### Not Applicable Controls (AI-User Context)

These controls are excluded for organizations that exclusively **use** third-party AI and do not develop, train, or provide AI systems:

| Control ID | Control Title | Exclusion Justification |
|---|---|---|
| A.6.2.2 | Design and Development of AI System | Organization does not design or develop AI systems |
| A.6.2.3 | Training and Testing AI Model | Organization does not train or test AI models |
| A.10.4 | Provision of AI System to Third Parties | Organization does not provide AI to others *(confirm during scoping)* |

---

*This reference is maintained as part of the ISO 42001 consulting toolkit. When the ISO/IEC 42001 standard is revised, update this document first, then cascade changes to all dependent templates.*
