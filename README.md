# ML_Traffic_Prediction
ML-based traffic prediction using Random Forest and SVR models with preprocessing and performance evaluation.

# 🚦 Traffic Prediction using Machine Learning

This project uses machine learning models (Random Forest and Support Vector Regression) to predict traffic density based on various features like day, weather, temperature, and zone data.

---

## 📂 Dataset

The dataset includes:

- `Day`: Name of the day (e.g., Monday, Tuesday, etc.)
- `Date`: Encoded date
- `CodedDay`: Numeric representation of the day
- `Zone`: City zone identifier
- `Weather`: Weather condition index
- `Temperature`: Temperature value
- `Traffic`: Traffic level (target variable)

---

## ⚙️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn (sklearn)
- Google Colab (for running the code)

---

## 🧠 Models Used

1. **Random Forest Regressor**  
   - Accuracy: ~86.58%

2. **Support Vector Regressor (SVR)**  
   - Accuracy: ~87.84%

---

## 📝 Features

- Data preprocessing
- Label Encoding
- Feature scaling using StandardScaler
- Train-test split (80/20)
- Random Forest Regression
- SVR with RBF kernel
- Accuracy and Error analysis


