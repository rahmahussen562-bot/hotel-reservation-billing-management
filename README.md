# 🏨 Hotel Reservation & Billing Management

<div align="center">

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![SQL Server](https://img.shields.io/badge/SQL%20Server-2019+-CC2927?logo=microsoftsqlserver&logoColor=white)
![Python](https://img.shields.io/badge/Python-3.8+-3776AB?logo=python&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?logo=powerbi&logoColor=black)
![Orange](https://img.shields.io/badge/Orange-Data%20Mining-F9A825?logoColor=white)

**End-to-End Data Pipeline for Hotel Operations**

A team capstone project covering the full analytics lifecycle: normalized database design, SQL-based analytical queries, exploratory data analysis, machine-learning modeling, and executive Power BI dashboards.

</div>

---

## 📋 Overview

This project demonstrates a comprehensive approach to hotel property management through data:

| Phase | Description | Tools |
|-------|-------------|-------|
| **Database Design** | Normalized (3NF) relational schema with 12+ entities modeling the full hotel lifecycle | SQL Server, T-SQL |
| **Analytical Queries** | 10+ solutions using views, recursive CTEs, and window functions | T-SQL |
| **Exploratory Data Analysis** | Profiling distributions, correlations, and data quality issues | Python, pandas, Matplotlib, Seaborn |
| **Machine Learning** | Benchmarked 8 models to predict reservation outcomes (best: Random Forest @ 81%) | Orange Data Mining |
| **Business Intelligence** | Executive KPI dashboards for occupancy, revenue, payment mix, and housekeeping | Power BI |

---

## 🗄️ Database Schema

The normalized relational database covers:

- **Guest Management** — guest profiles, loyalty tiers, contact information
- **Room Inventory** — room types, rates, availability, amenities
- **Reservations** — booking lifecycle from inquiry to checkout
- **Invoicing & Payments** — billing, payment methods, invoice aging
- **Services** — ancillary revenue streams (spa, dining, transport)
- **Housekeeping** — room status, cleaning schedules, staff assignments

All entities enforce referential integrity through primary/foreign keys and CHECK constraints.

---

## 📊 Key Analytical Solutions

| # | Business Question | SQL Technique |
|---|------------------|---------------|
| 1 | Guest lifetime value ranking | Window functions, CTEs |
| 2 | Real-time room availability | Recursive CTEs, joins |
| 3 | Daily occupancy rate | Aggregation, date functions |
| 4 | Invoice aging analysis | CASE expressions, DATEDIFF |
| 5 | Staff performance metrics | Window functions, ranking |
| 6 | Cancellation pattern analysis | GROUP BY, conditional aggregation |
| 7 | Revenue by channel/source | PIVOT, cross-tabulation |
| 8 | Seasonal demand forecasting | Moving averages, CTEs |

---

## 🤖 Machine Learning Results

8 models benchmarked for reservation outcome prediction:

| Model | Accuracy | Notes |
|-------|----------|-------|
| **Random Forest** | **81%** | Best overall performance with strong cancellation recall |
| Gradient Boosting | 79% | Competitive, higher precision on confirmations |
| Logistic Regression | 74% | Baseline linear model |
| SVM | 76% | Good with feature scaling |
| Decision Tree | 73% | Interpretable but overfits |
| KNN | 72% | Distance-based, sensitive to scaling |
| Naive Bayes | 70% | Fast, probabilistic baseline |
| Neural Network | 78% | Deep model, longer training |

---

## 📈 Power BI Dashboard

Executive KPIs tracked:

- 🛏️ **Occupancy Rate** — daily, weekly, monthly trends
- 💰 **Revenue Analysis** — by room type, channel, season
- 💳 **Payment Mix** — cash vs. card vs. corporate billing
- 🧹 **Housekeeping Status** — room readiness, turnaround time
- ❌ **Cancellation Metrics** — rate trends, top reasons, revenue impact

---

## 🛠️ Technology Stack

- **Database**: SQL Server 2019+ (T-SQL)
- **Analysis**: Python 3.8+ (pandas, Matplotlib, Seaborn)
- **Data Mining**: Orange Data Mining
- **BI**: Microsoft Power BI
- **Version Control**: Git / GitHub

---

## 📁 Project Structure

```
├── SQL scripts          # Database creation, data insertion, analytical queries
├── EDA notebooks        # Python exploratory data analysis
├── ML models            # Orange workflow files and results
├── Power BI reports     # .pbix dashboard files
└── Documentation        # Project reports and presentations
```

---

## 🚀 Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/rahmahussen562-bot/hotel-reservation-billing-management.git
   ```

2. **Set up the database** — Execute the SQL scripts in order:
   - Database creation → Table creation → Data insertion → Analytical views

3. **Run the analysis** — Open Jupyter notebooks for EDA

4. **View dashboards** — Open the `.pbix` file in Power BI Desktop

---

## 👩‍💻 Author

**Rahma Ahmed Hussein**

- 📧 [rahmahussen562@gmail.com](mailto:rahmahussen562@gmail.com)
- 💼 [LinkedIn](https://linkedin.com/in/rahma-husseiin)
- 🐙 [GitHub](https://github.com/rahmahussen562-bot)

---

## 📄 License

This project is licensed under the MIT License — see [LICENSE](LICENSE) for details.
