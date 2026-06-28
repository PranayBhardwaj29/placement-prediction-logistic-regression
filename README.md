# Placement Prediction — Logistic Regression

A simple end-to-end machine learning pipeline that predicts whether a student will be placed (hired) based on their **CGPA** and **IQ** scores, using Logistic Regression.

## Overview

This project walks through a complete, beginner-friendly ML workflow:

1. **Load & explore data** — read the dataset and inspect its shape and structure
2. **Visualize** — scatter plot of CGPA vs IQ, colored by placement outcome
3. **Train/test split** — 90/10 split of the data
4. **Feature scaling** — standardize features using `StandardScaler`
5. **Model training** — fit a `LogisticRegression` classifier
6. **Evaluation** — measure accuracy on the test set
7. **Decision boundary visualization** — plot the model's decision regions using `mlxtend`

## Dataset

The notebook expects a CSV file named `placement.csv` with the following columns:

| Column      | Description                          |
|-------------|---------------------------------------|
| cgpa      | Student's CGPA                        |
| iq        | Student's IQ score                    |
| placement`| Target label (1 = placed, 0 = not placed) |

## Project Structure

.
├── end_to_end_ml.ipynb   # Main notebook with the full pipeline
├── placement.csv         # The data used
└── README.md


## Results

The model is evaluated using accuracy score on the held-out test set. Exact results will vary depending on the random train/test split.

## Tech Stack

- Python
- NumPy / Pandas
- Matplotlib
- scikit-learn
