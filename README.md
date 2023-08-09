# Data Analysis and Visualization with Matplotlib

## Table of Contents
- [Background](#background)
- [Tasks and Analysis](#tasks-and-analysis)
- [Requirements](#requirements)

## Background
In this GitHub repository, you'll find a comprehensive analysis of a real-world dataset using Matplotlib, a powerful data visualization library in Python. The dataset revolves around a pharmaceutical company, Pymaceuticals, Inc., specializing in anti-cancer medications. The focus of the analysis is on potential treatments for squamous cell carcinoma (SCC), a common form of skin cancer.

## Tasks and Analysis
The analysis is broken down into several key tasks:

### 1. Data Preparation
- Merge the provided mouse metadata and study results DataFrames into a single DataFrame.
- Identify and handle duplicate mouse IDs and time points.

### 2. Generate Summary Statistics
- Calculate mean, median, variance, standard deviation, and SEM of tumor volume for each drug regimen.
- Present summary statistics in a dedicated DataFrame.

### 3. Create Bar Charts and Pie Charts
- Create bar charts showcasing the total number of mice/timepoints per drug regimen using both Pandas and Matplotlib.
- Generate pie charts illustrating the distribution of male and female mice.

### 4. Calculate Quartiles, Find Outliers, and Create a Box Plot
- Identify the final tumor volume for specific treatment regimens (Capomulin, Ramicane, Infubinol, Ceftamin).
- Calculate quartiles, interquartile range (IQR), and detect potential outliers.
- Visualize the final tumor volume distribution using a box plot, highlighting potential outliers.

### 5. Create a Line Plot and a Scatter Plot
- Plot tumor volume versus time point for a selected mouse treated with Capomulin.
- Generate a scatter plot showing the relationship between mouse weight and average tumor volume for Capomulin regimen.

### 6. Calculate Correlation and Regression
- Calculate the correlation coefficient and perform linear regression between mouse weight and average tumor volume for Capomulin.
- Overlay the linear regression model on the scatter plot.

## Requirements
- Data Preparation: Merging datasets, handling duplicates, and obtaining clean data.
- Generate Summary Statistics: Calculating and presenting summary statistics.
- Create Bar Charts and Pie Charts: Generating bar and pie charts using Pandas and Matplotlib.
- Calculate Quartiles, Find Outliers, and Create a Box Plot: Identifying outliers and visualizing data distribution.
- Create a Line Plot and a Scatter Plot: Creating line and scatter plots for specific data comparisons.
- Calculate Correlation and Regression: Calculating correlation and performing linear regression.
