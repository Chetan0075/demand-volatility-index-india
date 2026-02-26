📊 Dataset List & Sources

1️⃣ Retail Sales Data (Core Dataset)
Purpose:
Baseline demand at category & time level.
What it provides:
Monthly sales
Product categories
Regions / cities
Source Options:
Kaggle – Indian Retail / Superstore / E-commerce datasets
Synthetic but realistic retail datasets (acceptable for modeling)
Storage:
/data/raw/retail_sales.csv



2️⃣ CPI / Inflation Data
Purpose:
Measure purchasing power impact on demand.
What it provides:
Monthly CPI index
Inflation trends
Source:
Reserve Bank of India
Ministry of Statistics (MOSPI)
Storage:
/data/raw/cpi_data.csv



3️⃣ Fuel Price Data
Purpose:
Capture logistics cost & consumer sentiment shock.
What it provides:
Monthly petrol & diesel prices
Source:
Government fuel price historical data
Open fuel price datasets
Storage:
/data/raw/fuel_prices.csv



4️⃣ Weather Data
Purpose:
Quantify climate-driven demand disruptions.
What it provides:
Temperature
Rainfall
Extreme weather indicators
Source Options:
IMD (Indian Meteorological Department – historical summaries)
Kaggle weather datasets (India-focused)
Derived Feature:
Weather Severity Index
Storage:
/data/raw/weather_data.csv



5️⃣ Festival Calendar Data
Purpose:
Model seasonal demand distortion.
What it provides:
Festival name
Month
Region relevance (if available)
Examples:
Diwali
Holi
Eid
Navratri
Christmas
Source:
Storage:
/data/raw/festival_calendar.csv



6️⃣ Google Trends Data (Optional but Powerful)
Purpose:
Capture early consumer interest signals.
What it provides:
Search interest over time
Category-level intent proxy
Source:
Google Trends export
Storage:
/data/raw/google_trends.csv



🧠 Data Coverage Summary
Dataset	Type	Frequency
Retail Sales	Micro	Monthly
CPI	Macro	Monthly
Fuel Prices	Macro	Monthly
Weather	External	Monthly
Festival Calendar	Event	Monthly
Google Trends	Behavioral	Monthly
All datasets aligned to monthly granularity.
