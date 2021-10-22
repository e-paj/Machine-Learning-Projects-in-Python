# What I have done so far:

September 30, 2021:
- Started writing the report.
- Tomorrow start on the data analysis part!

September 29, 2021:
- I built a predictive system where I took an input data and used my model to check if the person has the disease or not.
- In order to this, I have to change the input_data, which I took from the original dataset, into a numpy array.
- Then I had to reshape the the numpy array otherwise the model expects 156 entries (it would not work).
- Then I standardized the reshaped numpy array and used the model to predict whether or not it has Parkinson's.
- Since I already know whether or not the person has the disease, it is easy to validate the prediction.
 
September 28, 2021:
- I initially took the information of the data to see if there are any missing values.
- Then I took the statistical measures of each variable. 
- Then we group the data by status and took the mean of each variable. 
- I split the data variables into features(X) and Target(Y).
- Split X and Y into training and Test data.
- I standardized the data to a common range.
- Then made a SVM model.
- I evaluated the accuracy score of my models.
