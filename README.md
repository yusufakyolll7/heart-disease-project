# Heart Disease Prediction with Machine Learning 🫀

This project uses real-world cardiovascular health data to predict whether a person is at risk of heart disease using various machine learning models.

## 📌 Objective

The goal is to clean, analyze, and model the dataset to identify the most suitable machine learning algorithm for heart disease prediction.

## 📊 Dataset

- Source: [Kaggle - Heart Failure Prediction](https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction)
- Features: Age, Cholesterol, MaxHR, ST Slope, Chest Pain Type, etc.
- Target: `HeartDisease` (0 = No, 1 = Yes)

## 🧪 Models Used

- Decision Tree  
- Random Forest    
- K-Nearest Neighbors (Best performing model: F1 Score = 0.89)

## 📈 Key Results

- Best Model: KNN
- Accuracy: 88.59%
- F1 Score: 89.86%
- Most influential features: ST Slope, MaxHR, Oldpeak

## 🔬 Techniques Used

- Data cleaning & visualization  
- Statistical analysis (T-test, p-values)  
- Feature scaling & encoding  
- Model evaluation (Accuracy, F1, Confusion Matrix)

## 🛠️ Libraries

`pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`

---

Feel free to explore the notebook and test the models. This project was completed as part of a 130-hour Python & AI course.
