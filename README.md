# DMAIC Food Delivery Analysis

This project applies the **Lean Six Sigma DMAIC** methodology to analyze and reduce food delivery delays using a real-world dataset from Kaggle.  
It also includes a **machine learning model** to predict late deliveries and proposes practical operational improvements.

## Problem Statement

Late food deliveries negatively impact customer satisfaction and business performance.  
The goal is to:
- Identify key factors causing delays
- Propose improvements to reduce delivery time
- Predict late deliveries using ML (future scope)

## Tools & Technologies
- Python
- Jupyter Notebook
- Pandas, NumPy
- Matplotlib, Seaborn
- DMAIC Methodology (Lean Six Sigma Green Belt level)

---

## Methodology: DMAIC

### Define Phase
- Over 30% of deliveries exceed 25 minutes
- Goal: Reduce late deliveries to under 15%
- Scope: Focused on delivery delay (not cooking time)

### Measure Phase
- Dataset: [Food Order Dataset – Kaggle](https://www.kaggle.com/datasets/ahsan81/food-ordering-and-delivery-app-dataset)
- Explored key variables: delivery time, cuisine type, restaurant, day of week
- Created `late_delivery` flag based on 25 min threshold

### Analyze Phase
- Visualized delivery time distribution
- Identified late delivery trends by:
  - Day of week
  - Cuisine
  - Restaurant
- Plotted control and Pareto charts

### Improve Phase
- Key root causes: weekends, specific cuisines, traffic, prep time
- Suggested actions:
  - Re-assign delivery zones
  - Prioritize high-delay restaurants
  - Use alert systems for prep time

### Control Phase
- Set up monitoring KPIs:
  - Avg delivery time
  - % of late deliveries
- Created a control chart over 12 weeks

---
### Author

**Praveen Shivaramu**

MSc Industry 4.0 & Management | Lean Six Sigma Green Belt Certified
https://www.linkedin.com/in/praveen-shivaramu-a3a54b218/

