# Performance Marketing Analyst Studio

An independent portfolio project by Sreejitha Nair, focused on practical performance marketing, paid media planning and marketing analytics.

## Live tool

[Open the Performance Marketing Analyst Studio](https://ai-marketing-budget-optimizer.onrender.com)

## Modules

1. **Lead Goal Planner** — work backwards from a lead target to estimate the required budget using an expected CPL, or CPC and click-to-lead conversion rate. Includes daily budget, contingency and MQL/SQL volume estimates.
2. **Campaign Analyzer** — calculate CPM, CTR, CPC, frequency, click-to-lead CVR, CPL, MQL rate, cost per MQL, MQL-to-SQL rate, cost per SQL, CPA and ROAS.
3. **Media Planner** — allocate budget across Meta, Google and LinkedIn using editable CPC and conversion-rate assumptions. Checks whether channel shares total 100%.
4. **Funnel Intelligence** — inspect conversion between impressions, clicks, landing-page views, leads, MQLs, SQLs, opportunities and wins.
5. **Scenario Simulator** — model the impact of changes to budget, CPC and conversion rate.
6. **Campaign Comparison & Reporting** — save campaign snapshots in the current browser session, export comparison data to CSV, and print/save a report as PDF.
7. **Practice datasets** — fictional B2B managed-office lead generation, e-commerce and local-service lead generation scenarios.

## Run it

Open [index.html](./index.html) in a modern browser. No installation, build step, API key or advertising account connection is required.

## Metric formulas

| Metric | Formula |
|---|---|
| CPM | Spend / impressions × 1,000 |
| CTR | Clicks / impressions × 100 |
| CPC | Spend / clicks |
| Frequency | Impressions / reach |
| Click-to-lead CVR | Leads / clicks × 100 |
| CPL | Spend / leads |
| MQL rate | MQLs / leads × 100 |
| Cost per MQL | Spend / MQLs |
| MQL-to-SQL rate | SQLs / MQLs × 100 |
| Cost per SQL | Spend / SQLs |
| CPA | Spend / conversions |
| ROAS | Attributed revenue / spend |

## Lead budget planning

- Using CPL: **Estimated base budget = target leads × expected CPL**
- Using funnel assumptions: **Required clicks = target leads / click-to-lead CVR**
- **Estimated base budget = required clicks × expected CPC**
- **Planned budget = base budget × (1 + contingency buffer)**

These are planning estimates, not guarantees. Use historical account data or clearly labelled assumptions. Real results vary with auction conditions, audience, creative, landing-page experience, sales follow-up and attribution.

## Important notes

This is a portfolio learning tool, not a live advertising-platform integration. It uses user-entered data and does not transmit it to an ad platform. Sample datasets are fictional. Forecasts and diagnostic thresholds are illustrative, not universal benchmarks. Use consistent reporting dates, attribution windows, cohorts and conversion definitions when comparing platforms. Campaign comparison data is held in the current browser session and is not a cloud database.

**Focus areas:** Performance Marketing · Paid Media · Media Planning · Campaign Measurement · Marketing Analytics
