# After-Hours Gaps Scan — June 23, 2026 (v7.7)

## TOOL HEALTH
- ✅ TV MCP (batch_run get_ohlcv) — fully live; SPY $734.87, QQQ $715.89
- ✅ stockanalysis.com AH pages — live data returned
- ✅ Finviz news — public feed live (Elite filter unavailable)
- ⚠️ Chrome MCP — unavailable (no tab group). AH gap discovery limited to WebFetch top-20 %-sort. $1B+ names beyond page 1 may be missed.

**SPY/QQQ Sanity Check:** SPY +0.16% AH, QQQ +0.31% AH — both within ±5% bounds. ✅

---

## STEP 1 — TRADEABLE AH GAPPERS (>$1B, >3% gap)

*Note: AH volume unverified for all names (stockanalysis AH pages show no volume; TV MCP extended-session intraday pull not performed). All conviction capped 🟡.*

### AH LOSERS

| Ticker | Company | AH Price | AH % | Mkt Cap | Catalyst | ETF Bucket | Conviction |
|--------|---------|---------|------|---------|---------|------------|-----------|
| **CBRS** | Cerebras Systems | $206.64 | **-8.86%** | $49.79B | EARNINGS — Rev +94% beat ($193.4M vs $56.65M expected) but guidance disappoints on slowing growth | UNCLASSIFIED (AI inference; closest XLK/SMH) | 🟡 |
| **FDX** | FedEx Corp | ~$304* | **~-4.0%*** | ~$82B | EARNINGS — Beat EPS ($6.31 vs $5.96) + Rev ($25.01B vs $24.04B); down on freight spin-off noise | IYT (transports) | 🟡 |
| **SYRE** | Spyre Therapeutics | $89.00 | **-8.30%** | $8.43B | UNCONFIRMED — prior close ~$97-101 after 35% run in <1 month; no primary source for June 23 event | XBI / IBB (biotech) | 🟡 |
| **WOR** | Worthington Enterprises | $53.90 | **-11.68%** | $3.01B | EARNINGS — EPS miss ($0.97 adj vs $1.06 est), Rev miss ($371.5M vs $386.5M est) | XLI (industrials) | 🟡 |

*FDX: AH price estimated at ~-4% (~$304) from earnings news — not confirmed via TV MCP extended session. FDX not in stockanalysis top-20 losers (Chrome MCP down); captured via IYT context + earnings search.

### AH GAINERS

| Ticker | Company | AH Price | AH % | Mkt Cap | Catalyst | ETF Bucket | Conviction |
|--------|---------|---------|------|---------|---------|------------|-----------|
| **ICLR** | ICON Public Limited | $151.00 | **+5.84%** | $10.92B | EARNINGS — Book-to-bill 1.42x, backlog $22.7B (+4%), guidance reaffirmed ($7.85-8.15B rev, $10-11 adj EPS) | XLV (healthcare) | 🟡 |

---

## STEP 2 — ETF AH SWEEP (57-ETF Embedded Universe)

*Method: batch_run(get_ohlcv, 5 bars) on 55 ETFs (+ SPY/QQQ from Step 0). "change_pct" = 5-bar cumulative session move (5 trading days), NOT single-session AH move. True AH moves visible only for ETFs with last_bar timestamp in AH session (noted).*

**AH moves (ETFs with AH-session last_bar):**
None exceed the >1.5% AH threshold. Markets are settling after today's session action.
- SPY: +0.16% AH ($734.87) | QQQ: +0.31% AH ($715.89) | IWM: ~flat ($295.55) | SMH: +0.46% AH ($624.70) | GLD: +0.05% AH ($377.32) | TLT: -0.09% AH ($86.14) | XBI: ~flat | XLF/XLU/XLE: ~flat AH

**5-Day Session Moves — Notable Themes:**

### 🚨 THEME-WIDE BREAKOUTS (DOWNSIDE)

