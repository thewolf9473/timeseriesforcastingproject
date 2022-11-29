## TIme Series Forcasting

## Objective

- Predict values for Para-9 to Para-13 for tenth year of each road section.
- Create graphs for comparing actual values with predicted values for Para-9 to Para-13.

## Input File (DATASET.xlsx)

- Original dataset contains 1009 rows and 15 columns.
- First column denotes each road section.
- Second column denotes the year no. for which parameter values are recorded.
- Columns 3 to 15 represents values for parameters 1 to 13.

## Model Used

- XGBoost Regressor
  XGBoost is a powerful approach for building supervised regression models. The validity of this statement can be inferred by knowing about its (XGBoost) objective function and base learners. The objective function contains loss function and a regularization term.

## Metric Used

- RMSE: Root Mean Square Error
The RMSE estimates the deviation of the actual y-values from the regression line. Another way to say this is that it estimates the standard deviation of the y-values in a thin vertical rectangle. where ei = yi - yi^. The RMSE can be computed more simply as RMSE = SDy √(1 - r2).

## Result

Final RMSE = 9.024
