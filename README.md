# ML_Traffic_Prediction
ML-based traffic prediction using Random Forest and SVR models with preprocessing and performance evaluation.

# 🚦 Traffic Prediction using Machine Learning

This project uses machine learning models (Random Forest and Support Vector Regression) to predict traffic density based on various features like day, weather, temperature, and zone data.

---

## 📂 Dataset

**Descrption :**  The dataset includes: The dataset used in this project contains traffic-related information collected over multiple zones and days. It includes 1439 rows and 7 columns, each representing different attributes that could affect traffic levels.


- `Day`: Day of the week (e.g., Monday, Tuesday).
- `Date`: Encoded version of the calendar date.
- `CodedDay`: Numerical representation of the day (e.g., Monday = 1, Tuesday = 2, etc.).
- `Zone`: Identifier for specific city zones (numerical).
- `Weather`: Numerical value representing weather conditions.
- `Temperature`: Recorded temperature (in °C) on that date in the zone.
- `Traffic`: Target variable – represents traffic level (on a scale or count).

---
## 🧠 Key Points:

- The dataset captures the multifactor influence on traffic, such as:
- Which day of the week it is (weekdays vs. weekends).
- Weather conditions (e.g., rain might increase or decrease traffic).
- Temperature (extreme heat/cold might reduce traffic).
- Zone differences (some areas are naturally busier).
- The dataset is clean (no missing values).
- Categorical columns like Day and Date are encoded before modeling.

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


