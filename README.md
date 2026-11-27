# Data Preprocessing & Feature Engineering

**Guided data preprocessing coursework & practical notebooks** · Python · pandas · NumPy · scikit-learn

This repository collects the exercises I practiced while learning to prepare tabular data for machine learning, including missing-value handling, outlier detection, scaling and categorical transformations.

**Scope and ownership:** These are guided learning exercises, not independent production pipelines.

## Topics and study notebooks

| Notebook | Focus |
| --- | --- |
| [Missing data visualization](missing_data_visualization.ipynb) | Missing-value patterns |
| [Quick missing data solutions](missing_data_quick_solution.ipynb) | Basic imputation methods |
| [Estimated value assignment](estimated_value_assignment.ipynb) | Legacy KNN and EM imputation |
| [Outliers](outliers.ipynb) | IQR and Local Outlier Factor |
| [Data standardization](data_standardization.ipynb) | Scaling and normalization |
| [Variable transformations](variable_transformations.ipynb) | Categorical transformations |
| [Categorical value assignment](value_assignment_for_categorical_variables.ipynb) | Categorical imputation |
| [Group-based value assignment](value_assignment_in_categorical_variable_breakdown.ipynb) | Group-based imputation |
| [Google Play Store](eda%26feature_engineering/eda%26feature_engineering.ipynb) | Data cleaning, size-unit conversion and exploratory analysis |

## Getting started

1. Create and activate a Python virtual environment.
2. Install dependencies: `python -m pip install -r requirements.txt`.
3. Open Jupyter: `python -m jupyter notebook`.
4. Run notebooks from their own directories.

### Legacy imputation exercise

The estimated-value notebook also requires `ycimpute`. It contains a temporary compatibility workaround for the removed NumPy alias `np.infty`. A separate legacy environment can be created using `requirements-legacy.txt` to avoid changing dependencies for other notebooks. The legacy dependency set is not a tested lockfile.

## Data and reproducibility

The notebooks were run locally during the cleanup using Python 3.12. Compatibility with other environments is not guaranteed. See [DATA_SOURCES.md](DATA_SOURCES.md) for dataset information and provenance limitations.
