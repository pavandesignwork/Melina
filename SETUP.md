# Brain Setup

Run this when the user says "set up the brain" or agrees to the first-session offer.

This is a one-time process. Goal: fill `company.md` and `brand.md` with real information and remove the `<!-- NOT CONFIGURED -->` marker from each. Takes about 5 minutes.

---

## How to run it

This is a conversation, not a form. Follow these rules:

- **Ask 2–3 questions at a time.** Wait for answers before continuing.
- **Plain language throughout.** No jargon unless the user uses it first.
- **Everything is skippable.** If they say "skip" or "not sure", leave it blank and move on.
- **Don't re-ask.** If one answer covers multiple questions, keep going.
- **Reflect back** what you heard after each batch — let them correct you before you write anything.
- **Target: 5 minutes.** If it's taking longer, move faster.

---

## Part 1 — The company

These answers fill `company.md`.

**Ask:**
1. "What's the company called, and what does it do — one sentence?"
2. "Who are your customers? Who are you building this for?"
3. "How big is the team, and what are the main roles?"
4. "Where are you right now — pre-launch, early customers, growing? What's the main thing you're focused on this month?"
5. "What are the one or two most active things the team is working on right now?" — tell them this section goes stale fastest and they should update it whenever things shift.
6. "What tools does the team live in day-to-day? Slack, Notion, GitHub — whatever's relevant."

---

## Part 2 — The brand voice

These answers fill `brand.md`.

**Ask:**
7. "How does your company sound when you write something? Direct and short, or detailed and thorough? Casual or formal?" — if they're unsure, ask them to paste a sentence or two they'd actually send a customer and work from that.
8. "Any words or phrases that feel off-brand — things you'd never say in a company email or post?"
9. "Does the tone stay the same internally with the team as it does externally with customers, or does it shift?"
10. "Do you have a visual identity — logo, brand colours, a style guide?" — optional. If no, skip and remove that section from `brand.md`.

---

## Finishing up

Once you have the answers:

1. Write them into `company.md` and `brand.md`. Replace all placeholder text. Use the user's own words — not polished AI prose.
2. Remove the `<!-- NOT CONFIGURED -->` line from the top of both files.
3. Show the user both finished files: *"Here's what I've written. Does this sound right? Tell me what to change."*
4. Make any corrections they ask for.
5. Tell them setup is done and that they can update either file any time just by telling you — for example: "add to the company profile that we just launched in Europe."

---

## After setup

The brain is live. Next session, Claude reads `company.md` and `brand.md` at session start and has full context. No re-explaining needed.
