# Market dashboard profile

This profile provides a compact market dashboard:

- 80% Stocks and 20% News layout;
- gold futures, PAXG/USD, BTC/USD, USD/UAH, and EUR/UAH watchlist;
- Russian and Ukrainian Google News RSS feeds for gold and crypto.

Copy the three TOML files into the active profile directory, for example:

```text
~/.config/glint/profiles/default/
```

Do not copy credentials into this directory. Configure OpenAI or Anthropic API access separately if you want on-demand article summaries.

The stock graph overlays EMA(20) and EMA(50) on price and shows RSI(14) below
it. MACD(12,26,9) appears as a second lower panel when the terminal is tall
enough. Set `show_ema`, `show_rsi`, or `show_macd` to `false` in `stocks.toml`
when you want to reserve more room for the price chart.
