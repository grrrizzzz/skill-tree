# AI Risk Treatment Plan

> **Current as of:** March 2026 | ISO/IEC 42001:2023

---

> **HOW TO CUSTOMIZE — REMOVE THIS BLOCK BEFORE DELIVERY**
>
> This template documents the organization's treatment decisions for all risks identified in the AI Risk Assessment Register (AIMS-RISK-001). It is designed for organizations that **use** third-party AI systems and are not AI developers or providers.
>
> **Before delivering to the client:**
> 1. Replace all `[bracketed placeholders]` with client-specific information.
> 2. Delete the six example treatment entries (RISK-001 through RISK-007) and replace with entries that correspond to the client's actual risk register. Every risk in AIMS-RISK-001 must have a corresponding treatment entry here.
> 3. Confirm that every Annex A control cited in the "Annex A Controls Selected" column is also marked as applicable in the client's Statement of Applicability (AIMS-SOA-001). This document feeds the SoA — inconsistencies will be flagged by auditors.
> 4. Assign real names and roles to all "Responsible Owner" and "Acceptance Authority" fields. Do not deliver a document with `[Name, Role]` placeholders.
> 5. Confirm that residual risk levels are consistent with the risk scoring methodology in AIMS-RISK-001. A residual risk level that drops from High to Low without substantial treatment measures will attract auditor scrutiny.
> 6. The Residual Risk Acceptance Register (Section 4) must be signed off by the named acceptance authority before the document is finalized. A template signature block is included.
> 7. Remove this entire HOW TO CUSTOMIZE block before delivery.
>
> **Clause traceability:** This document satisfies requirements under ISO/IEC 42001:2023 Clauses 6.1.3, 6.1.5, and 8.3. It bridges the Risk Assessment Register (AIMS-RISK-001) to the Statement of Applicability (AIMS-SOA-001).

---

## Document Metadata

| Field | Value |
|---|---|
| **Document ID** | AIMS-RTP-001 |
| **Version** | 1.0 |
| **Date** | [YYYY-MM-DD] |
| **Organization** | [Organization Name] |
| **AIMS Scope Reference** | [Reference to AIMS scope document, e.g., AIMS-SCOPE-001] |
| **Risk Register Reference** | AIMS-RISK-001 |
| **Prepared By** | [Name, Role] |
| **Approved By** | [Name, Role] |
| **Next Review Date** | [YYYY-MM-DD — no later than 12 months from Date] |

---

> **Legal Disclaimer:** This template does not constitute legal advice. The risk treatment options, example entries, and Annex A control references provided herein are for guidance purposes only. Organizations should consult qualified legal counsel for questions about regulatory obligations, including EU AI Act deployer obligations, data protection requirements, and sector-specific compliance requirements. Treatment decisions must be tailored to the specific context, operations, and risk appetite of the individual organization.

---

## Clause Traceability

| ISO/IEC 42001:2023 Reference | Requirement Addressed |
|---|---|
| **Clause 6.1.3** | AI risk treatment — selection of treatment options and controls |
| **Clause 6.1.5** | Documented information for risk treatment decisions and residual risk acceptance |
| **Clause 8.3** | AI risk treatment — operational implementation and monitoring of treatment actions |

---

## Section 1: Purpose

This Risk Treatment Plan documents the organization's decisions for treating all AI-related risks identified in the AI Risk Assessment Register (AIMS-RISK-001). For each identified risk, this plan records:

- The treatment option selected (Mitigate, Transfer, Avoid, or Accept)
- The specific measures to be implemented
- The Annex A controls selected as a result of the treatment decision
- The named owner responsible for implementation
- The target completion date
- The expected residual risk level after treatment

### Why This Document Exists

ISO/IEC 42001:2023 requires organizations to not only identify and assess AI risks but to make and document deliberate decisions about how to address them. Risk identification without treatment decisions is incomplete. This document closes that gap.

It also serves two critical bridging functions:

