# Controlled Vocabulary and Key Definitions

> **Current as of:** March 2026 | ISO/IEC 42001:2023 | EU AI Act (Regulation 2024/1689) | NIST AI RMF 1.0

---

## Purpose

This document is the single source of truth for terminology across all toolkit documents. When a term appears in a procedure, template, or client deliverable, its meaning is governed by the definition here.

Consistent vocabulary matters in ISO 42001 engagements for two reasons. First, auditors look for alignment between what a management system says it does and what its documentation actually describes. Inconsistent terminology creates ambiguity that auditors flag. Second, clients often arrive with their own informal language for AI tools and processes. Anchoring the engagement to standard definitions early prevents confusion later.

Use this glossary when onboarding a new client, drafting AIMS documentation, or reviewing client-produced documents for terminology consistency.

---

## Management System Terms

### Context of the Organization

**Definition:** The combination of internal and external factors that can affect an organization's approach to establishing, implementing, maintaining, and continually improving its AI management system. Internal factors include culture, governance structures, and existing capabilities. External factors include regulatory requirements, market conditions, and relationships with interested parties.

**Source:** ISO/IEC 42001:2023, Clause 4.1

**Why it matters:** Understanding context is the foundation of a well-scoped AIMS. Clients who skip this step tend to build management systems that look complete on paper but don't reflect how the organization actually operates. During discovery, this is where you start.

---

### Continual Improvement

**Definition:** The recurring activity of enhancing performance. In an AIMS context, this means systematically identifying opportunities to improve AI governance, risk controls, and operational practices over time, not just at certification.

**Source:** ISO/IEC 42001:2023, Clause 10.2

**Why it matters:** Auditors want to see evidence that improvement is ongoing, not a one-time event before the audit. Help clients build lightweight mechanisms (management review outputs, corrective action tracking) that generate this evidence naturally.

---

### Documented Information

**Definition:** Information that an organization is required to control and maintain, and the medium on which it is contained. This includes both documents (policies, procedures) and records (evidence that activities were performed).

**Source:** ISO/IEC 42001:2023, Clause 7.5

**Why it matters:** ISO 42001 specifies which documented information is required. Clients often have informal practices that satisfy the intent of a requirement but lack the documentation to prove it. Part of remediation is formalizing what already exists, not necessarily creating everything from scratch.

---

### Interested Parties

**Definition:** Persons or organizations that can affect, be affected by, or perceive themselves to be affected by the organization's AI-related decisions and activities. Examples include employees, customers, regulators, suppliers, and the communities where AI systems have impact.

**Source:** ISO/IEC 42001:2023, Clause 4.2

**Why it matters:** For SMB AI users, the most commonly overlooked interested parties are the employees whose work is affected by AI tools and the customers whose data those tools process. Identifying these groups early shapes the scope and the risk assessment.

---

### Internal Audit

**Definition:** A systematic, independent, and documented process for obtaining audit evidence and evaluating it objectively to determine the extent to which audit criteria are fulfilled. Internal audits are conducted by or on behalf of the organization itself, not by the certification body.

**Source:** ISO/IEC 42001:2023, Clause 9.2

**Why it matters:** Many SMB clients have never run a formal internal audit. Part of Phase 3 remediation is helping them establish a simple, repeatable internal audit process so they can maintain their AIMS after certification without ongoing consultant support.

---

### Management Review

**Definition:** A periodic evaluation by top management of the organization's AI management system to ensure its continuing suitability, adequacy, effectiveness, and alignment with the organization's strategic direction.

**Source:** ISO/IEC 42001:2023, Clause 9.3

**Why it matters:** Management review is a required AIMS activity and a common audit focus point. Clients need a documented agenda, inputs (audit results, nonconformities, performance data), and recorded outputs (decisions and actions). A one-page meeting record is usually sufficient for SMBs.

---

### Scope

**Definition:** The boundaries and applicability of the AI management system, including the organizational units, locations, AI systems, and activities covered. The scope must be documented and available to interested parties.

**Source:** ISO/IEC 42001:2023, Clause 4.3

**Why it matters:** Scope definition is one of the most consequential decisions in Phase 1. A scope that's too broad creates unnecessary compliance burden. A scope that's too narrow may exclude AI systems that carry real risk. The scope document becomes a reference point for every subsequent phase.

---

### Statement of Applicability (SoA)

