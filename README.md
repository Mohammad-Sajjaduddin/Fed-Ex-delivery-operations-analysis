# 📦 FedEx Delivery Operations Analysis using Exploratory Data Analysis (EDA)

## Overview

This project performs Exploratory Data Analysis (EDA) on a synthetic FedEx Delivery Dataset to uncover insights into shipment operations, delivery performance, customer segments, transportation modes, and shipping costs.

The analysis uses Python and data visualization techniques to identify operational trends and provide business recommendations for improving logistics efficiency.

---

## Problem Statement

FedEx manages thousands of shipments across different locations and transportation modes. Understanding delivery performance, shipment costs, and customer demand is essential for improving logistics operations. This project analyzes shipment data to identify patterns, optimize transportation strategies, and support data-driven business decisions.

---

## Business Objectives

- Analyze shipment trends.
- Evaluate delivery performance.
- Understand customer segment distribution.
- Compare shipment modes.
- Analyze shipping costs.
- Study delivery time patterns.
- Discover relationships among operational variables.
- Provide business recommendations.

---

## Dataset Information

The synthetic dataset contains shipment information such as:

- Shipment ID
- Origin
- Destination
- Pickup Date
- Delivery Date
- Delivery Status
- Shipment Mode
- Distance (KM)
- Weight (KG)
- Shipping Cost (USD)
- Customer Segment
- Delay Reason

An additional feature (**Delivery_Time_Days**) was created during feature engineering.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Squarify
- Jupyter Notebook

---

## Exploratory Data Analysis

The project includes:

- Data Cleaning
- Missing Value Analysis
- Feature Engineering
- Shipment Mode Analysis
- Customer Segment Analysis
- Delivery Status Analysis
- Monthly Shipment Trends
- Cost Distribution
- Delivery Time Analysis
- Correlation Heatmap
- Pair Plot Analysis

---

## Key Insights

- Ground is the most frequently used shipment mode.
- Business customers generate the highest shipment volume.
- Most shipments are successfully delivered.
- Delivery times are generally between 1–3 days.
- Shipping cost increases with shipment weight and travel distance.
- Delivery performance remains consistent across origin cities.

---

## Business Recommendations

- Improve monitoring of delayed shipments.
- Optimize transportation mode selection.
- Reduce logistics costs through better route planning.
- Strengthen relationships with business customers.
- Use shipment trends for demand forecasting.

---

## Project Structure

```
fedex-delivery-operations-analysis
│
├── data/
├── requirements.txt
├── README.md
└── LICENSE
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/fedex-delivery-operations-analysis.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```
notebooks/FedEx_Delivery_EDA.ipynb
```

---

## Future Improvements

- Build an interactive Power BI dashboard.
- Predict delivery delays using Machine Learning.
- Forecast shipment demand.
- Develop route optimization models.

---

## Author

Mohammad Sajjaduddin

GitHub: https://github.com/Mohammad-Sajjaduddin


---

## License

This project is licensed under the MIT License.
