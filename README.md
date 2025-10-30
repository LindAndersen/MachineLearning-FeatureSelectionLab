# Machine Learning Feature Selection Lab

This repository contains a feature selection laboratory project focusing on machine learning tasks using datasets like the Pima Indians Diabetes dataset and the Titanic dataset.

## Project Structure

```
├── dataprepper-0.1.0-py3-none-any.whl
├── PL_1.ipynb
├── PL_2.ipynb
├── PL_3.ipynb
├── Datasets/
│   ├── pima-indians-diabetes.csv
│   ├── titanic_gender_submission.csv
│   ├── titanic_test.csv
│   └── titanic_train.csv
└── RESULTS_PART2/
    ├── age_fare_pclass_sex.ipynb
    ├── age_fare_pclass_ticket_sex.ipynb
    ├── age_fare_ticket_sex_embarked.ipynb
    ├── fare_pclass_embarked.ipynb
    └── fare_pclass_ticket_embarked.ipynb

```

## Installation

To install the data preparation package, run the following command in your terminal from the project directory:

```bash
pip install dataprepper-0.1.0-py3-none-any.whl
```

## Datasets

1. **Pima Indians Diabetes Dataset**: A dataset for diabetes prediction among Pima Indians.
2. **Titanic Dataset**: The famous Titanic survival dataset, split into training and test sets.

## Lab Notebooks

- `PL_1.ipynb`: Feature Selection Pima
- `PL_2.ipynb`: Data Exploration, Model training and evaluation
- `PL_3.ipynb`: Model evaluation and results analysis

## Results

The `RESULTS_PART2` directory contains various analysis notebooks exploring different feature combinations:
- Age, fare, passenger class, and sex analysis
- Additional features like ticket and embarkation port
- Various combination studies for feature importance