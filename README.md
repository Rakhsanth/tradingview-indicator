# TradingView Indicator

Pine Script v6 starter for a custom TradingView indicator. Clone the repo, paste the script into the Pine Editor, and iterate from there.

## Indicator

`indicators/trend_momentum.pine` plots a fast/slow EMA trend backdrop, an RSI-based momentum tint, and optional long/short markers when trend and momentum agree.

## Use it on TradingView

1. Open [TradingView](https://www.tradingview.com/) and any chart.
2. Open the **Pine Editor** (bottom panel).
3. Paste the contents of `indicators/trend_momentum.pine`.
4. Click **Add to chart**.
5. Save the script to your TradingView account (optional) so it survives reloads.

Inputs you can tune in the indicator settings:

- Fast / slow EMA lengths
- RSI length and overbought / oversold levels
- Show or hide trend fill and signal markers

## Repo layout

```
indicators/trend_momentum.pine   # Pine Script v6 indicator
LICENSE                          # MIT
```

## License

MIT. See [LICENSE](LICENSE).
