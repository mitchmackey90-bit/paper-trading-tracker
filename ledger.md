# Paper-Trading Ledger (pretend money)

- Start: Mon Oct 12 2026
- Starting capital: $500.00
- Cash: $196.95

## Holdings
| ticker | qty | avg_cost | cost_basis | stop | target |
|---|---|---|---|---|---|
| FRO | 2.6923 | 59.429 | 160.00 | 57.90 | 62.50 |
| DHT | 5.3131 | 26.35 | 140.00 | 25.40 | 27.80 |

## Trades log
| time_utc | action | ticker | qty | price | total | reason |
|---|---|---|---|---|---|---|
| 2026-10-12T13:55:49Z | BUY | FRO | 2.6923 | 59.429 | 160.00 | Day gainer +5.9% (prev close 56.10), tanker sector strength alongside DHT; grinding to new intraday highs (last 5m closes 58.77→59.43, HOD 59.53). Momentum continuation. Stop 57.90 (below day low 58.00), target 62.50. Price: Yahoo Finance chart API 13:55 UTC. |
| 2026-10-12T13:55:49Z | BUY | DHT | 5.3131 | 26.35 | 140.00 | Day gainer +7.0% (prev 24.64), same tanker theme; holding near HOD 26.46 after reclaiming 26.3. Stop 25.40 (under day low 25.50), target 27.80. Price: Yahoo Finance 13:55 UTC. |
| 2026-10-12T13:55:49Z | BUY | ASTS | 1.8765 | 53.29 | 100.00 | +4.4% gainer, heavy volume (~7M shares in 25 min). Pulled back from HOD 54.67, holding above day low 52.81 — smaller size since momentum fading. Stop 52.40, target 56.50. Price: Yahoo Finance 13:55 UTC. |
| 2026-10-12T14:04:53Z | BUY | MDT | 0.8621 | 92.795 | 80.00 | +4.9% large-cap gainer (prev 88.48) on news its MiniMed exchange offer was oversubscribed; orderly grind to new HOD 92.78 with higher lows since 13:35. Catalyst-backed, lower volatility than the tankers. Stop 91.20 (under 91.25 consolidation), target 95.50. Price: Yahoo Finance 14:04 UTC. |
| 2026-10-12T14:35:22Z | SELL | MDT | 0.8621 | 91.2 | 78.62 | Bot1 stop-out: MDT pierced 91.20 stop (1m lows to 90.885, day LOD 90.71 after last check left it at 91.23). Fill at stop. PnL vs $80 cost ≈ -$1.38. Price: Yahoo Finance 2026-10-12T14:35:22Z. |
| 2026-10-12T18:14:41Z | SELL | ASTS | 1.8765 | 52.40 | 98.33 | Jr stop-out: ASTS pierced 52.40 stop on the 18:10 1m bar (low 52.22 on 129k, heaviest bar in the hour), new LOD 52.05 at 18:13; last 52.175. Fill at stop per team convention. PnL vs $100 cost ≈ -$1.67. Price: Yahoo Finance chart API 2026-10-12T18:14:41Z. |

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
- 2026-10-12T16:50:43Z — total $494.68, cash $98.62 (Jr mark, no trade; FRO 58.725, DHT 25.88, ASTS 53.53 marked; no stops/targets hit)
- 2026-10-12T17:04:05Z — total $493.62, cash $98.62 (Bot1 mark, no trade; FRO 58.565, DHT 25.80, ASTS 53.42 marked; no stops/targets hit)
- 2026-10-12T17:04:39Z — total $493.73, cash $98.62 (Bot4 mark, no trade; FRO 58.60, DHT 25.82, ASTS 53.373 marked; no stops/targets hit)
- 2026-10-12T17:04:44Z — total $493.75, cash $98.62 (Stock Bot mark, no trade; FRO 58.60, DHT 25.82, ASTS 53.385 marked; no stops/targets hit)

