# Linear Regression: Salary Prediction

This project demonstrates a simple **Linear Regression model** to predict employee salary based on years of experience.

---

## Dataset
The dataset used contains:
- **YearsExperience** : Independent variable (Feature)
- **Salary** : Dependent variable (Target)

---

## Objective
To build a regression model that learns the relationship between experience and salary and predicts future salaries accurately.

---

##  Technologies Used
- Python 
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

## Project Workflow

### 1. Import Libraries
Essential libraries for data handling, visualization, and modeling.

### 2. Load Dataset
The dataset is loaded using Pandas.

### 3. Understand Data
Exploratory steps:
- View first and last rows
- Check data types and summary statistics

### 4. Check Missing Values
Ensures dataset has no null values.

### 5. Data Visualization
Scatter plot used to visualize relationship between experience and salary.

### 6. Feature Selection
- **X** = Years of Experience  
- **Y** = Salary

### 7. Train-Test Split
Dataset split into:
- 80% training data
- 20% testing data

### 8. Model Selection
Linear Regression model from Scikit-learn is used.

### 9. Model Training
Model is trained using training dataset.

### 10. Model Parameters
- Intercept
- Coefficient (slope)

### 11. Predictions
Model predicts salary values for test data.

### 12. Evaluation Metrics
Model performance is evaluated using:
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

### 13. New Prediction
Example prediction for **12 years of experience**.

---

## Results

- The model shows a strong linear relationship between experience and salary.
- R² Score indicates how well the model explains the variance in data.

---

## How to Run

```bash
# Install dependencies
pip install pandas numpy matplotlib scikit-learn

# Run the notebook
jupyter notebook Linear_Regression_1.ipynb