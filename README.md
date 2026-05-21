# 📈 BackTest Trading Journal

A self-hosted monthly backtesting journal built as a single HTML file. No server, no dependencies to install — just open `index.html` in any browser or host it on GitHub Pages.

## Features

| Page | What's inside |
|------|--------------|
| **Metrics** | Win rate, PnL, balance, daily PnL bars, win/loss donut, cumulative equity curve |
| **Journal** | Full trade log with dropdowns for Setup, Session, Outcome, R:R auto-calc |
| **Calendar** | Monthly grid showing trades/day and daily PnL |
| **Analytics** | Avg hold time, session rankings, setup performance, Long vs Short bias, symbol breakdown, profit factor, streaks, PnL distribution, AI insights |

## Deploy to GitHub Pages

1. Fork or clone this repo
2. Go to **Settings → Pages**
3. Set Source to `main` branch, root `/`
4. Your journal will be live at `https://yourusername.github.io/your-repo-name`

## Data Storage

All data is saved in your browser's `localStorage`. Each month is stored independently — switching the month selector loads that month's trades without affecting other months.

> ⚠️ `localStorage` is per-browser and per-origin. Data does not sync across devices. To back up, use your browser's export tools or copy the localStorage values.

## Usage

1. Select the **month and year** in the sidebar
2. Go to **Journal** and click **Add Trade**
3. Fill in trade details — time in/out, entry/exit, SL/TP, setup, session, outcome, PnL
4. Check **Metrics** for monthly overview and **Analytics** for deep insights
5. Use **Calendar** to see your trading activity at a glance

## Tips for best analytics

- Always fill in **Time In** and **Time Out** for hold time analysis
- Set **Session** on every trade for session performance rankings  
- Set **Setup** type for setup breakdown
- Mark **Outcome** (Win/Loss/Breakeven) for win rate and streak tracking
- Enter your **Starting Balance** in the sidebar for accurate balance tracking
