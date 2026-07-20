# Portfolio build spec — Shrikant Naik

Working document for building the portfolio in Framer. Purpose: a **credibility artifact** linked from LinkedIn and job applications — skimmed in 30–90 seconds, front-loads proof, reinforces the CV rather than duplicating it.

Structure: **6 sections + footer.** Hero → Proof bento → Featured case (Yokogawa) → Second case (Clinical AI) → About → Experience → Footer. One separate page: the full Yokogawa case study.

---

## Section 1 — Hero

> **Shrikant Naik**
> Product marketing and GTM strategy, backed by four years of operations and project delivery.
> Currently proving it through hands-on GTM work — starting with Yokogawa's ERP market entry.
>
> *Mumbai · Global MBA, SP Jain School of Global Management · Available Sep 2026*
>
> Buttons: **View the Yokogawa case** · **LinkedIn**

Note: the hero leans on the projects as its proof, so the Yokogawa case must sit directly below and stay prominent.

---

## Section 2 — Proof bento (interactive)

Four tiles. Each shows the metric by default; on hover (desktop) / tap (mobile) reveals the context line. Make **+64%** the large anchor tile; the other three smaller around it.

| Metric | Reveal on hover/tap |
|---|---|
| **+64%** (anchor) | Program completion rate — customer research surfaced 6 drop-off points, fixed with automated milestone comms (CareerLabs) |
| **80% on-time** | Across 35+ projects managed solo, with 100% client retention (Pineapple Design) |
| **₹3L+** | Net-new retainer created mid-project at 100% margin (Pineapple Design) |
| **10+ hrs/wk** | Manual work eliminated by integrating 8+ AI tools into client workflows (Pineapple Design) |

Framer: hover-to-reveal is easy on desktop; **test tap behavior on mobile** — hover states can silently fail on touch.

---

## Section 3 — Featured case: Yokogawa (summary on main page)

> **Featured Case Study**
> ## Yokogawa ERP — Market Entry Strategy for ANZ
> A go-to-market strategy for Yokogawa Electric's Microsoft Dynamics 365 ERP business, entering the Food & Beverage and Pharmaceutical sectors across Australia and New Zealand.
>
> **The problem** — Yokogawa held a rare structural advantage, owning both plant-floor operational technology and ERP capability, but had no market intelligence, business case, or go-to-market plan to act on it.
>
> **The work** — Market sizing (TAM/SAM/SOM), competitive benchmarking, a modified adoption framework, three-scenario financial modeling, and an integrated GTM playbook.
>
> **The outcome** — A base-case revenue model of ~USD 3.34M over 36 months, a CDMO-first entry sequence, and positioning built on integration ownership rather than feature depth.
>
> **My role** — Project lead across a four-person team — owned the secondary research base, coordinated the four workstreams from market intelligence through to the final playbook, and ran project management and delivery cadence.
>
> **[ Read the full case study → ]**

Open item: confirm "project lead" holds with your three teammates before publishing.

---

## Section 4 — Second case: Clinical AI (summary on main page)

> **Second Case**
> ## Building Trust for Clinical AI Adoption — Singapore
> A B2B2C positioning framework for a diagnostic-AI product, addressing why clinical accuracy alone fails to convert patients into users.
>
> **The insight** — A privacy paradox: patients fear data misuse more than diagnostic error. In a survey of 80 Singaporean healthcare users, privacy concern was the strongest adoption barrier (r = −0.58), and 77.5% said they'd adopt AI if a doctor recommended it — versus 15% without.
>
> **The reframe** — Move positioning from "95% accurate" to "secure, doctor-recommended," sequencing institutional (B2B) trust before consumer (B2C) demand — validated against a market case where accuracy-led marketing produced a sub-2% conversion rate.
>
> **My role** — Sole author. Ran the full project end-to-end: designed and fielded the n=80 survey, analyzed the data, and built the positioning framework and go-to-market recommendation.
>
> **[ View the case → ]**

Note: real primary data, so figures stand as findings. Keep NotebookLM out of the copy (mention only in interviews if asked about workflow). If "designed and fielded" isn't exactly how the survey ran, adjust the verb.

---

## Section 5 — About

> ## About
> I spent four years making things run — 35+ projects delivered solo, customer research that lifted program completion 64%, workflows rebuilt around AI tools. What connected all of it is the instinct product marketing runs on: understand what customers actually need, then shape how the product meets them. I'm now an MBA candidate at SP Jain, building that into a PMM career through real go-to-market work — a market-entry strategy for Yokogawa's ERP business, and a positioning framework for clinical AI in Singapore. Open to product marketing and GTM roles from September 2026.

---

## Section 6 — Experience (condensed)

