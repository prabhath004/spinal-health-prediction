🦴 Spinal Health Prediction using Machine Learning

📌 Project Overview
This project predicts spinal health conditions (Normal vs. Abnormal) using Machine Learning & Medical Alignment.
It integrates Random Forest, SVM, and a Voting Classifier to optimize accuracy while ensuring medically valid predictions.

✅ Key Features
Trained on spinal dataset (with features like pelvic tilt, lumbar lordosis, etc.).
Uses Random Forest & SVM inside a Voting Classifier for robust predictions.
Applies medical adjustments to align with real-world diagnostic criteria.
Evaluates performance using Confusion Matrix, ROC Curve, and Precision-Recall Tradeoff.
Generates predictions for new spinal data and stores results in a CSV.
⚙️ Technologies & Algorithms Used
🔢 Machine Learning Models
Random Forest Classifier (Tuned using GridSearchCV)
Support Vector Machine (SVM)
Voting Classifier (Combines both models for better performance)
Medical Adjustment Logic (Overrides ML decisions when necessary)
📊 Evaluation Metrics
Accuracy: 95.24%
Recall: 100% (Minimizes false negatives, crucial in healthcare)
ROC AUC Score: 0.96
Precision-Recall Optimization

📊 Model Performance
Metric	Score
Accuracy	95.24%
Precision	91.30%
Recall	100%
F1-Score	95.45%
ROC AUC Score	0.96
🎯 Results Visualization
The model performance is validated using Confusion Matrix, ROC Curve, and Precision-Recall Tradeoff.

🔹 Confusion Matrix
✅ Correctly classified 38 Normal & 42 Abnormal cases
❌ Only 4 false positives (misclassified Normal cases)

🔹 ROC Curve
🚀 AUC Score of 0.96 indicates strong model performance.

🔹 Precision-Recall Curve
📊 Optimized threshold ensures better recall (reducing false negatives).
