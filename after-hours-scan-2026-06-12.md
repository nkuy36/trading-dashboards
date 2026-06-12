# After-Hours Scan — June 12, 2026 (v7.7)

## TOOL HEALTH
- TEST 1 TV MCP (batch_run): ✅ All 57 ETFs + 12 watchlist tickers pulled successfully
- TEST 2 stockanalysis AH gainers/losers: ✅ Tables populated
- TEST 3 Finviz public news: ✅ Headlines returned
- TEST 4 Chrome MCP: ⚠️ Not available — AH gap discovery limited to WebFetch top-20 %-sort; $1B+ names beyond page 1 may be missed

---

## STEP 1 — TRADEABLE AH GAPPERS (>$1B Market Cap)

**⚠️ Chrome MCP unavailable — discovery limited to top-20 %-sort. AVGO (major cap, AH down ~14%) NOT caught by top-20 losers list — surfaced via AMC earnings search.**

### GAINERS >$1B

| Ticker | Company | AH % | AH Price | Mkt Cap | Session Close | Session % | Volume |
|--------|---------|------|----------|---------|---------------|-----------|--------|
| FAC | Factorial Energy | +7.57% | $16.49 (stockanalysis, ~scan time) | $1.40B | $15.33 (TV MCP, batch_run) | **-38.58%** | AH volume unverified 🟡 |

- **Tradeable? 🟡 LOW CONVICTION** — AH bounce from a massive -38.58% session crash. Post-SPAC IPO unwind (IPO June 8, peaked $25.33 Jun 9). Stellantis solid-state battery milestone announced but "buy the rumor, sell the news" played out. Fade risk is HIGH.

### LOSERS >$1B

| Ticker | Company | AH % | AH Price | Mkt Cap | Notes |
|--------|---------|------|----------|---------|-------|
| PLBL | Polibeli Group Ltd | -6.45% | $7.25 (stockanalysis) | $2.84B | Indonesian goods trading co.; recent CFO change; no major catalyst found — likely AH illiquidity noise. NOT tradeable. |

### KEY AH STORY NOT IN TOP-20 LOSERS (surfaced via AMC earnings)
- **AVGO (Broadcom, ~$500B+ market cap)**: Reported Q2 FY26 AMC. Revenue $22.187B beat est. $22.04B; EPS beat consensus but missed whisper. AI semiconductor guidance reaffirmed >$100B for FY26 but NOT raised — disappointment. Web sources: AH ~-14%. TV MCP close: $382.07 (batch_run). AH price via TV MCP: unavailable (chart switched to SPCX post-IPO pull; quote_get returned SPCX data). **Overnight risk: SMH opens lower Monday.**

---

## STEP 2 — ETF AH SWEEP (57 ETFs — Today's Session Moves, Extended via TV MCP batch_run)

*Note: batch_run returns the daily session bar. AH-specific ETF moves are minimal for most ETFs; session data is the primary signal. All values from TV MCP batch_run, pulled ~scan time.*

### 🚨 THEME-WIDE BREAKOUTS (multiple ETFs in same category moving together)

1. **🚨 TRAVEL THEME-WIDE BREAKOUT**: JETS +8.49% + PEJ +2.35% → Iran ceasefire = oil down + travel reopening
2. **🚨 GOLD MINERS THEME-WIDE BREAKOUT**: GDX +8.16% + GDXJ +9.27% (juniors leading = REAL metals run, not just a hedge bid)
3. **🚨 NUCLEAR THEME-WIDE BREAKOUT**: URA +6.38% + NLR +4.00% → Iran peace deal unlocks energy/nuclear policy
4. **🚨 BIOTECH THEME-WIDE BREAKOUT**: XBI +3.60% + IBB +2.36% → Sector-wide move, not a single squeeze

### Index / Regime
| ETF | Theme | Session % | Close | Notes |
|-----|-------|-----------|-------|-------|
| SPY | S&P 500 | +1.78% | $741.75 | ✅ Sanity check passed (<5% from prior) |
| QQQ | Nasdaq 100 | +3.15% | $721.34 | ✅ Sanity check passed; tech led by AMD, SNDK |
| IWM | Small Caps | +2.99% | $292.95 | Broad risk-on, small caps participating |
| HYG | High-Yield Credit | +0.46% | $79.94 | Credit markets calm — no stress |
| TLT | 20Y Bonds | +0.70% | $85.77 | Bonds slightly bid (mild risk-off undertone) |
| UUP | US Dollar | -0.46% | $27.95 | Dollar weaker → metals tailwind |
| GLD | Gold | **+3.36%** | $386.54 | Gold surging WITH equities — unusual; dollar weak + Iran uncertainty |

