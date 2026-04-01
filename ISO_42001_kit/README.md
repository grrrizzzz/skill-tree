# ISO 42001 Readiness Service Toolkit

> A complete consulting toolkit for ISO/IEC 42001:2023 AI Management System readiness engagements — from initial scoping through certification.

> **Current as of:** March 2026 | ISO/IEC 42001:2023 | EU AI Act (Regulation 2024/1689)

---

## Who This Toolkit Is For

This toolkit is built for ISO 42001 consultants serving small and mid-sized businesses that **use** third-party AI systems. The clients here are AI users, not AI builders. They deploy tools like ChatGPT, Microsoft Copilot, Salesforce Einstein, or similar vendor-provided systems, and they need a structured management framework to govern how those systems are selected, deployed, monitored, and controlled.

If your client is building or training AI models, some templates will need adaptation. For the typical SMB AI-user engagement, this toolkit covers everything from initial scoping through certification audit support.

---

## Toolkit Structure

| Phase | Directory | Purpose | Key Deliverables |
|-------|-----------|---------|-----------------|
| Phase 0: Foundation | `00-foundation/` | Reference materials for the whole engagement | Annex A reference, glossary, traceability matrix, cross-framework mapping |
| Phase 1: Discovery & Scoping | `01-discovery/` | Understand the client's AI landscape and define scope | AI System Inventory, Stakeholder Register, AIMS Scope Statement |
| Phase 2: Gap Analysis | `02-gap-analysis/` | Assess current state against ISO 42001 requirements | Gap Analysis Workbook, Gap Analysis Report |
| Phase 3: Remediation | `03-remediation/` | Build the AIMS documentation set | AI Policy, AUP, Risk Register, Impact Assessments, SoA, Risk Treatment Plan, Supplier Assessments, Training Records, NCAR Log, Implementation Roadmap |
| Phase 4: Pre-Audit | `04-pre-audit/` | Stress-test the AIMS before the certification body arrives | Internal Audit Checklist, Management Review, Pre-Audit Readiness Checklist |
| Phase 5: Certification | `05-certification/` | Support Stage 1 and Stage 2 certification audits | Certification Audit Support Procedure |
| Business Development | `07-business/` | Win and manage engagements | Engagement Proposal, Statement of Work |

---

## Document Types

Every file in this toolkit is one of two types. The distinction matters.

**Internal Procedures** (`procedure-*.md`) are written for the consultant. They describe what to do, in what order, and what to watch for at each phase. These documents are **not for client distribution**. They contain firm methodology, pricing context, and guidance that should stay internal.

**Client Templates** (`template-*.md`) are deliverables. They get completed during the engagement and become part of the client's AIMS documentation set. Each template contains `HOW TO CUSTOMIZE` blocks with instructions for tailoring the document to the specific client. **Remove all HOW TO CUSTOMIZE blocks before delivering any template to a client.**

---

## Complete File Index

### `00-foundation/` — Foundational Reference

| File | Type | Description |
|------|------|-------------|
| `README.md` | Reference | Overview of the toolkit, document types, and engagement flow |
| `glossary.md` | Reference | Controlled vocabulary for all toolkit documents. Single source of truth for key terms. |
| `annex-a-reference.md` | Reference | Full Annex A control reference (A.2–A.10) with implementation guidance |
| `traceability-matrix.md` | Reference | Maps ISO 42001 clauses to toolkit documents and client deliverables |
| `cross-framework-mapping.md` | Reference | Maps ISO 42001 controls to EU AI Act and NIST AI RMF obligations |

### `01-discovery/` — Phase 1: Discovery & Scoping

| File | Type | Description |
|------|------|-------------|
| `README.md` | Reference | Phase 1 overview, inputs, outputs, and file guide |
| `procedure-discovery-scoping.md` | Internal Procedure | Step-by-step guide for running discovery workshops and documenting outputs |
| `template-ai-system-inventory.md` | Client Template | Structured inventory of all AI systems in scope |
| `template-stakeholder-register.md` | Client Template | Register of interested parties and their AIMS-relevant interests |

### `02-gap-analysis/` — Phase 2: Gap Analysis

| File | Type | Description |
|------|------|-------------|
| `README.md` | Reference | Phase 2 overview, inputs, outputs, and file guide |
| `procedure-gap-analysis.md` | Internal Procedure | How to conduct the gap analysis, score findings, and prioritize gaps |
| `template-gap-analysis-workbook.md` | Client Template | Clause-by-clause assessment workbook with scoring |
| `template-gap-analysis-report.md` | Client Template | Executive summary and findings report for client presentation |

### `03-remediation/` — Phase 3: Remediation

| File | Type | Description |
|------|------|-------------|
| `README.md` | Reference | Phase 3 overview, inputs, outputs, and file guide |
| `procedure-remediation-support.md` | Internal Procedure | How to sequence remediation work, manage client effort, and validate outputs |
| `template-ai-policy.md` | Client Template | Top-level AI Policy document (Clause 5.2) |
| `template-acceptable-use-policy.md` | Client Template | Acceptable Use Policy for AI systems (Annex A.2) |
| `template-risk-assessment-register.md` | Client Template | AI risk register with likelihood/impact scoring |
| `template-impact-assessment.md` | Client Template | AI impact assessment for individual AI systems |
| `template-soa.md` | Client Template | Statement of Applicability mapping Annex A controls |
| `template-risk-treatment-plan.md` | Client Template | Risk treatment decisions and action tracking |
| `template-supplier-assessment.md` | Client Template | Third-party AI supplier assessment questionnaire |
| `template-training-competence.md` | Client Template | Training records and competence evidence log |
| `template-ncar-log.md` | Client Template | Nonconformity, Corrective Action, and Review (NCAR) log |
| `template-implementation-roadmap.md` | Client Template | Phased implementation roadmap with milestones |

