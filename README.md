# Employee Attrition — Summary for HR

## The Problem
1,470 employees analyzed. **16.1% attrition rate** — roughly 1 in 6 employees left. This analysis identifies who is most likely to leave next, and why.

## Top 3 Drivers of Attrition
Based on feature importance from the predictive model (Logistic Regression, selected for its ability to correctly flag the most at-risk employees):

1. **Monthly Income** — the single strongest predictor. Lower-paid employees, and employees paid below their peers at the same job level, are markedly more likely to leave.
2. **Years at Company** — attrition is heavily concentrated among newer employees. Risk drops sharply after the first few years.
3. **Job Level** — attrition is highest at the lowest job levels, tapering off toward senior roles.

**Supporting pattern (from the exploratory analysis, not the top-ranked driver but the clearest gap in the data):**
Employees working **overtime leave at 31%**, compared to **10%** for those who don't — the single widest split found in the entire dataset. Sales and Laboratory Technician roles show the highest attrition rates by job function.

## Recommendations
1. **Review pay for underpaid-for-level employees.** Employees earning below the average for their job level are a flight risk regardless of department — a targeted pay-equity review for this group is likely to have the highest return on retention spend.
2. **Address overtime load in high-risk roles**, particularly Sales and Laboratory Technician positions. Reducing sustained overtime — or adding headcount/support in these roles — directly targets the widest attrition gap identified.

## What HR Gets
A Power BI dashboard with:
- **Overview** — attrition rate, headcount, and average risk score at a glance
- **Drivers** — the factors above, broken down visually by department, role, and tenure
- **Risk** — a live, sortable list of current employees ranked by predicted attrition risk, filterable by department and role, so at-risk employees can be identified and supported before they leave
