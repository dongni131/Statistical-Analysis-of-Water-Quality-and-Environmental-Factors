# Water Quality Analysis Using Environmental Data

## Overview

This project analyzes environmental water quality data to understand how physical and chemical factors affect water conditions.  
The focus is on exploring relationships between **water clarity, salinity, temperature, depth, pH, and dissolved oxygen** using statistical analysis.

The project emphasizes **exploratory data analysis and regression modeling**, rather than prediction or machine learning.

---

## Dataset

The dataset contains water quality measurements collected across multiple sampling locations and depths.

Key variables include:
- Salinity
- Water temperature
- Dissolved oxygen
- pH
- Secchi depth (water clarity)
- Sampling depth

---

## Objectives

The main goals of this project are to:

- Explore patterns and distributions of water quality indicators
- Identify relationships between environmental variables
- Quantify how specific factors influence water clarity and dissolved oxygen levels
- Validate statistical model assumptions

---

## Analysis Workflow

### 1. Data Cleaning
- Removed missing and invalid observations
- Ensured consistent units and data types
- Filtered extreme outliers when necessary

### 2. Exploratory Data Analysis (EDA)
- Summary statistics of all key variables
- Scatter plots and correlation analysis
- Visualization of relationships between depth, temperature, and clarity

### 3. Statistical Modeling
- Built **linear regression models** to analyze:
  - Factors affecting **Secchi depth (water clarity)**
  - Factors affecting **dissolved oxygen**
- Evaluated model performance and interpretability

### 4. Model Diagnostics
- Residual analysis
- QQ plots for normality
- Multicollinearity checks (VIF)

---

## Key Findings

- **Water depth** is strongly associated with reduced water clarity.
- **Higher water temperatures** tend to correspond to **lower dissolved oxygen levels**.
- Salinity and pH show secondary but meaningful relationships with water quality indicators.
- Regression diagnostics indicate that linear models provide a reasonable fit for this dataset.

---

## Methods & Techniques

- Descriptive statistics
- Data visualization
- Linear regression
- Residual and diagnostic analysis
- Variance Inflation Factor (VIF)

---


## Limitations

- The analysis is observational and does not imply causation.
- Results may vary across regions, seasons, or sampling methods.
- Linear models may not capture all nonlinear relationships in environmental systems.

---

## Conclusion

This project demonstrates how statistical analysis can be used to interpret environmental data and uncover meaningful relationships in water quality indicators.  
The results can help inform environmental monitoring and water resource management efforts.

---

## Author

Dongni Li
Ziliang Song
