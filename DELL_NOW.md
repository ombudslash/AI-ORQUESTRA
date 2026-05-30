# Dell Now

Status: DELL LOCAL EXECUTION REQUIRED

Dell worker target: `DESKTOP-SHHN4FP`

Current priority: run the private Dell WD hash gate and write the result report.

## Start Here

Open the private umbrella context on the Dell:

```text
C:\Users\ezequ\My Drive\AI-ORQUESTRA\.private\ENCORE_UMBRELLA_CONTEXT\UMBRELLA_CONTEXT
```

Read first:

```text
000_DELL_EXECUTE_NOW.txt
```

If Dell Codex is idle, paste the prompt from:

```text
000_DELL_CODEX_PROMPT_NOW.md
```

## Routing

Do not wait for Mac-to-Dell SSH. The Mac checked the Dell LAN address and SSH, SMB, RDP, and WinRM are not open.

Dell-side work must run locally on the Dell through Dell Codex or Dell PowerShell.

## Expected Proof

The current cutover gate is not done until this private file exists:

```text
DELL_WD_HASH_LAST_RUN.md
```

Mac Codex should not be deleted until the cutover audit is updated after that result is reviewed.

## Mirror Freshness

The Mac-side monitor refreshes the private Codex mirror before checking this gate. Dell can inspect:

```text
C:\Users\ezequ\My Drive\AI-ORQUESTRA\.private\CODEX_MAC_MIRROR\latest\MIRROR_MANIFEST.md
```

That manifest is the current proof that Mac Codex config, instructions, chat index, and raw transcripts were copied into the private mirror.
