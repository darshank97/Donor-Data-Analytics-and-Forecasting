# Donor Data Analytics & Forecasting  
*Capstone Project – Grand Canyon Council, Scouting America*  

---

## 📌 Problem Statement  
The Grand Canyon Council faced stagnating donations and donor attrition since 2019, despite a strategic goal of achieving **10% annual fundraising growth**.  
Our objective was to leverage donor data to:  
- Segment donors by behavior and value  
- Predict future donation amounts  
- Recommend data-driven strategies to increase engagement and retention  

Target outcome: **2.5–5% annual fundraising growth** through smarter donor analytics.  

---

## 🛠️ Tech Stack  
- **Languages & Tools**: SQL, Python (Pandas, NumPy, Matplotlib, Seaborn)  
- **Machine Learning**: RFM Analysis, K-Means Clustering, Random Forest Regression  
- **Visualization**: Tableau, Streamlit Dashboards  
- **Data Engineering**: Cleaning, transformation, feature engineering  
- **Synthetic Data**: 100K donor profiles for scenario testing & prediction augmentation  

---

## 🚀 Approach  

1. **Data Preparation**  
   - Gift Records: 66,019 records (donations, funds, payment methods)  
   - Constituent Records: 28,348 records (demographics, engagement, giving history)  
   - Data cleaning: removed duplicates, filled missing values, normalized donation features  

2. **RFM Segmentation**  
   - Scored donors by **Recency, Frequency, Monetary Value**  
   - Segments included: VIP Donors, Lapsed High-Value, Frequent Donors, General Donors  

3. **K-Means Clustering**  
   - Applied clustering (k=6) to validate RFM segmentation  
   - Confirmed natural donor groupings & behavioral patterns  

4. **Predictive Modeling**  
   - Trained a **Random Forest regression model**  
   - Achieved **R² = 0.9454** on test set  
   - Forecasted 2025 donations with multiple scenarios  

5. **Synthetic Data Integration**  
   - Generated **100K synthetic donor records** with demographic & behavioral features  
   - Enhanced predictive power, filled gaps in sparse data  
   - Enabled scenario-based forecasting and persona-driven strategies  

6. **Strategy Development**  
   - **Geographic focus**: Phoenix, Scottsdale, Mesa → 70% of donation value  
   - **Donor persona strategies**: Retain VIPs, reactivate lapsed donors, upgrade general donors  
   - Built Tableau and Streamlit dashboards for interactive donor insights  

---

## 📊 Key Results  

- **Segmentation Insights**  
  - VIP & High-Monetary Donors = ~70% of donations despite <20% of donor base  
  - Lapsed high-value donors identified as prime re-engagement target  

- **Forecasting Outcomes**  
  - Retaining top 20% donors projected to raise **$1.35M–$1.6M in 2025**  
  - Optimistic scenario (+10% retention) projected **$1.62M+**  

- **Impact**  
  - Enabled **targeted campaigns** → higher ROI vs blanket outreach  
  - Improved donor retention & upgrade strategies  
  - Framework scalable across other Scouting America councils  

---

