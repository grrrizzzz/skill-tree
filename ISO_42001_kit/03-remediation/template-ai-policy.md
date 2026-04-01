# AI Policy — [Organization Name]

> **Current as of:** March 2026 | ISO/IEC 42001:2023 | EU AI Act (Regulation 2024/1689)

---

> **HOW TO CUSTOMIZE THIS TEMPLATE (Remove this block before delivery)**
>
> This template is designed for organizations that **use** third-party AI tools and do not develop or train AI models. It is not appropriate for AI developers or providers without significant modification.
>
> **Required customizations:**
> 1. Replace all `[bracketed placeholders]` with organization-specific content.
> 2. Section 3 (Definitions): Remove any terms not relevant to the organization's AI context.
> 3. Section 5 (Roles and Responsibilities): Adjust role titles to match the organization's actual structure. Small organizations may consolidate roles.
> 4. Section 9 (Acceptable Use): Confirm the Acceptable Use Policy (AIMS-AUP-001) has been completed and is referenced correctly.
> 5. Section 14 (Related Documents): Update the document list to reflect only documents that exist in the organization's AIMS.
> 6. **Legal review:** This policy should be reviewed by qualified legal counsel before board approval, particularly for organizations subject to EU AI Act obligations or sector-specific AI regulations.
> 7. **Remove this block** before presenting to the client or submitting for board approval.
>
> *Consultant note: This is the first document a certification auditor will request. It must be complete, signed, and version-controlled before Stage 1 audit.*

---

## Document Metadata

| Field | Value |
|---|---|
| **Document ID** | AIMS-POL-001 |
| **Version** | 1.0 |
| **Effective Date** | [YYYY-MM-DD] |
| **Organization** | [Organization Name] |
| **Document Owner** | [Name, Role — e.g., Chief Operating Officer] |
| **Approved By** | [Name, Role — e.g., Board of Directors / CEO] |
| **Next Review Date** | [YYYY-MM-DD — no later than 12 months from Effective Date] |
| **Classification** | Public / Internal (select one) |
| **AIMS Scope Reference** | AIMS-SCOPE-001 |

---

> **Legal Disclaimer:** This template does not constitute legal advice. It is provided as a starting point for organizations implementing an AI Management System in accordance with ISO/IEC 42001:2023. Organizations should consult qualified legal counsel regarding their specific regulatory obligations, including but not limited to obligations under the EU AI Act (Regulation 2024/1689), applicable data protection legislation, and sector-specific AI regulations. Regulatory requirements evolve; organizations are responsible for ensuring this policy remains current with applicable law.

---

## 1. Purpose
*ISO/IEC 42001:2023 — Clause 5.2 | Control A.2.2*

[Organization Name] (the "Organization") is committed to using artificial intelligence (AI) tools and systems in a manner that is responsible, ethical, and aligned with our organizational values and legal obligations.

This policy establishes the Organization's governing framework for the acquisition, deployment, use, and oversight of AI systems within the scope of our AI Management System (AIMS). It communicates our commitment to responsible AI to employees, customers, suppliers, regulators, and other interested parties.

This policy exists because AI tools carry risks that differ from conventional software: they can produce outputs that are difficult to explain, may reflect biases present in training data, and can affect individuals in ways that are not immediately visible. Governing these risks requires explicit commitments at the organizational level, not just technical controls.

*Example statement for board approval:*
> *"[Organization Name] recognizes that AI tools are increasingly embedded in our business operations. We are committed to using these tools in ways that are fair, transparent, and accountable — and to maintaining human oversight of AI-assisted decisions that affect our customers, employees, and partners. This policy is the foundation of that commitment."*

---

## 2. Scope
*ISO/IEC 42001:2023 — Clause 4.3 | Control A.2.2*

### 2.1 Systems Covered

This policy applies to all AI systems within the Organization's defined AIMS scope, as documented in AIMS-SCOPE-001 and inventoried in the AI System Inventory (AIMS-INV-001). This includes:

- Standalone AI applications subscribed to by the Organization (e.g., generative AI platforms, AI-powered analytics tools)
- AI features embedded in existing software platforms used by the Organization (e.g., AI-assisted features in CRM, HR, finance, or productivity software)
- AI capabilities accessed through application programming interfaces (APIs) integrated into the Organization's systems or workflows
- AI tools used by employees, contractors, or third parties on behalf of the Organization

### 2.2 Organizational Units Covered

This policy applies to all organizational units, departments, and functions of [Organization Name], including:

- All employees (full-time, part-time, and casual)
- Contractors, consultants, and temporary workers with access to the Organization's systems or data
- Third-party service providers who use AI tools to deliver services to the Organization

