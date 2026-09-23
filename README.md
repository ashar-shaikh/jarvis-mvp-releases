Binary releases for the Jarvis desktop app.

No source code here - see the main jarvis-mvp repo. This repo exists so
the in-app updater can check for and download new releases without
needing authenticated access to the private source repo.

## Contents

- **Releases** - the packaged `.dmg` (macOS) and `.exe` installer
  (Windows, when built) for each version.
- `skills/jarvis-retrieval/` - the Claude Skill for querying a Jarvis
  install's indexed corpus via its MCP tools. Copy `SKILL.md` into your
  Claude Code/Desktop skills directory, and paste
  `PROJECT-INSTRUCTIONS.md` into your Project's custom instructions.