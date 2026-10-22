# Datheon Machine Learning & Data Science Internship

A collection of machine learning projects completed as part of the Datheon Machine Learning & Data Science Internship. This repository demonstrates data preprocessing, exploratory data analysis, supervised learning, model evaluation, and visualization using Python and Scikit-learn.

## Internship Overview

- **Program:** Machine Learning & Data Science Internship
- **Organization:** Datheon
- **Focus:** Supervised Machine Learning and Predictive Modeling
- **Tools:** Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, and Jupyter Notebook

## Projects

### Task 1: Iris Flower Classification

**Objective:** Build and compare supervised classification models to predict Iris flower species using flower measurements.

**Models**
- Logistic Regression
- Decision Tree Classifier

**Workflow**
1. Explore and visualize the Iris dataset.
2. Split the data into training and testing sets (80/20).
3. Scale features using `StandardScaler`.
4. Train and evaluate both classification models.
5. Compare model performance using classification metrics.
6. Visualize confusion matrices and decision boundaries.

**Key Concepts**
- Supervised classification
- Feature scaling
- Train-test splitting
- Model evaluation
- Confusion matrices and decision boundaries

### Task 2: California Housing Price Prediction

**Objective:** Predict median house values using the California Housing dataset and compare Ordinary Least Squares (OLS), Ridge, and Lasso regression models.

**Models**
- Linear Regression (OLS)
- Ridge Regression (L2 Regularization)
- Lasso Regression (L1 Regularization)

**Workflow**
1. Load and explore the California Housing dataset.
2. Check missing values and visualize feature correlations.
3. Separate input features from the target variable.
4. Split the data into training and testing sets.
5. Impute missing values and encode categorical features.
6. Create interaction features and standardize numerical features.
7. Tune Ridge and Lasso using `GridSearchCV`.
8. Compare models using MAE, RMSE, and R².
9. Visualize actual versus predicted values and residual distributions.

**Key Concepts**
- Regression and price prediction
- Feature engineering
- Missing-value imputation
- Categorical encoding and feature scaling
- Multicollinearity and regularization
- Hyperparameter tuning
- Residual analysis

## Technologies Used

- **Python** — Programming language
- **Pandas** — Data manipulation and analysis
- **NumPy** — Numerical operations
- **Scikit-learn** — Data preprocessing, model training, tuning, and evaluation
- **Matplotlib** — Data visualization
- **Seaborn** — Statistical visualization
- **Jupyter Notebook** — Interactive development and documentation

## Repository Structure

```text
Datheon_Machine_Learning_Data_Science_Internship/
├── Task1_Iris_Classification.ipynb
├── Task2_Housing_Price_Prediction.ipynb
├── data/
│   └── iris.csv
├── requirements.txt
└── README.md
```

*Adjust the filenames and folders above to match your actual repository.*

## Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/Junaid5253/Datheon_Machine_Learning_Data_Science_Internship.git
```

### 2. Navigate to the project folder

```bash
cd Datheon_Machine_Learning_Data_Science_Internship
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open the notebook for the task you want to explore and run the cells from top to bottom.

## Evaluation Metrics

### Classification — Task 1

- **Accuracy:** Proportion of correct predictions.
- **Precision:** Proportion of positive predictions that are correct.
- **Recall:** Proportion of actual positive cases identified.
- **F1-score:** Harmonic mean of precision and recall.
- **Confusion Matrix:** Shows correct and incorrect classifications.

### Regression — Task 2

- **MAE:** Average absolute prediction error.
- **RMSE:** Square root of the average squared prediction error.
- **R² Score:** Measures how much variation in house values is explained by the model.

Actual performance metrics and comparisons are reported in the respective notebooks after execution.

## Learning Outcomes

Through these projects, I am developing practical experience in:

- Exploring and preparing datasets for machine learning.
- Building classification and regression models.
- Applying feature engineering and preprocessing techniques.
- Comparing models using appropriate evaluation metrics.
- Tuning model hyperparameters.
- Visualizing model performance and prediction errors.
- Organizing machine learning projects using reproducible Jupyter Notebooks.

## Project Status

- [x] Task 1 — Iris Flower Classification
- [x] Task 2 — California Housing Price Prediction
- [ ] Task 3 — To be added
- [ ] Task 4 — To be added

## Author

**Junaid Abdullah**

- GitHub: [Junaid5253](https://github.com/Junaid5253)
- University: COMSATS University Islamabad
- Program: BS Data Science

---

This repository is maintained for learning, experimentation, and portfolio development as part of the Datheon Machine Learning & Data Science Internship.