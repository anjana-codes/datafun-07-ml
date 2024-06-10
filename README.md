# datafun-07-ml

Title: Specification for Project 7 Machine Learning
	
 Anjana Dhakal, 
 06/07/2024	

 Objectives: This project 7 will use Supervised Machine learning to create a linear regression model for a data set and then use that model to make predictions.

## Create GitHub Repository
```
 GitHub Repository: datafun-07-ml
 Documentation: README.md
```

## Clone to VS Code 
```
git clone site_URL
```

## Adding files 

- Include a .gitignore file to exclude the .venv file from the rest of the Python environment.
- Create a .venv to act as the virtual environment.
- Add a requirements.txt file to hold the required project modules.
-

## Create Project Virtual Environment
```
 py -m venv .venv
.\.venv\Scripts\activate
```

## Install all Required Packages
```
 py -m pip install jupyterlab pandas pyarrow matplotlib seaborn
 py -m pip freeze > requirements.txt
```

## Git add and commit
```
git add .
git commit -m "start a project"
git push origin main
```

## APPLY: Implement 10.16 and 15.4

- Part 1: Chart a Straight Line

The points along any straight line (in two dimensions) can be calculated with the equation:
y = mx + b
where
m is the line’s slope,
b is the line’s intercept with the y-axis (at x = 0),
x is the independent variable, and
y is the dependent variable.

In simple linear regression, y is the predicted value for a given x.

- Part 2: Predict Avg High Temp in NYC in January

Use Seaborn’s regplot function to plot each data point with the dates on the x-axis and the temperatures on the y-axis. The regplot function creates the scatter plot.

- Part 3: Predict Avg High Temp in NYC in January
