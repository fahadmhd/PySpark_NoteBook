# PySpark 
PySpark is the Python API for Apache Spark, an open source, distributed computing framework and set of libraries for real-time, large-scale data processing.

In this notebook, I create DataFrame and work on it.  A DataFrame is a two-dimensional labeled data structure with columns of potentially different types. 
Finally I obtain performance matrics and conlcude some results

### Performance Metrics [ see values obtained are: (0.41219200625784047, 4.768627321582243, 45.215286217550926)]
Based on the performance metrics obtained:

### R² Score: 0.412
- This indicates that approximately 53.4% of the variance in the tips can be explained by the model. This suggests a moderate level of predictive power.
### Mean Absolute Error (MAE): 4.768
- On average, the model's predictions deviate from the actual tips by around 4.24 units. This gives an idea of the typical magnitude of errors in the predictions.

### Mean Squared Error (MSE): 45.21 
 - This value indicates the average squared difference between the predicted and actual tips. A lower MSE generally indicates a better fit of the model to the data.

### Conclusion
The model demonstrates a moderate ability to predict tips, explaining about 41.2% of the variance. However, the mean absolute error of approximately 4.76 suggests there's room for improvement in the accuracy of the predictions. Further tuning and feature engineering might be necessary to enhance the model's performance.
