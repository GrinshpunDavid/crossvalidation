## Project description:
Develop a prototype of a machine learning model for Zyfra. The model should predict the amount of gold recovered from gold ore. 

### Data description:
Extraction and purification factory data. 

### Goal:
Develop a model for predicting the Au concentration after purification with sMAPE < 10.

### Steps performed:
- Exploratory Data Analysis
- Calculate target
- Concentration analysis
- Filling missing data using KNNImputer
- Crossvalidation on train data
- Testing different models
- hyperparameter tuning

### Results:
- sMAPE score for best RandomForestRegressor model on test datasets: 8.79
- The sanity score is 9.4, our model preform slightly better than the target mean.
