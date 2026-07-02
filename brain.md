# Melina

This file loads at the start of every Claude session. Read it before doing anything else.

## Session start

1. Read `company.md` — this tells you who you're working for and what's currently active.
2. If the task involves writing anything externally — emails, posts, announcements — read `brand.md` first.

## First-time check

This brain ships empty. At the start of a new session, open `company.md` and look for this marker:

```
<!-- NOT CONFIGURED -->
```

If it's there, the brain hasn't been set up. Say exactly this, once:

> *"This brain isn't configured yet. Say 'set up the brain' and I'll walk you through it in about 5 minutes."*

Don't start setup until the user agrees. Don't repeat the offer in the same session.

If the user says **"set up the brain"** at any time, open `SETUP.md` and follow it from the top.

## Tone and behaviour

- Follow the communication style in `brand.md` for anything written externally.
- Match the directness and precision of Melina's voice — no filler, no preamble.
- One clear question instead of guessing when intent is ambiguous.

## Capturing ideas

The `capture/inbox.md` file is a raw dump — the user puts anything there without organising it.

Don't touch it unless asked. When the user says **"process the inbox"**:

1. Read everything in `capture/inbox.md`.
2. Group related items.
3. Clean up each one — clear language, not AI-sounding.
4. Show the user the plan: what goes where and why.
5. Wait for confirmation before filing anything.
6. File each item into the right folder:

| Content type | Folder |
|---|---|
| Active work with a finish line | `active/` |
| A decision made, with reasoning | `decisions/` |
| Knowledge the team will look up again | `knowledge/` |
| Reference material or links | `library/` |

7. After filing, reset `capture/inbox.md` to its default state — header only, no old notes.

## Logging decisions

When a decision is discussed or made, file it in `decisions/` with a dated filename:

```
decisions/2026-06-29-chose-postgres-over-mongo.md
```

Every decision file must include: what was decided, why, what was considered and rejected, who was involved, and the date. Decisions are never deleted — only archived.

## Managing projects

Active work lives in `active/`. Use dated filenames:

```
active/2026-06-29-rebrand-project.md
```

When a project finishes or pauses, move it to `archive/`. Confirm the move with the user before doing it. Never delete.

## Team knowledge

The `team/` folder holds team member profiles. When the user mentions a new hire, role change, or departure, update `team/roster.md` and confirm what changed.

## Updating the brain

When the user tells you something new about the company — new product, new hire, pivot, partnership — update `company.md` directly and confirm what changed.

## The rule before any file operation

Before moving, overwriting, or deleting any file: state exactly what you're about to do and wait for explicit confirmation. No exceptions.
