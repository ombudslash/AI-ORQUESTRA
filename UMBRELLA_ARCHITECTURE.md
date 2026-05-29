# Umbrella Architecture

This is the public-safe map. Private details live in `ombudslash/ENCORE`.

## North Star

One operating context across Mac, Dell, phone, browser, and cloud.

The native app sidebars do not need to match. GitHub and durable reports are the shared layer.

## Device Roles

- Dell laptop `DESKTOP-SHHN4FP`: worker/storage node. Connected to drives, GitHub, Google Drive, Codex, Antigravity, and similar execution tools. Runs code processing, storage, indexing, scans, builds, tests, and unattended jobs.
- Mac: command/creative node. Directs work, reviews reports, supervises, creates plans, videos, music, art, philosophy, writing, and strategy.
- Phone Codex and web Codex: review/control surfaces for links, reports, status, and lightweight direction.
- Cloud Codex: optional backup execution layer.

## Shared Layer

- Public launcher: https://github.com/ombudslash/AI-ORQUESTRA
- Dell handoff: https://github.com/ombudslash/AI-ORQUESTRA/blob/main/DELL_CODEX_HANDOFF.md
- Dell storage map: https://github.com/ombudslash/AI-ORQUESTRA/blob/main/DELL_STORAGE_MAP.md
- Private context pack: https://github.com/ombudslash/ENCORE/tree/main/UMBRELLA_CONTEXT
- Private ENCORE repo: https://github.com/ombudslash/ENCORE
- Connector test repo: https://github.com/ombudslash/manus-github-connector-test

## Operating Rule

If a result must be visible across devices, it needs to become one of:

- GitHub file
- Google Drive file/folder
- generated report
- issue/PR/comment
- exported chat index or recap
- explicit handoff document

If useful work only exists inside one local Codex chat, it is not portable yet.

## Public/Private Boundary

Public `AI-ORQUESTRA` contains routing, roles, safe links, and non-sensitive status.

Private `ENCORE/UMBRELLA_CONTEXT` contains inherited Mac context, private source maps, instructions, chat index, and sensitive operating rules.

Do not mirror private context into this public repo.
