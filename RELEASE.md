# v1.19.0 — Bands and channels rebuilt
### Added
- Bollinger Bands, Bollinger Bands %B, Bollinger BandWidth, Keltner Channels, Donchian Channels, Envelope, Supertrend, Ichimoku Cloud, VWAP and Linear Regression Curve rebuilt with TradingView's inputs and default values.
- Extra settings where useful: basis MA type, offset, another timeframe with wait for timeframe closes, custom levels, Supertrend buy/sell signals and trend highlight, VWAP anchor period (session, week, month, quarter, year) with three standard-deviation or percentage bands, and alerts on band crosses and trend changes.
- New indicator: Linear Regression Channel, with upper and lower deviation, extendable lines and Pearson's R.

### Fixed
- Chart settings › Legend: the switches now change the legend (they were writing to a copy of the settings).
- The arrow of the Title menu no longer appears on top of its switch.
- ta.vwap with a band multiplier now returns the VWAP and its bands.

### Documentation
- README updated in 5 languages: new in 1.19.0.
