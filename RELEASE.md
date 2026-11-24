# v1.25.0 — Pine functions with several forms
### Changed
- Pine engine: every Pine v6 function with more than one form was checked against the official reference by comparing each form with the equivalent one.
- input.int and input.float accept options as the third positional argument (dropdown instead of a minimum value).
- input() with a price source as default value (for example close) creates a Source input.
- time and time_close support bars_back and timeframe_bars_back in both v6 forms; a number in third position is no longer read as a time zone.

### Documentation
- README updated in 5 languages: new in 1.25.0.
