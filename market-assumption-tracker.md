# Market Assumption Tracker Skill

*market-assumption-tracker · v1.0 · Ayumi Research · CC BY 4.0 · no dependencies*

---

## Purpose

A structured system for logging, tracking, and updating business hypotheses. Addresses the **analytical thinking** (36%) and **information-seeking** (70%) competency deficits by forcing explicit assumption declaration and evidence-based updates.

## Core Behaviors

When applied, the agent should:

1. **Extract assumptions from conversations.** "That assumes X is true. Let's log it."
2. **Categorize by risk.** Which assumptions, if wrong, kill the business?
3. **Track evidence status.** Unvalidated → Partially Validated → Confirmed → Refuted.
4. **Surface stale assumptions.** "This hypothesis is 3 months old with no new evidence."
5. **Challenge confirmation bias.** "You've logged 4 confirmations and 0 falsification attempts."

---

## Assumption Log Structure

```markdown
# Assumption: [Clear, testable statement]

**Category:** [Market / Problem / Solution / Business Model / Go-to-Market]
**Risk Level:** [CRITICAL / HIGH / MEDIUM / LOW]
**Created:** [YYYY-MM-DD]
**Last Updated:** [YYYY-MM-DD]

## Hypothesis
[What do you believe is true?]

## Why It Matters
[If this is wrong, what breaks?]

## Evidence For
- [Source, date, sample size]
- [Direct quote or data point]

## Evidence Against
- [Source, date, sample size]
- [Contradictory data point]

## Falsification Test
[What would prove this wrong?]

## Status
[ ] UNVALIDATED — No evidence yet
[ ] TESTING — Active validation in progress
[ ] PARTIALLY_VALIDATED — Some evidence, needs more
[ ] CONFIRMED — Strong evidence, low uncertainty
[ ] REFUTED — Evidence disproves hypothesis

## Notes
[Context, surprises, follow-up needed]
```

---

## Risk Levels

| Level | Definition | Action Required |
|-------|------------|-----------------|
| **CRITICAL** | If wrong, business model fails | Validate within 2 weeks |
| **HIGH** | If wrong, major pivot needed | Validate within 1 month |
| **MEDIUM** | If wrong, feature/strategy adjustment | Validate within 3 months |
| **LOW** | If wrong, minor optimization | Validate when convenient |

**Critical assumptions examples:**
- "Customers will pay €X/month for Y"
- "Target market size is >Z addresses"
- "Distribution channel A is accessible"

**Low assumptions examples:**
- "Primary user interface color preference"
- "Feature priority ordering"

---

## Agent Triggers

**Apply this pattern when founder says:**

| Phrase | Extracted Assumption |
|--------|---------------------|
| "Customers will..." | "Assumption: Customers will [behavior]" |
| "The market is..." | "Assumption: Market size/behavior is [X]" |
| "Obviously, people need..." | "Assumption: [Need] is obvious and validated" |
| "We can charge..." | "Assumption: Price point [X] is acceptable" |
| "Competitors don't offer..." | "Assumption: Competitive landscape is [X]" |

**Agent response:**
> "That's an assumption. Let's log it. How are we testing that?"

---

## Weekly Review Template

```markdown
## Assumption Review — Week of [Date]

### New Assumptions This Week
- [List]

### Status Changes
- [Assumption] → [New Status]
  - Evidence: [What changed?]

### Stale Assumptions (>30 days, still unvalidated)
- [Assumption] — [Days old]
  - Action: [Test plan or deprioritize]

### Critical Assumptions Still Unvalidated
- [Assumption] — [Days old]
  - Risk: [Why this matters]
  - Next step: [Specific test]

### Confirmation Bias Check
- Assumptions with only confirming evidence: [List]
- Assumptions with no falsification attempts: [List]
```

---

## Evidence Quality Scoring

| Source Type | Weight | Notes |
|-------------|--------|-------|
| Direct customer interview (paid user) | 5 | Highest quality |
| Direct customer interview (non-user) | 4 | Strong, but not behavioral |
| Survey (n > 100, representative) | 3 | Quantitative, watch for bias |
| Survey (n < 50, convenience sample) | 2 | Weak, directional only |
| Industry report (reputable source) | 2 | Secondary data |
| Founder's friend/opinion | 1 | Anecdotal, not evidence |
| Google search / blog post | 0 | Not evidence |

**Agent rule:** If an assumption's total evidence score is < 5, mark as UNVALIDATED regardless of founder confidence.

---

## Decision Gates

**Before building a feature:**
- [ ] Problem assumption: CONFIRMED or PARTIALLY_VALIDATED
- [ ] Solution assumption: At least TESTING
- [ ] At least 3 customer interviews logged

**Before raising funding:**
- [ ] Market size assumption: CONFIRMED
- [ ] Pricing assumption: PARTIALLY_VALIDATED or better
- [ ] Distribution assumption: TESTING or better
- [ ] All CRITICAL assumptions validated or actively testing

**Before hiring:**
- [ ] Revenue model assumption: CONFIRMED
- [ ] Customer acquisition assumption: PARTIALLY_VALIDATED or better

---

*Part of the Founder Agent Kit. Pairs with the Fonda personality (SOUL.md). References: see `references/RESEARCH.md`.*
