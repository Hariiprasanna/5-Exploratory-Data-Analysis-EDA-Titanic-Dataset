# 5-Exploratory-Data-Analysis-EDA-Titanic-Dataset

 **Objective**
The objective of this task is to perform Exploratory Data Analysis (EDA) on the Titanic dataset using Python, to uncover patterns, trends, and relationships within the data that may influence survival outcomes.


 **Tools & Technologies**
Python 3
Jupyter Notebook
Pandas – Data manipulation and exploration
Matplotlib & Seaborn – Data visualization


**Project Files**
Titanic_EDA.ipynb – Main Jupyter Notebook containing the entire analysis
Titanic_EDA_Report.pdf – Exported PDF summarizing the analysis and key insights
titanic.csv – Dataset used for the analysis
README.md – Project documentation


**Key EDA Steps & Methods Used**
1. Data Overview
Loaded dataset using pandas.read_csv()
Inspected structure using .info(), .shape, .head(), .describe()
Checked for missing values and data types

2. Univariate Analysis
Used .value_counts() for categorical columns
Plotted:
Histograms for continuous variables (e.g., Age, Fare)
Countplots for categorical variables (e.g., Sex, Embarked, Pclass)

3. Bivariate Analysis
Boxplots and violinplots to compare survival rate across Age, Fare, Sex
Scatterplots and pairplots to explore correlations
Heatmap to visualize feature correlations (using sns.heatmap())

4. Key Relationships Identified
Survival rate by gender (Females had higher survival)
Impact of passenger class (Pclass) on survival
Age distribution of survivors vs non-survivors
Influence of fare amount and embarked port


**Summary of Findings**
Gender and Class are strong predictors of survival.
Younger passengers and those who paid higher fares were more likely to survive.
Missing values in "Age" and "Cabin" were identified for handling in future preprocessing.
Visualizations revealed non-linear trends that could be valuable for modeling.


