# Envision Horizons Intelligence Room

Internal quarterly diagnostic room. Static HTML, no build step, no dependencies.

## Pages
| File | Contents | Window |
|---|---|---|
| `index.html` | Overview, canonical numbers, findings, defensibility table | mixed, stamped per report |
| `01-audience-segments.html` | Report 1 v2: Audience Segment Intelligence | 1 May – 28 Jul |
| `02-account-intelligence.html` | Report 2: Account Intelligence + three-tier attribution | 1 Mar – 28 Jul / leads 3 May – 30 Jul |
| `03-marketing-systems.html` | Report 3: Marketing Systems + Google console | 1 Mar – 28 Jul / Google 17 Jun – 28 Jul |
| `04-messaging-creative.html` | Report 4: Messaging and Creative Performance | 1 Mar – 28 Jul |
| `05-icp-filter.html` | Supplement: WebID ICP Filter v2 | 1 Mar – 28 Jul |
| `06-roadmap.html` | 90 Day Roadmap | from 29 Jul |

## Canonical figures
- **$24,411.17** LinkedIn spend, 1 Mar – 28 Jul, campaign grain. Other groupings return up to $24,703; hold the conservative figure.
- **17** LinkedIn-attributed leads, confirmed by Pipedrive label after removing 11 duplicate records. **6** resolve to a real brand.
- **Conversions are unsettled:** Campaign Manager 5 (1 May – 28 Jul), DemandSense 0 at campaign grain, Google 2. Reconciliation open.
- **Google:** $3,932.69 over 17 Jun – 28 Jul, 13.77% CTR, $1.51 CPC. Run rate $2,809/month.
- **No revenue data exists.** Pipedrive Deal Status is blank on 417 of 418 records.

## Rebuild history
Reports 1, 2 and 3 were rebuilt 30 July against the Google console exports, LinkedIn Campaign Manager demographics, and the Pipedrive lead export. Report 1 v2 withdraws v1's company-size and lead-qualification findings. Report 3 reverses its earlier recommendation to reduce Google spend.

## Deploy
Push to GitHub and import in Vercel. Framework preset **Other**, no build command, no output directory.
`vercel.json` sets `cleanUrls` and a `noindex` header. **This room is internal** — it names competitors, marks the client's own company as a suppression target, questions lead quality, and withdraws claims previously made to the client. Enable Vercel password protection before sharing any link.
