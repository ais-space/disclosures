# Security Policy

## Coordinated disclosure

This repository publishes security findings reported privately to maintainers.
We follow coordinated disclosure with a 90-day embargo by default:

1. A finding is reported privately to the maintainer (email, with a PGP key
   on request). The report contains: what, where (file:line), mechanism in
   plain words, history, affected versions, fix suggestion, PoC status
   (executed or honestly marked conceptual), and proposed embargo terms.
2. Details stay private until the embargo ends AND the fix is released
   (or the embargo expires per agreement). The embargo end is guidance for
   public disclosure, not an automatic permission — next steps are agreed
   with the maintainer based on the fix status.
3. Severities in reports are preliminary estimates; the final call belongs
   to the maintainer.

## What lands here, and when

- **Before the embargo ends:** `disclosures/pending.md` only — project,
  number of reports, send dates, embargo ends. No titles, no files, no
  severities, no CWE identifiers. Even a finding title tells an attacker
  where to look.
- **After the embargo ends:** the full report file under
  `disclosures/published/<project>/<id>.md`, plus a link to the vendor fix
  or advisory.

## Scope

- In scope: publishing our own coordinated-disclosure reports.
- Out of scope: receiving third-party reports about this repository
  (there is no code here to be vulnerable in — only report texts).
  If you believe a *published* report contains an error, contact
  founder@ais-platform.dev.

## Contact

Vladimir Sitnikov — founder@ais-platform.dev —
[LinkedIn](https://www.linkedin.com/in/vladimir-sitnikov-3a61433b5).
