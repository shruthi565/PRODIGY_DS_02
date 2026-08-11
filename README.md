# PRODIGY_DS_02 — Data Cleaning and Exploratory Data Analysis

## Task Description

Perform data cleaning and exploratory data analysis on a dataset of choice. Explore the relationships between variables and identify patterns and trends in the data.

## Dataset

For this task, the Titanic dataset was selected. The dataset contains information about passengers who travelled on the Titanic, including age, gender, passenger class, fare, family information, embarkation port, and survival status.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook / Google Colab

## Work Performed

### Data Cleaning

* Loaded the Titanic dataset.
* Inspected the dataset structure.
* Checked for missing values.
* Handled missing Age values using the median.
* Handled missing Embarked values using the mode.
* Checked and removed duplicate records.
* Converted categorical columns into appropriate data types.

### Exploratory Data Analysis

The following relationships were explored:

* Survival distribution
* Survival by gender
* Survival by passenger class
* Age distribution
* Age and survival
* Fare distribution
* Fare and survival
* Survival by embarkation port
* Family size and survival
* Travelling alone and survival
* Gender and passenger class
* Correlation between numerical variables

## Key Findings

* Female passengers had a higher survival rate than male passengers.
* First-class passengers generally had a higher survival rate.
* Higher fares were generally associated with better survival outcomes.
* Age showed some relationship with survival, but it was not the only determining factor.
* Family size showed different survival patterns.
* Multiple passenger characteristics were associated with survival.

## Conclusion

The Titanic dataset was successfully cleaned and analyzed using Python. Exploratory data analysis helped identify important relationships between passenger characteristics and survival. Data visualization made it easier to understand patterns and trends within the dataset.

## Files

* `Task-02_Titanic_EDA.ipynb` — Complete analysis notebook
* `cleaned_titanic_dataset.csv` — Cleaned dataset
* `README.md` — Project documentation
