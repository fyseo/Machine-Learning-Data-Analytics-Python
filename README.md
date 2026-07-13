# Machine Learning & Data Analytics Portfolio

A curated collection of data science and machine learning projects focusing on exploratory data analysis (EDA), feature engineering, predictive modeling, and Natural Language Processing (NLP). 

## Tech Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib/Seaborn
* **Techniques:** Linear/Ridge/Lasso Regression, Logistic Regression, Support Vector Machines (SVM), AdaBoost, TF/TF-IDF, Sentence Embeddings, GridSearch Optimization

---

## Projects Overview

### 1. MOOC Platform Text Classification & Analysis
* **Objective:** Perform descriptive analysis and classify user-generated text from a Massive Open Online Course (MOOC) platform based on Urgency, Confusion, and Sentiment.
* **Implementation:** Engineered a robust text preprocessing pipeline comparing TF, TF-IDF, and Sentence Embeddings (all-MiniLM-L6-v2). Evaluated Naïve Bayes, Random Forest, AdaBoost, Logistic Regression, and SVM models.
* **Result:** Achieved over 91% accuracy for Urgency classification using an optimized SVM model with RBF kernel via GridSearch.

### 2. Clinical Heart Disease Classifier
* **Objective:** Predict the presence of heart disease using raw clinical data.
* **Implementation:** Handled missing medical data using K-Nearest Neighbors (KNN) imputation and applied One-Hot Encoding. Compared L1 (Lasso) and L2 (Ridge) regularized Logistic Regression models.
* **Result:** The L2-Regularized model achieved an AUC of 0.87, successfully establishing a reliable baseline for clinical classification.

### 3. Housing Price Predictive Modeling
* **Objective:** Estimate housing prices using the California and Boston Housing datasets.
* **Implementation:** Addressed artificial price caps, mitigated multicollinearity by engineering ratio features, and normalized highly skewed data via logarithmic transformations. 
* **Result:** Deployed an optimized Ridge Regression model that successfully minimized error while preserving feature importance.

## How to Run
Each project is contained within its respective directory. You can view the Jupyter Notebooks (`.ipynb`) directly on GitHub to see the code, visualizations, and model outputs. To run locally:
1. Clone the repository.
2. Ensure you have Python 3.x and the required libraries installed (e.g., `pip install pandas scikit-learn jupyter`).
3. Launch Jupyter Notebook or JupyterLab to interact with the files.

## Contributors

* **Yousuf Islam** - [fyseo](https://github.com/fyseo)
* **Abdulrehman-Hatem** - [Abdulrehman's GitHub](https://github.com/Abdulrehman-Hatem)