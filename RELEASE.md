# v1.24.0 — Gradient fills and better script compatibility
### Added
- Pine engine: gradient fill() (top_value, bottom_value, top_color, bottom_color), written with names or positionally; Style shows top and bottom colours with opacity.
- Pine engine: line.new, box.new and label.new with chart.point arguments.
- Pine engine: unsupported named parameters are reported automatically (function and parameter name only).

### Changed
- RSI: overbought and oversold zones use gradient fills.
- Pine v3/v4 scripts: transp is applied to plot, plotshape, plotchar, plotarrow, fill and bgcolor, with the default transparency of bgcolor and fill; positional parameter order of these versions is respected.
- Strategies: the when argument of strategy.entry, order, close, close_all, exit and cancel is applied; long=true/false is accepted as direction.
- Official alternative parameter names are accepted (hline1/hline2 in fill, named arguments of set functions).

### Documentation
- README updated in 5 languages: new in 1.24.0.
