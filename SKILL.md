---
name: nz-legal-mcp-skill
description: Official New Zealand (NZ) legislation, multi-tier court precedent research, and citation verification skill.
version: 2.0.0
author: JurisAtlas
license: MIT
---

# New Zealand Legal Research & Multi-Tier Case Law Skill (`nz-legal-mcp`)

Use this skill whenever the user asks a legal question, drafts a pleading or contract, or researches case law across any judicial instance in **New Zealand (NZ)**.

## Verification & Research Rules

1. **Citation Verification:** Never fabricate a statutory provision or case citation. Query `search_legislation`, `search_case_law`, `search_tiered_court_decisions`, or `verify_citation` before citing any authority (e.g., `[2024] NZSC 5 or [2023] NZCA 120`).
2. **Multi-Tier Judicial Coverage:**
   - **First Instance (Trial / Municipal / District):** District Court of New Zealand (NZDC), Family Court, Employment Court & Environment Court
   - **Second Instance (Cantonal / Regional / Appellate):** High Court of New Zealand (NZHC) & Court of Appeal of New Zealand (NZCA)
   - **Supreme & Constitutional Instance:** Supreme Court of New Zealand / Te Kōti Mana Nui (NZSC)
   - **Primary Tiered Database:** Judicial Decisions Online (courtsofnz.govt.nz / districtcourts.govt.nz / nzlii.org) (`https://www.courtsofnz.govt.nz`)
