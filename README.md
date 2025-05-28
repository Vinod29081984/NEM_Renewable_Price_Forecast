# NEM_Renewable_Price_Forecast
Analysis and forecasting of electricity prices based on renewable energy generation in QLD's National Electricity Market (NEM):
This project explores how increasing renewable energy generation (such as solar and wind) influences electricity pricing trends in Queensland’s National Electricity Market (NEM). The study focuses on forecasting electricity prices using statistical and deep learning models, supported by scenario simulations.

##  Project Objective

**Research Question:**  
*How does increasing renewable energy generation influence electricity pricing trends in Queensland’s National Electricity Market?*

The goal is to:
- Analyze historical electricity and renewable generation data
- Develop accurate forecasting models for electricity prices
- Simulate different renewable energy scenarios to assess pricing impacts

##  Methods Used

- Data Collection & Cleaning
- Exploratory Data Analysis (EDA)
- Forecasting Models:
  - SARIMA
  - SARIMAX (with exogenous renewable input)
  - LSTM (Long Short-Term Memory Neural Network)
- Scenario Simulations:
  - +20% and –20% renewable generation
  - Peak-hour generation and storage-redeployment strategy

## Folder Structure
NEM_Renewable_Price_Forecast/
├── notebooks/ # Jupyter notebooks for full workflow
│ ├── 01_data_download_and_preparation.ipynb
│ ├── 02_exploratory_data_analysis.ipynb
│ ├── 03_modelling_and_forecasting.ipynb
│ └── 04_scenario_analysis.ipynb
│
├── data/ # Cleaned datasets used in the project
│ ├── merged_rrp_renewables_qld_5min.csv
│ ├── renewable_generation_hourly_qld.csv
│ ├── rrp_hourly.csv
│ ├── rrp_qld_daily.csv
│ └── rrp_renewables_qld_daily.csv

## 📈 Key Findings

- A weak negative correlation was found between renewable output and electricity prices.
- SARIMAX slightly outperformed SARIMA by incorporating renewable data.
- LSTM provided the lowest forecasting error but was less interpretable.
- Scenario simulations showed clear pricing sensitivity to renewable variation.

## 📎 Report & Documentation

The full project report includes:
- Introduction & literature review
- Approach & methodology
- Model evaluations & plots
- Scenario-based insights
- Reflections and future recommendations

Refer to the project report for full details.

---

##  Author

Vinod Ganeshan – Master of Data Analytics (QUT)  
