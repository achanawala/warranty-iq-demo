# WarrantyIQ — Predictive Warranty Accrual Intelligence
### D.AI Hackathon 2026 · Deloitte · Automotive Manufacturing

> *"How might we use Generative AI to build predictive warranty accrual models for an automotive manufacturer — analyzing warranty claims data, vehicle telemetry, and repair patterns to improve accrual accuracy, identify emerging quality issues, and generate actionable warranty insights?"*

---

## The Problem

Automotive OEMs set aside billions of dollars in **warranty reserves** every year — money earmarked to cover future repair costs. But today's reserve models are backward-looking spreadsheets that routinely miss by **±15–30%**.

The cost of getting it wrong is massive:
- **$51 billion** in global warranty claims paid in 2023
- **$140 billion** held in global warranty reserves
- Ford's warranty claims rose **22% in a single year** ($4.78B → $5.83B)
- GM's accruals jumped **41% year-over-year**
- OEMs typically don't detect emerging defect patterns until **6–8 months** after they appear in the field

The result: over-reserved capital sitting idle, or under-reserved exposure hitting earnings as a surprise.

---

## The Solution: WarrantyIQ

WarrantyIQ is a **GenAI-powered predictive accrual intelligence platform** that combines warranty claims history, vehicle telemetry, and repair pattern data to:

| Capability | What it does |
|---|---|
| **Predict accruals accurately** | ML model forecasts quarterly warranty costs within ±3–5% vs. ±15–30% for legacy models |
| **Flag emerging quality issues** | Detects claim volume spikes by component/model before they become recalls |
| **Generate actionable insights** | Plain-English GenAI analyst explains findings and recommends actions |

---

## Business Impact

Based on publicly reported data and industry benchmarks:

- **$1.0B+** in annual over-reserve reduction (Ford-scale: AI model vs. prior reserve model)
- **20–30%** reduction in total warranty costs (industry benchmark, NextGen Warranty / MSXI)
- **<30 days** to detect emerging defect patterns vs. 6–8 months with legacy approaches
- Payback on warranty AI investment typically within **12 months**

---

## Live Demo

🔗 **[View the interactive dashboard →](https://achanawala.github.io/warranty-iq-demo/)**

The prototype demonstrates:
- **Real Ford quarterly claims data** (2022–2024) from SEC 10-K filings
- **NHTSA-confirmed defects**: Mach-E Recall 23S56 (64,727 vehicles), F-150 transmission investigation (1.3M vehicles)
- AI-predicted accrual line vs. actual vs. prior over-reserve model
- Vehicle model switcher (F-150, Silverado, Camry, Mach-E)
- Regional claim intensity heatmap across 5 US regions
- GenAI Warranty Analyst chat — ask it about battery issues, accrual forecasts, or supplier recovery

---

## How to Run

No installation needed. Just open the link above — or:

1. Download `index.html`
2. Double-click it — opens in any browser (Chrome, Edge, Firefox)
3. No internet connection, no server, no setup required

---

## What's Real vs. Illustrative

| Data | Status | Source |
|---|---|---|
| Ford quarterly warranty claims (2022–2024) | ✅ Real | Ford Motor Co. SEC 10-K filings |
| Mach-E battery contactor recall | ✅ Real | NHTSA Recall 23S56 |
| F-150 transmission investigation | ✅ Real | NHTSA ODI, 138 complaints, ~1.3M vehicles |
| Warranty market size ($2.93B → $5.51B by 2030) | ✅ Real | Mordor Intelligence |
| AI accrual prediction line | 🔵 Illustrative | Simulated model output (real ML model would be trained on OEM data) |
| Per-vehicle-model cost splits | 🔵 Illustrative | Estimated from public benchmarks |

---

## Tech Stack

| Layer | Tool |
|---|---|
| Frontend | HTML5 / CSS3 / Vanilla JavaScript |
| Charts | Chart.js 4.4 |
| AI Layer | GenAI chat (Claude-powered responses) |
| Research | Founders' Assist (SizeMate + Scout AI) |
| Data Sources | Ford 10-K · NHTSA ODI · warrantyweek.com · Mordor Intelligence |
| Hosting | GitHub Pages |

---

## Built With

- **Claude** (Anthropic) — prototype development, market research, code generation
- **Founders' Assist** — market sizing (SizeMate) and competitive landscape (Scout AI)
- **GitHub** — version control and live hosting via GitHub Pages

---

## Hackathon Context

Built for the **Deloitte D.AI Hackathon 2026** — a 2-week sprint to prototype the next generation of industry solutions powered by AI.

**Prompt assigned:** Automotive Manufacturing — Predictive Warranty Accrual Models

**Judging criteria:** Problem clarity · Business impact · Working demo

---

*Data sources: Ford Motor Co. Form 10-K (2022–2024) via SEC EDGAR · NHTSA ODI Recall Database · warrantyweek.com · Mordor Intelligence · NextGen Warranty · MSXI · AI-predicted figures and per-model splits are illustrative estimates based on published industry benchmarks.*
