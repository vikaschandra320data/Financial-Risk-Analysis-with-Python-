# Financial-Risk-Analysis-with-Python-

# Overview
•	Developed a financial risk analysis system in Python to analyze transactional data and identify customer risk patterns.
•	Performed data cleaning, segmentation, hypothesis testing, and anomaly detection to extract vital insights into financial behaviors.
•	Created visualizations to represent transaction trends, account performance, overdrafts, and balance volatility.

# Tools Used
Python, Numbpy, Pandas, Matplotlib, Data visualization, Hypothesis test, Seaborn, Scipy

# Key Insights
Transaction Behavior
Customer transactions show clear variation between credits (inflows) and debits (outflows) across time.
Monthly trends highlight periods of higher spending and periods of stronger inflows, indicating non-uniform financial behavior.
🔹 Customer Activity Patterns
Customers are unevenly distributed across activity levels.
A smaller segment of accounts contributes to high transaction frequency, while the majority remain moderately or low active.
This suggests engagement is concentrated among a subset of users.
🔹 Balance vs Activity Relationship
High transaction frequency does not necessarily correspond to high account balances.
Some customers exhibit high activity but low balances, indicating cash-flow-driven behavior rather than savings-oriented behavior.
🔹 Customer Segmentation
Customers can be meaningfully segmented into:
High balance accounts → financially stable and high value
Medium/low balance accounts → moderate to vulnerable
Negative balance accounts → financially at risk
This highlights the need for segment-specific strategies.
🔹 Dormancy Patterns
A portion of accounts shows prolonged inactivity, indicating low engagement or potential churn risk.
These accounts represent opportunities for customer reactivation strategies.
🔹 Financial Risk Indicators
A subset of accounts exhibits high-risk characteristics, including:
High balance volatility
Frequent large withdrawals
Anomalous transaction patterns
Risk is not evenly distributed, but concentrated in specific accounts.
🔹 Anomaly Detection
Transaction analysis identified outliers using statistical thresholds (IQR method).
These anomalies may indicate:
Irregular financial behavior
Potential fraud
Exceptional transactions
🔹 Statistical Insight
A hypothesis test was conducted to evaluate the relationship between transaction frequency and average balance.
The analysis provides a data-driven validation (or rejection) of whether highly active accounts maintain higher balances.

# Conclusion
The project demonstrates how financial transaction data can be leveraged to gain 
insights into customer behaviour and risk. The findings support strategic recommendations 
such as rewarding high-value customers, re-engaging dormant accounts, and proactively 
monitoring risky transaction patterns. This end-to-end analysis highlights the practical 
application of data analytics in financial decision-making.
