# Here are the contents you can find in these notes.

## Pandas - Table of contents

1. Data Loading and Inspection
    * 1.1 Displaying Data Frames
    * 1.2 Data Inspection and Exploration
        * shape of the data
        * Info of the Data
        * Basic Statistics of the data
        * Accessing Columns
        * Finding no.of unique values from each column
        * Finding the count of unique values from each column
        * Finding stats for a specific column

2. Data Selection and Indexing
    * 2.1 Selecting Columns and Rows
        * Using squared brackets [ ]:
        * Using .loc[] for Label-Based Selection
        * Using .iloc[] for Integer-Based Selection
    * 2.2 Indexing Methods
        * Setting Index

3. Data Cleaning
    * 3.1 Handling Missing Data
        * Check Missing Data in a Column
        * To Find the count of missing values in each column
        * Filling the missing Data using fillna
        * Drop Rows or columns with missing data using dropna
    * 3.2 Handing Duplicates
        * Finding Duplicates using .duplicated
        * Drop the duplicated rows using .drop_duplicates
    * 3.3 String Operations
    * 3.4 Data Type Conversion
4. Data Manipulation
    * 4.1 Applying Functions to DataFrames
        * .apply for series and DataFrames
        * .map for series
        * .applymap for entire dataframe
    * 4.2 Adding and Removing Columns
    * 4.3 Combining DataFrames
        * Concatenation of DataFrames
        * Merging using inner join
        * Merging using left join
        * Merging one df column with other df index
5. Data Aggregation
    * 5.1 Grouping Data
        * Group with a single column using groupby method.
        * Group with single column and apply to entire Dataframe.
        * Group with multiple columns
    * 5.2 Aggregate Functions
        * Apply multiple aggregate functions to the grouped data.
        * Apply multiple aggregate functions for selected columns.
    * 5.3 Pivot Tables and Cross-Tabulations
6. Data Visualizations
    * 6.1 Find the Correlations
    * 6.2 Sorting Data and Creating Plots
        * Sorting Data
        * Creating Plots
7. Time Series Data Handling
    * 7.1 Working with DateTime Data
    * 7.2 Resampling and Shifting
        * Resampling
        * Shifting
    * 7.3 Rolling Statistics
8. Handling Categorical Data
    * 8.1 Encoding Categorical Variables
        * One-Hot Encoding using pd.get_dummies
        * Label Encoding using Category type
    * 8.2 Sorting Ordinal Data
9. Advanced Topics
    * 9.1 Multi-Indexing
    * 9.2 Handling Outliers
        * Identifying Outliers
        * Outlier Handling by NaN
        * Outlier Handling by Clip Values
10. Memory Optimization

