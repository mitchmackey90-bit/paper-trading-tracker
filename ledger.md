# Paper-Trading Ledger (pretend money)

- Start: Mon Oct 12 2026
- Starting capital: $500.00
- Cash: $98.62

## Holdings
| ticker | qty | avg_cost | cost_basis | stop | target |
|---|---|---|---|---|---|
| FRO | 2.6923 | 59.429 | 160.00 | 57.90 | 62.50 |
| DHT | 5.3131 | 26.35 | 140.00 | 25.40 | 27.80 |
| ASTS | 1.8765 | 53.29 | 100.00 | 52.40 | 56.50 |

## Trades log
| time_utc | action | ticker | qty | price | total | reason |
|---|---|---|---|---|---|---|
| 2026-10-12T13:55:49Z | BUY | FRO | 2.6923 | 59.429 | 160.00 | Day gainer +5.9% (prev close 56.10), tanker sector strength alongside DHT; grinding to new intraday highs (last 5m closes 58.77→59.43, HOD 59.53). Momentum continuation. Stop 57.90 (below day low 58.00), target 62.50. Price: Yahoo Finance chart API 13:55 UTC. |
| 2026-10-12T13:55:49Z | BUY | DHT | 5.3131 | 26.35 | 140.00 | Day gainer +7.0% (prev 24.64), same tanker theme; holding near HOD 26.46 after reclaiming 26.3. Stop 25.40 (under day low 25.50), target 27.80. Price: Yahoo Finance 13:55 UTC. |
| 2026-10-12T13:55:49Z | BUY | ASTS | 1.8765 | 53.29 | 100.00 | +4.4% gainer, heavy volume (~7M shares in 25 min). Pulled back from HOD 54.67, holding above day low 52.81 — smaller size since momentum fading. Stop 52.40, target 56.50. Price: Yahoo Finance 13:55 UTC. |
| 2026-10-12T14:04:53Z | BUY | MDT | 0.8621 | 92.795 | 80.00 | +4.9% large-cap gainer (prev 88.48) on news its MiniMed exchange offer was oversubscribed; orderly grind to new HOD 92.78 with higher lows since 13:35. Catalyst-backed, lower volatility than the tankers. Stop 91.20 (under 91.25 consolidation), target 95.50. Price: Yahoo Finance 14:04 UTC. |
| 2026-10-12T14:35:22Z | SELL | MDT | 0.8621 | 91.2 | 78.62 | Bot1 stop-out: MDT pierced 91.20 stop (1m lows to 90.885, day LOD 90.71 after last check left it at 91.23). Fill at stop. PnL vs $80 cost ≈ -$1.38. Price: Yahoo Finance 2026-10-12T14:35:22Z. |

## Value history (append-only)
- 2026-10-12T13:46:10Z — total $500.00, cash $500.00
- 2026-10-12T13:55:49Z — total $500.00, cash $100.00 (opened FRO, DHT, ASTS)
- 2026-10-12T14:04:53Z — total $499.69, cash $20.00 (bought MDT; FRO 59.12, DHT 26.29, ASTS 53.74 marked, no stops hit)
- 2026-10-12T14:07:33Z — total $497.44, cash $20.00 (Bot1 mark, no trade; FRO 59.09, DHT 26.17, ASTS 53.22, MDT 92.15 marked; no stops/targets hit)
- 2026-10-12T14:12:46Z — total $499.22, cash $20.00 (Bot2 mark, no trade; FRO 59.24, DHT 26.22, ASTS 53.92, MDT 91.92 marked; no stops/targets hit)
- 2026-10-12T14:15:11Z — total $498.81, cash $20.00 (Bot4 mark, no trade; FRO 59.30, DHT 26.25, ASTS 53.73, MDT 91.53 marked; no stops/targets hit)
- 2026-10-12T14:17:38Z — total $500.03, cash $20.00 (Jr mark, no trade; FRO 59.43, DHT 26.33, ASTS 54.10, MDT 91.23 marked; no stops/targets hit — MDT 0.03 above its 91.20 stop)
- 2026-10-12T14:35:22Z — total $498.23, cash $98.62 (Bot1 stopped out MDT @ 91.20; FRO 59.26, DHT 26.245, ASTS 53.6199 marked; no other stops/targets)
- 2026-10-12T14:36:20Z — total $497.34, cash $98.62 (Stock Bot mark, no trade; FRO 59.15, DHT 26.125, ASTS 53.65 marked; MDT already stopped by Bot1 @ 91.20; no stops/targets hit on remaining)
- 2026-10-12T14:43:38Z — total $497.61, cash $98.62 (Bot4 mark, no trade; FRO 59.18, DHT 26.15, ASTS 53.68 marked; no stops/targets hit)
- 2026-10-12T14:48:13Z — total $497.09, cash $98.62 (Bot2 mark, no trade; FRO 59.135, DHT 26.185, ASTS 53.365 marked; no stops/targets hit)
- 2026-10-12T14:48:22Z — total $496.96, cash $98.62 (Jr mark, no trade; FRO 59.11, DHT 26.185, ASTS 53.33 marked; no stops/targets hit)
- 2026-10-12T15:01:47Z — total $494.30, cash $98.62 (Stock Bot mark, no trade; FRO 58.55, DHT 25.885, ASTS 53.565 marked; no stops/targets hit — tankers rolling off HOD)
- 2026-10-12T15:04:01Z — total $494.36, cash $98.62 (Bot1 mark, no trade; FRO 58.59, DHT 25.87, ASTS 53.585 marked; no stops/targets hit)

