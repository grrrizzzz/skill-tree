# 07-Business

> **Classification:** Internal Use — Engagement Operations

---

## What This Directory Contains

This directory holds the business and engagement operations documents for ISO 42001 readiness engagements. These are the documents that govern how engagements are sold, contracted, and run — not the technical content delivered to clients.

| File | Type | Purpose |
|---|---|---|
| `template-engagement-proposal.md` | Client-facing template | Proposal template for new ISO 42001 readiness engagements. Customized per client and sent before the SOW. |
| `template-sow.md` | Client-facing template | Statement of Work template. Formalizes scope, deliverables, fees, and obligations. Sent after proposal acceptance, before work begins. |
| `procedure-engagement-management.md` | Internal procedure | Step-by-step guidance for running an engagement from first inquiry through close-out. Internal use only — not shared with clients. |

---

## How These Documents Relate to the Engagement Lifecycle

```
Inquiry
  │
  ▼
Discovery Call  ←─── procedure-engagement-management.md (Section 4.2)
  │
  ▼
Proposal        ←─── template-engagement-proposal.md
  │
  ▼
SOW             ←─── template-sow.md
  │
  ▼
Kickoff         ←─── procedure-engagement-management.md (Section 5)
  │
  ▼
Phase 1–5       ←─── procedure-engagement-management.md (Section 6)
  │
  ▼
Close-Out       ←─── procedure-engagement-management.md (Section 9)
```

The proposal sets client expectations. The SOW makes them binding. The engagement management procedure tells the consultant how to deliver on both.

---

## Usage Notes

- **Proposals and SOWs** are templates. Every `[PLACEHOLDER]` field must be replaced before sending to a client. Search for `[` to find all placeholders.
- **The engagement management procedure** is prescriptive by design. Follow it. If a situation isn't covered, escalate to the Lead Consultant before improvising.
- **Do not share the internal procedure with clients.** It contains internal process details, fee estimation guidance, and escalation logic that is not appropriate for client review.
- All client-facing documents should be exported to PDF or Word before delivery. See `00-foundation/README.md` for conversion instructions.

---

## Related Directories

The technical content delivered during each phase lives in the corresponding phase directory:

| Phase | Directory |
|---|---|
| Phase 1: Discovery and Scoping | `01-discovery/` |
| Phase 2: Gap Analysis | `02-gap-analysis/` |
| Phase 3: Remediation and Implementation | `03-remediation/` |
| Phase 4: Pre-Audit Readiness Review | `04-pre-audit/` |
| Phase 5: Certification Audit Support | `05-certification/` |

Controlled vocabulary used across all documents is defined in `00-foundation/glossary.md`.

---

*ISO 42001 Readiness Service Toolkit | 07-Business | Internal Use*
