# Linear Regression – Football Player Analysis

## Project Overview

This project uses **Linear Regression** to analyze the relationship between a football player's **Finishing** and **Attacking** statistics.

The goal is to build a simple machine learning model that can predict a player's **Attacking** rating based on their **Finishing** rating.

## Technologies Used

* Python
* Pandas
* Scikit-learn
* Matplotlib
* Jupyter Notebook

## Project Workflow

1. Load the football player dataset.
2. Select `Finishing` as the independent variable (X).
3. Select `Attacking` as the dependent variable (y).
4. Split the data into training and testing sets.
5. Train a Linear Regression model.
6. Predict Attacking ratings using the test data.
7. Evaluate the model using Mean Squared Error (MSE).
8. Visualize the actual data and regression line.
9. Allow users to enter a player's Finishing rating and predict their Attacking rating.

## Model

The model follows the basic Linear Regression equation:

**Attacking = Coefficient × Finishing + Intercept**

## Visualization

The project includes a scatter plot showing the actual player data and the Linear Regression line.

* **Yellow points:** Actual player data
* **Red line:** Regression line

## Example

The model can take a player's Finishing rating as input and provide a predicted Attacking rating.

```text
Enter the finishing stat of the player: 85

Predicted Attacking Stat of the player: 86.2
```

## Purpose

This project demonstrates how **machine learning and statistical analysis** can be applied to football player data to identify relationships between player attributes and make simple predictions.

## Future Improvements

* Add more player attributes such as Pace, Passing, Dribbling, and Shooting.
* Use Multiple Linear Regression.
* Compare different machine learning models.
* Evaluate the model using R², MAE, and RMSE.
* Build a football player prediction dashboard using Power BI.
