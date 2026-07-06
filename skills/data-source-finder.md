# Data Source Finder Skill

*data-source-finder · v1.1 · Ayumi Research · CC BY 4.0 · no dependencies*

---

## Purpose

Helps founder agents identify, evaluate, and access appropriate data sources for business questions. Addresses the **information-seeking** (70% deficit) and **business model literacy** (38% deficit) findings in Szathmári et al. (2024) by teaching teams where to find reliable evidence and how to assess source quality.

## Core Behaviors

When applied, the agent should:

1. **Match questions to source types** — "You need primary data, not a blog post"
2. **Evaluate source credibility** — Who published this? What's their incentive?
3. **Find free alternatives first** — Most founders don't need paid databases yet
4. **Teach search strategies** — How to find what you need, not just Google it
5. **Challenge weak citations** — "That's a press release, not research"

---

## Source Hierarchy (Best to Worst)

### Tier 1: Primary Data (You Collect)

| Source | Use Case | Effort |
|--------|----------|--------|
| Customer interviews | Problem validation, solution feedback | High |
| Your analytics | Product usage, conversion, retention | Low (if instrumented) |
| A/B tests | Feature decisions, pricing, messaging | Medium |
| Surveys (your audience) | Quantitative validation | Medium |

**Rule:** If the question is about YOUR customers, YOU must collect primary data. Secondary sources are supplementary only.

---

### Tier 2: Official Statistics (Government & Supranational)

Global and cross-regional first; national sources second.

**Global / cross-regional (all free):**

| Source | Coverage | Best For |
|--------|----------|----------|
| World Bank Open Data | 200+ countries | Macro indicators, development data, global benchmarks |
| IMF Data | Global macro | GDP, inflation, trade, monetary statistics |
| OECD Data | 38 developed economies | Labor, productivity, innovation, regulation |
| UN Data | Global | Demographics, health, trade, SDGs |
| WTO Stats | Global trade | Import/export flows, tariffs |
| ILO Stat | Global labor | Employment, wages, informal sector |

**Major national statistics offices (free):**

| Office | Country/Region |
|--------|----------------|
| US Census Bureau | USA |
| US Bureau of Labor Statistics (BLS) | USA |
| US Bureau of Economic Analysis (BEA) | USA |
| Eurostat | EU-27 |
| UK Office for National Statistics (ONS) | UK |
| Statistics Canada | Canada |
| Australian Bureau of Statistics (ABS) | Australia |
| Japan Statistics Bureau | Japan |
| India Ministry of Statistics (MoSPI) | India |
| National Bureau of Statistics of China | China |
| IBGE | Brazil |

For any other country: search "[country] national statistics office" — most publish free data in English.

**Best for:** Market size, demographics, economic indicators, industry employment.

**Search tip:** Use standard industry classification codes — NAICS (North America), ISIC (UN), NACE (EU), SIC (UK). They let you pull comparable data across sources.

---

### Tier 3: Industry Research & Analyst Firms

| Source | Focus | Cost |
|--------|-------|------|
| Gartner | IT, technology trends | Paid (enterprise) |
| Forrester | Tech, consumer research | Paid (enterprise) |
| IDC | Tech market data | Paid |
| McKinsey Global Institute | Cross-industry research | **Free** thought leadership |
| BCG, Bain, Deloitte, PwC, EY | Cross-industry | **Free** reports and sector studies |
| Statista | Aggregated statistics | Freemium |
| IBISWorld | Industry reports | Paid |
| Euromonitor | Consumer markets | Paid |
| Nielsen | Consumer behavior | Paid |

**Free alternatives that actually work:**

- Big-4 and strategy firm publications (McKinsey/BCG/Deloitte publish substantial free analysis)
- Public-company investor relations pages (industry data disclosed in filings)
- Industry association reports (often free to non-members too)
- Academic research via Google Scholar or SSRN
- Trade-body publications (WEF, World Economic Forum reports are free)

**Rule:** If a founder cites Gartner/Forrester without access to the actual report, ask for the link. Second-hand citations are worthless.

---

### Tier 4: Financial & Company Data

**Public companies (all free):**

