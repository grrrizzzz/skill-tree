# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is the **ISO 42001 Readiness Service Toolkit** — a consulting deliverables package (not a software project). It contains structured Markdown templates and procedures for delivering ISO/IEC 42001:2023 AI Management System readiness engagements to SMBs that **use** (not build) third-party AI systems.

## Repository Structure

The toolkit follows a **5-phase consulting engagement model** with a foundation layer and business development module:

- `00-foundation/` — Reference materials: glossary, Annex A control catalog, traceability matrix, cross-framework mapping (ISO 42001 / EU AI Act / NIST AI RMF)
- `01-discovery/` — Phase 1: Scoping workshops, AI system inventory, stakeholder register
- `02-gap-analysis/` — Phase 2: Clause-by-clause assessment against ISO 42001
- `03-remediation/` — Phase 3: Build AIMS documentation (policies, risk registers, SoA, etc.)
- `04-pre-audit/` — Phase 4: Internal audit and management review before certification
- `05-certification/` — Phase 5: Stage 1 and Stage 2 audit support
- `07-business/` — Engagement proposals and statements of work
- `.sisyphus/` — Project management metadata (plans, session tracking)
- `ISO_42001_kit/first_try/` — Archive of earlier version; do not modify

## Document Types (Critical Distinction)

- **`procedure-*.md`** — Internal consultant guides. Never deliver to clients. Contain methodology, pricing context, and step-by-step instructions.
- **`template-*.md`** — Client deliverables. Contain `HOW TO CUSTOMIZE` blocks that must be removed before client delivery.

## Content Conventions

- **Terminology** must match `00-foundation/glossary.md` — this is the single source of truth for all key terms (AIMS, AI system, risk assessment, etc.)
- **Annex A controls** use the published ISO 42001:2023 numbering scheme (A.2 through A.10, 39 controls total). The numbering was verified against multiple authoritative sources — do not renumber.
- **Cross-references** between documents use relative paths. Maintain these when moving or renaming files.
- **Traceability matrix** (`00-foundation/traceability-matrix.md`) maps every ISO 42001 clause to its corresponding toolkit template. Update it when adding or renaming templates.

## Standards Context

- **Primary standard:** ISO/IEC 42001:2023 (10-clause Harmonized Structure, Clauses 4-10)
- **EU AI Act** (Regulation 2024/1689) — full effect August 2, 2026
- **NIST AI RMF 1.0** — mapped for US-market clients
- **Target clients:** SMBs (40-200 employees) using third-party AI tools

## Working With This Toolkit

There is no build system, test suite, or linting. Content is authored in Markdown and converted to PDF/Word for delivery (Pandoc, Google Docs, or Obsidian).

When editing templates: preserve the `HOW TO CUSTOMIZE` block format so consultants know what to change per engagement. When editing procedures: maintain the phase-sequential structure (each phase's outputs feed the next phase's inputs).
