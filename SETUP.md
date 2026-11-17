# The guided setup

For the assistant: help the user create a small reference that improves one real
task. Use their language and explain technical choices only when they affect what
the user needs to do. Follow `AGENTS.md` and `PRIVACY.md` when available.

## 1. Establish the working surface only if necessary

Use capabilities you can actually verify. If file access is unclear, ask whether the
user is in an assistant with a working folder, a Project with uploaded context, or a
plain chat. They can describe what they see. Do not send them through several setup
guides or ask for a paid upgrade just to continue the interview.

- With a private writable folder, propose saving there after confirmation.
- With uploaded context or chat only, return `MY_BRAIN.md` for the user to keep.
- In this public template's checkout, do not save real context. Offer a separate private
  destination or return the document. Do not create a repo or change visibility for them.

If needed, consult [the optional assistant notes](docs/assistant-setup.md).

## 2. Interview one question at a time

Start with the first missing fact, usually their company or role. Do not assume they
work for a particular organization, have a sales job or use the maintainer's tools.
Reuse information already supplied and follow their priorities rather than a fixed form.

| Learn | A question you could ask |
|---|---|
| Company | Which company do you work for? |
| Role | What are you responsible for in your role? |
| Work | What takes most of your time in a normal week? |
| Collaboration | Who do you coordinate with to get that work done? |
| Projects | What is the main thing you are working on or need to move forward? |
| Outcome | What would you most like your assistant to help with? |
| Sources | Where do you currently keep the information for that project? |
| Preferences | What makes an answer or deliverable useful to you? |

These are question options, not a questionnaire to display at once. Ask follow-ups
only when they change the context or next step. People may skip, not know, or pause.
For a short version, cover company, role, recurring task, priority project and preferred
way to provide information, then try a task. Do not keep interviewing for completeness.

## 3. Offer explanation, selected analysis, or both

When projects or documents come up, offer a choice: explain them in conversation,
analyze a specific source they choose, or combine both. The choice is optional.

Before analysis, identify the source and purpose: a document, project, call, thread
or defined time range. Resolve ambiguous references before reading. Check the actual
connector and object access; do not promise that a link is readable. If unavailable,
ask for a relevant summary or selected file instead of a full export.

Summarize findings with source and date. Separate observations, hypotheses, decisions
and proposed next steps. An analysis is not permission to create tasks or change records.

## 4. Confirm and create the smallest useful brain

Show what you understood: role, responsibilities, collaboration, priority work, preferred
help, sources and unresolved points. Ask whether it is accurate and can be saved in the
chosen private destination. Accept corrections without restarting the interview.

After confirmation, use [MY_BRAIN.md](templates/MY_BRAIN.md), or the same sections if
the template is unavailable: profile, collaboration, projects, decisions, open questions
and sources. Leave unknowns as unknown. Keep source dates distinct from consultation
dates; do not label every statement confirmed just because saving was authorized.

If no writable private destination is available, provide the file or copyable text and
explain how to attach it next time. Do not claim to have saved, remembered, synchronized
or connected anything without verifying it.

For a pause, offer a short checkpoint the user can keep; do not silently save new
personal context. On resuming, use accessible context and ask only for missing details.

## 5. Try one useful task

Choose a small task based on their actual work: prepare a meeting, clarify a project's
next step or capture a decision. Offer the [fictional example](examples/meeting.md) if
they prefer not to use real data. No external writes are needed for the first trial.

Say what was saved, what is only proposed, what remains uncertain and how to resume.
Open a new session with the updated document/folder to check continuity. Do not rely
on automatic chat memory to preserve the complete brain.

## When one file is no longer enough

Offer a private folder structure only if it makes retrieval easier:

| Folder | Purpose |
|---|---|
| `context/` | Profile, responsibilities, collaboration, preferences and source map |
| `projects/` | One short file per meaningful project |
| `decisions/` | Decisions explicitly supported by the user or a responsible source |
| `inbox/` | Provisional findings and unresolved questions |
| `sources/` | Reference index with dates and scope, not raw data |

Use [the project template](templates/project.md). Update `MY_BRAIN.md` into an index
after migration. Never maintain two active copies of the same context. No database,
vector store, background service or global configuration is needed for this structure.
