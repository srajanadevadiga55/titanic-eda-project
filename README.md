# Titanic Dataset — Exploratory Data Analysis (EDA)

## Project Overview

This project performs Exploratory Data Analysis (EDA) on the Titanic passenger dataset using Python. The goal is to understand the data, handle missing values, identify outliers, and discover patterns related to passenger survival.

## Tools and Libraries

* Python
* Pandas
* Matplotlib
* Seaborn
* Google Colab

## Dataset

The Titanic dataset contains passenger information such as age, sex, passenger class, fare, and survival status.

## Data Cleaning

* Checked for missing values and duplicate records.
* Filled missing Age values using the median.
* Filled missing Embarked values using the mode.
* Removed the Cabin column because it contained many missing values.
* Verified that no missing values remained in the cleaned dataset.

## Visualizations

The project includes:

* Survival count plot
* Correlation heatmap
* Age distribution histogram
* Fare boxplot
* Pairwise scatter plots

The visualizations are available in `visualizations.zip`.

## Key Observations

* Approximately 38.4% of passengers survived.
* The dataset contained 891 rows and 12 columns before cleaning.
* Age had 177 missing values, while Cabin had 687 missing values.
* Passenger class, fare, age, and other features can be explored to understand survival patterns.
* The fare boxplot helps identify unusually high ticket fares.

## Files

* `EDA_Project.ipynb` — Complete analysis and Python code.
* `visualizations.zip` — Exported visualization images.
* `README.md` — Project documentation.

## Conclusion

This project demonstrates the basic EDA workflow: inspecting data, cleaning missing values, analyzing numerical features, creating visualizations, and interpreting patterns in the Titanic dataset.
