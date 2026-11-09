# Datheon Machine Learning & Data Science Internship

This repository contains the projects and implementations completed as part of the **Datheon Machine Learning & Data Science Internship**.

The projects cover data preprocessing, exploratory data analysis, machine learning algorithms, model evaluation, and visualization using Python.

## Projects

### Task 1 – Iris Classification

**Objective:** Classify Iris flowers into three species using machine learning algorithms.

- Dataset: Iris Dataset (150 samples, 4 features)
- Data preprocessing and exploratory data analysis
- Feature scaling using StandardScaler
- Models: Logistic Regression and Decision Tree
- Evaluation: Accuracy, F1-score, confusion matrix, and classification report

| Model               | Accuracy |
| ------------------- | -------: |
| Logistic Regression |    93.3% |
| Decision Tree       |    96.7% |

**Notebook:** `Task-1_Iris-Classification/iris_classification_benchmark.ipynb`

### Task 2 – California Housing Price Prediction

**Objective:** Predict median house values using regression algorithms.

- Dataset: California Housing Dataset (20,640 records)
- Data cleaning and missing-value imputation
- Exploratory data analysis and correlation analysis
- Feature engineering and multicollinearity analysis
- Numerical scaling and categorical encoding
- Models: Ordinary Least Squares (OLS), Ridge, and Lasso Regression
- Hyperparameter tuning using GridSearchCV
- Evaluation: RMSE, MAE, and R²
- Actual vs. predicted and residual analysis

| Model |      RMSE |       MAE |     R² |
| ----- | --------: | --------: | -----: |
| OLS   | 69,048.19 | 49,376.49 | 0.6362 |
| Ridge | 69,056.22 | 49,382.63 | 0.6361 |
| Lasso | 69,049.25 | 49,377.34 | 0.6362 |

**Notebook:** `Task-2_California-Housing-Regression/california_housing_regression.ipynb`

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook / Google Colab

## Repository Structure

```text
Datheon_Machine_Learning_&_Data_Science_Internship/
│
├── Task-1_Iris-Classification/
│   └── iris_classification_benchmark.ipynb
│
├── Task-2_California-Housing-Regression/
│   └── california_housing_regression.ipynb
│
├── README.md
└── requirements.txt
```

## Installation

Clone the repository:

```bash
git clone https://github.com/suramaxi92/Datheon_Machine_Learning_-_Data_Science_Internship
cd Datheon_Machine_Learning_&_Data_Science_Internship
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

Open the notebooks using Jupyter Notebook or Google Colab.

## Internship Progress

- [x] Task 1 – Iris Classification
- [x] Task 2 – California Housing Regression
- [ ] Task 3 - NLP Sentiment Classification

---

**Internship:** Datheon Machine Learning & Data Science Internship
