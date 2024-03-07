# PRODIGY_DS_02

# Titanic Dataset Analysis

This project performs exploratory data analysis (EDA) on the Titanic dataset. The dataset includes information about passengers such as Pclass, Name, Sex, Age, SibSp, Parch, Ticket, Fare, Cabin, and Embarked.

# Data Preprocessing

## Handling Missing Values:

1. Impute missing 'Age' values using the median.
2. Fill missing 'Fare' values with the median.
3. ...

## Feature Engineering:

1. Extract titles from 'Name' and map them to numerical values.
2. Create a new feature 'FamilySize' combining 'SibSp' and 'Parch'.
3. ...

## Categorical Encoding:

1. Convert categorical variables like 'Sex' into numerical values.
2. One-hot encode categorical variables if needed.

# Exploratory Data Analysis (EDA)

## Descriptive Statistics:

- Overview of statistical measures for numerical features.

## Visualization:

- Histograms for 'Survived', 'Fare', etc.
- Bar plots for 'Pclass', 'Sex', etc.
- Box plots for 'Age' distribution by 'Pclass'.


## Setup

Make sure you have the required Python libraries installed:

```bash
pip install pandas scikit-learn matplotlib seaborn plotly
