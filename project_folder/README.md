# Sentiment Analysis of Google Play Store User Reviews

## 1. Group Members
* Miras Asem

## 2. Dataset Information
* **Dataset Name:** Google Play Store User Reviews
* **Source URL:** [Kaggle - Google Play Store Apps](https://www.kaggle.com/datasets/lava18/google-play-store-apps/data?select=googleplaystore_user_reviews.csv)
* **License:** CC0: Public Domain (Available via Kaggle)

## 3. Installation and Execution Instructions

### Prerequisites
Python 3.8+ must be installed on your system.

### Setup Environment
```bash
pip install -r requirements.txt
```

Running the Pipeline
Execute the Jupyter notebooks in the notebooks/ directory in the following exact order. Each notebook must be run from start to finish using the "Kernel → Restart & Run All" command.

T1_EDA.ipynb

T2_Supervised.ipynb

T3_Unsupervised.ipynb

T4_Ensemble.ipynb

4. Final Model Results
Task,Model,Accuracy
Task 2 (Supervised), | Logistic Regression, |  0.8512
Task 2 (Supervised), | Decision Tree,       |  0.7723
Task 4 (Ensemble),   | Random Forest,       |  0.8271
Task 4 (Ensemble),   | Gradient Boosting,   |  0.8040

5. Visualizations
Sentiment Distribution
Top 10 Feature Importances (Random Forest)
6. Academic Integrity Statement
AI coding assistants were utilized strictly for syntax generation, boilerplate code structuring, and debugging purposes. All data analysis, model comparisons, and final conclusions represent original work.
