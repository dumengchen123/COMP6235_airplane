This project revolves around modeling and forecasting flight delays for airlines. 

Data is collected from Miami Airport and Miami weather sources, encompassing weather information and flight data for the entire year of 2023.

A training dataset is constructed with a specific data building criterion: if an airline exceeds 50 flights on a given day, it is labeled as a negative sample; otherwise, it is considered a positive sample. 

This approach forms the basis of creating a supervised learning dataset. The dataset includes features such as Maximum, Minimum, Average, Departure, and Precipitation, in addition to a label.

We employ machine learning algorithms, including Logistic Regression (LR), Support Vector Machine (SVM), Random Forest, and LightGBM, for training and prediction. 

Below is the result：
Logistic Regression - Accuracy: 0.8032786885245902 F1: 0.8909090909090909

Support Vector Machine - Accuracy: 0.8032786885245902 F1 : 0.8909090909090909

Random Forest - Accuracy: 0.8524590163934426 F1 : 0.9108910891089108

LightGBM - Accuracy: 0.8360655737704918 F1 : 0.8979591836734694
