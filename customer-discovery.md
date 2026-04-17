# Customer Discovery Skill

*customer-discovery · v1.0 · Ayumi Research · CC BY 4.0 · no dependencies*

---

## Purpose

Helps founder agents run customer discovery interviews that surface real problems instead of validation. Addresses the **information-seeking** (70%) and **customer service orientation** (66%) competency deficits identified in startup failure analysis (Szathmári et al., 2024).

## Core Behaviors

When applied, the agent should:

1. **Frame interviews around problems, not solutions.** Never lead with what you're building.
2. **Ask for specific stories, not opinions.** "Tell me about the last time..." beats "Would you..."
3. **Log assumptions before each interview.** What are you trying to confirm? What would falsify it?
4. **Redirect founder enthusiasm.** When the founder pivots to pitching, bring them back to listening.
5. **Challenge weak sources.** "Who did you talk to?" "When was this data collected?"

---

## Interview Template

### Pre-Interview Checklist

**Assumption being tested:**
```
[Write the specific hypothesis you're testing]
Example: "E-commerce founders spend >3 hours/week manually reconciling inventory"
```

**Falsification criteria:**
```
[What evidence would prove this wrong?]
Example: "If 7 of 10 founders say <1 hour/week or use automated tools"
```

**Target interviewee:**
```
[Role, company size, pain point relevance]
Example: "Founder/CEO, 5-50 employee e-commerce, handles operations personally"
```

---

### Opening Script (Problem-Focused)

```
"Hi [Name], thanks for making time. I'm researching [broad problem space, not your solution].
I'd love to understand how you currently handle [specific workflow].

This isn't a sales call — I'm not pitching anything today. I'm trying to understand
whether [problem] is actually painful enough that people are actively trying to solve it.

Can you walk me through the last time you dealt with [specific situation]?"
```

**Key:** Lead with the problem space, explicitly state you're not selling, ask for a specific recent story.

---

### Deep-Dive Questions

**Frequency & Severity:**
- "How often does this happen?"
- "When was the last time?"
- "What did you do to fix it?"
- "How much time/money did that cost?"

**Workarounds:**
- "What are you using right now to handle this?"
- "Show me the spreadsheet/tool/process you've built"
- "What do you hate about your current workaround?"

**Alternatives:**
- "What else have you tried?"
- "Why didn't that work?"
- "What would need to change for you to switch?"

**Validation:**
- "If this disappeared tomorrow, how much would it matter?"
- "What's the consequence of not solving this?"

---

### Red Flags (Agent Should Intervene)

| Founder Behavior | Agent Response |
|-----------------|----------------|
| "Would you use..." | "Ask for a story instead: 'Tell me about the last time...'" |
| Pitching the solution | "We're here to listen, not to sell. What's their actual problem?" |
| Leading questions | "That assumes X is true. Ask what they actually do." |
| Small sample size | "One friend isn't data. Who else have you talked to?" |
| Vague answers | "Can you give me a specific example from last week?" |

---

## Post-Interview Log

```markdown
## Interview #[N] — [Date]

**Interviewee:** [Role, company, context]
**Assumption tested:** [From pre-interview]
**Result:** CONFIRMED / REFUTED / MIXED

**Key quotes:**
- "[Direct quote about problem]"
- "[Direct quote about current workaround]"

**Surprising insights:**
- [What did you learn that you didn't expect?]

**Follow-up questions:**
- [What do you need to ask in the next interview?]

**Action:**
- [ ] Update assumption tracker
- [ ] Schedule follow-up interview
- [ ] Pivot assumption based on evidence
```

---

## Agent Triggers

**Apply this pattern when:**
- Founder says "I think customers want..."
- Founder mentions talking to "a few people" without specifics
- Team is building features without recent customer conversations
- Someone cites a source older than 6 months
- Founder is excited about validation without falsification attempts

**Response pattern:**
1. Note the claim, don't validate it
2. Ask for the source: "Who did you talk to?"
3. Ask for specificity: "What exactly did they say?"
4. Suggest falsification: "What would prove you wrong?"
5. Offer the interview template if none exists

---

*Part of the Founder Agent Kit. Pairs with the Fonda personality (SOUL.md). References: see `references/RESEARCH.md`.*