**GDX + GDXJ — GOLD MINERS THEME-WIDE COLLAPSE**
- GDX (large gold miners — NEM, AEM): **-9.85%** (5-day)
- GDXJ (junior gold miners): **-11.32%** (5-day)
- Both collapsing together = gold miners theme-wide (not single-name). Juniors leading down (real metals pain).
- Catalyst: Hawkish Fed (9 of 19 FOMC members now project ≥1 rate hike this year; Sept hike priced in), copper/silver supply easing. Gold itself relatively flat (GLD +0.05%) — miners underperforming spot.

**URA + NLR — NUCLEAR THEME-WIDE SELLOFF**
- URA (uranium/nuclear fuel — CCJ, OKLO, SMR): **-5.51%** (5-day)
- NLR (nuclear utilities/reactors): **-2.45%** (5-day)
- Both down = nuclear theme-wide, not single-SMR squeeze.

**COPX + XME + SLV — METALS COMPLEX BROAD CRASH**
- COPX (copper miners): **-11.07%** (5-day)
- XME (metals & mining — steel, coal): **-8.42%** (5-day)
- SLV (silver): **-12.51%** (5-day)
- LIT (lithium/battery): **-6.63%** (5-day)
- REMX (rare earth): **-5.39%** (5-day)
Attribution: Fed hawkishness + easing copper supply (global shipments rising since April) + demand concerns = multi-metal industrial selloff.

### Other Notable 5-Day Session Movers

| ETF | Theme | 5-Day % | Notes |
|-----|-------|---------|-------|
| ARKX | Space (RKLB, ASTS, PL) | -6.98% | |
| TAN | Solar | -5.69% | |
| IBIT | Spot Bitcoin | -5.49% | Diverges from WGMI |
| KWEB | China internet (BABA, PDD) | -5.88% | |
| SHLD | Defense tech (PLTR-heavy) | -4.99% | NOT defense theme-wide — ITA only -0.48% → PLTR-specific |
| USO | Crude oil | -4.37% | OPEC + demand pressure |
| BOTZ | Robotics/physical AI | -4.06% | AI spending concerns |
| ARKK | Speculative growth | -3.55% | Risk-off gauge |
| DRAM | HBM memory (MU, SK hynix) | -3.49% | Pre-MU earnings positioning? |
| IYT | Transports (FDX, UPS, rails) | -3.25% | FDX earnings headwind |
| QTUM | Quantum (IONQ, RGTI) | -2.12% | |
| MOO | Agriculture | -2.10% | |
| XRT | Retail equal-weight | -1.90% | |
| **WGMI** | Bitcoin miners | **+3.48%** | Diverges FROM IBIT — hash rate / HPC pivot thesis |
| **JETS** | Airlines | **+1.50%** | Summer travel demand; diverges from broader selloff |
| **AIPO** | AI power infra (VRT, VST, GEV) | **+1.41%** | Datacenter power demand intact |

---

## STEP 3 — FINVIZ AH NEWS DIGEST

*Public feed used; Finviz Elite filter unavailable.*

| Time (ET) | Headline | Source | Ticker/Theme | ETF Bucket |
|-----------|----------|--------|-------------|------------|
| 4:59 PM | 'Magnificent Seven' correction may be a sign of a healthy market | MarketWatch | Mag7 broad | XLK, XLC, QQQ |
| 4:48 PM | Wall Street ends lower on semiconductor selloff as AI spending concerns mount | Reuters | Semis / AI | SMH, XLK |
| 4:41 PM | Options Market Challenges Futures Aggressive Fed Hike Bets | Bloomberg | Macro/rates | TLT, HYG | UNCLASSIFIED |
| 4:15 PM | Supreme Court dismisses Falun Gong lawsuit vs. Cisco | Fox Business | CSCO | XLK |
| 4:14 PM | Tech Stocks Retreat on Concerns over AI Spending, Valuations | WSJ | Tech broad | XLK, QQQ |
| 4:55 PM | CFTC sues Kentucky over prediction markets | CNBC | Regulatory | UNCLASSIFIED |

