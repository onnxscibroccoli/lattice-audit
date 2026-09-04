# Audit prompt — paste this entire file into ChatGPT or Gemini

You are a risk officer. Do not flatter. Do not add sectors. Do not produce targets. Do not declare a market boom. Return only: GO/NO-GO for MODE=STAGED funding of the $5,000 table below on the next US cash session, plus mechanical defects if any.

US session note: Friday 4 Sep 2026 cash market is open until 16:00 America/New_York. Monday 7 Sep 2026 is Labor Day (closed). If they miss Friday, next session is Tuesday 8 Sep 2026.

## What this is

Project LATTICE. Thesis-first physical AI-infrastructure book. Human clicks. AI drafts. No broker API.

Thesis: tokens and watts keep rising. The stack (foundry, EUV, WFE, HBM, custom silicon, optics, power, materials, defense hardware) gets paid whether megawatts land in mega-campuses, smaller nodes, or both. Campuses are the floor. Lattice geography is the ideal, not the admission ticket. Nuclear and quantum are options, not the trunk.

This is four risk factors, not fifteen bets. Compute names glue (ASML–LRCX 1y corr 0.85). Lottery names (IONQ QBTS OKLO SMR) trade as one long-duration spec factor. RTX is the ballast that actually hedged 2022 (+19% vs compute ~−39%). RTX did **not** hedge COVID.

Planning math used ~25% blended public-market, not 97%. A $12M daughter outcome is voice+access, not this ticker list. "Profit in every regime" is rejected.

## MODE=STAGED (arithmetic locked. Funding this session is NO-GO until kill quotes exist.)

```
NAV 5000
Rule cash 400          (8% — the cash rule)
A_RESERVE 2300         (Sleeve A held in cash; NOT rule cash; NOT invested)
Fifteen B+C 2300
```

Tickets:

TSM 423, ASML 354, AVGO 212, LRCX 142, MU 142, LITE 142, IONQ 142,
COHR 106, GLW 106, QBTS 106, OKLO 106, RTX 106, APH 71, MRVL 71, SMR 71.
Sum 2300.

Themes (one label): compute TSM ASML AVGO LRCX MU MRVL; optics LITE COHR GLW APH; lottery IONQ QBTS OKLO SMR; defense RTX.
Caps: name 10% NAV, theme 35% NAV.

A_RESERVE converts only: (1) COMPRESS initial fill — not selected; (2) NAV ≥ 15000 next quarter; (3) quarterly DCA/ACCELERATE. Off-list = BROKE.

Day-one ignores sentiment. No extra names.

Rebalance quarterly iff weight outside [0.8t, 1.2t] AND dollar gap ≥ $50. Name cap wins.

## Kill (beats narrative)

Trunk if any two of: TSM leading-edge util <80% two quarters (or two soft leading-edge quotes); LRCX next-quarter guide < same quarter last year; two of MSFT AMZN GOOGL META cut FY capex two seasons.
ASML bookings lag; do not wait for them.
TSM also dies on lost process lead or two mix/margin fades.
Optics: two quarters GM down + pricing cited.
OKLO/SMR: no binding offtake by Q3 2028 or interconnect after 2031-12-31.
IONQ/QBTS: four quarters no commercial TTM progress and no sober partner.
Not a kill: campus approval, zoning loss, 20–40% hole with metrics intact.

## Overlay (off on day one)

S from VIX 20, SMH/SPY 18, put/call 15, WFE 15, FG 12, AAII 8, news 7, revisions 5.
Missing dropped and renormalized. Live engine coverage today ~0.57. Crypto FNG is a proxy, not CNN.

```
if kill: EXIT
elif initial fill: HOLD
elif S<=25: ACCELERATE only if laggard checklist else DCA leader
elif S<=40: DCA
elif S<=60: HOLD
elif S<=75: SLOW
elif S>=76 and 63d cluster corr>0.80: TRIM_TO_TARGET
else: SLOW
```

TRIM glue is per cluster. Optics 0.84 does not TRIM TSM. Corr of 0.80 is SLOW.

Laggard add: twins down AND two clean prints AND kill CLEAR AND size ≤10% of target. A missing box is unchecked. Incomplete dicts are not ACCELERATE.

## What is proven vs not

Proven as mechanics: $5k arithmetic; four-factor glue in 2016–26 prices; 2022 barbell vs pure chips; STAGED-style cash cuts MDD and CAGR; TRIM branch unit-tested; MODE lock.

Not proven: kill file on utilization history (series not wired); full 8-input S; lottery as 2016 hedge; public-market 25% from today; that social posts move semis.

10y barbell full CAGR ~35% includes the AI boom. STAGED analog 46/54 cash CAGR ~18% vs SPY ~15%, MDD −22% vs −34%. Insurance premium, not a forecast.

## Software honesty

Package `lattice/` + `scripts/analyze.py` fetch Yahoo, Pearson clusters, partial S. Engine SHA 9f7c51c. `python3 -m lattice.cli --session` loads cited 4 Sep prints and the session tape (news and revisions stay dropped). Empty identity CLI stays MISSED. Tests pass on cash identity, TRIM branch (never below target; weekly cap 10% of that name's target), kill edges, empty CLEAR → MISSED, SMH−SPY fraction-or-percent, complete laggard dictionaries, and `session_funding`. No broker. No Cboe/AAII/CNN equity feed in the identity CLI.

Empty OBSERVABILITY kill record is MISSED, not CLEAR. `funding_gate({})` is NO-GO. Eight dated quotes return ENGINE-READY. `session_funding` is GO only with quotes + broker-share recalc + human click. ENGINE-READY is not GO. Engine existence is not GO. Arithmetic GO is not funding GO. Operator still pastes quotes, recasts shares at the broker, and clicks.

SMH−SPY 20d: ≤−5%→20, 0→50, ≥+5%→80, linear. Fraction (0.03) or percent (3). Missing drops; never fakes 50. TRIM glue is per cluster.

## Voice (layer 2) — free tier, no ticker pumping

Posts describe constraints (power, wafers, optics), not "buy TSM." A free Facebook/YouTube/Instagram cadence cannot cause a semiconductor boom. Treat boom-talk as a rule-break risk. See VOICE.md.

## Return format

STAGED funding this session: GO or NO-GO
Defects (mechanics only)
Whether voice-as-boom is rejected (must be rejected)
One sentence the operator tapes to the monitor
