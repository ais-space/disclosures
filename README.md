# Disclosures

Independent security findings reported under coordinated disclosure.
Found with Sir Revizor — our closed audit system (static analysis plus manual
review of every finding). Not to be confused with AIS Revizor, the
open-source runtime trace engine: different product, shared name root.
Findings below were reported privately and are published only after
the embargo.

## Structure

- `disclosures/pending.md` — reports sent, embargo running. Aggregate only:
  project, number of reports, send dates, embargo ends. No technical details
  until the embargo ends.
- `disclosures/published/` — full report files, added only after the embargo
  ends AND the fix is released (or the embargo expires per agreement with the
  maintainer). Each published report links the vendor fix or advisory.

## Policy

See [SECURITY.md](SECURITY.md). In short: 90-day coordinated disclosure by
default, details stay private until then, every severity is preliminary and
the final call belongs to the maintainer.

## Status

No published reports yet. First pending entry: extism (5 reports, sent
2026-10-16) — see `disclosures/pending.md`.

## Contact

Vladimir Sitnikov — founder@ais-platform.dev —
[LinkedIn](https://www.linkedin.com/in/vladimir-sitnikov-3a61433b5).

## Order an audit

[![Order an audit](https://img.shields.io/badge/order%20an%20audit-founder%40ais--platform.dev-blue)](mailto:founder@ais-platform.dev?subject=Audit%20request%3A%20%3Cproject%3E)

Need the same treatment for your project? Write in with the repository URL,
the scope (contracts, chains, deadline) and what keeps you up at night.
You get what you see in `disclosures/published/`: every finding with code,
mechanism, history, affected versions, fix suggestion and honest PoC status —
reported privately first, published only after the embargo. No prices here:
every scope gets its own quote. Re-checks of earlier work with newer Revizor
versions are available — the version behind each report is always stated.

## License

Report texts: [CC-BY-4.0](LICENSE).