**Bridge from Risk Register to SoA.** Treatment decisions drive control selection. When the organization decides to mitigate a risk, it must select specific controls from ISO 42001 Annex A to implement. Those controls then appear in the Statement of Applicability (AIMS-SOA-001) as applicable, with this document as the justification. Auditors will trace this chain: risk identified in AIMS-RISK-001, treatment decided in AIMS-RTP-001, control selected and justified in AIMS-SOA-001.

**Formal accountability for residual risk.** Not all risk can be eliminated. After treatment, some residual risk remains. This plan documents who has formally accepted that residual risk and on what basis. Residual risk acceptance is a governance decision, not a technical one, and it requires a named authority.

### Scope

This plan covers all risks listed in AIMS-RISK-001. Every risk entry in the register must have a corresponding treatment entry in Section 3 of this document. Risks that are added to the register after this plan is first issued must be added to this plan within 30 days of the risk being identified.

---

## Section 2: Treatment Options

ISO/IEC 42001:2023 recognizes four treatment options. The organization selects one or more options for each identified risk. Options may be combined where appropriate (for example, partially mitigating a risk and accepting the residual).

### 2.1 Mitigate

Implement controls to reduce the likelihood of the risk materializing, reduce the impact if it does, or both. Mitigation is the most common treatment option for AI user organizations because most AI use risks can be meaningfully reduced through policy, training, and operational controls without abandoning the AI tool entirely.

**AI-specific examples:**
- Develop and enforce a data handling policy specifying what categories of data may and may not be entered into AI prompts
- Implement an AI Acceptable Use Policy (AUP) with clear prohibited use cases and consequences for non-compliance
- Require mandatory human review before AI-generated content is published or used in consequential decisions
- Establish a vendor assessment process to evaluate AI vendors' security and privacy posture before adoption
- Deliver staff training on AI risks, data classification, and responsible AI use
- Implement output monitoring to detect quality degradation or unexpected behavior changes after vendor model updates

### 2.2 Transfer

Shift the financial or operational consequences of the risk to a third party through contractual terms, insurance, or indemnification. Transfer does not eliminate the risk; it changes who bears the consequences if the risk materializes. For AI user organizations, transfer typically involves vendor contracts and insurance.

**AI-specific examples:**
- Negotiate contractual indemnification from the AI vendor for data breaches caused by vendor-side failures
- Obtain cyber insurance coverage that explicitly covers AI-related incidents, including vendor breach scenarios
- Include contractual liability clauses in customer agreements that address AI-generated content errors
- Require AI vendors to maintain current security certifications (ISO 27001, SOC 2 Type II) as a contractual condition

### 2.3 Avoid

Eliminate the risk by discontinuing the activity, use case, or AI system that creates it. Avoidance is appropriate when the risk level is High or Critical and no feasible mitigation exists, or when the business value of the AI system does not justify the risk exposure.

**AI-specific examples:**
- Prohibit use of personal ChatGPT accounts (free or paid) for any work tasks involving company or client data
- Maintain an approved AI tool list and prohibit use of any AI tool not on the list
- Discontinue use of an AI system that cannot provide adequate data processing agreements
- Withdraw from a use case where EU AI Act high-risk classification creates unacceptable compliance burden

### 2.4 Accept

Formally acknowledge the risk and decide not to take further treatment action, within the organization's risk acceptance criteria. Acceptance is not the same as ignoring a risk. It is a deliberate, documented decision by an authorized person that the risk is within the organization's risk appetite and that the cost of further treatment exceeds the expected benefit.

**AI-specific examples:**
- Accept the residual risk of occasional AI output inaccuracies in low-stakes internal drafting tasks after implementing review procedures
- Accept the risk of vendor model updates for non-critical AI tools where the impact of output changes is minor and the tool is not used in consequential decisions
- Accept the risk of limited AI vendor transparency for commodity AI tools where the data involved is non-sensitive and no personal data is processed

**Acceptance authority:** Risk acceptance must be authorized by the appropriate level of management based on the residual risk level, as defined in AIMS-RISK-001 Section 1.6. Low risks may be accepted by the AI System Owner. Medium risks require Department Head or equivalent. High risks require Senior Management. Critical risks require Top Management sign-off.

