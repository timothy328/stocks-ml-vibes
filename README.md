# Stocks ML Vibes

A structured workspace for researching public markets, building systematic
analysis, and experimenting with machine-learning and agentic workflows.
The repository supports both longer-horizon investing research and disciplined
short-horizon trading study.

## Repository structure

```text
stocks-ml-vibes/
├── discovery/
│   ├── data-sources/
│   ├── universe/
│   ├── research-questions/
│   └── due-diligence/
├── analysis/
│   ├── financial/
│   ├── technical/
│   ├── reporting/
│   ├── fpl/
│   ├── valuation/
│   ├── portfolio/
│   ├── macro/
│   ├── risk/
│   ├── sentiment/
│   └── alternative-data/
├── agentic/
│   ├── agents/
│   ├── tools/
│   ├── workflows/
│   ├── evaluations/
│   └── guardrails/
└── day-trading/
    ├── market-prep/
    ├── setups/
    ├── execution/
    ├── risk-management/
    ├── backtesting/
    └── trading-journal/
```

## Working principles

- Separate data collection, analysis, decision-making, and execution.
- Record assumptions, timestamps, data sources, and survivorship or look-ahead
  risks.
- Treat backtests and model outputs as evidence to evaluate, not guarantees of
  future returns.
- Keep position sizing, loss limits, and operational safeguards explicit.
- Do not use this repository as personalized financial advice.

## Areas

- `discovery/` - find instruments, datasets, research questions, and useful
  primary sources.
- `analysis/` - organize fundamental, market, reporting, portfolio, and
  alternative-data research.
- `agentic/` - develop agents and workflows that can retrieve, analyze, and
  explain market information with evaluation and safety controls.
- `day-trading/` - study intraday preparation, setups, execution, risk, and
  review.

The `fpl/` area is reserved for financial-planning and liquidity-oriented
analysis; its scope can be refined as the project develops.
