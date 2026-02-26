Modeling & DVI Engine

Purpose: Predict demand and compute volatility risk.

Subcomponents:

🔹 Forecasting Module

Time-series model (ARIMA / Prophet)

Forecast category-level demand

Output: Forecast + error metrics

🔹 Clustering Module

K-Means for regional segmentation

Identify stable vs sensitive regions

🔹 Shock Detection Module

Z-score / Isolation Forest

Detect abnormal demand spikes or drops

🔹 DVI Calculation Engine

Combine:

Demand Variance

Forecast Error

Inflation Sensitivity

Festival Surge

External Shock Score

Produce DVI score (0–100