---

## Section 3: Risk Treatment Register

The table below records the treatment decision for each risk identified in AIMS-RISK-001. Entries are listed by Risk ID, which corresponds directly to the Risk Register.

**Column definitions:**

| Column | Definition |
|---|---|
| **Risk ID** | Unique identifier matching AIMS-RISK-001. |
| **Risk Description** | Brief summary of the risk scenario. Full description is in AIMS-RISK-001. |
| **Risk Level** | Inherent risk level from AIMS-RISK-001 before treatment. |
| **Treatment Decision** | Mitigate / Transfer / Avoid / Accept (may combine options). |
| **Treatment Measures** | Specific actions to be implemented. Each measure should have a named owner and target date. |
| **Annex A Controls Selected** | ISO 42001 Annex A controls selected as a result of this treatment decision. These must be reflected in AIMS-SOA-001. |
| **Responsible Owner** | Named individual accountable for implementing treatment measures. |
| **Target Completion** | Date by which all treatment measures must be implemented. |
| **Residual Risk Level** | Expected risk level after all treatment measures are implemented. |
| **Acceptance Authority** | Named individual who formally accepts the residual risk. |
| **Status** | Not Started / In Progress / Implemented / Accepted |

---

### Treatment Entries

---

**RISK-001: Copilot Data Leakage**

| Field | Detail |
|---|---|
| **Risk ID** | RISK-001 |
| **Risk Description** | Employee pastes confidential client data into Microsoft Copilot prompts. Data transmitted to Microsoft AI infrastructure without adequate staff awareness of what is permissible. |
| **Risk Level** | 🟡 Medium (Score: 12) |
| **Treatment Decision** | Mitigate |
| **Treatment Measures** | (1) Develop and publish AI Acceptable Use Policy specifying data classification rules for Copilot use — define what data categories are permitted and prohibited in AI prompts. Owner: [IT Manager]. Target: [Date]. (2) Deliver mandatory staff training on Copilot data handling, covering data classification, prompt hygiene, and consequences of policy breach. Owner: [HR/Training Lead]. Target: [Date]. (3) Review Microsoft Copilot data processing agreement to confirm data retention settings and model training opt-out are configured correctly. Owner: [IT Manager / DPO]. Target: [Date]. |
| **Annex A Controls Selected** | A.6.2.10 (Acceptable use of AI systems), A.4.4 (AI system documentation and records) |
| **Responsible Owner** | [IT Manager / Name] |
| **Target Completion** | [YYYY-MM-DD] |
| **Residual Risk Level** | 🟢 Low (Score: 6) — after AUP publication and training completion |
| **Acceptance Authority** | [IT Manager / Name] |
| **Status** | Not Started |

---

**RISK-002: Shadow AI (Personal AI Accounts)**

| Field | Detail |
|---|---|
| **Risk ID** | RISK-002 |
| **Risk Description** | Employees use personal ChatGPT accounts for work tasks involving company and client data. No commercial data protection terms apply. Data may be used for model training. No policy, monitoring, or training in place. |
| **Risk Level** | 🟠 High (Score: 16) |
| **Treatment Decision** | Avoid + Mitigate |
| **Treatment Measures** | (1) Issue immediate interim guidance prohibiting use of personal AI accounts for any work tasks involving company or client data. Owner: [CEO / Senior Management]. Target: [Date — within 2 weeks of plan approval]. (2) Develop and publish AI Acceptable Use Policy with explicit prohibition on personal AI accounts for work tasks and a defined approved AI tool list. Owner: [IT Manager / DPO]. Target: [Date]. (3) Evaluate and provision an approved enterprise AI tool (e.g., ChatGPT Enterprise or Microsoft Copilot) to meet staff needs through an authorized channel. Owner: [IT Manager]. Target: [Date]. (4) Deliver staff training on shadow AI risks and the approved tools policy. Owner: [HR/Training Lead]. Target: [Date]. (5) Implement periodic monitoring to detect unauthorized AI tool use (e.g., web filtering logs, IT asset review). Owner: [IT Manager]. Target: [Date]. |
| **Annex A Controls Selected** | A.6.2.10 (Acceptable use of AI systems), A.9.3 (AI system monitoring and logging) |
| **Responsible Owner** | [IT Manager / Name] |
| **Target Completion** | [YYYY-MM-DD] |
| **Residual Risk Level** | 🟡 Medium (Score: 8) — residual risk of policy non-compliance; requires ongoing monitoring |
| **Acceptance Authority** | [Department Head / Name] |
| **Status** | Not Started |

