# 💳 Bank Fraud Detection Dashboard
### Built with Power BI | Author: Yuvarani Dharmasivam

---

## 📊 Project Overview

This project analyses **284,807 bank transactions** to identify fraud patterns and detect anomalies using an interactive Power BI dashboard. The dataset contains real anonymized credit card transactions, of which only **492 (0.17%)** are fraudulent — reflecting real-world fraud data imbalance.

The dashboard helps financial analysts and banking institutions:
- Identify fraud patterns quickly
- Compare fraudulent vs legitimate transaction amounts
- Monitor transaction distributions
- Filter and explore data interactively

---

## 🖥️ Dashboard Preview

### Page 1 - Transaction Overview
![Overview](screenshots/overview.png)

### Page 2 - Fraud Analysis
![Fraud Analysis](screenshots/fraud_analysis.png)

---

## 🔍 Key Insights

## 🔎 Analytical Insights

1. **Fraud detection is challenging due to severe class imbalance** - Only 0.17% of all transactions are fraudulent, highlighting the difficulty of identifying fraud accurately without generating excessive false positives.

2. **Fraudulent transactions generally involve higher transaction values** - Analysis shows that fraudulent transactions tend to have larger average amounts compared to legitimate transactions, making transaction value a critical indicator for anomaly detection.

3. **Transaction activity is concentrated in lower-value ranges** - Most legitimate transactions occur within lower transaction bands, while high-value outliers present a greater likelihood of suspicious activity.

4. **Low fraud frequency requires anomaly-focused monitoring** - Since fraudulent activity represents a very small proportion of total transactions, traditional volume-based monitoring is less effective than anomaly-based detection approaches.

5. **Interactive analysis improves fraud investigation efficiency** - The dashboard enables analysts to filter and isolate suspicious patterns quickly, supporting faster investigation and decision-making.

---

## 💡 Business Recommendations

| Recommendation | Description |
|----------------|-------------|
| 🚨 **Real-Time Fraud Alerts** | Implement automated alerts for unusually high-value transactions to enable immediate review and reduce potential financial losses |
| 🎯 **Risk-Based Transaction Monitoring** | Apply stricter fraud detection thresholds for high-value transaction categories where fraudulent activity is more likely |
| 🤖 **Anomaly Detection Models** | Use transaction value deviations and behavioural anomalies as key features for fraud prediction systems |
| 📈 **Continuous Fraud Trend Monitoring** | Monitor transaction trends regularly through dashboard reporting to detect emerging fraud patterns early |
| 🔍 **Focused Analyst Investigation** | Prioritise investigation efforts toward transaction segments with elevated fraud risk indicators |

---

## 📁 Project Structure

```
Bank-Fraud-Detection-PowerBI/
├── README.md
├── dashboard.pdf
└── screenshots/
    ├── overview.png
    └── fraud_analysis.png
```

---

## 🛠️ Tools Used

| Tool | Purpose |
|------|---------|
| **Power BI** | Dashboard creation and visualisation |
| **Microsoft Excel/CSV** | Data preparation |
| **GitHub** | Portfolio hosting |

---

## 📂 Dataset

- **Source:** [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- **Rows:** 284,807 transactions
- **Features:** Time, Amount, Class (0 = Legitimate, 1 = Fraud)
- **Fraud Rate:** 0.17%

---

## 📊 Dashboard Features

**Page 1 - Transaction Overview:**
- Total Transactions KPI Card
- Total Fraud Cases KPI Card
- Total Amount KPI Card
- Average Transaction Amount KPI Card
- Fraud vs Legitimate Pie Chart
- Average Amount by Transaction Type
- Transaction Amount Distribution
- Interactive Slicer Filter

**Page 2 - Fraud Analysis:**
- Top Fraud Transactions Table
- Highest Transaction Amount Card
- Fraud Pattern Over Time Chart
- Interactive Slicer Filter

---

## 📄 View Dashboard

📥 [Download Full Dashboard PDF](dashboard.pdf)

---

## 👩‍💻 Author

**Yuvarani Dharmasivam**
- GitHub: [@YuvaraniD](https://github.com/YuvaraniD)

---

## 📌 How to Use

1. Clone this repository
2. Open `dashboard.pdf` to view the full dashboard
3. Download the dataset from Kaggle link above

---


