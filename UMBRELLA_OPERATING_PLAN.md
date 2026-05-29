# Umbrella Operating Plan

This is the public-safe operating plan for using Mac, Dell, phone, browser, cloud Codex, GitHub, Google Drive, and similar tools as one system.

## Summary

- Dell is the worker and storage laptop.
- Mac is the creative and supervisory console.
- Phone and web Codex are review and lightweight control surfaces.
- GitHub and Google Drive are the durable shared layer.
- Native Codex sidebars and chats do not need to match across devices.

## Core Architecture

1. Public launcher: `ombudslash/AI-ORQUESTRA`
2. Private inherited context: `ombudslash/ENCORE/UMBRELLA_CONTEXT`
3. Dell worker files and status: `AI-ORQUESTRA/DELL_CODEX_HANDOFF.md` and `AI-ORQUESTRA/DELL_STORAGE_MAP.md`
4. Sensitive source rules, chat index, and case context: private ENCORE only
5. Review outputs: GitHub files, Drive reports, or generated dashboards, not local-only chat text

## Device Roles

### Dell

The Dell laptop should be treated as an always-ready worker node.

It owns:

- GitHub and repo operations
- Google Drive and mounted-drive access
- External-drive inventory and storage tasks
- Long scans, hashing, indexing, builds, tests, and unattended jobs
- Antigravity, Codex, and similar execution software
- Durable worker status reports

### Mac

The Mac should be treated as the creative and command node.

It owns:

- Direction and taste
- Report review
- Plans and strategy
- Writing, video, music, art, philosophy, and creative work
- Supervision of Dell outputs
- Final decisions before external or risky actions

### Phone and Web

Phone and web Codex should be treated as review/control surfaces.

They own:

- Reading GitHub and Drive reports
- Checking status
- Giving lightweight direction
- Approving or redirecting queued work

## Work Routing

Use this routing by default:

- If it is heavy, repetitive, storage-related, or code-processing work: send it to Dell.
- If it is creative, interpretive, strategic, or taste-heavy work: do it from Mac.
- If it is quick status, review, or redirection: phone or web is enough.
- If it must be visible later: save it to GitHub, Google Drive, or a report.

## No Fragile Remote Typing Rule

Chrome Remote Desktop keyboard mapping can corrupt shell punctuation. Do not depend on raw remote keystrokes for complex commands.

Use these paths instead:

1. Ask Dell Codex in plain language to run the command locally.
2. Put exact command/script content in GitHub and tell Dell Codex to read/run it locally.
3. Use Dell-local terminals only after keyboard layout is confirmed.
4. Avoid pasting complex shell commands through remote control unless a punctuation smoke test passes first.

## Operational Priorities

1. Stabilize Dell as worker/storage node.
2. Confirm Dell can read `ENCORE/UMBRELLA_CONTEXT`.
3. Keep public/private boundaries clean.
4. Keep Google Drive and external drives visible on Dell.
5. Have Dell write short durable status reports when work completes or blocks.
6. Keep Mac focused on command, review, and creative output.

## Success Criteria

The setup is working when:

- Mac, Dell, phone, and web all start from `AI-ORQUESTRA`.
- Dell can read the private context pack in ENCORE.
- Dell can access GitHub, Google Drive, and expected attached drives.
- Dell can run worker jobs and save outputs to GitHub or Drive.
- Mac can supervise through reports instead of babysitting remote windows.
- No sensitive ENCORE/private content is exposed in public `AI-ORQUESTRA`.
