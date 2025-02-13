Credit Card Fraud Detection using XGBoost

Overview

This project demonstrates a fraud detection system using XGBoost, Pandas, Seaborn, and Scikit-learn. The dataset consists of anonymized credit card transactions, where the goal is to classify transactions as fraudulent (1) or non-fraudulent (0).

Dataset

The dataset used is creditcard.csv, which contains transactions with fraud labels.

Due to class imbalance, only ~0.17% of transactions are fraudulent.

Project Steps

1️⃣ Data Exploration & Visualization

Check for missing values and class imbalance.

Visualizations: Class distribution, transaction amount distribution, correlation heatmap, and boxplot.

2️⃣ Data Preprocessing

Normalize transaction amounts using StandardScaler().

Remove unnecessary columns (Time, Amount).

Split dataset into training (80%) and testing (20%).

3️⃣ Model Training with XGBoost

Train an XGBoost classifier with logloss as the evaluation metric.

Predict fraudulent transactions.

4️⃣ Model Evaluation

Generate classification report (Precision, Recall, F1-score, Accuracy).

Display confusion matrix as a heatmap.

Plot the AUC-ROC curve to measure fraud detection effectiveness.

Installation & Usage

Install required dependencies:

pip install pandas numpy seaborn matplotlib scikit-learn xgboost

Run the notebook or Python script.

python fraud_detection.py

Results

Fraudulent transactions are successfully classified with high recall.

XGBoost performs well in handling class imbalance and optimizing fraud detection.

AUC-ROC Curve helps visualize the model's predictive power.

Contributions

Feel free to fork, improve, and submit pull requests! 🚀

License

This project is open-source and available under the MIT License.
