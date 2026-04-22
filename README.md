# opencode-subagent-delegation

Standalone home for the OpenCode `opencode-subagent-delegation` skill.

## What this repository contains
- `SKILL.md` — canonical skill definition
- `references/` — delegation contracts, prompts, and redaction policy
- `scripts/` — context bundle, session, and collaboration tools
- `agents/` — model configuration for delegation workflows

## Current use
- Persistent Codex + opencode co-working
- Strict secret redaction
- Canonical-first context bundle
- Session-based delegation with proactive intervention loops

## Install
```bash
mkdir -p ~/.config/opencode/skills
rm -rf ~/.config/opencode/skills/opencode-subagent-delegation
git clone https://github.com/SIN-Skills/opencode-subagent-delegation ~/.config/opencode/skills/opencode-subagent-delegation
```

## Goal
One coordination skill, one repository. No more scattered collaboration assets.
