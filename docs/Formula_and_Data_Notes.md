# Formula and Data Notes

## Data source

The operational dataset is simulated for portfolio practice because internal loyalty campaign data is not publicly available. The values were designed around a logical campaign funnel:

Impressions → Clicks → New Members → Partner Transactions → Eligible Spend → Incremental Revenue.

All operational results should be treated as illustrative.

## Excel features used

- SUM
- SUMIF
- IFERROR
- Basic percentage calculations
- Structured tables
- Conditional formatting
- Weekly summaries
- Column and line charts
- KPI cards

## Key formulas

CTR: `=IFERROR(Clicks/Impressions,0)`

Conversion Rate: `=IFERROR(New_Members/Clicks,0)`

Cost per Acquisition: `=IFERROR(Campaign_Cost/New_Members,0)`

ROI: `=IFERROR((Incremental_Revenue-Campaign_Cost)/Campaign_Cost,0)`

Achievement: `=IFERROR(Actual_New_Members/Member_Target,0)`

Partner reconciliation: `=SUMIF(Partner_Range,Partner_Name,Metric_Range)`

## Important limitation

In a real campaign, revenue attribution and ROI definitions must be agreed with finance and the partner. The revenue field in this portfolio is illustrative and should not be interpreted as audited company financial performance.