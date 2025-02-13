Salary Prediction (Regression Problem)

Overview

This project demonstrates a simple Salary Prediction model using Linear Regression. The dataset contains information on employees' years of experience and their corresponding salaries. The goal is to train a model that can predict salary based on experience.

Dataset

The dataset (Salary.csv) consists of two columns:

YearsExperience: Number of years of experience of an employee.

Salary: Corresponding salary of the employee.

The dataset contains 35 observations.

Dependencies

To run this project, you need the following Python libraries:

pip install pandas numpy matplotlib seaborn scikit-learn

Steps Involved

Import Required Libraries:

Pandas, NumPy, Matplotlib, Seaborn, and Scikit-learn.

Load and Explore Data:

Check for missing values, data types, and statistical summary.

Visualize data using scatter plots.

Prepare Data:

Split the data into training and testing sets.

Train the Model:

Use Linear Regression from sklearn.linear_model.

Test the Model:

Predict salary values for test data.

Compare actual vs predicted values.

Visualize Results:

Plot regression lines on training and testing data.

Evaluate Model:

Calculate R-squared score and RMSE.

Make Custom Predictions:

Predict salary for a given experience value.

Model Performance

R-squared score: 0.9786

Root Mean Squared Error (RMSE): 3939.85

Usage

Run the script using:

python salary_prediction.py

To predict salary for a custom experience value:

exp = 5
predicted_salary = lr.predict([[exp]])[0]
print(f"Salary of {exp} year experience employee = {int(predicted_salary)} thousands")

Results

The model accurately predicts salaries based on years of experience with a high R-squared score.

The regression line visually fits the data well.

Future Enhancements

Implement polynomial regression for better predictions.

Try feature engineering by adding additional parameters.

Improve model performance using different ML algorithms.

Author

Developed by [Your Name]

License

This project is open-source and available under the MIT License.
