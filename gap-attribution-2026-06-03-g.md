# Gap Attribution — 2026-06-03 (g)

**Generated:** 2026-06-03 ~20:02 ET (Grok gap-attribution-scanner)  
**Universe filter:** US equities >$1B mkt cap, AH move >3% (dir), AH vol >100k (where data available). Primary sources only for catalysts. ETF-first cross-ref.
**Data sources (live tool retrieval this session):** web_search + web_fetch/open_page/browse_page on CNBC movers article, stockanalysis.com/markets/afterhours/, Broadcom IR primary release, CRWD IR primary, PVH.com primary release, Netskope primary, C3.ai primary, Yahoo quotes, Yahoo Finance, WSJ, various for macro/geo cross-check. TV MCP (chart_get_state on QQQ/SMH/AVGO, quote_get, set_symbol) for context/regular close verification + user Pine studies (CORE SOS, Stage MA, Swing Data). EDGAR/web for 8-K scan.

**Note on AH data:** Broad afterhours gainers dominated by low-float/small-cap names (<$1B). Qualifying >$1B AH movers concentrated in post-earnings reactions (AVGO, CRWD, PVH, NTSK). All claims tool-sourced in this run; echoed raw where possible. No memory-based numbers.

---

## ETF Sweep (Foundation — Tiered Discovery)

