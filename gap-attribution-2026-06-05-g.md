# Gap Attribution — 2026-06-05 (g)

**Generated:** 2026-06-05 ~20:15 ET (Grok gap-attribution-scanner)  
**Universe filter:** US equities >$1B mkt cap, AH move >3% (either direction), AH vol >100k (where disclosed). Primary sources only for catalysts. ETF-first cross-ref.  
**Data sources (live tool retrieval this session):** BLS Employment Situation (empsit.nr0.htm), Yahoo Finance quotes (META/NVDA/AVGO/SMH/SPY/MRVL/FLEX/MARA/MU), stockanalysis.com/markets/afterhours/, CNN markets selloff article, CNBC (META equity raise + MRVL/FLEX S&P 500), SEC Form 8-K MSFT (Reid Hoffman), SEC META S-3ASR (debt shelf, Apr 30), S&P DJI index announcement URL via CNBC. TV MCP attempted (batch_run/quote_get returned stale COIN data — **degraded**; Yahoo + prior session scan used as fallback).  
**Session context:** Friday was a major risk-off day (Nasdaq worst since Apr 2025). Pure post-close AH screen shows **no** >$1B names >3% except **MRVL** (+4.57% AH on S&P 500 inclusion). Most large-cap gap risk is **carry-forward from regular session** closes at lows.

---

## ETF Sweep (Foundation — Tiered Discovery)

| ETF | Close | Day % | AH % | Vol | Notes |
|-----|-------|-------|------|-----|-------|
| **SMH** | $569.69 | **-9.22%** | -0.66% ($565.94) | 21.5M | Closed at/near session low. Top holdings: NVDA 15.2%, TSM 9.4%, MU 7.8%, AMD 7.6%, AVGO 7.2% |
| **SOXX** | $539.77 | **-10.44%** | — | 22.2M | Sympathetic semi breakdown (Yahoo peers table) |
| **QQQ** | $705.06 | -3.4% (session) | — | 97.3M | Nasdaq -4.18% |
| **SPY** | $737.55 | -2.58% | -0.32% ($735.19) | 91.1M | SPX 7,383.74 (-2.64%) |
| **XLK** | $180.30 | -6.66% | — | — | Tech sector hit |
| **XLF** | $52.30 | **+0.21%** | — | — | Financials relative strength |
| **XLP** | $83.44 | **+1.71%** | — | — | Defensive rotation |
| **IAK** | $133.60 | **+3.19%** | — | — | Insurance bid |

**🚨 THEME-WIDE BREAKDOWN (DOWN):** Semiconductor / AI hardware complex — synchronized selling across SMH/SOXX and Mag7-adjacent chips after (1) May jobs beat → rate-hike repricing, (2) Broadcom earnings hangover (June 3) + valuation sensitivity, (3) META equity-raise overhang afternoon. Memory (MU -13.25%), networking silicon (MRVL -16.74% session), and BTC-miner complex (MARA -11.24%) all hit. **Counter-trend AH:** MRVL +4.57% on S&P 500 inclusion news (effective June 22).

**Sources:** Yahoo Finance ETF/stock quotes (timestamp ~7:54–7:57 PM EDT Jun 5 2026); stockanalysis AH index row (SPY -0.33%, QQQ -0.62% AH); CNN Jun 5 selloff article.

---

## STEP 1 — TIER 1: ALWAYS REPORT

### A) MAG 7 / HYPERSCALERS

