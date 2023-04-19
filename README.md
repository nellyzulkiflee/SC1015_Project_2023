# SC1015_Project_2023 A133_Team 8

#TRY TO KEEP IT A 3-5 MINUTE READ!!!

A. Brief Introduction to Our Project

According to the World Health Organization, global obesity rates have doubled since 1980, leading health professionals to label obesity as a growing epidemic. Despite performing better than the US and European countries, HealthHub reported that Singapore's obesity rate has been on the rise in recent years. 30% of Singaporeans are considered overweight and 10% are categorized as obese.  
Therefore, our group has decided to investigate further on the factors that can lead to obesity.
We used a dataset published in 2019 that estimates the obesity levels of individuals in Mexico, Peru and Colombia with diverse eating habits and physical condition. The dataset comprises of 17 variables, both numerical and categorial, with 2111 records. 

B. ML Techniques Used for Our Project

a. Logistic Regression



b. kNN Classification

k-Nearest Neighbors (kNN) classification is a simple and intuitive machine learning algorithm used to analyse data because it is effective at identifying patterns and making predictions based on those patterns. The algorithm works by finding the k data points in the training dataset that are closest to a given data point in the test dataset, and then classifying the test data point based on the majority class of those k neighbors. For our project, firstly, we implemented kNN Classification that focuses on Eating Habits only:

Steps taken:
    1. Extracting the variables related to Eating Habits to a new dataframe
    2. Changing categorical data into dummies
    3. Splitting data into Predictor and Response Variables
    4. Normalise the range of independent variables by Feature Scaling
    5. Splitting dataset into Train and Test Sets
    6. Train the kNN Classifier and make preditions on the testing set
    7. Repeat the step 6 for different values of k, from 1 to 30
    8. Print the k-value with the highest accuracy score

Subsequently, we then implemented kNN Classification to All variables, by carrying out steps 2-8 with using the original dataset. 
    
For Eating Habits only, we obtained an accuracy score of 0.6025 at k = 3 while for All variables we obtained an accuracy score of 0.8565 at k = 1.


C. Insights and Conclusion from Our Project


D. Individual Contributions


E. References
