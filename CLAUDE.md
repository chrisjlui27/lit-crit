# Lit Crit — UIL Literary Criticism coaching workspace

This repo is a coach's planning workspace for the Texas UIL Literary Criticism
contest (high school, 2026-27 season). It holds the season plan, study tracks,
practice materials, and progress trackers. There is no application code.

## What lives where

| Path | Purpose |
|---|---|
| `season/season-plan.md` | Phased plan Sept -> State, with weekly cadence and milestones |
| `season/calendar.md` | Key dates for this season (fill in from the official UIL calendar) |
| `contest/format.md` | Exam structure, scoring, advancement, and test-taking strategy |
| `reading-list/2026-2027.md` | This year's novel / drama / poet, editions, and study notes |
| `terms/` | Literary-terms track (the Part 1 glossary), batched by week |
| `history/` | Literary-history and Nobel / Pulitzer track |
| `practice/` | Practice-test template, per-test answer keys, error logs, score tracker |
| `essay/` | Tie-breaker essay rubric, prompts, and model paragraphs |
| `team/` | Roster template and individual goal sheets (no real student data in git) |
| `weekly/` | Meeting agenda template and dated agendas |

## Conventions

- One markdown file per artifact. Dated files use `YYYY-MM-DD-slug.md`.
- Trackers are CSV so they can be opened in Sheets. Keep headers stable.
- Never commit student names, IDs, grades, or contact info. Use initials or
  codes in trackers, and keep the real roster outside the repo.
- Practice items should be written in the UIL style: a stem, five options
  (A-E), one correct answer, and a short rationale in the key.
- When writing items about the reading-list works, cite the required edition's
  page or line so students can check. Do not invent quotations; if the exact
  text is not at hand, write the item around a paraphrase and mark it
  `[verify quote]`.
- Anything pulled from memory about UIL rules or dates is marked `[verify]`
  until checked against the current UIL Constitution & Contest Rules (Section
  940), the Literary Criticism Handbook, or the official UIL calendar.

## Facts about the contest (verify each season)

- 90-minute written exam, 65 multiple-choice items plus a tie-breaker essay.
- Part 1: 30 items, 1 pt each. Literary terms and literary history, including
  roughly 8 items from the Nobel (Literature) and Pulitzer (Fiction, Poetry,
  Drama) recipient lists.
- Part 2: 20 items, 2 pts each. The annual reading list.
- Part 3: 15 items, 2 pts each. Unseen passages; ability in literary criticism.
- Part 4: essay on a short passage. Not scored except to break ties; judged on
  response to the prompt, depth of analysis, then quality of expression.
- Maximum score 100. No deduction for wrong answers `[verify]`, so students
  should answer every item.
- Part 1 terms come from the UIL glossary, which is based on Harmon's
  *A Handbook to Literature*.

## Skills

- `/practice-test` writes a practice set (any part, any length) in UIL style
  with a separate answer key.
- `/weekly-plan` drafts next week's meeting agenda from the season plan and the
  latest error logs.
