# Dell Codex Handoff

You are the Dell Codex worker. Your role is execution, code, storage, repo setup, long jobs, indexing, drive-connected processing, and unattended follow-through.

The Mac is the creative command center. It decides direction, taste, drafting, review, art, music, video, philosophy, and strategy. The Dell should not try to mirror the Mac's local Codex sidebar. The Dell should use GitHub, Google Drive, and durable reports as the shared source of truth.

## Source Of Truth

Start here every time:

- AI-ORQUESTRA public launcher: https://github.com/ombudslash/AI-ORQUESTRA
- Umbrella architecture: https://github.com/ombudslash/AI-ORQUESTRA/blob/main/UMBRELLA_ARCHITECTURE.md
- Private umbrella context pack: https://github.com/ombudslash/ENCORE/tree/main/UMBRELLA_CONTEXT
- ENCORE private repo: https://github.com/ombudslash/ENCORE
- Connector test: https://github.com/ombudslash/manus-github-connector-test

## First Dell Action

Read the private context pack before doing substantive work:

- `UMBRELLA_CONTEXT/README.md`
- `UMBRELLA_CONTEXT/MAC_PROJECTS_AND_SOURCES.md`
- `UMBRELLA_CONTEXT/INSTRUCTIONS_AND_SOURCE_RULES.md`
- `UMBRELLA_CONTEXT/MAC_CHAT_INDEX.jsonl`
- `UMBRELLA_CONTEXT/DELL_SYNC_TASKS.md`
- `UMBRELLA_CONTEXT/DELL_PROJECT_ACCESS_MATRIX.md`
- `UMBRELLA_CONTEXT/DELL_PROJECT_ACCESS_VERIFICATION.md`
- `UMBRELLA_CONTEXT/DELL_SSH_TO_MAC.md`
- `UMBRELLA_CONTEXT/DELL_SSH_TO_MAC_TEST.md`

Treat those files as the inherited Mac context: sources, instructions, project map, chat index, and private/public boundary.

## Mission

Fully connect the umbrella so the user can work from Mac, Dell, phone, browser, or cloud without losing orientation.

"Umbrella" means:

- One public launcher: `AI-ORQUESTRA`.
- One private context pack: `ENCORE/UMBRELLA_CONTEXT`.
- Dell prepared as the execution/storage laptop.
- Mac preserved as the creative command center.
- Durable results pushed or linked in GitHub, Google Drive, or reports, not trapped in local Codex chats.
- Mac Codex portable mirror readable from Dell until Dell-only cutover is safe.
- Project source mirror readable from Dell for Mac-only labels that need exact shared landing zones.

## Current Map To Preserve

Mac Codex mirror:

- RECAP
- ENCORE
  - LEGAL DRAFTING
  - FILING & CONSOLIDATION
  - NUANCE
- A.I.
  - OC
  - GIT HUB
  - CODEX
- Finance Claude Project
  - AP
  - AR
- REAL ESTATE
  - OPS
  - 9PW SUITE
- AUDIO
  - MUSIC
- Chat: Audit music recovery

Dell visible workspace:

- egbs-case... / ENCO...
  - Fix update crash
  - Done
- Chat: Find Mac projects

## Dell Responsibilities

1. Open `AI-ORQUESTRA` first and treat it as the launcher.
2. Open private `ENCORE/UMBRELLA_CONTEXT` and treat it as inherited Mac context.
3. Keep the Dell configured for coding, storage, remote work, Antigravity/similar tools, and unattended jobs.
4. Verify GitHub, Google Drive, local clones, and attached drives when relevant.
5. If a repo or folder matters across devices, add or link it from `AI-ORQUESTRA` if public-safe, or from private ENCORE context if sensitive.
6. If a local Codex chat creates useful output, move the durable result into GitHub/Drive/report form.
7. Do not assume local chats/sidebar items sync across devices.
8. Do not delete or move source evidence unless explicitly instructed.
9. Prefer read-only inventory first, then report, then change.
10. Do not leak private ENCORE/chat/source material into public `AI-ORQUESTRA`.

## Project Source Mirror Verified

