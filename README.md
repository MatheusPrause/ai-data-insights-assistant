\# AI Data Insights Assistant



\## Project Overview

This project focuses on building and evaluating predictive models to estimate disease progression based on clinical and physiological measurements. The objective is to explore the data, establish a baseline model, and progressively improve performance using more expressive machine learning techniques.



The project is designed as a professional data science workflow, covering exploratory data analysis, modeling, evaluation, and interpretation.



---



\## Dataset

The dataset used in this project is the Diabetes dataset from `scikit-learn`, which contains numerical, normalized clinical features and a continuous target variable representing disease progression.



\*\*Features include:\*\*

\- Age

\- Sex

\- Body Mass Index (BMI)

\- Blood Pressure (BP)

\- Six serum measurements



---



\## Methodology



\### 1. Exploratory Data Analysis (EDA)

\- Descriptive statistics

\- Correlation analysis

\- Heatmaps and scatter plots

\- Identification of relevant feature-target relationships



\### 2. Baseline Modeling

\- Linear Regression as an initial benchmark

\- Performance evaluation using RMSE and R²



\### 3. Advanced Modeling

\- Random Forest Regressor

\- Manual hyperparameter tuning

\- GridSearch cross-validation

\- Feature importance and permutation importance analysis



---



\## Results Summary



| Model                          | RMSE (approx.) | R² (approx.) |

|--------------------------------|----------------|--------------|

| Linear Regression              | ~59            | ~0.36        |

| Random Forest (baseline)       | ~54            | ~0.44        |

| Random Forest (optimized)      | Best overall   | Best overall |



The Random Forest model demonstrated superior performance by capturing non-linear patterns and feature interactions that linear models could not represent.



---



\## Key Insights

\- BMI and serum-related variables play a significant role in disease progression.

\- Tree-based models outperform linear models for this dataset.

\- Proper regularization improves generalization and reduces overfitting.



---



\## Project Structure

```text

ai-data-insights-assistant/

├── notebooks/

│   └── 01\_exploratory\_analysis.ipynb

├── data/

├── README.md

└── requirements.txt



\# How to Run



\# Create virtual environment

python -m venv venv



\# Activate (Windows)

venv\\Scripts\\activate



\# Install dependencies

pip install -r requirements.txt



\# Launch Jupyter

jupyter notebook



Future Improvements



Gradient Boosting models (XGBoost, LightGBM)



Feature engineering



Model interpretability using SHAP



Deployment as an interactive application



\# Author



\## Matheus Maximowitz Prause



Artificial Intelligence Undergraduate





