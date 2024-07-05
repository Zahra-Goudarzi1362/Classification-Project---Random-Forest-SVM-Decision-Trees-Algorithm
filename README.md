# Classification Project - Random Forest, SVM, Decision Trees Algorithm=Prediction of  Mobile Price 
Firstly import libraries
Import Datasets
Starting Preprocessing: 
# In This project we have 2 dataset(train & test)
# which Test dataset dont have taget value(y)
# we want to use train test to find y for test data
# for this, we should compare describe of both to check the range of changes of theri variables
# that shoub be the same ..like min,max,average
# so chk feature by featue all of items in describe
Then checking Missing values, There were not any misisng 
Drawing Scatter plots of all features with our target(Price range) separately
All scatter did not give me nay special information except "ram"
# we can check it by correlation also.
we can also check joint plot to get any useful info
we drawed some piplot to check data and apply some changes on some features like: column  ['sc_w']>=2] or df['px_height']!=0.. # it shoud be apply on DF_test also 
Then I started to modeling and chk accuracy of 3 algorithm: Decision Trees, RandomForest and SVM
SVM algorithm in this project had better score and accuracy. 
