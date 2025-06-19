# Heart Disease Prediction Project

A machine learning project to predict heart disease using various classification models based on UCI Heart Disease dataset.

## Dataset

The project uses heart disease data from four different locations:

1. Cleveland Clinic Foundation
2. Hungarian Institute of Cardiology, Budapest
3. V.A. Medical Center, Long Beach, CA
4. University Hospital, Zurich, Switzerland

The dataset contains 14 key attributes used for prediction.

## Project Structure

```
├── data/
│   ├── heart_disease_uci_imputed.csv    # Cleaned dataset with imputed values
│   └── heart_disease_uci_new.csv        # Processed dataset
├── notebooks/
│   ├── 01_heart_diseas_project_day_01_missing_values_imputation.ipynb
│   ├── 01_heart_diseas_project_day_02_removing_outliers.ipynb
│   ├── 02_instructor_function_to_imputer_null_values.ipynb
│   └── 02_My_function_to_imputer_null_values.ipynb
└── best_model_for_heart_diseas_prediction.pkl  # Saved best model
```

## Project Steps

1. **Data Preprocessing**

   - Missing value imputation
   - Outlier removal
   - Feature encoding using LabelEncoder
   - Train-test split (70-30)

2. **Model Training and Evaluation**
   - Multiple classification models tested
   - Cross-validation performed
   - Models evaluated using accuracy metric
   - Best performing model saved

## Model Improvements

Potential ways to improve model accuracy:

1. Feature Engineering
2. Feature Selection (reducing from 14 to fewer features)
3. Data Pre-processing (Scaling and Normalization)
4. Hyperparameter Tuning

## Usage

To use the saved model:

```python
import pickle

# Load the model
model = pickle.load(open("best_model_for_heart_diseas_prediction.pkl", "rb"))

# Make predictions
predictions =
```
