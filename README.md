# Diabetes Prediction Using Machine Learning

## About the Project

This project uses Machine Learning to predict the diabetes outcome based on diagnostic measurements from the Pima Indians Diabetes Dataset.

The goal is to understand the fundamental steps of building a classification model, including data analysis, preprocessing, model training, and evaluation.

## Technologies Used

* **Python**
* **Pandas** — Data loading and analysis
* **NumPy** — Numerical operations
* **Matplotlib** — Data visualization
* **Scikit-learn** — Data preprocessing, model training, and evaluation
* **Jupyter Notebook** — Interactive development and experimentation

## Machine Learning Algorithm

A **Support Vector Machine (SVM)** classifier with a linear kernel is used to predict the outcome.

## Project Workflow

1. Load the dataset using Pandas.
2. Explore the data using methods such as `head()`, `shape`, and `describe()`.
3. Separate the input features (`X`) from the target variable (`Outcome`).
4. Split the dataset into training and testing sets.
5. Standardize the numerical features using `StandardScaler`.
6. Train the SVM classification model.
7. Generate predictions for the training and testing datasets.
8. Evaluate the model using accuracy.

## Dataset

The project uses the Pima Indians Diabetes Dataset.

The dataset contains **768 records and 9 columns**, including diagnostic measurements and the target variable, `Outcome`.

* `Outcome = 0`: Diabetes-negative class
* `Outcome = 1`: Diabetes-positive class

## Initial Results

| Evaluation        | Accuracy |
| ----------------- | -------: |
| Training accuracy |   78.66% |
| Testing accuracy  |   77.27% |

These are preliminary results from the current implementation. The preprocessing workflow and model evaluation can be improved further.

## Future Improvements

* Prevent data leakage by fitting the scaler only on training data.
* Evaluate the model using a confusion matrix, precision, recall, and F1-score.
* Explore other classification algorithms.
* Improve model performance through validation and hyperparameter tuning.
* Add data visualizations and further exploratory data analysis.

## Disclaimer

This project is for educational purposes only. Its predictions are not intended for medical diagnosis or treatment decisions.

## Author

**Tejas BV**

GitHub: [@tejasbv46](https://github.com/tejasbv46)