- 2026-10-12T15:10:22Z — total $493.33, cash $98.62 (Bot4 mark, no trade; FRO 58.39, DHT 25.765, ASTS 53.62 marked; no stops/targets hit)
- 2026-10-12T15:11:50Z — total $493.27, cash $98.62 (Bot2 mark, no trade; FRO 58.37, DHT 25.75, ASTS 53.66 marked; no stops/targets hit)
- 2026-10-12T15:12:27Z — total $493.34, cash $98.62 (Jr mark, no trade; FRO 58.36, DHT 25.765, ASTS 53.666 marked; no stops/targets hit)
- 2026-10-12T15:24:39Z — total $496.27, cash $98.62 (Stock Bot mark, no trade; FRO 59.02, DHT 26.059, ASTS 53.45 marked; no stops/targets hit — tankers bouncing off midday lows)
- 2026-10-12T15:31:52Z — total $495.97, cash $98.62 (Bot1 mark, no trade; FRO 59.11, DHT 26.045, ASTS 53.20 marked; no stops/targets hit)
- 2026-10-12T15:35:19Z — total $494.84, cash $98.62 (Jr mark, no trade; FRO 58.855, DHT 25.925, ASTS 53.305 marked; no stops/targets hit)
- 2026-10-12T15:36:45Z — total $494.86, cash $98.62 (Bot2 mark, no trade; FRO 58.883, DHT 25.95, ASTS 53.205 marked; no stops/targets hit)
- 2026-10-12T15:38:10Z — total $494.98, cash $98.62 (Bot4 mark, no trade; FRO 58.89, DHT 25.955, ASTS 53.24 marked; no stops/targets hit)
- 2026-10-12T15:50:54Z — total $495.83, cash $98.62 (Stock Bot mark, no trade; FRO 58.885, DHT 25.945, ASTS 53.73 marked; no stops/targets hit)
- 2026-10-12T16:00:22Z — total $495.43, cash $98.62 (Jr mark, no trade; FRO 58.88, DHT 25.96, ASTS 53.48 marked; no stops/targets hit)
- 2026-10-12T16:00:40Z — total $495.37, cash $98.62 (Bot4 mark, no trade; FRO 58.87, DHT 25.945, ASTS 53.505 marked; no stops/targets hit)
- 2026-10-12T16:01:25Z — total $495.48, cash $98.62 (Bot1 mark, no trade; FRO 58.87, DHT 25.95, ASTS 53.55 marked; no stops/targets hit)

- 2026-10-12T16:02:07Z — total $495.53, cash $98.62 (Bot2 mark, no trade; FRO 58.85, DHT 25.97, ASTS 53.55 marked; no stops/targets hit)

- 2026-10-12T16:14:37Z — total $495.74, cash $98.62 (Stock Bot mark, no trade; FRO 58.90, DHT 25.995, ASTS 53.52 marked; no stops/targets hit)
- 2026-10-12T16:22:04Z — total $495.89, cash $98.62 (Bot4 mark, no trade; FRO 58.90, DHT 26.02, ASTS 53.53 marked; no stops/targets hit)
- 2026-10-12T16:23:19Z — total $495.72, cash $98.62 (Bot1 mark, no trade; FRO 58.86, DHT 26.005, ASTS 53.54 marked; no stops/targets hit)

- 2026-10-12T16:24:46Z — total $496.20, cash $98.62 (Bot2 mark, no trade; FRO 58.94, DHT 26.025, ASTS 53.623 marked; no stops/targets hit)
- 2026-10-12T16:26:25Z — total $496.42, cash $98.62 (Jr mark, no trade; FRO 58.965, DHT 26.03, ASTS 53.69 marked; no stops/targets hit)
- 2026-10-12T16:40:20Z — total $495.67, cash $98.62 (Stock Bot mark, no trade; FRO 58.91, DHT 25.955, ASTS 53.58 marked; no stops/targets hit)
- 2026-10-12T16:45:25Z — total $495.38, cash $98.62 (Bot4 mark, no trade; FRO 58.895, DHT 25.956, ASTS 53.444 marked; no stops/targets hit)

- 2026-10-12T16:46:12Z — total $495.31, cash $98.62 (Bot1 mark, no trade; FRO 58.90, DHT 25.95, ASTS 53.42 marked; no stops/targets hit)
- 2026-10-12T16:48:29Z — total $494.79, cash $98.62 (Bot2 mark, no trade; FRO 58.75, DHT 25.885, ASTS 53.54 marked; no stops/targets hit)
