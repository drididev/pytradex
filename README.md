# PyTradeX


**PyTradeX** — Stock Analysis & Trading Simulator


A professional demo project that combines an interactive dashboard (Streamlit) with a backtesting/trading engine. Designed to show interviewers strong Python skills: clean architecture, testing, CI, Docker, and deploy-ready configuration.


## Features
- Interactive Streamlit dashboard for fetching and visualizing OHLCV data
- Technical indicators: SMA, EMA, RSI, MACD (extendable)
- Simple backtester with strategy plug-ins (moving-average crossover, RSI)
- Exportable reports & backtest metrics (Sharpe, max drawdown, P&L)
- Dockerized app for consistent demos
- CI: lint, test, build checks (GitHub Actions)


## Quick start (developer)


Requirements: Docker (recommended) or Python 3.10+/poetry


Clone:
```bash
git clone https://github.com/drididev/pytradex.git
cd pytradex
