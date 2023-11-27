**Titanic Survival Prediction**

**Overview**

This repository hosts a machine learning script designed to predict survival on the Titanic. The script follows a systematic workflow, encompassing data loading, analysis, visualization, handling missing values, categorical column encoding, model training (Logistic Regression), and model evaluation.

**Logic**
**1. Data Loading**: The script loads the Titanic dataset from a CSV file. Ensure the dataset is uploaded to your Colab environment or adjust the file path accordingly.
**2. Data Analysis and Visualization**:

* Provides basic information about the dataset.
* Checks for missing values.
* Utilizes Seaborn for data analysis and visualization.
Handling Missing Values:

Drops the "Cabin" column.
Fills missing values in the "Age" column with the mean.
Fills missing values in the "Embarked" column with the mode.
Encoding Categorical Columns:

Converts categorical columns like "Sex" and "Embarked" into numerical values.
Model Training:

Utilizes Logistic Regression for training.
Model Evaluation:

Calculates accuracy scores on both training and test datasets.
Tech Stack
Python
Libraries: NumPy, Pandas, Matplotlib, Seaborn, scikit-learn