> ## Experience
>
> **Pineapple Design** — Senior Associate PM, Founder's Office (2024–25)
> Ran 35+ projects solo at 80% on-time and 100% retention. Created a net-new ₹3L+ retainer mid-project. Built an AI-powered brand chatbot adopted across all projects.
> *Demonstrates: end-to-end delivery, commercial instinct, AI-enabled workflow design.*
>
> **Your CxO Online Solutions** — Project Success Manager (2023–24)
> Promoted to PM in 3 months, reporting to the CEO. Drove a 15% satisfaction lift and 22% fewer support tickets during a period of 10% MRR growth.
> *Demonstrates: customer success, cross-functional delivery, stakeholder management.*
>
> **CareerLabs Technologies** — Senior Operations Associate (2021–23)
> Lifted program completion 64% via customer research identifying 6 drop-off points. Influenced the product roadmap by analyzing conversion data across 8 programs.
> *Demonstrates: customer research, data-to-decision, roadmap influence.*
>
> **Skills:** GTM strategy · Customer insights & market research · Cross-functional leadership · Project & program management · AI-driven process automation
>
> **[ Download full CV → ]** · **[ LinkedIn → ]**

The italic "demonstrates" lines are the translation layer — they make ops experience read as PMM-relevant. Keep them.

---

## Footer

> **Shrikant Naik** — Product marketing & GTM
> shrikantnaik6@gmail.com · LinkedIn · Mumbai · Available Sep 2026

---

# Full Yokogawa case study page (Section 3's destination)

This is the one page a scrutinizing reader opens. Numbers must match the source report exactly.

### Header
> ## Yokogawa ERP — Market Entry Strategy for Australia & New Zealand
> A go-to-market strategy for Yokogawa Electric's Microsoft Dynamics 365 ERP business entering the Food & Beverage and Pharmaceutical sectors.
>
> *Client: Yokogawa Engineering Asia · Scope: Market intelligence, business case, GTM playbook · Feb–Jun 2026 · Team of 4, SP Jain industry project*

### The challenge
> Yokogawa held a rare structural advantage: it owned the plant-floor operational technology (OT) inside process manufacturers and, after acquiring Votiva, had Microsoft Dynamics 365 ERP capability. No ANZ competitor held both. But the advantage was unrealized — no market intelligence, no validated business case, no go-to-market plan for the F&B and Pharma verticals. Three gaps blocked action: market intelligence, strategic viability, and commercial implementation.

### Approach
> A four-stage mixed-methods design: secondary market research, competitive benchmarking, a purpose-built adoption framework, and scenario-based financial modeling. The framework extended the standard Technology-Organization-Environment (TOE) model with a novel fourth construct — OT-ERP Integration Value Perception — to capture how buyers weight a vendor that owns both the automation and ERP layers.
>
> *(Honesty note, keep visible or in a caption: the framework was designed for a planned buyer survey; findings here draw from secondary evidence, not primary validation.)*

### Market sizing — [INTERACTIVE: TAM/SAM/SOM funnel]
> TAM: ANZ mid-market ERP, ~USD 1.19B by 2030. SAM: 55–75 qualified accounts, A$24.5–48.8M. SOM: a realistic 7–8 accounts over 36 months, ~A$5.06M — with CDMOs and dairy exporters as Tier 1 priorities.

### Competitive landscape — [INTERACTIVE: positioning matrix]
> Seven live vendors benchmarked (Fusion5, Dynamics Square, Walkerscott, BatchMaster, SAP, Oracle NetSuite, Infor). All compete on ERP features or brand; none owns the OT layer. Mapped on OT-integration capability vs. ANZ presence, Yokogawa occupies uncontested space — the strategic core of the recommendation.

### Financial model — [INTERACTIVE: three-scenario switcher]
> Three scenarios stress-tested against deal velocity, contract value, and reference-account timing: Conservative (~USD 1.14M), Base (~USD 3.34M), Best (~USD 4.79M). Sensitivity analysis identified sales-cycle length as the single biggest revenue lever.

### The recommendation — [INTERACTIVE: 7-stage stepper]
> A CDMO-first entry sequence, positioning on integration ownership rather than feature depth, compliance-led demand generation tied to regulatory deadlines, strict pricing discipline, and a lighthouse reference account by Month 12 — which the model shows drives 78% of 36-month revenue. Delivered as a 7-stage GTM lifecycle.

### My contribution
> Project lead across a four-person team — owned the secondary research base, coordinated the four workstreams from market intelligence through to the final playbook, and ran project management and delivery cadence.

---

# Interaction specs (4 total)

Priority: build the **three-scenario switcher** and **7-stage stepper** for sure (they show financial + execution depth). TAM/SAM/SOM and the matrix can be static-but-clean if time is short. Don't over-animate — a credibility artifact that's too interactive reads as a design demo, not a strategy case.

### 1. Three-scenario revenue switcher — MEDIUM difficulty
Segmented control (Conservative / Base / Best). On click, three metric cards + a bar chart + an assumptions line all update. Data (from report Table 18):

| Scenario | Y1 (A$) | Y2 (A$) | Y3 (A$) | 36-mo total (USD) | Y3 gross margin | ACV |
|---|---|---|---|---|---|---|
| Conservative | 280K | 650K | 800K | 1.14M | −45% | A$400K |
| Base | 660K | 1,970K | 2,430K | 3.34M | 7.5% | A$600K |
| Best | 950K | 2,700K | 3,600K | 4.79M | 5% | A$900K |

