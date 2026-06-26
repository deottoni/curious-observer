# Session Startup Checklist

Run this sequence at the start of every working session before doing anything else.

- [ ] 1. Read `user/profile.md`
- [ ] 2. Read `system/blueprint.md`
- [ ] 3. Ask which post number or phase we are working on
- [ ] 4. Read `curriculum/roadmap.md` — note the current phase and its methodology skill focus
- [ ] 5. Check `posts/index.md` — confirm which posts are published and which are in progress
- [ ] 6. Confirm which pipeline step we are starting from: Interrogator / Librarian / Auditor / Ghostwriter

---

## Hard Stops
- **Never skip the Interrogator** — no synthesis, no research, no drafting before the hypothesis is sharpened
- **Never initialize the Audio Producer** — it is planned but not active. See `system/agents/audio-producer.md` for the activation checklist.
- **If input is too vague** — do not start the Interrogator's question protocol. First ask for a concrete seed observation.

---

## Starting a New Post
1. Copy `posts/template.md` to `posts/drafts/post-0[N]-[slug].md`
2. Run the Interrogator (sharpen hypothesis)
3. Run the Librarian (whitelist-constrained retrieval)
4. Run the Auditor on all Tier 3 sources
5. Run the Ghostwriter (synthesis → draft)
6. Update `posts/index.md` and the Post Tracker in `curriculum/roadmap.md`

---

## Continuing an In-Progress Post
1. Read the existing draft from `posts/drafts/`
2. Confirm which pipeline step was last completed
3. Resume from the next step
4. Do not restart the Interrogator for a post already in Draft status unless the hypothesis has fundamentally changed

---

---

## End of Session

Before closing, always save a session file at `sessions/YYYY-MM-DD.md`. Use this structure:

```markdown
# Session — YYYY-MM-DD

## What We Did
[Bullet summary of decisions made, files changed, content produced]

## File State at Session End
| File | Status |
|---|---|
| ... | ... |

## Where We're Heading
[Immediate next step — specific enough to orient the next session cold]
```

**Rules:**
- No sensitive personal info, no private details
- Focus on project state and decisions, not conversation transcript
- "Where We're Heading" must be actionable — the next session should be able to start without asking what's next

---

## On Research Papers
Papers and articles are **read online** — never download PDFs locally. The `research/` folder holds only reading notes (markdown). Links to open-access papers live in `curriculum/roadmap.md`.

---

*Version: 1.1 — 2026-06-26. Updated: session-end protocol added, PDF download rule clarified.*
