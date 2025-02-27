# Salary Prediction Model

## Steps Involved

### 1. Import Required Libraries
- **Pandas**: For data manipulation.
- **NumPy**: For numerical operations.
- **Matplotlib & Seaborn**: For data visualization.
- **Scikit-learn**: For building the regression model.

### 2. Load and Explore Data
- Check for missing values, data types, and statistical summary.
- Visualize data using scatter plots.

### 3. Prepare Data
- Split the data into training and testing sets.

### 4. Train the Model
- Use **Linear Regression** from `sklearn.linear_model`.

### 5. Test the Model
- Predict salary values for test data.
- Compare actual vs predicted values.

### 6. Visualize Results
- Plot regression lines on training and testing data.

### 7. Evaluate Model
- Calculate **R-squared score** and **RMSE**.

### 8. Make Custom Predictions
- Predict salary for a given experience value.

---

## Model Performance
- **R-squared score**: `0.9786`
- **Root Mean Squared Error (RMSE)**: `3939.85`

---

## Usage
Run the script using:

```bash
python salary_prediction.py
```

To predict salary for a custom experience value:

```python
exp = 5
predicted_salary = lr.predict([[exp]])[0]
print(f"Salary of {exp} year experience employee = {int(predicted_salary)} thousands")
```

---

## Results
- The model accurately predicts salaries based on years of experience with a high **R-squared score**.
- The regression line visually fits the data well.

---

## Future Enhancements
- Implement **polynomial regression** for better predictions.
- Try **feature engineering** by adding additional parameters.
- Improve model performance using different ML algorithms.

---

## Author
Developed by **[Manda Pavan Kalyan]**

---

