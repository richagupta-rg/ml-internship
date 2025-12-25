# Task 1: Data Preprocessing – House Price Prediction

## Objective
The goal of this task is to perform data preprocessing on a house price dataset.
This includes data loading, inspection, cleaning, feature-target separation, and
preparing the data for machine learning models.

---

## Dataset
- Dataset: House Price Prediction
- File: `data/house_prediction.csv`
- Target variable: `PRICE`

---

## Steps Performed
1. Loaded the dataset using Pandas
2. Checked dataset shape and structure
3. Assigned meaningful column names
4. Handled missing values (if any)
5. Separated features (X) and target variable (y)
6. Performed train-test split
7. Standardized numerical features

---

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
---

## How to Run
```bash
git clone https://github.com/richagupta-rg/ml-internship.git
cd ml-internship
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
