# Credit Performance Analysis - NorthStar Financial

In today's competitive banking landscape, financial institutions must leverage data-driven insights to maintain a competitive edge and optimize their loan portfolios. This comprehensive bank loan performance analysis project demonstrates my expertise in SQL, Power BI, financial metrics analysis, and business intelligence capabilities - skills essential for a finance and data analytics role.
This analysis is designed for NorthStar Financial, a mid-tier US commercial bank seeking to improve its loan approval processes, reduce default rates, and increase overall portfolio profitability. By implementing advanced analytics dashboards combining SQL and Power BI, this initiative has successfully transformed raw financial data into actionable intelligence that drives strategic decision-making.

Snippet of the Dashboard view: 

![Summary](https://github.com/user-attachments/assets/89a6d4f2-c669-4bd9-8684-7d779a3578fb)

# A. Problem Statement

NorthStar Financial had experienced an alarming 12% increase in loan defaults over the previous fiscal year, while competitors maintained stable default rates. The bank's executive team identified several critical problems:

- Inconsistent Loan Assessment: Different loan officers were using varying criteria to evaluate applications, leading to inconsistent risk evaluations
- Limited Portfolio Visibility: Leadership lacked comprehensive views of loan performance across different segments and regions
- Reactive Decision-Making: Without timely performance metrics, the bank primarily responded to problems after they emerged rather than proactively managing risk
- Underperforming Revenue: The loan department was not meeting its revenue targets despite increasing application volume

The bank needed a comprehensive solution that could provide timely insights into loan performance metrics while enabling both operational and strategic decision-making across organizational levels.

# B. Solution Approach

## 1. Data Integration & Architecture

The solution leveraged a multi-layered approach:

- Data Collection & Storage: Integrated data from multiple sources including the core banking system, CRM platforms, and credit bureau feeds into a centralized data warehouse
- SQL-Based Analytics Engine: Developed sophisticated SQL queries to transform raw data into meaningful performance metrics (<a href="https://github.com/GauravvBhattarai/Credit-Performance/blob/main/SQLQuery.sql">Click Here for SQL Query</a>)
- Interactive Power BI Dashboards: Created dynamic visualizations allowing users across the organization to interact with and derive insights from the data (<a href="https://github.com/GauravvBhattarai/Credit-Performance/blob/main/Dashboard.pbix">Click Here for Interactive Dashboard</a>)

## 2. Key Analysis Components
1. Summary Dashboard: Comprehensive Loan Portfolio Health Metrics
The Summary Dashboard delivers both high-level KPIs and detailed loan quality metrics, allowing executives to quickly assess portfolio health:

Application Volume & Funding Trends: Tracking total applications, funded amounts, and received payments with month-to-date (MTD) and month-over-month (MoM) comparisons to identify emerging patterns
Risk Indicators: Monitoring average interest rates and debt-to-income ratios across the portfolio and by segment
Loan Quality Assessment: Distinguishing between "good loans" (Current/Fully Paid status) and "bad loans" (Charged Off status) with percentage breakdowns and financial impact analysis
Status Grid Analysis: Evaluating metrics across different loan statuses to identify where performance issues may be emerging

This dashboard enables leadership to quickly assess overall portfolio health and identify concerning trends before they significantly impact financial performance.
2. Overview Dashboard: Multi-Dimensional Analysis
The Overview Dashboard provides deeper analytical capabilities through multiple visualization types:

Temporal Analysis: Line charts tracking applications, funding, and payments over time to identify seasonality and trends
Geographic Performance: Heat maps highlighting regional variations in loan volume and performance to guide targeted interventions and marketing
Term Distribution: Donut charts showing the breakdown of loan terms to optimize product offerings
Employment Stability Impact: Bar charts analyzing how employment tenure correlates with loan performance
Purpose Analysis: Visualizing loan performance by stated purpose to identify higher-risk categories
Home Ownership Influence: Tree maps illustrating loan metrics across ownership categories

This multi-faceted view enables middle management to identify specific segments requiring attention and opportunities for product refinement.
3. Details Dashboard: Granular Data Exploration
The Details Dashboard provides operational teams with the ability to drill down into individual loans and narrow segments:

Customizable Filters: Ability to isolate specific loan categories, time periods, or performance metrics
Detailed Record View: Access to comprehensive information on individual loans for case reviews
Comparative Analysis: Side-by-side examination of different loan segments to identify distinguishing characteristics
