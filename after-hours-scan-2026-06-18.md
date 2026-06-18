# After-Hours Gaps Scan (v7.7) — June 18, 2026

**TOOL HEALTH:** ✅ TV MCP (batch_run) | ✅ stockanalysis AH pages | ✅ Finviz public news | ⚠️ Chrome MCP (not available in automated run — AH gap discovery limited to WebFetch top-20 %-sort; $1B+ names beyond page 1 may be missed)

---

## HEADLINE MACRO CONTEXT

- **Iran Peace Deal** (formalized June 16): Driving today's session — defense rotation (SHLD -2.7%), travel/leisure up (JETS +1.37%), homebuilders up (XHB +1.77%).
- **Intel-Apple Chip Partnership** announced 4:30 PM ET (after close): INTC AH **-7.01%** at $129.59 — sell-the-news on foundry economics concerns.
- **USO (crude oil) +2.19%** session: counterintuitive vs. Iran deal (which removes Hormuz risk premium); likely demand-optimism/OPEC dynamics.
- **Markets CLOSED Friday June 19** (Juneteenth). Next session: Monday June 22.

---

## STEP 1 — TRADEABLE AH GAPPERS (>$1B mkt cap, >3% gap)

**Source:** WebFetch stockanalysis.com/markets/afterhours/gainers/ + /losers/ (top-20 %-sort, Chrome MCP unavailable).

### Gainers

All 20 entries on the stockanalysis AH gainers page are micro-caps under $100M market cap. **ZERO pass the >$1B filter.** Largest: CANG $77.94M. This is a valid honest result for a Friday ahead of a holiday weekend.

### Losers (>$1B filter)

| Ticker | Company | AH % | AH Price | Mkt Cap | Conviction | Notes |
|--------|---------|------|----------|---------|-----------|-------|
| HQ | Horizon Quantum Holdings | -11.19% (stockanalysis) | $28.42 | $1.65B | 🟡 | ⚠️ DATA CONFLICT — see below |

**HQ Data Conflict:**
- stockanalysis AH: $28.42, -11.19% (implies prior close ~$32)
- TV MCP quote_get session close: **$29.00** (range $26.78–$31.80 intraday, vol 34,067)
- Web search (different timestamp): HQ at $29.80, +26% AH at one point
- Calculated: if session close = $29.00, then AH $28.42 = -2.0% AH, not -11.19%. The stockanalysis -11.19% likely references yesterday's (June 17) close of ~$32. Stock gapped up today from $32 → traded $26.78–$31.80 → closed $29.00 → AH ~$28.42.
- **Catalyst:** Quantum computing sector volatility; IonQ deal news (June 15 expanded commercial footprint). Data too conflicting for high conviction.
- **AH volume:** Unverified — conviction capped 🟡.
- **Tomorrow's setup:** Markets closed June 19. Monday June 22 gap-down risk from continued weakness.

---

## STEP 2 — ETF AFTER-HOURS SWEEP (57-ETF Embedded Universe)

**Data source:** TV MCP batch_run (get_ohlcv, 2 bars), regular session closes as of 4 PM ET June 18, 2026.  
⚠️ **Note:** batch_run returns SESSION closes, not AH prices. ETF AH volume is very thin Friday afternoon. Values shown are regular-session changes. AH ETF moves not confirmed.  
⚠️ **Note:** Some ETFs (SHLD, XME, XHB, JETS, PEJ, UNG, MOO) have last bars from ~12 PM ET (midday) due to thin liquidity — their "closes" may not reflect 4 PM official print.

### ETFs with Session Moves ≥ 1% (Notable)

| ETF | Theme | Session % | Close | Key Catalyst |
|-----|-------|-----------|-------|-------------|
| **USO** | Crude oil | **+2.19%** | $114.55 | Demand optimism despite Iran deal Hormuz reopening |
| **UNG** | Natural gas | **+1.91%** (midday) | $11.74 | LNG demand; power burn |
| **XHB** | Homebuilders | **+1.77%** (midday) | $111.01 | Iran deal → rate relief expectations |
| **SHLD** | Defense tech | **-2.70%** (midday) | $62.25 | Iran peace = defense de-risking |
| **XME** | Metals/mining | **-1.70%** (midday) | $116.96 | Materials rotation out |
| **JETS** | Airlines | **+1.37%** (midday) | $31.02 | Iran peace = travel/logistics optimism |
| **ARKK** | Speculative growth | **+1.12%** | $79.99 | Risk-on Friday |
| **IBIT** | Spot Bitcoin | **+1.19%** | $35.70 | Crypto risk-on |
| **TAN** | Solar | **+1.13%** | $60.98 | Energy transition + rates |
| **XBI** | Biotech small-cap | **+0.84%** | $140.46 | Broad market bid |
| **CIBR** | Cybersecurity | **+1.15%** | $84.74 | |