### `04-pre-audit/` — Phase 4: Pre-Audit Readiness

| File | Type | Description |
|------|------|-------------|
| `README.md` | Reference | Phase 4 overview, inputs, outputs, and file guide |
| `procedure-pre-audit-readiness.md` | Internal Procedure | How to conduct the readiness review and simulate auditor questions |
| `template-internal-audit-checklist.md` | Client Template | Internal audit checklist aligned to ISO 42001 clauses |
| `template-management-review.md` | Client Template | Management review agenda and minutes template |
| `template-pre-audit-checklist.md` | Client Template | Final readiness checklist before certification body engagement |

### `05-certification/` — Phase 5: Certification Audit Support

| File | Type | Description |
|------|------|-------------|
| `README.md` | Reference | Phase 5 overview and guidance for certification audit support |

### `07-business/` — Business Development

| File | Type | Description |
|------|------|-------------|
| `README.md` | Reference | Business development overview and file guide |
| `procedure-engagement-management.md` | Internal Procedure | Engagement management process from proposal through close |
| `template-engagement-proposal.md` | Client Template | Engagement proposal with scope, approach, and pricing |
| `template-sow.md` | Client Template | Statement of Work for signed engagements |

---

## How to Use This Toolkit

### Starting a new engagement

1. **Read `00-foundation/` first.** The glossary and Annex A reference are the backbone of every client conversation. Know the terminology before you're in front of a client.

2. **Use `07-business/` to scope and propose.** The engagement proposal and SOW templates define the engagement before work begins. The internal procedure covers how to scope, price, and manage the engagement.

3. **Follow phases 1 through 5 in sequence.** Each phase builds on the last. Discovery outputs feed the gap analysis. Gap analysis outputs drive remediation. Don't skip ahead.

4. **Use the internal procedure first, then the templates.** Each phase has a `procedure-*.md` that tells you how to run the phase. Read it before opening any client template.

5. **Strip HOW TO CUSTOMIZE blocks before delivery.** Every client template contains customization guidance in clearly marked blocks. These are for the consultant. Remove them before the client sees the document.

### Typical engagement timeline for an SMB

| Phase | Typical Duration |
|-------|-----------------|
| Phase 1: Discovery & Scoping | 1–2 weeks |
| Phase 2: Gap Analysis | 1–2 weeks |
| Phase 3: Remediation | 6–12 weeks |
| Phase 4: Pre-Audit | 2–3 weeks |
| Phase 5: Certification | 2–4 weeks (audit scheduling dependent) |

Total: roughly 3–5 months for a typical SMB engagement, depending on the client's starting point and internal capacity.

---

## Terminology Note

All documents use controlled vocabulary from `00-foundation/glossary.md`. When in doubt about a term, check the glossary before using it in a client document.

Key terms used throughout the toolkit:

- **AIMS** — AI Management System. The management system the client is building.
- **AI system** — A machine-based system that generates outputs such as predictions, recommendations, or decisions. In this toolkit, always refers to third-party systems the client deploys.
- **AI user** — An organization that deploys an AI system for its own purposes. The client type this toolkit serves.
- **Interested parties** — Stakeholders with relevant interests in the AIMS (employees, customers, regulators, suppliers).
- **SoA** — Statement of Applicability. Documents which Annex A controls apply and why.
- **Nonconformity** — A failure to meet a requirement of ISO 42001.
- **Documented information** — Any information the standard requires to be maintained or retained.

---

## Converting Documents for Client Delivery

All toolkit files are written in Markdown. For client delivery, convert to Word or PDF.

**Pandoc (recommended):**
```bash
pandoc template-name.md -o template-name.docx
pandoc template-name.md -o template-name.docx --reference-doc=your-template.docx
```

Install Pandoc from [pandoc.org](https://pandoc.org). A reference `.docx` file applies your firm's branding automatically.

**Google Docs:** File > Open > upload the `.md` file. Formatting needs manual cleanup but works for one-off documents.

**VS Code with Markdown PDF extension:** Right-click any `.md` file and export to PDF directly.

Always review converted documents before sending. Tables and code blocks sometimes need adjustment after conversion.

---

## Common Pitfalls

A few patterns show up repeatedly in SMB ISO 42001 engagements. Worth knowing before you start.

**Scope creep in Phase 1.** Clients often want to include every AI tool they've ever heard of. Push back early. A tightly scoped AIMS is easier to certify and easier to maintain. Start narrow; the scope can expand in future surveillance cycles.

**Underestimating Phase 3.** Remediation almost always takes longer than clients expect. They underestimate how much internal effort is required to review, approve, and implement policies. Set realistic expectations at the Phase 2 report-out, not after delays have already happened.

**Skipping the management review.** Some clients treat the management review as a formality. It isn't. Auditors look for evidence that top management is genuinely engaged with the AIMS, not just that a meeting happened. Help the client prepare substantive inputs and record meaningful decisions.

**Delivering templates without removing HOW TO CUSTOMIZE blocks.** This happens. Build a pre-delivery checklist into your workflow. Sending a client a document with visible consultant instructions is a credibility problem.

**Treating certification as the finish line.** ISO 42001 certification requires annual surveillance audits and a three-year recertification cycle. Brief the client on ongoing obligations before the engagement closes. The NCAR log and internal audit process need to continue after you leave.

---

## Version and Currency

All documents in this toolkit are current as of **March 2026**. Review the toolkit annually or whenever ISO/IEC 42001 is updated. The EU AI Act compliance dates are phased through 2027 — check `00-foundation/cross-framework-mapping.md` for current applicability timelines.

---

*ISO 42001 Readiness Service Toolkit | © Skill Tree AI | Confidential — Internal Use*
