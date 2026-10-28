# Verdict: FIX-FIRST

Blocking: altered CC BY license text. Also fix the major routing, evidence-handling, and credibility defects below before publication.

Audited all 11 tracked files, `git log --oneline -3`, and `HEAD~1..HEAD` at `f09e69a`. Findings include pre-existing defects. Paths below abbreviate `skills/` as `s/` and `references/RESEARCH.md` as `R`.

| file:line | issue | severity | suggested fix |
|---|---|---|---|
| LICENSE:250,348; fonda.json:6 | Section 3(a)(4) missing; Section 8 replaced with jurisdiction/contract terms, contradicting CC-BY-4.0 labeling throughout. | BLOCKER | Restore [canonical license](https://creativecommons.org/licenses/by/4.0/legalcode.en). |
| SOUL.md:87; fonda.json:22; s/customer-discovery.md:129 | Router misses discovery triggers: unsupported wants, feature-building without interviews, validation excitement. | MAJOR | Align trigger sets. |
| SOUL.md:91,93; fonda.json:14 | No-match means “none” versus default discovery; “first” undefined; one-skill rule prevents required tracker updates (s/customer-discovery.md:119). | MAJOR | Define priority, no-match, sequential handoffs. |
| SOUL.md:90; fonda.json:43; llms.txt:11 | Index omits persist-or-pivot trigger; prediction creation and weekly reviews lack explicit routing. | MINOR | Add proactive triggers everywhere. |
| SOUL.md:99; README.md:29; llms.txt:17 | Pasting SOUL alone provides neither skill files nor their root; logging assumes filesystem access. | MAJOR | Specify installation root, read/write capabilities, unavailable-file fallback. |
| SOUL.md:102,104,106; fonda.json:49 | Post-interview versus during-conversation timing; shared weekly file lacks merge rules; manifest omits filename patterns. | MINOR | Define draft/finalize, append/update, unique names and ISO weeks. |
| s/market-assumption-tracker.md:132,140 | Score <5 forces UNVALIDATED even when REFUTED/TESTING; anecdotes accumulate; analytics/official records and n=50–100 unspecified. | MAJOR | Separate status, evidence direction, quality and independence. |
| s/customer-discovery.md:132; s/data-source-finder.md:210,283 | Age triggers use six months, three years, five years. | MINOR | Define domain-specific freshness consistently. |
| s/pivot-signal-skill.md:39,46,147; CHANGELOG.md:7 | Unsourced thresholds called “calibrated”; two-month rules remain outside traction caveat. | MAJOR | Label heuristics; calibrate all triggers by cohort/cycle. |
| s/pivot-signal-skill.md:163 | Churn versus acquisition lacks matching units/time windows. | MINOR | Compare lost/new customer counts per period. |
| s/pivot-signal-skill.md:202,204,206 | Examples contradict categories: product change ≠ segment; diversification ≠ technology; enterprise→SMB ≠ channel. | MAJOR | Replace with sourced, definition-matching examples. |
| SOUL.md:93,143; R:99,105 | Failure-only narratives cannot establish what kills “most startups” or universal founder deficiencies. | MAJOR | Bound conclusions to sample; distinguish design hypotheses. |
| R:112,113; s/market-assumption-tracker.md:9; s/pivot-signal-skill.md:9 | Competency mappings disagree. | MINOR | Reconcile primary/secondary mappings. |
| CHANGELOG.md:6; s/data-source-finder.md:105,111,197 | BRIS is not renamed EBR; coverage omits EEA; “all free” overstates document access; OpenView-only pointer remains. | MINOR | Correct service description, costs and benchmark pointer. |
| README.md:15; CHANGELOG.md:10 | SOUL is 5,885 bytes; July “initial” history predates July (April commit). | NIT | Correct size and chronology. |

Claim checks: **Szathmári passes numerically**: 35/33/19/18/18 of 50 = 70/66/38/36/36. These appear in Results/Table 2, **not the abstract**, which names the five deficits. [Paper](https://www.frontiersin.org/journals/psychology/articles/10.3389/fpsyg.2024.1299135/full).

**High Alpha/OpenView passes for 2024**: High Alpha explicitly continued OpenView’s report in partnership; cite the edition rather than imply permanent co-authorship. [Publisher](https://www.highalpha.com/2024-saas-benchmarks-survey).

**BRIS is a valid replacement resource, not a rename**: operating since 2017 across EU/EEA; EBR closed in 2026. [EU](https://e-justice.europa.eu/topics/registers-business-insolvency-land/business-registers-search-company-eu/general-information-find-company_en), [Estonian registry](https://ariregister.rik.ee/eng/ebr/register).

All listed runtime files exist; kit/skill versions agree; tables are structurally intact. SOUL identifies ordinary routing/log destinations, but overlapping tasks and installation remain ambiguous.
