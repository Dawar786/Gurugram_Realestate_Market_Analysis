# Gurugram Real Estate Market Analysis 🏠📊

An end-to-end exploratory data analysis (EDA) of the Gurugram real estate market using Python. This project analyzes property listings across Gurgaon to uncover pricing trends, structural premiums, and geographic hotspots by utilizing **pandas**, **matplotlib**, and **seaborn**.

---

## 🚀 Project Overview
The Gurugram real estate market is one of India's most dynamic and high-growth sectors. This repository contains an analytical pipeline designed to clean raw housing data, perform statistical queries, and generate visual representations that answer **10 critical business questions** for real estate investors, builders, and homebuyers.

---

## 🧠 Business Questions Answered

Our analysis delivers clear, data-driven answers to the following 10 market questions:

1. **Which is the costliest flat in the dataset?** – Identifies the record-holding luxury listing, its location, and specifications.
2. **Which locality has the highest average price?** – Maps out the most exclusive and premium neighborhoods in Gurugram.
3. **Which locality has the highest rate per square foot?** – Uncovers where land and vertical space are valued at the highest premium.
4. **Do ready-to-move properties cost more than under-construction properties?** – Evaluates the possession-status price premium.
5. **Do RERA-approved properties command a price premium?** – Analyzes the financial impact of regulatory compliance on property valuations.
6. **How does area (sqft) impact property price?** – Examines the correlation and regression curve between property size and overall cost.
7. **Which BHK configuration is the most expensive on average?** – Breaks down average pricing trends across 1, 2, 3, 4, and 5+ BHK layouts.
8. **Which property type (Apartment, Floor, Plot) is the costliest?** – Compares structural asset classes to see which commands the highest market value.
9. **Do certain builders or companies consistently price higher?** – Evaluates brand equity by grouping average pricing by developer.
10. **Are larger homes always more expensive per square foot?** – Investigates if a price-per-sqft premium scales up with property size or if bulk-size discounts apply.

---

## 🛠️ Tech Stack & Libraries

* **Python 3.x** – Core programming language.
* **pandas** – Used for data ingestion, missing value imputation, outlier filtering, and aggressive grouping/aggregations.
* **matplotlib** – Used for foundational plot structuring, figure layouts, and canvas styling.
* **seaborn** – Used for advanced statistical visualizations, including box plots, scatter regression plots, and distribution lines.
* **Colab Notebook** – For interactive development and clean, inline visual output.

---

## 📦 Repository Structure

```text
├── data/
│   └── gurugram_realestate_dataset.csv  # Raw/Cleaned property listings data
├── notebooks/
│   └── gurugram_analysis.ipynb          # Step-by-step EDA and visualizations
├── README.md                            # Project documentation
└── requirements.txt                     # List of Python dependencies
```

---


## 📈 Key Visualization Samples Inside the Notebook
* **Scatter & Regression Plots:** Used to show the exact relationship between property area (sqft) and price.

