# AI System Inventory

> **Current as of:** March 2026 | ISO/IEC 42001:2023 | EU AI Act (Regulation 2024/1689)

---

## Document Metadata

| Field | Value |
|---|---|
| **Document ID** | AIMS-INV-001 |
| **Version** | 1.0 |
| **Date** | [YYYY-MM-DD] |
| **Organization** | [Organization Name] |
| **AIMS Scope Reference** | [Reference to AIMS scope document, e.g., AIMS-SCOPE-001] |
| **Prepared By** | [Name, Role] |
| **Approved By** | [Name, Role] |
| **Next Review Date** | [YYYY-MM-DD — no later than 90 days from Date] |

---

## Purpose

This inventory documents all AI systems within the organization's AI Management System (AIMS) scope, as required by ISO/IEC 42001:2023. It serves as the **foundational record** for the entire AIMS — risk assessments, impact assessments, the Statement of Applicability (SoA), and audit evidence all trace back to this document.

An incomplete inventory is the most common audit failure point. Many organizations are unaware that their existing SaaS platforms contain embedded AI features that fall within scope. This inventory addresses that gap through systematic discovery and registration of all AI systems, including those embedded in tools already in use.

---

## How to Complete This Inventory

### Who Should Complete This

This inventory requires input from multiple roles:

- **IT Lead / IT Manager** — Coordinates the inventory process, provides technical details on integrations and data flows, and identifies API-connected AI systems.
- **Department Heads** — Identify AI tools used within their teams, including tools adopted without formal IT approval (shadow AI). Each department head should review the Embedded AI Discovery Checklist (Section 3) for platforms their teams use daily.
- **ISO 42001 Consultant** — Guides completeness, validates risk classifications, and ensures alignment with AIMS scope and Annex A control requirements.
- **AI System Owner(s)** — Provide operational details for systems already identified. If no owner is assigned, this inventory process is where ownership gets established.

### When to Update

| Trigger | Action |
|---|---|
| **Quarterly review** (minimum) | Review entire inventory for accuracy; confirm status of all entries |
| **New AI tool adoption** | Add entry before deployment; do not deploy AI tools without an inventory record |
| **Vendor change or migration** | Update existing entry or create new entry; update risk classification if data flows change |
| **Significant feature update** | Review entry when a vendor adds AI capabilities to an existing tool (e.g., a CRM vendor enables AI-powered lead scoring) |
| **Organizational change** | Review inventory when departments restructure, merge, or change business processes |
| **Incident or near-miss** | Review and update the affected system's entry; reassess risk level |
| **Pre-audit preparation** | Full inventory review as part of internal audit or Stage 1/Stage 2 preparation |

### Completeness Standard

**If it uses AI or machine learning to process, classify, generate, recommend, predict, or automate — it belongs in this inventory.**

This includes:
- Standalone AI applications the organization subscribes to (e.g., ChatGPT Enterprise)
- AI features embedded in existing SaaS platforms (e.g., Microsoft 365 Copilot, Salesforce Einstein)
- API integrations that call AI/ML services (e.g., OpenAI API, Google Cloud AI)
- Custom automations built on AI/ML capabilities (e.g., Zapier workflows using AI steps, Power Automate with AI Builder)

This excludes:
- Rule-based automations using only deterministic if/then logic (no ML component)
- Traditional search and filter functions that do not use ML ranking
- Standard analytics dashboards using only statistical aggregation (no predictive modeling)

When in doubt, include the system and flag it for review. It is easier to remove a system from scope than to explain to an auditor why a system was omitted.

> **Legal Disclaimer:** This template does not constitute legal advice. Organizations should consult qualified legal counsel for questions about regulatory obligations, including EU AI Act classification and compliance requirements.

---

## Section 1: Inventory Instructions Summary

### Step-by-Step Process

1. **Gather your team.** Assemble the IT lead, department heads, and consultant. Schedule a dedicated session (allow 2–4 hours for initial inventory).

