# 🍩 Starbucks Bakery Data Analysis & Machine Learning

## 📌 Project Overview
This project explores the nutritional dataset of **Starbucks Bakery items (300+ products)**  
with the goal of identifying **health insights** and applying **machine learning** to classify and predict menu characteristics.  

The main research questions were:
- Which bakery items are **high/low in calories and sugar**?
- Which items are more suitable for **weight-conscious (low calorie)** vs **diabetic (low sugar)** consumers?
- What **nutritional factors** correlate most with calories?
- Can we use **clustering** to group items into "Healthy", "Balanced", and "High Sugar"?
- Can we **predict calories** using regression models from other nutrition variables?

---

## 📊 Dataset
- Source: Starbucks Bakery Nutrition File (Excel → cleaned into CSV)
- Size: 317 rows × 17 columns
- Key columns:
  - `Product Name`
  - `Calories`
  - `Total Fat (g)`
  - `Sugar (g)`
  - `Protein (g)`
  - `Sodium (mg)`
  - `Fiber (g)`
  - Vitamins & Minerals (%DV)

---

## 🛠 Tools & Libraries
- **Python**: pandas, numpy
- **Visualization**: matplotlib, seaborn
- **Machine Learning**: scikit-learn
- **Other**: Jupyter Notebook

---

## 🔎 Analysis Performed (30 Insights)
1. Data Cleaning (missing values, type conversion, duplicates)
2. Descriptive Statistics (mean, median, min/max for calories, sugar, fat)
3. Distribution plots (calories, sugar, protein)
4. Top/Bottom 5 items by Calories
5. Top/Bottom 5 items by Sugar
6. Top items by Protein
7. Calories per gram comparison
8. Sugar-to-Calorie ratio
9. Comparison: Cookies vs Muffins vs Cakes
10. Comparison: Small vs Large items
11. Fiber-rich items ranking
12. Correlation heatmap (Calories, Sugar, Fat, Protein)
13. Scatter plot: Calories vs Sugar
14. Scatter plot: Calories vs Protein
15. Linear Regression: Sugar predicting Calories
16. Clustering with K-Means (Healthy, Balanced, High Sugar)
17. PCA visualization of clusters
18. Hidden unhealthy group (low cal, high sugar)
19. High-protein group analysis
20. Regression model (RandomForest, XGBoost) predicting Calories
21. Classification: Healthy vs Non-healthy (logistic regression)
22. Outlier detection (Calories vs Weight)
23. % of Healthy vs Unhealthy items
24. "Healthy Score" (custom formula: High Protein + Low Fiber + Low Sugar)
25. Menu items exceeding WHO daily sugar intake
26. Menu items exceeding 30% daily fat intake
27. Nutrition radar charts (per category)
28. Business insight: only ~20% menus are “health-friendly”
29. Dashboard-ready summary (Calories, Sugar distribution)
30. Key Health Insights summary

---

## 💡 Key Health Insights
- **Average bakery item = ~350 kcal** (adding a latte → 500+ kcal in one sitting)
- **Many items exceed WHO daily sugar limit (25g)** in a single serving
- Only ~20% of bakery items are relatively **healthy (low cal, low sugar)**
- Strong correlation (r ≈ 0.8) between **Calories and Sugar**
- Some items are “hidden unhealthy” (low calories but very high sugar)

---

## 📂 Project Structure
