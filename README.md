# ics173-final-pattison
Final project github repository

##Proposal

Track A

**Question:** How many visitor days will Maui have each month in 2026, and how sure are we?

**Stakeholder:** An airline network planner using monthly visitor day volume forecasts to determine whether additional flights or flight schedule changes may be needed during specific periods in the year.

**Data sources:**
| # | Source | URL | How I get it (code or manual) |
|---|--------|-----|-------------------------------|
| 1 | DBEDT 2026 preliminary Monthly visitor statistics for Maui | https://files.hawaii.gov/dbedt/economic/tourism/monthly-islands/2026%20Maui.xlsx|
| 2 | Hawaii Open Data: Overall Hawaii visitor Numbers | https://opendata.hawaii.gov/dataset/report-card-1-overall-hawaii-visitor-numbers, pulled by code with Python|

**Plan:**
- Baseline: <#Seasonal Naive Baseline>
- Model 1: <#Linear Regression>
- Model 2: <#Gradient Boosting>
- Metric: <MAPE> because it shows how large an error is relative to expected demand. An airline network planner would want to know deviations from expected demand to prepare possible changes in flight frequencies and schedules.
****