**Definition:** A documented statement describing the controls from ISO 42001 Annex A that are applicable to the organization, along with justification for their inclusion or exclusion. The SoA is a required AIMS document.

**Source:** ISO/IEC 42001:2023, Clause 6.1.6

**Why it matters:** The SoA is one of the first documents a certification auditor will request. It demonstrates that the organization has thought through which controls apply to its specific context and why. For AI user organizations, many development-focused controls will be excluded, and the SoA is where that exclusion is formally justified.

---

## AI-Specific Terms

### AI Developer

**Definition:** An entity that designs, creates, or builds an AI system. The developer is responsible for the technical architecture, training methodology, and core capabilities of the system.

**Source:** ISO/IEC 22989:2022

**Why it matters:** Most SMB clients are not AI developers. Clarifying this distinction early prevents scope creep and helps clients understand which ISO 42001 controls are relevant to their role. When a client says "we built a chatbot," probe whether they trained a model or configured a vendor-provided tool.

---

### AI Management System (AIMS)

**Definition:** A management system that provides a framework for organizations to develop, implement, maintain, and continually improve the responsible development and use of AI. An AIMS addresses governance, risk management, and operational controls for AI activities within the organization's defined scope.

**Source:** ISO/IEC 42001:2023

**Why it matters:** The AIMS is what the client is building. It's not a software platform or a single policy document. It's a system of interconnected policies, procedures, roles, records, and review activities. Helping clients understand this distinction early prevents them from treating certification as a documentation exercise rather than a governance commitment.

---

### AI Provider

**Definition:** An entity that makes an AI system available for use by others, typically through a product or service offering. The provider may or may not be the same entity as the developer.

**Source:** ISO/IEC 22989:2022

**Why it matters:** For SMB AI user clients, their AI providers (Microsoft, Salesforce, OpenAI, etc.) are key interested parties and supply chain considerations. ISO 42001 requires organizations to address risks from third-party AI providers. Understanding the provider relationship is essential for the AI inventory and risk assessment.

---

### AI System

**Definition:** An engineered system that generates outputs such as predictions, recommendations, decisions, or content that influence real or virtual environments. AI systems are designed to operate with varying levels of autonomy.

**Source:** ISO/IEC 22989:2022; ISO/IEC 42001:2023

**Why it matters:** Not every software tool is an AI system. The distinction matters for scoping. A rule-based automation (if/then logic) is generally not an AI system. A tool that uses machine learning, natural language processing, or generative models typically is. During discovery, use this definition to help clients accurately inventory what falls within scope.

---

### AI Tool

**Definition (working definition for this toolkit):** A specific software application or feature that incorporates AI system capabilities and is used by the organization to perform business tasks. Examples include ChatGPT, Microsoft Copilot, Salesforce Einstein, and similar vendor-provided products. An AI tool is the practical, user-facing manifestation of an AI system.

**Source:** Working definition; not a formal ISO term

**Why it matters:** Clients think in terms of tools, not systems. Using "AI tool" in client conversations and then mapping those tools to the formal "AI system" definition in documentation bridges the gap between how clients talk about their technology and how the standard describes it.

---

### AI User

**Definition:** An entity that uses an AI system for its intended purpose. The AI user operates the system but did not necessarily develop or train it.

**Source:** ISO/IEC 22989:2022

**Why it matters:** This is the role that defines the client population this toolkit serves. AI users have a different set of ISO 42001 obligations than AI developers or providers. Many Annex A controls are scoped to development activities and will be excluded from the SoA for AI user organizations. Establishing this role clearly in Phase 1 shapes the entire engagement.

---

### Responsible AI

**Definition (working definition for this toolkit):** An approach to AI development and use that prioritizes fairness (avoiding discriminatory outcomes), transparency (explainability of AI decisions), accountability (clear ownership of AI-related decisions and their consequences), and safety (preventing harm to individuals and society). Responsible AI is the practical expression of the values that ISO 42001 is designed to operationalize.

**Source:** Working definition; aligned with ISO/IEC 42001:2023 principles and EU AI Act objectives

**Why it matters:** Clients often encounter "responsible AI" as marketing language. Grounding it in these four concrete dimensions gives the term operational meaning and connects it to specific AIMS controls. Use this definition when explaining to clients why certain policies and procedures exist.

---

### Third-Party AI

**Definition (working definition for this toolkit):** An AI system developed, trained, and maintained by an external vendor and accessed by the organization through a commercial product, API, or service subscription. The organization did not build the underlying model and has limited visibility into its technical internals.

