# Customer-Insights-Predictive-Marketing-Optimization

## 📌 Overview

This project delivers a full-scale market intelligence solution for optimizing direct marketing campaigns using advanced data science techniques. It simulates a real-world marketing scenario where customer data from a food company is leveraged to segment the audience, forecast behavior, and maximize campaign ROI.

This end-to-end pipeline includes data cleaning, exploratory analysis, feature engineering, machine learning modeling, sentiment analysis, RFM segmentation, market basket analysis, and strategic business recommendations.

---


## 📊 Core Project Objectives

- Predict which customers will respond to a marketing campaign
- Improve success rate from 15.4% to 72% using predictive modeling
- Identify customer characteristics that correlate with purchasing
- Generate strategic recommendations for high-ROI campaigns

---

## 🛠 Tools & Technologies

- **Languages**: Python (pandas, NumPy, scikit-learn, matplotlib, seaborn)
- **ML Models**: Random Forest, Naive Bayes, Decision Tree
- **EDA & Visualization**: seaborn, matplotlib
- **NLP**: TextBlob (Sentiment Analysis)
- **Segmentation**: RFM Analysis, Market Basket Analysis (Apriori)
- **Statistical Tests**: ANOVA, Chi-square

---

## 📁 Project Structure

- `notebooks/`: Jupyter notebooks organized by project stages
    - `1.Preprocessing.ipynb`: Cleaning and preparing the dataset
    - `2.EDA.ipynb`: In-depth exploratory data analysis
    - `3.RFM+Churn+MBA.ipynb`: RFM segmentation, churn prediction, and association rule mining
    - `4.Sentiment analysis.ipynb`: Customer review sentiment scoring
    - `5.Extra Point 1+2.ipynb`: Advanced insights & modeling enhancements
    - `FoodMarketingAnalysis.ipynb`: Final modeling, evaluation, and recommendations
- `data/`: Cleaned and raw CSV files
- `reports/`: Final marketing analysis report in PDF
- `README.md`: Project overview and documentation

---

## ✅ Key Results

| Metric                  | Pilot Campaign | With Model |
|------------------------|----------------|------------|
| Success Rate           | 15.4%          | 72.2%      |
| Net Profit             | –3,046 MU      | +3,319 MU  |
| Profit Gain            | —              | +6,244 MU  |

---

## 🔍 Key Insights

- Customers who are **younger**, **single/divorced**, and have **no dependents** show the highest likelihood of responding.
- Customers spending > $2,000 and active on **web/catalog** channels perform best.
- Sentiment analysis reveals product satisfaction trends aligning with purchasing behavior.
- Churn risk scoring helps identify customers who need retention strategies.
- RFM segmentation allows hyper-personalized marketing strategies.

---

## 📈 Statistical Highlights

Significant predictors for campaign success:
- **Income**
- **Recency**
- **Tenure (Customer Days)**
- **Total Spend**
- **Web Purchases**
- **Dependencies**

---

## 📎 Dataset

- `ifood_df.csv`: Kaggle source – [Marketing Data](https://www.kaggle.com/datasets/jackdaoud/marketing-data)
- Supplemented with `tbl_customers.csv`, `tbl_reviews.csv`, and other relational data
