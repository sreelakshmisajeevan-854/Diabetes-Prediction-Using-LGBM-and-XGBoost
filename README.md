# Diabetes Prediction Using LightGBM and XGBoost

## Objective

The objective of this project is to build and compare machine learning models using LightGBM (LGBM) and XGBoost (XGBM) for diabetes prediction.

The performance of both algorithms is evaluated and compared using appropriate classification metrics.

## Dataset

The Diabetes dataset is used for this machine learning classification problem.

The dataset contains various patient-related features that are used to predict the target outcome.

> Note: The assignment instructions mention the Titanic dataset in the EDA section, while the objective specifies the Diabetes dataset. This project uses the Diabetes dataset as specified in the objective.

## Tasks Performed

### 1. Exploratory Data Analysis (EDA)

- Loaded the dataset using Pandas.
- Examined the shape and structure of the dataset.
- Checked data types and summary statistics.
- Identified missing values.
- Analyzed feature distributions.
- Used histograms and box plots to understand numerical variables.
- Created visualizations to study relationships between features and the target variable.

### 2. Data Preprocessing

The following preprocessing steps were performed:

- Handled missing values using appropriate imputation techniques.
- Encoded categorical variables where required.
- Checked for inconsistencies and duplicate records.
- Applied additional preprocessing techniques where necessary.
- Prepared the dataset for machine learning.

### 3. Train-Test Split

The preprocessed dataset was divided into:

- Training dataset
- Testing dataset

The training data was used to build the models, while the testing data was used to evaluate their performance on unseen data.

### 4. LightGBM Model

A LightGBM classification model was implemented using Python.

Steps included:

- Building the LightGBM classifier.
- Training the model on the training dataset.
- Generating predictions on the test dataset.
- Evaluating the model using classification metrics.
- Performing hyperparameter tuning where required.

### 5. XGBoost Model

An XGBoost classification model was implemented and trained using the same dataset.

Steps included:

- Building the XGBoost classifier.
- Training the model on the training dataset.
- Generating predictions on the test dataset.
- Evaluating the model using classification metrics.
- Performing hyperparameter tuning where required.

### 6. Model Evaluation

The models were evaluated using the following metrics:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- ROC-AUC (where applicable)

Cross-validation was also used to obtain a more reliable estimate of model performance.

### 7. Comparative Analysis

The performance of LightGBM and XGBoost was compared based on their evaluation metrics.

A comparison of the models helps identify:

- Which model performs better on the dataset.
- Differences in accuracy and other classification metrics.
- Strengths and weaknesses of each algorithm.
- The suitability of each algorithm for diabetes prediction.

## LightGBM vs XGBoost

| LightGBM | XGBoost |
|---|---|
| Uses a leaf-wise tree growth strategy | Uses a level-wise tree growth strategy |
| Generally faster for large datasets | Can be computationally intensive |
| Efficient memory usage | Often provides strong predictive performance |
| Can handle large datasets efficiently | Supports extensive regularization |
| Uses histogram-based learning | Uses gradient boosting with regularization |

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- LightGBM
- XGBoost
- Jupyter Notebook / Google Colab

## Project Structure

```text
Diabetes-Prediction-Using-LGBM-and-XGBoost/
│
├── Diabetes_Prediction_LGBM_XGBoost.ipynb
├── diabetes.csv
└── README.md
