# Optional: work with files in your assistant

**You can start with just the prompt in the README.** These notes are for people who
want the assistant to maintain files. Account capabilities and menus can vary.

## Claude chat or Project

Paste the starter prompt. The assistant can interview you without reading this repo.
Keep the resulting document and attach it next time, or add it to a private Project's
context if your account offers that feature. Put the workflow instructions in that
project's instructions if useful. Updating an attachment is not a GitHub sync.

## Claude with folder access / Cowork

Select your own private brain folder. Ask Claude to read `AGENTS.md` and `SETUP.md`
if you copied the template there, then use the starter prompt. Verify actual read/write
access before expecting it to save. Some accounts show Cowork separately; others
have a unified chat/work experience. Do not assume it discovers local skills exactly
like Claude Code.

## Claude Code

Open your private copy as the working folder and start a new session. `CLAUDE.md`
imports the shared instructions; `.claude/skills/` links to the canonical workflows.
Use the normal starter prompt, or `/brain-onboarding` if available. If links were
lost in a ZIP download, request `skills/brain-onboarding/SKILL.md` directly.

## Codex

Open your private copy as a project/working folder and start a new chat. `AGENTS.md`
supplies the project rules and `.agents/skills/` exposes the workflows. Paste the
starter prompt or use `$brain-onboarding` if available. Default account settings
are sufficient to try the interview; no API integration is required for this template.

## Keep it simple

Do not replace global instructions or install a background service for the setup.
Add a connector only when a chosen task needs one, using your organization's process.
Test access on a specific object. No credentials are included or needed in the repo.

To check continuity, start a new session with your saved private context and ask:
"What do you know about my work, what is uncertain, and which sources did you use?"

Official references and review date are in [sources.md](sources.md). These notes have
not been tested across every plan, operating system or assistant version.