### SHLD vs. ITA Attribution
- SHLD: -2.70% | ITA: -0.09% → **Divergence = SHLD-specific, not broad defense sell-off** (ITA barely moved). SHLD is PLTR-heavy but PLTR was +1.24% today — SHLD decline may reflect broader Iran peace rotation out of defense tech names beyond PLTR.

### Defense Pair: NOT a theme-wide breakout (SHLD fell hard, ITA flat — diverging signals)
### Biotech Pair: XBI +0.84% / IBB +0.51% — both up modestly, **not a THEME-WIDE BREAKOUT** (moves moderate)
### Airlines/Travel: JETS +1.37% / PEJ -0.15% — diverging (JETS up, PEJ flat) — **NOT theme-wide**

### All 57 ETFs — Complete Session Close Data

**INDEX / REGIME:**
- SPY: $748.02 (+0.23%) | QQQ: $740.42 (+0.29%) | IWM: $295.43 (+0.52%)
- VIX: $16.41 (-1.56%) — low fear, risk-on | HYG: $80.03 (+0.05%) — credit calm
- TLT: $86.73 (-0.12%) | UUP: $28.30 (+0.14%) | GLD: $386.49 (-0.38%)

**SECTOR SPDRs:**
- XLK: $191.52 (+0.38%) | XLV: $149.66 (+0.54%) | XLF: $53.65 (-0.51%)
- XLE: $53.82 (+0.43%) | XLI: $181.52 (+0.13%) | XLY: $117.16 (+0.13%)
- XLP: $83.42 (-0.11%) | **XLU: $44.80 (-1.06%)** | XLB: $51.97 (-0.09%)
- XLC: $109.35 (-0.39%) | XLRE: $43.96 (-0.54%)

**INDUSTRY GROUPS:**
- SMH: $661.25 (+0.59%) | IGV: $89.21 (+0.54%) | CIBR: $84.74 (+1.15%)
- XBI: $140.46 (+0.84%) | IBB: $173.04 (+0.51%) | KRE: $71.63 (+0.08%)
- XOP: $153.42 (+0.60%) | XHB: $111.01 (+1.77%) | XRT: $86.30 (-0.25%)
- IYT: $83.94 (-0.64%) | JETS: $31.02 (+1.37%) | PEJ: $65.51 (-0.15%)

**AI / TECH THEMES:**
- DRAM: $77.35 (+0.79%) | QTUM: $168.50 (+0.78%) | BOTZ: $38.44 (+0.44%)
- ARKK: $79.99 (+1.12%) | ARKX: $34.26 (+0.23%) | AIPO: $33.90 (+0.06%)
- DTCR: $31.86 (-1.03%) | SHLD: $62.25 (-2.70%) | ITA: $239.00 (-0.09%)
- WGMI: $72.49 (+0.40%) | IBIT: $35.70 (+1.19%)

**POWER / MATERIALS:**
- URA: $47.90 (+0.84%) | NLR: $127.00 (+0.19%) | GRID: $194.77 (+0.20%)
- TAN: $60.98 (+1.13%) | COPX: $85.38 (-0.76%) | REMX: $95.65 (-0.08%)
- XME: $116.96 (-1.70%) | LIT: $81.83 (-0.39%) | GDX: $82.41 (-0.21%)
- GDXJ: $107.43 (-0.02%) | SLV: $59.43 (-0.55%)

**COMMODITIES / GLOBAL:**
- USO: $114.55 (+2.19%) | UNG: $11.74 (+1.91%) | MOO: $76.94 (-0.09%)
- KWEB: $25.25 (+0.06%)

---

## STEP 3 — FINVIZ AH NEWS DIGEST

*Source: WebFetch finviz.com/news (public feed). Finviz Elite filter unavailable — public feed used.*

