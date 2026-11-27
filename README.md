# Data Preprocessing & Feature Engineering

Course-based exercises and exploratory notebooks covering tabular data preparation in Python. These are study materials, not production pipelines or independently designed projects.

| Notebook | Focus |
| --- | --- |
| `missing_data_visualization.ipynb` | Missing-value visualization |
| `missing_data_quick_solution.ipynb` | Mean, median and other imputation examples |
| `estimated_value_assignment.ipynb` | Legacy KNN and EM imputation exercises |
| `outliers.ipynb` | IQR and Local Outlier Factor |
| `data_standardization.ipynb` | Scaling and normalization examples |
| `variable_transformations.ipynb` | Categorical transformations |
| `value_assignment_for_categorical_variables.ipynb` | Categorical imputation |
| `value_assignment_in_categorical_variable_breakdown.ipynb` | Group-based imputation |
| `eda&feature_engineering/` | Google Play Store cleaning and exploratory analysis |

## Run locally

Create a virtual environment, install `python -m pip install -r requirements.txt`, then open Jupyter with `python -m jupyter notebook`. Run the notebooks from their own folders. For the legacy `ycimpute` exercise, use a separate compatible environment (Python 3.11 suggested) and `requirements-legacy.txt`; dependency compatibility has not been tested.

## Data and limitations

See [DATA_SOURCES.md](DATA_SOURCES.md). Edited notebooks have cleared outputs and need to be rerun. The original course exercises are preserved except for targeted corrections. The dependency files are not verified lockfiles; no execution or production validation is claimed.