| Source | Coverage |
|--------|----------|
| SEC EDGAR | US-listed companies — 10-Ks, 10-Qs, S-1s |
| Companies House | UK-registered companies |
| European Business Register | EU countries |
| SEDAR+ | Canadian public companies |
| TDnet / EDINET | Japan |
| Company investor relations pages | Globally — annual reports, presentations |
| Yahoo Finance, Google Finance | Basic financials, global |
| Macrotrends | Historical financials, US-focused |
| Stock Analysis (stockanalysis.com) | Global, free financials |

**Private companies and startups:**

| Source | Coverage | Cost |
|--------|----------|------|
| Crunchbase | Global startup/funding data | Freemium |
| OpenCorporates | Corporate registry data, 200M+ entities | Free (with limits) |
| PitchBook | Private markets, deep VC data | Paid (expensive) |
| Dealroom | European startups/VC | Freemium |
| Tracxn | Global startup tracking | Paid |

**Professional tools (paid, usually not needed pre-Series A):**

- Bloomberg Terminal, Refinitiv Eikon, S&P Capital IQ, FactSet

**Best for:** Competitor analysis, pricing benchmarks, market trends, risk signals.

**Search tip:** Read the "Risk Factors" section in 10-Ks — companies are legally required to disclose what could kill their business.

---

### Tier 5: Startup & Ecosystem Research

| Source | Focus | Cost |
|--------|-------|------|
| CB Insights | Research reports, failure analyses, trends | Freemium |
| Startup Genome | Global ecosystem rankings, scaling data | Free reports |
| Global Entrepreneurship Monitor (GEM) | National entrepreneurship rates, fear of failure | Free |
| Y Combinator Research / YC library | Founder-focused content | Free |
| a16z (Andreessen Horowitz) portfolio content | VC market commentary | Free |
| First Round Review | Operator and founder essays | Free |
| Stripe Atlas Guides | Legal / ops / incorporation | Free |
| Kauffman Foundation | US entrepreneurship research | Free |

**Best for:** Benchmarks (churn, retention, growth rates), startup-specific operational data, early-stage industry perspective.

---

### Tier 6: News & Media (Use Carefully)

| Source | Reliability | Use Case |
|--------|-------------|----------|
| Wire services (Reuters, AP, Bloomberg News) | High | Breaking news, factual |
| Major business press (FT, WSJ, Economist, Nikkei) | High | Analysis, trends |
| Trade publications | Medium-High | Sector trend awareness |
| Tech press (TechCrunch, The Information, Stratechery) | Medium | Startup announcements, commentary |
| General news | Low-Medium | Context only |

**Rule:** News is for awareness, not evidence. Always find the primary source (filing, study, press release) and cite that instead.

---

### Tier 7: Avoid (Not Evidence)

| Source | Why It's Weak |
|--------|---------------|
| Reddit, forums, Quora | Anecdotal, selection bias |
| LinkedIn posts | Self-promotion, unverified |
| Twitter/X, Threads | Opinions, not data |
| Random blog posts | No methodology, no sources |
| Founder's opinion | Not evidence |
| "Everyone says..." | Appeal-to-popularity fallacy |
| AI-generated content without sources | Provenance unclear |

**Response:** "That's not a source. Where's the actual data?"

---

## Question-to-Source Mapping

| Question Type | Best Source | Search Strategy |
|---------------|-------------|-----------------|
| "How big is the market?" | Tier 2 + Tier 3 | Industry code (NAICS/ISIC/NACE) + "market size" + year |
| "What do customers want?" | Tier 1 (interviews) | Talk to 10+ actual customers |
| "How much should we charge?" | Tier 1 + Tier 4 (competitor pricing) | Competitor websites + willingness-to-pay tests |
| "Who are our competitors?" | Tier 4 + Tier 5 | Crunchbase / Dealroom + industry association directories |
| "Is this trend real?" | Tier 2 + Tier 3 | Cross-reference 3+ independent sources |
| "What's the regulation?" | Tier 2 (regulator sources) | Official regulator websites for the jurisdiction |
| "How fast is the market growing?" | Tier 2 + Tier 3 | Pull 3+ years of trend data |
| "What's a normal churn/retention rate?" | Tier 5 | OpenView, ChartMogul, SaaS benchmark reports |
| "How much does a startup like mine raise?" | Tier 4 (Crunchbase, PitchBook, Dealroom) | Filter by stage, vertical, geography |