| Ticker | Session | AH | Catalyst (PRIMARY) | Type |
|--------|---------|-----|-------------------|------|
| **META** | $593.00 **-5.51%** | $589.17 -0.65% | FT report (discovery) that Meta may raise tens of billions in equity for AI infra (studying GOOGL $85B convertible structure). **Company statement (CNBC):** spokesperson called report "pure speculation"; "huge opportunities lie ahead in AI… raise capital in the most flexible ways." Meta raised 2026 capex guide to up to $145B (prior context). Not hired banks; may not issue. | POLICY-STAKE / EQUITY OVERHANG |
| **NVDA** | $205.10 **-6.20%** | $204.35 -0.37% | Sympathetic semi selloff + macro (jobs/yields). No new company 8-K tonight. Session low $204.34. | MACRO / SECTOR |
| **GOOGL** | $368.53 -0.98% | — | Alphabet equity-raise context cited as template for META chatter; stock down 4th straight week per CNBC. | CONTEXT |
| **MSFT** | — | — | **8-K Item 5.02 (SEC primary):** Reid Hoffman informed board June 2 he will not stand for re-election at 2026 annual meeting; continues until meeting. Not due to disagreement. Filed June 5, 2026. [SEC 8-K](https://www.sec.gov/Archives/edgar/data/789019/000119312526258667/d26760d8k.htm) | GOVERNANCE |
| **AAPL** | $307.34 -1.25% | — | Quiet vs chip complex | — |
| **AMZN** | $246.03 -3.06% | — | Tech beta | — |
| **TSLA** | $391.00 -6.56% | — | Growth/rates sensitivity | — |

### B) SEMIS BELLWETHERS

| Ticker | Session | AH | Notes |
|--------|---------|-----|-------|
| **AVGO** | $385.73 **-7.92%** | $385.65 -0.02% | Continued digestion of June 3 Q2 FY26 print (primary IR: Q2 rev $22.187B +48%, AI semi $10.8B +143%, Q3 guide ~$29.4B). CNN: "underwhelming guidance" narrative + jobs day. [Broadcom IR](https://investors.broadcom.com/news-releases/news-release-details/broadcom-inc-announces-second-quarter-fiscal-year-2026-financial) |
| **AMD** | $466.38 **-10.86%** | — | Sector contagion; closed weak |
| **MU** | $864.01 **-13.25%** | — | Memory unwind ("parabolic" trade per market commentary) |
| **TSM** | $415.17 -6.69% | — | ADR sympathy |
| **ASML** | $1,641.74 -6.59% | — | Equipment sympathy |

### C) MACRO PROXIES

| Ticker | Session | Notes |
|--------|---------|-------|
| JPM/GS/BAC | Mixed; XLF +0.21% | Financials held up vs tech |
| XOM/CVX | Energy weaker with Brent -2.27% ($92.87) | |
| CAT/DE | Industrials pressured with risk-off | |

### D) ANY NAME WITH >10% SESSION MOVE (>$1B) — magnitude signal

| Ticker | Move | Mkt Cap | Driver |
|--------|------|---------|--------|
| **MRVL** | **-16.74%** session / **+4.57% AH** | ~$231B | Session: semi massacre. AH: S&P 500 inclusion June 22 (see Tier 2) |
| **MU** | -13.25% | ~$974B | Memory/chip unwind + jobs |
| **MARA** | -11.24% | ~$4.7B | BTC -4.5% (~$60,915); miner complex |
| **INTC** | -11.28% | ~$498B | Semi beta |
| **ARM** | -12.84% | ~$366B | Semi beta |

*Pure AH >10% movers on stockanalysis were all <$100M mkt cap (GMHS +85%, YXT -41%, etc.) — excluded.*

### E) MATERIAL 8-K FILINGS TODAY

- **MSFT** — Item 5.02 director departure (Reid Hoffman). Primary: [SEC 8-K June 5, 2026](https://www.sec.gov/Archives/edgar/data/789019/000119312526258667/d26760d8k.htm). Verified.
- **META** — S-3ASR filed April 30, 2026 registers **debt securities** (not equity shelf); $25B note program context. Primary: [SEC S-3ASR](https://www.sec.gov/Archives/edgar/data/1326801/000119312526194008/d102985ds3asr.htm). Equity raise tonight is **unconfirmed** (FT discovery; META denies).
- No other material large-cap 8-Ks (1.01/2.01/4.02/5.02 officer changes beyond MSFT) confirmed in scan. Catalyst unconfirmed — investigate manually for after-midnight EDGAR.

---

## STEP 2 — TIER 2: THEME-ALIGNED MOVERS

### AI / Compute (incl. semis, connectivity, datacenter supply chain)

| Ticker | AH % | Vol context | Theme | Catalyst (PRIMARY URL) | Type | Tomorrow setup |
|--------|------|-------------|-------|------------------------|------|----------------|
| **MRVL** | **+4.57%** ($263.47→$275.50) | 88.8M session | AI/Compute connectivity | **S&P 500 inclusion effective June 22** — Marvell + Flex added; replace POOL, CPB. [S&P DJI announcement PDF](https://www.spglobal.com/spdji/en/documents/indexnews/announcements/20260605-1483743/1483743_shuffle546-june2026.pdf) (cited via [CNBC](https://www.cnbc.com/2026/06/05/marvell-technology-flex-sp-500-campbells-pool.html)). AI infra chipmaker; NVDA partnership/investment context. | INDEX / REGULATORY | **Gap-up candidate** — index inclusion flow vs brutal -16.7% session. Chop if macro dominates; watch SMH open. Near multi-week extended base — Stockbee episodic pivot if holds AH gains. |
| **FLEX** | +1.63% | 5.2M session | AI/Compute (EMS/power) | Same S&P 500 inclusion (effective June 22). Contract mfg for AAPL/NVDA. Primary URL above. | INDEX | Below 3% AH filter but paired with MRVL. Modest gap-up watch. |
| **META** | -0.65% AH (session -5.51%) | 29.5M | AI/Compute capex | Equity raise speculation + company denial (CNBC quotes spokesperson). | POLICY-STAKE | **Gap-down / fade risk** if dilution fears persist; gap-up if denial sticks + buyers step in. Dilution overhang = avoid until clarity. |
| **AVGO** | -0.02% AH | 49.8M | AI/Compute semis | June 3 earnings hangover; Friday -7.92% on jobs + sentiment. [Broadcom IR](https://investors.broadcom.com/news-releases/news-release-details/broadcom-inc-announces-second-quarter-fiscal-year-2026-financial) | EARNINGS (lagged) | Gap-down risk if SMH weak; no fresh positive catalyst tonight. |
| **NVDA/AMD/MU** | <-0.4% AH | Heavy | AI/Compute | Macro + sector beta | MACRO | Continuation lower if yields stay elevated; closed near lows. |

**Conviction:** MRVL AH + S&P inclusion is the clearest **actionable** Tier 2 counter-trend vs broad semi wreck. Entry only with gap-hold + volume vs SMH; stop below AH low / prior day low ($261.39). 3–5d hold if episodic pivot forms (Qullamaggie).

### Bitcoin Miners → AI Pivot

| Ticker | Session | AH | Catalyst |
|--------|---------|-----|----------|
| **MARA** | -11.24% | -1.46% | BTC ~$60,915 (-4.53% per Yahoo). Macro risk-off + crypto bleed. No new company PR tonight. MARA pivots to energy/AI infra (company profile). |
| **HUT/IREN/CIFR** | -12% to -8% range | — | Sympathetic miner selloff |

**Setup:** High gap-down risk if BTC breaks $60K overnight. No long bias until BTC stabilizes.

### Nuclear / Quantum / Space / Rare Earth
No qualifying >3% AH movers with primary catalysts. **PL** (space) -25.98% session — catalyst unconfirmed in this scan (investigate manually).

---

## STEP 3 — TIER 3: EMERGING THEME RADAR

- **S&P 500 rebalance cluster (MRVL + FLEX):** Index inclusion as liquidity/event catalyst amid semi selloff — watch if other AI infra names get sympathy bids Monday.
- **"Good news is bad news" jobs trade:** May NFP **172,000** (BLS primary) vs ~115K prior month revision context — rekindles Fed hike odds (CNN: ~43% Dec hike per CME FedWatch). Emerging **rates-over-AI** regime sub-theme if repeats.
- **META equity-financing template:** Following GOOGL $85B raise narrative — hyperscaler balance-sheet funding for AI capex becoming market focus (dilution fear). Not yet a formal Tier 2 theme until primary equity filing.
- Micro-cap AH gainers (GPUS +16%, etc.) <$1B — monitor only.

---

## STEP 4 — TIER 4: MACRO / EXOGENOUS

| Event | Source | Implication | Regime |
|-------|--------|-------------|--------|
| **May jobs +172K**, unemployment **4.3%** unchanged | [BLS primary](https://www.bls.gov/news.release/empsit.nr0.htm) | Strong labor → Fed easing "off the table" near-term; hike odds up | Risk-off for growth |
| **10Y yield ~4.54%** | CNN Jun 5 article | Pressure on long-duration tech | Bearish growth |
| **VIX 21.51 (+39.7%)** | Yahoo ^VIX | Fear regime; snapped 9-week SPX win streak | Risk-off |
| **BTC <$61K (-4.5%)** | Yahoo BTC-USD | Miners/COIN/MSTR pressure | Risk-off crypto |
| **Gold -3.35%** | Yahoo GC=F | Real yields rising hurt non-yield assets | Risk-off |
| **Brent $92.87 (-2.27%)** | Yahoo | Oil down but yields up anyway → jobs focus | Mixed |
| **Nasdaq -4.18%** worst since Apr 2025 | CNN | AI/semi unwind | Risk-off |
| Fed speakers AH | None flagged | — | — |

**Regime read:** **Risk-off / defensive rotation.** Jobs strength + yields + semi valuation unwind dominate. AI secular thesis intact but **near-term NO EDGE on blind longs** in chips until stabilization. Watch Sunday futures and Asia for follow-through.

---

## STEP 5 — TOMORROW'S EARNINGS PREVIEW (June 6, 2026)

Limited BMO/AMC >$1B names surfaced in calendar search this session. **Catalyst unconfirmed — investigate manually** pre-open (Yahoo/TradingView earnings calendar).  
**Watchlist carry-over:** Names reporting next week (AVGO context done; META earnings est. Jul 29).  
**Read-through:** Any pre-announcements in semis could gap SMH; jobs reaction may overshadow single-name prints Monday.

---

## STEP 6 — SYNTHESIS: TOMORROW'S GAP MAP

**Top 5 gap-up candidates (Tier 2/theme first):**
1. **MRVL** (T2 AI/Compute) — +4.57% AH on S&P 500 inclusion June 22; primary S&P DJI/CNBC. Counter-trend vs -16.7% session.
2. **FLEX** (T2 AI/Compute EMS) — +1.63% AH, same index catalyst; smaller magnitude.
3. **Defensive leaders** (COO +8.6%, ABM +6.7%, XLP/IAK) — rotation, not AH gappers; intraday strength only.
4–5. **Limited** other >$1B >3% AH gainers. Catalyst unconfirmed for additional names.

**Top 3 gap-down / fade risk:**
1. **SMH complex / MU / AMD / NVDA** — closed at lows, no AH recovery; jobs + yields headwind. Sector gap-down continuation risk.
2. **META** — equity dilution overhang (unconfirmed raise); session -5.5%, fragile AH. Fade on any deal confirmation.
3. **MARA / miner complex** — BTC sub-$61K; -11% session. Cascade if BTC breaks support.

**Theme of the night:** **AI/Semis valuation unwind + macro repricing** (jobs → rates) with a **single bright spot**: MRVL/FLEX S&P 500 inclusion AH bid. Bearish for broad AI hardware near-term; bullish isolated index-flow names only.

**Regime read:** Risk-off. Defensive rotation (staples, insurance, utilities). Semis closed at lows. VIX spike. Sit tight on tech longs; hedge bias.

**EOD entry candidates (3–5d, Stockbee/Qullamaggie):** **MRVL only** if tomorrow holds AH gains + reclaims prior structure with volume (despite ugly session). Otherwise **no EOD setups** — wait for base formation post-selloff. Use LUK ORB / CORE SOS on chart for confirmation; stops tight.

**Overnight briefing:** Friday delivered the year's worst Nasdaq session (-4.18%) as May payrolls rose 172K (BLS), pushing 10Y yields toward 4.54% and rekindling Fed hike bets. Semiconductors crashed (SMH -9.2%, MU -13%, MRVL -17% intraday) on continued Broadcom earnings hangover and "priced for perfection" AI trade unwind. META fell 5.5% on unconfirmed FT report of a massive equity raise for AI capex; company called it "pure speculation." After the bell, **Marvell (+4.6% AH) and Flex (+1.6% AH) popped on S&P 500 inclusion effective June 22** (S&P DJI announcement). Pure AH screen otherwise showed only micro-caps >3%. Bitcoin ~$61K pressured miners (MARA -11%). Regime: risk-off; tomorrow favors cautious open, MRVL gap-up watch vs broad semi gap-down risk. MSFT 8-K: Reid Hoffman leaving board. No trade recommendations — verify all levels pre-market.

---

## STEP 7 — ASSUMPTION AUDIT

| Assumption | If wrong |
|------------|----------|
| MRVL AH +4.57% holds into open | Gap fades; index news already priced |
| META equity raise stays unconfirmed | Formal S-1/filed offering = further gap-down |
| Jobs report is dominant macro driver | Geopolitical headline could override |
| TV MCP degraded; Yahoo/BLS/CNN/SEC are accurate | Re-verify quotes at open |
| No hidden >$1B AH movers outside stockanalysis | Manual Finviz/Barchart check pre-market |

**Fact Verification (live-sourced this session):**
- Claim: NFP +172K May, unemployment 4.3%. Source: web_fetch BLS empsit.nr0.htm Jun 5 2026. **Verified: Yes**
- Claim: SPX 7,383.74 (-2.64%), Nasdaq 25,709.43 (-4.18%). Source: Yahoo index rows. **Verified: Yes**
- Claim: META $593.00 (-5.51%), AH $589.17 (-0.65%). Source: Yahoo META quote ~7:57 PM EDT. **Verified: Yes**
- Claim: MRVL $263.47 (-16.74%), AH $275.50 (+4.57%). Source: Yahoo MRVL ~7:56 PM EDT. **Verified: Yes**
- Claim: SMH $569.69 (-9.22%), AVGO $385.73 (-7.92%), NVDA $205.10 (-6.20%). Source: Yahoo quotes. **Verified: Yes**
- Claim: BTC ~$60,913 (-4.53%). Source: Yahoo BTC-USD. **Verified: Yes**
- Claim: MRVL/FLEX join S&P 500 June 22. Source: CNBC article linking S&P DJI PDF. **Verified: Yes** (announcement; PDF fetch blocked by S&P security)
- Claim: META spokesperson "pure speculation." Source: CNBC Jun 5 article (company email quoted). **Verified: Yes**
- Claim: MSFT Reid Hoffman 8-K Item 5.02. Source: SEC 8-K fetch. **Verified: Yes**
- **UNVERIFIED:** Exact AH share volume per name; Broadcom IR page fetch failed (prior Jun 3 primary still valid); FT full text (403); precise FedWatch %

---

**Files:** gap-attribution-2026-06-05-g.md + .html  
**Deploy target:** https://nkuy36.github.io/trading-dashboards/gap-attribution-2026-06-05-g.html