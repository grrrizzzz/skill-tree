# AI Risk Assessment Methodology and Risk Register

> **Current as of:** March 2026 | ISO/IEC 42001:2023

---

> **HOW TO CUSTOMIZE — REMOVE THIS BLOCK BEFORE DELIVERY**
>
> This template combines the risk assessment methodology (Part 1) and the risk register (Part 2) into a single client-facing document. It is designed for organizations that **use** third-party AI systems and are not AI developers or providers.
>
> **Before delivering to the client:**
> 1. Replace all `[bracketed placeholders]` with client-specific information.
> 2. Delete the eight example risk entries (RISK-001 through RISK-008) and replace with risks identified during the client's actual risk identification workshops. The examples are illustrative only.
> 3. Update the Risk Summary Dashboard (Part 3) to reflect the client's actual risk register entries.
> 4. Confirm the AI systems referenced in the register match the client's AI System Inventory (AIMS-INV-001). Every AI system in the register must have a corresponding inventory entry.
> 5. Assign real risk owners — do not leave `[Name, Role]` placeholders in a delivered document.
> 6. Confirm the EU AI Act deployer obligations section is current. The August 2, 2026 deadline for deployer obligations is approaching; update if the regulatory timeline has changed.
> 7. Remove this entire HOW TO CUSTOMIZE block before delivery.
>
> **Clause traceability:** This document satisfies requirements under ISO/IEC 42001:2023 Clauses 6.1.1, 6.1.2, 6.1.3, 6.1.5, 8.2, and 8.3, and supports implementation of Annex A control A.5.2 (AI System Risk Assessment).

---

## Document Metadata

| Field | Value |
|---|---|
| **Document ID** | AIMS-RISK-001 |
| **Version** | 1.0 |
| **Date** | [YYYY-MM-DD] |
| **Organization** | [Organization Name] |
| **AIMS Scope Reference** | [Reference to AIMS scope document, e.g., AIMS-SCOPE-001] |
| **Prepared By** | [Name, Role] |
| **Approved By** | [Name, Role] |
| **Next Review Date** | [YYYY-MM-DD — no later than 12 months from Date] |

---

> **Legal Disclaimer:** This template does not constitute legal advice. The risk assessment methodology and example risk entries provided herein are for guidance purposes only. Organizations should consult qualified legal counsel for questions about regulatory obligations, including EU AI Act deployer obligations, data protection requirements, and sector-specific compliance requirements. Risk assessments must be tailored to the specific context, operations, and risk appetite of the individual organization.

---

## Clause Traceability

| ISO/IEC 42001:2023 Reference | Requirement Addressed |
|---|---|
| **Clause 6.1.1** | Actions to address risks and opportunities — general |
| **Clause 6.1.2** | AI risk assessment — process requirements |
| **Clause 6.1.3** | AI risk treatment — treatment options and plan |
| **Clause 6.1.5** | Documented information for risk assessment and treatment |
| **Clause 8.2** | AI risk assessment — operational implementation |
| **Clause 8.3** | AI risk treatment — operational implementation |
| **Annex A: A.5.2** | AI System Risk Assessment — control implementation |

---

## Part 1: Risk Assessment Methodology

---

### 1.1 Purpose

This document establishes the methodology by which [Organization Name] identifies, analyzes, evaluates, and treats risks associated with its use of AI systems. It also serves as the organization's AI Risk Register — the living record of identified risks, their current status, and the treatment actions assigned to address them.

AI risk assessment is required by ISO/IEC 42001:2023 because AI systems introduce categories of risk that differ materially from conventional software. AI outputs are probabilistic, not deterministic. AI systems can produce biased, inaccurate, or unexpected results. AI vendors can change model behavior without notice. Employees can misuse AI tools in ways that expose the organization to data protection, regulatory, and reputational harm. These risks require a structured, documented approach to identification and management.

This methodology produces three outputs:

1. **The AI Risk Register** (Part 2 of this document) — a structured record of all identified AI risks, their assessed likelihood and impact, current controls, and treatment decisions.
2. **Risk Treatment Actions** — specific actions assigned to named owners with target completion dates, tracked in the Risk Register and the Risk Treatment Plan (AIMS-RTP-001).
3. **Residual Risk Acceptance Records** — documented decisions by authorized personnel to accept residual risks that fall within the organization's risk acceptance criteria.

---

### 1.2 Scope

This risk assessment covers all AI systems within the organization's AIMS scope as defined in [AIMS-SCOPE-001] and inventoried in the AI System Inventory (AIMS-INV-001). Every AI system listed in the inventory must have at least one risk entry in this register.

The scope includes:

- **Standalone AI applications** subscribed to by the organization (e.g., ChatGPT Enterprise, Microsoft Copilot)
- **AI features embedded in existing SaaS platforms** (e.g., HubSpot AI, Salesforce Einstein, Grammarly Business)
- **API integrations** that call AI/ML services (e.g., OpenAI API, Google Cloud AI)
- **Custom automations** built on AI/ML capabilities (e.g., Zapier AI steps, Power Automate with AI Builder)

This risk assessment does **not** cover:

