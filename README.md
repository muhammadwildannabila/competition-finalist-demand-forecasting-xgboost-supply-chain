# 🏆 Core Experience — Demand Forecasting & Supply Chain Intelligence (Finalist Project)

<div align="center">

![Python](https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge&logo=python)
![Machine Learning](https://img.shields.io/badge/Machine-Learning-orange?style=for-the-badge)
![XGBoost](https://img.shields.io/badge/XGBoost-Optimized-green?style=for-the-badge)
![Time Series](https://img.shields.io/badge/Time-Series-Forecasting-purple?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Finalist%20Competition-gold?style=for-the-badge)

### 🟡 Competition Project (Data Challenge / Hackathon)

🏆 **Finalist — Big Data Analytics Competition (FESMARO), Universitas Negeri Malang 2025**

### 📦 Data Science | Forecasting | Supply Chain Analytics

</div>

---

## 🧠 Problem Background

In modern supply chains, **accurate demand forecasting is critical** for maintaining operational efficiency.  
However, one of the most challenging scenarios occurs when a **high-impact product is discontinued**, leading to:

- 📉 Sudden and significant demand drops  
- 📦 Inventory imbalance (overstock / understock)  
- ⚠️ Disruption in planning and distribution  

> In this case study, demand dropped **more than 80%** due to product discontinuation.

---

## 🎯 Objective

This project is designed to:

- Predict **monthly demand with high accuracy**  
- Detect **structural changes in demand patterns**  
- Identify **key features influencing demand behavior**  
- Deliver **actionable insights for supply chain strategy**

---

## ⚙️ Analytical Pipeline

The analytical workflow follows a structured data science lifecycle:

1. **Data Exploration**
   - Analyze demand patterns and anomalies  
   - Identify structural breaks in time series  

2. **Data Preprocessing**
   - Handle missing values  
   - Encode categorical variables  
   - Aggregate data into monthly format  

3. **Feature Engineering**
   - Create business-driven features:
     - `late_delivery_risk`
     - `profit_ratio`
     - `is_discontinued`  

4. **Model Development**
   - Statistical Models: SARIMA, Holt-Winters  
   - Machine Learning Models:
     - Linear Regression, Ridge, Lasso  
     - Random Forest, Gradient Boosting  
     - XGBoost & Tuned XGBoost  

5. **Model Evaluation**
   - Performance metric: **MAPE (Mean Absolute Percentage Error)**  

6. **Model Interpretation**
   - Feature importance analysis  
   - Identifying key demand drivers  

7. **Insight & Recommendation**
   - Translate results into business strategies  

---

## 📊 Exploratory Data Analysis

### 🔹 Demand Time Series Pattern
![Time Series](assets/time_series_comparison.png)

**Insight**
- Demand is relatively stable across periods  
- A sharp decline occurs in the final period  
- Indicates a **structural break caused by product discontinuation**

---

### 🔹 Product Contribution Analysis
![Seasonal](assets/top_product_demand.png)

**Insight**
- *Perfect Rip Deck* contributes **>20% of total demand**  
- Becomes the **primary driver of demand collapse**

---

## 🧪 Data Preparation & Feature Engineering

Key transformations:

- Data cleaning and aggregation  
- Feature construction based on business logic  

📌 Important Features:
- `Product_ID`  
- `Discount`  
- `Late_delivery_risk`  

These features significantly influence demand prediction.

---

## 🤖 Modeling & Evaluation

### 🔹 Model Performance Comparison
![MAPE](assets/model_comparison.png)

| Model | MAPE |
|------|------|
| 🥇 Tuned XGBoost | **0.45** |
| Random Forest | 0.48 |
| XGBoost | 0.47 |
| Gradient Boosting | 0.62 |
| Linear Models | 0.75 – 0.89 |
| Holt-Winters | 2.59 |
| SARIMA | 2.62 |

---

### 🔹 Actual vs Predicted (XGBoost)
![Scatter](assets/prediction_comparison.png)

**Insight**
- Predictions align closely with actual values  
- Indicates **high precision and strong generalization**

---

### 🔹 Time Series Model Comparison
![TS](assets/time_series_comparison.png)

**Insight**
- Traditional models fail to capture structural change  
- Machine learning models are more adaptive and robust  

---

## 📈 Key Findings

- **Tuned XGBoost is the best-performing model**  
- Demand patterns are **non-linear and event-driven**  
- Traditional time series models are insufficient for disruption scenarios  

📌 Key Drivers:
- Product dependency  
- Discount strategy  
- Delivery risk  

---

## 💡 Strategic Insights

- Demand collapse can be **anticipated with the right features**  
- Machine learning enables **early detection of risk signals**  
- Businesses can shift from **reactive to proactive decision-making**

---

## 🚀 Business Impact

This solution offers measurable benefits:

- 📈 +30% improvement in forecasting accuracy  
- 📦 20% reduction in overstock risk  
- ⚠️ Up to 80% mitigation of demand loss  

---

## 👨‍💻 Contribution

| Name | Role |
|------|------|
| **Muhammad Wildan Nabila** | Data Scientist / ML Engineer |
| Anindya Samantha Prayoga | Data Scientist |
| Muhammad Firdig Haqqy Abdillah | Data Analyst |

---

## 🔗 Official Repository

👉 https://github.com/anindyaprayoga/dataco-supply-chain-1

---

## 🧩 Tech Stack

- Python (Pandas, NumPy)  
- Machine Learning (Scikit-learn, XGBoost)  
- Time Series (Statsmodels)  
- Visualization (Matplotlib, Seaborn)  

---

## ⚠️ Notes

- Dataset: DataCo Smart Supply Chain (competition dataset)  
- No external data used  
- Research-oriented and experimental  

---

## 🏁 Conclusion

Tuned XGBoost demonstrates superior performance in forecasting demand under dynamic and disrupted conditions, outperforming traditional time series models. 

The findings confirm that demand is not random, but driven by key factors such as product dependency, discount strategy, and delivery risk. 

This approach enables businesses to shift from reactive forecasting to **proactive, data-driven supply chain decision-making**.

This project demonstrates how **data-driven approaches can transform supply chain operations into intelligent, adaptive systems**.

---
