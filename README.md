##### Use https://nbviewer.org to upload the file in case of errors
---

# Diamond Price Forecast
This notebook uses data from a diamond dataset available on Kaggle to build a regression model capable of predicting the price of a diamond based on its characteristics.

## Dataset
The dataset used is Ulrik Thyge Pedersen's "Diamonds", which contains information on 53940 diamonds, including characteristics such as carat weight, color, clarity, depth and chart, as well as the price of each diamond in dollars. The specific dataset used in this project can be found at https://www.kaggle.com/datasets/ulrikthygepedersen/diamonds

## Data analysis
Before creating the forecast model, a quick exploratory analysis of the data was performed, with the aim of understanding the distribution of characteristics and identifying possible correlations between them and the price of diamonds. This analysis was done using Python libraries such as pandas, seaborn and matplotlib.

## Data Pre-processing
Before creating the model, the data was pre-processed to remove missing values, transform categorical data into numeric data, and standardize feature scales. This was done using the scikit-learn library.

## Regression Model
To create the regression model, several algorithms were tested, including linear regression, decision tree and polynomial regression. The final model chosen was the linear regression, which presented the best performance in terms of evaluation metrics such as the mean absolute error and the coefficient of determination.

## Conclusion
This notebook demonstrates how you can use data analysis and machine learning techniques to predict diamond prices based on their characteristics. The linear regression model developed in this notebook can be used to help buyers and sellers determine the fair price of a diamond based on its characteristics.

## Contribution

Contributions are welcome! If you find any bugs or have any suggestions for improvement, please open an issue in the repository or submit a pull request.
a pull request.