---

**RISK-003: AI Bias in Lead Scoring**

| Field | Detail |
|---|---|
| **Risk ID** | RISK-003 |
| **Risk Description** | HubSpot AI lead scoring model may use variables that serve as proxies for protected characteristics, resulting in systematically lower scores for prospects from certain demographic groups. No internal bias testing or review of scoring criteria has been conducted. |
| **Risk Level** | 🟡 Medium (Score: 8) |
| **Treatment Decision** | Mitigate |
| **Treatment Measures** | (1) Request HubSpot documentation on lead scoring model inputs, methodology, and any bias testing conducted by the vendor. Owner: [CRM Owner / Name]. Target: [Date]. (2) Conduct internal review of lead scoring outputs for demographic patterns — sample recent scored leads and analyze score distribution by available demographic indicators. Owner: [Sales Manager / Data Analyst]. Target: [Date]. (3) Establish and document policy that AI lead scores are one input to sales prioritization, not the sole determinant. Define mandatory human review requirement for all AI-scored leads before action is taken. Owner: [Sales Manager]. Target: [Date]. (4) Schedule quarterly bias review — periodic check of score distribution to detect emerging patterns. Owner: [Sales Manager]. Target: Ongoing from [Date]. |
| **Annex A Controls Selected** | A.9.5 (Human oversight of AI systems), A.5.3 (AI system impact assessment) |
| **Responsible Owner** | [Sales Manager / Name] |
| **Target Completion** | [YYYY-MM-DD] |
| **Residual Risk Level** | 🟢 Low (Score: 4) — after human review policy and quarterly bias review implemented |
| **Acceptance Authority** | [Sales Manager / Name] |
| **Status** | Not Started |

---

**RISK-004: AI-Generated Inaccurate Customer Content**

| Field | Detail |
|---|---|
| **Risk ID** | RISK-004 |
| **Risk Description** | Staff use generative AI to draft customer-facing communications. AI may generate factually incorrect content (wrong prices, incorrect product specifications, inaccurate service terms) that is published or sent without adequate review. |
| **Risk Level** | 🟡 Medium (Score: 9) |
| **Treatment Decision** | Mitigate |
| **Treatment Measures** | (1) Implement mandatory human review and approval process for all AI-generated customer-facing content before publication or sending. No AI-generated content to be published without named reviewer sign-off. Owner: [Marketing/Communications Manager]. Target: [Date]. (2) Develop AI output review checklist for customer communications — covering factual accuracy, pricing, regulatory compliance, and brand consistency. Owner: [Marketing/Communications Manager]. Target: [Date]. (3) Add AI disclosure statement to relevant customer communications where required by applicable law or organizational policy. Owner: [DPO / Legal]. Target: [Date]. |
| **Annex A Controls Selected** | A.9.5 (Human oversight of AI systems), A.8.5 (AI system output management) |
| **Responsible Owner** | [Marketing/Communications Manager / Name] |
| **Target Completion** | [YYYY-MM-DD] |
| **Residual Risk Level** | 🟢 Low (Score: 3) — after mandatory review process and checklist implemented |
| **Acceptance Authority** | [Marketing/Communications Manager / Name] |
| **Status** | Not Started |

---

**RISK-006: EU AI Act Non-Compliance**

