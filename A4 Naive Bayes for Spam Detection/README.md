# Activity 5: Naive Bayes for Spam Detection

## Objective
The goal of this activity is to classify email messages as **Spam** or **Ham (Not Spam)** using a **Naive Bayes Classifier**.

## Instructions

### Dataset
- Download the dataset containing the following columns:
  - **Message**: The email text content.
  - **Label**: The classification of the email as `Spam` or `Ham`.
- Files to use:
  - `TrainingData.csv` for training the model.
  - `TestingData.csv` for testing and predictions.

### Steps

#### 1. Data Loading
- Import the required libraries.
- Load the training and testing datasets into your program.

#### 2. Data Preprocessing
- Use `CountVectorizer` or any other text preprocessing tool to convert email messages into numerical features.

#### 3. Implementation
- Split the dataset into training and testing sets if necessary.
- Train a **Naive Bayes Classifier** using the training data.

#### 4. Prediction
- Use the trained model to classify the emails in `TestingData.csv`.
- Save the predictions to a new CSV file.

#### 5. Visualization (Optional)