**Source:** Working definition; not a formal ISO term

**Why it matters:** Third-party AI is the dominant AI use pattern for SMB clients. It creates specific governance challenges: the organization is responsible for how it uses the system but cannot control the model itself. ISO 42001 requires organizations to address these supply chain risks through vendor assessment, contractual controls, and usage policies.

---

## Risk and Compliance Terms

### Corrective Action

**Definition:** Action taken to eliminate the cause of a nonconformity and prevent its recurrence. Corrective action goes beyond fixing the immediate problem; it addresses the root cause so the same failure doesn't happen again.

**Source:** ISO/IEC 42001:2023, Clause 10.1

**Why it matters:** Auditors distinguish between correction (fixing the symptom) and corrective action (fixing the cause). When a nonconformity is raised during audit, the client needs to demonstrate both. Help clients build a simple corrective action process during Phase 3 so they're not improvising during Stage 2.

---

### Impact Assessment

**Definition:** A structured evaluation of the potential effects of an AI system on individuals, groups, or society. ISO 42001 requires organizations to assess AI system impacts as part of risk management, considering both intended and unintended consequences.

**Source:** ISO/IEC 42001:2023, Clause 6.1.4

**Why it matters:** Impact assessment is one of the more substantive requirements for AI user organizations. It's not the same as a general risk assessment. It specifically asks: what could this AI system do to people? For SMB clients using tools like AI-driven hiring software or customer scoring models, this assessment can surface significant risks that weren't previously visible.

---

### Nonconformity

**Definition:** Non-fulfillment of a requirement. In an AIMS context, a nonconformity occurs when the organization fails to meet a requirement of ISO 42001, its own documented policies or procedures, or other applicable requirements it has committed to.

**Source:** ISO/IEC 42001:2023, Clause 10.1

**Why it matters:** Nonconformities raised during certification audit are not automatically fatal to certification. Minor nonconformities can be closed with a corrective action plan. Major nonconformities require resolution before certification is granted. Help clients understand this distinction so audit findings don't create unnecessary alarm.

---

### Risk Treatment

**Definition:** The process of selecting and implementing options to address identified risks. Treatment options include avoiding the risk, accepting it, transferring it (e.g., through contractual terms with a vendor), or mitigating it through controls.

**Source:** ISO/IEC 42001:2023, Clause 6.1.3

**Why it matters:** For AI user organizations, risk treatment often involves a combination of vendor contractual controls, internal usage policies, and monitoring procedures. The risk treatment plan feeds directly into the SoA, since the controls selected to treat risks determine which Annex A controls are applicable.

---

## Terms Your Clients May Encounter

The following terms relate to AI development and model training. They are **not applicable to AI user organizations** as operational concepts and are **not part of the AIMS scope** for the clients this toolkit serves. They are included here for reference awareness only, so consultants can recognize and contextualize these terms when clients encounter them in vendor documentation, media coverage, or regulatory guidance.

| Term | Brief Explanation |
|---|---|
| **Dataset curation** | The process of selecting, cleaning, and preparing data used to train an AI model. Relevant to AI developers, not AI users. |
| **Fine-tuning** | Adapting a pre-trained AI model to a specific task or domain by training it further on a smaller, targeted dataset. Some vendors offer fine-tuning as a service; if a client uses this capability, it may affect their AIMS scope. |
| **Hyperparameter** | A configuration setting that controls how an AI model is trained (e.g., learning rate, number of layers). Set by developers before training begins. Not relevant to AI users. |
| **Model training** | The process by which an AI system learns patterns from data. Conducted by AI developers. AI users consume the outputs of trained models but do not conduct training themselves. |

If a client is considering using a vendor's fine-tuning capability or building a custom model on top of a foundation model, flag this for scope review. It may shift their role from pure AI user toward AI developer for that specific system, with corresponding changes to applicable AIMS controls.

---

## Abbreviations

| Abbreviation | Full Term |
|---|---|
| **AI RMF** | AI Risk Management Framework (NIST) |
| **AIMS** | AI Management System |
| **ISMS** | Information Security Management System |
| **NCAR** | Nonconformity and Corrective Action Report |
| **PDCA** | Plan-Do-Check-Act (continual improvement cycle) |
| **RTP** | Risk Treatment Plan |
| **SoA** | Statement of Applicability |

---

*ISO 42001 Readiness Service Toolkit | 00-Foundation | Internal Use*