| Field | Detail |
|---|---|
| **Risk ID** | RISK-006 |
| **Risk Description** | Organization has not assessed its obligations as an AI deployer under the EU AI Act (Regulation 2024/1689). Deployer obligations take effect August 2, 2026. Non-compliance may result in fines of up to €15 million or 3% of global annual turnover. |
| **Risk Level** | 🟠 High (Score: 15) |
| **Treatment Decision** | Mitigate |
| **Treatment Measures** | (1) Conduct EU AI Act deployer obligations assessment — classify all in-scope AI systems against EU AI Act risk categories (prohibited, high-risk, limited risk, minimal risk). Engage legal counsel to confirm classification. Owner: [DPO / Legal / AIMS Manager]. Target: [Date — before August 2, 2026]. (2) For any AI system classified as high-risk: conduct fundamental rights impact assessment, implement required human oversight, establish record-keeping, and prepare transparency documentation. Owner: [DPO / Legal]. Target: [Date]. (3) Develop and implement a compliance roadmap documenting obligations, timelines, and responsible owners for each in-scope AI system. Owner: [AIMS Manager]. Target: [Date]. (4) Deliver EU AI Act awareness training to relevant staff — covering deployer obligations, prohibited practices, and reporting requirements. Owner: [HR/Training Lead]. Target: [Date]. (5) Establish process for monitoring EU AI Act regulatory guidance and updates from the European AI Office. Owner: [DPO / AIMS Manager]. Target: Ongoing from [Date]. |
| **Annex A Controls Selected** | A.5.2 (AI system risk assessment), A.10.2 (Compliance with legal and regulatory requirements) |
| **Responsible Owner** | [DPO / Legal / Name] |
| **Target Completion** | [YYYY-MM-DD — mandatory: before August 2, 2026] |
| **Residual Risk Level** | 🟡 Medium (Score: 9) — residual compliance risk remains until full assessment and implementation complete; review after August 2026 |
| **Acceptance Authority** | [Senior Management / Name] |
| **Status** | Not Started |

---

**RISK-007: Over-Reliance on AI (Automation Bias)**

| Field | Detail |
|---|---|
| **Risk ID** | RISK-007 |
| **Risk Description** | Staff accept AI recommendations without adequate critical review for decisions with significant consequences for customers, employees, or the organization. No formal human oversight policy, no defined review requirements, and no training on automation bias. |
| **Risk Level** | 🟡 Medium (Score: 12) |
| **Treatment Decision** | Mitigate |
| **Treatment Measures** | (1) Define and document human oversight requirements for each AI use case — specify which decisions require human review, what that review must include, and who is authorized to approve. Owner: [AIMS Manager / Department Heads]. Target: [Date]. (2) Implement mandatory review checkpoints for high-stakes AI-assisted decisions — document that human review occurred, the reviewer's assessment, and any deviation from the AI recommendation. Owner: [Department Heads]. Target: [Date]. (3) Develop and deliver training on automation bias and responsible AI use, including practical guidance on when and how to override AI recommendations. Owner: [HR/Training Lead]. Target: [Date]. (4) Establish a clear escalation path for staff to raise concerns about AI outputs without fear of retaliation. Owner: [AIMS Manager / HR]. Target: [Date]. |
| **Annex A Controls Selected** | A.9.5 (Human oversight of AI systems), A.9.4 (AI system performance monitoring) |
| **Responsible Owner** | [AIMS Manager / Name] |
| **Target Completion** | [YYYY-MM-DD] |
| **Residual Risk Level** | 🟢 Low (Score: 6) — after oversight policy, mandatory checkpoints, and training implemented |
| **Acceptance Authority** | [AIMS Manager / Name] |
| **Status** | Not Started |

---

> **Note:** The entries above are examples corresponding to illustrative risks in AIMS-RISK-001. Replace with treatment entries for the client's actual identified risks. Every risk in AIMS-RISK-001 must have a corresponding entry in this register.

---

## Section 4: Residual Risk Acceptance Register

After treatment measures are implemented, some residual risk remains. This register documents the formal acceptance of residual risks by the appropriate authority. Acceptance is a governance decision, not a technical one.

**When to use this register:** An entry is required for every risk where the residual risk level is Low, Medium, or higher and the organization has decided not to pursue further treatment. Risks where treatment is still in progress should not be formally accepted until treatment is complete and the residual level has been confirmed.

