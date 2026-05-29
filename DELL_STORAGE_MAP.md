# Dell Storage Map

This file is the Dell-facing working map for execution, storage, indexing, and unattended jobs. GitHub is the shared source of truth; local Codex sidebars are not assumed to match across devices.

## Verified Repositories

- AI-ORQUESTRA home base: https://github.com/ombudslash/AI-ORQUESTRA
- Dell handoff: https://github.com/ombudslash/AI-ORQUESTRA/blob/main/DELL_CODEX_HANDOFF.md
- ENCORE case operations: https://github.com/ombudslash/ENCORE
- Connector test: https://github.com/ombudslash/manus-github-connector-test

## Dell Local Working Roots

- AI-ORQUESTRA checkout: `C:\Users\ezequ\My Drive\AI-ORQUESTRA`
- ENCORE local root: `C:\Users\ezequ\My Drive\ENCORE`
- EGBS case operations workspace: `C:\Users\ezequ\My Drive\ENCORE\egbs-caseops`
- ENCORE generated reports: `C:\Users\ezequ\My Drive\ENCORE\egbs-caseops\data\reports`

## ENCORE Durable Outputs Currently Mapped

- Case source map, 2023-2026: `data\reports\case_source_map_20260526_192441\source_map_2023_2026.html`
- All-source map, 2023-2026: `data\reports\all_source_map_20260526_191751\source_map_2023_2026.html`
- WD Elements focused map: `data\reports\wd_elements_source_map_20260527_000000\source_map_2023_2026.html`
- WD Elements full map: `data\reports\wd_elements_full_source_map_20260527_000000\source_map_2023_2026.html`
- WD Elements preservation dashboard: `data\reports\wd_elements_preservation_20260526_201359\index.html`
- WD Elements preservation register: `data\reports\wd_elements_preservation_20260526_201359\targeted_wd_case_evidence_register.csv`

## Current Preservation State

- WD Elements targeted case hits identified: 18.
- WD Elements case files copied into preservation folder: 15.
- SHA-256 verified copied files: 14.
- Copied large Giusti video awaiting SHA-256 verification: 1.
- Large Giusti videos pending copy decision: 3 files, about 93.53 GB total.

## Current Blockers

- WD Elements is not always mounted; reconnect it before continuing WD video copy/hash work.
- iCloud EGBS folder is visible on Windows but currently materializes folder shells only, with 0 readable files under the locked EGBS tree.
- ENCORE is visible to authenticated Git, but the local ENCORE tree has not been committed in this Dell workspace yet.
- Do not move, delete, or rename evidence files without explicit instruction.

## Operating Notes

- Use AI-ORQUESTRA as the launcher and shared map.
- Keep durable reports linked here or in the ENCORE repo.
- Keep evidence copies separate from source evidence.
- Prefer read-only inventory before preservation or transformation.
