# MSCS 634 - Lab 1: Data Visualization and Statistical Analysis

**Name:** Milan Bista  
**Course:** MSCS 634 – Data Science Tools  
**Assignment:** Lab 1 – Data Visualization, Preprocessing & Analysis in Jupyter Notebook

---

## 📘 Overview

This lab demonstrates how to apply key data science techniques including:

- Data visualization  
- Data preprocessing  
- Statistical analysis  

Using **Jupyter Notebook**, I explored a real-world dataset, cleaned it, visualized key patterns, and analyzed statistical properties. This process reflects a common workflow used in data-driven decision-making.

---

##  Dataset

The dataset used in this lab was collected from Kaggle. This lab analyzes Sleep Health and Lifestyle Dataset patterns using data visualization, preprocessing, and statistical analysis techniques.


---

## Folder Structure
 -- src
        --lab1.ipynb
 -- sleepHealthAndLifestyle.csv
 -- screenshots


##  Key Visualizations

1. **Scatter Plot**  
   Used to visualize the relationship between two numeric variables. It helped identify correlation trends.

2. **Pie Chart**  
   Showed the distribution of sleep disorders. Found that 58% of individuals reported no sleep disorder, while 20% had insomnia and 20% had sleep apnea.

3. **Histogram and Box Plot**  
   Revealed the distribution and spread of numerical columns, helping to detect skewness and outliers.

---

## Data Preprocessing

- **Missing Values:**  
  Handled using mean replacement and row dropping.

- **Outliers:**  
  Detected using the IQR method and removed to avoid skewed results.

- **Data Reduction:**  
  Dropped less relevant columns and sampled the dataset to simplify analysis.

- **Scaling:**  
  Applied Min-Max Scaling and Z-score standardization to normalize data ranges.

---

## Statistical Analysis

- **General Info:**  
  `.info()` and `.describe()` provided a summary of dataset structure and descriptive statistics.

- **Central Tendency Measures:**  
  Calculated mean, median, and mode for key columns.

- **Dispersion Measures:**  
  Computed standard deviation, variance, range, and IQR.

- **Correlation Matrix:**  
  A heatmap visualized relationships between numerical columns, highlighting strong and weak correlations.

---

## Challenges & Decisions

- Some columns such as `'Person ID'` were dropped from correlation analysis due to irrelevance.
- Missing values were not prevalent in columns

---


