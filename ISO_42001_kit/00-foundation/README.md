# ISO 42001 Readiness Service Toolkit

> **Current as of:** March 2026 | ISO/IEC 42001:2023 | EU AI Act (Regulation 2024/1689) | NIST AI RMF 1.0

---

## What This Toolkit Is

This toolkit supports a small consulting firm delivering ISO/IEC 42001:2023 readiness services to small and mid-sized businesses (SMBs). The clients this toolkit serves are **AI users**, not AI builders. They deploy third-party AI systems, such as ChatGPT, Microsoft Copilot, Salesforce Einstein, or similar vendor-provided tools, and need a structured management system to govern how those systems are selected, used, monitored, and controlled.

ISO/IEC 42001:2023 is the international standard for AI Management Systems (AIMS). It gives organizations a framework to demonstrate responsible, accountable AI use. This toolkit walks a consultant through every phase of a readiness engagement, from initial scoping through certification audit support.

---

## Document Types

Every file in this toolkit falls into one of two categories. Knowing the difference matters before you open anything.

**Internal Procedures** are step-by-step guides written for the consultant. They describe what to do, in what order, and what to watch for. Clients do not receive these documents.

**Client Templates** are deliverables. They get filled in during the engagement, either by the consultant working with the client or by the client directly. These are the artifacts that end up in the client's AIMS documentation set and, ultimately, in front of an auditor.

Each folder's README identifies which files are procedures and which are templates.

---

## Toolkit Structure

### `00-foundation/` — Foundational Reference Documents

The reference layer. These documents don't change per client. They define shared vocabulary, map the standard's controls, and provide the traceability backbone for the whole engagement.

- `glossary.md` — Controlled vocabulary and key definitions (single source of truth for all terminology used across the toolkit)
- `annex-a-reference.md` — Full Annex A control reference with implementation guidance notes
- `traceability-matrix.md` — Maps ISO 42001 clauses to toolkit documents and client deliverables

### `01-discovery/` — Phase 1: Discovery and Scoping

The engagement starts here. This phase establishes the client's context, identifies their AI systems, defines the AIMS scope, and surfaces the interested parties who matter.

- Internal procedure: how to run discovery workshops and document outputs
- Client templates: AI inventory worksheet, scope definition document, stakeholder register

### `02-gap-analysis/` — Phase 2: Gap Analysis

Compare the client's current state against ISO 42001 requirements. This phase produces the gap register that drives everything in Phase 3.

- Internal procedure: how to conduct the gap analysis, score findings, and prioritize gaps
- Client templates: gap analysis workbook, findings summary report

### `03-remediation/` — Phase 3: Remediation and Implementation Support

Close the gaps. This phase guides the client through building or updating the policies, procedures, and records their AIMS requires.

- Internal procedure: how to sequence remediation work, manage client effort, and validate outputs
- Client templates: remediation plan tracker, policy templates, procedure templates, Statement of Applicability (SoA)

### `04-pre-audit/` — Phase 4: Pre-Audit Readiness Review

A structured internal review before the certification body arrives. This phase stress-tests the AIMS documentation and identifies any remaining gaps.

- Internal procedure: how to conduct the readiness review, simulate auditor questions, and produce the readiness report
- Client templates: readiness review checklist, evidence log, readiness report

### `05-certification/` — Phase 5: Certification Audit Support

Support the client through Stage 1 and Stage 2 certification audits. This phase covers audit logistics, nonconformity response, and post-audit follow-up.

- Internal procedure: how to prepare the client, manage audit day, and handle nonconformities

### `06-cross-framework/` — Cross-Framework Mapping

Many clients face overlapping regulatory requirements. This folder maps ISO 42001 controls to the EU AI Act (Regulation 2024/1689) and the NIST AI Risk Management Framework 1.0, so consultants can identify synergies and avoid duplicating client effort.

- ISO 42001 to EU AI Act mapping
- ISO 42001 to NIST AI RMF mapping
- Consolidated cross-framework summary

### `07-business/` — Business Templates

The commercial layer. These documents support the consulting firm's own operations.

- Proposal template
- Statement of Work (SOW) template
- Engagement management tracker

---

## How to Run an Engagement

Follow phases 1 through 5 in sequence for each client. The phases are designed to build on each other: discovery outputs feed the gap analysis, gap analysis outputs feed remediation, and so on.

**Typical engagement flow:**

1. **Phase 1 (Discovery):** Understand the client's organization, AI systems, and stakeholders. Define the AIMS scope. Deliverable: signed scope document and AI inventory.
2. **Phase 2 (Gap Analysis):** Assess current state against ISO 42001 requirements. Deliverable: gap register and findings report.
3. **Phase 3 (Remediation):** Build the AIMS. Policies, procedures, records, SoA. Deliverable: complete AIMS documentation set.
4. **Phase 4 (Pre-Audit):** Review everything before the certification body does. Deliverable: readiness report with any remaining actions.
5. **Phase 5 (Certification):** Support Stage 1 and Stage 2 audits. Deliverable: nonconformity responses (if needed), audit closure.

Cross-framework mapping (Phase 6 folder) can be introduced at any point when a client has EU AI Act or NIST obligations. Business templates (Phase 7 folder) are used before and throughout the engagement.

---

## How to Convert to Word or PDF

All toolkit documents are written in Markdown. For client delivery, convert to Word or PDF using one of these approaches.

**Pandoc (recommended for batch conversion):**
```bash
pandoc input.md -o output.docx --reference-doc=your-template.docx
pandoc input.md -o output.pdf
```
Install pandoc from [pandoc.org](https://pandoc.org). A reference `.docx` file lets you apply your firm's branding and styles automatically.

**Google Docs import:**
Open Google Docs, go to File > Open, and upload the `.md` file. Formatting will need manual cleanup, but it's a fast option for one-off documents.

**VS Code with Markdown PDF extension:**
Right-click any `.md` file and export to PDF directly. Good for quick previews.

**Typora or Obsidian:**
Both applications render Markdown natively and export to PDF or Word with minimal friction. Useful if you're editing documents before delivery.

For client-facing deliverables, always review the converted document before sending. Table formatting and code blocks sometimes need adjustment after conversion.

---

## Legal Disclaimer

This toolkit does not constitute legal advice. Organizations should consult qualified legal counsel for regulatory compliance matters.

---

*ISO 42001 Readiness Service Toolkit | Internal Use*
