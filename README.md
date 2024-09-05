# PySpark 
PySpark is the Python API for Apache Spark, an open source, distributed computing framework and set of libraries for real-time, large-scale data processing.

In this notebook, I created DataFrame and work on it.  A DataFrame is a two-dimensional labeled data structure with columns of potentially different types. 
Finally I obtained performance matrics and conlcude some results

### Performance Metrics [ see values obtained are: (0.412, 4.76, 45.21)]
Based on the performance metrics obtained:

### R² Score (Coefficient of determination):  (value obtained in example 0.412)
- R-squared (R2) is defined as a number that tells you how well the independent variable(s) in a statistical model explain the variation in the dependent variable. It ranges from 0 to 1, where 1 indicates a perfect fit of the model to the data.
- This indicates that approximately 41.2%  of the variance in the tips can be explained by the model. This suggests a moderate level of predictive power.


### Mean Absolute Error (MAE):(value obtained in example 4.768)
- Mean Absolute Error (MAE) is a measure of the average size of the mistakes in a collection of predictions, without taking their direction into account. It is measured as the average absolute difference between the predicted values and the actual values and is used to assess the effectiveness of a regression model.
-  On average, the model's predictions deviate from the actual tips by around  4.76 units. This gives an idea of the typical magnitude of errors in the predictions.

### Mean Squared Error (MSE): (value obtained in example 45.21 )
 - Mean squared error (MSE) measures error in statistical models by using the average squared difference between observed and predicted values.
 - This value indicates the average squared difference between the predicted and actual tips. A lower MSE generally indicates a better fit of the model to the data.

### Conclusion
The model demonstrates a moderate ability to predict tips, explaining about 41.2% of the variance. However, the mean absolute error of approximately 4.76 suggests there's room for improvement in the accuracy of the predictions. Further tuning and feature engineering might be necessary to enhance the model's performance.
