# 🚇 Ridership Analytics — Chicago vs Philadelphia

## 📌 Project Overview

This project analyzes and compares public transportation ridership in **Chicago (CTA)** and **Philadelphia (SEPTA)** using historical mobility data.

The objective is to build a **data analytics pipeline** and an **interactive Power BI dashboard** to understand urban mobility patterns, network structure, and differences in transportation usage between the two cities.

The study focuses on two complementary levels of analysis:

* **Route level** → operational network performance
* **Mode level (Bus vs Rail)** → strategic mobility behavior

---

## 🎯 Main Objectives

* Clean and harmonize heterogeneous transit datasets
* Build a dimensional **star schema model**
* Compute advanced KPIs using DAX
* Perform statistical exploration with Python
* Design an interactive Power BI dashboard for decision support

---

## 📊 Key KPIs

The dashboard includes several performance indicators:

* Monthly ridership growth (MoM)
* Route network volatility (ridership dispersion)
* City performance gap (Chicago vs Philadelphia)
* Mode share (Bus vs Rail dependence)
* Comparative historical trends

---

## 🧠 Analytical Approach

The project combines:

* Data Engineering (ETL & preprocessing)
* Business Intelligence (Power BI modeling)
* Statistical Analysis (Python notebooks)
* Urban Mobility Analytics interpretation

---

## 🗂 Repository Structure

```
├── Chicago-Philadelphie/
│   └── (processed datasets used in Power BI)
│
├── Notebooks/
│   ├── data_cleaning.ipynb        # Data preparation and transformation
│   ├── data_integration.ipynb     # Merging Chicago & Philadelphia datasets
│   └── exploratory_analysis.ipynb # Statistical exploration
│
├── output/
│   ├── comparative_mode_ridership_clean.csv
│   ├── comparative_route_ridership_clean.csv
│   └── final datasets exported for Power BI
│
└── README.md
```

---

## ⚙️ Data Processing Workflow

1. Raw datasets collected from CTA and SEPTA sources
2. Cleaning and harmonization using Python (Pandas)
3. Feature engineering (date, city, route, mode)
4. Export of structured datasets (CSV)
5. Import into Power BI
6. Star schema modeling
7. KPI computation with DAX
8. Dashboard visualization

---

## 📈 Power BI Dashboard

The dashboard is organized into **two analytical pages**:

### 1️⃣ Route Comparison (Operational Analysis)

* Ridership by route
* Network stability (volatility)
* Performance gap between cities
* Seasonal patterns

### 2️⃣ Mode Comparison (Strategic Analysis)

* Bus vs Rail usage
* Monthly growth trends
* City mobility behavior
* Mode share indicators

---

## 🧪 Statistical Analysis (Python)

Performed using Jupyter notebooks:

* Descriptive statistics
* Distribution analysis
* Correlation exploration
* Comparative trend analysis

Libraries used:

* pandas
* numpy
* matplotlib
* seaborn
* scipy

---

## 🛠 Technologies Used

* **Python** — Data preparation & statistics
* **Pandas / NumPy / SciPy**
* **Jupyter Notebook**
* **Power BI** — Data modeling & dashboarding
* **DAX** — KPI calculations

---

## 📊 Expected Insights

This project helps to:

* Identify structural differences between transport networks
* Measure network efficiency and stability
* Detect ridership patterns
* Understand urban mobility behavior
* Support transport planning decisions

---

## 👩‍💻 Author

**Leila Mourid**

---

## 📎 Notes

The datasets are used for educational and analytical purposes only.
No real-time operational decisions should be made solely from this dashboard.

