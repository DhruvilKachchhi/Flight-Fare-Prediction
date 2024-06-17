# Flight-Fare-Prediction

This repository contains a study on predicting flight ticket prices using machine learning models.

### Dataset
The dataset used in this study contains 10683 records for training and 2671 records for testing. The dataset includes features such as date, time, airline, source, destination, route, departure time, arrival time, duration, total stops, and additional information.

### Preprocessing
The preprocessing steps involved converting date and time features into Day, Month, and Year. Categorical features were converted into one-hot encoding.

### Feature Engineering
New features were created, and unnecessary columns were dropped after encoding. Correlation between features was also checked.

### Model Building
Several regression models were tested, including Linear Regression, Polynomial Regression, Ridge Regression, Decision Tree Regression, Gradient Boosting Regression, XGBoost Regression, and Random Forest Regression.

### Model Performance
The XGBoost Regression model performed the best, with an MAE of 1132.43 and an R2 score of 0.8374.

### Key Findings
Duration and Total_Stops are significant predictors of flight prices. Airline, Source, and Destination categorical variables also contribute substantially.

### Conclusion
The analysis demonstrates that flight ticket prices can be effectively predicted using machine learning models. The XGBoost Regression model performed the best.
