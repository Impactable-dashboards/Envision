# Envision Horizons Impact Report

Internal quarterly impact report on the locked v1.1 IA. Static HTML, no build step, no dependencies.
Ten tabs, shared nav. Cycle 1 March to 28 July 2026. Last updated 2 August 2026.

| File | Tab | Contents |
|---|---|---|
| `index.html` | Summary | Thesis, scorecard, what is working, Next 90 in brief |
| `02-results.html` | Results | Account funnel, movement inside the period, reach and warm pool growth |
| `03-performance.html` | Performance | **The only home for spend.** Windsor verified. Channel, funnel, campaign detail, verdicts |
| `04-intent.html` | Intent | ICP filtered website companies and people, ad exposure cross reference |
| `05-pipeline.html` | Pipeline | Reverse funnel, three tier attribution, hot accounts, hygiene defects |
| `06-insights.html` | Insights | Part one audience segments, part two messaging and creative |
| `07-ecosystem.html` | Ecosystem | The Board. 22 motions, six groups, EMS 47/100, next three unlocks |
| `08-next90.html` | Next 90 | 14 moves, 3 CUT / 3 SCALE / 4 BUILD / 4 TEST, budget arc, commitment log |
| `09-strategy.html` | Strategy | ICP, white space, assumptions ledger, hard coded definitions and suppression list |
| `10-sources.html` | Sources | Every file with window and limitation, what cannot be claimed, corrections log |

## Canonical figures
- **Spend, Windsor verified:** LinkedIn $14,473.64 (1 May to 28 Jul, 89d) · Google $3,932.69 (17 Jun to 28 Jul, 42d). **Windows differ and are never summed.**
- **Leads:** 18 through 31 July, 17 through 28 July. 6 resolve to a genuine ICP brand.
- **Conversions are unsettled:** Campaign Manager 5, DemandSense 0, Google 2. Never quote one without naming the source.
- **EMS 47/100, stage Reach.** Activate is gated and unscored.
- **Penetration:** 27.8% weighted. The converting pool sits at 47.6% and 7.51x frequency.
- **No revenue data exists.** Pipedrive Deal Status blank on 417 of 418 records.

## Thesis
Expand now, in this order: cut the waste, activate what is already owned, then Meta. Meta ranks third behind two zero cost unlocks, which is what makes the ask defensible.

## Data artifacts
`performance.json` and `ecosystem.json` sit alongside the room in the working directory. Performance is the ledger spine; every spend number renders once, on tab 03.

## Deploy
Push to GitHub, import in Vercel. Framework preset **Other**, no build command, no output directory.
`vercel.json` sets `cleanUrls` and a `noindex` header. **This room is internal.** It names competitors, marks the client's own company as a suppression target, questions lead quality, and logs six corrections to claims previously made. Enable Vercel password protection before sharing any link.