**Acceptance authority levels** (from AIMS-RISK-001 Section 1.6):
- Low residual risk: AI System Owner
- Medium residual risk: Department Head or equivalent
- High residual risk: Senior Management (COO, CTO, or equivalent)
- Critical residual risk: Top Management (CEO or Board)

---

| Risk ID | Residual Risk Level | Acceptance Rationale | Accepted By (Name / Role) | Acceptance Date | Review Date |
|---|---|---|---|---|---|
| RISK-001 | 🟢 Low | After AUP publication and mandatory training, likelihood of inadvertent data leakage is materially reduced. Microsoft's commercial data protection commitments provide contractual backstop. Residual risk is within organizational risk appetite. | [Name / IT Manager] | [YYYY-MM-DD] | [YYYY-MM-DD] |
| RISK-002 | 🟡 Medium | Prohibition on personal AI accounts and approved tool list reduce exposure significantly. Residual risk of policy non-compliance cannot be fully eliminated without disproportionate monitoring investment. Compensating control: periodic IT monitoring of web traffic. Accepted pending next scheduled review. | [Name / Department Head] | [YYYY-MM-DD] | [YYYY-MM-DD — 6 months] |
| RISK-003 | 🟢 Low | Human review requirement for all AI-scored leads and quarterly bias review reduce discrimination risk to acceptable level. HubSpot's vendor documentation reviewed. Residual risk is within organizational risk appetite. | [Name / Sales Manager] | [YYYY-MM-DD] | [YYYY-MM-DD] |
| RISK-004 | 🟢 Low | Mandatory human review and accuracy checklist before publication eliminate the primary pathway to customer harm. Residual risk of reviewer error is within organizational risk appetite for this use case. | [Name / Marketing Manager] | [YYYY-MM-DD] | [YYYY-MM-DD] |
| RISK-006 | 🟡 Medium | Compliance roadmap and legal review underway. Residual compliance risk acknowledged pending completion of EU AI Act assessment before August 2, 2026 deadline. This acceptance is conditional and must be reviewed upon completion of the deployer obligations assessment. | [Name / Senior Management] | [YYYY-MM-DD] | [YYYY-MM-DD — mandatory before August 2, 2026] |
| RISK-007 | 🟢 Low | Human oversight policy, mandatory review checkpoints, and automation bias training reduce over-reliance risk to acceptable level. Residual risk of individual reviewer error is within organizational risk appetite. | [Name / AIMS Manager] | [YYYY-MM-DD] | [YYYY-MM-DD] |
| [RISK-NNN] | [Level] | [Rationale for accepting residual risk — include why further treatment is not feasible or proportionate] | [Name / Role] | [YYYY-MM-DD] | [YYYY-MM-DD] |

---

### Acceptance Sign-Off

By signing below, the named acceptance authority confirms they have reviewed the residual risk level and rationale for the risks assigned to them in this register and formally accept those risks on behalf of the organization.

| Name | Role | Signature | Date |
|---|---|---|---|
| [Name] | [Role] | _________________ | [YYYY-MM-DD] |
| [Name] | [Role] | _________________ | [YYYY-MM-DD] |
| [Name] | [Role] | _________________ | [YYYY-MM-DD] |

---

## Section 5: Treatment Implementation Tracker

This summary table provides a snapshot of treatment progress across the full risk register. Update this table each time a treatment measure is completed or a status changes.

| Metric | Count |
|---|---|
| **Total risks identified (AIMS-RISK-001)** | [N] |
| **Treatment: Mitigate** | [N] |
| **Treatment: Transfer** | [N] |
| **Treatment: Avoid** | [N] |
| **Treatment: Accept** | [N] |
| **Combined treatment (e.g., Mitigate + Transfer)** | [N] |
| **Status: Implemented** | [N] |
| **Status: In Progress** | [N] |
| **Status: Not Started** | [N] |
| **Residual risk: Low** | [N] |
| **Residual risk: Medium** | [N] |
| **Residual risk: High** | [N] |
| **Residual risk: Critical** | [N] |

