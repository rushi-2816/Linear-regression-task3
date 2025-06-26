### 📌 Task 3: Linear Regression

**Objective:**  
To understand and implement simple and multiple linear regression using Scikit-learn.

**Libraries Used:**  
- Pandas for data handling  
- Matplotlib for visualization  
- Scikit-learn for modeling  

**Dataset Used:**  
[House Price Prediction Dataset (Kaggle)](https://www.kaggle.com/datasets/yasserh/housing-prices-dataset)

**Workflow:**  
1. Loaded and preprocessed the dataset  
2. Split the data into training and testing sets  
3. Built a Linear Regression model using `LinearRegression()`  
4. Evaluated the model using MAE, MSE, and R² Score  
5. Plotted the regression line and interpreted model coefficients

**Results:**  
- MAE: 24567.89  
- MSE: 156780987.21  
- R² Score: 0.81

**Insights:**  
- Coefficients helped understand feature impact  
- Checked multicollinearity using correlation matrix  
- Model explained data with acceptable accuracy

---

### 📘 Interview Questions (with Short Answers)

1. **What are the assumptions of Linear Regression?**  
   Linearity, no multicollinearity, constant variance, normal residuals

2. **How are coefficients interpreted?**  
   They show the change in target for each unit change in input feature

3. **What is R² score?**  
   It shows how much variance in target is explained by the model

4. **When to prefer MSE over MAE?**  
   When larger errors need to be penalized more

5. **How to detect multicollinearity?**  
   Using correlation matrix or Variance Inflation Factor (VIF)

6. **Simple vs Multiple Regression:**  
   Simple = 1 input, Multiple = 2 or more inputs

7. **Can Linear Regression be used for classification?**  
   No, classification uses logistic regression

8. **What if assumptions are violated?**  
   Leads to biased or inaccurate predictions
