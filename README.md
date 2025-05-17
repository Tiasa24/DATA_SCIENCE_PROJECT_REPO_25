# DATA_SCIENCE_PROJECT_REPO_25
Project Title:
Predictive Modeling of Sign Language Acquisition in Children

Objective:
To identify cognitive and demographic factors that influence the pace of sign language acquisition in children, using real-world session data.

Dataset:

Source: ASL-Play dataset from Databrary (https://osf.io/3w8ka/files/osfstorage)

Collected by: NYU Infant Action Lab (Karen Adolph et al.)

Structure:

24 families

Two sessions per family

Each session stored as a separate CSV file

Additional demographics file with child and caregiver information

Data Management:

Organize data by sessions and family ID

Merge session files and align with demographics

Clean and standardize column formats

Extract features such as number of signs, time between signs, session length, and child age

Modeling Approach:

Regression-based prediction of sign acquisition pace

Models considered: Linear Regression, Random Forest Regressor

Evaluation metrics: RMSE, MAE, R² Score

Feature importance analysis included

Data Type:
Tabular data including categorical, continuous, and time-based variables

Version Control:

Code and notebooks tracked using Git

Data used in read-only mode

All changes documented in GitHub repository

Timeline Overview:

Weeks 1–2: Dataset review and preprocessing

Weeks 3–4: Feature engineering and EDA

Weeks 5–6: Model training and evaluation

Week 7: Final analysis, write-up, and submission
