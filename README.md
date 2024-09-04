# Python_Projects_Cradit_Card_Fraud_Detection(Logistic Regression Model for Fraud Detection)

# This is my 2nd python progect where i build a......
## Logistic Regression Model for Fraud Detection
This Python script uses logistic regression to detect fraudulent transactions based on a mock dataset. It leverages the `pandas` library for data manipulation and `scikit-learn` for model training and evaluation.

### Features

- Data Handling: Utilizes `pandas` to create and manage the dataset.
- Model Training: Uses `scikit-learn` to split the data into training and testing sets, and to train a logistic regression model.
- Evaluation Metrics: Calculates and prints accuracy, precision, recall, F1 score, and the confusion matrix to evaluate the model's performance.

### Usage

1. Ensure you have the required libraries installed: `pandas` and `scikit-learn`.
2. Run the script to train the logistic regression model on the mock dataset.
3. The script will output the model's performance metrics, including accuracy, precision, recall, F1 score, and the confusion matrix.

### Example
Accuracy: 0.75
Precision: 0.8
Recall: 0.6666666666666666
F1 Score: 0.7272727272727272
Confusion Matrix:
[[2 1]
 [1 2]]

### Dependencies
- `pandas`
- `scikit-learn`

### How It Works
1. Data Preparation: A mock dataset is created with transaction amounts, merchant categories, time of day, and fraud labels.
2. Feature Selection: The features (`transaction_amount`, `merchant_category`, `time_of_day`) are selected for training.
3. Model Training: The dataset is split into training and testing sets. A logistic regression model is trained on the training set.
4. Model Evaluation: The model's predictions on the test set are evaluated using various metrics.
