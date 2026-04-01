# Phase 1: Discovery & Scoping

> **Current as of:** March 2026 | ISO/IEC 42001:2023

---

## What This Phase Accomplishes

Phase 1 is the foundation of every ISO 42001 readiness engagement. Before you can assess gaps, build policies, or prepare for an audit, you need to know what the client has, who cares about it, and where the boundaries are.

This phase answers three questions:

1. **What AI systems does the organization use?** This includes formally adopted tools, embedded AI features within SaaS platforms, and unauthorized shadow AI. Most SMB clients significantly undercount their AI systems at the start of an engagement.

2. **Who are the interested parties?** Every person, group, or organization with a stake in how the client uses AI — employees, customers, vendors, regulators, and more. Clause 4.2 requires this to be documented.

3. **What is the AIMS scope?** The defined boundaries of the AI Management System — which business units, AI systems, locations, and activities are in scope. Clause 4.3 requires this to be documented and available.

Phase 1 typically takes 1–2 weeks for an SMB with 40–200 employees.

---

## Files in This Directory

| File | Type | Audience | Description |
|---|---|---|---|
| `procedure-discovery-scoping.md` | Internal Procedure | Consultant | Step-by-step guide for executing Phase 1. Includes interview scripts, decision trees, the embedded AI detection methodology, classification frameworks, and escalation triggers. A junior consultant with ISO management system experience can execute this procedure without prior ISO 42001 knowledge. |
| `template-stakeholder-register.md` | Client Template | Client | Stakeholder register for documenting all interested parties per Clause 4.2. Includes 12 pre-filled example entries covering the most common stakeholder types for AI user organizations, a blank register for client use, and a Clause 4.2 requirements mapping. |

---

## How This Phase Connects to the Engagement Lifecycle

```
Phase 1: Discovery & Scoping    ← YOU ARE HERE
    │
    ├── Produces: AI System Inventory
    │   └── Used by: Phase 2 (Gap Analysis) — each AI system assessed against ISO 42001 controls
    │
    ├── Produces: Stakeholder Register
    │   └── Used by: Phase 2 (Clause 4.2 evidence), Phase 3 (stakeholder engagement planning)
    │
    ├── Produces: Draft AIMS Scope Statement
    │   └── Used by: Phase 2 (Clause 4.3 evidence), Phase 3 (scope finalization)
    │
    └── Produces: Phase 1 Summary Report
        └── Used by: Phase 2 kickoff, Client Sponsor alignment
```

**Prerequisite:** Signed Statement of Work (SOW) from `07-business/`

**Next phase:** Phase 2 — Gap Analysis (`02-gap-analysis/`)

---

## Key ISO 42001 Clauses Addressed

| Clause | Requirement | Phase 1 Output |
|---|---|---|
| **4.1** | Understanding the organization and its context | Executive Sponsor Interview findings; organizational context documented in Phase 1 Summary Report |
| **4.2** | Understanding the needs and expectations of interested parties | Stakeholder Register |
| **4.3** | Determining the scope of the AIMS | Draft AIMS Scope Statement |

---

*ISO 42001 Readiness Service Toolkit | 01-Discovery | Internal Use*
