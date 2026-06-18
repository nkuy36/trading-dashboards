# Gap Attribution — 2026-06-17 (g)

**Generated:** 2026-06-17 ~20:xx ET (Grok gap-attribution-scanner)  
**Universe filter:** US equities >$1B mkt cap, AH move >3% (either dir), AH vol >100k (where available). Primary sources only (EDGAR/IR/gov/hyperscaler/GlobeNewswire direct, company press). ETF-first + direct mover pages (Barchart post-market, stockanalysis afterhours, Investing.com, Yahoo).  
**Data sources (live this session):** web_search + web_fetch on barchart.com post-market, stockanalysis.com/markets/afterhours/, finance.yahoo.com/quote/* (RUM/WDC etc for AH prices, news); GlobeNewswire via Yahoo for RUM press releases; multiple searches for EDGAR/8-K, Fed decision coverage (CNBC, Barron's, Reuters); earnings calendars (Investing.com, digrin, Yahoo). TradingView MCP attempted (quote_get returned non-specific/inconsistent data across symbols); fell back fully to web tools. Anti-hallucination: all prices, %, mcap, catalysts, times from raw tool output this turn. No prior memory.

**Session context:** After Fed (Warsh debut) held rates 3.50-3.75% (unanimous), removed forward guidance language, dot plot showed some 2026 hike expectations. RUM dominant large-cap AH mover on material corporate event. Broad AH lists dominated by microcaps; filtered to qualifying names. WDC continued strong momentum into AH on AI storage theme. Risk tone mixed/neutral post-Fed + event-driven.

---

## ETF Sweep (Foundation — Tiered Discovery)

| ETF | Close/Session | AH/Notes | Vol / Drivers | Top Holdings / Theme Context |
|-----|---------------|----------|---------------|------------------------------|
| **SMH** (Semis/AI) | Strong session (WDC/AMD context) | Quiet-mild positive | — | WDC +4-5%+ day/AH leadership on storage demand; NVDA/AMD/AVGO read-through |
| **QQQ / TQQQ** | Positive session | Mild | — | Tech/AI bid selective |
| **SPY** | Modest positive | Quiet | — | Broad tape post-Fed hold |
| **IBIT / BITO** (BTC-miners/AI pivot) | BTC ~ quiet | — | — | RUM AI infra pivot sympathy (miners-to-cloud theme) |
| **UFO / ARKX** (Space) | — | — | — | No major tonight |
| **URNM / NLR** (Nuclear) | — | — | — | Quiet |

**Catalyst hypothesis:** Single-name event-driven (RUM acquisition close + AI rebrand) + ongoing AI storage momentum (WDC). Fed hold with hawkish tilt (no guidance, hike dots) provides neutral-mixed regime. No broad >3% large-cap AH rotation beyond RUM and momentum names. Micros dominate raw % lists.

**Sources:** web_fetch stockanalysis afterhours tables + Barchart post-market; Yahoo quotes; Fed coverage from CNBC/Barron's/Reuters (raw headlines + decision details).

---

## STEP 1 — TIER 1: ALWAYS REPORT (universe-wide, market-movers)

### A) MAG 7 / HYPERSCALERS (report any news, even if <3% AH move)

| Ticker | Close | Session % | AH % | Catalyst | Primary Source | Type |
|--------|-------|-----------|------|----------|----------------|------|
| NVDA | — | Modest/quiet | Quiet | No material company news isolated. Sector context only. | web searches + Yahoo | SECTOR |
| MSFT | — | Quiet | Quiet | None | — | — |
| GOOGL | — | Quiet | Quiet | None | — | — |
| AMZN | — | Quiet | Quiet | None | — | — |
| META | — | Quiet | Quiet | None | — | — |
| AAPL | — | Quiet | Quiet | None | — | — |
| TSLA | — | Modest | Quiet | Possible Musk/SpaceX halo but no primary | — | OTHER |

No material 8-K or IR releases for Mag7 tonight per scans.

### B) SEMIS BELLWETHERS

- **WDC**: Strong session +~4.56% (close ~712 area per snapshots) + AH continuation +3.5% range noted (to ~737 area in one Yahoo). AI storage demand momentum, new highs, analyst updates. Primary ongoing theme (prior earnings strong, SanDisk swap upcoming June 22). No new single filing today.
- **AMD**: Strong session noted in coverage. AH modest.
- **AVGO, MU, TSM, ASML**: Selective sector bid, no standout >3% isolated AH + fresh primary.

### C) MACRO PROXIES

- Financials (JPM/GS/BAC): Benefited from session risk tone.
- Energy (XOM/CVX): Mixed/headwind from any oil moves.
- Industrials (CAT/DE): Broad lift.
- Overall tape: Post-Fed hold, selective strength in AI/storage.

### D) ANY NAME WITH >10% AH MOVE (regardless of theme, >$1B mcap filter)

- **RUM**: ~+17% AH (close 7.29 → AH 8.53). mcap ~1.58B. Qualifies. See Tier 2 full.
- No other >10% with >$1B mcap + volume in filtered lists (microcaps like LPA etc. excluded).

### E) MATERIAL 8-K FILINGS TODAY

- **RUM**: 8-K for closing of Northern Data acquisition (material agreement/completion + share issuance). Filed ~today alongside press. Primary via company GlobeNewswire + referenced 8-K.
- No other standout material 8-Ks (1.01, 2.01, 5.02 etc.) on >$1B mcap names confirmed in targeted EDGAR/web searches for June 17 filings. "Catalyst unconfirmed — investigate manually" for any missed.

**Primary for RUM:** GlobeNewswire "Rumble Announces Realignment... Quake AI" + "Rumble Closes Acquisition of Northern Data" (3h ago on Yahoo). 8-K references on StockTitan/EDGAR paths (maintenance note on direct sec.gov).

---

## STEP 2 — TIER 2: THEME-ALIGNED MOVERS (your edge tier)

### AI/Compute + Bitcoin Miners → AI Pivot (PRIMARY THEME OF THE NIGHT)

| Ticker | AH % / Price | Vol / mcap | Catalyst + PRIMARY SOURCE | Type | Tomorrow's setup | Conviction |
|--------|--------------|------------|---------------------------|------|------------------|------------|
| **RUM** | +17.01% (8.53 from close 7.29) | Elevated (millions shares noted) / ~1.58B | Closes acquisition of Northern Data AG (adds ~250 MW unmonetized energy capacity + ~22,000 NVIDIA GPUs for cloud/AI). Realignment: two units — Rumble (video platform) + Quake AI (renamed cloud/AI-infra business). Corporate parent rebrand to RUM Group Inc. effective ~June 18. Massive AI infra pivot. | CONTRACT / M&A / REBRAND | Gap-and-go potential on primary validation + GPU capacity news. Stockbee/Qullamaggie: episodic pivot + theme breakout (miners-to-AI adjacent). Watch volume hold. | HIGH |
| **WDC** | +3.5% AH range (after +4.56% session to ~712+) | High | Ongoing AI storage demand momentum + analyst updates. No single new primary event tonight (prior strong Q + future catalysts like SanDisk swap June 22). Hits highs. | THEME MOMENTUM | Continuation / gap-and-go if AI theme holds post-Fed. | MD |

**Primary sources (RUM priority):**
1. Company GlobeNewswire press releases (via Yahoo Finance): "Rumble Closes Acquisition of Northern Data" + rebrand/Quake AI announcement (June 17, 2026).
2. 8-K filing (referenced in coverage/StockTitan for material closing + share/warrant issuance).
3. Yahoo Finance quote page (raw: close 7.29, AH 8.53 +1.24 / +17.01%, mcap 1.578B).

**Catalyst TYPE:** M&A / RESTRUCTURING (AI infra). 

**Stockbee/Qullamaggie context:** High-velocity event-driven move on confirmed acquisition close + capacity news. Strong 3-5 day hold candidate if gaps and holds with volume. RUM fits BTC-miners-to-AI pivot + direct AI/Compute.

**Cluster:** RUM + WDC (storage/GPU ecosystem) form AI infra cluster tonight. RUM is the clear catalyst name.

---

## STEP 3 — TIER 3: EMERGING THEME RADAR (discovery tier — DO NOT SKIP)

- Qualifying large movers limited. RUM is the clear event; others (FR REIT +8%, TPB +14%+, CRH +4.88%, PBT +6.3%, PHM +3.2%, ALL -5.65%) appear in tables but lack fresh material primary catalysts isolated tonight (recent earnings or sector momentum).
- No new emerging sub-sector cluster (e.g. 2+ related names on gov/DoD/policy) beyond the AI infra names above.
- Microcap AH (LPA +67%, ADTX etc.) excluded by mcap/vol filter. No actionable Tier 3 graduation tonight.

If RUM/WDC-style AI infra moves repeat, candidate for deeper theme expansion.

---

## STEP 4 — TIER 4: MACRO / EXOGENOUS (regime tier)

- **Fed June 17 (Warsh debut):** Rates held steady 3.50%-3.75% (unanimous). Statement removed forward guidance language ("not well suited"). Dot plot: no cuts priced in 2026 by many; 9 officials see hike in 2026. Neutral-to-hawkish tilt signaled early in Warsh era. Press conference live coverage (CNBC/Yahoo).
- **No major Treasury auction surprise, China policy, or oil inventory flagged as dominant AH driver.**
- **Geopolitical/Crypto:** Quiet relative to prior sessions.
- **Market implication:** Event-driven + selective theme (AI) over macro. Regime: neutral hold with less dovish bias. Risk-on selective in AI/storage; broad tape quiet post-decision.

**Sources:** Raw coverage (CNBC "Chairman Warsh drastically alters Fed rate statement", Barron's "Interest Rates Kept Steady", Reuters, Yahoo calendar/Fed snippets, raw decision text references).

---

## STEP 5 — TOMORROW'S EARNINGS PREVIEW (filtered)

Tomorrow (Jun 18 2026) BMO/AMC from calendars (Investing.com, digrin.com, Yahoo Finance earnings calendar, Nasdaq):

- **ACN (Accenture plc)**: BMO. Large cap (~110B). Consensus EPS ~3.72-3.75, rev ~18.78-18.9B. Sector read-through to IT/services/AI consulting.
- **KR (Kroger Co.)**: BMO. ~39B mcap. EPS est ~1.58, rev ~45B+. Consumer staple.
- Limited other >$1B or theme-aligned (no Mag7, semis bellwethers, nuclear/space names). Light calendar overall.

**Notable setups:** ACN (theme-adjacent to AI infra spend). Watch options implied moves + historical gaps for these. No major AMC flagged in scan.

**Sources:** web_search + snippets from investing.com earnings calendar, digrin, Yahoo.

---

## STEP 6 — SYNTHESIS: TOMORROW'S GAP MAP

**Top 5 gap-up candidates for tomorrow (Tier 2 theme-aligned first, then magnitude):**
1. **RUM** (AI/Compute + BTC-to-AI pivot, Tier 2) — +17% AH on confirmed Northern Data close + Quake AI rebrand/GPU capacity. Primary sources. Gap-and-go high probability.
2. **WDC** (AI/Compute storage, Tier 2 momentum) — Strong session + AH continuation. Theme tailwind.
3. ACN (earnings BMO, Tier 1/2 adjacent) — If beat/raise on AI demand.
4. Broader AI infra / semis sympathy if RUM/WDC hold.
5. Housing/REIT names (PHM/FR) if sector data supportive (lower conviction).

**Top 3 gap-down / fade risk candidates:**
1. Any post-Fed profit taking in recent runners if hawkish dots weigh.
2. Energy if macro softens.
3. Names without primary follow-through from today (selective).

**Theme of the night:** AI Infrastructure pivot / GPU cloud (RUM acquisition close dominant catalyst; WDC storage momentum). Bullish for theme-aligned.

**Regime read:** Neutral-mixed (Fed hold + no guidance + some hike dots). Selective risk-on in AI/storage. Event-driven over macro.

**EOD entry candidates:** RUM on any dip/hold into close tomorrow if breakout structure forms (3-5d hold potential per Qullamaggie episodic).

**One-paragraph "overnight briefing":** RUM ripped +17% AH on closing the Northern Data deal (250MW + 22k GPUs) and rebranding its cloud unit Quake AI — clean primary catalyst for the AI infra / miners-to-AI theme. WDC extended gains on storage demand. Fed (Warsh #1) held rates as expected but stripped guidance and showed some 2026 hike dots. Tomorrow light but ACN/KR BMO. Focus: RUM gap sustainability + AI cluster follow-through vs. post-Fed digestion. Primary sources locked on RUM.

---

## STEP 7 — ASSUMPTION AUDIT

- Assumed RUM AH volume qualifies (>100k); from table activity it does.
- Assumed no larger undisclosed 8-Ks; searches returned none material.
- Fed tone interpretation (hawkish tilt) from removal of guidance + dots; actual market reaction to be confirmed open.
- No edge claimed on trade; patterns only.

---

**Fact Verification (selected claims from this run):**
- RUM AH +17.01% to 8.53, close 7.29, mcap ~1.578B: web_fetch Yahoo quote page (raw values).
- RUM Northern Data close + Quake AI rebrand: GlobeNewswire press (Yahoo Finance links, dated today).
- Fed hold 3.5-3.75%, no guidance, dots: CNBC/Barron's/Reuters live coverage.
- Tomorrow ACN/KR BMO: Investing.com / digrin calendars.
- All other numbers echoed from tool output.

**Full report (HTML):** gap-attribution-2026-06-17-g.html (self-contained, dark theme, tier filters).

**GitHub:** https://nkuy36.github.io/trading-dashboards/gap-attribution-2026-06-17-g.html (after deploy).

*All catalysts attributed to primary where possible. Aggregators for discovery only.*