# ❤️ Heart Disease Prediction using Decision Tree and Random Forest

This project uses a **Decision Tree** and a **Random Forest Classifier** to predict the presence of heart disease using the Heart Disease dataset
---

## 📌 Objectives

✅ Train and evaluate a **Decision Tree Classifier**  
✅ Prevent overfitting by controlling **max_depth**  
✅ Train and evaluate a **Random Forest Classifier**  
✅ Compare performance of both models  
✅ Visualize the Decision Tree  
✅ Analyze **feature importance**  
✅ Use **cross-validation** to verify generalization

---

## 🧪 Model Performance

| Model           | Test Accuracy | Cross-Validation Accuracy |
|----------------|---------------|----------------------------|
| Decision Tree  | ~89%          | ~84%                      |
| Random Forest  | ~95%          | ~87%                      |

---

## 📊 Feature Importance

Random Forest provides insights into which features contribute the most. Example top features:
- `thal`
- `cp` (chest pain)
- `ca`
- `oldpeak`

---

## 🧾 Instructions to Run (Google Colab Recommended)

1. Open [Google Colab](https://colab.research.google.com/)
2. Paste code cells one-by-one from the provided notebook/code
3. Run each cell in order to:
   - Load data
   - Train models
   - Visualize decision tree
   - View accuracy and feature importance

---

## 📦 Libraries Used

- `pandas`
- `matplotlib`
- `seaborn`
- `sklearn`

---

## 🧠 Conclusion

- **Random Forest** performs better and generalizes well.
- **Decision Tree** is easy to visualize and interpret but prone to overfitting.
- **Cross-validation** helps in validating the true accuracy.
- Feature importance reveals medically relevant predictors like chest pain and thalassemia.
