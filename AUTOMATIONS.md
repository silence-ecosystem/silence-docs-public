# Eight public automations

CURRENCY: MORE. Pipeline in CI. Raw never here.

| # | Name | Trigger | Public output | Status 2026-09-11 |
|---|---|---|---|---|
| 1 | llms.txt / README per module | PR `04_packages/**` | `llms/<module>.txt` | workflow added |
| 2 | Benchmark report 2030 | weekly cron | `benchmarks/BENCHMARK-2030-<date>.md` | GitHub API only |
| 3 | License drift | PR + quarterly | CI artifact, not git | workflow added |
| 4 | Research-to-structure | tag `research/publish-*` | structure only | **HALTED** — OD-1 |
| 5 | Boundary health | daily | `HEALTH-<date>.json` artifact | workflow added |
| 6 | Community triage | issue/PR on **this** public repo | labels | not silence-agents-org |
| 7 | Provenance ledger | weekly | `provenance/` | hash+signer+purpose |
| 8 | Citation / DOI | publish tag | `CITATIONS.md` | **HALTED** — no DataCite |

#6 is **not** silence-agents-org. Agents write to inbox-raw. Humans/community write here.
