# Spark_ML

Use PySpark on Databrick platform to run machine learning classification on the adult dataset [1]. The adult data set record individual's annual income along with various factors, such as age, education, marital status, work class etc. In this project we utilize PySpark dataframe, SQL, ML, and MLlib to build classifiers to train and predict individual's annual income. 


## About the code  

1. Load the adult data set into a Spark table. 
2. Explore the table using Spark SQL and dataframe API
3. Aggregate some data and convert it into pandas dataframe to visualize the data 
4. Create ML pipeline with StringIndexer, OneHotEncoder, and VectorAssembler. Transform the data. 
5. Split the data into training and testing data sets.  
6. Train logistic regression and gradient boost classifier to predict the income. 
7. Hyperparameter tuning using cross validation 
8. Review the feature importance of the gradient boost classifier 
9. Train a random forest classifier and review its feature importance 



## References 
[1] http://archive.ics.uci.edu/ml/datasets/adult <br>

