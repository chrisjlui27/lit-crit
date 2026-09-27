# Lit Crit — UIL Literary Criticism coaching workspace

This repo is a coach's planning workspace for the Texas UIL Literary Criticism
contest (high school, 2026-27 season). It holds the season plan, study tracks,
practice materials, official UIL resources, and progress trackers. There is
no application code.

## Season facts

- Practice format: four 10-minute q-time sessions a week, Monday-Thursday.
  Mon terms, Tue reading list, Wed history/prizes, Thu unseen passage.
  Full timed tests and essays happen outside q-time.
- Reading list: Hawthorne's short stories (12; only 6 eligible before
  Region), Anne Bradstreet (12 poems plus 77 prose Meditations), Neil
  Simon's *Lost in Yonkers*. Details in `reading-list/2026-2027.md`.
- Dates: Invitational A January 2027 (TBD, via Tabroom); District Lit Crit
  Thu Apr 2, 2027 at Mt. Vernon; Regional Fri Apr 24 at TJC; State May
  16-18 at UT Austin. See `season/calendar.md`.

## What lives where

| Path | Purpose |
|---|---|
| `season/season-plan.md` | Phased plan with the weekly q-time rotation and reading schedule |
| `season/calendar.md` | Meet dates, locations, and milestones counted back from District |
| `contest/format.md` | Exam structure, scoring, essay rules, and strategy (verified against the 2026 Inv A test) |
| `reading-list/` | This year's list, prize-list windows by meet, and a notes file per work |
| `terms/` | Every tested Part 1 term since 2009 as CSV, the frequency tiers, and the glossary to fill |
| `history/` | Literary-history periods, the Nobel and Pulitzer winner CSVs, and per-meet year windows |
| `practice/` | Test template, test logs, error logs, score tracker |
| `essay/` | Tie-breaker essay rubric (UIL's criteria), prompts, Bradstreet prompts |
| `lessons/` | Ten-minute versions of UIL's sample lessons (close reading, devices, meter, sonnets) |
| `resources/` | Official UIL PDFs (2026-27 reading list and Bradstreet addendum, 2026 Invitational A test with key, master list of tested terms, sample lessons) and saved pulitzer.org / nobelprize.org pages the prize CSVs were parsed from |
| `team/` | Goal sheet by student code (no real student data in git) |
| `weekly/` | Agenda template for the Mon-Thu rotation and dated agendas |

## Conventions

- One markdown file per artifact. Dated files use `YYYY-MM-DD-slug.md`.
- Trackers are CSV so they can be opened in Sheets. Keep headers stable.
- Never commit student names, IDs, grades, or contact info. Use codes (S1,
  S2) in trackers and keep the real roster outside the repo. Coaches' and
  coordinators' names stay out too.
- Official UIL documents go in `resources/` as PDFs with descriptive
  names. Derived data (CSVs, summaries) goes in the topic folder and says
  which resource it came from.
- Practice items are written in the UIL style: a stem that reads as a
  sentence completed by the answer, five options A-E, one correct, and a
  key with a one-line rationale and, where possible, a Handbook 12e page.
- When writing items about the reading-list works, cite page, act/scene, or
  line. Do not invent quotations; if the exact text is not at hand, write
  the item around a paraphrase and mark it `[verify quote]`. Hawthorne and
  Bradstreet are public domain and may be quoted at length; Simon is not.
- Anything from memory about UIL rules or dates is marked `[verify]` until
  checked against Section 940 of the Constitution & Contest Rules, the
  Literary Criticism Handbook, or the official UIL calendar.

## Facts about the contest (verified against the 2026 Invitational A test)

- 90-minute exam, 65 multiple-choice items plus a required essay.
- Part 1: 30 items, 1 pt each. About 16 glossary terms, 8 literary-history,
  6 prize/author items. Prize items come only from that meet's year window
  (see `reading-list/2026-2027.md`); the Nobel list is in full at every meet.
- Part 2: 20 items, 2 pts each, on the reading list. Two poems are printed
  with line numbers and get four device items each.
- Part 3: 15 items, 2 pts each, on unseen passages.
- Essay: required. No essay, or no sincere attempt at the topic, means
  disqualification. Judged on following the instructions, critical insight,
  effectiveness, then grammar. Never changes the objective score.
- Maximum objective score 100. No deduction for wrong answers `[verify]`.
- Authority for Part 1: Harmon, *A Handbook to Literature*, 12th ed.; keys
  cite its page numbers.

## Skills

- `/practice-test` writes a practice set (any part, any length) in UIL
  style with a separate key, drawing on the terms CSV and reading-list notes.
- `/weekly-plan` drafts next week's Mon-Thu q-time agenda from the season
  plan, the reading schedule, and the latest error logs.
