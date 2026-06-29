# Index Second Brain

A free, open-source company knowledge starter kit for Claude.

Download the folder, point Claude at it, and you have a company brain that reads, writes, and organises everything — no accounts, no API keys, no setup beyond Claude Desktop.

> Built by [Index Brain](https://index.brain) · MIT licensed · Free forever

---

## What this is

A company knowledge system built for teams. Your decisions, processes, active projects, and institutional knowledge — all in one folder Claude can read, write, and organise.

Claude reads everything in context and works like a team member who actually remembers what was agreed last month.

---

## Requirements

- **Claude Desktop** (macOS Apple Silicon or Windows)
- A **paid Claude plan** — Pro, Max, Team, or Enterprise
- Nothing else. No API keys. No accounts. No installs.

---

## Quick start

1. **Download** this folder (click "Code → Download ZIP" on GitHub) and move it somewhere permanent — not your Downloads folder.
2. **Open Claude Desktop**, go to the Cowork tab, and point a session at this folder.
3. **Say "run onboarding."** Claude asks you a handful of questions about your company and fills in the two foundation files for you. Takes about 5 minutes.
4. **Start working.** Drop ideas in `01-ideas/inbox.md`. Say "process the inbox" when you're ready to organise them.

---

## What's inside

```
index-second-brain/
├── README.md              you are here
├── claude.md              instructions Claude reads at the start of every session
├── ONBOARDING.md          the one-time company setup interview Claude runs for you
├── about-company.md       who you are as a company (blank, filled by onboarding)
├── voice-and-brand.md     how your company writes and sounds (blank, filled by onboarding)
├── 01-ideas/
│   └── inbox.md           dump raw thoughts here, unsorted
├── 02-projects/           active work with a finish line
├── 03-decisions/          key decisions with reasoning, dated and kept forever
├── 04-wiki/               evergreen knowledge the team looks things up in
├── 05-resources/          reference material you collect
└── 06-archive/            finished or paused work, out of the way
```

Folders are numbered so they sort in the order you actually use them: capture → process → reference → archive.

---

## How it works

**Drop raw notes in the inbox**

```
01-ideas/inbox.md
```

Paste anything — a rough idea, a link, a decision you just made, something a customer said. Don't organise it. Just dump it.

**Say "process the inbox"**

Claude reads everything, groups related notes, cleans each one up, and files them into the right folder. It shows you the plan before moving anything.

**Find anything later**

Every decision lives in `03-decisions/` with its reasoning and date. Every piece of evergreen knowledge lives in `04-wiki/`. Projects move to `06-archive/` when they're done — nothing gets deleted.

---

## What onboarding does

This brain ships blank on purpose. The first time you connect it, Claude notices the foundation files are empty and offers to set them up. Say yes and it interviews you — your company name, what you build, who you serve, your team size, your current focus, and how your company writes. No form to fill in. Everything is skippable.

When onboarding is done, every Claude session starts with full context: who you are, what you're building, what's active, and how to sound like you.

---

## The two foundation files

| File | What it does |
|---|---|
| `about-company.md` | Tells Claude who it's working for — company, team, stage, current focus |
| `voice-and-brand.md` | Tells Claude how to write in your company's voice |

These are the difference between a brain that knows your company and a folder full of files. Fill them once, update them when things change.

---

## Decisions get their own folder

Most knowledge systems treat decisions like any other note. This one doesn't.

Decisions go in `03-decisions/` with a dated filename and their reasoning captured — what was decided, why, what alternatives were considered, who was involved. Six months later when someone asks "why did we pick X over Y?", the answer is there.

---

## The safety rule

Before Claude moves, overwrites, or deletes any file, it shows you the plan first and waits for your go-ahead. Always.

---

## License

MIT. Free to use, change, share, and build on. See `LICENSE`.

---

Made by [Index Brain](https://index.brain)
