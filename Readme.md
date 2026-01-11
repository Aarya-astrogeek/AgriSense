# 🌾 Agri-Price Intelligence Dashboard

##  Project Overview

This project builds an **end-to-end agricultural analytics system** that forecasts crop prices and translates them into **actionable business insights**.
The final deliverable is an **interactive dashboard** that visualizes:

* Crop price forecasts
*  Margin and profitability opportunities
* State-wise performance indicators
*  Risk zones and procurement signals

The system is designed to be **modular and scalable**, allowing easy expansion to new crops, markets, or regions without redesigning the dashboard.

---

##  Objectives

* Forecast future agricultural commodity prices across states and markets
* Identify high-margin crops and regions
* Support procurement and pricing decisions using risk and signal indicators
* Provide a business-ready analytics dashboard for stakeholders

---

##  Data & Outputs

The dashboard is powered by multiple analytical outputs, each stored as a CSV file:

| File Name                           | Description                                           |
| ----------------------------------- | ----------------------------------------------------- |
| `agri_price_forecast_all_crops.csv` | Daily price forecasts by state, commodity, and market |
| `latest_margins.csv`                | Current margin estimates for each crop                |
| `margin_forecasts.csv`              | Future margin projections                             |
| `state_performance_index.csv`       | Composite performance score for each state            |
| `risk_zones.csv`                    | Risk classification by state and commodity            |
| `procurement_signals.csv`           | Buy / Hold / Avoid signals                            |
| `regional_market_balancing.csv`     | Supply-demand gap indicators                          |
| `all_buckets_accuracy.csv`          | Forecast model accuracy metrics                       |

---

## Dashboard Features

The interactive dashboard includes:

### Price Forecast Analysis

* Time-series visualization of forecasted prices
* Commodity-wise and market-wise comparison
* Date-based trend analysis

###  Margin & Profitability Insights

* Crop-wise margin comparison
* Identification of high-profit opportunities
* Future margin trend visualization

###  State-wise Performance Indicators

* Geographic map of state performance indices
* Comparative regional analysis

### Risk & Procurement Intelligence

* Risk zone classification
* Procurement signals for decision support
* Actionable tables for stakeholders

###  Interactivity

* Filters for **State**, **Commodity**, and **Market**
* Cross-filtering across all visuals
* Dynamic updates based on user selection

---

## Modular & Scalable Framework

The analytics framework is designed to scale effortlessly:

* New crops → add rows to CSV
* New states or regions → auto-reflected in visuals
* No hard-coded logic or static assumptions
* Same dashboard structure supports future expansion

This makes the system suitable for **large-scale agri-market intelligence platforms**.

---
##  Dashboard Access

The interactive Power BI dashboard can be accessed here:  
👉 [Live Power BI Dashboard](https://iitgoffice-my.sharepoint.com/:u:/g/personal/k_yatharth_iitg_ac_in/IQCwhaN-UP7kQpkTwa3bhvUMAZMM2_mdcnPmDZMXgwN2wVg?e=xEbIlN

Below are selected previews from the dashboard.

##  Tools & Technologies

* **Python** – Data preprocessing, forecasting, and analytics
* **CSV-based data pipelines** – Modular output storage
* ** Power BI** – Interactive dashboard development

---

##  How to Use

1. Open the dashboard tool (Tableau or Power BI)
2. Load all CSV files provided in the `/data` directory
3. Ensure relationships are based on:

   * `state`
   * `commodity`
   * `market`
4. Use filters to explore insights interactively

---

##  Business Value

This dashboard enables:

* Better procurement planning
* Smarter pricing decisions
* Regional opportunity identification
* Risk-aware agri-business strategy

---

##  Future Enhancements

* Integration with real-time market feeds
* Make the model segregate the cops into buckets to apply respective models. 
* Automated forecast updates
* Role-based dashboards for farmers, traders, and policymakers.

Author

**Aarya Shisode, Yatharth Kabra and Ankit Sinha**
 
 Consulting and Analytics Club Project

---

##  License

This project is for academic and demonstration purposes.