**UNCLASSIFIED headlines:** Options market / Fed hike timing (macro); CFTC/Kentucky prediction markets (no direct ETF fit).

---

## STEP 4 — WATCHLIST AH ACTIVITY

*Method: batch_run(get_ohlcv, 5 bars). All timestamps 1782221400 = regular session close (not AH), except SPY/QQQ which are AH. AH volume unverified.*

| Ticker | Close | 5-Day % | Today's Intraday Move | Notes |
|--------|-------|---------|----------------------|-------|
| TSLA | $381.61 | -5.57% | $392.61 open → $381.61 close (~-2.8%) | Continued tech/EV selling |
| NVDA | $200.04 | -5.28% | $202.17 → $200.04 (~-1.1%) | **Held $200 psychological key level** |
| SOFI | $17.29 | +0.52% | $16.72 → $17.29 (recovered) | Outperforming on rate narrative |
| AMD | $519.85 | -4.94% | $509.08 → $519.85 (recovered intraday) | Closed off lows |
| PLTR | $116.70 | -13.29% | $120.15 → $116.70 (~-2.9%) | France intel drop + UK NHS contract risk |
| MARA | $14.70 | +1.03% | $14.03 → $15.48 → close $14.70 (volatile) | Bitcoin miner, tracked WGMI divergence |
| COIN | $158.18 | -6.57% | $156.98 → $158.18 (recovered) | Crypto pressure easing intraday |
| SNDK | $1,963.60 | -7.99% | $2,007.70 → $1,963.60 (~-2.2%) | Flash storage, memory selloff |
| META | $562.20 | -5.30% | Essentially flat today ($562.25 → $562.20) | 5-day sell exhausted |
| AMZN | $234.11 | -5.60% | $232.55 → $234.11 (recovered) | Closed off lows |
| SPY | $734.87 | +0.16% AH | AH session | Stable post-session |
| QQQ | $715.89 | +0.31% AH | AH session | Slight recovery |

---

## STEP 5 — AMC EARNINGS RESULTS

### 1. CBRS — Cerebras Systems (AI inference chips)
- **Q1 2026 results released AMC June 23**
- Revenue: $193.4M (+94% YoY) vs $56.65M expected — **MASSIVE BEAT**
- Key partnerships: $20B OpenAI inference compute deal; AWS multi-year partnership
- **AH reaction: -8.86% (~$207)** — guidance signals slowing growth despite massive beat
- Session close: $226.72 (via TV MCP, 10:07 PM ET pull)
- Sector read-through: UNCLASSIFIED (AI inference hardware; watch NVDA/AMD for sympathy)

### 2. WOR — Worthington Enterprises (building products/industrial)
- **Q4 FY2026 (calendar Q2 2026) released AMC June 23**
- Revenue: $371.5M vs $386.5M expected — **MISS**
- Adj EPS: $0.97 vs $1.06 expected — **MISS**
- Net earnings increased YoY ($48.1M vs $3.6M) but adjusted EPS fell from $1.06 prior year
- Dividend raised to $0.20/share (+5%)
- **AH reaction: -11.68% ($53.90)**
- Sector read-through: XLI (industrials negative; building products demand concerns)

### 3. ICLR — ICON Public Limited (CRO / clinical research)
- **Q1 2026 results released AMC June 23** (conf call June 24 8am ET)
- Revenue: $2,034M (+0.9% YoY)
- Adj EPS: $2.50
- Net book-to-bill: **1.42x** (strong pipeline build)
- Backlog: **$22.7B (+4% QoQ)**
- 2026 guidance reaffirmed: $7.85-8.15B revenue, $10-11 adj EPS
- **AH reaction: +5.84% ($151.00)**
- Sector read-through: XLV positive (CRO demand stable despite pharma spending concerns)