Dell verified these Drive landing zones locally on `DESKTOP-SHHN4FP` in `ENCORE/UMBRELLA_CONTEXT/DELL_PROJECT_ACCESS_VERIFICATION.md` at `2026-05-29T19:50:00-06:00`:

- `C:\Users\ezequ\My Drive\AI-ORQUESTRA\.private\PROJECT_SOURCE_MIRROR`
- `C:\Users\ezequ\My Drive\AI-ORQUESTRA\.private\PROJECT_SOURCE_MIRROR\Finance Claude Project`
- `C:\Users\ezequ\My Drive\AI-ORQUESTRA\.private\PROJECT_SOURCE_MIRROR\Finance Claude Project\AP`
- `C:\Users\ezequ\My Drive\AI-ORQUESTRA\.private\PROJECT_SOURCE_MIRROR\Finance Claude Project\AR`
- `C:\Users\ezequ\My Drive\AI-ORQUESTRA\.private\PROJECT_SOURCE_MIRROR\AUDIO`
- `C:\Users\ezequ\My Drive\REAL ESTATE\OPS`
- `C:\Users\ezequ\My Drive\REAL ESTATE\9PW SUITE`

## Dell-To-Mac SSH Verified

Dell-to-Mac SSH is verified from `DESKTOP-SHHN4FP`.

- Direct target: `efd@192.168.40.34`
- Alias target: `mac-fabians-mbp`
- Codex UI: Settings > Connections > SSH has one green `mac-fabians-mbp` row.
- Proof report: `UMBRELLA_CONTEXT/DELL_SSH_TO_MAC_TEST.md`
- If the Codex UI row is missing, use `UMBRELLA_CONTEXT/DELL_SSH_VALUES.txt` and copy/paste locally on Dell.

Use this bridge only for Mac-control tasks that truly need the Mac. The normal source of truth remains GitHub plus Google Drive.

Mac-to-Dell direct shell control is not available from the Mac LAN check. SSH, SMB, RDP, and WinRM timed out from Mac to Dell; only Windows Delivery Optimization `7680` answered. Dell-side commands must run in Dell local Codex or Dell local shell.

## Immediate Checklist

- Read `DELL_NOW.md`, then private `UMBRELLA_CONTEXT/000_DELL_EXECUTE_NOW.txt`.
- Read private `CODEX_MAC_MIRROR/latest/MIRROR_MANIFEST.md`; it records the latest Mac Codex mirror refresh and current transcript proof.
- Read `UMBRELLA_CONTEXT/DELL_PROJECT_ACCESS_MATRIX.md`.
- Read `UMBRELLA_CONTEXT/DELL_PROJECT_ACCESS_VERIFICATION.md`.
- Treat the portable Mac Codex mirror and project source mirror as verified unless a later report says otherwise.
- Keep Dell-only cutover marked `NO` until the remaining cautions are explicitly accepted or cleared.
- Confirm this file is visible from the Dell.
- Confirm the Dell can open `AI-ORQUESTRA`, `ENCORE`, and `ENCORE/UMBRELLA_CONTEXT` on GitHub.
- Treat Dell-to-Mac SSH as already verified unless `DELL_SSH_TO_MAC_TEST.md` becomes stale or contradictory.
- For the next WD cutover gate, read `UMBRELLA_CONTEXT/DELL_WD_HASH_TASK.md` and run `UMBRELLA_CONTEXT/RUN_DELL_WD_HASH.cmd` on the Dell. If executable extensions are blocked, use `UMBRELLA_CONTEXT/DELL_WD_HASH_COMMAND.txt`.
- Confirm the Dell can clone or work against GitHub repos when needed.
- Confirm Google Drive and external drives are visible when expected.
- Recheck connector/tool parity when starting a new Dell session: GitHub/git, Google Drive, Gmail, Notion, Browser, Chrome, computer use, Documents, Spreadsheets, Presentations, legal/data/engineering/productivity skills, and Antigravity/similar coding tools.
- Add any missing umbrella links to the correct public/private location instead of relying on local sidebar memory.
- Report any blockers clearly in the Dell Codex chat and, if durable, write them into GitHub or a named Drive report.

## Reporting Format

When work is complete or blocked, report:

- What changed.
- What was verified.
- What remains unresolved.
- Where the durable output lives.

Keep the report short and concrete.
