# Learning Record Format

Learning records live in `./learning-records/` and use sequential numbering: `0001-slug.md`, `0002-slug.md`, etc. Create the directory lazily — only when the first record is written.

They are the equivalent of architecture decision records: they capture non-obvious understanding reached, misconceptions corrected, and prior knowledge established — the things that steer future sessions and set the zone of proximal development.

## Template

```md
# {Short title of what was understood or corrected}

{1-3 sentences: what is now understood (or what misconception was corrected), and why it changes what to teach next.}
```

That is the whole format. A record can be a single paragraph. The value is recording *that* this is now understood and *why* it changes the next move — not in filling out sections.

## Optional sections

Include only when they add value:

- **Status** frontmatter (`active | superseded by LR-NNNN`) — when a later understanding replaces an earlier one.
- **Evidence** — how the user demonstrated the understanding (explained it cold, predicted correctly, corrected their own earlier account). Useful when the claim might be revisited.
- **Implications** — what this unlocks or rules out next.

## When to write one

Write a record when any of these is true:

1. **The user demonstrated genuine understanding of something non-trivial** — they passed an understanding-test: explained it cold in their own words, or predicted correctly from the model. Not mere exposure. This sets a new floor for what to teach next.
2. **A misconception was corrected** — the user believed something wrong and now sees why. These are the highest-value records: they predict future stumbling blocks for related topics.
3. **The user disclosed prior knowledge** — "I already understand X." Record it, and the depth claimed, so future sessions don't re-explain it.
4. **The mission shifted** — the user discovered they care about something different. Cross-link to `MISSION.md` and update it.

### What does *not* qualify

- Material merely covered. Coverage is not understanding. Wait for evidence.
- Anything already captured tersely in `GLOSSARY.md`. Don't duplicate.
- Session activity logs. Records are decision-grade insights, not a journal.

## Supersession

When a later record contradicts an earlier one (understanding deepened or corrected), mark the old one `Status: superseded by LR-NNNN` rather than deleting it. How the understanding evolved is itself useful signal.
