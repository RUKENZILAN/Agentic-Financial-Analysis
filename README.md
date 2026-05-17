# Strategic Financial Autopilot (Antigravity Multi-Agent Workflow)

An autonomous multi-agent financial intelligence system engineered on the **Antigravity** platform. This production-ready orchestration framework ingests messy, unstandardized enterprise financial statements (Trial Balances, Balance Sheets, Income Statements) and coordinates a team of 7 specialized AI agents to execute advanced quantitative analysis. 

The ultimate pipeline deliverable is a standalone, ultra-premium interactive dashboard (`index.html`) loaded with executive KPIs, dynamic **Chart.js** stress-test simulations, and deep corporate health metrics.

---

## 📈 System Architecture & Data Pipeline

The workflow utilizes a robust mix of parallel processing and sequential dependency loops to ensure absolute analytical rigor and zero data truncation.

```text
       [ 📂 RAW FINANCIAL DATA ] (CSV / Excel / Trial Balance)
                   │
                   ▼
       ┌───────────────────────────────┐
       │       AGENT 1: CEO AGENT      │ <─── (Step 1: Normalizes and maps
       │   (Data Mapping & Parsing)    │       raw headers into clean JSON)
       └───────────────┬───────────────┘
                       │
         ┌─────────────┼─────────────┬─────────────┐
         │ (JSON)      │ (JSON)      │ (JSON)      │ (JSON)
         ▼             ▼             ▼             ▼
  ┌────────────┐┌────────────┐┌────────────┐┌────────────┐
  │  AGENT 2   ││  AGENT 3   ││  AGENT 4   ││  AGENT 5   │
  │  ANALYST   ││  AUDITOR   ││ OPTIMIZER  ││ FORECASTER │
  │   AGENT    ││   AGENT    ││   AGENT    ││   & RISK   │
  └─────┬──────┘└─────┬──────┘└─────┬──────┘└─────┬──────┘
        │             │             │             │
        │ (Ratios &   │ (Balance    │ (Budget     │ (Z-Score &
        │  Trends)    │  Auditing)  │  Scenarios) │  Runway)
        └─────────────┼─────────────┼─────────────┘
                      ▼             ▼
               ┌───────────────────────────────┐
               │        AGENT 6: DUPONT        │
               │             AGENT             │ (Deconstructs ROE)
               └───────────────┬───────────────┘
                               │
                               ▼
               ┌───────────────────────────────┐
               │       AGENT 1: CEO AGENT      │
               │     (Data Consolidation)      │ (Merges all sub-agent
               └───────────────┬───────────────┘  reports into Board Summary)
                               │
                               ▼ (Full Consolidated Payload)
               ┌───────────────────────────────┐
               │    AGENT 7: UI/UX REPORTING   │
               │            AGENT              │ (Injects data into Tailwind
               └───────────────┬───────────────┘  & Chart.js templates)
                               │
                               ▼
                     [ 🌐 INDEX.HTML ] (Standalone Interactive Dashboard)


## 📊 Live Dashboard Preview
![Financial Autopilot Dashboard](Screenshot_Index html.png)
<img width="657" height="938" alt="Screenshot_Index html" src="https://github.com/user-attachments/assets/ff28b640-9b5e-4530-a610-daff15ce999b" />

