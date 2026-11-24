# v1.26.0 — Rounding half up
### Changed
- Values exactly halfway are rounded up (3971.165 → 3971.17) in math.round with precision, str.tostring with a format, format.mintick, format.percent, format.volume and math.round_to_mintick.
- Prices and values shown on the chart, price scale and legend use the same rounding.
- Rounding no longer depends on binary floating-point representation (for example 3971.16499…).

### Documentation
- README updated in 5 languages: new in 1.26.0.