### 2.3 Exclusions

The following are outside the scope of this policy:

- Rule-based automation using only deterministic logic (no machine learning component)
- Traditional statistical reporting and analytics dashboards without predictive modeling
- AI systems used exclusively by third-party suppliers in their own operations, where the Organization has no control over or input to those systems

*Note: When in doubt about whether a system falls within scope, refer to the AI System Inventory (AIMS-INV-001) or consult the AIMS Owner.*

---

## 3. Definitions
*ISO/IEC 42001:2023 — Clause 3 | Controlled Vocabulary: AIMS-GLOSS-001*

The following terms are used throughout this policy. Full definitions are maintained in the Organization's Controlled Vocabulary (AIMS-GLOSS-001).

| Term | Definition |
|---|---|
| **AI Management System (AIMS)** | The framework of policies, procedures, roles, and controls through which the Organization governs its AI activities. |
| **AI System** | An engineered system that generates outputs such as predictions, recommendations, decisions, or content that influence real or virtual environments, operating with varying levels of autonomy. |
| **AI Tool** | A specific software application or feature incorporating AI system capabilities, used by the Organization to perform business tasks (e.g., Microsoft Copilot, ChatGPT Enterprise, Salesforce Einstein). |
| **AI User** | An entity that uses an AI system for its intended purpose. The Organization is an AI user; it did not develop or train the AI systems it uses. |
| **Responsible AI** | An approach to AI use that prioritizes fairness (avoiding discriminatory outcomes), transparency (explainability of AI decisions), accountability (clear ownership of AI-related decisions), and safety (preventing harm to individuals and society). |
| **Interested Parties** | Persons or organizations that can affect, be affected by, or perceive themselves to be affected by the Organization's AI-related decisions and activities. Includes employees, customers, regulators, and suppliers. |
| **Shadow AI** | The use of AI tools by employees without organizational knowledge, approval, or governance controls. Shadow AI is a prohibited practice under this policy. |
| **Third-Party AI** | An AI system developed, trained, and maintained by an external vendor and accessed by the Organization through a commercial product, API, or service subscription. |

---

## 4. AI Governance Principles
*ISO/IEC 42001:2023 — Clause 5.2 | Control A.2.3*

The Organization's use of AI is governed by the following responsible AI principles. These principles apply to all AI systems within scope and inform all AI-related decisions, from tool selection to operational use.

### 4.1 Fairness

The Organization is committed to using AI tools in ways that do not produce discriminatory or inequitable outcomes. Before deploying AI tools that affect individuals (including employees, customers, or applicants), the Organization will assess the potential for biased outputs and implement appropriate mitigations.

### 4.2 Transparency

The Organization will be transparent about its use of AI with employees, customers, and other interested parties. Where AI tools influence decisions that affect individuals, the Organization will disclose the role of AI and, where practicable, provide meaningful explanations of AI-assisted outcomes.

### 4.3 Accountability

Clear ownership of AI-related decisions and their consequences is maintained at all times. AI tools do not relieve individuals or the Organization of accountability for decisions made using AI outputs. The AIMS Owner is accountable for the overall governance framework; AI System Owners are accountable for the responsible use of specific tools.

### 4.4 Human Oversight

The Organization maintains meaningful human oversight of AI-assisted processes, particularly where AI outputs influence decisions that affect individuals or carry significant business, legal, or reputational risk. AI tools are used to support human judgment, not replace it.

### 4.5 Privacy

The Organization will not use AI tools in ways that compromise the privacy of individuals. Data entered into AI tools must comply with the Organization's data protection obligations and the data handling requirements set out in the Acceptable Use Policy (AIMS-AUP-001).

### 4.6 Safety

The Organization will assess and manage risks associated with AI tool use, including risks of harm to individuals, operational disruption, and reputational damage. AI tools will not be used in contexts where the risk of harm is unacceptable and cannot be adequately mitigated.

### 4.7 Societal Responsibility

The Organization recognizes that AI use has implications beyond the immediate transaction or interaction. We will not use AI tools in ways that contribute to societal harm, undermine public trust in AI, or violate applicable laws and regulations.

*Example responsible AI principles statement for inclusion in board communications:*
> *"Our AI governance principles — fairness, transparency, accountability, human oversight, privacy, safety, and societal responsibility — are not aspirational statements. They are operationalized through specific controls in our AI Management System, including impact assessments, acceptable use policies, and human review requirements for high-stakes AI-assisted decisions."*

---

## 5. Roles and Responsibilities
*ISO/IEC 42001:2023 — Clause 5.3 | Control A.3.2*