---

## Source Evaluation Checklist

```markdown
## Source: [Name/URL]

### Credibility Check
- [ ] Published by recognized organization (government, university, established firm)
- [ ] Author named and qualified
- [ ] Publication date within last 3 years (or explain why older is OK)
- [ ] Methodology explained (how was data collected?)
- [ ] Sample size disclosed (if survey/research)
- [ ] Funding/sponsorship disclosed (conflict of interest check)

### Incentive Check
- Who benefits if you believe this?
- Are they selling something related?
- Are they competing with what you're building?
- Is this a press release disguised as news?

### Verification
- [ ] Can you find the same data elsewhere?
- [ ] Do other sources agree?
- [ ] Is the primary source available?

### Verdict
[ ] USE — Reliable, appropriate for question
[ ] USE WITH CAUTION — Some limitations, supplement with other sources
[ ] DON'T USE — Unreliable or inappropriate
```

---

## Search Strategies

### Google Search Operators

```
site:.gov "market size" "semiconductors" [year] # Government sources
site:.int OR site:.org "industry report" [year] # Intl orgs / NGOs
filetype:pdf "annual report" [industry]         # PDF reports only
"[industry] market" size [year]                 # Add -[prior years] to exclude stale results
intitle:"market research" [industry]            # In title
"[keyword]" -pinterest -quora                   # Exclude low-signal domains
```

### Finding Industry Data

1. **Identify the industry association**
   - Search: "[industry] association [region]"
   - Example: "SEMI" for semiconductors, "IATA" for air travel, "IFPI" for music
2. **Check their publications** — most associations publish annual reports
3. **Find public companies in the space** — their annual reports contain market data
4. **Look for government statistics** — use standard industry codes

### Academic Research

1. **Google Scholar** (scholar.google.com) — filter by last 5 years; look for "free PDF" links
2. **SSRN** (ssrn.com) — working papers across business/economics; mostly free
3. **ResearchGate** — authors often share full papers; can request directly
4. **University repositories** — search `site:.edu [topic] research`
5. **arXiv** (arxiv.org) — technical / quantitative research

---

## Agent Triggers

**Apply this pattern when:**

| Founder Statement | Agent Response |
|-------------------|----------------|
| "I read online that..." | "Where exactly? Link please." |
| "Everyone knows..." | "That's not evidence. Show me the data." |
| Cites a blog post | "Who wrote this? What's their methodology?" |
| Uses 5-year-old data | "That's stale. What's the current number?" |
| Single source for critical claim | "Find two more independent sources." |
| "The report says..." (no link) | "Which report? Can I see it?" |
| Cites competitor press release | "That's their marketing, not fact. Find independent verification." |
| AI summary with no citations | "Where did the model pull this from? Verify before using it." |

---

## Quick Reference: Best Free Sources by Category

**Market size & growth**
- World Bank Open Data, IMF, OECD (macro)
- Eurostat, US Census, national statistics offices (regional)
- Public-company annual reports (sector slices)
- McKinsey / BCG / Deloitte thought leadership

**Customer behavior**
- Your own analytics (GA4, Mixpanel, Amplitude, PostHog, etc.)
- Customer interviews (you conduct)
- Public survey data (Pew Research, national statistics offices)

**Competitor intelligence**
- Competitor websites (pricing, features)
- SEC EDGAR / Companies House (filings if public)
- Crunchbase, Dealroom (funding, headcount signals)
- Job postings (hiring priorities reveal strategy)
- App stores and review sites (customer feedback)

**Industry trends**
- Trade publications (free articles)
- Government industry publications
- University research (Google Scholar, SSRN)
- Patent filings via Google Patents (R&D direction)

**Startup benchmarks**
- CB Insights, Startup Genome, GEM reports
- OpenView SaaS Benchmarks (annual)
- First Round State of Startups
- Y Combinator essays

**Regulations**
- Official regulator websites for the jurisdiction
- EUR-Lex (EU law), regulations.gov (US)
- Law-firm client alerts (free, focused on recent changes)

---

*Part of the Founder Agent Kit. Pairs with the Fonda personality (SOUL.md). References: see `references/RESEARCH.md`.*
