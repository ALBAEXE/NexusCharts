# v1.18.0 — Moving averages rebuilt, legend settings
### Added
- Moving averages rebuilt with TradingView's inputs and default values: SMA, EMA, WMA, HMA, VWMA and ALMA now have Length, Source, Offset, Smoothing (None, SMA, SMA + Bollinger Bands, EMA, SMMA (RMA), WMA, VWMA) with its length and BB StdDev, Timeframe and Wait for timeframe closes, plus alerts when the price crosses the average.
- New moving averages: SMMA, DEMA, TEMA, LSMA, McGinley Dynamic and MA Cross (two averages with type, length and colour, cross markers, fill and alerts).
- Moving Average Ribbon with four averages, each with show/hide, type, source, length and colour.
- Chart settings › Legend: logo, title (symbol, name or both), market status, chart values, bar change, volume and change from the previous day; for indicators: titles, inputs, values and background with opacity.
- Indicator input names are shown in the chosen language (also for scripts that use the same English names).
- Plot types "Line with breaks", "Step line with breaks" and "Area with breaks".

### Fixed
- A source input used inside request.security now reads the other timeframe's candles, as in Pine Script.
- Line, step line and area plots now connect across missing values, as in Pine Script; only the "with breaks" styles leave gaps.
- Moving averages already on the chart from the library are updated to the new version and keep their changed inputs.

### Documentation
- README updated in 5 languages: new in 1.18.0.
