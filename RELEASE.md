# v1.13.0 — Full Pine Script engine and strategies
### Added
- The Pine Script engine now covers every function, variable and constant in the official Pine v6 reference, including matrices, enums, polylines and chart points.
- Strategies are simulated like a strategy tester: market, limit and stop orders, take profit, stop loss and trailing stop (strategy.exit), pyramiding, commissions, order quantity types, and trade statistics (net profit, equity, drawdown, closed and open trades). Simulation only: no real orders are ever placed.
- Older scripts: Pine v1, v2 and v3, scripts without //@version, offset(), and quoted text that continues on the next line.

### Fixed
- A user function with the same name as a variable (for example `x = x()`) is now called correctly.
- Several strategy signals on the same candle are stacked instead of drawn on top of each other.

### Documentation
- README updated in 5 languages: new in 1.13.0.
