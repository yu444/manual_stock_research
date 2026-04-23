# Manual_Stock

> **The first systematic, real-time benchmark of LLM investment signal quality.**

Every trading day, three AI models — Claude, DeepSeek, and Gemini — independently generate BUY/HOLD/SELL signals on 11 high-conviction tech stocks. Each signal is timestamped before the market opens. No hindsight. No cherry-picking. Just daily predictions measured against actual price outcomes.

The result: a growing, auditable record of *which AI thinks better about markets* — and whether any of them can beat a careful human analyst.

---

## What's Being Tracked

**11 tickers:** NVDA · AMD · QCOM · MSFT · PYPL · GOOG · META · ASML · TSM · AVGO · MU

<img width="1244" height="705" alt="image" src="https://github.com/user-attachments/assets/614c05b5-7eaa-4dda-96bb-261ff141b392" />


**5 signal sources per ticker, per day:**
| Source | Type |
|--------|------|
| 🧠 Claude | Anthropic LLM |
| 🐋 DeepSeek | Chinese frontier LLM |
| ✨ Gemini | Google LLM |
| 🎮 Game Theory | DeepSeek re-run with Nash equilibrium framework |
| 🧑‍💻 Me | Human contrarian baseline |

---
<img width="2100" height="1500" alt="image" src="https://github.com/user-attachments/assets/635b61e3-741d-45c3-b692-6184a9362ff5" />

<img width="2382" height="1771" alt="image" src="https://github.com/user-attachments/assets/9e6b3b2b-a43e-4b28-8109-376664b5c9a6" />

<img width="2370" height="1771" alt="image" src="https://github.com/user-attachments/assets/44f8e40b-bcb1-4c14-bd43-9098e43ec793" />

## Why This Matters

LLMs are increasingly used for financial analysis. But no one has systematically asked: **do they actually get it right?**

This project runs that experiment in production — real money, real signals, real outcomes. Key research questions:

- Does model consensus outperform individual models?
- Does a human contrarian beat the AI herd?
- Which models are regime-aware vs. trend-following?
- Can game theory framing improve signal quality?

---

## Live Dashboard

**[📊 manual-stock.duckdns.org](https://manual-stock.duckdns.org/web/login.html)**

Ticker cards with signal badges · Performance charts · Full reasoning per model · Daily updates

---

## Research Paper

**[📄 Benchmarking Multi-LLM Investment Signals: Accuracy, Consensus, and the Augmented Analyst Edge](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=6515058)**

*Qiyu Zhang — SSRN Preprint, 2026*

Formalizes the methodology: Information Coefficient tracking, per-model Sharpe ratios, Spearman correlation, chi-square signal independence tests, and regime-conditional accuracy analysis.

---

## Signal Methodology

Each model receives identical market data daily and produces a structured signal:
