# Titanic_Logistic_model
# This is a classification model built to predict the people who survived or deceased out of the total passengers on board. The data set is acquired from kaggle. The data set is partially clean, however there is certain amount of data cleaning that I had to implenent in order to only retain numeric values on which the model can train and there make predictions on the passengers that did survive. 
# The exploratory data analysis was carried out forst to understand the dataset better and find correlations between the different columns of the dataset. 
# The second step was the clean the data, I found quiet a few age data missing, hence I visualised the differnt classes of tickets bought with age as the parameter. Once i creawd this boxplot, I was able to view the average age for each of the 3 class of tickets. I wrote a function to fill in these aberage values into the missing data. 
# I dropped a few unnecessary pr non numeric columns which would interfere with training the model.
# I split the data into train and test and fit the train data into the model and then predicted the results for test data. 
# I then compared the predicted and actual data and formed a classification report. 
