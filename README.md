🏙 NYC Restaurant Inspection Machine Learning Analysis
📌 Research Questions

RQ1: How much variation in inspection scores is explained by geography?

RQ2: What predicts repeat violation behavior?

RQ3: Are certain cuisine types associated with severe violations given geography?

📊 Data Source

NYC Department of Health & Mental Hygiene
289,000+ inspection records

🔎 Methods Used

Linear Regression

Ridge Regression

Random Forest

Gradient Boosting

HistGradientBoosting

Mutual Information Feature Selection

Permutation Importance

Geographic Feature Engineering

Class Imbalance Handling (Upsampling)

📈 Key Findings

Geography explains minimal variation in inspection score (R² ≈ 0.02)

Repeat identical violations highly predictable (Accuracy ≈ 0.89)

Severe violations moderately predictable (ROC-AUC ≈ 0.66)

Location and inspection phase strongest predictors

🛠 Tools Used

Python

Pandas

Scikit-learn

Seaborn

Matplotlib

KMeans clustering
