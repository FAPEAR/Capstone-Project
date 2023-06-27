# Capstone-Project
The workflow of this project consists of several stages, it starts with the clear definition of the problem and the collection of relevant data, then the data is explored and pre-processed, followed by the selection and training of the appropriate model. The performance of the model is evaluated, adjustments are made if necessary, and it is validated using techniques such as cross-validation.

In this paper, we will focus on addressing the challenge of customer retention through data analysis and the development of predictive models. We will explore different techniques and approaches, evaluate their effectiveness, and discuss their application in a business context. The ultimate goal is to provide companies with the necessary tools to proactively predict and address customer churn, thus improving their ability to retain their customers and maximize their business success.

# Project Motivation
Many companies have adopted business models based on monthly or annual subscriptions instead of one-time fees. However, this transition has introduced the challenge of retaining customers and avoiding the loss of subscriptions. The ability to predict and detect customer churn before it occurs has become critical for businesses that want to keep their customers paying.

To overcome these challenges, Big Data tools are used, such as Apache Spark, which has become a popular and trusted choice in the field of large-scale data processing and analysis. Apache Spark is known for its ability to handle large volumes of data and its exceptional processing speed in distributed environments.

# Libraries used:
- pySpark
- Pandas
- Seaborn
- Numpy
- Matplotlib

# File Description
We work with only a 128MB slice of the original data set. This will allow us to perform more efficient and manageable data analysis and exploration. The data set includes information such as user id, session id, subscription level, action performed by the user such as downgrade, upgrade, listen to next file, invite a friend, among others, timestamp, user’s gender, location and name, among others. The relationship of these variables with the problem to be solved is key because through them it will be possible to determine the behavior of the users in ‘Sparkify’.

- user_dataset_definitive.CSV: Copied Data defined and extracted for the machine learning stage in CSV
- mini_sparkify_event_data.json: only 128 MB portion of the original data set (It is not related in this repository but it is in the Udacity workspace)
- Sparkify.ipynb: The main coding file in jupyter notebook format developed in Udacity workspace, where you can identify the step by step of the CRISP methodology applied in this project.
  
# Summary of Analysis Results
To determine the best machine learning model, the results in the test dataset are generally taken into account. The primary reason is to test how each model performs on previously unseen data, providing a more realistic measure of its performance in real-world situations.

The training data set (train) is used to fit the models and search for the best combination of hyperparameters. However, performance on the training set does not always reflect performance on new data. A model that fits the training data very well may be overfitting, meaning that it has overfitted the specifics of the training data and does not generalize well to new data.

The ones highlighted in green in the table attached are the best results in Accuracy, Precision, Recall and F1-score for the test data set and the ones highlighted in blue are the best for the train data set, taking into account all of the above and the results obtained, the model with the best measurements is the Decision Tree Classifier.

# Acknowledgements
https://stackoverflow.com/questions/tagged/capstone?tab=Votes

https://www.kaggle.com/discussions/general/185307

Please refer to: https://medium.com/@fabian.perez.arevalo/dont-let-the-music-stop-at-sparkify-ff51dd9db3e5