| Time ET | Headline | Ticker | ETF Bucket | Attribution |
|---------|----------|--------|-----------|-------------|
| 4:30 PM | **Trump Announces Intel-Apple Partnership** (chip design/build in US) | INTC, AAPL | XLK, SMH | INTC AH -7.01% → sell the news |
| 4:42 PM | Trump cites market gains as validation of Iran deal | — | SPY/QQQ (macro) | Confirms risk-on theme |
| 4:46 PM | Reformation (clothing brand) prepares for summer IPO | — | UNCLASSIFIED (pre-IPO) | Watch XRT post-IPO |
| 4:31 PM | Wall St advances with boost from chips, Iran optimism | SPX, COMP | SPY, QQQ, SMH | Session close story |
| 4:15 PM | Stock Market Today: U.S. Stocks Close Week on Strong Note | — | SPY | Session close recap |
| 4:05 PM | Nasdaq, S&P 500 end on sharp gains as stocks rebound on Iran deal | — | SPY, QQQ | Session close |
| 4:03 PM | S&P 500 closes higher, Nasdaq climbs nearly 2% on chips | — | SPY, QQQ, SMH | Session close recap |

**UNCLASSIFIED:** Reformation IPO (clothing brand, no ticker yet). RFMD ticker noted in Finviz but appears to be a placeholder — Reformation is not yet public.

---

## STEP 4 — WATCHLIST AH ACTIVITY

*Data: TV MCP batch_run (session closes). AH prices via web search where available. All times: session close pulled at ~5:30 PM ET.*

| Ticker | Session Close | Session % | AH Price | AH % | AH Vol | Notes |
|--------|-------------|-----------|---------|------|--------|-------|
| **INTC** | $134.26 | +0.92% | **$129.59** | **-7.01%** | unverified | ⚠️ Apple partnership sell-the-news |
| TSLA | $399.83 | +2.26% | n/a | n/a | — | Strong session, Iran deal beneficiary |
| NVDA | $210.21 | +0.60% | n/a | n/a | — | Steady; SMH +0.59% |
| AMD | $537.55 | +0.45% | n/a | n/a | — | |
| PLTR | $128.88 | +1.24% | n/a | n/a | — | Defense tech ETF confusing vs PLTR actual performance |
| SNDK | $2,203.56 | +1.48% | n/a | n/a | — | |
| MARA | $14.19 | +1.14% | n/a | n/a | — | Bitcoin miner, IBIT +1.19% |
| META | $578.00 | +0.18% | n/a | n/a | — | |
| SOFI | $17.87 | +0.45% | n/a | n/a | — | |
| COIN | $163.38 | -0.31% | n/a | n/a | — | |
| AMZN | $243.74 | -0.04% | n/a | n/a | — | |
| AAPL | $297.83 | +0.12% | n/a | n/a | — | Partnership beneficiary but muted |

**SPY Sanity Check:** $748.02 (+0.23%) — within 5% bounds ✅  
**QQQ Sanity Check:** $740.42 (+0.29%) — within 5% bounds ✅  
Note: Headlines claim "Nasdaq nearly 2%" — TV MCP shows QQQ +0.29%. Discrepancy may reflect intraday high vs. session close fade, or index vs. ETF difference.

---

## STEP 5 — AMC EARNINGS RESULTS

**No major AMC earnings tonight.** Confirmed via web search — earnings whispers shows no significant reports after close June 18, 2026. AMC Entertainment (AMC) next reports Aug 11, 2026.

---

## STEP 6 — CATALYST ATTRIBUTION FOR AH GAPPERS

### INTC — Not from stockanalysis screen but the most important AH mover on the watchlist

| Field | Detail |
|-------|--------|
| **Ticker** | INTC (Intel Corporation) |
| **Mkt Cap** | ~$600B (US government owns 10% stake; per web search) |
| **AH Price** | $129.59 (-7.01% from $134.26 close) |
| **Catalyst Type** | POLICY-STAKE / CONTRACT |
| **Catalyst** | Trump announces Apple-Intel chip partnership to manufacture chips in US (4:30 PM ET). Intel to design/build chips for Apple in America, reducing reliance on TSMC. US government holds 10% equity stake in Intel (~$60B). |
| **Primary Source** | CNBC: "Intel gains 10% after Trump says company will partner with Apple on U.S. chip design" |
| **Direction** | DOWN AH (-7%) despite partnership — sell-the-news. Foundry services running $2.4B operating loss in Q1 2026; 18A node yields below profitable levels. Foundry economics unfavorable. |
| **ETF Bucket** | SMH, XLK |
| **Tomorrow's Setup** | Markets CLOSED June 19. Monday June 22: gap-down open likely if AH weakness holds. Watch SMH open. |

