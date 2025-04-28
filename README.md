# ELEVATE LABS TASK 5 - Titanic Dataset Exploratory Data Analysis (EDA)

## Overview
This project focuses on performing **Exploratory Data Analysis (EDA)** on the Titanic dataset. The objective is to extract insights using various data visualization techniques and basic statistical analysis. The dataset contains information about passengers aboard the Titanic, and we aim to understand the distribution of survivors vs non-survivors and identify relationships and trends within the data.

## Project Structure
- **TASK05.ipynb**: Jupyter notebook containing the complete EDA process, visualizations, and observations.
- **Titanic_EDA_Report.pdf**: Documented report about the task performed

## Dataset
The dataset used is the **Titanic dataset** (which can be found on Kaggle) containing two columns:
- **PassengerId**: A unique identifier for each passenger.
- **Survived**: The survival status of each passenger (1 = survived, 0 = did not survive).

## Tools Used
- **Python**: Programming language used for analysis.
- **Pandas**: For data manipulation and analysis.
- **Matplotlib & Seaborn**: For data visualization.
- **Jupyter Notebook**: For interactive data analysis and visualization.

## Steps Performed
1. **Data Inspection**:
   - Used `describe()`, `info()`, and `value_counts()` to inspect the dataset and get an overview of its structure and summary statistics.
   
2. **Data Visualization**:
   - **Countplot**: Displayed the count of survivors vs non-survivors.
   - **Heatmap**: Showed correlations between columns.
   - **Histograms**: Visualized the distribution of survivors.
   - **Boxplot**: Compared the distribution of data.
   - **Pairplot**: Identified relationships between different variables (if applicable).

3. **Observations**:
   - After each visualization, observations were added to help understand trends, patterns, and anomalies in the data.

## Observations & Findings
- There are more **non-survivors** than **survivors** in the dataset, as shown by the countplot.
- The **PassengerId** column has no impact on survival status, as indicated by the heatmap.
- Further insights can be gained by including additional features like **age, class, fare**, etc., for more detailed analysis.

## How to Run the Project
1. Clone the repository to your local machine using the following command:
