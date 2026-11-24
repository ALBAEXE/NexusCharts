# v1.15.1 — Fixes
### Fixed
- Indicators drawn in a pane below the chart (for example RSI) used the decimals of the symbol's price, such as 5 on EURUSD. They now use the script's precision when it sets one, otherwise 2 decimals, or the price decimals for very small values (for example MACD on EURUSD).
- Changing language while Bar Replay is waiting for a starting point now updates its Cancel and Start here buttons right away.
- Button names read by screen readers (VoiceOver, TalkBack) were always in English; they now follow the chosen language.

### Documentation
- README updated in 5 languages: new in 1.15.1.
