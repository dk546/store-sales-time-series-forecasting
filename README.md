# Store Sales - Time Series Forecasting

This project forecasts sales for product families sold across Favorita stores in Ecuador using historical sales data and external signals.

## Workflow Overview

### 1. Load & Explore Data
- `train.csv`: Main time series (date, store, family, promotions, sales)
- `stores.csv`: Store metadata
- `oil.csv`: Daily oil prices
- `holidays_events.csv`: National & local events
- `transactions.csv`: Daily store traffic

### 2. Prototype Forecast
- Select a single `store_nbr` and `family`
- Build & evaluate a SARIMA model

### 3. Extend Model
- Add external regressors: promotions, holidays, oil, etc.
- Forecast across all store-family pairs

### 4. Evaluate & Visualize
- RMSE metrics
- Forecast vs. actual plots

---

##  Notes
- Dataset is ignored in version control for cleanliness
- Use `.ipynb` notebooks for interactive modeling