### Sector SPDRs
| ETF | Sector | Session % | Close |
|-----|--------|-----------|-------|
| XLK | Tech | **+3.94%** | $184.80 |
| XLF | Financials | +1.90% | $53.34 |
| **XLE** | **Energy** | **-2.08%** | **$57.55** | **Iran ceasefire = oil supply coming back** |
| XLI | Industrials | +2.86% | $176.18 |
| XLY | Consumer Disc. | +2.17% | $116.60 |
| XLP | Staples | +0.17% | $85.82 |
| XLU | Utilities | +0.70% | $44.53 |
| **XLB** | **Materials** | **+4.21%** | **$52.18** | **Iran peace = supply chain normalization** |
| XLC | Communications | +0.69% | $111.65 |
| XLV | Healthcare | +0.23% | $153.81 |
| XLRE | REITs | +0.67% | $45.36 |

### Industry Groups
| ETF | Theme | Session % | Close | Notes |
|-----|-------|-----------|-------|-------|
| **SMH** | **Semiconductors** | **+6.41%** | **$619.96** | AMD +10.83%, SNDK +18.41%, DRAM +9.06% — AI chip day |
| IGV | Software | +0.78% | $90.70 | Relatively flat — PLTR -0.61% drag |
| CIBR | Cybersecurity | +2.58% | $85.33 |  |
| **XBI** | **Biotech Small-Cap** | **+3.60%** | **$133.79** | 🚨 THEME-WIDE (pairs with IBB) |
| **IBB** | **Biotech Large-Cap** | **+2.36%** | **$170.66** | 🚨 THEME-WIDE (pairs with XBI) |
| KRE | Regional Banks | +1.92% | $73.41 |  |
| **XOP** | **Oil & Gas E&P** | **-2.26%** | **$165.34** | **Iran ceasefire = supply expansion** |
| XHB | Homebuilders | +2.99% | $107.59 | Rates flat + risk-on |
| XRT | Retail Equal-Weight | +2.68% | $87.73 |  |
| IYT | Transports | +3.70% | $86.51 | Oil down = transport beneficiary |
| **JETS** | **Airlines** | **+8.49%** | **$29.53** | 🚨 TRAVEL THEME-WIDE — Iran ceasefire |
| PEJ | Travel/Leisure | +2.35% | $65.20 | 🚨 TRAVEL THEME-WIDE — pairs with JETS |

### AI / Tech Themes
| ETF | Theme | Session % | Close | Notes |
|-----|-------|-----------|-------|-------|
| **DRAM** | **HBM Memory** | **+9.06%** | **$65.01** | AI memory shortage theme; SK Hynix/Micron/Samsung |
| QTUM | Quantum | +5.54% | $161.30 | IONQ, RGTI, QBTS running |
| BOTZ | Robotics/Physical AI | +1.73% | $37.12 |  |
| ARKK | Speculative Growth | +3.07% | $75.65 | Risk appetite strong |
| ARKX | Space | +2.27% | $33.78 | SpaceX IPO day but SPCX NOT yet in holdings |
| **AIPO** | **AI & Power Infra** | **+5.29%** | **$31.45** | VRT, VST, GEV — datacenter power buildout |
| DTCR | Data Center REITs | +3.21% | $31.16 | EQIX, DLR |
| SHLD | Defense Tech | +1.49% | $63.82 | Below 1.5% threshold — PLTR drag |
| ITA | Defense Primes | +3.16% | $233.79 | Iran peace deal ≠ less defense spending |
| **WGMI** | **Bitcoin Miners** | **+11.27%** | **$65.97** | Crypto + AI HPC pivot; MARA +11.64% |
| IBIT | Spot Bitcoin | +1.41% | $36.04 | BTC broadly bid |

