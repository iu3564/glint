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

The stock graph shows RSI(14) and MACD(12,26,9) in separate lower panels by
default. Set `show_rsi = false` or `show_macd = false` in `stocks.toml` if a
smaller terminal should reserve more height for the price chart.
