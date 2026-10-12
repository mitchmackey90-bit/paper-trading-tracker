# Paper-Trading Ledger (pretend money)

- Start: Mon Oct 12 2026
- Starting capital: $500.00
- Cash: $20.00

## Holdings
| ticker | qty | avg_cost | cost_basis | stop | target |
|---|---|---|---|---|---|
| FRO | 2.6923 | 59.429 | 160.00 | 57.90 | 62.50 |
| DHT | 5.3131 | 26.35 | 140.00 | 25.40 | 27.80 |
| ASTS | 1.8765 | 53.29 | 100.00 | 52.40 | 56.50 |
| MDT | 0.8621 | 92.795 | 80.00 | 91.20 | 95.50 |

## Trades log
| time_utc | action | ticker | qty | price | total | reason |
|---|---|---|---|---|---|---|
| 2026-10-12T13:55:49Z | BUY | FRO | 2.6923 | 59.429 | 160.00 | Day gainer +5.9% (prev close 56.10), tanker sector strength alongside DHT; grinding to new intraday highs (last 5m closes 58.77→59.43, HOD 59.53). Momentum continuation. Stop 57.90 (below day low 58.00), target 62.50. Price: Yahoo Finance chart API 13:55 UTC. |
| 2026-10-12T13:55:49Z | BUY | DHT | 5.3131 | 26.35 | 140.00 | Day gainer +7.0% (prev 24.64), same tanker theme; holding near HOD 26.46 after reclaiming 26.3. Stop 25.40 (under day low 25.50), target 27.80. Price: Yahoo Finance 13:55 UTC. |
| 2026-10-12T13:55:49Z | BUY | ASTS | 1.8765 | 53.29 | 100.00 | +4.4% gainer, heavy volume (~7M shares in 25 min). Pulled back from HOD 54.67, holding above day low 52.81 — smaller size since momentum fading. Stop 52.40, target 56.50. Price: Yahoo Finance 13:55 UTC. |
| 2026-10-12T14:04:53Z | BUY | MDT | 0.8621 | 92.795 | 80.00 | +4.9% large-cap gainer (prev 88.48) on news its MiniMed exchange offer was oversubscribed; orderly grind to new HOD 92.78 with higher lows since 13:35. Catalyst-backed, lower volatility than the tankers. Stop 91.20 (under 91.25 consolidation), target 95.50. Price: Yahoo Finance 14:04 UTC. |

## Value history (append-only)
- 2026-10-12T13:46:10Z — total $500.00, cash $500.00
- 2026-10-12T13:55:49Z — total $500.00, cash $100.00 (opened FRO, DHT, ASTS)
- 2026-10-12T14:04:53Z — total $499.69, cash $20.00 (bought MDT; FRO 59.12, DHT 26.29, ASTS 53.74 marked, no stops hit)
- 2026-10-12T14:07:33Z — total $497.44, cash $20.00 (Bot1 mark, no trade; FRO 59.09, DHT 26.17, ASTS 53.22, MDT 92.15 marked; no stops/targets hit)
- 2026-10-12T14:12:46Z — total $499.22, cash $20.00 (Bot2 mark, no trade; FRO 59.24, DHT 26.22, ASTS 53.92, MDT 91.92 marked; no stops/targets hit)
- 2026-10-12T14:15:11Z — total $498.81, cash $20.00 (Bot4 mark, no trade; FRO 59.30, DHT 26.25, ASTS 53.73, MDT 91.53 marked; no stops/targets hit)