### Annex A Controls Selected (Summary)

The following Annex A controls have been selected as a result of treatment decisions in this plan. Each must be reflected as applicable in AIMS-SOA-001.

| Annex A Control | Control Name | Selected For Risk(s) |
|---|---|---|
| A.4.4 | AI system documentation and records | RISK-001 |
| A.5.2 | AI system risk assessment | RISK-006 |
| A.5.3 | AI system impact assessment | RISK-003 |
| A.6.2.10 | Acceptable use of AI systems | RISK-001, RISK-002 |
| A.8.5 | AI system output management | RISK-004 |
| A.9.3 | AI system monitoring and logging | RISK-002 |
| A.9.4 | AI system performance monitoring | RISK-007 |
| A.9.5 | Human oversight of AI systems | RISK-003, RISK-004, RISK-007 |
| A.10.2 | Compliance with legal and regulatory requirements | RISK-006 |
| [A.X.X] | [Control name] | [Risk ID(s)] |

> **Important:** This table must be reconciled with AIMS-SOA-001 before the document is finalized. Every control listed here must appear as applicable in the SoA. Every control marked applicable in the SoA that relates to risk treatment must trace back to a treatment decision in this plan.

---

## Section 6: Review and Update

### When to Update This Plan

This plan is a living document. It must be updated whenever any of the following occur:

| Trigger | Required Action | Owner |
|---|---|---|
| **New risk identified** | Add treatment entry within 30 days of risk being added to AIMS-RISK-001 | AIMS Manager |
| **Treatment measure completed** | Update status to Implemented; confirm residual risk level; update Residual Risk Acceptance Register if not already done | Responsible Owner |
| **Treatment measure overdue** | Escalate to Department Head; document reason for delay; revise target date | Responsible Owner |
| **Residual risk level changes** | Update acceptance register; confirm acceptance authority is still appropriate for new level | AIMS Manager |
| **New AI system adopted** | Assess risks for new system; add to AIMS-RISK-001; add treatment entries here | AIMS Manager / IT Manager |
| **AI incident or near-miss** | Review treatment entries for affected system; assess whether treatment measures were adequate; update as needed | AIMS Manager |
| **Regulatory change** | Review compliance-related treatment entries; update measures and controls as needed | DPO / Legal |
| **Annual review** | Full review of all treatment entries; confirm status, residual risk levels, and acceptance decisions are current | AIMS Manager |

### Scheduled Review Cycle

| Review Type | Frequency | Owner |
|---|---|---|
| **Full plan review** | Annual (minimum) | AIMS Manager |
| **High and Critical risk treatment review** | Quarterly | Senior Management |
| **Post-treatment implementation review** | Within 30 days of treatment completion | Responsible Owner |
| **Pre-audit review** | Before Stage 1 and Stage 2 certification audit | AIMS Manager / Consultant |

### Relationship to Other AIMS Documents

This plan does not stand alone. It is part of an interconnected set of AIMS documents:

- **AIMS-RISK-001 (Risk Assessment Register)** — the source of all risks treated in this plan. Changes to the register must be reflected here.
- **AIMS-SOA-001 (Statement of Applicability)** — the destination for control selections made in this plan. Every Annex A control selected here must appear as applicable in the SoA.
- **AIMS-INV-001 (AI System Inventory)** — the source of AI system information referenced in risk entries. Every AI system referenced in this plan must have an inventory entry.
- **AIMS-AUP-001 (AI Acceptable Use Policy)** — the primary operational control for data handling and shadow AI risks. Referenced in treatment measures for RISK-001 and RISK-002.

---

## Version History

| Version | Date | Author | Summary of Changes |
|---|---|---|---|
| 1.0 | [YYYY-MM-DD] | [Name] | Initial issue |
| [1.1] | [YYYY-MM-DD] | [Name] | [Description of changes] |

---

*ISO 42001 Readiness Service Toolkit | 03-Remediation | Confidential Client Deliverable*