2. **Start with known AI tools.** List every AI application the organization has consciously adopted. Check procurement records, software license lists, and expense reports for AI-related subscriptions.

3. **Run the Embedded AI Discovery Checklist.** Work through Section 3 systematically. This is where most organizations find AI systems they didn't know they had.

4. **Complete the AI System Register.** For each system identified, fill in every column of the register in Section 2. Leave no column blank — if information is unknown, mark it "[To Be Confirmed]" and assign an owner to resolve.

5. **Classify risk levels.** Use the criteria in Section 4 to assign High / Medium / Low risk to each system.

6. **Assign ownership.** Every system must have a named owner. If a system has no clear owner, escalate to management for assignment.

7. **Review and approve.** The completed inventory should be reviewed by the AIMS lead and approved by management before it becomes an active AIMS record.

8. **Schedule the next review.** Set the next review date (no more than 90 days out) and add it to the organization's calendar.

---

## Section 2: AI System Register

### Category Values

| Category | Definition |
|---|---|
| **Standalone AI Tool** | A dedicated AI application the organization subscribes to or licenses specifically for its AI capabilities |
| **Embedded AI Feature** | AI functionality built into a broader SaaS platform the organization already uses; may be auto-enabled |
| **API Integration** | An AI/ML service accessed programmatically via API, typically integrated into internal workflows or applications |
| **Custom Automation** | An internally built automation that incorporates AI/ML steps (e.g., a workflow using AI Builder, a script calling an LLM API) |

### Status Values

| Status | Definition |
|---|---|
| **Active** | Approved and currently in use within the organization |
| **Under Review** | Being evaluated for adoption, risk assessment in progress, or under periodic review |
| **Decommissioning** | Approved for removal; transition plan in progress |
| **Approved** | Approved for use but not yet deployed |
| **Unapproved (Shadow AI)** | In use without formal organizational approval; requires immediate review |

### AI System Register Table

