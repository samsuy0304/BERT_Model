# Supervised Learning for Cost-Effective Solution | Linear Regression Modeling

## Overview
Developed a linear regression model to estimate the conversion factor between measurements obtained from equipment used in Bit Error Rate testing of differential pair cables. The goal was to asses the accuracy of a newer cost effective equipment and establish a relationship between the measurements compared to an older more accurate equipment.

## Methods

### Linear Regression Modeling
- Chose linear regression as the modeling technique due to its interpretability and suitability for capturing linear relationships.
- Trained a linear regression model using measurements from yellow boards as features and measurements from L boards as the target variable.
- Evaluated the model's performance using metrics such as mean squared error (MSE), root mean squared error (RMSE), and R-squared.

### Visualization
- Plotted scatter plots to visualize the relationship between actual and predicted measurements from L boards for both training and testing data.
- Examined coefficients of the linear regression model to understand the conversion factor or relationship between measurements from yellow and L boards.

## Results
- Achieved a mean squared error (MSE) of 4690.84 and a root mean squared error (RMSE) of 68.49.
- The R-squared value of 0.7175 indicates that approximately 71.75% of the variance in measurements from L boards is explained by the linear regression model.
- Scatter plots visually demonstrate the model's performance in predicting measurements from L boards based on measurements from yellow boards.

## Conclusion
- The linear regression model provides a reliable estimate of the conversion factor between measurements obtained from yellow and L boards.
- This conversion factor can be used to obtain accurate measurements using cost-effective L boards, thus reducing testing costs without sacrificing accuracy.