The following roles carry specific AI governance responsibilities. Role assignments are documented in the AIMS Roles and Responsibilities Register (AIMS-ROLES-001).

| Role | Responsibilities |
|---|---|
| **AIMS Owner** (e.g., COO, CEO, or designated senior leader) | Overall accountability for the AIMS; approves this policy and its revisions; chairs management review; ensures adequate resources for AIMS implementation. |
| **AI System Owner** (assigned per AI tool) | Accountable for the responsible use of a specific AI system; maintains the system's inventory record; conducts or commissions impact assessments; monitors system performance and vendor compliance. |
| **IT Lead / IT Manager** | Manages technical integration of AI tools; maintains the approved AI tools list; reviews and approves new AI tool requests; monitors for shadow AI. |
| **Department Heads** | Ensure staff within their teams comply with this policy and the Acceptable Use Policy; identify AI tool needs and submit requests through the approved process; escalate AI-related incidents. |
| **All Employees and Contractors** | Use AI tools only as permitted by this policy and the Acceptable Use Policy; complete required AI awareness training; report AI-related incidents, unexpected outputs, or policy violations. |
| **Legal / Compliance** | Advises on regulatory obligations related to AI use; reviews AI-related contracts and data processing agreements; monitors regulatory developments. |
| **Data Protection Officer (if applicable)** | Advises on data protection implications of AI tool use; reviews impact assessments for data protection considerations; liaises with regulators as required. |

*Example roles table for a small organization (fewer than 50 employees):*
> *In smaller organizations, the AIMS Owner and AI System Owner roles may be held by the same individual (e.g., the CEO or Operations Manager). Where roles are consolidated, the individual must ensure that all responsibilities are fulfilled and that there is no conflict of interest in oversight activities.*

---

## 6. AI Risk Management
*ISO/IEC 42001:2023 — Clauses 6.1.2, 6.1.3 | Controls A.5.2*

The Organization is committed to identifying, assessing, and treating risks associated with AI systems within scope. AI risk management is integrated into the Organization's overall risk management framework.

### 6.1 Risk Assessment

The Organization will conduct a formal AI risk assessment for each AI system within scope, prior to deployment and at least annually thereafter. Risk assessments will consider:

- Technical risks (e.g., inaccurate outputs, system failures, data leakage)
- Ethical and fairness risks (e.g., biased outputs, discriminatory outcomes)
- Operational risks (e.g., over-reliance on AI, loss of human expertise)
- Legal and regulatory risks (e.g., non-compliance with data protection law, EU AI Act obligations)
- Reputational risks (e.g., public disclosure of AI misuse)

Risk assessments are documented using the AI Risk Assessment template (AIMS-RISK-001).

### 6.2 Risk Treatment

For each identified risk, the Organization will select and implement appropriate treatment options, which may include:

- Avoiding the risk by not deploying or discontinuing use of an AI tool
- Accepting the risk where it falls within the Organization's defined risk appetite
- Transferring the risk through contractual terms with AI vendors
- Mitigating the risk through operational controls, usage restrictions, or human oversight requirements

Risk treatment decisions are documented in the Risk Treatment Plan (AIMS-RTP-001) and reflected in the Statement of Applicability (AIMS-SOA-001).

### 6.3 Risk Monitoring

Identified risks and treatment measures are reviewed at least annually and following any significant change to an AI system, its use, or the regulatory environment. Risk monitoring outputs are reported to the AIMS Owner and reviewed at management review.

---

## 7. AI System Impact Assessment
*ISO/IEC 42001:2023 — Clauses 6.1.4 | Controls A.5.3, A.5.4*

The Organization recognizes that AI systems can have significant impacts on individuals and groups, including employees, customers, and members of the public. Impact assessment is a distinct and required activity, separate from risk assessment.

### 7.1 When Impact Assessment Is Required

An AI System Impact Assessment (AISIA) is required:

- Before deploying any new AI system within scope
- When an existing AI system is materially changed (new use case, new data inputs, significant vendor update)
- At least annually for AI systems that affect individuals (e.g., AI tools used in hiring, customer service, credit assessment, or performance management)
- When an incident or near-miss suggests that an AI system may be causing unintended harm

### 7.2 Impact Assessment Content

Impact assessments will evaluate:

- The potential effects of the AI system on individuals and groups, including vulnerable populations
- The potential for discriminatory, unfair, or harmful outcomes
- Privacy and data protection implications
- Mitigations applied and residual impacts
- Human oversight measures in place

Impact assessments are documented using the AI System Impact Assessment template (AIMS-AISIA-001) and reviewed by the AI System Owner and, where applicable, the Data Protection Officer.

