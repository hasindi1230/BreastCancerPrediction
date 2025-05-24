# BreastCancerPrediction

# Breast Cancer Mortality and Survival Months Prediction

This project focuses on predicting breast cancer mortality and estimating patient survival months using machine learning techniques. The analysis is divided into classification tasks (mortality prediction) and regression tasks (survival time estimation).

## Project Overview

Breast cancer remains a leading cause of mortality worldwide. This project aims to build predictive models that help estimate the likelihood of mortality and predict survival duration after diagnosis, supporting clinical decision-making and patient management.

## Description of Datasets

- `2024)5DATA002W.2_MachineLearningDataMining_Coursework_Setting_Student_Document_Revised(25012025v.6)(1).csv`  
  Original breast cancer dataset.

- `classification_dataset.csv`  
  Prepared dataset for mortality prediction (classification).

- `regression_dataset.csv`  
  Prepared dataset for survival months prediction (regression).
  
## Description of Notebooks

- **FinalNotebook1.ipynb**  
  Loads and cleans the raw dataset, performs feature engineering, and generates two separate datasets tailored for classification (mortality) and regression (survival months) tasks.

- **FinalNotebook2.ipynb**  
  Implements and evaluates various classification algorithms to predict the mortality status of breast cancer patients.

- **FinalNotebook3.ipynb**  
  Develops regression models to predict the survival duration (in months) for breast cancer patients after diagnosis.

## How to Run

- Open each notebook in the order mentioned above.
- Ensure the `data/` folder is in the same directory as the notebooks.
- Install necessary Python packages (e.g., pandas, scikit-learn, plotly.express).
