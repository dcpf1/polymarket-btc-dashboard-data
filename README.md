# POLY·BTC — Public Ledger (data repo)

Public, auto-published data + dashboard for a **paper-trading** bot that follows the
"Down-move Stickiness" edge on Polymarket BTC/ETH 5-minute up/down markets.

**Paper trading only — no live orders, no real capital.** A simulated $150 portfolio
tracks how the edge would perform. This repo is written to automatically by the
`shadow_live.py` engine every ~60 seconds.

## Live dashboard

https://dcpf1.github.io/polymarket-btc-dashboard-data/

## Files

| File | Description |
|------|-------------|
| `index.html` | The dashboard (vanilla HTML/CSS/JS, no external libraries). |
| `dashboard_data.json` | Current portfolio, open positions, resolved trades, per-strategy stats. Rewritten every ~60s. |
| `balance_history.json` | Hourly portfolio-value samples for the equity chart (~50-day rolling window). |

Bets, PnL, and stats only — no keys, wallet addresses, or credentials are ever
published here.