### HQ — Only >$1B entry from stockanalysis losers

| Field | Detail |
|-------|--------|
| **Ticker** | HQ (Horizon Quantum Holdings Ltd.) |
| **Mkt Cap** | $1.65B |
| **AH Price** | ~$28.42 (stockanalysis); TV MCP session close $29.00 |
| **Catalyst Type** | Catalyst unconfirmed (data conflict — flag for 8 PM scan to investigate) |
| **AH Volume** | Unverified — conviction 🟡 |
| **Direction** | DOWN (session range $26.78–$31.80; volatile) |
| **ETF Bucket** | QTUM (quantum — IONQ, RGTI, QBTS anchor) |
| **Tomorrow's Setup** | Markets closed June 19. Monday June 22 TBD. |

---

## STEP 7 — TOMORROW'S EARNINGS PREVIEW

**Markets CLOSED June 19, 2026 (Juneteenth).** No trading session tomorrow.

**Monday June 22:** Earnings calendar unavailable via WebFetch (site requires login). Verify manually via Earnings Whispers or Zacks before Monday open.

---

## STEP 8 — PERSONAL POSITIONS PLAN

**Theme bias for Monday June 22:** Risk-on, geopolitical tail removed, but:
- **Headwind:** INTC AH -7% → SMH may gap down Monday. Watch if weakness bleeds into NVDA/AMD.
- **Tailwind:** Iran peace deal fully priced for airlines, homebuilders, energy importers.
- **Key overnight risk:** INTC gap-down Monday could create a "chip hangover" overhang on SMH/XLK early Monday morning. PLTR still firm (+1.24%) — ITA/defense primes did not sell off, so SHLD weakness may be sector-specific.
- **USO +2.19%** — counterintuitive with Iran deal in place; monitor for whether oil strength fades Monday.
- **Gold (GLD -0.38%) / Defense (SHLD -2.7%):** Both selling with Iran peace deal — consistent risk-on rotation narrative.
- **TSLA +2.26%:** Strong session; no specific catalyst identified beyond general risk-on bid.

---

## STEP 9 — ASSUMPTION AUDIT

| Item | Status | Notes |
|------|--------|-------|
| TV MCP price method | batch_run (get_ohlcv) | Primary method; used for all 57 ETFs and 12 watchlist stocks. quote_get used for INTC/HQ/AAPL AH sanity check |
| AH ETF prices | NOT confirmed via TV MCP | batch_run returns session closes (4 PM ET bars). ETF AH moves not pulled — session changes reported only |
| Some ETF bars (midday) | SHLD, XME, XHB, JETS, PEJ, UNG, MOO | Last bars at ~12 PM ET; these ETFs illiquid at close |
| Chrome MCP | ⚠️ unavailable | Automated run; WebFetch top-20 only — $1B+ names beyond page 1 may be missed |
| AH gapper gainers | All micro-caps <$100M | ZERO pass >$1B filter — valid result |
| AH gapper losers | HQ only at $1.65B | Data conflict between stockanalysis, TV MCP, and web search |
| HQ AH | ⚠️ DATA SUSPECT | stockanalysis -11.19% vs TV MCP implied -2% vs web search +26% at different timestamp |
| INTC AH | -7.01% per web search | Not confirmed via TV MCP AH pull (batch_run = session close) |
| Finviz Elite filter | Unavailable | Public feed used |
| QQQ +0.29% vs "Nasdaq nearly 2%" | Discrepancy noted | Intraday high vs. close, or COMP vs QQQ difference |
| AMC earnings | None tonight | Confirmed |
| Markets June 19 | CLOSED (Juneteenth) | Next session Monday June 22 |
| Monday June 22 earnings | Calendar unavailable | Verify manually |
| AH volume | Unverified for all entries | TV MCP batch intraday pull not attempted; no AH volume column on stockanalysis |
| UNCLASSIFIED headlines | Reformation IPO | Pre-IPO clothing brand, no ticker |
| USO +2.19% | Counterintuitive vs Iran deal | Demand optimism or OPEC dynamics — noted, not resolved |