### 4. FDX — FedEx Corp (transport/logistics)
- **Q4 FY2026 results released AMC June 23** (last quarter including freight before spin-off)
- Adj EPS: **$6.31 vs $5.95-5.96 expected — BEAT**
- Revenue: **$25.01B vs $24.03-24.04B expected — BEAT**
- FY guidance: 11% YoY revenue growth; adj EPS $16.90-18.10
- Note: Last quarter including FedEx Freight (spun off June 1, 2026)
- **AH reaction: ~-4% (~$304)** — beat overshadowed by freight spin-off complexity + forward uncertainty
- Session close: $317.24 (TV MCP)
- Sector read-through: IYT negative despite operational beat

### 5. CCL — Carnival Corporation (cruise)
- Reported Q2 FY2026 **BMO June 23** (not AMC) — consensus $0.34 EPS, $6.69B rev
- Not an AH gapper; results baked into session. PEJ -0.29% (5-day) relatively contained.

---

## STEP 6 — CATALYST ATTRIBUTION

| Ticker | Catalyst Type | Direction | Primary Source | Tomorrow Setup | Parent ETF |
|--------|--------------|-----------|---------------|---------------|------------|
| CBRS | EARNINGS (Q1 2026) | ↓ -8.86% AH | Alphastreet, TheStreet | Guidance-driven fade likely continues; watch whether $200 level holds | UNCLASSIFIED |
| WOR | EARNINGS (Q4 FY2026) | ↓ -11.68% AH | SEC 8-K; FinancialContent | Gap-and-fade likely; no near-term catalyst to reverse | XLI |
| FDX | EARNINGS (Q4 FY2026) | ↓ ~-4% AH | CNBC, Alphastreet | Watch whether beat narrative recovers at open vs. freight spin-off noise | IYT |
| ICLR | EARNINGS (Q1 2026) | ↑ +5.84% AH | SEC 6-K | Gap-and-go possible given backlog strength; conf call 8am ET June 24 | XLV |
| SYRE | UNCONFIRMED | ↓ -8.30% AH | No primary source found | Treat as uncertain; likely profit-taking after 35% run; watch for SKYWAY trial catalyst | XBI/IBB |
| PLTR | POLICY-CONTRACT | ↓ -13.29% (5d) | Yahoo Finance, Benzinga | Political headwinds persist; France/UK contracts at risk; avoid momentum longs | SHLD (PLTR-specific) |
| GDX+GDXJ | MACRO (Hawkish Fed) | ↓ -9.85%/-11.32% (5d) | CanadianMiningReport, FinanceMagnates | Continued downside risk if Sept hike bets hold | GDX+GDXJ theme-wide |
| COPX+XME+SLV | MACRO (Fed + supply) | ↓ -11%/-8.4%/-12.5% (5d) | TradingEconomics | Copper below $6.3/lb; supply concerns easing | COPX/XME/SLV |

---

## STEP 7 — TOMORROW'S EARNINGS PREVIEW (June 24, 2026)

### 🔥 MICRON TECHNOLOGY (MU) — AMC June 24 — TOP PRIORITY
- **Q3 FY2026 results after close June 24**
- Consensus: **$19.72 EPS** on **$34.52B revenue** (Alphastreet); alternate: $19.95 EPS / $34.66B
- Company guidance (prior quarter): ~$33.5B revenue ± $750M, non-GAAP EPS ~$19.15, gross margin ~81%
- HBM capacity **fully booked** through early 2027 — no demand risk
- EPS estimate up 68.1% over 90 days (massive bullish revision momentum)
- Historical gap: typically ±8-12% on MU earnings
- If beat + guides up: 🟢 SMH, DRAM, NVDA, AMD — potential broad semi recovery
- If miss/light guide: 🔴 accelerates current tech selloff; DRAM ETF already -3.49% (5d)
- Watch: gross margin trajectory (~81% expected) and HBM mix shift

### ICLR (ICON Public Limited) — Conf call 8am ET June 24
- Results already out (AMC June 23) — AH +5.84%
- Call at 8am may drive pre-market continuation if tone is positive

---

