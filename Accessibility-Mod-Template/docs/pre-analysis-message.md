# Pre-analysis message (send before every Codex analysis)

Copy and send the following message to Codex CLI **before starting any analysis**.

---

Before starting analysis:

- I am using the Accessibility Mod Template for Codex CLI.
- You MUST follow AGENTS.md and all Codex workflow documentation in this repository.
- The ONLY local game data available to you is what exists under:
  Accessibility-Mod-Template/workspace-input/

- Actual source paths used (if different from the examples in setup-guide):
  - logs source path: [e.g. C:\\Games\\MyGame\\MelonLoader\\]
  - managed source path: [e.g. D:\\SteamLibrary\\steamapps\\common\\MyGame\\MyGame_Data\\Managed\\]
  - decompiled source path: [e.g. E:\\Decompile\\MyGame\\]
  - ui source path: [e.g. where you exported UI dumps]



- Git repository status (optional):
  - Repository already initialized (git init has been run): [yes/no]
  - Current branch (if known): [main/master/other]
  - Remote already configured: [yes/no]
  - Intended primary remote name: [origin]

- GitHub publishing intent (optional):
  - I intend to publish/push changes to GitHub in this session: [yes/no]
  - GitHub CLI auth is already configured locally (you may verify with `gh auth status` ONLY after approval): [yes/no]
  - Remote URL (if already known): [https://github.com/<USER>/<REPO>.git or SSH URL]

- Files currently present in workspace-input:
  - logs/: [describe contents briefly]
  - managed/: [list DLLs present, or say 'none']
  - decompiled/: [present / not present]
  - ui/: [describe contents, or say 'none']

- Do NOT assume the existence of any other files, paths, or game data.
- If additional files are required, request them using the mandatory protocol
  defined in AGENTS.md and WAIT for confirmation before continuing.

Confirm that you understand these constraints before proceeding.