### Power / Materials
| ETF | Theme | Session % | Close | Notes |
|-----|-------|-----------|-------|-------|
| **URA** | **Uranium/Nuclear** | **+6.38%** | **$45.52** | 🚨 NUCLEAR THEME-WIDE (pairs with NLR) |
| **NLR** | **Nuclear Reactors** | **+4.00%** | **$121.95** | 🚨 NUCLEAR THEME-WIDE (pairs with URA) |
| GRID | Grid Equipment | +2.82% | $189.01 |  |
| TAN | Solar | +5.47% | $63.03 | Iran peace = energy policy pivot |
| **COPX** | **Copper Miners** | **+8.78%** | **$85.97** | Supply chain normalization + China demand |
| **REMX** | **Rare Earth** | **+7.86%** | **$95.50** | MP, USAR; export controls theme |
| **XME** | **Metals & Mining** | **+5.99%** | **$120.44** |  |
| LIT | Lithium/Battery | +5.60% | $82.37 |  |
| **GDX** | **Gold Miners Large** | **+8.16%** | **$80.03** | 🚨 GOLD MINERS THEME-WIDE |
| **GDXJ** | **Junior Gold Miners** | **+9.27%** | **$104.26** | 🚨 LEADING = REAL METALS RUN |
| **SLV** | **Silver** | **+6.68%** | **$61.29** |  |

### Commodities / Global
| ETF | Theme | Session % | Close | Notes |
|-----|-------|-----------|-------|-------|
| **USO** | **Crude Oil** | **-6.58%** | **$125.43** | Iran ceasefire = massive supply relief |
| UNG | Natural Gas | +0.09% | $11.35 | Flat |
| MOO | Agriculture | +0.99% | $78.59 |  |
| KWEB | China Internet ADRs | +1.46% | $26.49 | Mild China bid |

---

## STEP 3 — FINVIZ AH NEWS DIGEST (Public Feed — post 4 PM ET)

*Note: Finviz Elite filter unavailable — public feed used. All headlines from 4:00–5:00 PM ET, June 12, 2026.*

**DOMINANT STORY: SPACEX IPO (SPCX)**
- 4:55 PM — MarketWatch: "SpaceX's stock closes 19% above IPO price — making it the 6th-most valuable company on earth"
- 4:48 PM — NYT: "SpaceX's Unlikely Journey From Far-Out Idea to $2 Trillion Juggernaut"
- 4:46 PM — BBC: "Elon Musk becomes world's first trillionaire as SpaceX soars in stock market debut"
- 4:40 PM — WSJ: "SpaceX Shares Close Up 19% in Historic Debut as Musk Becomes First Trillionaire"
- 4:33 PM — MarketWatch: "SpaceX's stock closes 19% above IPO price — and keeps climbing after hours"
- 4:18 PM — Yahoo Finance: "SpaceX closes up nearly 20% after historic IPO"

**IRAN PEACE DEAL (MACRO CATALYST)**
- 4:14 PM — WSJ: "Stocks Climb on SpaceX's Debut" *(also Iran)*
- 4:07 PM — Reuters: "Wall Street ends up on Iran war peace deal hopes, SpaceX's historic debut"
- 4:05 PM — MarketWatch: "U.S. stocks end higher amid optimism for Iran peace deal and SpaceX's record IPO"

**ETF Attribution:**
- SPCX → UNCLASSIFIED (new IPO, not yet in ARKX holdings; ARKX is closest proxy — up +2.27%)
- Iran peace deal → USO ❌ (crude down -6.58%), JETS/PEJ ✅ (airlines up), XLB ✅ (materials up), GLD ✅ (gold holding bid = uncertainty premium), XLE ❌ (energy down)

---

## STEP 4 — WATCHLIST AH ACTIVITY (TV MCP batch_run, pulled ~scan time)

| Ticker | Session Close | Session % | AH % | AH Price | Notes |
|--------|---------------|-----------|------|----------|-------|
| **SPCX** | $160.95 | **+19.2% (IPO)** | +1.81% AH | ~$163.86 (web) | Historic IPO; $135 IPO → $160.95 close; Musk = world's first trillionaire |
| **AMD** | $511.57 | **+10.83%** | AH volume unverified | — | BofA raised PT to $600-665; Oracle $70B datacenter signal; Computex announcements |
| **SNDK** | $1,980.10 | **+18.41%** | AH volume unverified | — | AI NAND flash structural shortage; 692% YTD; no single Jun 12 catalyst — structural momentum |
| **MARA** | $14.08 | **+11.64%** | AH volume unverified | — | WGMI day; bitcoin miners ripping; AI HPC pivot |
| **TSLA** | $406.43 | +4.67% | AH unverified | — | Musk halo effect (SpaceX IPO day) |
| **SOFI** | $16.58 | +4.80% | AH unverified | — | Risk-on + financials day |
| **COIN** | $159.78 | +3.28% | AH unverified | — | Crypto bid |
| **NVDA** | $205.19 | +1.84% | AH unverified | — | Modest; AMD stole chip headlines today |
| **AMZN** | $238.55 | +0.26% | AH unverified | — | Underperformed despite QQQ +3.15% |
| **META** | $566.98 | +0.20% | AH unverified | — | Underperformed — rotation out of mega-cap into mid-cap growth |
| **PLTR** | $127.99 | -0.61% | AH unverified | — | Slight underperform; SHLD drag |
| SPY | $741.75 | +1.78% | — | — | ✅ Sanity check passed |
| QQQ | $721.34 | +3.15% | — | — | ✅ Sanity check passed |

