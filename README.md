# Product Return Prediction

A classification project to predict whether a product will be returned using simulated e-commerce data. Features include delivery time, price, product group, and return reason. The model helps reduce return-related business costs.

**Tools**
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Google Colab

**Model**
- Algorithm: Random Forest
- Tuning: GridSearchCV (72 combinations)
- Test Accuracy: **75%**

**Key Results**
- Best Parameters:
  ```python
  {'bootstrap': True, 'max_depth': 10, 'max_features': 'sqrt', 'min_samples_split': 2, 'n_estimators': 200}

  
