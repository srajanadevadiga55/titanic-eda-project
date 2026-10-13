# Titanic Dataset — Exploratory Data Analysis (EDA)

## Project Overview

This project performs Exploratory Data Analysis (EDA) on the Titanic passenger dataset to understand passenger characteristics, survival patterns, missing values, and potential outliers.

## Dataset

* **Source:** [Titanic Dataset on GitHub](https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv)
* **Original size:** 891 rows × 12 columns
* **Target variable:** `Survived`
* **Survival values:** 0 = Did not survive, 1 = Survived

## Tools and Libraries

* Python
* Pandas and NumPy
* Matplotlib and Seaborn
* Google Colab
* GitHub

## Analysis Performed

1. Loaded and inspected the dataset.
2. Checked the dataset shape, data types, summary statistics, and missing values.
3. Checked for duplicate records.
4. Handled missing values and removed the highly incomplete `Cabin` column.
5. Detected potential fare outliers using the Interquartile Range (IQR) method.
6. Created visualizations to explore survival counts, correlations, age distribution, fare outliers, and relationships between numerical variables.

## Data Cleaning

* **Age:** Filled 177 missing values using the median.
* **Embarked:** Filled 2 missing values using the mode.
* **Cabin:** Removed because 687 values (77.10%) were missing.
* **Duplicates:** No duplicate rows were detected.
* **Fare outliers:** Detected 116 potential outliers using the IQR method. They were retained because they may represent valid fares.

The cleaned dataset contains **891 rows and 11 columns**, with no missing values.

## Key Analytical Insights

* 342 passengers survived (38.4%), while 549 did not survive (61.6%).
* The dataset contains missing values in `Age`, `Cabin`, and `Embarked`.
* The fare distribution contains potential high-value outliers.
* The correlation heatmap helps explore relationships among numerical variables.
* Passenger survival patterns can be explored using passenger class, age, and fare.

These findings describe patterns in the dataset and do not establish causation.

## Visualizations

The `visualizations.zip` file contains the exported graphs:

* Survival count
* Correlation heatmap
* Age distribution
* Fare boxplot
* Pairwise scatter plots

## Files in This Repository

* `EDA_Project (1).ipynb` — Executed notebook containing the analysis, code, and visualizations.
* `visualizations.zip` — Exported visualization images.
* `README.md` — Project documentation and key findings.

## How to Run

1. Download the notebook from this repository.
2. Open [Google Colab](https://colab.research.google.com/).
3. Upload and open the notebook.
4. Run the cells from top to bottom.

## Conclusion

This EDA project demonstrates data inspection, missing-value handling, duplicate checking, IQR-based outlier detection, and visualization using Python. It provides an initial understanding of the Titanic dataset and its survival patterns.
