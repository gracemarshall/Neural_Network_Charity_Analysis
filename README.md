# Neural_Network_Analysis
![Neural_NWimage.png](https://github.com/gracemarshall/Neural_Network_Charity_Analysis/blob/main/images/Neural_NWimage.png)

## Project Overview
The purpose of the Neural_Network_Analysis is to use unsupervised machine learning neural networks, features in the provided dataset to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.The following deiliverables will be produced.

* Preprocessing Data for a Neural Network Model
* Compile, Train, and Evaluate the Model
* Optimize the Model
* A Written Report on the Neural Network Model (README.md)

##  Results
#### Data Processing
###### The following pre-processing steps have been performed:
1. The EIN and NAME columns have been dropped 
2. The columns with more than 10 unique values have been grouped together 
3. The categorical variables have been encoded using one-hot encoding 
4. The preprocessed data is split into features and target arrays 
5. The preprocessed data is split into training and testing datasets 
6. The numerical values have been standardized using the StandardScaler() module 

![Application_df.png](https://github.com/gracemarshall/Neural_Network_Charity_Analysis/blob/main/images/Del1.png)

#### Compile, Train, and Evaluate the Model

![1st_attemp.png](https://github.com/gracemarshall/Neural_Network_Charity_Analysis/blob/main/images/1st_attemp.png)

![2nd_attemp.png](https://github.com/gracemarshall/Neural_Network_Charity_Analysis/blob/main/images/2nd_attemp.png)

![3rd_attemp.png](https://github.com/gracemarshall/Neural_Network_Charity_Analysis/blob/main/images/3rd_attemp.png)

![Accuracy1.png](https://github.com/gracemarshall/Neural_Network_Charity_Analysis/blob/main/images/Accuracy1.png)

![Accuracy2.png](https://github.com/gracemarshall/Neural_Network_Charity_Analysis/blob/main/images/Accuracy2.png)

![Accuracy3.png](https://github.com/gracemarshall/Neural_Network_Charity_Analysis/blob/main/images/Accuracy3.png)

### Data Visualization
![Classification_plot.png](https://github.com/gracemarshall/Neural_Network_Charity_Analysis/blob/main/images/counts_plot.png)

![application_type.png](https://github.com/gracemarshall/Neural_Network_Charity_Analysis/blob/main/images/counts_plot_application_type.png)

## Summary
After three attempts, the highest model accuracy is 50.8% which is far from the 75% that I was hoping for. I added a fourth hidden layer on the 3rd attempt without success of getting closer to 75%. Possible reasons for the low accuracy could be the small size of the data set because changing the features didn't impact the accuracy rate. 
