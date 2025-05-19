# GA-Optimized Regression Models
Regression Models Enhanced with Genetic Algorithm Optimization(Machine learning)

This project demonstrates how **Genetic Algorithms (GA)** can be used to improve the performance of various **regression models** by tuning their coefficients and hyperparameters. The analysis is based on a synthetic dataset of student study hours and exam scores.

Dataset

The dataset contains 1,000 samples with:

* `Hours`: Number of hours studied
* `Scores`: Exam score (out of 100)

Models Used

* Linear Regression
* Polynomial Regression (degree selected via GA)
* Ridge Regression
* Lasso Regression
* Decision Tree Regressor
* Random Forest Regressor

Role of Genetic Algorithm

The GA was used to:

* Optimize model coefficients (w, b)
* Dynamically select the best polynomial degree (1 to 6)
* Tune hyperparameters like alpha (Ridge/Lasso), depth (Decision Tree), and number of estimators (Random Forest)

Evaluation Metrics

* MAE (Mean Absolute Error)
* MSE (Mean Squared Error)
* RMSE (Root Mean Squared Error)
* R² Score (Coefficient of Determination)

 Key Results

* Polynomial Regression (degree 3) had the best R² before GA.
* After GA, Random Forest gave the best accuracy.
* GA-tuned models performed better overall in terms of RMSE and R².
* No overfitting detected: training and test scores were close.

 Files

* `task1.ipynb`: Main notebook with all code and analysis
* `task1.pdf`: Project report
* `expanded_data.xlsx`: Synthetic dataset used

 Conclusion

Genetic Algorithms can significantly improve the accuracy of regression models by intelligently tuning their parameters. Random Forest and GA-optimized Lasso Regression achieved the best performance in this project.