---

## STEP 5 — AMC EARNINGS RESULTS

### AVGO — Broadcom (Q2 FY26)
- **Result**: Revenue $22.187B vs est. $22.04B (BEAT). EPS beat consensus, missed "whisper" number.
- **Guidance**: AI semiconductor revenue reaffirmed >$100B for FY26 — NOT raised. That's the disappointment.
- **AH reaction**: ~-14% per web sources (multiple reports). TV MCP AH price unavailable (chart stuck post-SPCX; see audit).
- **Sector read-through**: 🔴 NEGATIVE for SMH Monday open. AVGO is a top-3 SMH holding. SMH was +6.41% today — expect partial giveback. AMD's strength (+10.83%) should partially offset.
- **Conference call key point**: CEO Hock Tan reaffirmed long-term AI chip supercycle but declined to raise 2026 guidance — market had priced in a raise.

*No other major AMC earners confirmed for June 12. (AMC Entertainment's next earnings is August 2026.)*

---

## STEP 6 — CATALYST ATTRIBUTION

### FAC — Factorial Energy
- **Type**: IPO/SPAC UNWIND + NEWS (non-earnings)
- **Catalyst**: Post-SPAC lock-up selling pressure; peaked Jun 9 at $25.33 just 1 day after IPO. Stellantis solid-state battery milestone announced but stock fell despite the news (sell-the-news pattern).
- **Primary source**: [Benzinga — Why FAC Fell After Stellantis Milestone](https://www.benzinga.com/trading-ideas/movers/26/06/53148191/why-factorial-energy-stock-is-falling-after-stellantis-battery-milestone)
- **Direction**: AH bounce from -38.58% regular session crash
- **Tomorrow's setup**: HIGH FADE RISK — dead-cat bounce. SPAC lock-up dynamics; float is limited; no institutional accumulation signal. Gap-down risk if AH buyers are exhausted overnight.
- **ETF**: LIT (tangential — solid-state battery / EV battery theme)
- **AH volume**: Unverified — conviction capped 🟡

### AVGO — Broadcom
- **Type**: EARNINGS AMC
- **Direction**: DOWN AH (~-14%)
- **ETF bucket**: SMH (major holding), XLK (minor)
- **Tomorrow's setup**: FADE gap at open for SMH. AVGO fundamentals still strong (AI chip growth +143% YoY) but guide didn't raise — sell the news. Watch whether dip buyers emerge at prior support.

### SPCX — SpaceX (UNCLASSIFIED — New IPO)
- **Type**: IPO (LARGEST IN HISTORY — $75B raised)
- **Direction**: UP (closed +19% from $135 IPO price; AH +1.81% continuing)
- **ETF**: UNCLASSIFIED — not yet in any ETF; ARKX closest proxy (+2.27% today)
- **Tomorrow's setup**: Watch $160.95 close as key support. IPO momentum runs often continue D+2/D+3. Musk/SpaceX narrative very strong. Risk: massive floating supply (514M shares traded Day 1).
- **Catalyst confirmed**: [CNBC SpaceX IPO Live Updates](https://www.cnbc.com/2026/06/12/spacex-ipo-spcx-live-updates.html)

---

## STEP 7 — TOMORROW'S EARNINGS PREVIEW (June 15, 2026)

*Note: stockanalysis.com/markets/earnings/ returned HTTP 404. earningswhispers.com requires login. Web search found limited data.*

**Known June 15 reporters (web search):**
- **FCEL** (FuelCell Energy) — small cap; energy/hydrogen theme; not in major tracked themes
- **VFS** (VinFast) — EV maker; XLY tangential; typically volatile
- **CPB** (Campbell's) — XLP (consumer staples); defensive name

**No major watchlist names (TSLA, NVDA, AMD, MARA, COIN, META, AMZN, PLTR) reporting June 15.**

**NOTE**: Earnings calendar unavailable — verify manually via Benzinga/EarningsWhispers for any pre-market releases that could affect Monday open.

---

## STEP 8 — PERSONAL POSITIONS PLAN

**Overnight risks:**
1. **SMH/AVGO**: If long SMH or semiconductor names, AVGO's -14% AH is a headwind for Monday open. AMD's +10.83% session should partially offset, but expect choppy open.
2. **USO/Oil short**: Iran ceasefire validates oil short thesis (USO -6.58% today). Overnight risk = ceasefire falls apart (common in Middle East negotiations). Keep stops above $131 (pre-news level). Brent reportedly fell from $115 → $103.
3. **WGMI/MARA/crypto**: +11.27%/+11.64% on the day. Weekend crypto volatility can flush extended names. Size down heading into weekend, or hold with stops.
4. **SNDK**: +18.41% on enormous dollar move ($307/share). AI NAND thesis is structural and real. Momentum is extreme — normal to see -5 to -10% giveback on Day+1 before continuation. Wait for intraday flush before adding.
5. **JETS**: +8.49% on Iran ceasefire. Take partial profits (deal is tentative, not signed). Watch Monday for confirmation vs. fade.
6. **SPCX**: Clean IPO setup. $150 open as support tier; $160.95 close as key level. Continuation likely if AH holds above close.
7. **GLD/GDXJ**: Gold ran +3.36%, juniors +9.27%. Unusual to see gold + equities both up big → likely dollar weakness + end-of-geopolitical-cycle flows. GLD could consolidate Monday; GDXJ more volatile.

**Theme bias for Monday (June 15): RISK-ON with sector rotation caveat**
- Macro tailwinds: Iran peace (oil down, travel up, dollar weak, risk appetite high)
- Headwinds: AVGO -14% AH presses semis; metals/gold extremely extended; SpaceX euphoria may fade
- Longs: JETS (dip buyer), copper/materials on any pullback, DRAM on AVGO-induced SMH flush
- Watches: SPCX continuation, AMD next leg
- Trims: SNDK (extended), WGMI/MARA (weekend crypto risk), GDXJ (extended after 9% day)

---

## STEP 9 — ASSUMPTION AUDIT

| Item | Method Used | Issues / Flags |
|------|-------------|----------------|
| TV MCP price pulls | batch_run(get_ohlcv) for all 57 ETFs and watchlist — RELIABLE | ✅ All 57 ETFs successful |
| quote_get method | Used for AVGO (post chart_set_symbol) and SPCX | ⚠️ quote_get returned SPCX data when called for AVGO after chart was set to SPCX — bug documented Jun 12; AVGO AH price written as "unavailable — not pulled" per protocol |
| SPY sanity check | SPY +1.78%, QQQ +3.15% | ✅ Both within 5% bounds; large QQQ move explainable by SPCX IPO + Iran deal |
| AH volume | stockanalysis has no volume column; TV MCP intraday pull not attempted (chart stuck on SPCX) | FAC: "AH volume unverified" — conviction capped 🟡 |
| Chrome MCP | Not available | ⚠️ Top-20 %-sort only; AVGO missed in losers list — caught via AMC earnings search |
| Finviz Elite | Not available | "Public feed used" — noted |
| VIX | Not batch_run'd | Not a tradeable ETF; use HYG (+0.46%), TLT (+0.70%), UUP (-0.46%) as proxy — all point to controlled risk-on regime |
| ETF data vs AH | batch_run returns daily session bar, not AH bars | Noted; AH ETF moves are typically <0.3% and not the primary signal |
| AVGO AH price | TV MCP unavailable; web sources cited ~-14% | Numbers from web flagged as secondary source; TV MCP primary source was not obtainable |
| Tomorrow's earnings | stockanalysis 404; EarningsWhispers login-gated | FCEL, VFS, CPB from web search — verify manually |
| UNCLASSIFIED headlines | SPCX IPO (no ETF bucket — new ticker) | Noted; ARKX closest proxy |
| Data pull time | All TV MCP batch_run data at timestamp 1781271000 (Jun 12, 2026 market close) | Pulled ~post-4 PM ET |

---

*Generated by after-hours-catalyst-scanner v7.7 | June 12, 2026*
