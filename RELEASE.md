# v1.12.2 — Pine v4 support
### Added
- Pine Script v4 indicators run too: functions without the ta./math./str. prefix, security(), iff(), tostring(), input(type=…) and the tr, vwap and obv variables.
- Gold: tick volume across the whole history since 2011.

### Fixed
- Pine v5: dividing two whole numbers written in the code gives a whole number (5 / 2 = 2), as on TradingView. Pine v6 keeps the decimal result.

### Documentation
- README updated in 5 languages: new in 1.12.2.
