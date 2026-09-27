# Literary terms track (Part 1)

Authority: *A Handbook to Literature*, 12th ed., Harmon. Items are worded
from its definitions and the key cites its page numbers.

## Files

- `tested-terms-2009-2026.csv`: every Part 1 term item from 2009 through
  the 2026 State meet (3,646 rows): season, meet, correct answer, and the
  four distractors. Parsed from UIL's master list in `resources/`.
- `most-tested-terms.md`: frequency tiers built from that CSV. The 221
  terms tested five or more times cover about 68% of all items; adding the
  138 tested three or four times covers about 81%.
- `glossary.csv`: the full Harmon-based glossary, to be filled in with
  `term,definition,example,batch` as the season goes. Start empty.

## Batching for Monday q-time

About 18 terms a week, one Monday block each, twelve batches to cover
Tier 1 by mid-January:

1. Batches 1-12: Tier 1 in frequency order (top of `most-tested-terms.md`),
   but pull each term's family in with it (all the rhyme types together,
   all the sonnet types together, all the feet together).
2. Batches 13-20 (Jan-Mar): Tier 2, then Tier 3.
3. From March: error-log terms only.

Each batch handout: term, Harmon's definition in one sentence, one example
line (from Bradstreet or Hawthorne when possible, so it does double duty).

## Item styles seen in Part 1

- Definition to term: the most common. Harmon's wording, sometimes with
  his examples ("goodest for best, hern for hers").
- NOT items: "Not a form of poetry considered to be a pattern poem is..."
  Four options belong to the family; one does not.
- Distinctions within a family: metonymy vs. synecdoche, feminine vs.
  masculine vs. compound rhyme, Italian vs. Shakespearean vs. Spenserian
  sonnet, Edwardian vs. Georgian vs. Victorian.

## The families that recur

Meter and scansion; stanza and fixed forms; rhyme types; sound devices;
figures of speech; repetition schemes; narrative terms; drama terms; period
and group names; word-error terms; classical sets. The full lists are at
the bottom of `most-tested-terms.md`.
