DATABYTE-TASK2 /topic-4
Training and Deploying a ML model
Problem Statement: Training and Deploying a ML model with the "Iris dataset".
My approach: 
a):data_prep: 
             1-Here i did basic  data processing i.e. loading dataset, hide warning in results, train_test_split of "iris dataset" and LabelEncoding for                    categorical target column (i.e. "species") 
             2-I used "iris data"  to deploy my machine learning models. .
             3-Given data has target variable as "categorical". i use label encoding to encode those categorical values.
             4-Now,i split given data in test(20%) and train(80%).
             5-After data process we get x_train,x_test,y_train,y_test
b):model_knn:
             1-To deploy "iris dataset" i use  knn(k-nearest neighbour classifier).
             2-now fit model on x_train and y_train.
             3-we can use x_test to check accuracy of model_knn with y_test.
             4-model_knn(sepal_length,sepal_width,petal_length,petal_width) will predict corressponding type of species i.e. "virginica"
c): model_LR:
             1-To deploy "iris dataset" i use logistic regression (LR)  model.
             2-i also use ensemble  method (AdaBoostClassifier) to boost LR  model via ensembling.
             3- i use n_estimators =500 and learning_rate is equal to one.
             4- now i fit this  model with  x_train and y_train.
             5-model_LR(sepal_length,sepal_width,petal_length,petal_width) will predict corressponding type of species i.e. "virginica",
               where 0:setosa
                     1: versicolor
                     2: virginica.
