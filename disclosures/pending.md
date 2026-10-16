# Pending disclosures

Reports sent, embargo running — plus active engagements. Aggregate only:
no technical details until an embargo ends (see `../SECURITY.md`).

## Lifecycle

Every project row moves through these statuses, in order:

1. `preparation` — the target is scoped (repository, history, license check);
   the audit has not started.
2. `in work` — the audit is in progress.
3. `embargo since DATE` — findings reported to the maintainer, details
   private until the embargo ends AND the fix is released (or the embargo
   expires per agreement).
4. `published` — the row leaves this table; full reports move to
   `published/<project>/` with links to the vendor fix or advisory.

Rules: one row per project, status always current (updated at session
finalization, like HANDOFF). When a project moves to `embargo`, the next
patient is already listed as `preparation` — the board never goes quiet.
Statuses carry no timelines and no scope detail: `in work` says work is
ongoing, nothing more. The Revizor column names the version behind each
report; versions grow over time, and re-checks with newer versions are
available on request.

## Board

**extism (`extism/extism`)**
- **Status:** embargo since 2026-10-16
- **Reports sent:** 2026-10-16
- **Embargo since:** 2026-10-16 (guidance end 2027-01-14)
- **Sir Revizor:** v0.10.1 (Rust findings; language legs to v0.10.7)
- **Notes:** Maintainer replied 2026-10-16: will fix URL-fetch limits + error-code handling; remaining findings declined as minor; release credit promised.

**solady (`Vectorized/solady`)**
- **Status:** in work
- **Reports sent:** — (audit queued)
- **Embargo since:** —
- **Sir Revizor:** v0.10.10 (current; recorded per finding at close)
- **Notes:** Audit in progress since 2026-10-16.
