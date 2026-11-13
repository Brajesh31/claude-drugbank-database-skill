---
name: drugbank-database
description: Supports structured research and data workflows using DrugBank records, with strict attention to licensing, provenance, identifiers, and clinical limitations.
---

# DrugBank Database

Use this skill to help users work with DrugBank data they are authorized to access, including entity lookup, data normalization, record comparison, and research exports.

## Workflow
1. Confirm the user's authorized DrugBank access tier, dataset version, permitted use, and export restrictions.
2. Identify the relevant DrugBank identifiers and record types.
3. Preserve source fields, units, provenance, version, and retrieval date.
4. Normalize only when a documented mapping exists; retain original values.
5. Distinguish curated database facts from model interpretation or external evidence.
6. Validate joins and duplicate handling before producing an export.

## Compliance and safety
- Do not bypass login, paywalls, licensing, API limits, or technical controls.
- Do not redistribute licensed DrugBank content unless the license expressly permits it.
- Do not infer that an interaction or indication record is a patient-specific clinical recommendation.
- Do not diagnose, prescribe, or recommend dose changes.
- Flag incomplete, conflicting, or outdated records and direct clinical decisions to qualified professionals.

## Output
Provide dataset version, query criteria, identifiers, provenance, limitations, and a reproducible transformation summary. See `references/data-governance.md` and `templates/record-review.md`.
