1️⃣ Project Title
# Demand Volatility Index (DVI): 
A Predictive Retail Intelligence System for India

2️⃣ Problem Statement
Retail businesses in India often face unexpected demand fluctuations driven by inflation, fuel prices, weather changes, and festival cycles. These demand shocks lead to inventory mismanagement, revenue loss, and operational inefficiencies.
This project aims to develop a Demand Volatility Index (DVI) that predicts and quantifies demand instability using multi-source economic and retail data.

3️⃣ Business Objective
Predict category-level demand fluctuations
Identify macroeconomic impact on consumer purchasing
Quantify volatility risk
Enable strategic inventory planning

4️⃣ Key KPIs
Forecast RMSE / MAPE
Demand Variance
Inflation Sensitivity Score
Festival Surge Multiplier
Regional Stability Score

5️⃣ System Overview
Briefly describe:
The system integrates retail sales data with macroeconomic indicators such as CPI, fuel prices, weather patterns, and festival events to forecast demand trends and compute a composite Demand Volatility Index (DVI).

Out of ~1.05M order item records, only ~71K had valid foreign key matches with the Orders table.
For analytical correctness, the project enforces strict referential integrity and excludes orphan records.

### Shock Detection Logic
A conservative 2σ threshold was used.  
No extreme demand shocks were detected in the observed period.  
Lower σ thresholds were tested for sensitivity analysis.

