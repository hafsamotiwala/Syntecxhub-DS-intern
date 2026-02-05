# Wine Dataset Correlation & Pairwise Analysis

This project explores the **Wine dataset** from `scikit-learn` to analyze correlations and pairwise relationships between numeric features.

---

## Dataset

- **Samples:** 178 wines  
- **Features:** 13 numeric chemical properties (e.g., Alcohol, Malic acid, Flavanoids, Color intensity, OD280/OD315)  
- **Target:** Wine class (0, 1, 2)

---

## Steps

1. Loaded dataset into a Pandas DataFrame  
2. Computed **Pearson correlations** between numeric features  
3. Visualized **correlation heatmap** (upper triangle masked, annotated)  
4. Created **pairplots** for key variables  
5. Summarized strongest positive & negative correlations

---

## Key Findings

- **Strong Positive Correlations:**  
  - Flavanoids ↔ Total phenols (~0.86)  
  - OD280/OD315 ↔ Flavanoids (~0.78)  

- **Strong Negative Correlations:**  
  - Alcohol ↔ Malic acid (~-0.44)  
  - Flavanoids ↔ Nonflavanoid phenols (~-0.33)  

> Insights highlight which chemical properties are closely related and may influence wine classification.

---

## Visualizations

- **Heatmap:** Shows all feature correlations  
- **Pairplot:** Scatter plots and distributions for selected features by wine class

---