- Risks associated with AI model training or development (the organization does not develop AI models)
- Risks internal to the AI vendor's infrastructure that are entirely outside the organization's control and not addressable through organizational treatment actions
- General IT and cybersecurity risks not specific to AI (these are addressed in the organization's information security risk register)

---

### 1.3 Risk Assessment Process

The organization follows a five-step risk assessment process for AI systems:

**Step 1 — Identify Risks**

For each AI system in scope, identify risks using the risk categories defined in Section 1.4. Risk identification is conducted through:
- Structured workshops with AI system owners and department heads
- Review of the AI System Inventory (AIMS-INV-001) for data flows, use cases, and user populations
- Review of vendor documentation, terms of service, and data processing agreements
- Review of incident reports and near-misses from the previous period
- Consideration of regulatory developments (EU AI Act, data protection law, sector-specific requirements)

Each identified risk is assigned a unique Risk ID and entered into the Risk Register (Part 2).

**Step 2 — Analyze Likelihood and Impact**

For each identified risk, assess:
- **Likelihood** — How probable is it that this risk will materialize? Use the 1–5 scale defined in Section 1.5.
- **Impact** — If this risk materializes, how severe would the consequences be? Use the 1–5 scale defined in Section 1.5.

Likelihood and impact are assessed based on the current state of controls (i.e., with existing controls in place, not in a hypothetical zero-control scenario).

**Step 3 — Evaluate Risk Level**

Calculate the Risk Score: **Risk Score = Likelihood × Impact**

Map the Risk Score to a Risk Level using the thresholds in Section 1.5. Risk Level determines the urgency and nature of the required treatment response.

**Step 4 — Determine Treatment**

For each risk, select a treatment option (see Section 1.7):
- **Avoid** — Eliminate the risk by discontinuing the activity or AI system
- **Mitigate** — Implement controls to reduce likelihood or impact
- **Transfer** — Shift risk to a third party through contract, insurance, or indemnification
- **Accept** — Formally accept the risk within the organization's risk acceptance criteria (see Section 1.6)

Document the treatment decision, specific treatment actions, assigned owner, and target completion date in the Risk Register.

**Step 5 — Document and Review**

Record all risk assessment outputs in this document. Conduct reviews at the frequency defined in Section 1.8. Update the register when new risks are identified, when treatment actions are completed, or when trigger events occur.

---

### 1.4 Risk Identification Categories

The following categories are used to structure risk identification for AI user organizations. These categories reflect the specific risk profile of organizations that **use** third-party AI systems — they are not generic IT risk categories and do not include AI development risks (model training failures, dataset bias in training) which are vendor responsibilities.

#### Category 1: Data Risks

Risks arising from how organizational data is handled when interacting with AI systems.

| Risk Type | Description | Example |
|---|---|---|
| **Data leakage to AI vendor** | Confidential, personal, or commercially sensitive data is transmitted to an AI vendor's systems and may be used for model training, retained beyond agreed periods, or exposed in a breach | Employee pastes client contract terms into a generative AI prompt |
| **Data quality issues** | Poor-quality input data produces unreliable AI outputs that are then used for business decisions | Incomplete customer records fed into an AI scoring model produce inaccurate risk scores |
| **Unauthorized data processing** | AI systems process personal data in ways not covered by the organization's privacy notices, consent mechanisms, or data processing agreements | AI tool processes employee performance data without a lawful basis under GDPR |
| **Data residency violations** | AI vendor stores or processes data in jurisdictions not permitted under the organization's data protection obligations | EU customer data processed on US-based AI infrastructure without adequate transfer mechanisms |

#### Category 2: Output Risks

Risks arising from the quality, accuracy, or fairness of AI-generated outputs.

| Risk Type | Description | Example |
|---|---|---|
| **Biased or discriminatory outputs** | AI system produces outputs that systematically disadvantage individuals or groups based on protected characteristics or demographic proxies | AI lead scoring model ranks prospects differently based on postcode as a proxy for ethnicity |
| **Inaccurate outputs used for decisions** | AI-generated content or recommendations contain factual errors that are acted upon without adequate human review | AI-generated product specification document contains incorrect technical parameters sent to a customer |
| **Hallucinations and fabrications** | Generative AI produces plausible-sounding but entirely fabricated information presented as fact | AI assistant cites non-existent legal cases or regulatory requirements in a compliance document |
| **Output misattribution** | AI-generated content is presented as human-authored, creating false impressions about the organization's capabilities or communications | Marketing content generated by AI is published without disclosure, creating regulatory or reputational risk |

#### Category 3: Operational Risks

Risks arising from how AI systems are integrated into and affect organizational operations.

| Risk Type | Description | Example |
|---|---|---|
| **Over-reliance on AI** | Staff accept AI recommendations without adequate critical review, particularly for high-stakes decisions | Customer service team approves all AI-generated responses without review, including responses containing errors |
| **Vendor service disruption** | AI vendor experiences outages, service degradation, or discontinues the product, disrupting dependent business processes | Core business workflow dependent on an AI API fails when the vendor experiences a multi-hour outage |
| **AI tool changes without notice** | AI vendor updates model behavior, capabilities, or output format without adequate notice, breaking dependent processes or changing output quality | Vendor silently updates language model, causing previously reliable outputs to change in tone or accuracy |
| **Scope creep** | AI tools are used for purposes beyond their validated and approved use cases, introducing unassessed risks | Tool approved for internal drafting assistance is used to process customer personal data without a DPA review |

#### Category 4: Compliance Risks

Risks arising from failure to meet regulatory, legal, or contractual obligations related to AI use.

| Risk Type | Description | Example |
|---|---|---|
| **EU AI Act non-compliance** | Organization fails to meet deployer obligations under the EU AI Act (effective August 2, 2026), including obligations for high-risk AI systems | Organization uses an AI system that qualifies as high-risk under Annex III of the EU AI Act without conducting required conformity assessment review |
| **Data protection violations** | AI use creates GDPR or equivalent data protection violations through unlawful processing, inadequate consent, or failure to honor data subject rights | AI system retains personal data beyond permitted retention periods; organization cannot fulfill a data subject erasure request |
| **Contractual breaches** | AI use violates terms of service with AI vendors, customer contracts, or partner agreements | Employee uses personal ChatGPT account to process client data in violation of client confidentiality agreement |
| **Sector-specific non-compliance** | AI use violates sector-specific regulations (financial services, healthcare, legal) | AI-generated financial advice provided to customers without required regulatory disclosures |

#### Category 5: Reputational Risks

Risks arising from AI use that damages the organization's reputation or stakeholder trust.

| Risk Type | Description | Example |
|---|---|---|
| **AI-generated content misrepresentation** | AI-generated content misrepresents the organization's positions, capabilities, or commitments | AI-generated press release contains inaccurate claims about the organization's products |
| **Customer trust erosion** | Customers discover undisclosed AI use in interactions or decisions affecting them, damaging trust | Customer discovers their service application was assessed by an AI system without disclosure |
| **Public AI incident** | Organization is publicly associated with an AI-related failure (bias, error, misuse) that attracts media or regulatory attention | AI-generated customer communication contains discriminatory language; incident becomes public |

#### Category 6: Third-Party Risks

Risks arising from the organization's dependence on AI vendors and their practices.

| Risk Type | Description | Example |
|---|---|---|
| **Vendor data handling failures** | AI vendor mishandles organizational data through inadequate security, unauthorized use for training, or breach | AI vendor uses customer data submitted via API to train its models without adequate contractual prohibition |
| **Vendor AI model changes** | Vendor changes the underlying AI model in ways that materially affect output quality or behavior | Vendor replaces underlying LLM with a different model; outputs change in ways that break the organization's review process |
| **Vendor insolvency or exit** | AI vendor ceases operations or exits the market, leaving the organization without a critical tool and potentially without access to its data | Niche AI vendor shuts down with 30 days' notice; organization has no migration plan |
| **Inadequate vendor due diligence** | Organization adopts an AI vendor without adequate assessment of their security, privacy, and compliance posture | AI vendor lacks SOC 2 certification; organization discovers this after processing sensitive customer data |

#### Category 7: Human Oversight Risks

Risks arising from insufficient or ineffective human oversight of AI systems and outputs.

| Risk Type | Description | Example |
|---|---|---|
| **Insufficient human review** | AI outputs are used in consequential decisions without adequate human review, particularly where errors could cause harm | AI-generated customer credit assessments are approved automatically without human review |
| **Automation bias** | Staff systematically defer to AI recommendations even when their own judgment or available evidence suggests the AI may be wrong | Staff override their own correct assessments to align with AI recommendations due to perceived AI authority |
| **Inadequate escalation paths** | No clear process exists for staff to escalate concerns about AI outputs, biased results, or unexpected behavior | Staff notice AI outputs appear biased but have no mechanism to report or escalate the concern |
| **Oversight capability gaps** | Staff lack the competency to meaningfully review AI outputs in their domain | Non-technical staff reviewing AI-generated legal or technical content lack the expertise to identify errors |

---

### 1.5 Risk Scoring Matrix

#### Likelihood Scale

| Score | Level | Definition |
|---|---|---|
| **1** | Rare | The risk is highly unlikely to materialize. No known precedent in the organization or similar organizations. Would require an unusual combination of circumstances. |
| **2** | Unlikely | The risk could materialize but is not expected to. Has occurred in similar organizations but not frequently. |
| **3** | Possible | The risk may materialize. Has occurred in similar organizations. Could reasonably be expected to occur at some point. |
| **4** | Likely | The risk is expected to materialize. Has occurred in the organization or occurs regularly in similar organizations. |
| **5** | Almost Certain | The risk is expected to materialize in the near term. May already be occurring. |

#### Impact Scale

| Score | Level | Definition | Examples |
|---|---|---|---|
| **1** | Negligible | Minimal consequences. No regulatory action. No customer impact. Easily remediated. | Minor internal process disruption; no data involved |
| **2** | Minor | Limited consequences. Internal disruption. No regulatory action. Minor customer impact. | Small number of customers affected; no personal data breach; reputational impact contained |
| **3** | Moderate | Significant consequences. Possible regulatory inquiry. Moderate customer impact. Remediation requires meaningful effort. | Regulatory inquiry initiated; moderate number of customers affected; reputational damage in specific channels |
| **4** | Major | Serious consequences. Regulatory enforcement action possible. Significant customer impact. Substantial remediation cost. | Regulatory fine; significant customer data breach; material reputational damage; litigation risk |
| **5** | Catastrophic | Severe consequences. Regulatory enforcement action likely. Widespread customer impact. Existential threat to the organization or its operations. | Large-scale data breach; significant regulatory fine; class action litigation; severe reputational damage; loss of operating license |

#### Risk Scoring Matrix

| | **Impact 1** | **Impact 2** | **Impact 3** | **Impact 4** | **Impact 5** |
|---|---|---|---|---|---|
| **Likelihood 5** | 5 — Medium | 10 — Medium | 15 — High | 20 — Critical | 25 — Critical |
| **Likelihood 4** | 4 — Low | 8 — Medium | 12 — Medium | 16 — High | 20 — Critical |
| **Likelihood 3** | 3 — Low | 6 — Low | 9 — Medium | 12 — Medium | 15 — High |
| **Likelihood 2** | 2 — Low | 4 — Low | 6 — Low | 8 — Medium | 10 — Medium |
| **Likelihood 1** | 1 — Low | 2 — Low | 3 — Low | 4 — Low | 5 — Medium |

#### Risk Level Thresholds

| Risk Score | Risk Level | Color Code | Required Response |
|---|---|---|---|
| **1–6** | Low | 🟢 Green | Monitor. Accept or treat at discretion. Review annually. |
| **7–12** | Medium | 🟡 Amber | Treatment required. Assign owner and target date. Review within 6 months. |
| **13–19** | High | 🟠 Orange | Priority treatment required. Escalate to senior management. Review within 3 months. |
| **20–25** | Critical | 🔴 Red | Immediate action required. Escalate to top management. Consider suspending AI system use pending treatment. |

---

### 1.6 Risk Acceptance Criteria

The organization's risk acceptance criteria are as follows:

| Risk Level | Acceptance Authority | Conditions for Acceptance |
|---|---|---|
| **Low (1–6)** | AI System Owner | May be accepted without further escalation. Document acceptance decision in Risk Register. |
| **Medium (7–12)** | Department Head or equivalent | May be accepted only if: (a) treatment is not feasible within a reasonable timeframe, and (b) compensating controls are documented. Acceptance must be reviewed at next scheduled review. |
| **High (13–19)** | Senior Management (e.g., COO, CTO, or equivalent) | May be accepted only in exceptional circumstances with documented justification. Acceptance must be reviewed within 3 months. Regulatory risks at this level should not be accepted without legal counsel review. |
| **Critical (20–25)** | Top Management (CEO or Board) | Acceptance requires explicit top management sign-off. Regulatory and data protection risks at this level should not be accepted. Consider suspending the AI system or use case pending treatment. |

**Automatic escalation triggers:** Regardless of risk score, the following conditions require escalation to senior management:
- Any risk involving a potential personal data breach affecting more than 50 individuals
- Any risk involving potential EU AI Act non-compliance for a high-risk AI system
- Any risk that has already materialized (i.e., an incident has occurred)
- Any risk where the organization has received regulatory inquiry or enforcement notice

---

### 1.7 Risk Treatment Options

For each identified risk, the organization selects one of four treatment options:

#### Avoid

Eliminate the risk by discontinuing the activity, use case, or AI system that creates it.

*When to use:* When the risk level is Critical or High and no feasible mitigation exists, or when the business value of the AI system does not justify the risk exposure.

*AI-specific examples:*
- Prohibit use of personal ChatGPT accounts for work tasks involving company data
- Discontinue use of an AI system that cannot provide adequate data processing agreements
- Remove an AI feature from a customer-facing workflow where bias risk cannot be adequately mitigated
- Withdraw from a use case where EU AI Act high-risk classification creates unacceptable compliance burden

#### Mitigate

Implement controls to reduce the likelihood of the risk materializing, reduce the impact if it does, or both.

*When to use:* When the risk can be reduced to an acceptable level through feasible controls without eliminating the business value of the AI system.

*AI-specific examples:*
- Implement data classification training so employees know what data can and cannot be entered into AI prompts
- Establish mandatory human review checkpoints for AI outputs used in customer-facing decisions
- Implement AI acceptable use policy with clear prohibited use cases
- Require vendor data processing agreements before deploying any AI system that processes personal data
- Implement output monitoring to detect quality degradation or unexpected behavior changes
- Establish vendor assessment process to evaluate security and privacy posture before adoption

#### Transfer

Shift the financial or operational consequences of the risk to a third party through contractual terms, insurance, or indemnification.

*When to use:* When the risk cannot be fully mitigated internally but can be partially addressed through contractual protections or insurance coverage.

*AI-specific examples:*
- Negotiate contractual indemnification from AI vendor for data breaches caused by vendor-side failures
- Obtain cyber insurance coverage that explicitly covers AI-related incidents
- Include contractual liability clauses in customer agreements that address AI-generated content errors
- Require AI vendors to maintain their own ISO 27001 or SOC 2 certification as a contractual condition

#### Accept

Formally acknowledge the risk and decide not to take further treatment action, within the organization's risk acceptance criteria.

*When to use:* When the risk level is Low or Medium, treatment costs exceed the expected benefit, and the risk is within the organization's risk appetite.

*AI-specific examples:*
- Accept the residual risk of occasional AI output inaccuracies in low-stakes internal drafting tasks after implementing review procedures
- Accept the risk of vendor model updates for non-critical AI tools where the impact of output changes is minor
- Accept the risk of limited AI vendor transparency for commodity AI tools where the data involved is non-sensitive

---

### 1.8 Review Frequency

#### Scheduled Reviews

| Review Type | Frequency | Trigger | Owner |
|---|---|---|---|
| **Full risk register review** | Annual (minimum) | Calendar-based | AIMS Manager / Risk Owner |
| **High and Critical risk review** | Quarterly | Calendar-based | Senior Management |
| **Post-treatment review** | Within 30 days of treatment action completion | Treatment action closed | Risk Owner |

#### Trigger-Based Reviews

The following events require an unscheduled review of affected risk register entries:

| Trigger Event | Action Required |
|---|---|
| **New AI system adopted** | Add risk entries for the new system before deployment |
| **AI system retired or replaced** | Review and close or transfer associated risk entries |
| **AI incident or near-miss** | Review affected risk entries; reassess likelihood and impact; initiate corrective action |
| **Vendor notifies of model update** | Review risks associated with that vendor's AI system |
| **Regulatory change** | Review compliance risk entries; update treatment actions as required |
| **Organizational change** (restructure, merger, new business line) | Review all risk entries for affected AI systems and use cases |
| **Data protection authority inquiry or enforcement** | Immediate escalation; review all data-related risk entries |
| **EU AI Act deployer obligations effective (August 2, 2026)** | Full compliance risk review; confirm all high-risk AI system obligations are addressed |

---

## Part 2: Risk Register

### How to Use This Register

Each row represents one identified risk. Risks are identified at the level of a specific AI system and use case — not at the level of a risk category. A single AI system may have multiple risk entries across different categories.

**Column Definitions:**

| Column | Definition |
|---|---|
| **Risk ID** | Unique identifier. Format: RISK-NNN. Assign sequentially; do not reuse IDs. |
| **AI System** | The specific AI system or tool to which this risk applies. Must match an entry in AIMS-INV-001. |
| **Risk Category** | The risk category from Section 1.4 (Data, Output, Operational, Compliance, Reputational, Third-Party, Human Oversight). |
| **Risk Description** | A specific, concrete description of the risk scenario. Avoid generic descriptions. Describe what could go wrong, how, and to whom. |
| **Likelihood (1–5)** | Assessed likelihood using the scale in Section 1.5. |
| **Impact (1–5)** | Assessed impact using the scale in Section 1.5. |
| **Risk Score** | Likelihood × Impact. |
| **Risk Level** | Low / Medium / High / Critical, based on thresholds in Section 1.5. |
| **Current Controls** | Controls already in place that were considered when assessing likelihood and impact. |
| **Treatment Decision** | Avoid / Mitigate / Transfer / Accept. |
| **Treatment Actions** | Specific actions to be taken. Include owner and target date. |
| **Residual Risk** | Expected risk level after treatment actions are completed. |
| **Risk Owner** | The named individual responsible for monitoring this risk and ensuring treatment actions are completed. |
| **Review Date** | Date this risk entry is next due for review. |
| **Status** | Open / In Treatment / Closed / Accepted. |

---

### Risk Register Table

> **Note:** The following eight entries are example risks for illustrative purposes. Replace with risks identified during the organization's actual risk assessment workshops. All AI systems referenced must have corresponding entries in AIMS-INV-001.

---

**RISK-001**

| Field | Detail |
|---|---|
| **Risk ID** | RISK-001 |
| **AI System** | Microsoft 365 Copilot |
| **Risk Category** | Data Risks |
| **Risk Description** | An employee pastes confidential client data (e.g., contract terms, financial information, personal data) into a Microsoft Copilot prompt. The data is transmitted to Microsoft's AI infrastructure and may be retained, used for model improvement, or exposed in a future security incident. The organization has not trained staff on what data is permissible to enter into Copilot prompts. |
| **Likelihood** | 3 — Possible |
| **Impact** | 4 — Major |
| **Risk Score** | 12 |
| **Risk Level** | 🟡 Medium |
| **Current Controls** | Microsoft 365 E3/E5 license with commercial data protection commitments. Microsoft's data processing agreement in place. No specific staff training on Copilot data handling. |
| **Treatment Decision** | Mitigate |
| **Treatment Actions** | (1) Develop and publish AI Acceptable Use Policy specifying data classification rules for Copilot use. Target: [Date]. Owner: [IT Manager]. (2) Deliver mandatory staff training on Copilot data handling. Target: [Date]. Owner: [HR/Training Lead]. (3) Review Microsoft Copilot data processing agreement to confirm data retention and training opt-out settings. Target: [Date]. Owner: [IT Manager / DPO]. |
| **Residual Risk** | Low (Score: 6) — after training and policy implementation |
| **Risk Owner** | [IT Manager / Name] |
| **Review Date** | [YYYY-MM-DD] |
| **Status** | Open |

---

**RISK-002**

| Field | Detail |
|---|---|
| **Risk ID** | RISK-002 |
| **AI System** | ChatGPT (personal/free accounts) — Shadow AI |
| **Risk Category** | Compliance Risks / Data Risks |
| **Risk Description** | Employees are using personal ChatGPT accounts (free or paid) to perform work tasks, including processing company data, drafting client communications, and summarizing confidential documents. Personal accounts do not have commercial data protection terms; data may be used by OpenAI for model training. This use is not authorized, not monitored, and not covered by any data processing agreement. This creates GDPR violations, potential contractual breaches with clients, and uncontrolled data leakage. |
| **Likelihood** | 4 — Likely |
| **Impact** | 4 — Major |
| **Risk Score** | 16 |
| **Risk Level** | 🟠 High |
| **Current Controls** | No current controls. No policy prohibiting personal AI account use. No monitoring. No training. |
| **Treatment Decision** | Mitigate + Avoid (partial) |
| **Treatment Actions** | (1) Issue immediate interim guidance prohibiting use of personal AI accounts for work tasks involving company or client data. Target: [Date — within 2 weeks]. Owner: [CEO / Senior Management]. (2) Develop and publish AI Acceptable Use Policy with explicit prohibition on personal AI accounts for work tasks. Target: [Date]. Owner: [IT Manager / DPO]. (3) Evaluate and provision an approved enterprise AI tool (e.g., ChatGPT Enterprise or Microsoft Copilot) to meet staff needs through an authorized channel. Target: [Date]. Owner: [IT Manager]. (4) Deliver staff training on shadow AI risks and the approved AI tools policy. Target: [Date]. Owner: [HR/Training Lead]. |
| **Residual Risk** | Medium (Score: 8) — residual risk of non-compliance with policy; requires ongoing monitoring |
| **Risk Owner** | [IT Manager / Name] |
| **Review Date** | [YYYY-MM-DD — 3 months from Date] |
| **Status** | Open |

---

**RISK-003**

| Field | Detail |
|---|---|
| **Risk ID** | RISK-003 |
| **AI System** | HubSpot AI Lead Scoring |
| **Risk Category** | Output Risks |
| **Risk Description** | HubSpot's AI lead scoring model assigns scores to prospects based on behavioral and demographic data. The model may use variables that serve as proxies for protected characteristics (e.g., postcode as a proxy for ethnicity or socioeconomic status, job title patterns correlated with gender). This could result in systematically lower scores for prospects from certain demographic groups, constituting indirect discrimination. The organization has not reviewed the model's scoring criteria or tested for demographic disparities in outputs. |
| **Likelihood** | 2 — Unlikely |
| **Impact** | 4 — Major |
| **Risk Score** | 8 |
| **Risk Level** | 🟡 Medium |
| **Current Controls** | HubSpot's standard terms of service. No internal bias testing. No review of scoring criteria. Sales team uses scores as one input among several. |
| **Treatment Decision** | Mitigate |
| **Treatment Actions** | (1) Request HubSpot documentation on lead scoring model inputs, methodology, and bias testing. Target: [Date]. Owner: [CRM Owner / Name]. (2) Conduct internal review of lead scoring outputs for demographic patterns — sample 100 recent scored leads and analyze score distribution by available demographic indicators. Target: [Date]. Owner: [Sales Manager / Data Analyst]. (3) Establish policy that AI lead scores are one input to sales prioritization, not the sole determinant. Document human review requirement. Target: [Date]. Owner: [Sales Manager]. |
| **Residual Risk** | Low (Score: 4) — after review and human oversight policy implementation |
| **Risk Owner** | [Sales Manager / Name] |
| **Review Date** | [YYYY-MM-DD] |
| **Status** | Open |

---

**RISK-004**

| Field | Detail |
|---|---|
| **Risk ID** | RISK-004 |
| **AI System** | AI-assisted customer communications (generative AI tool) |
| **Risk Category** | Output Risks |
| **Risk Description** | Staff use a generative AI tool to draft customer-facing communications including product information, pricing details, and service terms. The AI may generate factually incorrect content (wrong prices, incorrect product specifications, inaccurate service terms) that is published or sent to customers without adequate review. Customers may rely on this incorrect information to their detriment, creating contractual, regulatory, and reputational risk for the organization. |
| **Likelihood** | 3 — Possible |
| **Impact** | 3 — Moderate |
| **Risk Score** | 9 |
| **Risk Level** | 🟡 Medium |
| **Current Controls** | Informal peer review for some communications. No formal review process. No AI output review checklist. |
| **Treatment Decision** | Mitigate |
| **Treatment Actions** | (1) Implement mandatory human review and approval process for all AI-generated customer-facing content before publication or sending. Target: [Date]. Owner: [Marketing/Communications Manager]. (2) Develop AI output review checklist for customer communications (factual accuracy, pricing, regulatory compliance). Target: [Date]. Owner: [Marketing/Communications Manager]. (3) Add AI disclosure statement to relevant customer communications where required by applicable law or organizational policy. Target: [Date]. Owner: [DPO / Legal]. |
| **Residual Risk** | Low (Score: 3) — after mandatory review process implementation |
| **Risk Owner** | [Marketing/Communications Manager / Name] |
| **Review Date** | [YYYY-MM-DD] |
| **Status** | Open |

---

**RISK-005**

| Field | Detail |
|---|---|
| **Risk ID** | RISK-005 |
| **AI System** | [Primary AI Tool — e.g., Microsoft Copilot / ChatGPT Enterprise] |
| **Risk Category** | Operational Risks |
| **Risk Description** | The AI vendor updates the underlying AI model without providing adequate advance notice to the organization. The update changes output behavior, tone, accuracy characteristics, or format in ways that break dependent business processes, invalidate established review procedures, or produce outputs that no longer meet the organization's quality standards. The organization has no mechanism to detect model changes or assess their impact before they affect operations. |
| **Likelihood** | 3 — Possible |
| **Impact** | 3 — Moderate |
| **Risk Score** | 9 |
| **Risk Level** | 🟡 Medium |
| **Current Controls** | Vendor change notifications (if subscribed). No internal process for monitoring output quality changes. No baseline output quality documentation. |
| **Treatment Decision** | Mitigate |
| **Treatment Actions** | (1) Subscribe to vendor change notification channels (release notes, product blogs, API changelogs) for all in-scope AI systems. Target: [Date]. Owner: [IT Manager]. (2) Establish a lightweight output quality monitoring process — periodic spot-checks of AI outputs against established quality criteria. Target: [Date]. Owner: [AI System Owner per system]. (3) Document baseline output characteristics for critical AI use cases to enable comparison after vendor updates. Target: [Date]. Owner: [IT Manager / AI System Owners]. (4) Include vendor notification obligations in AI vendor contracts at next renewal. Target: [Contract renewal date]. Owner: [Procurement / Legal]. |
| **Residual Risk** | Low (Score: 6) — after monitoring and notification processes implemented |
| **Risk Owner** | [IT Manager / Name] |
| **Review Date** | [YYYY-MM-DD] |
| **Status** | Open |

---

**RISK-006**

| Field | Detail |
|---|---|
| **Risk ID** | RISK-006 |
| **AI System** | All in-scope AI systems |
| **Risk Category** | Compliance Risks |
| **Risk Description** | The organization is unaware of or has not assessed its obligations as an AI deployer under the EU AI Act (Regulation 2024/1689). Deployer obligations take effect August 2, 2026. If any AI system in use qualifies as a high-risk AI system under Annex III of the EU AI Act, the organization faces specific obligations including fundamental rights impact assessments, human oversight requirements, record-keeping, and transparency to affected individuals. Non-compliance may result in regulatory fines of up to €15 million or 3% of global annual turnover. |
| **Likelihood** | 3 — Possible |
| **Impact** | 5 — Catastrophic |
| **Risk Score** | 15 |
| **Risk Level** | 🟠 High |
| **Current Controls** | No current EU AI Act compliance assessment. No classification of AI systems against EU AI Act risk categories. No awareness training on EU AI Act deployer obligations. |
| **Treatment Decision** | Mitigate |
| **Treatment Actions** | (1) Conduct EU AI Act deployer obligations assessment — classify all in-scope AI systems against EU AI Act risk categories (prohibited, high-risk, limited risk, minimal risk). Target: [Date — before August 2, 2026]. Owner: [DPO / Legal / AIMS Manager]. (2) For any AI system classified as high-risk: conduct fundamental rights impact assessment, implement required human oversight, establish record-keeping. Target: [Date]. Owner: [DPO / Legal]. (3) Deliver EU AI Act awareness training to relevant staff. Target: [Date]. Owner: [HR/Training Lead]. (4) Establish process for monitoring EU AI Act regulatory guidance and updates. Target: [Date]. Owner: [DPO / AIMS Manager]. |
| **Residual Risk** | Medium (Score: 9) — residual compliance risk remains until full assessment and implementation complete; review after August 2026 |
| **Risk Owner** | [DPO / Legal / Name] |
| **Review Date** | [YYYY-MM-DD — within 3 months; mandatory review before August 2, 2026] |
| **Status** | Open |

---

**RISK-007**

| Field | Detail |
|---|---|
| **Risk ID** | RISK-007 |
| **AI System** | All AI systems used in consequential decisions |
| **Risk Category** | Human Oversight Risks |
| **Risk Description** | Staff accept AI recommendations without adequate critical review for decisions that have significant consequences for customers, employees, or the organization. This includes automation bias — the tendency to defer to AI outputs even when the staff member's own judgment or available evidence suggests the AI may be wrong. High-stakes decisions affected may include customer credit or service assessments, employee performance evaluations, supplier selection, and pricing decisions. Errors in these decisions may cause harm to affected individuals and expose the organization to legal and regulatory risk. |
| **Likelihood** | 3 — Possible |
| **Impact** | 4 — Major |
| **Risk Score** | 12 |
| **Risk Level** | 🟡 Medium |
| **Current Controls** | No formal human oversight policy. No defined review requirements for AI-assisted decisions. No training on automation bias. |
| **Treatment Decision** | Mitigate |
| **Treatment Actions** | (1) Define and document human oversight requirements for each AI use case — specify which decisions require human review, what that review must include, and who is authorized to approve. Target: [Date]. Owner: [AIMS Manager / Department Heads]. (2) Develop and deliver training on automation bias and responsible AI use, including practical guidance on when and how to override AI recommendations. Target: [Date]. Owner: [HR/Training Lead]. (3) Implement review records for high-stakes AI-assisted decisions — document that human review occurred and the reviewer's assessment. Target: [Date]. Owner: [Department Heads]. (4) Establish escalation path for staff to raise concerns about AI outputs without fear of retaliation. Target: [Date]. Owner: [AIMS Manager / HR]. |
| **Residual Risk** | Low (Score: 6) — after oversight policy and training implemented |
| **Risk Owner** | [AIMS Manager / Name] |
| **Review Date** | [YYYY-MM-DD] |
| **Status** | Open |

---

**RISK-008**

| Field | Detail |
|---|---|
| **Risk ID** | RISK-008 |
| **AI System** | All AI systems processing customer personal data |
| **Risk Category** | Third-Party Risks |
| **Risk Description** | An AI vendor suffers a data breach that exposes customer personal data processed through the vendor's AI system. The organization has transmitted customer data to the vendor's infrastructure as part of normal AI system use (e.g., via API calls, file uploads, or prompt inputs). The vendor's breach triggers the organization's own GDPR notification obligations (72-hour notification to supervisory authority; notification to affected individuals). The organization may face regulatory scrutiny for inadequate vendor due diligence and contractual protections. |
| **Likelihood** | 2 — Unlikely |
| **Impact** | 5 — Catastrophic |
| **Risk Score** | 10 |
| **Risk Level** | 🟡 Medium |
| **Current Controls** | Data processing agreements in place with primary AI vendors. Vendor security certifications reviewed at initial procurement. No ongoing vendor security monitoring. No data breach response procedure specific to AI vendor incidents. |
| **Treatment Decision** | Mitigate + Transfer |
| **Treatment Actions** | (1) Review and update data processing agreements with all AI vendors processing personal data — confirm breach notification obligations, timelines, and indemnification terms. Target: [Date]. Owner: [DPO / Legal]. (2) Implement annual vendor security review process — confirm AI vendors maintain current security certifications (ISO 27001, SOC 2 Type II). Target: [Date]. Owner: [IT Manager / Procurement]. (3) Update data breach response procedure to include AI vendor breach scenarios — define internal escalation, supervisory authority notification, and customer notification processes. Target: [Date]. Owner: [DPO]. (4) Review cyber insurance policy to confirm coverage for AI vendor breach scenarios. Target: [Date]. Owner: [Finance / Legal]. (5) Minimize personal data transmitted to AI vendors — implement data minimization review for all AI use cases involving personal data. Target: [Date]. Owner: [DPO / IT Manager]. |
| **Residual Risk** | Low (Score: 4) — after DPA review, monitoring, and response procedure implementation |
| **Risk Owner** | [DPO / Name] |
| **Review Date** | [YYYY-MM-DD] |
| **Status** | Open |

---

### Adding New Risk Entries

When adding new risks to this register, copy the template below and complete all fields:

```
**RISK-[NNN]**

| Field | Detail |
|---|---|
| **Risk ID** | RISK-[NNN] |
| **AI System** | [AI System Name — must match AIMS-INV-001] |
| **Risk Category** | [Data / Output / Operational / Compliance / Reputational / Third-Party / Human Oversight] |
| **Risk Description** | [Specific, concrete description of the risk scenario] |
| **Likelihood** | [1–5] — [Level] |
| **Impact** | [1–5] — [Level] |
| **Risk Score** | [Likelihood × Impact] |
| **Risk Level** | [🟢 Low / 🟡 Medium / 🟠 High / 🔴 Critical] |
| **Current Controls** | [Controls already in place] |
| **Treatment Decision** | [Avoid / Mitigate / Transfer / Accept] |
| **Treatment Actions** | [Specific actions with owner and target date] |
| **Residual Risk** | [Expected level after treatment] |
| **Risk Owner** | [Name, Role] |
| **Review Date** | [YYYY-MM-DD] |
| **Status** | [Open / In Treatment / Closed / Accepted] |
```

---

## Part 3: Risk Summary Dashboard

> **Note:** Update this dashboard whenever the Risk Register is updated. This section provides a management-level view of the organization's AI risk profile.

---

### 3.1 Risk Register Summary

| Metric | Count |
|---|---|
| **Total risks in register** | 8 *(update with actual count)* |
| **Critical risks (Score 20–25)** | 0 |
| **High risks (Score 13–19)** | 2 (RISK-002, RISK-006) |
| **Medium risks (Score 7–12)** | 6 (RISK-001, RISK-003, RISK-004, RISK-005, RISK-007, RISK-008) |
| **Low risks (Score 1–6)** | 0 |
| **Risks with open treatment actions** | 8 |
| **Risks accepted (no treatment)** | 0 |
| **Risks closed** | 0 |

---

### 3.2 Risks by AI System

| AI System | Risk Count | Highest Risk Level | Risk IDs |
|---|---|---|---|
| Microsoft 365 Copilot | 1 | 🟡 Medium | RISK-001 |
| ChatGPT (personal accounts) — Shadow AI | 1 | 🟠 High | RISK-002 |
| HubSpot AI Lead Scoring | 1 | 🟡 Medium | RISK-003 |
| AI-assisted customer communications | 1 | 🟡 Medium | RISK-004 |
| [Primary AI Tool] | 1 | 🟡 Medium | RISK-005 |
| All in-scope AI systems | 2 | 🟠 High | RISK-006, RISK-007 |
| All AI systems processing personal data | 1 | 🟡 Medium | RISK-008 |

*Update this table to reflect the organization's actual AI system inventory.*

---

### 3.3 Risks by Category

| Risk Category | Risk Count | Highest Risk Level | Risk IDs |
|---|---|---|---|
| Data Risks | 1 | 🟡 Medium | RISK-001 |
| Output Risks | 2 | 🟡 Medium | RISK-003, RISK-004 |
| Operational Risks | 1 | 🟡 Medium | RISK-005 |
| Compliance Risks | 2 | 🟠 High | RISK-002 (partial), RISK-006 |
| Reputational Risks | 0 | — | — |
| Third-Party Risks | 1 | 🟡 Medium | RISK-008 |
| Human Oversight Risks | 1 | 🟡 Medium | RISK-007 |

*Note: RISK-002 spans both Compliance and Data risk categories.*

---

### 3.4 Open Treatment Actions Summary

| Risk ID | AI System | Treatment Action Summary | Owner | Target Date | Status |
|---|---|---|---|---|---|
| RISK-001 | Microsoft Copilot | Develop AI Acceptable Use Policy; deliver staff training; review DPA | [IT Manager] | [Date] | Open |
| RISK-002 | Shadow AI (ChatGPT personal) | Issue interim guidance; publish AUP; provision enterprise AI tool; deliver training | [IT Manager] | [Date] | Open |
| RISK-003 | HubSpot AI Lead Scoring | Request vendor documentation; conduct bias review; implement human oversight policy | [Sales Manager] | [Date] | Open |
| RISK-004 | AI customer communications | Implement mandatory review process; develop review checklist; add AI disclosure | [Comms Manager] | [Date] | Open |
| RISK-005 | Primary AI Tool | Subscribe to vendor notifications; implement output monitoring; document baselines | [IT Manager] | [Date] | Open |
| RISK-006 | All AI systems | Conduct EU AI Act assessment; implement high-risk obligations; deliver training | [DPO / Legal] | [Before Aug 2026] | Open |
| RISK-007 | All consequential decision AI | Define oversight requirements; deliver automation bias training; implement review records | [AIMS Manager] | [Date] | Open |
| RISK-008 | All AI systems (personal data) | Review DPAs; implement vendor security review; update breach response; review insurance | [DPO] | [Date] | Open |

---

### 3.5 Risk Trend

| Review Period | Total Risks | Critical | High | Medium | Low | New Risks Added | Risks Closed |
|---|---|---|---|---|---|---|---|
| [Initial Assessment — Date] | 8 | 0 | 2 | 6 | 0 | 8 | 0 |
| [Next Review — Date] | | | | | | | |
| [Following Review — Date] | | | | | | | |

*Update this table at each scheduled review to track risk profile trends over time.*

---

## Version History

| Version | Date | Author | Changes |
|---|---|---|---|
| 1.0 | [YYYY-MM-DD] | [Name] | Initial version |

---

*ISO 42001 Readiness Service Toolkit | 03-Remediation | Confidential Client Deliverable*
