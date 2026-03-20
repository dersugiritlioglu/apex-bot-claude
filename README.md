# APEX Trading Bot 🤖

Browser-based BTC/USDT paper trading bot. Open `index.html` — no install, no npm, no build step.

## Features
- **Master Algorithm** — auto-detects Bullish / Bearish / Sideways / Volatile regime
- **5 Named Algorithms** — each optimised for a specific market condition
- **Live reasoning panel** — explains every decision step by step
- **5 Tabs** — Live Trading · Strategy · Trade Log · Calendar · Algorithms
- **Paper trading** — $10,000 simulated account, persistent state
- **Backtested** — 972 tests across 6 historical BTC regimes (2020–2026)

## Algorithms
| # | Name | Regime | Logic |
|---|---|---|---|
| 1 | Trend Rider | Bullish | MACD + EMA confirm |
| 2 | Momentum Surge | Bullish + High Vol | MACD + volume ≥ 1.5× |
| 3 | Bear Bouncer | Bearish | BB lower band + RSI |
| 4 | Range Hunter | Sideways | RSI extremes + BB %B |
| 5 | Volatility Shield | Volatile | EMA only, 25% size |

## Data
Live from Binance public API — no API key required.
