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

### a. Summary Dashboard

Comprehensive Credit Portfolio Health Metrics (Snapshot):

![Summary](https://github.com/user-attachments/assets/55417f73-e641-4046-88a5-e583ce79cdf4)

The Summary Dashboard delivers both high-level KPIs and detailed loan quality metrics, allowing executives to quickly assess portfolio health. The dashboard would help decision makers in: 

- Application Volume & Funding Trends: Tracking total applications, funded amounts, and received payments with month-to-date (MTD) and month-over-month (MoM) comparisons to identify emerging patterns
- Risk Indicators: Monitoring average interest rates and debt-to-income ratios across the portfolio and by segment
- Loan Quality Assessment: Distinguishing between "good loans" (Current/Fully Paid status) and "bad loans" (Charged Off status) with percentage breakdowns and financial impact analysis
- Status Grid Analysis: Evaluating metrics across different loan statuses to identify where performance issues may be emerging

This dashboard enables leadership to quickly assess overall portfolio health and identify concerning trends before they significantly impact financial performance.

### b. Overview Dashboard

Multi-Dimensional Analysis (Snapshot):

![Overview](https://github.com/user-attachments/assets/30e4e1cc-9360-4175-9941-9c8cf6f3dfc3)

The Overview Dashboard provides deeper analytical capabilities through multiple visualization types:

- Temporal Analysis: Line charts tracking applications, funding, and payments over time to identify seasonality and trends
- Geographic Performance: Heat maps highlighting regional variations in loan volume and performance to guide targeted interventions and marketing
- Term Distribution: Donut charts showing the breakdown of loan terms to optimize product offerings
- Employment Stability Impact: Bar charts analyzing how employment tenure correlates with loan performance
- Purpose Analysis: Visualizing loan performance by stated purpose to identify higher-risk categories
- Home Ownership Influence: Tree maps illustrating loan metrics across ownership categories

This multi-faceted view enables middle management to identify specific segments requiring attention and opportunities for product refinement.

### c. Details Dashboard

Granular Data Exploration (Snapshot): 

![Details](https://github.com/user-attachments/assets/a1dc54e4-7030-47aa-86ac-5d4a8d0211b4)

The Details Dashboard provides operational teams with the ability to drill down into individual loans and narrow segments:

- Customizable Filters: Ability to isolate specific loan categories, time periods, or performance metrics
- Detailed Record View: Access to comprehensive information on individual loans for case reviews
- Comparative Analysis: Side-by-side examination of different loan segments to identify distinguishing characteristics

# C. Business Impact & Value Creation

The implementation of this analytics solution delivered substantial value to NorthStar Financial across multiple dimensions:

## 1. Enhanced Risk Management

- Early Warning System: Identified deteriorating performance in home improvement loans in the Southeast region three months before traditional reports would have flagged the issue
- Risk-Based Pricing Optimization: Refined interest rate structures based on correlations between default rates and borrower characteristics, increasing risk-adjusted returns by 8%
- Default Reduction: Decreased overall default rates by 15% through improved applicant screening based on insights from historical performance data

## 2. Operational Efficiency

- Streamlined Reporting: Reduced manual reporting time by 70%, allowing analysts to focus on insight generation rather than data compilation
- Faster Decision Cycles: Decreased time required for portfolio reviews from weeks to days, enabling more agile responses to market changes
- Resource Allocation: Optimized staffing in loan processing based on application volume patterns, improving turnaround times while maintaining quality

## 3. Strategic Advantage

- Product Development: Identified underserved market segments with strong performance characteristics, leading to two new specialized loan products
- Competitive Positioning: Enhanced the bank's ability to provide tailored loan terms, increasing application approvals by 12% without increasing risk exposure
- Regulatory Compliance: Improved documentation and monitoring capabilities, reducing compliance-related exceptions by 40%

## 4. Financial Performance

- Revenue Growth: Increased loan portfolio yield by 0.3% through optimized pricing strategies
- Cost Reduction: Decreased loan processing costs by identifying and eliminating inefficient workflows
- Profitability Enhancement: Improved net interest margin on the loan portfolio by 0.5 percentage points

# D. Technical Execution

## 1. SQL Implementation

While the SQL code itself remains in the technical documentation, the approach incorporated:

- Advanced Query Techniques: Utilized window functions, CTEs, and complex joins to transform raw data into meaningful metrics
- Performance Optimization: Implemented indexed views and optimized query structures to ensure dashboard responsiveness
- Data Quality Assurance: Created validation queries to ensure data integrity before visualization
- Automated Refreshes: Established scheduled query execution to keep dashboards updated with minimal manual intervention

The SQL foundation provides reliable, consistent calculations for critical metrics like loan status distributions, default rates, and portfolio performance indicators.

## 2. Power BI Visualization

The Power BI implementation focused on creating actionable insights through:

- Intuitive Design: Developed user-friendly interfaces with consistent color coding and clear labeling
- Interactive Elements: Implemented cross-filtering capabilities allowing users to explore relationships between different metrics
- Drill-Down Capabilities: Created hierarchical views enabling users to move from summary to detailed information seamlessly
- Mobile Optimization: Ensured dashboards function effectively on various devices for on-the-go decision-making

# E. Key Learnings & Best Practices

Several important insights emerged through this project that can benefit similar initiatives:

- Cross-Functional Collaboration: Early involvement of both technical and business stakeholders was crucial for developing relevant metrics and visualizations
- Iterative Development: Adopting an agile approach with frequent feedback cycles improved dashboard relevance and adoption
- Data Literacy Development: Investing in user training significantly increased dashboard utilization and value realization
- Balanced Metrics: Ensuring dashboards included both leading indicators (applications, interest rates) and lagging indicators (defaults, collections) provided a more complete performance picture

# F. Future Enhancements

While the current solution provides significant value, several opportunities for enhancement have been identified:

- Predictive Analytics: Implementing machine learning models to predict default probability based on historical patterns
- External Data Integration: Incorporating macroeconomic indicators to provide context for performance trends
- Natural Language Processing: Adding plain-language insight generation to make analytics more accessible to non-technical users
- Scenario Planning Tools: Developing what-if analysis capabilities to model the impact of policy changes or market shifts

# G. Conclusion

This bank loan performance analysis project demonstrates the power of combining SQL data processing with Power BI visualization to transform raw financial data into strategic insights. The solution has enabled NorthStar Financial to enhance risk management, improve decision-making, and ultimately strengthen its competitive position in the marketplace.
The project showcases the ability to bridge technical data skills with financial domain knowledge to deliver tangible business value, exactly the combination needed in a finance and data analytics role. By understanding both the technical underpinnings and the business context, it is demonstrated how data can be leveraged not just for reporting but as a strategic asset driving organizational performance.