Know more in the Notes - [Click Here](https://github.com/ds-teja/100_Days_MLDL/blob/main/Compiled%20Notes%20by%20Me/00%20-%20Pandas_Complete_Guide.pdf)

---
## Numpy - Table Of Contents

1. Numpy Array Basics
    * 1.1 Creating Numpy Arrays
2. Array Inspection
    * 2.1 Array Dimension and Shapes
    * 2.2 Array Indexing and Slicing
3. Array Operations
    * 3.1 Element-wise Operations
    * 3.2 Append and Delete
    * 3.3 Aggregation Functions and ufuncs
4. Working with Numpy Arrays
    * 4.1 Combining Arrays
    * 4.2 Splitting Arrays
    * 4.3 Alias vs. View vs. Copy of Arrays
    * 4.4 Sorting Numpy Arrays
5. Numpy for Data Cleaning
    * 5.1 Identify Missing Values
    * 5.2 Removing rows or columns with Missing Values
6. Numpy for Statistical Analysis
    * 6.1 Data Transformation
    * 6.2 Random Sampling and Generation
7. Numpy for Linear Algebra
    * 7.1 Complex Matrix Operations
    * 7.2 Solve Linear Equations
8. Advanced Numpy Techniques
    * 8.1 Masked Arrays
    * 8.2 Structured Arrays Conclusion

Know More from the Notes - [Click Here](https://github.com/ds-teja/100_Days_MLDL/blob/main/Compiled%20Notes%20by%20Me/01-%20Numpy_Complete_Guide.pdf)

---
## Matplotlib - Table Of Contents
1. Basic Plotting
    * 1.1 Creating Simple Line Plots
    * 1.2 Customization options for labels, colors, and styles
    * 1.3 Saving Matplotlib plots as image files
2. Plot Types 
    * 2.1 Bar Chart
    * 2.2 Histograms
    * 2.3 Scatter plots
    * 2.4 Pie Charts
    * 2.5 Box Plot (Box and Whisker Plot)
    * 2.6 Heatmap, and Displaying Images 2.7 Stack Plot
3. Multiple Subplots
    * 3.1 Creating Multiple Plots in a Single Figure 
    * 3.2 Combining Different Types of Plots
4. Advanced Features
    * 4.1 Adding annotations and text
    * 4.2 Fill the Area Between Plots
    * 4.3 Plotting Time Series Data
    * 4.4 Creating 3D Plots
    * 4.5 Live Plot Incorporating Animations and Interactivity.

---
## Seaborn - Table of Contents
1. Seaborn Introduction
2. Categorical Plots
    * 2.1 Count Plot
    * 2.2 Swarm Plot
    * 2.3 Point Plot
    * 2.4 Categorical Box Plot
    * 2.5 Categorical Violin Plot
    * 2.6 Cat Plot
3. Univariate Plots
    * 3.1 KDE Plot
    * 3.2 Rug Plot
    * 3.3 Dist Plot
    * 3.4 Box Plot & Violin Plot
    * 3.5 Strip Plot
4. Bivariate Plots
    * 4.1 Regression Plot
    * 4.2 Joint Plot
    * 4.3 Hexbin Plot
5. Multivariate Plots
    * 5.1 Using Parameters
    * 5.2 Relational Plot
    * 5.3 Facet Grid
    * 5.4 Pair Plot
    * 5.5 Pair Grid
6. Matrix Plots
    * 6.1 Heatmap
    * 6.2 Cluser Map

---
## Plotly - Table of Contents
1. Important Plotly Modules
    * 1.1 Plotly Express
    * 1.2 Plotly graph objects
2. Basic Plots
    * 2.1 Line Plots
    * 2.2 Bar Plots
    * 2.3 Scatter Plots
    * 2.4 Pie Charts 
    * 2.5 Histograms
3. Advanced Plots
    * 3.1 Box Plot
    * 3.2 Violin Plot
    * 3.3 Density Heatmap 
    * 3.4 3D Plots
    * 3.5 Scatter Matrix
    * 3.6 Facet Grid
    * 3.7 Animated Plots

---

## EDA on Loan Defaulter Dataset

1. Inspecting the data
2. Handling Missing Values
3. Feature Engineering of Numeric Columns
4. Feature Engineering of Cat Columns
5. Data Visualization of Numeric Columns
6. Data Visualization of Cat Columns
7. Final Observations

---

## Inferential Statistics

1. Understanding Normal Distribution
2. Understanding Estimation Theory
3. Understanding Central Limit Theorm
4. Understanding p-value
5. Z-Test
6. T-Test
7. Chi-square test
8. F-Test
9. ANOVA
10. Solving Problems for these.

---
## Exploring Scikit-learn Features

1. Creating Train, Test Data
2. Creating a Model
3. Evaluating a Model
4. Understanding Cross Validation
5. Understanding Evaluation Metrics
4. Comparing different Models

---
## Complete Feature Engineering

1. Handling Missing values
    * 1.1 Problems of Having Missing values
    * 1.2 Understanding Types of Missing Values
    * 1.3 Dealing MV Using SimpleImputer Method
    * 1.4 Dealing MV Using KNN Imputer Method
2. Handling Categorical Values
    * 2.1 One Hot Encoding
    * 2.2 Label Encoding
    * 2.3 Ordinal Encoding
    * 2.4 Multi Label Binarizer
    * 2.5 Count/Frequency Encoding
    * 2.6 Target Guided Ordinal Encoding
3. Feature Scaling
    * 3.1 Standardization/Standard Scaler
    * 3.2 Normalization/MinMax Scaler
    * 3.3 Max Abs Scaler
    * 3.4 Robust Scaler
4. Feature Selection
    * 4.1 why Feature Selection Matters
    * 4.2 Types of Feature Selection
    * 4.3 Filter Methods
        * Variance Threshold
        * SelectKBest
        * SelectPercentile
        * GenericUnivariateSelect
    * 4.4 Wrapper Methods
        * RFE
        * RFECV
        * SelectFromModel
        * SequentialFeatureSelector
5. Feature Transformation
    * Undestanding QQPlot and PP-Plot
    * logarithmic transformation
    * reciprocal transformation
    * square root transformation
    * exponential transformation
    * boxcox transformation
6. Using Column Transformer to speed up FE
7. Using Pipelines to automate the FE
    * What are Pipelines
    * Accessing individual steps in pipeline
    * Accessing Parameters in Pipeline
    * Performing Grid Search with Pipeline
    * Combining Transformers and Pipeline
    * Visualizing the Pipeline

---

## Understanding Machine Learning Algorithms

1. What is Machine Learning?
2. What are the Types of Machine Learning?
3. Supervised Machine Learning
4. Unsupervised Machine Learning
5. Reinforcement Learning
6. Semi-Supervised Learning
7. Steps in ML Project
8. Exploring Step 1 Data Collection
9. Exploring Step 2 Data Preparation
    - Exploratory Data Analysis
    - Data Preprocessing
    - Feature Engineering 
10.Exploring Step 3 - Train Model on Dataset
    - Types of Learning
    - Under Fitting and OverFitting
    - Regularization techniques
    - Hyperparameter Tuning
11. Exploring Step 4 - Evaluation of a Model
    - Evaluation Metrics
    - Confusion Matrix
    - Recall/Sensitivity
    - Precision
    - Specificity
    - F1 Score
    - AUC and ROC Curve
    - Analysis of a Model
12. Supervised Learning
    - Linear Regression
    - Regularization Techniques
    - Logistic Regression
    - Decision Trees
    - Ensemble Techniques
    - Random Forests
    - AdaBoost
    - Gradient Boost
    - XG Boost
    - K-Nearest Neighbours
    - Support Vector Machines
- Naive Bayes Classifiers
13. Unsupervised Learning
    - Clustering Techniques
    - K-Means Clustering
    - Hierarchical Clustering
    - DB Scan Clustering
    - Evaluation of Clustering Models
    - Curse of Dimensionality
    - Principal Component Analysis
14. Cheat Sheet of Supervised and Unsupervised Algorithms

---

## Big Mart Sales Prediction Project

1. Inspecting the Data
2. Data visualization of Numeric Columns
3. Feature Engineering of Numeric Columns
4. Data Visualization of Cat Columns
5. Feautre Engineering of Cat Columns
6. Model Building 
7. Simple Linear Regression
8. Applying Regularization Techniques
9. Boosting Regressors
10. Hyperparameter Tuning the Models

---

