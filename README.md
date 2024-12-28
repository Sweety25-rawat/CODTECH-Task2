# CODTECH-Task2
# Linear Regression on Auto MPG Dataset

## Project Overview

This project demonstrates the implementation of a simple Linear Regression model using Python to predict the Miles Per Gallon (MPG) of cars based on their horsepower. The dataset used in this project is the **Auto MPG dataset**, which is a popular dataset for regression analysis in the field of machine learning.

## Dataset Information

The dataset, `auto-mpg.csv`, contains information about various car models, including attributes such as:

- MPG (Miles per Gallon) - Target variable
- Horsepower - Used as the feature for this project
- Other attributes (not used in this project) include cylinders, displacement, weight, acceleration, and model year.

## Data Preprocessing

1. **Handling Missing Values**:
   - Missing values in the dataset are represented by `?`. These are replaced with `NaN` and subsequently removed.
2. **Data Type Conversion**:
   - The `horsepower` column is converted from string to float for numerical computations.
3. **Feature and Target Selection**:
   - Feature: `horsepower`
   - Target: `mpg`

## Workflow

1. **Data Loading**:
   - The dataset is loaded from a CSV file into a Pandas DataFrame.
2. **Data Preprocessing**:
   - Missing values are handled, and necessary type conversions are performed.
3. **Exploratory Data Analysis (EDA)**:
   - Distribution of the target variable (`mpg`) is analyzed.
   - Correlation between `horsepower` and `mpg` is explored.
4. **Train-Test Split**:
   - The data is split into training (80%) and testing (20%) sets.
5. **Model Training**:
   - A Linear Regression model is trained using the `horsepower` feature to predict the `mpg` target.
6. **Model Evaluation**:
   - The model's performance is evaluated using Mean Squared Error (MSE) and R-squared (R2) score.
7. **Visualization**:
   - Training data regression line and actual vs. predicted values for test data are plotted.

## Tools & Libraries

- **pandas**: For data manipulation and preprocessing.
- **numpy**: For numerical computations.
- **matplotlib**: For data visualization.
- **sklearn** (scikit-learn): For model building, training, and evaluation.

## Model Performance

The model's performance metrics include:

- **Mean Squared Error (MSE)**: A measure of the average squared difference between actual and predicted values.
- **R-squared (R2)**: A measure of how well the model explains the variance in the target variable.

## Visualizations

### Training Data

- A scatter plot showing the relationship between horsepower and MPG, along with the regression line.

### Testing Data

- A plot comparing actual MPG values to predicted MPG values to assess model accuracy.

## File Structure

- `auto-mpg.csv`: Dataset file
- `linear_regression.py`: Python script containing the code

## Results

- The model successfully captures the inverse relationship between horsepower and MPG, showing a negative slope in the regression line.
- The R-squared value indicates how much variance in MPG is explained by horsepower alone.

## Conclusion

This project showcases the application of Linear Regression to predict car fuel efficiency using a single feature, `horsepower`. The approach is effective but limited by the use of only one predictor. While the model performs reasonably well, incorporating additional features could enhance accuracy.

## Future Work

- **Incorporate additional features**: Include variables like weight, acceleration, and displacement for better predictions.
- **Handle missing values effectively**: Use imputation techniques instead of dropping rows.
- **Experiment with advanced regression models**: Explore polynomial regression, decision trees, or neural networks.

---

Thank you for checking out the project!

