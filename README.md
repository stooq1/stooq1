# stooq1

Independent quant research and market-data engineering, mostly crypto perpetuals.

**[strategy-graveyard](https://github.com/stooq1/strategy-graveyard)**: four months of honest tests of retail trading edges (order-book walls, aggressor flow, liquidation cascades, cross-market conductors, daily trend, funding carry, extreme-funding arbitrage on 658 perps), with the infrastructure that produced them: a Binance websocket → ClickHouse collector running unattended since June 2026, a tokenized-index feed, MOEX ISS / Dukascopy fetchers, an event-study and walk-forward framework, and a research journal where every hypothesis is closed with a number.

The headline: at the one-minute horizon on liquid instruments the ratio of edge to costs is 0.4–0.8, across four instruments, two venues and four leaders. The only regime where an edge appeared above costs was the March 2020 panic.

What I do: market-data collectors and pipelines (websockets, ClickHouse, Docker), backtests without lookahead, event studies, honest reviews of other people's backtests. Python, pandas, ClickHouse, Grafana.

Patches to ccxt, cryptofeed, nautilus_trader, vectorbt, zipline-reloaded and hummingbot: [stooq1.com/patches](https://stooq1.com/patches/).

Open to quant-developer and data-engineering work, remote: [mail@stooq1.com](mailto:mail@stooq1.com), [stooq1.com](https://stooq1.com). Write-ups: [posts/](https://github.com/stooq1/strategy-graveyard/tree/main/posts) and [dev.to/stooq1](https://dev.to/stooq1).
