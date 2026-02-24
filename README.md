# Data Pre-processing & Feature Engineering Repository

This repository contains comprehensive **data pre-processing** and **feature engineering** studies implemented in various data science projects. The primary goal is to transform raw data into a clean, optimized, and meaningful format for machine learning models.

Current focus: **Google Play Store Dataset** analysis and processing.

---

## 📁 Project Structure & Content

The notebooks in this project represent different stages of the data cleaning and preparation pipeline:

* **`missing_data_visualization.ipynb`**: Visualizing the density and distribution of null values.
* **`missing_data_quick_solution.ipynb`**: Fast imputation strategies (mean/median/mode) for missing values.
* **`estimated_value_assignment.ipynb`**: Model-based (predictive) imputation techniques for missing data.
* **`outliers.ipynb`**: Detection (IQR, Z-score) and handling (capping/removal) of outliers.
* **`data_standardization.ipynb`**: Feature scaling methods including StandardScaler, RobustScaler, and MinMaxScaler.
* **`variable_transformations.ipynb`**: Logarithmic transformations and normalization of data distributions.
* **`value_assignment_for_categorical_variables.ipynb`**: Label Encoding and One-Hot Encoding for categorical data.
* **`eda&feature_engineering/`**: Dataset-specific Exploratory Data Analysis and feature extraction.

---

## 🛠️ Techniques Applied

From a data scientist's perspective, the following standard operations are implemented:

1. **Missing Value Analysis:** Randomness analysis of null values and selection of appropriate imputation methods.
2. **Outlier Management:** Visual detection via Boxplots and Scatter plots; thresholding using the Interquartile Range (IQR) method.
3. **Feature Scaling:** Normalizing numerical data to improve model performance and convergence.
4. **Categorical Encoding:** Converting nominal and ordinal data into numerical formats compatible with machine learning algorithms.

---

## 🚀 Tech Stack

* **Language:** Python 3.x
* **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
* **Environment:** Jupyter Notebook (.ipynb)

---
