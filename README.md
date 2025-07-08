# 📊 Telecom Customer Churn Analysis

This project explores customer churn patterns for a telecom provider using exploratory data analysis (EDA), storytelling visuals, and business-driven insights. The goal is to identify which customers are most likely to churn and uncover the underlying factors behind their decisions.

---

## 🧰 Tech Stack / Libraries Used

- Python 3.x  
- Pandas  
- NumPy  
- Matplotlib & Seaborn  
- Plotly Express (for interactive maps)  
- Google Colab (development environment)  

---

## 📈 Key Analytical Steps

- ✅ Data Cleaning & Understanding  
- ✅ Feature Engineering  
  - Heavy user segmentation  
  - Tenure bucketing  
  - International mismatch flag  
- ✅ Visual Storytelling  
  - Pie charts, bar graphs, stacked charts  
  - Choropleth maps, line plots, heatmaps  
- ✅ Business-Oriented Insight Generation  

---

## 💡 Key Insights Summary

- 📌 **Churn is imbalanced**: Only 14% of customers churned — imbalance matters for downstream modeling.
- 📌 **International plan holders churn more** — potentially due to pricing or dissatisfaction.
- 📌 **Heavy users and mid-term customers** show higher churn risk.
- 📌 **Repeated customer service calls** correlate strongly with churn.
- 📌 **Churn occurs at both low and high cost extremes** — engagement and perceived value both matter.

---

## 💡 Final Business Recommendation

Reducing churn will require a mix of:
- Improving customer support systems
- Reassessing pricing for international and heavy users
- Strengthening customer engagement in the mid-lifecycle phase

These changes could directly impact customer satisfaction and long-term retention.

---

## 📊 Files

```bash
📁 Telecom_Churn_Analysis/
│
├── churn_analysis_v1.ipynb         # Initial EDA and setup
├── churn_analysis_v2.ipynb         # Refined visuals and better structure
├── churn_analysis_final.ipynb      # Clean visuals + polished insights
├── README.md                       # Project overview and conclusions
