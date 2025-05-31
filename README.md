# Titanic_Survial-Prediction

Predicting passenger survival on the Titanic using logistic regression. This was built as a basic machine learning project using the Kaggle Titanic dataset.

## About the Project

The goal was to build a simple, interpretable model to classify whether a passenger survived or not. Logistic regression was used as the baseline model. After cleaning the data and doing a bit of feature engineering (like family size), the model achieved ~78% accuracy on the validation set.

## What’s in it

- Logistic Regression model
- Basic EDA using Seaborn/Matplotlib
- Handling missing data
- One-hot encoding for categorical variables
- Final predictions written to `submission.csv` (Kaggle-ready)

## Tech Stack

- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- scikit-learn

## Notes

Not a complex model — just something to get comfortable with the ML workflow: cleaning, training, evaluating, and predicting. Could definitely be improved with feature extraction (e.g., titles from names) or trying tree-based models later.

## License

Do whatever you want with it.
