Employee Salary Prediction using Linear Regression
Project Overview
This project uses Simple Linear Regression to predict an employee's
salary based on their years of work experience. The model is built with
Python and Scikit-learn in a Jupyter Notebook or Google Colab.
Dataset
The notebook loads the Salary_Data.csv dataset directly from this URL:

https://raw.githubusercontent.com/mk-gurucharan/Regression/master/Salary_Data.csv
- Input feature (X): YearsExperience
- Target variable (y): Salary
Technologies and Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
Project Workflow
1. Import the required libraries.
2. Load the salary dataset.
3. Explore the dataset using its shape, columns, information, and
   statistical summary.
4. Check for missing values.
5. Visualize the relationship between years of experience and salary
   using a scatter plot.
6. Separate the input feature (YearsExperience) and target
   (Salary).
7. Split the data into training and testing sets using an 80:20 ratio
   (random_state=42).
8. Train a LinearRegression model.
9. Predict salaries for the test data.
10. Plot the regression line with the actual data.
11. Evaluate the model using MAE, MSE, RMSE, and R² score.
12. Predict salaries for employees with 2, 4, 6, 8, and 10 years of
    experience.
How to Run
Option 1: Google Colab
1. Open Google Colab.
2. Upload RCA_A1.ipynb.
3. Run the notebook cells in order.
Option 2: Jupyter Notebook
1. Install Python.
2. Install the required libraries:
   pip install pandas numpy matplotlib scikit-learn jupyter
3. Open a terminal in the folder containing the notebook.
4. Start Jupyter:
   jupyter notebook
5. Open RCA_A1.ipynb and run the cells in order.
Note: An internet connection is required to download the dataset
from the URL used in the notebook.
Model Evaluation
The notebook calculates these regression metrics on the test data:
- MAE (Mean Absolute Error): Average absolute difference between
  actual and predicted salaries.
- MSE (Mean Squared Error): Average squared prediction error.
- RMSE (Root Mean Squared Error): Square root of MSE.
- R² Score: Indicates how well the model explains the variation in
  salary.
The actual metric values are displayed when the notebook is executed.
Prediction Example
After training, the notebook predicts salaries for experience values of
2, 4, 6, 8, and 10 years.
Project File
- RCA_A1.ipynb --- notebook containing the complete data analysis,
  model training, evaluation, visualizations, and predictions.
  
  👩‍💻 12. GitHub Submission

*Faculty GitHub ID:* [complexiota](https://github.com/complexiota)

*Student GitHub Repository:* [LinearRegression – AD3363](https://github.com/vaishnavisachinyadav-ui/LinearRegression-AD3363)
