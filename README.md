# Founder Agent Kit

A personality and skillset for building AI agents that help founders validate ideas and discover markets.

---

## What This Is

**Fonda**, a skeptical customer advocate who asks hard questions before you spend money. Not a chatbot. Not a co-founder surrogate. A consistent, methodical presence that introduces productive friction.

---

## What's Included

- **SOUL.md** — Core personality (~5.9KB), including the **Skill Router** (which skill to load when) and the workspace convention for logs
- **skills/** — 4 operational skills:
  - `customer-discovery.md` — Interview frameworks, falsification checklists
  - `data-source-finder.md` — Finding real market data (incl. agent-native API research)
  - `market-assumption-tracker.md` — Hypothesis logging, risk scoring
  - `pivot-signal-skill.md` — When to pivot vs. persevere
- **references/RESEARCH.md** — Research foundation and full bibliography
- **fonda.json** — Machine-readable kit manifest (for agent runtimes)
- **llms.txt** — Agent-discovery index (the llms.txt convention)

---

## How to Use

SOUL.md follows a character-definition convention used by local agent frameworks including Hermes (NousResearch) and OpenClaw. **Copy the whole kit** — SOUL.md plus `skills/` and `references/` — into the runtime; the Skill Router in SOUL.md assumes the skill files sit at `skills/<name>.md` relative to the kit root. Pasting SOUL.md alone still gives you the persona and its questioning behavior, but skill loading degrades to applying the principles from memory (the router says exactly that). Alternatively, paste SOUL.md into any other runtime as a system prompt. The skill files are modular markdown — load them alongside SOUL.md when the matching situation comes up, or keep them as reference.

Artifacts go to the workspace convention in SOUL.md ("Where Things Live") — adjust the `fonda/` root to your runtime's workspace. If the runtime has no file access, keep the logs as structured chat output instead; don't skip them.

---

## Disclaimer

This kit provides structured inquiry, not business advice. The agent challenges assumptions and demands evidence. It does not make decisions for you.

**Use cases:**

- Pre-launch validation
- Customer discovery guidance
- Market research assistance
- Pivot decision support

**Not for:**

- Financial advice
- Legal compliance
- Medical or regulated industries
- Replacing human judgment

If you want a cheerleader, this isn't it. The value is friction, not answers.

---

## License

CC BY 4.0. Use, modify, redistribute. Attribution required.

---

## Built By

Ayumi Research, a small lab running applied AI experiments.

[research.ayumi.town](https://research.ayumi.town)
