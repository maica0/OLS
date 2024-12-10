# OLS

## Ordinary Least Squares (OLS) Regression Training

This project demonstrates the implementation of Ordinary Least Squares (OLS) regression to analyse relationships between variables and predict outcomes.

### Techniques Used
1. **Data Preprocessing**:
   - **Outlier Handling**: Applied capping to limit the impact of extreme values, ensuring robust coefficient estimation.
   - **Normalisation**: Input features were normalised to improve model performance and convergence during training.
   - **Feature Engineering**: Explored feature transformations to better capture linear relationships.

2. **Model Development**:
   - Implemented an OLS regression model to estimate coefficients of the predictor variables.
   - Assessed multicollinearity using Variance Inflation Factor (VIF) to ensure predictors were independent.

3. **Model Evaluation**:
   - **Goodness-of-Fit**: R-squared and Adjusted R-squared were calculated to measure the model's explanatory power.
   - **Residual Diagnostics**:
     - Residual plots were examined to validate linearity and homoscedasticity assumptions.
     - Statistical tests confirmed the absence of significant autocorrelation or non-linearity.

### Results
- The OLS regression model provided clear insights into feature significance and their impact on the target variable.
- Residual analysis confirmed that the model adhered to the key assumptions of linear regression.
- **Limitations**: Certain features displayed limited explanatory power, indicating potential for incorporating additional predictors or exploring non-linear approaches in future work.
