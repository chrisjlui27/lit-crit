---
name: practice-test
description: Write a UIL Literary Criticism practice set (Part 1 terms/history, Part 2 reading list, or Part 3 unseen passage) in UIL style with a separate answer key. Use when the coach asks for a quiz, practice items, a practice set, a reading check, a Thursday passage, or a mock test.
---

Write a practice set for UIL Literary Criticism following `practice/template.md`.

Ask nothing; infer from the request. Defaults: 8 items, Part 1 terms, for a
10-minute q-time block. Arguments may name a part, a count, a terms batch
or tier, a work or story or poem from the reading list, a period, a prize
list and year window, or "full" for a 65-item test.

Style, from the 2026 Invitational A test in `resources/`:

- The stem is a sentence completed by the correct option: "Rhyme in which
  the rhyming stressed syllables are followed by an identical unstressed
  syllable is". Five options A-E in alphabetical order, one correct.
- Distractors come from the same family as the answer. For terms, take the
  real distractors from `terms/tested-terms-2009-2026.csv` when the term is
  there; the CSV's `distractors` column is the family UIL uses.
- Use NOT items sparingly (about one in eight), bolding **Not**.
- Definitions follow Harmon's *A Handbook to Literature*, 12th ed.

By part:

- Part 1 terms: choose from `terms/most-tested-terms.md` tiers unless a
  batch is named. History and prize items only from facts in `history/`
  files; if the prize CSVs are empty, say so and write terms items instead.
  Respect the meet's prize-year window from `reading-list/2026-2027.md`.
- Part 2: draw on `reading-list/2026-2027.md` and the notes files there.
  Cite page, act/scene, or line. For Bradstreet, print the poem with line
  numbers and write device items on cited lines, as UIL does. Hawthorne and
  Bradstreet may be quoted; *Lost in Yonkers* may not be quoted at length,
  so paraphrase and mark `[verify quote]`. Never invent quotations.
- Part 3: use a public-domain passage (pre-1929), print it in full with
  line numbers every four lines, and ask about the governing device, form,
  rhyme type, theme as a sentence, and which lines carry an idea.

Key: answer, category tag using the vocabulary in
`practice/error-logs/README.md`, one-line rationale, Handbook page if known.

Save to `practice/tests/YYYY-MM-DD-<slug>.md` with today's date, then report
the path and item count.