---

## 8. Third-Party AI Governance
*ISO/IEC 42001:2023 | Controls A.10.2, A.6.2.11*

The Organization uses AI systems developed and maintained by third-party vendors. Managing third-party AI risk is a primary governance obligation.

### 8.1 Vendor Assessment

Before adopting any new AI tool, the Organization will conduct a vendor assessment covering:

- The vendor's AI governance practices and responsible AI commitments
- Data processing terms, including where data is stored, how it is used, and whether it is used to train the vendor's models
- Security certifications and incident response capabilities
- Regulatory compliance posture (including EU AI Act obligations where applicable)
- Contractual protections, including data processing agreements and liability terms

Vendor assessments are documented using the AI Supplier Assessment template (AIMS-SUP-001).

### 8.2 Ongoing Supplier Monitoring

Approved AI vendors are subject to ongoing monitoring, including:

- Annual review of vendor compliance and contractual terms
- Review of vendor security and compliance certifications
- Assessment of material changes to vendor AI systems, terms of service, or data handling practices
- Escalation to the AIMS Owner where vendor practices fall below required standards

### 8.3 Contractual Requirements

All AI vendor contracts must include, at minimum:

- A data processing agreement compliant with applicable data protection law
- Clarity on whether organizational data is used to train vendor AI models (and opt-out rights where applicable)
- Incident notification obligations
- Audit rights or equivalent assurance mechanisms

---

## 9. Acceptable Use
*ISO/IEC 42001:2023 | Controls A.6.2.10, A.9.3, A.9.4*

### 9.1 Acceptable Use Policy

The Organization's Acceptable Use Policy (AIMS-AUP-001) governs how employees, contractors, and third parties may use AI tools in the course of their work. All personnel within scope of this policy are required to read, understand, and comply with the Acceptable Use Policy.

### 9.2 Approved AI Tools

Only AI tools that have been assessed, approved, and listed in the Organization's Approved AI Tools Register (maintained by IT) may be used for work purposes. The use of unapproved AI tools with organizational data is prohibited.

### 9.3 Summary of Prohibited Uses

The following uses of AI tools are prohibited under this policy. Full details are set out in the Acceptable Use Policy (AIMS-AUP-001):

- Entering customer personally identifiable information (PII) into AI tools not approved for that data classification
- Using personal AI accounts for work purposes involving organizational data
- Using AI tools to make final decisions about individuals (e.g., hiring, termination, credit, service denial) without mandatory human review
- Using AI to generate content that misrepresents the Organization or its products and services
- Using AI tools not on the approved list without prior IT and compliance approval
- Sharing confidential business information with AI tools without authorization

### 9.4 Shadow AI

The use of AI tools outside the Organization's approved governance process (shadow AI) is prohibited. Employees who discover or suspect shadow AI use must report it through the incident reporting process (AIMS-INC-001).

---

## 10. Human Oversight
*ISO/IEC 42001:2023 | Control A.9.5*

The Organization is committed to maintaining meaningful human oversight of AI-assisted processes. AI tools are decision-support tools; they do not replace human judgment or organizational accountability.

### 10.1 Oversight Requirements

Human review is mandatory before acting on AI outputs in the following contexts:

- Decisions that affect an individual's employment, compensation, or performance assessment
- Decisions that affect a customer's access to products, services, or credit
- Customer-facing communications generated by AI tools
- Financial decisions above [insert threshold, e.g., $10,000] informed by AI analysis
- Any AI output that will be presented as fact in a legal, regulatory, or contractual context

### 10.2 Override Capability

The Organization will ensure that human operators retain the ability to override, correct, or disregard AI outputs in all operational contexts. No AI system within scope will be configured in a way that prevents human intervention.

### 10.3 Escalation

Where an AI output is unexpected, potentially harmful, or raises ethical concerns, the employee must escalate to their manager and, where appropriate, to the AIMS Owner. Escalation procedures are set out in the Incident Reporting Procedure (AIMS-INC-001).

---

## 11. Transparency
*ISO/IEC 42001:2023 | Controls A.8.2, A.8.3*

### 11.1 Disclosure to Customers and Interested Parties

The Organization will disclose to customers and other interested parties when AI tools are used in ways that materially affect them, including:

- When customer-facing communications are generated or substantially assisted by AI
- When AI tools are used to make or inform decisions about individual customers (e.g., pricing, service eligibility, risk scoring)
- When customers interact directly with AI-powered interfaces (e.g., AI chatbots, virtual assistants)

Disclosure will be made in plain language, at the point of interaction or in the Organization's published privacy notice, as appropriate.