## STEP 8 — PERSONAL POSITIONS PLAN

*(Note: No specific position data in memory — general plan based on today's analysis)*

**Overnight risks:**
- CBRS long: -8.86% gap — guidance-driven; may continue lower at open unless AH recovers
- WOR long: -11.68% gap — earnings miss; likely fades further; no near-term catalyst
- FDX long: -4% AH despite beat — freight narrative headwind; could recover if beat is re-rated at open
- ICLR: +5.84% AH — positive setup for tomorrow's conf call; gap-and-go candidate

**Theme bias for tomorrow (June 24):**
- **RISK-OFF / MIXED** — broad tech weakness persists (AI spending concerns); metals still under Fed pressure
- **MU earnings = the pivot event** for the entire semiconductor space
  - Beat + raise → likely broad semi bounce (NVDA, AMD, SMH, DRAM)
  - Miss/light → extends selling in tech, SMH tests further lows
- **PLTR**: avoid longs until France/UK contract situation resolves
- **JETS/Airlines** diverging positively — summer travel trade intact
- **WGMI (bitcoin miners)** showing strength vs. IBIT weakness — HPC/AI pivot thesis
- **AIPO** holding up (+1.41%) — datacenter power demand theme intact despite AI spending fears

**Watchlist entry setups still valid:**
- NVDA: Held $200. If MU beats, NVDA $200 is a key support/long setup with tight stop
- SOFI: Outperformer this week (+0.52% while market -5%) — rate sensitivity trade
- ICLR: Conf call at 8am ET — AH gap may extend on strong backlog narrative

---

## STEP 9 — ASSUMPTION AUDIT

1. **TV MCP price method:** batch_run(get_ohlcv, 5 bars) used for all ETF sweep (54 ETFs) and watchlist (10 names). CBRS and FDX pulled individually via chart_set_symbol + data_get_ohlcv. batch_run is the primary and confirmed working engine.

2. **change_pct interpretation:** All "5-day %" values from batch_run represent 5-bar cumulative move (first bar open → last bar close), NOT single-session AH moves. Clearly labeled throughout.

3. **ETF AH moves:** Only ETFs with last_bar timestamp 1782248400 (AH session) show true AH prices. None exceeded >1.5% AH threshold. Remaining ETFs capped at regular session close (1782248400 = most recent session for those).

4. **AH volume:** UNVERIFIED for all gappers. stockanalysis AH pages show no volume column. TV MCP extended-session intraday pull not performed. All gappers flagged 🟡 conviction.

5. **Chrome MCP:** Unavailable (no tab group). AH gap discovery limited to top-20 %-sort from WebFetch. FDX ($82B, -4% AH) was NOT in top-20 losers list — captured only via earnings news + IYT bucket context. Any other large-cap AH movers beyond page 1 may have been missed.

6. **FDX AH price:** Estimated ~$304 (-4%) from earnings news headlines. NOT confirmed via TV MCP extended session. TV MCP session close $317.24 confirmed. AH volume unverified.

7. **Finviz:** Elite filter unavailable — public feed only. AH-specific filtering not possible.

8. **SYRE:** No primary source found for June 23 specific catalyst. Catalyst marked UNCONFIRMED. Prior close ~$97-101 (after 35% run in <1 month), now ~$89 AH. Profit-taking most likely.

9. **UNCLASSIFIED headlines:** Options market / Fed hike timing (Bloomberg 4:41 PM); CFTC/Kentucky prediction markets (CNBC 4:55 PM).

10. **SPY sanity check:** ✅ SPY +0.16% AH ($734.87), QQQ +0.31% AH ($715.89) — within ±5% bounds.

11. **CCL:** Reported BMO June 23 (not AMC). Not an AH gapper.

---

*Report generated: June 23, 2026 | v7.7 | Sources: TV MCP (batch_run get_ohlcv), stockanalysis.com (WebFetch), Finviz (WebFetch public), WebSearch (earnings/catalyst attribution)*
