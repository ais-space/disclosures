# Contributing

This repository is a disclosure portfolio, not a codebase. The only
acceptable changes are:

1. **Status moves** on the `disclosures/pending.md` board
   (`preparation` → `in work` → `embargo since DATE` → `published`),
   updated when the underlying work changes state — never ahead of it.
2. **New pending rows** when reports are sent (aggregate data only:
   project, count, dates, embargo end — no technical details, ever,
   before the embargo ends).
3. **Publications** after an embargo ends AND the fix is released
   (or the embargo expires per agreement with the maintainer):
   full report files under `disclosures/published/<project>/`,
   plus links to the vendor fix or advisory, plus a CHANGELOG entry.

Hard rules (no exceptions):

- No finding details, file names, severities, or CWE identifiers outside
  `disclosures/published/` — and there, only post-embargo.
- No finding COUNTS anywhere public before publication (not in rows,
  changelogs, or commit messages): statuses and embargo dates show the work,
  numbers appear only with the published reports.
- The embargo end is guidance for agreement, not an automatic permission:
  confirm with the maintainer before publishing.
- Severities in published reports stay preliminary; the final call is
  always the maintainer's (see the per-bug report template).
- Every published report cross-links the vendor fix or advisory when one
  exists.
