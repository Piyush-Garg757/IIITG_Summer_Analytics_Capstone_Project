
# Dynamic Pricing for Urban Parking Lots

**Summer Analytics 2025 Capstone Project**

This project aims to build a dynamic pricing strategy for urban parking lots using historical occupancy and pricing data. By analyzing patterns in lot usage and external factors such as time of day and weekends, we train a model to suggest optimal pricing.

---

## 📁 Files Included

- `Urban_Parking_Dynamic_Pricing_Final_Submission.ipynb`: Main Jupyter Notebook with code, visualizations, model, and insights.
- `README.md`: Project overview and instructions.

---

## 📌 Objective

To optimize parking lot revenue using dynamic pricing by identifying patterns in occupancy and pricing trends.

---

## 📊 Workflow Summary

1. **Data Preprocessing**:
   - Cleaned timestamps, engineered hour, weekday, weekend features.
2. **EDA (Exploratory Data Analysis)**:
   - Visualized hourly occupancy trends.
3. **Modeling**:
   - Trained Random Forest Regressor to predict price using occupancy, hour, and weekend indicator.
4. **Evaluation**:
   - Used RMSE and R² to evaluate model performance.

---

## 🚀 How to Run

1. Open the `.ipynb` file in Jupyter Notebook or Google Colab.
2. Run each cell step-by-step.
3. Review EDA plots and final model performance metrics.

---

## 🧠 Key Insights

- Higher occupancy during peak hours → pricing should be increased accordingly.
- Weekend trends differ from weekdays → suggest differentiated pricing.
- Random Forest performs decently on simulated data — performance expected to improve on real-world data.

