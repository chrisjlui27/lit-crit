---
name: practice-test
description: Write a UIL Literary Criticism practice set (Part 1 terms/history, Part 2 reading list, or Part 3 unseen passage) in UIL style with a separate answer key. Use when the coach asks for a quiz, practice items, a practice set, or a mock test.
---

Write a practice set for UIL Literary Criticism following `practice/template.md`.

Ask nothing; infer from the request. Defaults: 15 items, Part 1 terms, 15
minutes. Arguments may name a part, a count, a terms batch, a work from the
reading list, a period, or a prize list.

Rules:

- Five options A-E, one correct, distractors plausible and from the same
  category (a meter item's distractors are other meters).
- Match UIL phrasing: short stems, definitions worded as in Harmon's
  *A Handbook to Literature*.
- Part 2 items: draw on `reading-list/2026-2027.md` and the notes files in
  `reading-list/`. Cite page, act/scene, or line. Never invent quotations;
  if the exact text is not in the repo, write the item around a paraphrase
  and tag it `[verify quote]`.
- Part 3 items: use a public-domain passage (pre-1929), quote it in full at
  the top, and ask about form, speaker, devices, and meaning.
- Prize-list and history items: only use facts present in `history/` CSVs or
  notes. If a needed list is empty, say so and write the other items.
- Key: answer, category tag (same vocabulary as `practice/error-logs/README.md`),
  one-line rationale.

Save to `practice/tests/YYYY-MM-DD-<slug>.md` with today's date, then report
the path and item count.
