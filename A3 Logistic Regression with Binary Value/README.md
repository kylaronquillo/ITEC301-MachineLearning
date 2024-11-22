# Activity 4: Logistic Regression with a Binary Outcome

## Objective
Learn how to implement a simple logistic regression model to predict whether a student passes or fails based on the number of study hours.

## Instructions

1. **Download the Dataset**
   - Download a sample dataset in CSV format with the following columns:
     - `Hours_studied`: Continuous numeric feature (e.g., from 0 to 10 hours).
     - `Pass`: Binary target variable (1 for pass, 0 for fail).  
     [Dataset Link](https://github.com/mlouwisa/ml-stash/blob/main/datasets/student_pass.csv)  
   - Alternatively, you can manually create the dataset in Jupyter.

2. **Load the Dataset**
   - Import and load the dataset into your Jupyter Notebook.
   - Name the dataset file `student_pass.csv`.

3. **Visualize the Data**
   - Visualize the dataset using an appropriate plot to observe the relationship between study hours and pass/fail outcomes.

4. **Implement Logistic Regression**
   - Write code to implement logistic regression using the dataset.

5. **Visualize the Logistic Curve**
   - Plot the logistic regression curve (sigmoid-shaped curve) using your solution.

6. **Make Predictions**
   - Implement functionality to predict the probability of passing for specific input values of study hours.

## Expected Output
Your code should be able to:
- Plot a sigmoid-shaped logistic regression curve.
- Predict probabilities of passing as study hours increase.
- Make specific predictions for given study hours.
