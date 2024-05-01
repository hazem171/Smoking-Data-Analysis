# Smoking-Data-AnalysisPredicting Smoking Status using Health Metrics
Overview
This project aims to predict whether a person smokes or not based on various health metrics such as heart rate, blood pressure, and cholesterol level. The dataset used in this project contains anonymized health data of individuals, including their age, sex, current smoking status, heart rate, blood pressure, cigarette consumption, and cholesterol level.

Dataset
The dataset used in this project is provided in a CSV format and contains the following columns:

age: Age of the individual.
sex: Gender of the individual (male or female).
current_smoker: Smoking status of the individual (yes or no).
heart_rate: Heart rate of the individual.
blood_pressure: Blood pressure of the individual in the format "systolic/diastolic".
cigs_per_day: Number of cigarettes smoked per day by the individual.
chol: Cholesterol level of the individual.

Preprocessing
The dataset is preprocessed to handle missing values and convert categorical variables into numerical representations.
Blood pressure is split into systolic and diastolic pressure columns.
Age is grouped into categories for analysis.

Exploratory Data Analysis (EDA)
The distribution of key variables is visualized using histograms, bar plots, and box plots.
The relationship between smoking status and health metrics is analyzed.

Statistical Analysis
T-tests are performed to compare mean values of health metrics between smokers and non-smokers in different age groups.
Machine Learning Model
Logistic regression is chosen as the predictive model due to its simplicity and interpretability.
Hyperparameter tuning is performed using grid search to optimize model performance.

Results
The model achieves high accuracy in predicting smoking status based on health metrics.
Evaluation metrics such as accuracy, precision, recall, and F1-score are provided.
Usage

To run the project, follow these steps:

Install the required Python packages listed in requirements.txt.
Download the dataset and place it in the appropriate directory.
Run the Jupyter Notebook or Python script to preprocess the data, perform analysis, and train the predictive model.
Dependencies
Python 3.x
pandas
numpy
matplotlib
seaborn
scikit-learn
Author
Hazem Hossam