- 2026-10-12T17:06:48Z — total $494.02, cash $98.62 (Bot2 mark, no trade; FRO 58.61, DHT 25.82, ASTS 53.515 marked; no stops/targets hit)
- 2026-10-12T17:11:27Z — total $494.02, cash $98.62 (Jr mark, no trade; FRO 58.68, DHT 25.835, ASTS 53.37 marked; no stops/targets hit)

- 2026-10-12T17:18:59Z — total $493.12, cash $98.62 (Bot1 mark, no trade; FRO 58.50, DHT 25.76, ASTS 53.36 marked; no stops/targets hit)
- 2026-10-12T17:23:36Z — total $493.63, cash $98.62 (Stock Bot mark, no trade; FRO 58.575, DHT 25.805, ASTS 53.40 marked; no stops/targets hit)

- 2026-10-12T17:23:45Z — total $493.48, cash $98.62 (Bot4 mark, no trade; FRO 58.57, DHT 25.805, ASTS 53.324 marked; no stops/targets hit)

- 2026-10-12T17:24:17Z — total $493.49, cash $98.62 (Bot2 mark, no trade; FRO 58.55, DHT 25.795, ASTS 53.39 marked; no stops/targets hit)
- 2026-10-12T17:27:18Z — total $492.67, cash $98.62 (Jr mark, no trade; FRO 58.41, DHT 25.73, ASTS 53.335 marked; no stops/targets hit)
- 2026-10-12T17:37:10Z — total $491.81, cash $98.62 (Bot1 mark, no trade; FRO 58.305, DHT 25.67, ASTS 53.20 marked; no stops/targets hit — new afternoon lows on all three)
- 2026-10-12T17:38:21Z — total $491.76, cash $98.62 (Bot4 mark, no trade; FRO 58.32, DHT 25.66, ASTS 53.18 marked; no stops/targets hit)
- 2026-10-12T17:38:16Z — total $491.73, cash $98.62 (Stock Bot mark, no trade; FRO 58.32, DHT 25.66, ASTS 53.165 marked; no stops/targets hit)
- 2026-10-12T17:42:16Z — total $493.05, cash $98.62 (Bot2 mark, no trade; FRO 58.58, DHT 25.835, ASTS 53.00 marked; no stops/targets hit — tankers bouncing off afternoon lows, ASTS drifting toward 52.77 LOD, 0.60 above stop)
- 2026-10-12T17:43:32Z — total $493.40, cash $98.62 (Jr mark, no trade; FRO 58.62, DHT 25.865, ASTS 53.0399 marked; no stops/targets hit — tankers bouncing off 17:37–17:39 afternoon lows, ASTS still under entry near LOD 52.77)

- 2026-10-12T17:50:13Z — total $493.85, cash $98.62 (Bot1 mark, no trade; FRO 58.72, DHT 25.885, ASTS 53.081 marked; no stops/targets hit — tankers holding bounce off 17:37 lows, ASTS still soft under entry)

- 2026-10-12T17:53:17Z — total $493.51, cash $98.62 (Bot4 mark, no trade; FRO 58.67, DHT 25.865, ASTS 53.03 marked; no stops/targets hit — tankers holding bounce off 17:37 lows, ASTS soft under entry near LOD)

- 2026-10-12T17:55:29Z — total $493.28, cash $98.62 (Stock Bot mark, no trade; FRO 58.67, DHT 25.875, ASTS 52.88 marked; no stops/targets hit — tankers holding bounce off 17:37 lows under lunch coil; ASTS soft under entry, pressing toward LOD 52.77, stop 52.40 ~0.9% away)

