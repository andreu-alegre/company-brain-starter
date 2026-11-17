# Company Brain Starter

**Help your AI understand your work. Start with one prompt.**

[Español](README.es.md)

A small, open template for a **private work brain**: your role, collaborators,
projects, decisions and trusted sources. The assistant interviews you and builds it
with you. You do not need to fill out a template, install anything or connect your apps
to try the conversation.

**Preview — the initial structure is being reviewed.**

## Start here

Open Claude, Codex or another assistant and paste this:

```text
Help me set up a private work brain: a small, maintained reference about my work.
If you can read it, use https://github.com/andreu-alegre/company-brain-starter
for the setup guide. If you cannot open it, continue with the instructions below;
do not pretend you read it or require me to install anything.

Use my language. Ask one clear question at a time and wait for my answer.
Understand my company, role, responsibilities, collaborators, current projects,
priorities and what I want help with. Do not assume them. Reuse what I already told you.
When useful, offer to let me explain or analyze a specific source I choose.
Agree on the source and scope before reading external information. We can start
without connectors. Never ask me for passwords, tokens or a full account export.

Once you know enough, show me a short summary, including uncertainties, and ask me
to confirm it before saving. Start with a single MY_BRAIN.md containing my profile,
collaboration, projects, decisions, open questions and sources with dates.
Keep real information in my own private space, never in the public starter.
If you cannot save files, give me the document and explain how to keep it for next time.
Do not change app settings, publish, send messages or connect accounts for this setup.
Finish by suggesting one small useful task. Start with your first question.
```

That is all you need to begin. You can skip questions, say you do not know, or ask for
a five-question version. The assistant should help with your work, not make you complete
an endless onboarding form.

## What happens next

1. You explain what you do, one question at a time.
2. You review what the assistant understood.
3. It prepares your private `MY_BRAIN.md`, or saves it in your chosen private workspace
   if it has permission and file access.
4. You try a real task: prepare a meeting, clarify a project or capture a decision.

The prompt works as a conversation without access to this repo. File access, connectors,
skills and persistence depend on your assistant and account. See the optional
[Claude and Codex notes](docs/assistant-setup.md) if you want to work with a folder.

## From one document to a working structure

Start with [one document](templates/MY_BRAIN.md). When it becomes hard to navigate,
ask your assistant to move the same information into:

```text
my-private-brain/
├── context/       # Role, collaboration, working preferences and source map
├── projects/      # Goals, observed status, dependencies and next steps
├── decisions/     # Explicit decisions, with date and source
├── inbox/         # Observations and questions awaiting confirmation
└── sources/       # A small index of references, not raw exports
```

Use one active storage format. If you migrate to folders, replace the old document
with a short index so the assistant does not maintain two conflicting copies.

**This repository is public. Your completed brain should be private.** Download a ZIP
or create a new **private** repository with **Use this template** when available.
Do not put real work context in a public fork, issue or pull request.

## What is included

- [Guided setup](SETUP.md), with an interview that adapts to your answers.
- Three workflows: [onboarding](skills/brain-onboarding/SKILL.md),
  [meeting preparation](skills/meeting-brief/SKILL.md) and
  [capturing useful context](skills/brain-capture/SKILL.md).
- [Templates](templates/README.md) and a [fictional example](examples/meeting.md).
- Shared instructions with thin adapters for Claude Code and Codex.

The brain is a maintained reference, not an automatic backup of your chats. It does
not connect accounts, activate automations or grant permission to act in your apps.

[Privacy](PRIVACY.md) · [How to contribute](CONTRIBUTING.md) ·
[Documentation sources](docs/sources.md) · [MIT license](LICENSE)
