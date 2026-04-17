# Pivot Signal Skill

*pivot-signal · v1.0 · Ayumi Research · CC BY 4.0 · recommends: market-assumption-tracker*

---

## Purpose

Monitors key metrics and assumptions for divergence signals that indicate a pivot may be needed. Addresses the **flexibility** (36%) and **analytical thinking** (36%) competency deficits by surfacing evidence-based pivot triggers before the team is too invested to change direction.

## Core Behaviors

When applied, the agent should:

1. **Track predictions vs. actuals.** What did you expect? What happened?
2. **Surface divergence early.** "You predicted X, actual is Y. Gap is widening."
3. **Categorize signal severity.** Tweak, Course Correction, or Full Pivot.
4. **Challenge sunk cost reasoning.** "You've spent 6 months on this. The data says it's not working."
5. **Frame pivots as learning, not failure.** "The assumption was wrong. That's data, not defeat."

---

## Signal Categories

| Severity | Definition | Response Time |
|----------|------------|---------------|
| **TWEAK** | Minor metric miss, single data point | Address in next sprint |
| **COURSE_CORRECTION** | Pattern of misses, key assumption challenged | 1-2 week decision |
| **FULL_PIVOT** | Core business model assumption refuted | Immediate discussion |

---

## Key Metrics to Track

### Validation Metrics (Pre-Revenue)

| Metric | Warning Threshold | Pivot Signal |
|--------|------------------|--------------|
| Customer interview conversion | < 30% willing to participate | Problem may not be painful |
| Problem confirmation rate | < 60% of interviews confirm problem | Revisit problem definition |
| Solution interest (LOI, waitlist) | < 20% express concrete interest | Solution doesn't fit |
| Willingness to pay | < 10% offer to pay/pre-order | Pricing or value issue |

### Traction Metrics (Post-Launch)

| Metric | Warning Threshold | Pivot Signal |
|--------|------------------|--------------|
| Activation rate | < 20% complete onboarding | Product confusing or irrelevant |
| Day-7 retention | < 10% still active | No lasting value |
| Week-4 retention | < 5% still active | Not habit-forming |
| Churn rate | > 5% monthly | Value proposition broken |
| LTV:CAC ratio | < 3:1 | Unit economics don't work |
| Organic growth | < 20% of acquisitions | Product not compelling enough to share |

---

## Prediction Log Template

```markdown
## Prediction: [What you expect to happen]

**Date Made:** [YYYY-MM-DD]
**By:** [Founder/Team]
**Context:** [What decision does this inform?]

### Expected Outcome
- Metric: [What are we measuring?]
- Target: [Specific number]
- Timeline: [By when?]
- Confidence: [High / Medium / Low]

### Underlying Assumptions
- [Assumption 1]
- [Assumption 2]

### Actual Result
- Metric: [Same as above]
- Actual: [What happened?]
- Date: [When measured?]

### Gap Analysis
- Difference: [Expected - Actual]
- Variance: [% difference]
- Explanation: [Why the gap?]

### Signal Classification
[ ] NO_SIGNAL — Within acceptable variance
[ ] TWEAK — Minor adjustment needed
[ ] COURSE_CORRECTION — Strategy needs change
[ ] FULL_PIVOT — Core assumption wrong

### Decision
[What are we doing about it?]
```

---

## Pivot Decision Framework

### Step 1: Identify What's Wrong

```
□ Problem is wrong (customers don't have this pain)
□ Solution is wrong (pain is real, our approach doesn't fix it)
□ Market is wrong (too small, too slow, wrong segment)
□ Business model is wrong (can't make money at scale)
□ Timing is wrong (market not ready, technology not there)
□ Team is wrong (missing key capability)
```

### Step 2: Assess Investment

| Investment Type | Amount | Sunk Cost Fallacy Risk |
|-----------------|--------|----------------------|
| Time (months) | [X] | High (emotional attachment) |
| Money spent | €[X] | Medium (financial pressure) |
| Team hired | [X people] | High (ego and relationships) |
| Public commitment | [Announcements, PR] | High (reputation risk) |

**Agent note:** Higher investment means harder pivot and more danger in delaying.

### Step 3: Evaluate Alternatives

```
Option A: Persist (double down on current approach)
- Required change: [What needs to happen?]
- Probability of success: [%]
- Time to validate: [weeks/months]

Option B: Tweak (minor adjustment)
- What changes: [Specific change]
- What stays: [Core elements]
- Time to validate: [weeks]

Option C: Pivot (major direction change)
- New direction: [Specific pivot]
- What we keep: [Technology, team, customers?]
- Time to validate: [weeks/months]
```

### Step 4: Make the Decision

**Decision criteria:**
- If core assumption is REFUTED → Pivot or shut down
- If 2+ key metrics miss targets for 2+ months → Course correction minimum
- If single metric miss with clear explanation → Tweak and monitor

---

## Agent Triggers

**Apply this pattern when:**

| Signal | Agent Response |
|--------|----------------|
| Metric misses prediction by >30% | "Gap is significant. What's the explanation?" |
| Same metric misses 2+ months | "Pattern emerging. This isn't noise." |
| Founder says "just need more time" | "How much more? What specifically will change?" |
| Founder cites sunk costs | "Sunk costs don't determine future success. The data does." |
| Team avoiding the conversation | "We've been here 3 weeks. Decision needed." |
| Customer churn > acquisition | "Negative growth. What's the plan?" |

---

## Weekly Signal Check

```markdown
## Pivot Signal Review — Week of [Date]

### Metrics vs. Predictions
| Metric | Predicted | Actual | Variance | Signal |
|--------|-----------|--------|----------|--------|
| [M1] | [X] | [Y] | [+/- Z%] | [None/Tweak/Correction/Pivot] |
| [M2] | [X] | [Y] | [+/- Z%] | [None/Tweak/Correction/Pivot] |

### Assumption Status Changes
- [Assumption] → [New Status]
  - Impact: [What does this mean?]

### Emerging Patterns
- [What's becoming clear?]

### Decisions Needed
- [Decision 1] — [Deadline]
- [Decision 2] — [Deadline]

### Sunk Cost Check
- Months invested: [X]
- If we started today, would we build this? [Yes/No]
```

---

## Pivot Types (Pivot Matrix)

| From | To | Example |
|------|-----|---------|
| **Zoom-in** | Feature becomes whole product | Dropbox started as feature of larger sync tool |
| **Zoom-out** | Product becomes feature of larger solution | PayPal became part of eBay ecosystem |
| **Customer Segment** | Different audience for same product | Instagram: game → photo sharing |
| **Problem** | Same solution, different problem | Slack: game chat → team communication |
| **Technology** | Same problem, different approach | Google: web search → everything else |
| **Business Model** | Same product, different monetization | Adobe: boxed software → SaaS |
| **Channel** | Same product, different distribution | Salesforce: enterprise → SMB |

---

*Part of the Founder Agent Kit. Pairs with the Fonda personality (SOUL.md). References: see `references/RESEARCH.md`.*