### 11.2 Explanation of AI-Assisted Decisions

Where an AI-assisted decision significantly affects an individual, the Organization will, upon request, provide a meaningful explanation of the factors that influenced the decision and the role of AI in reaching it. This obligation applies to employees and customers alike.

### 11.3 Internal Transparency

The Organization will maintain an accurate and current AI System Inventory (AIMS-INV-001) that documents all AI systems in use. This inventory is available to the AIMS Owner, AI System Owners, and internal auditors.

---

## 12. Compliance and Review
*ISO/IEC 42001:2023 — Clauses 9.3, 10.2*

### 12.1 Regulatory Compliance

The Organization is committed to complying with all applicable laws and regulations governing AI use, including:

- EU AI Act (Regulation 2024/1689), where applicable to the Organization's AI systems and activities
- Applicable data protection legislation (e.g., GDPR, UK GDPR, or equivalent)
- Sector-specific AI regulations applicable to the Organization's industry
- Consumer protection and anti-discrimination laws as they apply to AI-assisted decisions

The Legal/Compliance function is responsible for monitoring regulatory developments and advising the AIMS Owner of changes that require policy updates.

### 12.2 Policy Review

This policy will be reviewed at least annually, or sooner if:

- A significant change occurs in the Organization's AI tool portfolio
- A material regulatory change affects the Organization's AI obligations
- An AI-related incident reveals a gap in the policy
- The certification body or an internal audit identifies a nonconformity related to this policy

Policy reviews are conducted by the AIMS Owner with input from Legal/Compliance, IT, and relevant department heads. Revised policies require board or senior leadership approval before taking effect.

### 12.3 Management Review Integration

AI policy compliance and performance are standing agenda items at the Organization's annual management review, conducted in accordance with the Management Review Procedure (AIMS-MR-001). Management review outputs include decisions on policy revisions, resource allocation, and corrective actions.

### 12.4 Internal Audit

Compliance with this policy is assessed as part of the Organization's annual internal audit of the AIMS. Internal audit findings related to this policy are reported to the AIMS Owner and addressed through the corrective action process (AIMS-CAR-001).

---

## 13. Policy Exceptions
*ISO/IEC 42001:2023 — Clause 6.1*

### 13.1 Exception Process

Exceptions to this policy may be granted in limited circumstances where strict compliance would create an unreasonable operational burden and the exception does not materially increase risk to individuals or the Organization.

To request an exception:

1. Submit a written request to the AIMS Owner, describing the specific policy requirement, the reason for the exception, the proposed alternative control, and the duration of the exception.
2. The AIMS Owner will review the request with Legal/Compliance and IT within [10] business days.
3. Approved exceptions are documented in the Policy Exception Register and reviewed at the next management review.
4. Exceptions are time-limited (maximum 12 months) and must be renewed if the underlying circumstances persist.

### 13.2 No Exceptions to Core Prohibitions

Exceptions will not be granted for the following:

- The prohibition on using unapproved AI tools with customer PII
- The requirement for human review of AI-assisted decisions affecting individuals
- The requirement to conduct impact assessments before deploying new AI systems

---

## 14. Related Documents

The following documents form part of the Organization's AIMS and should be read in conjunction with this policy:

| Document ID | Document Title |
|---|---|
| AIMS-SCOPE-001 | AIMS Scope Document |
| AIMS-GLOSS-001 | Controlled Vocabulary and Key Definitions |
| AIMS-AUP-001 | Acceptable Use Policy — AI Systems |
| AIMS-INV-001 | AI System Inventory |
| AIMS-ROLES-001 | AIMS Roles and Responsibilities Register |
| AIMS-SOA-001 | Statement of Applicability |
| AIMS-RISK-001 | AI Risk Assessment Template |
| AIMS-RTP-001 | Risk Treatment Plan |
| AIMS-AISIA-001 | AI System Impact Assessment Template |
| AIMS-SUP-001 | AI Supplier Assessment Template |
| AIMS-INC-001 | AI Incident Reporting Procedure |
| AIMS-MR-001 | Management Review Procedure |
| AIMS-CAR-001 | Corrective Action Procedure |
| AIMS-AUDIT-001 | Internal Audit Procedure |

---

## 15. Version History

| Version | Date | Author | Summary of Changes | Approved By |
|---|---|---|---|---|
| 1.0 | [YYYY-MM-DD] | [Name] | Initial version | [Name, Role] |
| | | | | |

---

*[Organization Name] AI Management System | AIMS-POL-001 | Version 1.0*
*This document is subject to version control. Printed copies are uncontrolled. Refer to the document management system for the current version.*