Assumptions lines:
- Conservative: Only 1 CDMO pilot converts · ACV A$400K · no advocate revenue · sales cycles 50% longer.
- Base: 2 CDMO + 3 dairy wins · ACV A$600K · 1 advocate account by month 24 · 12–18 month sales cycles.
- Best: 3 CDMO + 2 dairy Tier-1A · ACV A$900K · 2 advocate accounts by month 18 · Microsoft co-sell active.

Framer build: either (a) embed as a code component reusing the Chart.js prototype, or (b) three static chart frames swapped by a segmented control. Embed is more elegant; swap is simpler.

### 2. TAM/SAM/SOM funnel — EASY (native Framer)
Three stacked frames of decreasing width (100% / 82% / 60%), each with a click state that fills its color and swaps a detail line below.
- TAM · ANZ mid-market ERP · USD 1.19B — "Total addressable market. Entire ANZ mid-market ERP opportunity across four target sub-segments, ~USD 1.19B by 2030."
- SAM · qualified accounts · A$24.5–48.8M — "Serviceable available market. 55–75 accounts meeting revenue and compliance-pain thresholds with multi-site or high regulatory complexity."
- SOM · 36-month target · A$5.06M — "Serviceable obtainable market. ~7–8 deals over 36 months (2 CDMO + 3 dairy + 2 Tier-2), the base-case commercial target."

### 3. 7-stage GTM stepper — EASY (native Framer)
Row of 7 numbered buttons + a detail panel. Default to Stage 5 with an amber accent (it's the lighthouse milestone driving 78% of revenue). Gate criteria (from report Table 21):
1. Target & awareness — 5–8 accounts advanced to Stage 2; two compliance webinars executed.
2. Qualification & discovery — TOE / OT-IVP score ≥ 70/100; all four minimum thresholds met.
3. Blueprint workshop — signed-off use-case shortlist (top 3); commercial framing accepted. Paid engagement.
4. Business case & proposal — NPV positive; payback under 24 months; formal proposal issued.
5. Pilot execution — data latency < 5s; user adoption > 90%. Lighthouse milestone — reference win by Month 12.
6. Rollout & adoption — multi-site go-live; > 90% adoption; first Expand-layer revenue invoiced.
7. Expansion & advocacy — module/site expansion triggered; reference asset published; ARR growth.

### 4. Competitive positioning matrix — EASY (native Framer)
2×2 plot: x-axis = OT integration capability (low→high), y-axis = ANZ ERP market presence (low→high). Plot competitors low on OT (Fusion5, Dynamics Square, SAP, Oracle NetSuite, BatchMaster clustered left); YEA alone in the high-OT "uncontested" quadrant. Hover a vendor to show its weakness vs. YEA. Optional if time-constrained.

---

# Framer build brief (paste into Framer AI as a starting point)

```
A single-page portfolio, clean and minimal, for a product marketing / GTM candidate.
Audience: recruiters skimming for 60 seconds. Prioritize legibility and fast proof over decoration.

Hero: full-width, generous whitespace. Large name, one-line positioning, smaller supporting
line, two buttons (primary "View the Yokogawa case", secondary "LinkedIn"). Neutral background.

Proof bento: bento-box grid of 4 tiles, one large anchor tile. Each shows a big metric number
by default; on hover (desktop) or tap (mobile) reveals a one-line context sentence.

Featured case + second case: two prominent case-study cards, each with a bold title, one-line
summary, four short labeled blocks (Problem/Work/Outcome/My role), and a CTA to a full page.

About: one short paragraph, human voice.

Experience: three roles, each with a one-line achievement summary and an italic "demonstrates" line.
Skills row. Links to full CV and LinkedIn.

Footer: name, email, LinkedIn, location, availability.

Typography: one strong sans-serif, high contrast, restrained color (near-black text, one accent).
Mobile-responsive. No stock imagery. Sentence case throughout.
```

Framer AI output is a starting point, not final — expect to hand-adjust spacing, the bento reveal, and any embedded chart.

---

# Honesty checkpoints (this is what protects you in interviews)

- Yokogawa case keeps the "team of 4" line visible. Not solo work.
- Yokogawa: no claim of validated/primary research — the report's own limitations section says the PLS-SEM survey wasn't administered. Copy says "secondary evidence."
- Clinical AI: real n=80 data, so figures stand — but be ready to answer "how did you get 77.5%" consistently. Keep NotebookLM out of the copy; volunteer it only if asked about workflow.
- All figures match the source documents exactly (USD 3.34M / 1.14M / 4.79M, TAM 1.19B, ACVs, r = −0.58, 77.5%). If you adjust any Yokogawa number for design, adjust toward the report, not away.

# Open items before publishing

1. Confirm "project lead" on Yokogawa holds with your three teammates.
2. Confirm "designed and fielded" matches how the n=80 survey actually ran.
3. Decide bento layout (which tile is the anchor — recommended: +64%).
