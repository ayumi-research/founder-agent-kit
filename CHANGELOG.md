# Changelog

## 1.1.1 — 2026-10-28 (post-adversarial-audit fixes)

- **LICENSE**: replaced with the canonical CC BY 4.0 legal code (the previous copy was an altered draft — missing Section 3(a)(4), Section 8 replaced with outdated jurisdiction wording). BLOCKER from audit.
- **SOUL.md**: router now covers discovery triggers (validation excitement, building without interviews), defines the no-match default (customer-discovery), allows sequential two-skill loads (interview → tracker update), and handles missing skill files honestly.
- **market-assumption-tracker v1.1**: evidence-score rule now gates *confirmation* (≥5 + no significant counter-evidence) instead of silently forcing UNVALIDATED over REFUTED/TESTING; added survey n 50–100 tier; purpose mapped to its primary competency (analytical thinking) only.
- **pivot-signal v1.2**: calibration note now covers BOTH metric tables (thresholds are unsourced self-serve heuristics); pivot-matrix examples replaced with definition-matching shapes (the old ones mixed categories); churn trigger rephrased to matching units; purpose mapped to flexibility + business model literacy.
- **data-source-finder v1.2**: BRIS wording corrected (interconnection system, EU/EEA — not a rename of EBR, which closed); benchmark pointers updated (High Alpha SaaS Benchmarks).
- **references/RESEARCH.md**: one primary competency per skill; scope bound to the 50-failure sample (percentages are from Results/Table 2, not the abstract).
- **README/llms.txt/fonda.json**: installation + solo-mode fallback documented; load_when fields synced with the router.

## 1.1.0 — 2026-10-28

- **SOUL.md**: added **Skill Router** (situation → which skill to load; fixes the bootstrap gap where trigger tables lived only inside unloaded skills) and **Where Things Live** (workspace convention for assumption/interview/prediction/review artifacts).
- **data-source-finder v1.2**: European Business Register → BRIS (EU e-Justice) — renamed service; OpenView SaaS Benchmarks → SaaS Benchmarks Report (High Alpha, with OpenView) — report moved homes; new **Agent-Native Research** section (structured APIs, citation verification via Crossref/OpenAlex).
- **pivot-signal v1.1**: added calibration note — traction-metric thresholds are self-serve/B2C-calibrated; enterprise/sales-led motions must re-derive from own cohort data.
- **New**: `fonda.json` (machine-readable manifest) + `llms.txt` (agent-discovery index).

## 1.0 — 2026 (initial release through the July bibliography fixes)

- Initial kit: Fonda personality, 4 skills, research foundation, bibliography fixes (replaced nonexistent refs, corrected editions).
