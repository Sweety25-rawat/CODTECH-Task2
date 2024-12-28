# CODTECH-Task2
# Predictive Modeling with Linear Regression

## Project Description
This project focuses on implementing a **simple linear regression model** using the **Auto-MPG dataset**. The objective is to predict the fuel efficiency (MPG) of cars based on the `horsepower` feature. The task involves data preprocessing, building a predictive model, evaluating its performance, and visualizing the results.

## Dataset
- **Name**: Auto-MPG Dataset
- **Source**: This dataset was used in the 1983 American Statistical Association Exposition.
- **Description**: The dataset contains information about cars, including features like `mpg`, `horsepower`, `weight`, and more.
- **Target Variable**: `mpg` (miles per gallon)
- **Feature**: `horsepower` (used for this task)

## Project Steps
1. **Data Preprocessing**:
   - Handle missing values in the dataset.
   - Convert relevant columns to numeric types.
2. **Model Implementation**:
   - Split the data into training (80%) and testing (20%) sets.
   - Train a **Linear Regression** model on the training set.
3. **Model Evaluation**:
   - Evaluate performance using **Mean Squared Error (MSE)** and **R-squared (R²)**.
4. **Visualization**:
   - Plot the regression line on training data.
   - Visualize actual vs. predicted values for the test set.

## How to Run the Code

1. **Clone the Repository**:
   ```bash
   git clone <repository_url>
   cd <repository_folder>
   ```

2. **Install Dependencies**:
   Ensure you have Python installed. Then, install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Script**:
   Execute the Python script to train the model and visualize the results:
   ```bash
   python predictive_modeling.py
   ```

## Dependencies
The following Python libraries are required:
- `pandas`
- `numpy`
- `matplotlib`
- `sklearn`

## Results
1. **Evaluation Metrics**:
   - Mean Squared Error (MSE): Evaluates the average squared difference between actual and predicted values.
   - R-squared (R²): Explains the proportion of variance in the target variable explained by the model.
2. **Visualizations**:
   - Regression Line: Displays the model's fit on training data.
   - Actual vs. Predicted: Shows the accuracy of predictions on the test set.

## License
This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Acknowledgments
The dataset used in this project was originally published as part of the 1983 American Statistical Association Exposition.

---

Feel free to raise an issue or contribute to this repository!

