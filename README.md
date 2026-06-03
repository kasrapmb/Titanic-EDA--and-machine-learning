# Titanic EDA and Machine Learning

A data analysis and machine learning project on the Titanic dataset. This project focuses on exploring passenger information, identifying survival patterns, and building classification models to predict survival outcomes.

## Project Overview

The main objectives of this project are:

- Perform Exploratory Data Analysis (EDA)
- Visualize important patterns in the data
- Investigate relationships between features and survival
- Apply basic feature engineering techniques
- Train and evaluate multiple machine learning models
- Compare model performance

## Dataset Features

The dataset contains the following features:

| Feature | Description |
|----------|------------|
| Survived | Survival status (0 = No, 1 = Yes) |
| Pclass | Passenger class |
| Name | Passenger name |
| Sex | Gender |
| Age | Passenger age |
| Siblings/Spouses Aboard | Number of siblings/spouses aboard |
| Parents/Children Aboard | Number of parents/children aboard |
| Fare | Ticket fare |

## Exploratory Data Analysis

The analysis includes:

- Dataset inspection
- Summary statistics
- Survival distribution analysis
- Age distribution analysis
- Fare distribution analysis
- Gender-based survival analysis
- Passenger class analysis
- Correlation analysis
- Outlier detection
- Feature relationship visualization

## Feature Engineering

A new feature was created:

- *Family_Size*
  - Combines family-related features to represent the total family size of each passenger.

## Machine Learning Models

The following classification models were trained and evaluated:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- K-Nearest Neighbors (KNN)

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

## Project Structure

titanic-eda-and-machine-learning/
│
├── Titanic_EDA_ML_GitHub.ipynb
├── titanic.csv
├── README.md
└── requirements.txt

## Results

The models were evaluated using classification metrics and accuracy scores. A final comparison was performed to identify the best-performing model for the Titanic survival prediction task.

## Future Improvements

- Hyperparameter tuning
- Cross-validation
- Additional feature engineering
- Ensemble learning techniques
- Advanced model evaluation

## Author

Kasra
Computer Engineering Student
Interested in Data Science and Machine Learning
