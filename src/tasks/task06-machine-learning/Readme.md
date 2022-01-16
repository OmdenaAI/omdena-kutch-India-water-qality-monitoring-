Task 6 : Machine Learning 

AIM : This task revolved around data pre-processing, exploratory analysis, preparation of training and testing data for best suitable classification model. 

Data Pre-processing  and exploration 

1. First we concatenated the individual data files. 
2. Null Values :- nearly 60% of the data had null values so we decided to drop them.
3. Outliers :- Dissolved oxygen showed highest data points outside of the inter-quartile range however seeing its percentage and type of spread, we decided to retain them.
4. No significant correlation between parameters were found except one relation between Dissolved Organic matter and Suspended Matter.  

Training and Testing Data Preparation 

1. Due to the lack of in-situ data in India for training, we applied the research based thresholds for labelling the records into ‘good’, ‘poor’ and ‘Needs treatment’ classes and generate our own training and testing data.
2. We normalised the data using Min-Max scalar

About the Model 

We have used SMOTE to handle the imbalance dataset 
