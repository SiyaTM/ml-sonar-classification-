# Machine Learning Models for Sonar Object Classification

This repository contains Python code for implementing and evaluating three machine learning models—Logistic Regression, Support Vector Machine (SVM), and Random Forest—on a dataset for sonar object classification.

## Overview

### Dataset
The dataset used for this project contains sonar signals, and the task is to classify objects as either rocks (R) or mines (M).

### Models Implemented

1. **Logistic Regression:**
   - A linear model suitable for binary classification problems.
   - Utilizes the logistic function to model the probability of an instance belonging to a specific class.

2. **Support Vector Machine (SVM):**
   - Effective in high-dimensional spaces and capable of handling complex decision boundaries.
   - Considerations include feature scaling, handling imbalanced data with class weights, and hyperparameter tuning using Grid Search.

3. **Random Forest:**
   - Ensemble learning method that builds multiple decision trees and combines their predictions.
   - Address considerations such as feature scaling, handling imbalanced data with class weights, and hyperparameter tuning using Grid Search.

## Code Structure

1. **Logistic Regression:**
   - File: `logistic_regression.py`
   - Data preprocessing includes loading the dataset, exploring statistical measures, and separating features and labels.
   - Splits the data into training and test sets.
   - Trains a Logistic Regression model and evaluates its performance on both training and test sets.
   - Demonstrates making predictions for new data.

2. **Support Vector Machine (SVM):**
   - File: `support_vector_machine.py`
   - Extends the considerations for SVM, including feature scaling, handling imbalanced data with class weights, and hyperparameter tuning using Grid Search.
   - Trains an SVM model and evaluates its performance on training and test sets.
   - Demonstrates making predictions for new data.

3. **Random Forest:**
   - File: `random_forest.py`
   - Incorporates considerations such as feature scaling, handling imbalanced data with class weights, and hyperparameter tuning using Grid Search.
   - Trains a Random Forest model and evaluates its performance on training and test sets.
   - Demonstrates making predictions for new data.

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/sonar-object-classification.git
   cd sonar-object-classification
   ```

2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the desired model script:

   - For Logistic Regression:

     ```bash
     python logistic_regression.py
     ```

   - For Support Vector Machine:

     ```bash
     python support_vector_machine.py
     ```

   - For Random Forest:

     ```bash
     python random_forest.py
     ```

## Results and Further Improvements

- Evaluate and compare the accuracy of each model on the provided dataset.
- Consider additional model evaluation metrics (precision, recall, F1-score) for a comprehensive analysis.
- Experiment with different hyperparameters or algorithms to further improve model performance.

Feel free to explore and modify the code based on your specific requirements and data characteristics. If you have any questions or suggestions, please feel free to reach out.

Happy coding!