- 2026-10-12T17:57:14Z — total $493.45, cash $98.62 (Bot2 mark, no trade; FRO 58.685, DHT 25.885, ASTS 52.92 marked; no stops/targets hit — tankers holding bounce off 17:37 lows under lunch coil; ASTS soft under entry, ~0.15 above LOD 52.77, stop 52.40 ~1.0% away)
- 2026-10-12T18:02:00Z — total $492.19, cash $98.62 (Jr mark, no trade; FRO 58.55, DHT 25.805, ASTS 52.67 marked; no stops/targets hit — ASTS broke LOD 52.77 on an 87k bar (new LOD 52.618), stop 52.40 ~0.5% away)
- 2026-10-12T18:04:20Z — total $491.79, cash $98.62 (Bot1 mark, no trade; FRO 58.52, DHT 25.765, ASTS 52.61 marked; no stops/targets hit — ASTS new LOD 52.56, stop 52.40 ~0.4% away)
- 2026-10-12T18:07:39Z — total $491.55, cash $98.62 (Bot4 mark, no trade; FRO 58.50, DHT 25.73, ASTS 52.61 marked; no stops/targets hit — ASTS new LOD 52.47 at 18:04, stop 52.40 only ~0.4% from last, 0.07 under LOD; tankers drifting near afternoon lows)
- 2026-10-12T18:09:30Z — total $492.07, cash $98.62 (Bot2 mark, no trade; FRO 58.59, DHT 25.80, ASTS 52.56 marked; no stops/targets hit — ASTS held 52.47 LOD, stop 52.40 ~0.3% away; tankers ticking up off 18:05 lows)
- 2026-10-12T18:10:02Z — total $492.58, cash $98.62 (Stock Bot mark, no trade; FRO 58.725, DHT 25.86, ASTS 52.471 marked; no stops/targets hit — ASTS tagged new LOD 52.47 at 18:04 and is back there, 0.07 above 52.40 stop; tankers bounced off 18:05 lows)
- 2026-10-12T18:14:41Z — total $492.65, cash $196.95 (Jr stopped out ASTS @ 52.40; FRO 58.76, DHT 25.88 marked; no other stops/targets)
- 2026-10-12T18:18:21Z — total $493.01, cash $196.95 (Bot1 mark, no trade; FRO 58.815, DHT 25.92 marked; no stops/targets hit — tankers firming off afternoon lows after ASTS stop-out)
- 2026-10-12T18:19:50Z — total $492.76, cash $196.95 (Bot4 mark, no trade; FRO 58.75, DHT 25.905 marked; no stops/targets hit — tankers stalled under lunch coil, slipped off 18:16 pop)
- 2026-10-12T18:22:08Z — total $493.64, cash $196.95 (Bot2 mark, 1:22 PM CT, no trade; FRO 58.84, DHT 26.025 marked; no stops/targets hit — DHT poked back above the ~26.0 lunch coil on an 80k bar at 18:21, FRO still capped under ~58.9)
- 2026-10-12T18:23:17Z — total $493.47, cash $196.95 (Stock Bot mark, 1:23 PM CT, no trade; FRO 58.835, DHT 25.995 marked; no stops/targets hit — DHT's 18:21 poke above the ~26.0 coil faded back under on the next bar, FRO still under ~58.9)
- 2026-10-12T18:30:36Z — total $493.75, cash $196.95 (Jr mark, 1:30 PM CT, no trade; FRO 58.88, DHT 26.025 marked; no stops/targets hit — DHT holding just above the ~26.0 coil for 7 bars, FRO testing ~58.9 but not through)
- 2026-10-12T18:32:50Z — total $493.74, cash $196.95 (Bot4 mark, 1:32 PM CT, no trade; FRO 58.84, DHT 26.045 marked; no stops/targets hit — DHT still coiled just above ~26.0, FRO capped under ~58.9; both underwater vs entry, no fresh catalyst to redeploy cash)
- 2026-10-12T18:35:59Z — total $493.45, cash $196.95 (Bot2 mark, 1:35 PM CT, no trade; FRO 58.762, DHT 26.03 marked; no stops/targets hit — FRO slipped back under ~58.9 after the 18:24–18:25 poke, DHT still coiled just above ~26.0; both underwater vs entry, cash idle with no fresh catalyst)
- 2026-10-12T18:36:37Z — total $493.48, cash $196.95 (Bot1 mark, 1:36 PM CT, no trade; FRO 58.78, DHT 26.025 marked; no stops/targets hit — DHT still coiled just above ~26.0, FRO fading under ~58.9; both underwater vs entry, no FRO reclaim so no add)
- 2026-10-12T18:40:05Z — total $493.45, cash $196.95 (Stock Bot mark, 1:40 PM CT, no trade; FRO 58.77, DHT 26.025 marked; no stops/targets hit — DHT still coiled just above ~26.0, FRO faded back off 58.89 under the ~58.9 coil)
- 2026-10-12T18:42:36Z — total $493.50, cash $196.95 (Bot4 mark, 1:42 PM CT, no trade; FRO 58.82, DHT 26.01 marked; no stops/targets hit — DHT dipped to 25.98 on 18:41 but holding ~26.0 coil, FRO bounced off 58.72 still under ~58.9; both underwater vs entry, no fresh catalyst to redeploy cash)
- 2026-10-12T18:47:30Z — total $493.96, cash $196.95 (Jr mark, 1:47 PM CT, no trade; FRO 58.84, DHT 26.085 marked; no stops/targets hit — DHT poked 26.11 on a 63k 18:46 bar but still under entry; FRO still capped under ~58.9, Jr add condition unmet)
- 2026-10-12T18:48:28Z — total $493.88, cash $196.95 (Bot1 mark, 1:48 PM CT, no trade; FRO 58.83, DHT 26.075 marked; no stops/targets hit — DHT holding the 18:46 push above ~26.0 (26.075, still under 26.35 entry); FRO 58.83 still capped under ~58.9, add condition unmet)
- 2026-10-12T18:49:45Z — total $493.74, cash $196.95 (Bot2 mark, 1:49 PM CT, no trade; FRO 58.80, DHT 26.065 marked; no stops/targets hit — DHT holding just above ~26.0 after the 18:46 push, still under 26.35 entry; FRO 58.80 still capped under ~58.9, no fresh catalyst to redeploy cash)
- 2026-10-12T18:51:48Z — total $493.72, cash $196.95 (Stock Bot mark, 1:51 PM CT, no trade; FRO 58.81, DHT 26.055 marked; no stops/targets hit — DHT holding ~26.06 after the 18:46 push, FRO still under ~58.9 coil; SPY new LOD 777.06)
- 2026-10-12T18:52:48Z — total $493.80, cash $196.95 (Bot4 mark, 1:52 PM CT, no trade; FRO 58.81, DHT 26.07 marked; no stops/targets hit — DHT holding ~26.07 after the 18:46 push, still under 26.35 entry; FRO flat at 58.81 under ~58.9 coil; both underwater, no fresh catalyst to redeploy cash)

- 2026-10-12T19:01:45Z — total $493.62, cash $196.95 (Bot2 mark, 2:01 PM CT, no trade; FRO 58.805, DHT 26.04 marked; no stops/targets hit — DHT slipped to 26.04 off the ~26.07 coil, still under 26.35 entry; FRO flat ~58.80 under ~58.9; both underwater, cash idle, no fresh catalyst)
- 2026-10-12T19:02:08Z — total $493.60, cash $196.95 (Bot1 mark, 2:02 PM CT, no trade; FRO 58.805, DHT 26.035 marked; no stops/targets hit — DHT easing off the 18:46 shelf (26.04 on 8k), still under 26.35 entry; FRO pinned 58.78–58.84 under ~58.9, add condition unmet)

- 2026-10-12T19:02:16Z — total $493.60, cash $196.95 (Jr mark, 2:02 PM CT, no trade; FRO 58.805, DHT 26.035 marked; no stops/targets hit — DHT still coiled above ~26.0 under entry, FRO still under ~58.9 coil; Jr add condition unmet)
- 2026-10-12T19:03:42Z — total $493.66, cash $196.95 (Bot4 mark, 2:03 PM CT, no trade; FRO 58.81, DHT 26.045 marked; no stops/targets hit — FRO flat 58.76–58.83 under ~58.9 coil, DHT holding ~26.04 above the ~26.0 shelf, both still under entry; cash idle, no fresh catalyst)
- 2026-10-12T19:04:27Z — total $493.66, cash $196.95 (Stock Bot mark, 2:04 PM CT, no trade; FRO 58.81, DHT 26.045 marked; no stops/targets hit — both flat in 3:00 PM ET window on light volume, still under entry; SPY 777.31 hugging LOD 777.05)
- 2026-10-12T19:12:09Z — total $493.24, cash $196.95 (Jr mark, 2:12 PM CT, no trade; FRO 58.80, DHT 25.97 marked; no stops/targets hit — FRO tagged 58.95 on the 19:10 bar (close 58.93) but was rejected back to 58.80 next bar, DHT slipped back under the ~26.0 shelf; Jr add condition unmet)
- 2026-10-12T19:12:42Z — total $493.37, cash $196.95 (Bot1 mark, 2:12 PM CT, no trade; FRO 58.82, DHT 25.985 marked; no stops/targets hit — FRO's 19:10 tag of 58.95 rejected on the 14k 19:11 bar, DHT back under ~26.0 shelf; add condition unmet)
- 2026-10-12T19:12:56Z — total $493.40, cash $196.95 (Bot2 mark, 2:12 PM CT, no trade; FRO 58.83, DHT 25.985 marked; no stops/targets hit — FRO rejected the 19:10 poke to 58.95 back to 58.83, DHT still under the ~26.0 shelf at 25.985; both underwater vs entry, cash idle, no fresh catalyst)
- 2026-10-12T19:16:30Z — total $493.09, cash $196.95 (Stock Bot mark, 2:16 PM CT, no trade; FRO 58.775, DHT 25.955 marked; no stops/targets hit — FRO sliding off the 19:10 58.95 rejection, DHT under the ~26.0 shelf on a 16k 19:15 bar; SPY 777.31 near LOD 777.05)
- 2026-10-12T19:17:50Z — total $493.21, cash $196.95 (Bot4 mark, 2:17 PM CT, no trade; FRO 58.76, DHT 25.985 marked; no stops/targets hit — FRO drifting lower after the 19:10 58.95 rejection, ~0.14 under the ~58.9 lid; DHT bounced off 25.94 (19:15) but still under the ~26.0 shelf and 26.35 entry; SPY 777.24 near LOD 777.05; cash idle, no fresh catalyst)
- 2026-10-12T19:23:32Z — total $493.34, cash $196.95 (Bot1 mark, 2:23 PM CT, no trade; FRO 58.77, DHT 26.005 marked; no stops/targets hit — FRO still under ~58.9 after 19:10 rejection (19:18 low 58.68 then flat ~58.77); DHT poked 26.10 on 19:21 37k bar then faded to 26.005, chopping the ~26.0 shelf; Jr add condition unmet; SPY 777.29 near LOD 777.05)

- 2026-10-12T19:24:11Z — total $493.25, cash $196.95 (Bot2 mark, 2:24 PM CT, no trade; FRO 58.765, DHT 25.99 marked; no stops/targets hit — FRO flat ~58.77 under ~58.9 after 19:10 rejection, DHT faded back under ~26.0 shelf after 19:21 poke to 26.10; both underwater vs entry, cash idle, no fresh catalyst)
- 2026-10-12T19:26:41Z — total $493.16, cash $196.95 (Jr mark, 2:26 PM CT, no trade; FRO 58.77, DHT 25.97 marked; no stops/targets hit — FRO drifting 58.72–58.82 under ~58.9 after the 19:10 rejection, DHT faded the 19:21 poke to 26.10 back under the ~26.0 shelf; Jr add condition unmet)
- 2026-10-12T19:28:16Z — total $492.82, cash $196.95 (Bot4 mark, 2:28 PM CT, no trade; FRO 58.715, DHT 25.935 marked; no stops/targets hit — both drifting to fresh afternoon lows on light volume (FRO 58.72, DHT 25.935, under the ~26.0 shelf), still well above stops 57.90 / 25.40 and under entry; SPY 777.30 near LOD 777.05; cash idle, no fresh catalyst)
- 2026-10-12T19:35:00Z — total $492.77, cash $196.95 (Stock Bot mark, 2:35 PM CT, no trade; FRO 58.685, DHT 25.94 marked; no stops/targets hit — both grinding lower on light volume (FRO 19:31 low 58.61, DHT 19:32 low 25.89) while SPY lifts off LOD to 777.56; stops 57.90 / 25.40 intact)
- 2026-10-12T19:36:39Z — total $493.08, cash $196.95 (Bot2 mark, 2:36 PM CT, no trade; FRO 58.75, DHT 25.965 marked; no stops/targets hit — both bouncing modestly off 19:31–19:32 afternoon lows (FRO 58.61, DHT 25.89) as SPY lifts off LOD to 777.85; still under entry, well above stops 57.90 / 25.40; cash idle, no fresh catalyst)
- 2026-10-12T19:36:32Z — total $493.08, cash $196.95 (Bot1 mark, 2:36 PM CT, no trade; FRO 58.75, DHT 25.965 marked; no stops/targets hit — small bounce off 19:31–19:32 afternoon lows (FRO 58.61, DHT 25.89) as SPY lifts to 777.83 on an 90k 19:35 bar; tankers still under ~58.9 / ~26.0 lids and entry; stops 57.90 / 25.40 intact)
- 2026-10-12T19:40:18Z — total $493.65, cash $196.95 (Jr mark, 2:40 PM CT, no trade; FRO 58.835, DHT 26.03 marked; no stops/targets hit — both bounced off the 19:31–19:32 afternoon lows with SPY (FRO back to 58.91 high on the 15k 19:39 bar, DHT reclaimed ~26.0 at 26.03–26.08); FRO still under the 58.95 add trigger, so Jr add condition unmet)
- 2026-10-12T19:42:36Z — total $493.66, cash $196.95 (Bot4 mark, 2:42 PM CT, no trade; FRO 58.827, DHT 26.035 marked; no stops/targets hit — both holding the bounce off the 19:31–19:32 afternoon lows (FRO 58.61, DHT 25.89) with SPY 777.79 off LOD 777.05; FRO topped 58.906 on the 19:39 bar but still capped under ~58.9 lid, DHT holding just above ~26.0 shelf (26.03–26.08); both under entry, well above stops 57.90 / 25.40; cash idle, no fresh catalyst)
- 2026-10-12T19:46:07Z — total $493.82, cash $196.95 (Bot1 mark, 2:46 PM CT, no trade; FRO 58.85, DHT 26.055 marked; no stops/targets hit — FRO 6th approach to the ~58.9 lid topped 58.906 (19:39) with closes stuck 58.81–58.85 on 7–17k bars, no >58.95 close on >20k; DHT holding above ~26.0 for ~9 bars (26.015–26.05) on 5–22k, still under 26.35 entry; add condition unmet)
- 2026-10-12T19:46:10Z — total $493.77, cash $196.95 (Stock Bot mark, 2:46 PM CT, no trade; FRO 58.85, DHT 26.045 marked; no stops/targets hit — 14 min to close, tankers flat-coiled (FRO 58.79–58.87 under ~58.9 lid, DHT 26.02–26.08 holding just above ~26.0) on 8–22k bars; SPY 777.84 off LOD 777.05; no new entries this late, holding overnight with stops 57.90 / 25.40)
- 2026-10-12T19:46:34Z — total $493.64, cash $196.95 (Bot2 mark, 2:46 PM CT, no trade; FRO 58.82, DHT 26.035 marked; no stops/targets hit — 14 min to close, FRO ticked back to 58.82 still under the ~58.9 lid, DHT 26.035 holding just above ~26.0 on 13–20k bars; SPY 777.81 off LOD 777.05; no new entries this late, holding overnight with stops 57.90 / 25.40)
- 2026-10-12T19:49:55Z — total $494.27, cash $196.95 (Jr mark, 2:49 PM CT, no trade; FRO 58.935, DHT 26.095 marked; no stops/targets hit — late tanker pop: FRO 7th approach printed 58.935 (19:48 bar high 58.91 on 12.6k) but no >58.95 close on a >20k bar, DHT pushed 26.12 on a 40k 19:48 bar (heaviest in ~30 min) still under 26.35 entry; ~10 min to close, no new entries, holding overnight with stops 57.90 / 25.40)
- 2026-10-12T19:52:17Z — total $494.21, cash $196.95 (Bot4 mark, 2:52 PM CT, no trade; FRO 58.945, DHT 26.079 marked; no stops/targets hit — FRO 19:50 bar closed 58.96 on 17.4k (above 58.95 but under the >20k add bar), DHT faded to 26.08 after the 19:48 40k poke to 26.12; both still under entry, stops 57.90 / 25.40 intact; ~8 min to close, no new entries, holding overnight)
- 2026-10-12T19:56:30Z — total $494.48, cash $196.95 (Stock Bot mark, 2:56 PM CT, no trade; FRO 58.995, DHT 26.105 marked; no stops/targets hit — FRO finally cleared the ~58.9 lid on the 15:53 ET bar (close 59.06 on 32.6k, HOD-area 59.08 on 75.7k next bar), DHT holding 26.10–26.13 on 30–45k bars; both still under entry; ~4 min to close, no new entries, holding overnight with stops 57.90 / 25.40)
- 2026-10-12T19:57:41Z — total $495.35, cash $196.95 (Bot1 mark, 2:57 PM CT, no trade; FRO 59.13, DHT 26.20 marked; no stops/targets hit — FRO's lid break holding into the bell (19:54–19:56 closes 59.01–59.06 on 47–76k bars, last 59.13), DHT firming to 26.20 on a 70k 19:56 bar, still under 26.35 entry; ~3 min to close, no new entries, holding overnight with stops 57.90 / 25.40)
- 2026-10-12T19:58:49Z — total $495.22, cash $196.95 (Bot2 mark, 2:58 PM CT, no trade; FRO 59.14, DHT 26.17 marked; no stops/targets hit — ~2 min to close, FRO holding the ~58.9 lid break (19:53–19:57 closes 59.01–59.14 on 32–76k bars), DHT firming to 26.17 after a 214k 19:57 bar but still under 26.35 entry; both underwater vs entry, stops 57.90 / 25.40 intact; no new entries this late, holding overnight)
- 2026-10-12T20:02:01Z — total $495.83, cash $196.95 (Jr post-close mark, 3:02 PM CT, no trade — market closed; FRO 59.22, DHT 26.245 marked at Yahoo regularMarketPrice close; no stops/targets hit — closing rush lifted both: FRO's lid break held to a 59.22 close on a 145k final bar (~0.21 under 59.429 entry), DHT closed 26.245 on 200k+ final bars (~0.10 under 26.35 entry); holding overnight with stops 57.90 / 25.40)
- 2026-10-12T20:05:00Z — total $495.83, cash $196.95 (Bot4 post-close mark, 3:05 PM CT, no trade — market closed; FRO 59.22, DHT 26.245 at Yahoo regularMarketPrice close, unchanged from Jr's post-close mark; no stops/targets hit; holding overnight with stops 57.90 / 25.40)

- 2026-10-12T20:09:41Z — total $495.83, cash $196.95 (Bot1 post-close mark, 3:09 PM CT, no trade — market closed; FRO 59.22, DHT 26.245 at Yahoo regularMarketPrice close, unchanged from Jr/Bot4 post-close marks; no stops/targets hit; holding overnight with stops 57.90 / 25.40)
