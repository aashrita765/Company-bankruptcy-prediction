# Company-bankruptcy-prediction

💼 Company Bankruptcy Prediction – Project Summary

📊 Objective: Built a machine learning system to predict whether a company will go bankrupt based on its financial indicators.

💡 Business Motivation: Early bankruptcy detection assists investors, auditors, and banks in identifying high-risk firms and preventing financial loss.

🧾 Dataset: Sourced from Kaggle — contained numerical financial ratios like ROA, debt ratio, working capital, current ratio, and profitability measures.

🧹 Data Cleaning: Used klib and pandas to remove duplicates, handle missing values, and eliminate constant or redundant columns.

📈 Exploratory Data Analysis (EDA): Visualized distributions and correlations to understand feature relationships and detect outliers.

⚖️ Class Imbalance Handling: Applied SMOTE (Synthetic Minority Oversampling Technique) to generate synthetic bankrupt company samples, balancing both classes.

⚙️ Feature Scaling: Standardized numerical features using StandardScaler to ensure equal importance across all variables.

🤖 Models Implemented: Trained and compared five algorithms —

Logistic Regression (baseline linear model)

Random Forest (bagging ensemble)

XGBoost (boosting ensemble)

K-Nearest Neighbors (distance-based model)

Deep Neural Network (nonlinear representation learning using TensorFlow)

🧠 Model Training: Split data into 80% training and 20% testing; trained each model on balanced and standardized data.

📊 Evaluation Metrics: Measured performance using Accuracy, Precision, Recall, F1-score, and ROC–AUC for fair comparison.

🏆 Best Model: XGBoost achieved the highest performance — 98.5% accuracy and AUC = 1.00, indicating perfect separation between bankrupt and non-bankrupt firms.

📉 Other Results:

Random Forest: AUC = 1.00, Accuracy ≈ 90.8%

DNN & KNN: Accuracy ≈ 93.9%, AUC ≈ 0.94–0.98

Logistic Regression: Accuracy ≈ 90.8%, AUC = 0.96

🧩 Insights: Ensemble models (Random Forest, XGBoost) captured complex financial dependencies better than linear or distance-based models.

⚙️ Tools & Libraries: Python, pandas, NumPy, scikit-learn, imbalanced-learn, TensorFlow/Keras, Matplotlib, klib.

🚀 Future Enhancements:

Perform hyperparameter tuning (GridSearchCV/Optuna).

Add explainability (SHAP or LIME).

Incorporate time-series trends for better financial forecasting.
