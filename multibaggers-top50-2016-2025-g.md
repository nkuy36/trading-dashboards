# Top-50 Annual Winners 2016–2025 — Grok independent pass

**Date:** 2026-08-05 · **Tag:** `-g` (Grok)  
**Interactive dashboard:** [multibaggers-top50-2016-2025-g.html](./multibaggers-top50-2016-2025-g.html)  
**Live:** https://nkuy36.github.io/trading-dashboards/multibaggers-top50-2016-2025-g.html

## Scope
- 500 rows: top 50 US stocks by calendar-year total return each year 2016–2025
- Liquidity gate: prior-year ADV ≥ $10M, raw price ≥ $5, ≥200 trading days
- Entry features from local parquets only (no market APIs)

## Core findings
1. **Bimodal entry geometry** — drawdown reversals (2016, 2023) vs momentum continuation (2018, 2024)
2. **Only ~9% near 2-year highs** at Jan 1 of the cohort year — "buy new highs" is not universal
3. **~49% had negative prior-year return** (clean sample)
4. **Liquidity above $10M does not sort winner magnitude**
5. **Driver mix is regime-dependent** (cyclical energy years vs secular AI/SaaS/COVID years)
6. **Two-sleeve screener + regime switch** required
7. **15 data_suspect rows** in top-50 (junk delisted series) + systematic entity duplicates

## Driver counts (500)
| Driver | n |
|---|---:|
| secular_theme | 175 |
| cyclical | 148 |
| catalyst | 101 |
| turnaround | 49 |
| data_suspect | 15 |
| spinoff | 8 |
| squeeze | 3 |
| re-rating | 1 |

## Screener (Jan 1 only)
- **Sleeve A (drawdown):** dist to 2y high ≤ −45%, prior ret ≤ −15%, liquid, cycle/beaten-down growth — use after crash years
- **Sleeve B (continuation):** prior +25% to +120%, dist −35% to −5%, active theme — use in live bull themes

## vs Claude pass
- Same science on geometry/regime/two screens
- ~72% driver label agreement
- Grok: stronger junk kill-list · Claude: cascade decomp + dup class

## Local project files
- Full analysis: `GROK_WORK/GROK_ANALYSIS.md`
- Annotated CSV: `GROK_WORK/grok_top50_annotated.csv`
- Comparison: `GROK_WORK/COMPARE_VS_CLAUDE.md`

*Descriptive research only. Not trade advice. Local dataset may contain residual feed errors — see data_suspect list.*
