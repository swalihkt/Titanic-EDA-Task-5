# Titanic EDA Task 5

This repository contains the exploratory data analysis (EDA) on the Titanic dataset. The goal is to perform a step-by-step analysis and visualization of the dataset to understand various patterns, relationships, and trends.

## Files in this Repository:
- **Titanic_EDA.ipynb**: Jupyter notebook containing the code for the EDA process.
- **Titanic_EDA_Report.pdf**: A PDF report summarizing the findings from the EDA.
- **train.csv**: The Titanic dataset used for the analysis.
- **README.md**: This file, explaining the project and the steps involved.

## Project Steps:

### Step 1: Load the Dataset
The Titanic dataset is loaded into a pandas DataFrame for further exploration.

### Step 2: Initial Exploration
We performed some initial checks on the data using:
- **df.info()**: To check the basic structure of the dataset.
- **df.describe()**: To get a statistical summary.
- **df.isnull().sum()**: To check for missing values.

### Step 3: Visualize the Data
We used Seaborn and Matplotlib to generate visualizations:
1. **Gender Distribution**: To observe the gender distribution of passengers.
2. **Survival Rate by Gender**: To compare survival rates between male and female passengers.
3. **Age Distribution**: To see the distribution of ages among passengers.
4. **Correlation Heatmap**: To visualize the correlations between various numeric features.

### Step 4: Relationship Analysis
- **Pairplot**: Analyzed the relationship between age, fare, and passenger class, with a focus on survival.

### Step 5: Observations and Insights
The following observations were made based on the visualizations:
- **Gender Distribution**: More males than females were on board.
- **Survival Rate by Gender**: Females had a higher survival rate compared to males.
- **Age Distribution**: Most passengers were younger adults and children, with a peak in the 20–30 age range.
- **Correlation Heatmap**: Higher fares were associated with higher survival rates, and lower-class passengers had lower survival rates.

### Step 6: Summary of Findings
- **Higher survival rate for females.**
- **First-class passengers had a higher survival probability.**
- **Age had a slight correlation with survival (children survived more).**
- **Fare and Pclass showed a strong relationship, with higher fares being associated with higher class and better survival chances.**

### Step 7: Conclusion
This project provides valuable insights into the Titanic dataset. The analysis helped us identify trends in gender, age, and class, as well as how these factors contributed to survival rates. These findings can be used for further predictive modeling or decision-making regarding passenger safety measures.