| ID | System Name | Vendor | Category | Description | Department(s) | Data Input Types | Data Output Types | Risk Level | Users | Date Added | Status | Owner |
|---|---|---|---|---|---|---|---|---|---|---|---|---|
| AI-001 | ChatGPT Enterprise | OpenAI | Standalone AI Tool | Content generation, research assistance, data analysis, document drafting | Marketing, Legal, Operations | Text prompts, business documents, internal data (per acceptable use policy) | Generated text, summaries, analysis, code | Medium | 35 | 2025-06-15 | Active | J. Martinez, Head of Operations |
| AI-002 | Microsoft 365 Copilot | Microsoft | Embedded AI Feature | Document drafting, email summarization, presentation creation, Excel data analysis, Teams meeting summaries | All departments | Emails, documents, spreadsheets, meeting transcripts, calendar data | Drafted content, summaries, data insights, suggested actions | Medium | 120 | 2025-09-01 | Active | R. Chen, IT Director |
| AI-003 | Salesforce Einstein | Salesforce | Embedded AI Feature | Lead scoring, opportunity insights, sales forecasting, next-best-action recommendations | Sales, Customer Success | CRM records, customer interactions, deal history, email engagement data | Lead scores, win probability, revenue forecasts, recommended actions | High | 28 | 2025-03-10 | Active | T. Okonkwo, VP Sales |
| AI-004 | HubSpot AI | HubSpot | Embedded AI Feature | Email send-time optimization, subject line suggestions, content assistant, predictive lead scoring | Marketing, Sales | Contact records, email engagement metrics, website behavior, content performance | Optimized send times, content suggestions, lead scores, campaign recommendations | Medium | 22 | 2025-07-20 | Active | L. Patel, Marketing Director |
| AI-005 | Zoom AI Companion | Zoom | Embedded AI Feature | Meeting summaries, smart chapters, action item extraction, in-meeting question suggestions | All departments | Meeting audio and video, chat messages, screen-shared content | Meeting summaries, action items, chapter markers, follow-up suggestions | Medium | 95 | 2025-11-01 | Active | R. Chen, IT Director |
| AI-006 | Google Workspace Gemini | Google | Embedded AI Feature | Email drafting in Gmail, document creation in Docs, data analysis in Sheets, presentation generation in Slides | Finance, HR | Emails, documents, spreadsheets, internal data | Drafted content, data analysis, generated presentations, suggested responses | Medium | 45 | 2026-01-15 | Active | R. Chen, IT Director |
| AI-007 | Slack AI | Slack (Salesforce) | Embedded AI Feature | Channel summaries, intelligent search across message history, thread recaps, conversation highlights | All departments | Slack messages, shared files, channel history | Conversation summaries, search results, thread recaps, key highlights | Low | 110 | 2025-10-05 | Active | R. Chen, IT Director |
| AI-008 | Grammarly Business | Grammarly | Standalone AI Tool | Writing assistance, tone detection, clarity suggestions, plagiarism detection, brand tone enforcement | Marketing, Legal, Customer Support | Text input from documents, emails, browser-based writing | Writing suggestions, tone analysis, clarity scores, plagiarism reports | Low | 50 | 2024-11-20 | Active | L. Patel, Marketing Director |
| AI-009 | GitHub Copilot | GitHub (Microsoft) | Standalone AI Tool | Code suggestions, code completion, code review assistance, pull request summaries | Engineering | Source code, code comments, pull request content | Code suggestions, auto-completions, review comments, PR summaries | Medium | 12 | 2025-08-01 | Active | S. Nakamura, Engineering Lead |
| AI-010 | Internal Sentiment Analysis | OpenAI API (via Zapier) | API Integration | Automated analysis of customer support ticket sentiment; routes high-negativity tickets to senior staff | Customer Support | Customer support ticket text, customer metadata | Sentiment scores, priority flags, routing recommendations | High | 8 | 2025-12-01 | Active | A. Fernandez, Support Manager |
| AI-011 | [System Name] | [Vendor] | [Category] | [Description] | [Department(s)] | [Data Input Types] | [Data Output Types] | [Risk Level] | [#] | [YYYY-MM-DD] | [Status] | [Owner Name, Title] |
| AI-012 | [System Name] | [Vendor] | [Category] | [Description] | [Department(s)] | [Data Input Types] | [Data Output Types] | [Risk Level] | [#] | [YYYY-MM-DD] | [Status] | [Owner Name, Title] |

*Add rows as needed. Every AI system in scope must have an entry. The ID format (AI-NNN) should be sequential and never reused, even if a system is decommissioned.*

---

## Section 3: Embedded AI Discovery Checklist

Most organizations undercount their AI systems because they overlook AI features embedded in platforms they already use. Many SaaS vendors have added AI capabilities in the past 12–24 months, sometimes enabling them by default.

Work through each SaaS category below. For every platform your organization uses, complete the discovery steps.

### Productivity Suites

**Platforms to check:** Microsoft 365, Google Workspace, Apple Intelligence (iWork)

| Platform | Discovery Step | Completed | Findings |
|---|---|---|---|
| [Platform Name] | Check vendor's AI/ML feature page for current AI capabilities | [ ] | |
| [Platform Name] | Review release notes from past 12 months for AI feature additions | [ ] | |
| [Platform Name] | Check if AI features are auto-enabled or opt-in | [ ] | |
| [Platform Name] | Document data that flows to AI features | [ ] | |
| [Platform Name] | Confirm data processing location (on-premise, cloud region) | [ ] | |

### CRM Platforms

**Platforms to check:** Salesforce (Einstein), HubSpot, Zoho (Zia), Pipedrive, Dynamics 365

| Platform | Discovery Step | Completed | Findings |
|---|---|---|---|
| [Platform Name] | Check vendor's AI/ML feature page for current AI capabilities | [ ] | |
| [Platform Name] | Review release notes from past 12 months for AI feature additions | [ ] | |
| [Platform Name] | Check if AI features are auto-enabled or opt-in | [ ] | |
| [Platform Name] | Document data that flows to AI features | [ ] | |
| [Platform Name] | Confirm data processing location (on-premise, cloud region) | [ ] | |

### Communication Tools

**Platforms to check:** Slack, Microsoft Teams, Zoom, Google Meet, Webex

| Platform | Discovery Step | Completed | Findings |
|---|---|---|---|
| [Platform Name] | Check vendor's AI/ML feature page for current AI capabilities | [ ] | |
| [Platform Name] | Review release notes from past 12 months for AI feature additions | [ ] | |
| [Platform Name] | Check if AI features are auto-enabled or opt-in | [ ] | |
| [Platform Name] | Document data that flows to AI features | [ ] | |
| [Platform Name] | Confirm data processing location (on-premise, cloud region) | [ ] | |

### HR Platforms

**Platforms to check:** Workday, BambooHR, ADP, Rippling, Gusto, HiBob

| Platform | Discovery Step | Completed | Findings |
|---|---|---|---|
| [Platform Name] | Check vendor's AI/ML feature page for current AI capabilities | [ ] | |
| [Platform Name] | Review release notes from past 12 months for AI feature additions | [ ] | |
| [Platform Name] | Check if AI features are auto-enabled or opt-in | [ ] | |
| [Platform Name] | Document data that flows to AI features | [ ] | |
| [Platform Name] | Confirm data processing location (on-premise, cloud region) | [ ] | |

### Finance and Accounting

**Platforms to check:** QuickBooks, Xero, NetSuite, Sage, FreshBooks

| Platform | Discovery Step | Completed | Findings |
|---|---|---|---|
| [Platform Name] | Check vendor's AI/ML feature page for current AI capabilities | [ ] | |
| [Platform Name] | Review release notes from past 12 months for AI feature additions | [ ] | |
| [Platform Name] | Check if AI features are auto-enabled or opt-in | [ ] | |
| [Platform Name] | Document data that flows to AI features | [ ] | |
| [Platform Name] | Confirm data processing location (on-premise, cloud region) | [ ] | |

### Marketing Platforms

**Platforms to check:** Mailchimp, Marketo, HubSpot Marketing Hub, ActiveCampaign, Constant Contact

| Platform | Discovery Step | Completed | Findings |
|---|---|---|---|
| [Platform Name] | Check vendor's AI/ML feature page for current AI capabilities | [ ] | |
| [Platform Name] | Review release notes from past 12 months for AI feature additions | [ ] | |
| [Platform Name] | Check if AI features are auto-enabled or opt-in | [ ] | |
| [Platform Name] | Document data that flows to AI features | [ ] | |
| [Platform Name] | Confirm data processing location (on-premise, cloud region) | [ ] | |

### Project Management

**Platforms to check:** Asana, Monday.com, Jira, ClickUp, Notion, Linear

| Platform | Discovery Step | Completed | Findings |
|---|---|---|---|
| [Platform Name] | Check vendor's AI/ML feature page for current AI capabilities | [ ] | |
| [Platform Name] | Review release notes from past 12 months for AI feature additions | [ ] | |
| [Platform Name] | Check if AI features are auto-enabled or opt-in | [ ] | |
| [Platform Name] | Document data that flows to AI features | [ ] | |
| [Platform Name] | Confirm data processing location (on-premise, cloud region) | [ ] | |

### Customer Support

**Platforms to check:** Zendesk, Intercom, Freshdesk, ServiceNow, Help Scout

| Platform | Discovery Step | Completed | Findings |
|---|---|---|---|
| [Platform Name] | Check vendor's AI/ML feature page for current AI capabilities | [ ] | |
| [Platform Name] | Review release notes from past 12 months for AI feature additions | [ ] | |
| [Platform Name] | Check if AI features are auto-enabled or opt-in | [ ] | |
| [Platform Name] | Document data that flows to AI features | [ ] | |
| [Platform Name] | Confirm data processing location (on-premise, cloud region) | [ ] | |

### Discovery Summary

| SaaS Category | Platforms Reviewed | AI Features Found | New Inventory Entries Created |
|---|---|---|---|
| Productivity Suites | | | |
| CRM Platforms | | | |
| Communication Tools | | | |
| HR Platforms | | | |
| Finance and Accounting | | | |
| Marketing Platforms | | | |
| Project Management | | | |
| Customer Support | | | |
| **Total** | | | |

---

## Section 4: Risk Classification Criteria

Use these criteria to assign a risk level to each AI system in the register. When a system meets criteria across multiple levels, assign the **highest applicable level**.

### High Risk

An AI system is classified as **High Risk** when any of the following apply:

- The system makes or directly influences decisions affecting individuals' rights, employment, credit, safety, or legal status
- The system processes sensitive personal data (health, biometric, financial, protected characteristics) as AI inputs
- The system operates autonomously without meaningful human review before its outputs take effect
- The system's outputs directly trigger automated actions with material consequences (e.g., auto-rejecting applications, auto-routing emergency requests)
- Failure or malfunction of the system could cause significant financial, reputational, or legal harm to the organization or affected individuals

**Examples from the register:** AI-003 (Salesforce Einstein — lead scoring directly influences sales resource allocation and customer treatment), AI-010 (Sentiment Analysis — auto-routes tickets affecting customer service quality)

### Medium Risk

An AI system is classified as **Medium Risk** when:

- The system affects business operations or produces outputs that inform business decisions
- A human reviews and approves outputs before they take effect, but the AI significantly shapes the decision
- The system processes internal business data, non-sensitive customer data, or employee work product
- Errors in the system's outputs could lead to moderate business impact (wasted effort, incorrect reporting, suboptimal decisions) but are catchable before causing harm

**Examples from the register:** AI-001 (ChatGPT Enterprise — generates content reviewed by staff), AI-002 (Microsoft 365 Copilot — drafts reviewed before sending), AI-009 (GitHub Copilot — code suggestions reviewed before merging)

### Low Risk

An AI system is classified as **Low Risk** when:

- The system is used for convenience or productivity enhancement only
- The system processes only publicly available or non-sensitive data as AI inputs
- All outputs are purely advisory, with full human control over whether and how to use them
- The system has no direct or indirect effect on decisions about individuals
- Failure of the system would cause minimal operational disruption

**Examples from the register:** AI-007 (Slack AI — summarizes internal messages for convenience), AI-008 (Grammarly Business — writing suggestions with full user control)

### Risk Classification Decision Tree

```
Does the system make or influence decisions about individuals' rights,
employment, credit, safety, or legal status?
  ├── YES → HIGH RISK
  └── NO ↓

Does the system process sensitive personal data as AI inputs?
  ├── YES → HIGH RISK
  └── NO ↓

Does the system operate autonomously without human review before
outputs take effect?
  ├── YES → HIGH RISK
  └── NO ↓

Does the system affect business operations or inform business decisions?
  ├── YES → MEDIUM RISK
  └── NO ↓

Is the system used only for convenience/productivity with full human control?
  ├── YES → LOW RISK
  └── NO → Default to MEDIUM RISK and investigate further
```

---

## Section 5: Annex A Control Mapping

This inventory directly supports the following ISO/IEC 42001:2023 Annex A controls. The mapping below shows how specific columns and sections of this inventory provide evidence for each control.

| Annex A Control | Control Title | How This Inventory Addresses It |
|---|---|---|
| **A.6.2.4** | Verification and Validation of AI System | The register documents each AI system's intended purpose and current status, providing the foundation for validating that third-party AI tools meet organizational requirements. The risk classification (Section 4) ensures validation rigor is proportionate to risk. |
| **A.6.2.5** | Deployment of AI System | The **Date Added** and **Status** columns track deployment status. Systems transition through Under Review → Approved → Active, creating an audit trail of controlled deployment. |
| **A.6.2.6** | Operation and Monitoring of AI System | The **Status** and **Owner** columns establish ongoing monitoring responsibility. Active systems require periodic review per the update schedule. The register's quarterly review cycle provides structured monitoring checkpoints. |
| **A.6.2.9** | AI System Documentation | The register itself serves as a core AI system documentation record. Each entry's **Description**, **Data Input Types**, **Data Output Types**, and **Risk Level** columns fulfill the documentation requirement for each in-scope system. |
| **A.7.2** | Data for Development and Enhancement of AI System | The **Data Input Types** and **Data Output Types** columns document what data each AI system processes. For systems where the organization provides data for fine-tuning or customization (partially applicable), these columns capture that data flow. |
| **A.7.3** | Data Quality for ML and Data for AI System | The **Data Input Types** column identifies the data flowing into each AI system, enabling the organization to assess and manage input data quality per system. |
| **A.7.5** | Data Acquisition and Collection | The Embedded AI Discovery Checklist (Section 3) includes data flow documentation for each platform, supporting the organization's understanding of how data is acquired and fed to AI features. |
| **A.9.2** | Objectives for Responsible Use of AI System | The **Description** column documents each system's intended use, and the **Risk Level** classification connects to the organization's responsible use objectives. |
| **A.9.3** | Intended Use of AI System | The **Description** column explicitly states the intended use for each AI system. Combined with the **Category** column, this documents the boundaries of approved use. |
| **A.9.4** | Processes for Responsible Use of AI System | The **Risk Level** classification drives the level of process controls required for each system. The **Status** column (especially the Unapproved/Shadow AI status) supports processes for identifying and formalizing unauthorized AI use. |
| **A.10.2** | Suppliers of AI System Components | The **Vendor** column identifies all AI suppliers. The register serves as the starting point for vendor assessment and ongoing supplier monitoring activities. |

---

## Section 6: EU AI Act Deployer Relevance

This inventory also supports compliance with EU AI Act (Regulation 2024/1689) deployer obligations under **Article 26**. Organizations that deploy AI systems within the EU or that affect EU residents should note the following.

### How This Inventory Supports EU AI Act Obligations

| EU AI Act Deployer Obligation | How This Inventory Helps |
|---|---|
| **Maintain awareness of AI systems in use and their purpose** | The AI System Register (Section 2) documents every AI system, its vendor, description, and intended use |
| **Risk classification** | Section 4 provides risk classification criteria that can be mapped to EU AI Act risk categories (Unacceptable, High-Risk, Limited Risk, Minimal Risk) |
| **Human oversight measures** | The **Owner** column and risk classification drive the organization's human oversight posture; high-risk systems require documented human-in-the-loop controls |
| **Data handling practices** | **Data Input Types** and **Data Output Types** columns document data flows for each AI system |
| **Record-keeping and documentation** | The inventory itself, with its version history and update schedule, serves as a deployer documentation record |

### Important Limitations

The risk classification criteria in Section 4 are designed for ISO 42001 AIMS purposes and **do not constitute an EU AI Act risk classification**. The EU AI Act defines its own risk categories with specific legal criteria, including a list of prohibited practices (Article 5) and high-risk system categories (Article 6, Annex III).

Organizations subject to the EU AI Act should conduct a separate regulatory classification for each AI system in this inventory, informed by qualified legal counsel.

> While ISO 42001 certification covers significant ground for EU AI Act compliance, additional deployer obligations exist. See cross-framework mapping (06-cross-framework/cross-framework-mapping.md) for details.

---

## Section 7: Version History

| Version | Date | Author | Changes |
|---|---|---|---|
| 1.0 | [YYYY-MM-DD] | [Name] | Initial inventory created |
| | | | |
| | | | |
| | | | |

---

*ISO 42001 Readiness Service Toolkit | 01-Discovery | Client Template*
