# SC1015_Project_2023 A133_Team 8

A. Brief Introduction to Our Project

According to the World Health Organization, global obesity rates have doubled since 1980, leading health professionals to label obesity as a growing epidemic. Despite performing better than the US and European countries, HealthHub reported that Singapore's obesity rate has been on the rise in recent years. 30% of Singaporeans are considered overweight and 10% are categorized as obese.  
Therefore, our group has decided to investigate further on the factors that can lead to obesity.
We used a dataset published in 2019 that estimates the obesity levels of individuals in Mexico, Peru and Colombia with diverse eating habits and physical condition. The dataset comprises of 17 variables, both numerical and categorial, with 2111 records. 

B. ML Techniques Used for Our Project

a. Logistic Regression
Logistic regression is a powerful tool that helps us understand the relationship between a binary outcome and one or more independent variables. It's used to predict the probability of a "yes" or "no" outcome, based on the values of the independent variables. For our project, firstly we implemented Logistic Regression that focuses on Eating Habits only:

Steps taken:

    1. Extracting the variables related to Eating Habits to a new dataframe
    
    2. Changing categorical data into dummies
    
    3. Splitting data into Predictor and Response Variables
    
    4. Normalise the range of independent variables by Feature Scaling
    
    5. Splitting dataset into Train and Test Sets
    
    6. Train the Logistic Regression and make preditions on the testing set

    7. Print the confusion matrix and classification report

    8. Print the accuracy score

Subsequently, we then implemented Logistic Regression to All variables, by carrying out steps 1-8 using the original dataset. 
    
For Eating Habits only, we obtained an accuracy score of 0.46687 while for All variables we obtained an accuracy score of 0.85647.



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

Subsequently, we then implemented kNN Classification to All variables, by carrying out steps 2-8 with       using the original dataset. 
    
For Eating Habits only, we obtained an accuracy score of 0.6025 at k = 3 while for All variables we         obtained an accuracy score of 0.8565 at k = 1.


C. Insights and Conclusion from Our Project

- Diet alone is not enough to predict an individual's obesity levels. Obesity is caused by numerous other factors, such as lifestyle and physical conditions, and hence having a healthy diet alone is not sufficient.


D. Individual Contributions

Nelly: Logistic Regression and Data Cleaning

Wisnu: kNN Classification and Conclusion


E. References

Bhattacharjee, S. (2019, August 7). How KNN algorithm works, when do we use KNN and how do we choose the factor K in Knn? LinkedIn. Retrieved April 21, 2023, from https://www.linkedin.com/pulse/how-knn-algorithm-works-when-do-we-use-choose-factor-k-bhattacharjee/ 

Banerjee, P. (2020, March 13). KNN classifier tutorial. Kaggle. Retrieved April 21, 2023, from https://www.kaggle.com/code/prashant111/knn-classifier-tutorial#9.-Declare-feature-vector-and-target-variable- 

FAO, & PAHO. (2016). Panorama of food and nutrition security in Latin America and the Caribbean 2016. Food and Agriculture Organization of the United Nations. https://doi.org/10.4060/ca8535en

Foo, L. H. (2017). Dietary intake and food sources of Singaporean adults. Asia Pacific Journal of Clinical Nutrition, 26(1), 96-103. https://doi.org/10.6133/apjcn.042016.06

HealthHub. (2022, November 15). Obesity in Singapore: It's not a small world. HealthHub. Retrieved April 17, 2023, from https://www.healthhub.sg/live-healthy/764/its-not-a-small-world-after-all 

Health Promotion Board. (2021). National Health Survey 2021. Retrieved April 17, 2023, from https://www.healthhub.sg/live-healthy/647/national-health-survey-2021

Institute of Mental Health. (2016). Study finds obesity linked to depression, anxiety and poor quality of life. Retrieved April 17, 2023, from https://www.imh.com.sg/news/study-finds-obesity-linked-to-depression-anxiety-and-poor-quality-of-life/

Ministry of Health. (2019). Disease Burden in Singapore. Retrieved April 17, 2023, from https://www.moh.gov.sg/resources-statistics/singapore-health-facts/disease-burden-in-singapore

Palechor, F. M., & Manotas, A. de. (2019). Dataset for estimation of obesity levels based on eating habits and physical condition in individuals from Colombia, Peru and Mexico. Data in Brief, 25, 104344. https://doi.org/10.1016/j.dib.2019.104344 

Tan, C. E., Ma, S., Wai, D., Chew, S. K., & Tai, E. S. (2004). Can we apply the National Cholesterol Education Program Adult Treatment Panel definition of the metabolic syndrome to Asians? Diabetes Care, 27(5), 1182–1186. doi:10.2337/diacare.27.5.1182