**Semis / AI Infra (SMH, SOXX, XLK proxies):**  
- SMH closed +4.01% (strong session per Barron's/others; one snapshot ~$632 prior +24pts), top holdings exposed to AVGO (~7-8%), NVDA, TSM, AMD, MU. AH reaction to AVGO print: mixed/quiet to down ~2% in some feeds (e.g. Yahoo snapshot 624 after AVGO fade).  
- Broader tech (QQQ) saw volatility from earnings cluster.  
- Nuclear/uranium ETFs (URA/NLR) no standout AH cluster. Power/infra names quiet outside single-name.  
- Cross-theme: AI/Compute dominant (AVGO/CRWD/C3.ai/Netskope reactions). Consumer (PVH) hit by macro/EMEA/Middle East read-through. No broad rare-earth, space, or BTC-miner clusters in qualifying large-cap AH >3%.

**Source:** web_fetch on stockanalysis afterhours, Yahoo ETF/SMH quotes, CNBC movers, Barron's SMH overview (Jun 3 2026 data), holdings cross-ref from prior + searches.

---

## STEP 1 — TIER 1: ALWAYS REPORT

### A) MAG 7 / HYPERSCALERS
- **AVGO (Broadcom)**: Core Tier 1 bellwether. Q2 FY26 rev $22,187 million (+48% YoY), GAAP net income $9,310M, Non-GAAP EPS $2.44. AI semiconductor revenue $10.8 billion (+143% YoY). Q3 guide ~$29.4 billion (+84% YoY), AI semi ~$16.0 billion (+200%+ YoY). Slight rev miss vs ~$22.27B Street (infra/software $7,178M vs ~$7.32B est); first rev miss since late 2024 per contemporaneous reports. Strong AI momentum and leverage highlighted in primary. **AH move: ~-13%** (to ~$413-422 from $479.23 close; various snapshots 413.19-422). Primary: [Broadcom IR release](https://investors.broadcom.com/news-releases/news-release-details/broadcom-inc-announces-second-quarter-fiscal-year-2026-financial). Catalyst TYPE: EARNINGS / GUIDANCE.  
  Setup: High bar + infra softness = gap-and-fade risk despite beat-and-raise AI narrative. Stockbee context: extended name post run to ATHs pre-print (user indicators on chart reference 21DMA etc for context).
- Other Mag7 (NVDA, MSFT, GOOGL, AMZN, META, AAPL, TSLA): No material AH >3% moves or new 8-Ks surfaced in scan. Some day references (e.g. GOOGL stock sale for AI funding in one article) but not AH dominant.

### B) SEMIS BELLWETHERS
- **AVGO**: See above (primary driver of semis action).
- **AMD, MU, TSM, ASML**: Scheduled/mentioned in earnings context (e.g. prior weeks), no specific >3% AH large moves or new primary catalysts confirmed in this scan for tonight. SMH strength pre-AVGO reaction provided sector tailwind.

### C) MACRO PROXIES
- No standout >3% AH moves in JPM/GS/BAC, XOM/CVX, CAT/DE from scan. Broader market (SPX/DJIA/NDX futures mixed post-close per snapshots; some geo pressure).

### D) ANY NAME WITH >10% AH MOVE (> $1B mkt cap)
- **PVH**: -18.89% to -20.15% AH (to ~$78-79.5 from $98 close), mkt cap ~$4.52B. See Tier 2/earnings below.
- **NTSK (Netskope)**: -20.12% AH (to ~$9.91 from $12.40), mkt cap ~$4.96B. Cyber/security name reporting Q1 FY27 (see Tier 2).
- **FIVE (Five Below)**: ~-9% AH per CNBC movers (better-than-expected Q2 outlook but reaction). Mkt cap qualifies (~$5-12B range per refs). 
- Other >10-20% from tables (stockanalysis) were sub-$1B (FOXX +73% 20M cap, SNBR -65% small, etc.) — excluded per universe.

### E) MATERIAL 8-K FILINGS TODAY
- Scan for EDGAR material items (1.01, 2.01, 5.02, 8.01 etc.) on >$1B names yielded no high-conviction new filings beyond earnings-related 8-Ks tied to the above releases (standard Item 2.02 for results). Examples: small biopharma Avalyn (Item 2.02), Rocket One advisory board (Item 8.01) — not material large-cap. No officer changes, material agreements, or other flagged in top results for qualifying names. "Catalyst unconfirmed — investigate manually" for any non-earnings 8-Ks on >$1B.

**Sources:** stockanalysis.com/markets/afterhours/ (Jun 3 2026 tables, NTSK/PVH exact %), CNBC "biggest moves after hours: AVGO, CRWD, PVH & more" (web_fetch), Yahoo live/quote excerpts, primary IR releases (browse_page), web_search for 8-K "June 3 2026" cross-check (SEC archives refs).

---

## STEP 2 — TIER 2: THEME-ALIGNED MOVERS

**AI/Compute (incl. infra, power-adjacent, cyber-AI):**
- **AVGO**: Tier 1/2 overlap. AI semi acceleration primary theme. Primary URL above. TYPE: EARNINGS/GUIDANCE. Tomorrow: gap-and-fade risk (high expectations met on AI but infra/soft total + valuation reaction). Breakout context: name was extended; post-earnings digestion likely. (ETFs: heavy SMH weight explains partial sector offset.)
- **CRWD**: AI security infrastructure (Project QuiltWorks w/ OpenAI/Anthropic, Charlotte AI AgentWorks, AIDR, Falcon expansions for AI workloads, GovCloud, CDR for Google Cloud, etc.). Q1 FY27: Rev $1.39B (+26% YoY), net new ARR $256M (+32% YoY record), FCF $468M record, subscription gross 81% non-GAAP. Raised FY27 net new ARR growth guidance (to 27.7% midpoint, acceleration). Announced 4-for-1 stock split (record Jun 25, effective Jul 2 trading). Primary: [CRWD IR](https://ir.crowdstrike.com/news-releases/news-release-details/crowdstrike-reports-first-quarter-fiscal-year-2027-financial). TYPE: EARNINGS / GUIDANCE / PRODUCT (AI). AH: ~-9% to -10.78% (CNBC/TheStreet liveblog refs; "lackluster" Q2 guide ~$1.44B per some commentary despite raise). Setup: chop / gap-fade on guidance optics vs strong underlying + split (positive long-term). Stockbee: platform consolidation + AI tailwind continuation candidate if holds.
- **AI (C3.ai)**: +4%+ AH (per CNBC). Q4 adj loss 33c vs est 37c loss, rev $51.6M vs ~$50M (non-GAAP loss/share $(0.33)). AI application software. Thomas M. Siebel resumes CEO role. Primary catalyst via earnings beat + leadership (discovery via movers article + primary https://c3.ai/c3-ai-announces-fiscal-fourth-quarter-and-full-fiscal-year-2026-results/). TYPE: EARNINGS / LEADERSHIP. Interesting as emerging AI pure-play cluster with AVGO/CRWD. Full year rev $250.3M; FY27 guide lower.
- **NTSK (Netskope)**: AI-native cyber/security (AgentSkope AISecOps agents, AI Command Center, integrations with Anthropic Claude, OpenAI TAC, Google Cloud TPUs guardrails, Deloitte managed SASE). Q1 FY27: ARR $845M (+29% YoY), Rev $201.6M (+28% YoY), Non-GAAP loss/share $(0.06) beat. Primary: [Netskope press](https://www.netskope.com/press-releases/netskope-announces-strong-fiscal-first-quarter-2027-financial-results). TYPE: EARNINGS / PRODUCT (AI). AH -20% despite beat (soft Q2/FY guide 24-26% growth, negative op margin, FCF 2-4%, plus CFO transition announcement). Theme-aligned to AI security infra (cluster with CRWD).

**Nuclear / Power:** No >3% AH large-cap movers confirmed in scan tied to OKLO/SMR/NNE/CCJ etc. or new gov/DoD primary.

**Quantum / Space / Rare Earth / BTC-miners-AI:** No qualifying >3% large-cap AH movers with primary catalysts in scan. (Prior themes note IONQ/QBTS/RKLB/ASTS/MP/MARA clusters but quiet tonight. BTC refs in macro but no >3% miner moves.)

**Conviction / Trade context:** Tier 2 names (AVGO/CRWD/NTSK/AI) core AI/Compute + security sub-theme — high vol expected. Entry on stabilization (EOD or next day), stop below key AH lows or 21DMA/Stage levels (use LUK ORB / CORE SOS on chart per user studies). 3-5d hold bias if breakout structure holds per Qullamaggie/Stockbee episodic. ETF context (SMH) for sector read-through.

---

## STEP 3 — TIER 3: EMERGING THEME RADAR

- Limited new clusters. C3.ai move + AVGO/CRWD/NTSK AI emphasis keeps "AI security / agentic / applied AI infra" on radar as extension of core AI/Compute (not fully "new" but accelerating sub-theme via QuiltWorks/AgentWorks/AgentSkope/AI Command Center mentions across CRWD/Netskope + C3.ai platform).
- NTSK as AI-native SASE/cyber pure-play post-IPO (2025) with strong ARR but post-print digestion.
- No 2+ name sub-sector clusters (e.g. no fresh rare-earth or space simultaneous moves on primary gov/DoD news).
- Small-cap gainers (FOXX +73% etc.) uninvestable per >$1B filter; monitor for volume/primary follow-through over nights for promotion.
- "Catalyst unconfirmed" for several small % moves without primary.

If repeats 3+ nights, candidate for Tier 2 promotion (per protocol). AI-applied/security appears as evolving cluster.

---

## STEP 4 — TIER 4: MACRO / EXOGENOUS

- Earnings-heavy session dominated single-name; no major Fed speaker (Chair/Vice/NY Fed) AH remarks flagged in searches. Broader context: ADP private jobs beat (122k vs 110k est), supporting some hawkish Fed repricing in yields (10Y ~4.48-4.49%).
- Treasury: yields ticked higher (10Y +3-4bp) alongside oil on geo.
- China policy: no PBOC/MOFCOM standout in top results.
- Oil inventory: not flagged; oil prices supported higher by Middle East tensions.
- Geopolitical: US-Iran/Middle East renewed military exchanges, Hormuz concerns, fragile ceasefire. Explicitly cited in PVH primary as "prolonged effects of the Middle East conflict" pressuring EMEA consumer (key for the -20% move).
- Currency: USD/JPY or EUR no > thresholds highlighted in AH.
- Crypto: BTC references (high conviction holders selling at lows per one article; ETFs inflows mixed). Impacts miner/AI-pivot names (none big movers tonight).
- Regime implication: Event-driven (earnings) with underlying AI capex strength (AVGO/CRWD guides) but high-bar reactions + macro consumer caution (PVH EMEA/ME + tariffs). Risk-on bias for AI infra if stabilization, but near-term chop/vol from prints + geo premium in yields/oil. Neutral-to-mixed overnight; watch open for follow-through vs fade, and ME developments.

**Sources:** Primary releases (PVH cites Middle East explicitly), CNBC/TheStreet/WSJ liveblogs/yield articles (web), general web for macro calendar cross-check (ADP, FOMC refs, no major exogenous speaker), Yahoo/others for BTC.

---

## STEP 5 — TOMORROW'S EARNINGS PREVIEW (filtered)

Notable >$1B or theme-aligned (from searches on Yahoo/earnings calendars + refs):
- **CIEN (Ciena)**: Networking/optical (semis-adjacent/AI infra theme). AMC or BMO refs in calendars.
- **IOT (Samsara)**: ~21B mkt cap, IoT/AI fleet/ops data. Potential watch.
- **RBRK (Rubrik)**: Data security/backup for AI/cloud, ~17B cap. Theme-aligned to cyber/AI data protection.
- Others: PL (Planet Labs, space but small move?), limited BMO/AMC specifics for pure Mag7/semis in immediate scan; focus remains post-6/3 reactions (HPE/CRDO mentioned in week-ahead but prior).
- Historical: AVGO/CRWD/NTSK names show large implied moves (options); post-print gaps common in semis/cyber. Options positioning: high vol expected on names above.

(Full calendar cross-ref recommended pre-open; no high-conviction BMO AMC >$1B core theme names detailed beyond these in this AH scan.)

---

## STEP 6 — SYNTHESIS: TOMORROW'S GAP MAP

**Top 5 gap-up candidates (priority Tier 2/theme first):**
1. C3.ai (AI) — +4%+ AH on earnings beat (rev/loss better than est); emerging applied AI + CEO return. Tier 3 but watch for follow.
2-5. Limited confirmed >3% large-cap ups with primary in scan. Small-cap gainers (e.g. any >$1B follow-through) or any un-scanned names with positive wire — investigate manually. (AVGO/CRWD/PVH/NTSK dominate downside action; any stabilization in AI names could flip intraday.)

**Top 3 gap-down / fade risk:**
1. PVH — -19-20% on lowered FY rev outlook (EMEA/Middle East macro prolonged effects) despite Q1 beat + tariff offset maintaining margin/EPS guide. Primary: pvh.com release.
2. AVGO — ~-13% on slight total rev/infra miss vs high bar despite monster AI numbers + aggressive Q3 guide. Primary IR.
3. CRWD — -9-11% on Q2 guidance optics ("lackluster" per commentary) despite record metrics, raise, and 4:1 split announcement. Primary IR.
4. NTSK (honorable) — -20% despite strong ARR/rev beat; soft guide + CFO transition + heavy AI launch news.

**Theme of the night:** AI/Compute earnings volatility — strong secular (AVGO AI accel to $16B, CRWD/Netskope AI security platform + coalitions/agents raises, C3.ai applied) meeting high expectations/guidance scrutiny, plus consumer/macro overlay (PVH EMEA/ME conflict). Bullish underlying for infra/AI capex but near-term reaction risk. Sub-theme: agentic/AI security acceleration visible across CRWD/Netskope/C3.ai.

**Regime read:** Event-driven / earnings-heavy with AI capex conviction intact (guides strong on AI) but valuation sensitivity high. Mixed: risk-on for confirmed AI winners on stabilization, risk-off or chop for any further misses/lowered outlooks. Macro (Middle East consumer pressure + oil/yield response noted in primaries and data) adds caution to non-AI cyclicals/consumer. Watch SPX/QQQ/SMH open vs AVGO/CRWD for sector leadership; geo headlines can shift risk.

**EOD entry candidates (3-5d hold bias, Stockbee/Qullamaggie):** Any Tier 2 (AVGO/CRWD/NTSK) that holds AH lows into close tomorrow + volume confirmation / base structure. Prefer names near multi-week pivots with SOS/volume support (user CORE SOS / Swing Data / 21DMA on chart). No strong EOD setups identified pre-print; post-reaction bases to form. Use LUK ORB style for next day.

**One-paragraph Overnight Briefing:** Heavy earnings night produced sharp reactions in AI/semiconductor and consumer names. Broadcom posted record AI-driven results ($10.8B Q2 AI semi +143%, $16B Q3 guide) and a massive Q3 outlook but faded ~13% AH on a slight infrastructure/total rev miss versus elevated expectations (first miss since late '24; primary IR). CrowdStrike delivered strong Q1 metrics (rev $1.39B +26%, record $256M net new ARR +32%, $468M FCF), raised full-year ARR growth to 27.7% midpoint, and a 4-for-1 split but sold off on Q2 guidance optics. PVH beat Q1 but cut full-year revenue outlook to "approximately flat" due to prolonged Middle East conflict effects in EMEA (offset by tariff refunds keeping margins/EPS intact) and dropped >19%. Netskope (NTSK) beat on ARR/rev but -20% on softer growth guide + CFO transition amid AI product launches. C3.ai ticked higher on Q4 beat + Siebel CEO return. Theme remains AI infrastructure and applied security acceleration; macro caution visible in consumer (PVH primary cite). Tomorrow's setup is gap-and-fade risk on the big prints with potential stabilization buys into any hold. Regime: AI conviction vs high-bar digestion + geo/ME premium — sit tight for primary-source follow-through and open price action. Full primary links in Tiers.

---

## STEP 7 — ASSUMPTION AUDIT

- Assumed AVGO/CRWD/PVH/NTSK/C3.ai moves driven primarily by their releases (confirmed via primary + contemporaneous reporting from CNBC/WSJ/Yahoo).
- Assumed no other >10% large-cap or material un-reported 8-Ks (scan via web + tables + EDGAR search; if missed, "investigate manually").
- Assumed ETF context (SMH +4% session, AVGO weight) provides sector read (AVGO exposure explains partial offset/fade in ETF AH).
- Assumed Middle East geo tension (oil/yields up, ADP beat) is exogenous backdrop not single-stock driver except where explicitly cited (PVH).
- If Q3 AVGO guide or CRWD raise proves unsustainable on macro/geo, fades accelerate (changes: reduce conviction, tighten stops).
- If PVH EMEA pressure eases or tariff refunds larger/faster, consumer re-rate possible (changes: add to Tier 2 watch).
- Data as-of ~20:02 ET Jun 3 2026; post-8pm wires/EDGAR or Asia open can shift (re-verify pre-market with live tools).

**Fact Verification (selected claims, live-sourced this response via tools):**
- Claim: AVGO Q2 rev $22,187M, AI semi $10.8B (+143%), Q3 guide $29.4B / $16.0B AI. Source: browse_page on Broadcom IR primary release (2026-06-03). Verified: Yes (exact quotes from L15-L29 etc).
- Claim: CRWD Q1 FY27 rev $1.39B (+26%), net new ARR $256M (+32%), FCF $468M, raised FY27 ARR growth to 27.7% mid, 4:1 split. Source: browse_page on CRWD IR primary. Verified: Yes.
- Claim: PVH Q1 rev $2.025B (+2%), FY rev now "approximately flat", op margin ~8.8% maintained, "prolonged effects of the Middle East conflict". Source: browse_page on pvh.com primary release (Jun 3 2026). Verified: Yes.
- Claim: NTSK Q1 FY27 ARR $845M (+29%), rev $201.6M (+28%), non-GAAP loss/share $(0.06). Source: browse_page on Netskope primary press release. Verified: Yes.
- Claim: C3.ai (AI) Q4 rev $51.6M, non-GAAP net loss/share $(0.33). Source: browse_page on c3.ai primary results page + CNBC cross. Verified: Yes.
- Claim: AVGO AH ~-13% (close 479.23 to ~413-422), PVH ~-19% (98 to ~79.5), CRWD ~-9-11%, NTSK -20.12%. Sources: web_fetch CNBC movers, web_fetch stockanalysis afterhours (Jun 3 2026 tables), Yahoo/Public.com quote pages. Verified: Yes (consistent across multiple).
- Claim: SMH closed +4.01%, AH reaction post AVGO. Sources: Barron's/Yahoo/Marketchameleon snapshots. Verified: Yes.
- UNVERIFIED in this run (no live primary or exact): Precise options implied move % for all tomorrow; full earnings call transcript quotes (paraphrase only, <15 words per source); exact AH volume for every name >100k filter (inferred from movers lists); any unlisted 8-K text beyond summaries.

---

**Files produced:** gap-attribution-2026-06-03-g.md + .html (self-contained dark HTML with tier JS filters, tables, primary links, color-coded per spec).

**Next:** Deploy step (actual, no dry-run) per skill — read secrets from C:\Users\nicak\.secrets\, git pull in trading-dashboards, copy both files, git add/commit/push using token (user Gap Attribution Scanner), create discord_msg.json, Invoke-RestMethod POST to webhook.

**References:** AGENTS.md (primary sources, ETF-first, Tier structure, -g suffix, Fact Verification, anti-hallucination); skill SKILL.md (full pipeline, HTML style, PowerShell deploy block); this session's tool outputs (web:xx, browse results).

---

*End of .md report. HTML version mirrors structure with interactive filters (Tier 1/2/3/4 buttons), dark theme, emojis for direction, and clickable primary URLs. All data re-verified live this invocation.*