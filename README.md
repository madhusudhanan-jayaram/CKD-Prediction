🧠 CKD Classification using Machine Learning
Welcome to the CKD classification project! This repository is focused on building and evaluating machine learning models to detect Chronic Kidney Disease (CKD) using structured patient health records.

🔬 Project Overview
This project uses the CKD dataset to train classification models that predict whether a patient is likely to have CKD. It includes complete steps for:

Data cleaning and encoding

Feature scaling

Exploratory Data Analysis (EDA)

Model training (Decision Tree with GridSearchCV)

Evaluation using F1-score, precision, recall

Future prediction using test samples

Balanced class handling using class_weight='balanced'

📁 Repository Structure
bash

📦 ckd-classification-ml
 ┣ 📊 CKD.csv                  # Dataset
 ┣ 📓 decision_tree_classification_grid.ipynb
 ┣ 📄 ckd_test_samples.json    # Test samples for future prediction
 ┗ README.md                   # Project overview and usage
🚀 Models Used
✅ DecisionTreeClassifier with GridSearchCV

Weighted scoring using f1_weighted to handle class imbalance

📈 Sample Metrics
mathematica
Copy
Edit
Accuracy       : 86%
Precision (0)  : 0.85
Precision (1)  : 0.88
Recall    (0)  : 0.94
Recall    (1)  : 0.71
F1-score       : 0.85 (weighted)
🔮 Future Predictions
Includes functionality to:

Accept new patient data as Python dictionaries

Scale inputs using the same training pipeline

Output human-readable results with emoji-enhanced formatting

python
Copy
Edit
Test Case 1: 🟢 CKD Detected (Confidence: 0.92)
Test Case 2: 🔵 No CKD (Confidence: 0.84)
📌 How to Use
Clone the repo:

bash

git clone https://github.com/madhusudhanan-jayaram/ckd-classification-ml.git
Run the Jupyter notebook:

bash

jupyter notebook decision_tree_classification_grid.ipynb
Try out predictions with your own test data or use the provided ckd_test_samples.json.

🧠 Skills Demonstrated
Data preprocessing and feature engineering

Grid search hyperparameter tuning

Model evaluation metrics for classification

Real-world test case simulation

Code readability and formatting best practices

👨‍💻 Author
Madhu Sudhanan Jayaram
AI & Full-Stack Enthusiast | Machine Learning Explorer


