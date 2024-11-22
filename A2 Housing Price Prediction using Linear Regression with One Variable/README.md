# Activity 3: Housing Price Prediction using Linear Regression with One Feature

## Objective
Understand how linear regression works with one variable by predicting house prices based on their sizes. This activity introduces linear regression concepts, data visualization, and simple model evaluation in Jupyter.

## Instructions

1. **Download the Dataset**
   - Download a sample dataset in CSV format containing two columns: **Size** (in square feet) and **Price** (in thousands of dollars) from this link:  
     [Sample Dataset on GitHub](https://github.com/mlouwisa/ml-stash/tree/3ebf0b20b92ddd07c649a047645226fc4895fbef/datasets)  
   - Alternatively, you can manually create one in Jupyter.

2. **Load the Dataset**
   - Import and load the dataset into your Jupyter Notebook.
   - Name the dataset file `house_prices.csv`.

3. **Visualize the Data**
   - Create a visualization of the imported dataset.
   - Display the visualized data in Jupyter.

4. **Implement Linear Regression**
   - Apply linear regression to the dataset to predict housing prices based on size.

5. **Make Predictions**
   - Input any house size value to make predictions on housing prices.

6. **Visualize the Regression Line**
   - Plot the regression line.
   - Display the regression graph and interpret the results.

## Optional Step: Evaluate Model Performance
- Evaluate the model performance using Mean Squared Error (MSE):
  ```python
  mse = mean_squared_error(y, model.predict(X))
  print(f"Mean Squared Error: {mse}")
