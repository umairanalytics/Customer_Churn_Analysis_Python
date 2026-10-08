#Customer churn analysis

Analyzed customer, subscription, and support data to identify churn patterns, revenue at risk, customer behavior, and retention opportunities using Python, SQLite, Pandas, NumPy, Matplotlib, and Seaborn.

Key Analysis
Calculated overall churn and retention rates
Compared churn across subscription plans
Analyzed customer revenue and tenure
Investigated support interactions and churn
Created churn-risk segments
Identified revenue at risk and retention opportunities
Key Findings
Overall churn: 28.57%
Basic plan churn: 60%
Standard plan churn: 22.22%
Premium plan churn: 14.29%
Monthly revenue at risk: 73.94K
Average monthly revenue (ARPU): 18.85
Support escalation vs. churn correlation: 0.77
Data & Feature Engineering

Created a SQLite database containing Customer, Subscription, and Support tables. Cleaned and merged the data, handled missing values and duplicates, standardized fields, and created features such as Churn Flag, Tenure Days, Complaint Count, and Churn Risk.

Business Insights
The Basic plan requires immediate retention analysis.
Escalated support cases can serve as an early churn-warning signal.
High-value and high-risk customers should receive proactive retention campaigns.
Improving support resolution and reviewing Basic-plan pricing/benefits may help reduce churn.
Tools

Python | Pandas | NumPy | SQLite | Matplotlib | Seaborn

Techniques: Data Cleaning, SQL/Joins, Feature Engineering, EDA, Correlation Analysis, Pivot Tables, Customer Segmentation, KPI Analysis.

Workflow:
Raw Data → SQLite → Cleaning → Integration → Feature Engineering → EDA → Visualization → Business Insights
