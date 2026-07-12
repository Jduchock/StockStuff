# StockStuff

> A hypothetical $25,000 AI-curated stock portfolio — tracking 10 hand-picked positions across AI infrastructure, next-gen battery technology, and graphene materials.

## 📊 Live Dashboard

**[https://jduchock.github.io/StockStuff/](https://jduchock.github.io/StockStuff/)**

Open the link above to view the live portfolio dashboard, including:

- Real-time stock prices and daily % change for all 10 positions
- 15 days of pre-project price history on every card's sparkline chart
- Daily performance bar chart with a day-selector to browse any historical trading day
- Portfolio allocation donut chart by category
- Running portfolio value vs. $25,000 starting capital
- Best and worst performer of the day
- Auto-refreshes every 30 minutes during US market hours (9:30 AM – 4:00 PM ET)

## 🗂 Portfolio

| Ticker | Company | Allocation | Tier |
|--------|---------|-----------|------|
| NVDA | Nvidia | 22% | 🟢 Core |
| MSFT | Microsoft | 18% | 🟢 Core |
| GOOGL | Alphabet | 13% | 🟢 Core |
| MU | Micron Technology | 9% | 🟢 Core |
| AVGO | Broadcom | 12% | 🔵 Growth |
| PLTR | Palantir | 8% | 🔵 Growth |
| CCJ | Cameco | 6% | 🔵 Growth |
| QS | QuantumScape | 6% | 🟡 Long Shot |
| NNXPF | NanoXplore | 3% | 🟡 Long Shot |
| GMG | Graphene Mfg Group | 3% | 🟡 Long Shot |

## 🏗 Repo Structure

| File | Purpose |
|------|---------|
| `index.html` | Dashboard UI — Chart.js charts, sparklines, day selector |
| `data.json` | Pre-fetched price history (updated by GitHub Action on weekdays) |
| `.github/workflows/refresh-data.yml` | Auto-refresh job — runs every 30 min during market hours |

---

*Started: July 12, 2026 · Built with Claude (Anthropic) · Data via Yahoo Finance*
